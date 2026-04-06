# Kobe Skill

> 你的私人凌晨4点健身伙伴——不用睡觉，永远有话要说。

## 仓库里有什么

| 文件 | 技能名 | 用途 |
|------|--------|------|
| `SKILL.md` | `/Laoda` | 科比版PUA — 压力激励系统，失败/挫折时触发 |
| `kobe-bryant-persona.skill` | Kobe Bryant | 角色技能 — 以科比的口吻说话 |
| `laoda-skill/SKILL.md` | `/Laoda` | 独立版PUA技能包 |

## 快速安装

**`/Laoda` 模式（压力激励）：**

```bash
# 安装
claude skill install /path/to/kobe-skill/SKILL.md

# 或 npm
npx skills add shizukuyu0207/kobe-skill
```

**科比角色模式（对话）：**

```bash
claude skill install /path/to/kobe-skill/kobe-bryant-persona.skill
```

## `/Laoda` 触发词

```
/Laoda  /laoda  laoda  老打  老爹
mamba mode  mamba  mamba mentality
motivate me  kobe me up
加油  别放弃  再试试  你行的
又失败了  为什么还不行  算了  做不了
```

## Kobe 角色触发词

```
Kobe  Mamba Mentality  what would Kobe say
曼巴心态  科比会怎么说  科比视角
```

## 示例

**你：** `/Laoda 工作好卷，感觉要寄了`

**Kobe：** "让我把话说清楚——球场不在乎你的感受。它只在乎你能做什么。你觉得我职业生涯没想过摆烂？我想过。但我没有。工作会救你。每次都是。下一题：你打算怎么办？"

## 文件清单

| 文件 | 说明 |
|------|------|
| `SKILL.md` | `/Laoda` PUA系统技能 |
| `laoda-skill/SKILL.md` | 独立版PUA安装包 |
| `kobe-bryant-persona.skill` | Kobe Bryant角色包 |
| `references/` | 支撑文档 |

## 致谢

框架灵感来自 [PUA skill](https://github.com/tanweai/pua) — 用科比哲学替换了企业味道话术，转化为曼巴心态驱动的工作激励系统。

---

*"你要是想让我做件事？告诉我我做不到。"* —— 科比看完这个仓库之后如是说
