![Aubia makes your AI agents review each other.](assets/aubia-github-header-en-light.png#gh-light-mode-only)
![Aubia makes your AI agents review each other.](assets/aubia-github-header-en-dark.png#gh-dark-mode-only)

**English** | [Français](README.fr.md)

[Join the waitlist →](https://aubia.dev/en) | [Devlog →](https://aubia.dev/en/blog) | [Community discussions →](https://github.com/aubia-dev/community/discussions) | [@aubia_dev](https://x.com/aubia_dev) | [LinkedIn](https://www.linkedin.com/company/aubia-dev)

![Phase 0 Waitlist](https://img.shields.io/badge/Phase%200-Waitlist-9D8AFA?style=flat-square&labelColor=15171C)
![Beta 0.1 macOS Apple Silicon](https://img.shields.io/badge/Beta%200.1-macOS%20Apple%20Silicon-F3A4B7?style=flat-square&labelColor=15171C&logo=apple&logoColor=EEF0F3)
![Made in Paris](https://img.shields.io/badge/Made%20in-Paris-FEBF94?style=flat-square&labelColor=15171C)
[![X @aubia_dev](https://img.shields.io/badge/%40aubia__dev-15171C?style=flat-square&logo=x&logoColor=EEF0F3)](https://x.com/aubia_dev)

The easiest way to miss an error is to be the one who wrote it, and it holds just as true for an AI agent. Aubia is the layer above Claude Code, Codex CLI and Mistral that makes them cross-review each other: every agent output is reviewed by a model from another provider before it reaches you.

## Cross-review and Opinions to Executable Plan Mode

In automatic cross-review, one agent implements and a model from another family reviews. The two exchange the diff until convergence, in 3 iterations by default, a setting you can change. If they still disagree, you arbitrate.

Opinions to Executable Plan Mode submits a technical decision to several models in parallel. Each argues its position, then Aubia synthesizes the convergences, isolates the disagreements and generates an Executable Plan that you approve or adjust.

## BYOK and local agents

You keep your Anthropic, OpenAI and Mistral subscriptions and keys, and Aubia never resells tokens. Your API keys are encrypted with a key stored in your OS keychain. The agents run on your machine, each in its own git worktree, and no Aubia server ever sees your source code.

## Roadmap

| Milestone | Content |
|---|---|
| Phase 0, current | Public waitlist, this profile, the community space and the devlog on aubia.dev |
| Beta 0.1 | On macOS Apple Silicon: cross-review, Opinions to Executable Plan Mode and the local cockpit. First waitlist invites |
| After beta 0.1 | One feature per 0.x version, including two new providers: Gemini via Antigravity CLI and a local engine compatible with the OpenAI API. Details on the [aubia.dev roadmap](https://aubia.dev/en#roadmap) |
| 1.0 | Linux and Windows support |

## Contact

For press and partnerships, write to `contact@aubia.dev`. For your personal data and GDPR, to `dpo@aubia.dev`.

Aubia is designed and written by Mike EL GHALI, from Paris. The devlog recounts the decisions behind it, article after article.
