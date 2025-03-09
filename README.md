#NFL-Big-Data-Bowl-2025

# 🏈 NFL Big Data Bowl 2025 - Predicting Play Type

![NFL Banner](https://upload.wikimedia.org/wikipedia/en/a/a2/National_Football_League_logo.svg)  

## 📌 Project Overview
This project analyzes **NFL Next Gen Stats to predict Run vs. Pass plays using pre-snap player tracking data.** It includes:
✅ **Data Loading & Preprocessing**
✅ **Feature Engineering from Tracking Data**
✅ **Predictive Modeling with Logistic Regression**
✅ **Team-wise Play Analysis with Visualizations**

---

## 🔍 Background

The NFL Big Data Bowl is an annual competition where data scientists analyze NFL tracking data to gain insights and improve decision-making in football. This project focuses on predicting play types based on pre-snap player movements.

---

## 📊 Dataset
- **Source**: Next Gen Stats provided by the NFL Team
- **Files Used**:
``games.csv`` (Game details),
``players.csv`` (Player details),
``plays.csv`` (Play-by-play data),
``player_play.csv`` (Player-specific tracking data),
``tracking_week_1.csv`` (Player movements for Week 1)

Key Features: Down, Distance, Yard Line, Play Type, Speed, Acceleration, Formation, etc.

---

## 🚀 Features

### 🔹 ***1. Data Loading & Preprocessing***
- Merges plays.csv with games.csv to filter Week 1 data
- Cleans and structures pre-snap player tracking data

### 🔹 ***2. Feature Engineering***
- Aggregates average speed, acceleration, and distance covered by players before the snap
- Merges with play data to prepare features for modeling

### 🔹 ***3. Predictive Modeling***
- Uses Logistic Regression to predict Run vs. Pass plays
- Converts offensive formation into dummy variables for better prediction
- Trains the model on labeled data and evaluates accuracy

### 🔹 ***4. Team-wise Play Analysis***
- Allows users to select a team for analysis
- Displays play type distribution (Run vs. Pass)
- Summarizes pre-snap metrics for the team
- Shows offensive formation usage

---

## 🛠️ Tech Stack
🔹 **Python** (Pandas, NumPy)
🔹 **Matplotlib & Seaborn** (Visualizations)
🔹 **Scikit-learn** (Logistic Regression)
🔹 **Google Colab** (Development)

---

## 🧠 Challenges
- Cleaning and merging large datasets;
- Handling missing values & feature selection for better predictions

---

## 📌 Future Improvements
- Implement advanced ML models (Random Forest, XGBoost);
- Add real-time player tracking visualizations;
- Extend analysis to all weeks of the season

---

## 📜 License
This project is open-source. Contributions are welcome!

---

⭐ If you found this useful, don’t forget to star this repo! ⭐
