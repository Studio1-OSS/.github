<div align="center">

# Studio1 OSS

### Open-source tools from the [Studio1](https://studio1hq.com) team

**We help devtool, SaaS, AI and open-source teams grow with technical content and developer experience work. When a project needs a tool that doesn't exist yet, we build it and open-source it here.**

[Website](https://studio1hq.com) · [Case studies](https://studio1hq.com/case-studies) · [Blog](https://studio1hq.com/blog) · [Contact](mailto:contact@studio1hq.com)

</div>

---

## What we build

Everything here comes out of real developer-facing work: tutorials, docs, DX audits, launch support and DevRel programs with 35+ devtool and SaaS teams. Our projects cluster around three areas:

- **AI agents on open models.** Run the agents developers already use, and new kinds of agents, on open models.
- **LLM evaluation.** Transparent, evidence-first ways to compare models.
- **Developer experience.** Tools and demos that come out of docs and DX work.

## Projects

### AI agents

| Project | What it does | Status |
| --- | --- | --- |
| **[nconnect](https://github.com/Studio1-OSS/nconnect)** · [nconnect.sh](https://nconnect.sh) | Run the coding agents you already use, such as Claude Code, Codex and OpenCode, on open models from [Nebius Token Factory](https://tokenfactory.nebius.com/). One install, nine agents, cost metering, and an Auto mode that picks a model for each task. | Active |
| **[OpenCrewBot](https://github.com/Studio1-OSS/OpenCrewBot)** | An open-source alternative to Grok Bot, on open models. Your own team of AI bots in one chat app, each with its own model, tools, memory and cloud browser. Built on Mastra. | New |

### Evaluation

| Project | What it does | Status |
| --- | --- | --- |
| **[awesome-llm-benchmarks](https://github.com/Studio1-OSS/awesome-llm-benchmarks)** · [awesomellmbenchmarks.com](https://awesomellmbenchmarks.com/) | An open-source leaderboard and evaluation environment that tests models on interactive tasks, from HTML5 Canvas graphics to small games, with Elo rankings and cost-to-latency comparisons. | Active |

### Apps

| Project | What it does | Status |
| --- | --- | --- |
| **[revenue-intelligence](https://github.com/Studio1-OSS/revenue-intelligence)** · [live demo](https://revenue-intelligence-tf.vercel.app/) | Turn customer feedback into account insights, revenue-risk signals and evidence-backed answers. Powered by Nebius Token Factory and Qwen3.8-27B, with Turso and Auth0. Bring your own AI key. | Experimental |

## Featured

### nconnect: your coding agents on open models

```sh
curl -fsSL https://nconnect.sh/install.sh | sh
nconnect claude        # Claude Code on Nebius open models (alias: nclaude)
```

Works with Claude Code, Codex, OpenCode, Pi, Prime Agent, Hermes, DeepSeek Harness, Grok Build and Unreal Agent. Your agent install stays untouched, `nconnect usage` shows what each session cost, and `--model auto` picks a model per task. [Docs](https://nconnect.sh/docs) · [Video tutorial](https://www.youtube.com/watch?v=u8c_exTe2To)

### OpenCrewBot: a team of AI bots in one chat app

```sh
git clone https://github.com/Studio1-OSS/OpenCrewBot.git
cd OpenCrewBot && pnpm install && pnpm dev
```

Chat with bots one-on-one or put them in a room and let them split the work. Each bot picks its own Nebius model and can search the web, keep a `MEMORY.md`, browse in a cloud browser you can watch live, and use your connected apps. It runs in mock mode until you add keys.

## Built on open models

Three of our four projects run on open models from [Nebius Token Factory](https://tokenfactory.nebius.com/): nconnect, OpenCrewBot and revenue-intelligence. awesome-llm-benchmarks compares open and closed models side by side.

## Contributing

Issues and pull requests are welcome in every repository. For bigger changes, open an issue first so we can agree on direction. Each repo's README has its own setup steps; [nconnect → Contributing](https://github.com/Studio1-OSS/nconnect#contributing) is a good place to start.

## Contact

- **General inquiries:** [contact@studio1hq.com](mailto:contact@studio1hq.com)
- **Work with us:** [Book a strategy call](https://cal.com/studio1/collab)
- **Website:** [studio1hq.com](https://studio1hq.com)

## License

Each project is licensed separately; see the `LICENSE` file in each repository. nconnect, awesome-llm-benchmarks and revenue-intelligence are MIT licensed.
