# Policy Risk Memo Architect

Decision-ready geopolitical and policy memo skill for OpenClaw.

This skill helps convert ambiguous geopolitical and policy questions into structured, decision-useful analysis with explicit uncertainty, evidence limits, competing hypotheses, scenarios, and actionable options.

## What this skill does

- Clarifies the actual decision problem before analysis
- Separates facts, assumptions, judgments, and scenarios
- Surfaces evidence limits and key unknowns
- Produces bounded recommendations with trade-offs
- Supports quick briefs, standard memos, scenario briefs, and red-team challenge mode

## Best use cases

- Country and regional risk briefs
- Policy and regulatory exposure assessments
- Sanctions and trade implications notes
- Strategic scenario planning under uncertainty
- Executive decision support memos

## Installation

```bash
clawhub install global-think-tank-analyst
```

## Usage

Invoke the skill from OpenClaw with a clear decision question, audience, and time horizon.

Example prompts:

- "Prepare a policy-risk memo on EU CBAM exposure for a Kazakh metals exporter over 12 months."
- "Give me a scenario brief on US-China semiconductor controls for 2026–2028."
- "Red-team this claim: sanctions risk for this supply chain is manageable."

## Output quality principles

- Decision clarity over rhetorical complexity
- Explicit uncertainty over false precision
- Evidence discipline over confidence theater
- Actionable options over generic commentary

## Repository structure

- `SKILL.md` — canonical skill instructions
- `README.md` — project overview and usage
- `.github/` — issue templates and CI checks

## Versioning

We use semantic versioning for skill releases where practical.

## License

MIT License. See [LICENSE](LICENSE).
