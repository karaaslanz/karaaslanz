# Ömer Karaaslan

Founder of [Karaaslan Labs](https://github.com/karaaslanlabs), an AI-native product company building useful, trustworthy, and scalable digital products.

## Current focus

- Building Karaaslan Labs
- Developing GüvenCheck
- Designing AI-native product development systems
- Co-maintaining [patlux/pi-commandcode-provider](https://github.com/patlux/pi-commandcode-provider)
- Contributing to open-source AI and developer tooling

## Open source

I focus on correctness, reliability, lifecycle behavior, and maintainability in AI/developer-tooling projects.

### Maintainer responsibility

- [patlux/pi-commandcode-provider](https://github.com/patlux/pi-commandcode-provider) — co-maintainer with delegated issue-triage, PR review/merge, and release responsibility. My first maintenance action under that role was reviewing and approving automated provider-compatibility PR [#116](https://github.com/patlux/pi-commandcode-provider/pull/116) after its CI/security/compatibility checks passed; the change was then merged to `main`.

### Selected authored contributions

- [shep-ai/shep #863](https://github.com/shep-ai/shep/pull/863) — respect `SHEP_HOME` for agent checkpoints.
- [shep-ai/shep #875](https://github.com/shep-ai/shep/pull/875) — update Codex resume CLI syntax.
- [shep-ai/shep #877](https://github.com/shep-ai/shep/pull/877) — detect the pnpm Windows command shim.
- [asheshgoplani/agent-deck #2327](https://github.com/asheshgoplani/agent-deck/pull/2327) — fit the embedded preview after session restart.
- [asheshgoplani/agent-deck #2358](https://github.com/asheshgoplani/agent-deck/pull/2358) — show clear feedback when MCP Manager is unavailable for a tool.

All five changes above were authored from this account and merged upstream.

### Review impact

- [openai/openai-agents-python #5083](https://github.com/openai/openai-agents-python/pull/5083) — review identified first a peek→pop TOCTOU race and then a narrower ordering race in compensating wrong-key recovery. The author acknowledged the first finding; the final implementation authenticated the exact claimed SQLite row in the same transaction, rolled back on authentication failure, and added controlled append/clear interleaving coverage that addressed both review threads.
- [asheshgoplani/agent-deck #2298](https://github.com/asheshgoplani/agent-deck/pull/2298) — review caught a regression where quick-create could preserve custom-tool identity while overwriting an explicit per-session command override. The author updated the implementation and regression coverage; I re-reviewed the corrected head.

Review work is listed separately from authored contributions.

### Working style

- Trace behavior before proposing a fix.
- Prefer focused regression coverage over broad rewrites.
- Keep authorship, review impact, and maintainer responsibility as separate claims.
- Follow each repository's contribution and AI-disclosure rules.

Current areas of interest:

- AI agent orchestration and developer tooling
- Reliability and lifecycle correctness
- Observability and failure recovery
- Maintainable, testable contribution paths

## Links

- Website: https://karaaslanlabs.com
- Organization: https://github.com/karaaslanlabs
