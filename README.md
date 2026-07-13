# hiring-signal-skills

Six Claude Code skills for auditing repos and GitHub profiles the way recruiters and staff engineers actually evaluate them — plus a skill for designing AI automation projects with enough real engineering depth to survive that scrutiny.

**These are the exact skills used to plan my own GitHub portfolio transformation.** Not a demo — the repository audits, recruiter-scan simulation, and profile strategy that shaped `github.com/dani-aisystems` were produced by these skill files, unedited beyond stripping anything project-specific before publishing them here.

## Why this exists

Most developers get one piece of advice about their GitHub profile: "make it better." That's not actionable. These skills encode the specific, repeatable judgment calls a senior engineer and a technical recruiter actually make — what counts as a critical finding vs. a style preference, what a recruiter notices in the first 60 seconds, what separates a real AI-automation project from a ChatGPT wrapper — so you can run that judgment against your own repos instead of guessing.

## What's included

| Skill | Use it when you want to... |
|---|---|
| `repository-auditor` | Get a hiring-impact-ranked audit of a single repo before pinning or featuring it |
| `github-portfolio-strategist` | Design your overall profile strategy — positioning, pinned repos, profile README |
| `technical-recruiter-review` | See your profile exactly as a recruiter would in a 60–90 second scan |
| `ai-automation-architect` | Design an AI agent/automation project with real architecture, not a thin wrapper |
| `open-source-advisor` | Get a specific, credible open-source contribution plan instead of generic advice |
| `devops-ci-reviewer` | Audit and generate CI/CD, Dependabot, and branch-protection config for a repo |

Each skill file documents its own role definition, workflow, decision framework, and output format — read any `SKILL.md` directly to see exactly how it reasons.

## Install

```bash
/plugin marketplace add dani-aisystems/hiring-signal-skills
/plugin install hiring-signal-skills@hiring-signal-skills
```

Skills are then available namespaced, e.g. `/hiring-signal-skills:repository-auditor`.

## Example

> "Audit this repo before I pin it" → `repository-auditor` returns a scorecard (documentation, architecture, testing, security, consistency), a ranked list of critical/high/medium findings each with a concrete fix and effort estimate, and a decisive verdict: pin-ready, needs work, or not portfolio-ready yet.

## License

MIT — see [LICENSE](./LICENSE).
