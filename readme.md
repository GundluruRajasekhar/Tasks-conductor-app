# Conductor: AI agent control desk

Built for the IBM watsonx Orchestrate challenge: *AI agents should create value, not operational headaches.*

Conductor shows how one control desk can **build visibility, orchestrate, manage and govern** agents from any platform.

## What it does
1. **Registry:** see every agent, where it runs, its risk and its net value per month. Pause or resume any agent.
2. **Orchestration:** send a task by skill. Conductor picks the active agent with the best net value.
3. **Governance:** a per-agent spend cap blocks overspend. Risky tasks wait for a human to approve or reject.
4. **Audit trail:** every decision is logged with a time.
5. **Self-tests:** one button runs 15 checks on the routing, policy and input rules.

## Run it
Open `index.html` in any modern browser. No install, no build, no network.

## How it maps to the problem statement
| Challenge theme | Feature |
|-----------------|---------|
| Wherever they are built or run | Origin column covers watsonx Orchestrate, Python, LangChain and SaaS agents |
| Orchestrate | Skill-based routing by net value |
| Manage | Pause, resume, spend caps, value metrics |
| Govern | Approval queue and audit trail |
| Value, not headaches | Net value is the headline number |

## Security
CSP with `default-src 'none'`, no `innerHTML` or `eval`, sanitised and range-checked input, no storage, no network.

## Accessibility
Skip link, landmarks, labelled controls, live regions, visible focus, 44 px targets, AA contrast, reduced motion.

## Tests
Press **Run self-tests** on the page. Expected: `15 of 15 tests passed.`

## Project files
`index.html` (app) · `requirements.md` · `readme.md` · `tasks.md`

## Next steps
Connect to the real watsonx Orchestrate APIs, add sign-in and role-based approvals, and persist the audit trail.
