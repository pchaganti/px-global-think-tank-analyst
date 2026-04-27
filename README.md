# Policy Risk Memo Architect

[![ClawHub](https://img.shields.io/badge/ClawHub-global--think--tank--analyst-2bc6a4)](https://clawhub.ai/vassiliylakhonin/global-think-tank-analyst)
[![CI](https://github.com/vassiliylakhonin/global-think-tank-analyst/actions/workflows/ci.yml/badge.svg)](https://github.com/vassiliylakhonin/global-think-tank-analyst/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Overview

Decision‑ready geopolitical and policy memo skill for OpenClaw and Codex. Converts geopolitical, policy, sanctions, trade, and regulatory questions into structured, fact‑verified memos with explicit uncertainty and evidence limits.

## What the skill does

- Quick brief (Mode A)
- Standard memo (Mode B)
- Scenario brief (Mode C)
- Red‑team challenge (Mode D)

Choose a mode based on client needs and the required level of detail.

## Installation

```bash
openclaw skills install vassiliylakhonin/global-think-tank-analyst
```

## Codex variant

Include `skills/codex/SKILL.md` in your assistant definition to use the skill with Codex.

## Example Prompts

### Mode A – Quick Brief

```
Prepare a quick brief on the EU CBAM exposure for a Kazakh metals exporter over the next 12 months.
```

### Mode B – Standard Memo

```
Write a policy‑risk memo on sanctions exposure for a Russian energy company operating in Central Asia.
```

### Mode C – Scenario Brief

```
Provide a scenario brief on possible U.S‑China semiconductor control developments for 2026‑2028.
```

### Mode D – Red‑Team Challenge

```
Red‑team the claim that supply‑chain sanctions risk for a European tech firm is manageable.
```

## Output Quality

| Criterion | What is provided |
|-----------|------------------|
| **Decision‑oriented** | Structured outline: *Question → Decision → Audience → Horizon → Evidence Mode* |
| **Explicit uncertainty** | Levels: `Certain`, `Plausible`, `Judgment`, `Unknown` |
| **Fact/Assessment separation** | Tags `Fact`, `Assessment`, `Assumption`, `Scenario`, `Unknown` |
| **Evidence discipline** | Mode: `source‑backed`, `reasoning‑only`, `mixed` |
| **Limited evidence handling** | Output `EVIDENCE ACCESS LIMITED` when no live verification is possible |

## Repository structure

```
/SKILL.md
/codex/SKILL.md
/README.md
/LICENSE
```

## License

MIT – see the `LICENSE` file.
