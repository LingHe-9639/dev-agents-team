# 🧭 dev-agents-team

### Multi-Agent Development Team

> **9 roles × 3 task modes = full pipeline for coding, Skill development, and project building**

> **v2.0 Upgrade**: Inspired by GitHub agency-agents + top-tier engineering practices (Google SRE / ThoughtWorks Tech Radar / Martin Fowler Evolutionary Architecture). Every agent leveled up from "functional" to "expert developer caliber".

---

## Elevator Pitch

> Give any AI tool a complete development team — from requirements analysis to code review, architecture design to deployment, fully coordinated without manual oversight.

---

## Contents

- [Features](#-features)
- [Roles](#-roles)
- [Task Modes](#-task-modes)
- [Workflow](#-workflow)
- [Installation](#-installation)
- [Quick Start](#-quick-start)
- [Deliverables](#-deliverables)
- [Versioning](#-versioning)
- [Upgrade Details](#-upgrade-details)

---

## ✨ Features

| Feature | Description |
|---|---|
| 9 Roles | 司南 / 罗盘 / 青图 / 织网 / 铸铁 / 刻石 / 白泽 / 青龙 / 御史 |
| 3 Task Modes | 🟢 Lightweight · 🟡 Standard · 🔴 Full, activated on demand |
| Independent Skill Engineering | 刻石 owns SKILL.md, decoupled from backend |
| Full-process Quality Gates | 白泽 review + 司南 final + 御史 oversight |
| Quantitative Judgment System | TDS scoring / Performance budgets / NFR thresholds / SLO & Error Budget |
| Universal Installation | Works with any AI platform supporting Skills directories |

---

## 🏗️ Architecture

```
dev-agents-team/
├── README.md              ← Chinese version
├── README_en.md           ← English version
├── CHANGELOG.md           ← v2.0 detailed changelog
└── agents/
    ├── dev-team-ceo/          # 司南 - Tech Decision Maker
    ├── dev-team-requirements/ # 罗盘 - Requirements Engineer
    ├── dev-team-architect/    # 青图 - Architecture Decision Maker
    ├── dev-team-frontend/     # 织网 - Frontend Engineer
    ├── dev-team-backend/      # 铸铁 - Backend Systems Engineer
    ├── dev-team-reviewer/     # 白泽 - Technical Mentor
    ├── dev-team-devops/       # 青龙 - Platform Engineer
    ├── dev-team-monitor/      # 御史 - Quantitative Analyst
    └── dev-team-skill/        # 刻石 - Role Architect
```

### Role Overview (v2.0)

| Layer | Agent | v2.0 Core Upgrade | Modes |
|---|---|---|---|
| Dispatch | **司南** | Tech Debt Scoring (TDS 5-dim 15-pt) / Veto rights / Velocity tracking | All |
| Design | **罗盘** | NFR framework / 4-dim boundary用例 / Given-When-Then acceptance | Standard / Full |
| Design | **青图** | C4 model / Tech radar / Performance budgets / Evolutionary architecture | Standard / Full |
| Build | **织网** | Atomic design / Core Web Vitals / State management L1-L4 | Standard / Full |
| Build | **铸铁** | Observability 3D / Resilience 3-patterns / Cache L1/L2/L3 | Standard / Full |
| Build | **刻石** | Adversarial testing / Role interaction matrix / S-A-B-C-D grading | Standard / Full |
| Quality | **白泽** | Grady Rumble 4-dim smells / Mentor feedback framework / Cyclomatic complexity | All |
| Delivery | **青龙** | SLO/SLI/SLA + Error Budget / MTTR / Platform engineering | All |
| Watch | **御史** | Metric cascade / Efficiency baselines / Pattern recognition / Error budget | Full only |

---

## 🎯 Task Modes

### 🟢 Lightweight (3 agents)

Single script, Skill tweak, minor fix.

```
用户 → 司南 → Engineer (铸铁/织网/刻石) → 白泽 → 青龙 → 司南 → 用户
```

### 🟡 Standard (5–6 agents)

Feature module, full Skill build, small project.

```
用户 → 司南 → 罗盘 → 青图 → Engineers (parallel) → 白泽 → 青龙 → 司南 → 用户
```

### 🔴 Full (9 agents)

Complete project, multi-module, strict quality control. 御史 monitors throughout.

---

## ⚙️ Workflow

```
1.  用户 → 司南: submit request
2.  司南: determine mode (TDS scoring), announce team roster
3.  罗盘: requirements → specs (with NFR) → 司南
4.  青图: architecture → tech plan (with performance budget + tech radar) → 司南
5.  司南: approve plan, assign tasks to 织网/铸铁/刻石
6.  Engineers (parallel): build → 白泽 for review
7.  白泽: review (4-dim code smells) → reject (Engineer revises) / pass (司南 final)
8.  司南 final → 青龙
9.  青龙: environment/deployment/SLO check → 司南
10. 司南 → 用户: delivery report, request confirmation
11. 用户 confirms → 青龙 publishes
12. 御史: monitors (metric cascade + efficiency baselines), reports to 司南
```

**Automatic handoffs (司南 not involved):**

- 罗盘 ↔ 用户 (clarifying requirements)
- Engineer ↔ 白泽 (revision loop)

---

## 📥 Installation

Each agent is a `SKILL.md` file in its own directory.

Copy the `agents/` folder into your AI platform's Skills directory:

```
# User-level (all projects)
~/.skills/

# Project-level
<your-project>/.skills/
```

Activate by selecting `司南` from the skills panel.

---

## 🚀 Quick Start

1. Copy `agents/` to your AI platform's Skills directory
2. Select `司南-技术总监` from skills/experts
3. Submit your development request

司南 will determine the task type, announce the mode, and bring in the required team.

---

## 📦 Deliverables

| Deliverable | From | Review | Goes to |
|---|---|---|---|
| Requirements doc | 罗盘 | 司南 | 青图 |
| Architecture plan | 青图 | 司南 (veto rights) | Engineers |
| Frontend code | 织网 | 白泽 (4-dim smells) | 司南 |
| Backend code | 铸铁 | 白泽 (4-dim smells) | 司南 |
| SKILL.md | 刻石 | 白泽 (adversarial testing) | 司南 → 青龙 |
| Deployment ready | 青龙 | 司南 (SLO/Error Budget) | 用户 confirms → publish |

---

## 📄 Versioning

| Version | Date | Changes |
|---|---|---|
| v1.0.0 | 2026-04-17 | Initial release |
| **v2.0.0** | **2026-04-17** | **Full upgrade: all 9 agents gained quantitative judgment dimensions, engineering depth, veto rights, and adversarial testing awareness. See CHANGELOG.md** |

---

## 📖 Upgrade Details

v2.0 vs v1.x — what changed in each agent:

| Agent | From "Functional" to "Expert" | Key Addition |
|---|---|---|
| 司南 | No tech judgment → Tech decision maker | TDS (5-dim 15-pt), 5-dim decision framework, 5 veto rights, velocity tracking |
| 罗盘 | No NFR → Requirements engineer | NFR framework, 4-dim boundary用例, Given-When-Then acceptance criteria |
| 青图 | Static design → Evolutionary architecture | C4 model, tech radar, concrete performance budget numbers, Strangler Fig |
| 织网 | Generic components → Atomic design | Atom→Molecule→Organism→Template→Page, Core Web Vitals thresholds, state L1-L4 |
| 铸铁 | Basic API → Reliable systems | Observability 3D, resilience 3-patterns, cache L1/L2/L3 |
| 白泽 | Bug list → Technical mentor | Grady Rumble 4-dim, mentor feedback framework, cyclomatic complexity |
| 青龙 | Deployment → Platform engineering | SLO/SLI/SLA + Error Budget, MTTR targets, post-mortem template |
| 御史 | Qualitative → Quantitative | Metric cascade, efficiency baselines, pattern recognition, error budget monitoring |
| 刻石 | Code templates → Role architect | Adversarial testing, role interaction matrix, MCP permission guide, S-A-B-C-D grading |

Full line-by-line diff available in `CHANGELOG.md`.

---

## 📜 License

- License: MIT License
- Open to contributions, Fork welcome

---

*This project is a clean template package and contains no personal data.*
