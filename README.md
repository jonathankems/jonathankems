## Hi, I'm Jonathan

I build AI agents that handle support and engineering work at [Snappedly](https://snappedly.com).
[snappedly.com](https://snappedly.com) · [X @jonathankemsley](https://x.com/jonathankemsley)

### What I'm building

**[Factories](https://factories.snappedly.com): an AI support and engineering team that runs on a Mac you own** (alpha)

- Takes customer reports from Slack, issues from GitHub, and production errors from PostHog.
- Triages each report against the codebase. Bugs go to the agents, questions go back to the reporter, and anything else stops with a stated reason.
- An orchestrator agent hands triage, spec, build, review, and deploy to specialist agents. The customer picks the model for each agent and the steps that need human approval.
- Built with TypeScript, Swift, React, and Cloudflare Workers.

**[Snappedly Skills](https://github.com/snappedly/skills): open-source workflow skills for AI coding agents**

- 25 skills that take a change from plan to merged pull request in Claude Code, Codex, and other agents.
- Splits independent work across parallel subagents, each with a fresh context window.
- A person reviews and merges by default. A PR that an agent merges itself gets a label, so reviewers can find it.
- 19 releases, CI validation, a changelog, and a [documentation site](https://docs.snappedly.com/skills/).
