<div align="center">

# 🎮 DevOps Quest
### *Level up from Noob Ops to Deploy Master*

![Level](https://img.shields.io/badge/Current_Level-1-6C5CE7?style=flat-square)
![XP](https://img.shields.io/badge/XP-0%2F9000-00B894?style=flat-square)
![Class](https://img.shields.io/badge/Class-Unassigned-E17055?style=flat-square)

*A gamified guide to becoming a DevOps engineer — treat every tool as a skill,*
*every stage as a level, and every real project as a boss fight.*

</div>

---

## 🧙 The Premise

You start as a **Script Kiddie** with a terminal and a dream. Nine levels stand between
you and the title of **Deploy Master**. Each level unlocks new abilities. Skip a level
and the boss fights later will destroy you. This is the way.

```mermaid
journey
    title Your DevOps Journey (Effort vs Confidence)
    section Early Days
      Learn Linux & Git: 3: Script Kiddie
      Write first script: 4: Script Kiddie
    section The Grind
      Break a pipeline: 2: Apprentice
      Fix it at 2am: 5: Apprentice
      First green build: 7: Practitioner
    section The Ascent
      Deploy to prod: 6: Practitioner
      Survive an outage: 8: Engineer
      Automate everything: 9: Engineer
    section Endgame
      Design a system: 9: Architect
      Pass the interview: 10: Deploy Master
```

---

## 🗺️ The Skill Tree

Instead of a straight line, think of this as an RPG skill tree — some branches
you can grind in parallel, others gate the next tier.

```mermaid
flowchart TB
    subgraph T1["🟢 TIER 1 — Foundations"]
        direction LR
        L["🐧 Linux"] --- G["🔧 Git"] --- N["🌐 Networking"]
    end

    subgraph T2["🔵 TIER 2 — Automation"]
        direction LR
        P["🐍 Scripting"] --- Y["📄 YAML/JSON"] --- A["🔌 APIs"]
    end

    subgraph T3["🟣 TIER 3 — Delivery"]
        direction LR
        C["🔁 CI/CD"] --- D["🐳 Docker"] --- K["☸️ Kubernetes"]
    end

    subgraph T4["🟠 TIER 4 — Mastery"]
        direction LR
        I["🏗️ IaC"] --- M["📊 Monitoring"] --- S["🔐 Security"]
    end

    T1 --> T2 --> T3 --> T4 --> BOSS(("👑 BOSS:<br/>Ship a Real<br/>Production System"))

    style T1 fill:#00b894,stroke:#00895c,color:#fff
    style T2 fill:#0984e3,stroke:#065a9e,color:#fff
    style T3 fill:#6c5ce7,stroke:#4834b0,color:#fff
    style T4 fill:#e17055,stroke:#b04a30,color:#fff
    style BOSS fill:#2d3436,stroke:#fdcb6e,stroke-width:3px,color:#fdcb6e
```

---

## 🏆 Levels & XP Table

| Lvl | Class Title | Unlocks | XP to Clear |
|:---:|---|---|:---:|
| 1 | 🧑‍💻 **Script Kiddie** | Linux, Bash, basic Git | 500 |
| 2 | 🔍 **Terminal Novice** | Networking basics, GitHub flow | 500 |
| 3 | 🐍 **Automator** | Python/JS, YAML, JSON, REST APIs | 800 |
| 4 | 🔁 **Pipeline Apprentice** | Jenkins / GitHub Actions / GitLab CI | 1000 |
| 5 | 🐳 **Container Tamer** | Docker, Docker Compose | 1000 |
| 6 | ☸️ **Orchestrator** | Kubernetes, cloud (AWS/Azure/GCP) | 1500 |
| 7 | 🏗️ **Infra Architect** | Terraform, Ansible | 1200 |
| 8 | 📡 **Observability Mage** | Prometheus, Grafana, logging/alerts | 1000 |
| 9 | 🛡️ **Security Sentinel** | Secrets mgmt, DevSecOps, access control | 1200 |
| 🏁 | 👑 **Deploy Master** | *Real-world project + interview boss fight* | 300 |

**Total XP to Deploy Master: 9000**

---

## ⚔️ Boss Fights (Real Projects)

Each boss fight is a project that forces you to combine everything learned so far.
No boss, no level-up — theory alone won't save you.

```mermaid
stateDiagram-v2
    [*] --> Boss1
    Boss1: 🐳 Boss 1 — Dockerize a Full App
    Boss2: 🔁 Boss 2 — Build a CI/CD Pipeline
    Boss3: ☸️ Boss 3 — Deploy to Kubernetes
    Boss4: 🏗️ Boss 4 — Provision Infra with Terraform
    Boss5: 📊 Boss 5 — Add Monitoring & Alerts
    FinalBoss: 👑 Final Boss — End-to-End Automated System

    Boss1 --> Boss2
    Boss2 --> Boss3
    Boss3 --> Boss4
    Boss4 --> Boss5
    Boss5 --> FinalBoss
    FinalBoss --> [*]: 🎉 Deploy Master Achieved
```

| Boss | Victory Condition |
|---|---|
| 🐳 Dockerize a Full App | App runs identically on any machine via `docker compose up` |
| 🔁 Build a CI/CD Pipeline | Push to `main` → auto build, test, deploy — no manual steps |
| ☸️ Deploy to Kubernetes | App survives a pod being killed, with zero downtime |
| 🏗️ Provision Infra with Terraform | Entire environment rebuilt from code in under 10 minutes |
| 📊 Add Monitoring & Alerts | You get paged *before* a user complains |
| 👑 Final Boss | A stranger could deploy your project from the README alone |

---

## 🎒 Your Inventory (Tool Loadout)

<table>
<tr>
<td valign="top" width="33%">

**⚙️ Core Kit**
- Linux / Bash
- Git & GitHub
- Python or JS

</td>
<td valign="top" width="33%">

**🚚 Delivery Kit**
- Docker
- Kubernetes
- CI/CD platform of choice

</td>
<td valign="top" width="33%">

**🛡️ Endgame Kit**
- Terraform / Ansible
- Prometheus / Grafana
- Secrets manager

</td>
</tr>
</table>

---

## 📜 Quest Log (Repo Structure)

```text
devops-quest/
├── README.md
├── 📓 quest-log/        # notes per level
├── 📚 scrolls/          # PDFs & study material
├── 🎞️ tomes/            # slides & presentations
└── ⚔️ boss-fights/      # real projects, one folder per boss
```

---

## 🧾 Rules of the Quest

1. **No skipping tiers.** Kubernetes without Docker is a boss fight you will lose.
2. **XP only counts if you build something.** Watching tutorials is not grinding.
3. **Break things on purpose.** You learn more from a failed deploy than a smooth one.
4. **Document as you go.** Your `quest-log/` is future-you's cheat sheet.
5. **The final boss is an interview.** Practice explaining *why*, not just *how*.

---

<div align="center">

### 🕹️ Status: `Level 1 — Script Kiddie`
### Next Unlock: 🐧 Linux Fundamentals

**Your terminal awaits. Press Start.**

</div>\