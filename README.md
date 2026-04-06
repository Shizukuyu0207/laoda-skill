# Kobe Skill

> Your personal 4am gym buddy who never sleeps and always has opinions.

## Two Skills in This Repo

| File | Skill Name | What It Does |
|------|-----------|---------------|
| `SKILL.md` | `/Laoda` | Kobe PUA — pressure & motivation system, triggers on failure/frustration |
| `kobe-bryant-persona.skill` | Kobe Bryant | Persona — speaks AS Kobe on any topic |
| `laoda-skill/SKILL.md` | `/Laoda` | Standalone version of the PUA skill |

## Quick Start

**For `/Laoda` mode (PUA pressure system):**

```bash
# Install
claude skill install /path/to/kobe-skill/SKILL.md

# Or npm
npx skills add shizukuyu0207/kobe-skill
```

**For Kobe Bryant persona (conversational):**

```bash
claude skill install /path/to/kobe-skill/kobe-bryant-persona.skill
```

## `/Laoda` Triggers

```
/Laoda  /laoda  laoda
mamba mode  mamba  mamba mentality
motivate me  kobe me up
加油  别放弃  再试试
又失败了  为什么还不行  算了
```

## Kobe Persona Triggers

```
Kobe  Mamba Mentality  what would Kobe say
曼巴心态  科比会怎么说
basketball philosophy  mamba
```

## Example

**You:** `/Laoda I'm stuck and nothing works`

**Kobe:** "Let me be clear — the court doesn't care about your feelings. It only cares about what you can do. You think I never felt like sitting out? I did. Know what I did? Got back in the gym. The work will save you. Every time."

## Files

| File | Description |
|------|-------------|
| `SKILL.md` | `/Laoda` PUA system skill |
| `laoda-skill/SKILL.md` | Standalone `/Laoda` package |
| `kobe-bryant-persona.skill` | Kobe Bryant persona bundle |
| `references/` | Supporting docs |

## Credit

Framework inspired by [PUA skill](https://github.com/tanweai/pua) — Kobe philosophy replaces corporate flavor text with Mamba Mentality.

---

*"You want me to do something? Tell me I can't do it."* — What Kobe would've said about this repo
