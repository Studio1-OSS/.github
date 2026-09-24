<div align="center">

# Studio1 OSS

**Open-source projects from [Studio1](https://studio1hq.com)**, a technical content and developer growth partner for devtool, SaaS, AI, and open-source teams.

[Website](https://studio1hq.com) · [Case Studies](https://studio1hq.com/case-studies) · [Blog](https://studio1hq.com/blog) · [Contact](mailto:contact@studio1hq.com)

</div>

---

## About

Everything in this organization comes out of real developer-facing work: tutorials, docs, DX audits, launch support, and DevRel programs we run with 35+ devtool and SaaS teams. When we hit a problem that no existing tool solves, we build the tool and open-source it.

Our projects tend to cluster around three things:

- **AI agent tooling**: making open models and coding agents work better together
- **LLM evaluation**: transparent, evidence-first ways to compare models
- **Developer experience**: tooling and benchmarks born from docs and DX work

## Projects

| Project | Description | Status |
| --- | --- | --- |
| [nebius-tf-relay](https://github.com/Studio1-OSS/nebius-tf-relay) | Run local coding agents (Claude Code, Codex, OpenCode, and more) on [Nebius Token Factory](https://tokenfactory.nebius.com/) open models. One local daemon translates Anthropic/OpenAI wire formats on the fly, with cost metering, retries, and model fallback. | Active |
| [awesome-llm-benchmarks](https://github.com/Studio1-OSS/awesome-llm-benchmarks) | An evidence-first benchmark suite for comparing model-generated web experiences. Tests are defined before runs are added, so every result traces to one prompt, one model, one cost record. | Active |
| [revenue-intelligence](https://github.com/Studio1-OSS/revenue-intelligence) | Customer revenue intelligence with evidence-backed AI insights. Powered by Nebius Token Factory, NVIDIA Nemotron, Turso, and Auth0. Bring your own AI key. | Experimental |

### Featured: nebius-tf-relay

```sh
curl -fsSL https://nebius-tf-relay.vercel.app/install.sh | sh
nebiusrelay claude   # Claude Code on Nebius open models
```

Works with Claude Code, Codex, OpenCode, Pi, Prime Agent, Hermes, DeepSeek Harness, Grok Build, and Unreal Agent. Nothing about your agent install changes, and your keys never leave your machine.

## Contributing

Issues and pull requests are welcome across all our repositories. For bigger changes, open an issue first so we can align on direction. Each repo includes setup instructions in its README. Start with [`nebius-tf-relay` → Local development](https://github.com/Studio1-OSS/nebius-tf-relay#local-development) for the flagship project.

## Contact

- **General inquiries:** [contact@studio1hq.com](mailto:contact@studio1hq.com)
- **Work with us:** [Book a strategy call](https://cal.com/studio1/collab)
- **Website:** [studio1hq.com](https://studio1hq.com)

## License

Individual projects are licensed separately. See each repository's `LICENSE` file (most are MIT).
