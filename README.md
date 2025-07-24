# 🏏 IPL Analytics Dashboard (2008–2019)

An interactive web app that visualizes IPL statistics using Python, Streamlit, and Plotly. The dashboard allows users to explore player and match performance across multiple seasons.

---

## 🔧 Technologies Used

- **Python 3**
- **Pandas** – for data manipulation
- **Plotly** – for interactive charts (bar, scatter, pie)
- **Streamlit** – to build the web UI
- **CSV Files** – as data sources

---

## 📊 Features

- 📌 **Top Batsmen KPIs** (Runs, Average, Strike Rate)
- 🥇 **Player of the Match Leaderboard**
- 🏏 **Toss Decision Analysis** (Bat vs Field)
- 🧠 **Team Performance by Wins**
- 🎯 **Bowler Insights** (Economy, Wickets)
- 🔍 Pie, Line, and Bar Charts for visual comparisons

---

## 📁 Dataset Sources

- `Top_100_batsman.csv` – Top 100 IPL batsmen stats  
- `Top_100_bowlers.csv` – Top 100 IPL bowlers stats  
- `matches.csv` – Match-level IPL data  

---

## 🖼️ Screenshots

*(Optional: Insert chart images or Streamlit UI screenshots here)*

---

## 🚀 Run Locally

```bash
git clone https://github.com/your-username/ipl-analytics-dashboard.git
cd ipl-analytics-dashboard
pip install -r requirements.txt
streamlit run dataanalytics_streamlit.py
