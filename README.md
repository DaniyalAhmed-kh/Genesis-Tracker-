# ◈ GENESIS SYSTEM

> *A personal life operating system for cloud security mastery, Islamic intellectual development, and elite performance , built as a single, self-contained HTML file.*

```
CLOUD SECURITY · ISLAMIC LEADERSHIP · CYBER ELITE · FEB–NOV 2026
```

---

<img width="1611" height="833" alt="s5" src="https://github.com/user-attachments/assets/8a237cea-90da-4a1f-a29a-e01aef4d955f" />


## What Is This

Genesis System is a master training tracker and personal OS designed around one purpose: building the conditions for elite output over a sustained 10-month campaign. It tracks every dimension of the plan — Azure pentesting labs, cloud security certification pathway, machine grinding, Islamic scholarship, and a long-term bucket list — with everything persisted locally in the browser, no server required.

The entire application ships as a single `.html` file. Open it. Close it. Snapshot it. It carries all your progress with it.

---

## Tracks

### ⚗ Azure Codex — 19 Phases
Custom Azure penetration testing lab curriculum built from scratch on a personal tenant. Covers the full attack chain from legal framework and passive recon through to anti-forensics, defence evasion, and professional reporting.

Each phase has three completion gates: **Lab Built**, **Techniques Executed**, **Documented**. All three must be checked to count as complete.

| Phase | Title | Hours |
|-------|-------|-------|
| Phase 0 | Legal Framework & Tenant Setup | 6–8 hrs |
| Phase 1 | Passive Reconnaissance | 8–10 hrs |
| Phase 2 | Active Enumeration | 10–12 hrs |
| Phase 3 | Initial Access & Auth Attacks | 15–20 hrs |
| Phase 4 | Post-Auth Enumeration | 12–15 hrs |
| Phase 5 | Privilege Escalation | 20–25 hrs |
| Phase 6 | Lateral Movement | 15–20 hrs |
| Phase 7 | Azure Resource Exploitation | 20–25 hrs |
| Phase 8 | Persistence & Backdoors | 12–15 hrs |
| Phase 9 | Data Exfiltration | 10–12 hrs |
| Phase 10 | Defence Evasion | 15–20 hrs |
| Phase 11 | Anti-Forensics & IR Manipulation | 8–10 hrs |
| Phase 12 | Reporting & Remediation | 10–12 hrs |
| App. E–J | AI/ML, Sentinel, DevOps, Power Platform, OAuth, Blue Team | 5–8 hrs each |

### ◉ PwnedLabs Pathway — 32 Labs
Structured PwnedLabs progression across four tiers, mapped to the 10-month timeline.
<img width="1550" height="893" alt="s3" src="https://github.com/user-attachments/assets/383e2c9a-e82d-43cc-9648-3846b2cd2700" />

- **T1 Foundation** — Core Azure and AWS concepts (Labs 1–8)
- **T2 Intermediate** — Logic Apps, service firewalls, social engineering, S3 exploitation (Labs 9–18)
- **T3 Advanced** — Kubernetes RBAC, Splunk attacks, GCP infiltration, IR investigation (Labs 19–27)
- **T4 Expert Ranges** — StormShadow × 2, PhantomWave, ThunderDome, PromptStorm full cyber ranges

### ◆ Machines
Import your VulnHub, HackMyVM, VulNyx, DockerLabs, and GitHub machine lists via `.md` format. Track completion, difficulty, time spent, and notes. Visualise your whole library in an interactive galaxy canvas.
<img width="1559" height="848" alt="s4" src="https://github.com/user-attachments/assets/0ddfe5eb-9dc5-4a1b-b30d-a429590af89c" />

### ☽ Islamic Mastery — 10 Modules
The intellectual and spiritual backbone of the system. Ten modules covering:
<img width="1547" height="775" alt="s6" src="https://github.com/user-attachments/assets/74c720f4-7482-4006-a296-5769c85f877c" />

1. Inner Foundation — Tazkiyah & Baseerah
2. Mastery of the Quran — Quran, Arabic & Tafsir
3. Seerah & Hadith — Leadership Manual
4. Aqeedah, Fiqh & Political Thought — Theological Foundation
5. Islamic History & Civilization — Science of Civilizations
6. Political Theory & Statecraft — Power & Governance
7. Rhetoric, Argumentation & Dialectics — Sword of the Intellect
8. Physical Excellence — Body as Instrument
9. Leadership & Strategic Thinking — Command
10. Digital Sovereignty & Cyber Leadership — The Modern Front

Each module contains prioritised books (P1/P2), videos, websites, and practices — over 130 resources total.

### ★ Portfolio — 52 Weeks
A 52-week offensive security tool-building challenge. One tool per week, eight phases from reconnaissance through to a public portfolio site. Every tool has a GitHub publication gate and a notes/build log.

### ✦ Bucket List
Long-term goals across CTF arenas, certifications, research, teaching, physical feats, and legacy targets.

---

## Genesis Enhancement Layer

The enhanced version adds a persistent HUD panel and several quality-of-life systems on top of the original app — all injected without touching the core bundle.

### ⬡ XP & Rank System

Every completion earns XP. Seven rank tiers unlock progressively:

| Rank | XP Required | Icon |
|------|------------|------|
| Ghost | 0 | ◈ |
| Operator | 100 | ◉ |
| Specialist | 300 | ◆ |
| Sentinel | 700 | ⬡ |
| Shadow | 1,200 | ⬟ |
| Wraith | 2,000 | ✦ |
| Apex Operator | 3,000 | ★ |

**XP values:** Azure Phase (all 3 gates) = 25 XP · PwnedLab = 15 XP · Machine = 10 XP · Intel Resource = 5 XP · Bucket Goal = 20 XP · Portfolio Project = 12 XP

### 🔥 Streak System
Tracks daily activity. Miss a day and it resets. The streak counter animates with fire at 3+ days and escalates at 7+.

### ⏱ Pomodoro Timer
25/5/15 minute work-break-long cycle with an SVG ring progress display. Auto-advances between modes. Counts sessions.

### ✦ Daily Brief
Opens automatically each morning with the current Gregorian and Hijri date, today's rotating quote, your streak/rank/overall progress summary, and your primary objective for the day auto-detected from wherever you are in the curriculum.

### ⚔ Boss Battle Countdown
Real-time countdown to your certification target date. Configurable in the settings tab.

### ✎ Session Journal
Log what you worked on each session. Entries persist in localStorage alongside all other progress data.

### 🏆 Achievements
Nine unlockable badges: First Blood, Seven Days, Century, Machine Hunter, Intel Scholar, Halfway, Diamond Streak, One Thousand, Apex Operator.

### Living Background
- Matrix rain — green characters falling continuously across the canvas
- Particle constellation — floating nodes that draw connection lines as they drift
- Particle burst — explodes from your click point every time you complete something, in your current rank's colour
- Screen flash — subtle green pulse on every completion

---

## Technical Details

**Stack:** React 18 + ReactDOM (CDN, bundled in file) · Pure vanilla JS for the enhancement layer · HTML5 Canvas for background and particle effects · `localStorage` for all persistence

**No build step. No server. No dependencies to install.** Open the file in a browser.

**File size:** ~450KB single HTML file (includes the full React production bundle)

### localStorage Keys
| Key | Contents |
|-----|----------|
| `azure-labs-v1` | Per-phase lab completion state |
| `pwned-labs-v1` | Per-lab completion state |
| `ctf-tracker-v4` | Machine list + completion |
| `islamic-path-v1` | Per-resource completion |
| `bucket-list-v1` | Per-goal completion |
| `portfolio-v1` | Per-project build/publish state |
| `genesis-enhance-v4` | XP, streak, journal, rank, settings |

### Snapshot System
The app has a built-in **Save Snapshot** feature (top-right header button) that bakes your entire current `localStorage` state into a new `.html` file. Open that snapshot file in any browser and all your progress is there — no import step needed.

The enhancement layer includes a `<script>` that runs before the React bundle and hydrates `localStorage` from the embedded snapshot data automatically.

### Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `1`–`7` | Switch between the seven main tabs |
| `` ` `` | Toggle HUD minimize/expand |

### Reset
HUD → ⚙ Settings → **RESET ALL DATA** clears every key and reloads. Or: DevTools → Application → Local Storage → clear manually.

---

## Philosophy

This system is built on three convictions:

**First** — meaningful mastery cannot be tracked with a to-do app. It requires a structure that reflects the full complexity of what you are building: technical depth, spiritual foundation, physical capability, and long-horizon vision operating simultaneously.

**Second** — the tool should serve the mission, not become its own project. Everything is a single file. There is no setup, no maintenance, no cloud account. It disappears when you don't need it and reappears exactly where you left it.

**Third** — the environment shapes the operator. The aesthetic, the animations, the daily brief, the countdown — these are not decoration. They are constant reminders of the weight of the work and the honour of attempting it.

> *"Prepare against them whatever you are able of power and of steeds of war."*
> — Quran 8:60

---

## Usage

```bash
# Clone
git clone https://github.com/yourusername/genesis-system.git

# Open — that's it
open GenesisSystem_Enhanced.html
```

No npm. No build. No internet required after the initial load (fonts are pulled from Google Fonts on first open).

To use the machine tracker, export your machine list as a `.md` table from your notes and import it via the **Machines** tab.

---

## Roadmap

- [ ] Mobile-responsive HUD layout
- [ ] Offline font fallback (embed fonts directly)
- [ ] PWA manifest for home screen install
- [ ] Export to PDF — weekly progress report
- [ ] Optional sync via self-hosted endpoint

---
## Lisence 

Copyright (c) 2026 [Your Name]. All rights reserved.

No part of this software may be reproduced, distributed, or transmitted
in any form or by any means without the prior written permission of the author.
---
