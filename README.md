### Hi, I'm Jovan 👋

Senior full-stack engineer on a live ticketing and payments platform. I work across a large .NET monolith and its migration to a modern .NET and Next.js stack: APIs, SQL, payments, infrastructure, and the incidents that come with them.

I use **Claude Code** as a daily engineering tool, not just for autocomplete. I've built a workflow around it so the agent's output gets checked as hard as a colleague's PR would be.

#### Start here

| | |
|---|---|
| **[claude-code-workflow](https://github.com/jovanmb/claude-code-workflow)** | The skills, hooks and guardrails I use with an AI agent on a production codebase. Every rule is traced to the failure that caused it, and a recorded review run shows what the agent caught and what it got wrong. |
| **[my-sticky-dashboard](https://github.com/jovanmb/my-sticky-dashboard)** · [live demo](https://jovanmb.github.io/my-sticky-dashboard/) | The work dashboard I use every day, rebuilt on sample data. A typed domain shared by a Fastify + SQLite API and an in-memory demo backend, with 38 unit and API tests, 8 Playwright tests, CI, and an [AI decision log](https://github.com/jovanmb/my-sticky-dashboard/blob/main/docs/DECISIONS.md) of twelve times I had to correct the agent. |

#### How I work with AI agents

- **Verify the mechanism before stating a finding.** A diff shows what changed, not why.
- **Every finding must survive a refutation pass**, and come with a concrete failure scenario and file:line evidence.
- **The agent reads, a human decides.** Credentials, production data and anything outward-facing stay behind explicit approval.

#### Stack

C# / .NET · TypeScript · Next.js / React · Node.js · SQL Server · PostgreSQL · AWS (CDK) · Playwright · GitHub Actions
