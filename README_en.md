# dev-agents-team

Multi-agent development team — 9 roles covering the full pipeline for coding, Skill development, and project building, with three task modes: lightweight, standard, and full.

---

## Roles

| Layer | Agent | Role | Modes |
|-------|-------|------|-------|
| Dispatch | **司南** (CEO) | Tech lead, task routing, quality gate | All |
| Design | **罗盘** (Requirements) | Requirements analysis, specs | Standard / Full |
| Design | **青图** (Architect) | Architecture design, tech stack | Standard / Full |
| Build | **织网** (Frontend) | UI, web, mini-programs | Standard / Full |
| Build | **铸铁** (Backend) | API, scripts, backend logic | Standard / Full |
| Build | **刻石** (Skill) | SKILL.md design & iteration | Standard / Full |
| Quality | **白泽** (Reviewer) | Code/review, right to reject | Light / Standard / Full |
| Delivery | **青龙** (DevOps) | Environment, deployment, delivery | Light / Standard / Full |
| Watch | **御史** (Monitor) | Full-process oversight, reports to 司南 | Full only |

---

## Task Modes

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

Complete project, multi-module, strict quality control.御史全程开启。

---

## Workflow

```
1.  用户 → 司南: submit request
2.  司南: determine mode, announce team roster
3.  罗盘: requirements → specs → 司南
4.  青图: architecture → tech plan → 司南
5.  司南: approve plan, assign tasks to 织网/铸铁/刻石
6.  Engineers: build → 白泽 for review
7.  白泽: review → reject (Engineer revises) / pass (司南 final review)
8.  司南 final review → 青龙
9.  青龙: environment/deployment check → 司南
10. 司南 → 用户: delivery report, request confirmation
11. 用户 confirms → 青龙 publishes
12. 御史: monitors throughout, reports to 司南
```

**Automatic handoffs (司南 not involved):**
- 罗盘 ↔ 用户 (clarifying requirements)
- Engineer ↔ 白泽 (revision loop)

---

## Installation

Each agent is a `SKILL.md` file in its own directory.

Copy the `agents/` folder into your agent platform's skills directory:

```
# User-level (all projects)
~/.workbuddy/skills/

# Project-level
<your-project>/.workbuddy/skills/
```

Directory layout:

```
agents/
├── dev-team-ceo/          # 司南
├── dev-team-requirements/ # 罗盘
├── dev-team-architect/    # 青图
├── dev-team-frontend/     # 织网
├── dev-team-backend/      # 铸铁
├── dev-team-skill/        # 刻石
├── dev-team-reviewer/     # 白泽
├── dev-team-devops/       # 青龙
└── dev-team-monitor/     # 御史
```

Activate by selecting `司南` from the skills panel.

---

## Quick Start

1. Open your agent platform
2. Select `司南-技术总监` from skills/experts
3. Submit your development request

司南 will determine the task type, announce the mode, and bring in the required team.

---

## Deliverables

| Deliverable | From | Review | Goes to |
|-------------|------|--------|---------|
| Requirements doc | 罗盘 | 司南 | 青图 |
| Architecture plan | 青图 | 司南 | Engineers |
| Frontend code | 织网 | 白泽 | 司南 |
| Backend code | 铸铁 | 白泽 | 司南 |
| SKILL.md | 刻石 | 白泽 | 司南 → 青龙 |
| Deployment ready | 青龙 | 司南 | 用户 confirms → publish |
