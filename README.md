<div align="center">

# 🏏 Under Pressure — SupeRR Selector S2 (Round 1)
### Quantifying Clutch Performance & Auction Strategy for Rajasthan Royals

[![Live Demo](https://img.shields.io/badge/Live_Dashboard-Launch_App-EA1A8E?style=for-the-badge&logo=githubpages&logoColor=white)](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)
[![Data Scope](https://img.shields.io/badge/Dataset-842_T20_Matches_(2022--2026)-0B1F4B?style=for-the-badge)]()
[![Tech Stack](https://img.shields.io/badge/Built_With-HTML5_%7C_CSS3_%7C_Vanilla_JS-1B2437?style=for-the-badge)]()

*An interactive, zero-dependency sports analytics web application evaluating T20 batter and bowler reliability under high-leverage match situations.*

</div>

---

## 📊 Executive Overview

Traditional T20 averages and strike rates treat every ball equally—masking the difference between scoring runs in a low-stakes middle over versus delivering when a match hangs in the balance. 

**Under Pressure** models ball-by-ball win-probability leverage across **842 IPL and T20I matches (199,029 deliveries)** from 2022 to 2026 to isolate true clutch performers and identify actionable squad gaps for the **Rajasthan Royals (RR)** ahead of the IPL 2027 Auction.

---

## ✨ Key Dashboard Features

* **🔥 Interactive Match Leverage Heatmap:** Visualizes the Pressure Index across all 20 overs for both 1st Innings and Chases. Click or focus any cell to inspect exact over-by-over leverage thresholds.
* **🏆 Pressure Reliability Rating (RPRR) Leaderboards:** Switch seamlessly between the **Top 10 Batters** and **Top 10 Bowlers**, complete with expandable player cards showing:
  * Pressure Strike Rate / Economy vs. Baseline
  * Win-Probability Added (Impact per 100 balls)
  * Positive Innings/Spell Hit Rate & Bootstrap Top-10 Stability
  * Phase-by-Phase Pressure Distribution (Powerplay, Middle, Death)
* **🩷 Rajasthan Royals Gap Analysis:** Benchmarks RR against all 10 IPL franchises across 6 phase-role combinations, highlighting critical recruitment priorities (Death Batting `#10/10`, Powerplay/Death Pace Bowling) alongside core retention targets (`Yashasvi Jaiswal`).
* **📐 Transparent Statistical Methodology:** Full breakdown of pressure tiers (*Extreme*, *High*, *Ordinary*), win-probability swing metrics, and sample-size eligibility thresholds.

---

## 🧮 Analytical Methodology

1. **Win-Probability & Leverage Modeling:** Out-of-fold win-probability estimates determine the expected absolute win-probability swing ($|\Delta \text{WP}|$) on the next delivery, generating a normalized **Pressure Index**.
2. **Reliability & Resampling (RPRR):** To prevent small-sample fluke rankings, raw Pressure Reliability Ratings (**PRR**) are shrunk toward the mean and evaluated at the **25th percentile across 120 bootstrap resamples**.
3. **Qualification Criteria:** Active in 2026 with a minimum sample of **150 pressure balls & 15 innings** for batters, and **120 pressure balls & 15 spells** for bowlers.

| Pressure Tier | Share of Deliveries | Mean Win-Prob Swing / Ball | Wickets / 100 Balls |
| :--- | :---: | :---: | :---: |
| **Extreme** | 10% | 3.93 pts | 6.57 |
| **High** | 15% | 1.72 pts | 5.40 |
| **Ordinary** | 75% | 0.69 pts | 5.25 |

---

## 🛠️ Architecture & Tech Stack

Built as a lightweight, ultra-fast single-file web application with zero external JavaScript frameworks or build steps required:

* **Structure & Accessibility:** Semantic HTML5 with ARIA attributes (`aria-pressed`, `aria-expanded`, keyboard-navigable heatmap cells).
* **Styling:** Custom CSS Grid & Flexbox layout featuring Rajasthan Royals brand palette (`#EA1A8E` Pink & `#0B1F4B` Navy), fluid typography (`Barlow Condensed` & `IBM Plex Sans`), and automatic **Dark Mode** support via `prefers-color-scheme`.
* **Data Visualization:** Pure DOM-driven horizontal range bars, phase breakdown meters, and interactive heat matrices.

---

## 🚀 Running Locally

No package manager or local server is needed:

```bash
# Clone the repository
git clone [https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git)

# Navigate into the directory
cd YOUR-REPO-NAME

# Open index.html in any modern browser
