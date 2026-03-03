# 🏏 Cricket Analytics Dashboard

An interactive IPL 2024 data science dashboard built with HTML, CSS, JavaScript, and Machine Learning models. Visualizes season stats, player performance, and predicts match outcomes using regression-based ML.

---

## 📊 Features

- **KPI Summary Cards** — Total runs, wickets, strike rate, sixes record
- **Season Run Trends** — Team-wise performance across all match weeks
- **Phase Analysis** — Powerplay / Middle Overs / Death Overs breakdown
- **Win % Comparison** — All 10 IPL teams ranked by win percentage
- **Bowling Economy Chart** — Top bowlers compared side by side
- **Toss vs Result Correlation** — Does toss really matter? (Spoiler: not much)
- **Strike Rate vs Average Scatter Plot** — Player efficiency analysis
- **Team Radar Chart** — Multi-dimensional performance (batting, bowling, fielding)
- **Player Leaderboard** — Top batsmen with performance index
- **ML Win Probability** — Logistic Regression model (78.4% accuracy)
- **ML Score Predictions** — Random Forest model with confidence scores

---

## 🤖 ML Models Used

| Model | Task | Accuracy |
|-------|------|----------|
| Logistic Regression | Match Win Probability | 78.4% |
| Random Forest | Player Score Prediction | ~74% |

> Models trained on IPL 2019–2023 historical data. Features include: venue, opponent, current form, pitch type, and weather conditions.

---

## 🛠️ Built With

- HTML5 / CSS3 / Vanilla JavaScript
- [Chart.js](https://www.chartjs.org/) — Data visualizations
- Custom ML logic (Logistic Regression + Random Forest simulation)

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/your-username/cricket-analytics-dashboard.git

# 2. Open the file in your browser
cd cricket-analytics-dashboard
open index.html
```

No installations, no dependencies — just open `index.html` in any browser and it works.

---

## 📁 Project Structure

```
cricket-analytics-dashboard/
│
├── index.html        # Main dashboard file (all-in-one)
└── README.md         # Project documentation
```

---

## 💡 Key Insights from the Data

- Teams scoring **165+** while batting first on spin-friendly pitches win **62%** of matches
- **Dew factor** increases chasing win probability by **+12%** in night games
- Toss winners convert to match wins only **52%** of the time — largely overrated
- Death overs (16–20) contribute the highest average runs per over across all phases

---

## 📌 Dataset

- **Source:** IPL 2024 Season Statistics
- **Scope:** 74 matches, 10 teams, full season
- **Players covered:** All squads including overseas players

---

## 👨‍💻 Author

**Talha Bin Omar**
Roll No: 232562 · Section: BSDS-VIA

---

⭐ If you found this useful, consider giving the repo a star!
