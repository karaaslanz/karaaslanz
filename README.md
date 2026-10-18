# Ömer Karaaslan

**Founder of [Karaaslan Labs](https://karaaslanlabs.com) · Co-maintainer of [pi-commandcode-provider](https://github.com/patlux/pi-commandcode-provider) · Maintainer of [Markdown Reader](https://github.com/petertzy/markdown-reader) · Collaborator on [opencode-mem](https://github.com/tickernelz/opencode-mem)**

I build products, software systems, and technology ventures through Karaaslan Labs. My work spans software engineering, AI, automation, research, integrations, reliability, CI, and production debugging.

Alongside company work, I maintain and contribute to open-source developer tooling. I prefer focused changes, clear ownership, and regression-backed fixes over broad rewrites.

## Current work

- **[Karaaslan Labs](https://karaaslanlabs.com)** — products, software systems, and new technology ventures.
- **GüvenCheck** — a Türkiye-first personal digital trust, decision-support, and protection product currently developed privately within Karaaslan Labs.
- **[KL Security Key](https://github.com/karaaslanlabs/kl-security-key)** — experimental FIDO2/WebAuthn authenticator engineering on RP2040, including attestation and Windows/Entra interoperability work.
- **[pi-commandcode-provider](https://github.com/patlux/pi-commandcode-provider)** — co-maintainer; issue triage, PR review/merge, compatibility work, and releases.
- **[Markdown Reader](https://github.com/petertzy/markdown-reader)** — maintainer; issue triage, PR review, CI/reliability, and day-to-day maintenance.
- **[opencode-mem](https://github.com/tickernelz/opencode-mem)** — repository collaborator; memory-tooling and reliability work following an upstream merged contribution.

Public GitHub activity focuses on open engineering, open-source maintenance, and selected company surfaces. Proprietary product development is not mirrored here by default.

## Open source

Recent work also includes contributions and reviews across **OpenAI Agents Python**, **tensorflow-onnx**, **caarlos0/env**, **agent-deck** and **Shep** with a recurring focus on compatibility, lifecycle correctness, test coverage, and maintainability.

## Selected open-source evidence

- **Merged upstream contributions:** [tensorflow-onnx #2500](https://github.com/onnx/tensorflow-onnx/pull/2500) (ONNX 1.23 compatibility CI), [Markdown Reader #299](https://github.com/petertzy/markdown-reader/pull/299) (stale AI Work result guard), and [opencode-mem #309](https://github.com/tickernelz/opencode-mem/pull/309) (bulk-delete failure handling).
- **Approved upstream reviews:** [pi-commandcode-provider #131](https://github.com/patlux/pi-commandcode-provider/pull/131) (temporary-file cleanup), [Markdown Reader #315](https://github.com/petertzy/markdown-reader/pull/315) (editing during save), and [opencode-mem #317](https://github.com/tickernelz/opencode-mem/pull/317) (user-profile language handling).

These links document specific contributions and reviews, not blanket ownership or endorsement by the upstream projects.

## Recent upstream engineering · October 2026

My recent [pi-commandcode-provider](https://github.com/patlux/pi-commandcode-provider) work includes **seven merged upstream PRs** (September–October 2026), spanning:

- **Authentication and privacy:** [OAuth callback origin validation #149](https://github.com/patlux/pi-commandcode-provider/pull/149) and [stream/error redaction #155](https://github.com/patlux/pi-commandcode-provider/pull/155).
- **Runtime reliability:** [quota request deadlines #152](https://github.com/patlux/pi-commandcode-provider/pull/152) and [stream transport fallback #154](https://github.com/patlux/pi-commandcode-provider/pull/154).
- **Pricing and release stewardship:** [DeepSeek pricing #122](https://github.com/patlux/pi-commandcode-provider/pull/122), [Grok rate correction #127](https://github.com/patlux/pi-commandcode-provider/pull/127), and [v0.7.3 release preparation #123](https://github.com/patlux/pi-commandcode-provider/pull/123).

I also contribute to larger protocol/tooling ecosystems. For example, [MCP TypeScript SDK #3011](https://github.com/modelcontextprotocol/typescript-sdk/pull/3011) proposes asynchronous tool-output validators. **That PR is open and not merged**; upstream review and acceptance remain with the project maintainers.

### Review-ready fixes (not upstream merged)

These are **proposed changes in my own forks**, prepared for the original PR authors to assess. They are not upstream approvals or releases.

- **[pi-commandcode-provider #158: routing recovery and protocol compatibility](https://github.com/karaaslanz/pi-commandcode-provider/tree/review/pr158-routing-recovery-compat-20261018)**: preserves provider requests when optional routing configuration is malformed, supports repair through the real Pi 1.3.0 RPC command, and prevents wrong-wire compatibility flags. Local unit, typecheck and Pi-host regression checks passed.
- **[Markdown Reader #443: editor integration and publication freshness](https://github.com/karaaslanz/markdown-reader/tree/review/pr443-publication-integration-20261018)**: restores editor/project integration and prevents publication previews from using stale selected-tab contents. Local TypeScript, ESLint, production build and three focused regression checks passed. Upstream review remains outstanding.

My goal is to earn deeper upstream responsibility through precise technical work, useful reviews, verifiable tests, and long-term collaboration.

## Contact

Open to selected technical collaborations through Karaaslan Labs.

📩 **[contact@karaaslanlabs.com](mailto:contact@karaaslanlabs.com)** · 🌐 **[karaaslanlabs.com](https://karaaslanlabs.com)**
