# 🏏 Under Pressure — SupeRR Selector S2 | Round 1

### Who delivers when the game is on the line?

An interactive cricket analytics dashboard designed to explore pressure performance in IPL and T20I cricket, evaluate player reliability in high-leverage situations, and identify strategic squad-building opportunities for Rajasthan Royals.

<p align="center">
  <a href="https://harsh-alt938.github.io/superr-selector-under-pressure/">
    <img src="https://img.shields.io/badge/🚀_LIVE_DASHBOARD-Explore_Now-EA1A8E?style=for-the-badge" alt="Live Dashboard"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-Structure-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-Styling-1572B6?style=flat-square&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-Interactive-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/GitHub_Pages-Deployed-222222?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Responsive-Design-16A34A?style=flat-square"/>
</p>

---

## 📌 Project Overview

In T20 cricket, performance under pressure can define the outcome of a match.

**Under Pressure — SupeRR Selector S2, Round 1** is a data-driven cricket analytics project that examines player performance during high-leverage deliveries. It evaluates pressure reliability, compares batting and bowling performances, and highlights potential areas for squad improvement.

The dashboard transforms cricket statistics into an interactive and visually engaging analytical experience.

### 🎯 Project Objectives

- Identify batters who perform consistently in high-pressure situations.
- Evaluate bowlers based on pressure-handling ability.
- Visualize pressure intensity across different innings and overs.
- Assess Rajasthan Royals' strengths and weaknesses.
- Support data-driven cricket strategy and squad evaluation.

---

## 🌐 Live Demo

**Explore the interactive dashboard here:**

🔗 https://harsh-alt938.github.io/superr-selector-under-pressure/

The dashboard is hosted using GitHub Pages and can be accessed directly through a web browser.

---

## ✨ Key Features

### 📊 Pressure Index Heatmap
- Visualizes pressure intensity across 20 overs.
- Separates first innings and chase scenarios.
- Interactive cells display pressure index information.
- Highlights high-leverage overs.

### 🏏 Batter Performance Rankings
- Top 10 pressure-reliable batters.
- Pressure Reliability Rating (RPRR).
- Strike rate under pressure versus normal situations.
- Batting impact and consistency metrics.
- Powerplay, middle-over, and death-over distribution.

### 🎯 Bowler Performance Rankings
- Top 10 pressure-reliable bowlers.
- Economy rate under pressure versus normal situations.
- Wicket contribution under pressure.
- Bowling phase distribution.
- Reliability and impact indicators.

### 🩷 Rajasthan Royals Squad Analysis
- Franchise performance comparison across 10 teams.
- Batting performance by phase.
- Bowling performance by phase.
- Identification of potential strategic gaps.
- Insights into death-over batting and pressure bowling.

### 📈 Analytical Methodology
- Win-probability-based pressure evaluation.
- Leverage measurement through expected win-probability swing.
- Pressure Reliability Rating.
- Bootstrap-based reliability estimation.
- Minimum sample eligibility criteria.

### 🎨 User Experience
- Clean and modern sports analytics interface.
- Interactive player ranking cards.
- Responsive layout for desktop and mobile.
- Dark mode support.
- Accessible button focus states.
- No backend server required.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Dashboard structure |
| CSS3 | Styling, responsive layout, visualizations |
| JavaScript | Interactivity and data rendering |
| GitHub | Version control and project repository |
| GitHub Pages | Website hosting |
| Google Fonts | Typography |

---

## 📂 Project Structure

```text
superr-selector-under-pressure/
│
├── index.html       # Main dashboard (HTML, CSS, JavaScript, data)
├── README.md        # Project documentation
└── .gitignore      # Optional Git ignore configuration
```

The dashboard is implemented as a self-contained HTML application. Its styling, JavaScript logic, and analytical dataset are embedded within the main file.

---

## 🚀 Getting Started

### Run Locally

No installation or additional dependencies are required.

**Step 1:** Clone the repository.

```bash
git clone https://github.com/harsh-alt938/superr-selector-under-pressure.git
```

**Step 2:** Navigate to the project directory.

```bash
cd superr-selector-under-pressure
```

**Step 3:** Open the dashboard.

Open `index.html` directly in your browser.

Alternatively, use the VS Code Live Server extension for local development.

### Deploy Using GitHub Pages

1. Create a public GitHub repository.
2. Upload `index.html` to the repository root.
3. Navigate to **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` directory.
6. Click **Save**.

Your website will be published using GitHub Pages.

---

## 📐 Analytical Methodology

The dashboard uses the Pressure Reliability Rating (RPRR) to compare player performance in high-leverage situations.

The methodology described in the dashboard includes:

- Out-of-fold win-probability modeling.
- Expected absolute win-probability change to estimate leverage.
- Batter value measured through win probability added.
- Bowler value measured through the negative of win probability added.
- Bootstrap resampling for reliability estimation.
- Eligibility thresholds based on pressure balls and pressure innings.

### Dataset Snapshot

| Metric | Value |
|---|---:|
| Matches analyzed | 842 |
| Total deliveries | 199,029 |
| Pressure deliveries | 49,758 |
| IPL matches | 362 |
| Analysis period | 2022–2026 |

*These figures represent the dataset snapshot embedded in the dashboard.*

---

## 📊 Dashboard Insights

The project explores questions such as:

- Which batters deliver the greatest impact under pressure?
- Which bowlers maintain control in high-leverage overs?
- How does pressure intensity change during a chase?
- Where do Rajasthan Royals rank across different match phases?
- Which player profiles could strengthen the squad?

The dashboard is intended to support exploratory analysis and strategic discussion, rather than serve as a definitive auction or selection recommendation.

---

## 🔮 Future Improvements

Potential enhancements include:

- Integration with updated ball-by-ball datasets.
- Advanced player comparison tools.
- Filters for season, team, and match situation.
- Auction price and player availability analysis.
- Interactive squad selection simulator.
- Automated dashboard updates.
- Additional data visualizations.

---

## ⚠️ Disclaimer

This project is an independent cricket analytics and visualization project created for educational, analytical, and demonstration purposes.

The rankings, metrics, and squad insights are based on the dataset and methodology embedded in the dashboard. They should not be interpreted as official IPL statistics, official team recommendations, or guaranteed predictions of future performance.

Player availability, auction prices, and official squad information should be independently verified before making decisions.

---

## 👨‍💻 Author

**Harsh Bhardwaj**

GitHub: [@harsh-alt938](https://github.com/harsh-alt938)

---

<p align="center">
  <b>Turning cricket data into pressure-proof insights. 🏏📊</b>
</p>

<p align="center">
  ⭐ If you find this project interesting, consider starring the repository!
</p>
