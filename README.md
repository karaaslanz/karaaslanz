# Ömer Karaaslan

**Founder of [Karaaslan Labs](https://karaaslanlabs.com) · Core Maintainer of [pi-commandcode-provider](https://github.com/patlux/pi-commandcode-provider) · Maintainer of [Markdown Reader](https://github.com/petertzy/markdown-reader)**

I build technology products and software systems through Karaaslan Labs, and maintain open-source developer tooling. My work focuses on reliability, integrations, automation, lifecycle correctness, CI, and production debugging.

At Karaaslan Labs, we develop products, systems, and new technology ventures across different problem areas—using software, AI, automation, and research according to the need.

**Open to selected paid technical collaborations through Karaaslan Labs** — open-source maintenance, AI/developer-tooling integrations, reliability/debugging, and technical product or system work.

📩 **[contact@karaaslanlabs.com](mailto:contact@karaaslanlabs.com)** · 🌐 **[karaaslanlabs.com](https://karaaslanlabs.com)**

## What I build & maintain

- **[Karaaslan Labs](https://karaaslanlabs.com)** — technology company developing products, software systems, and new technology ventures.
- **[GüvenCheck](https://github.com/karaaslanlabs/guvencheck)** — current Karaaslan Labs product for assessing suspicious digital content and making the risk, reason, and next action easier to understand.
- **[pi-commandcode-provider](https://github.com/patlux/pi-commandcode-provider)** — core maintainer with delegated issue triage, PR review/merge, and release responsibility.
- **[Markdown Reader](https://github.com/petertzy/markdown-reader)** — maintainer in the project's initial onboarding period, helping with issue triage, PR review, CI/reliability, and day-to-day maintenance.

## Maintainer work

- **[pi-commandcode-provider #122](https://github.com/patlux/pi-commandcode-provider/pull/122)** — authored and landed time-aware DeepSeek V4 peak pricing across native and legacy transports, with deterministic UTC boundary/weekend coverage.
- **[pi-commandcode-provider #123](https://github.com/patlux/pi-commandcode-provider/pull/123)** — prepared and shipped the v0.7.3 stable release after owner approval; the release workflow published the verified release through trusted publishing.
- **[Markdown Reader #295](https://github.com/petertzy/markdown-reader/pull/295)** — current maintainer CI work adding a real pull-request validation gate; fork and upstream validation cover 155 backend tests, 8 frontend tests, lint, and production build.

## Selected upstream work

- **[shep-ai/shep #863](https://github.com/shep-ai/shep/pull/863)** — respect `SHEP_HOME` for agent checkpoints.
- **[shep-ai/shep #875](https://github.com/shep-ai/shep/pull/875)** — update Codex resume CLI syntax.
- **[shep-ai/shep #877](https://github.com/shep-ai/shep/pull/877)** — detect the pnpm Windows command shim.
- **[agent-deck #2327](https://github.com/asheshgoplani/agent-deck/pull/2327)** — fit the embedded preview after session restart.
- **[agent-deck #2358](https://github.com/asheshgoplani/agent-deck/pull/2358)** — show clear feedback when MCP Manager is unavailable for a tool.
- **[tensorflow-onnx #2500](https://github.com/onnx/tensorflow-onnx/pull/2500)** — current ONNX 1.23 compatibility work with an isolated, validated package/API smoke lane.

## Review impact

- **[pi-commandcode-provider #124](https://github.com/patlux/pi-commandcode-provider/pull/124)** — identified a provider-wire compatibility boundary around non-GPT Responses tool calling; a co-maintainer confirmed the risk and made a full tool-call roundtrip regression a pre-merge requirement.
- **[caarlos0/env #441](https://github.com/caarlos0/env/pull/441)** — identified a nested parsing regression at the FuncMap/scalar-struct boundary; the author independently reproduced it and changed the implementation and regression coverage.
- **[Markdown Reader #284 → #292](https://github.com/petertzy/markdown-reader/pull/292)** — review identified timeout/signal-composition risks; the replacement implementation adopted endpoint-specific budgets, composed cancellation, and focused regression coverage.
- **[openai/openai-agents-python #5083](https://github.com/openai/openai-agents-python/pull/5083)** — identified concurrency/race conditions in recovery logic; the final implementation changed to authenticate the exact claimed SQLite row in the same transaction and added controlled interleaving coverage.

## How I work

- Trace real behavior before proposing a fix.
- Prefer focused regression coverage over broad rewrites.
- Keep ownership, authorship, review impact, and maintainer responsibility explicit.
- Optimize for changes that are testable, maintainable, and useful in production.
