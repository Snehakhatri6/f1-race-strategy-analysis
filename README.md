# 🏎️ Race Strategy & Tyre Performance Analysis — Japanese GP 2026

## 📌 Overview

This project presents a race strategy case study using FastF1 data from the Japanese Grand Prix 2026.
The analysis focuses on tyre degradation, race pace consistency, and pit-stop decision-making to understand how strategy impacts race performance.

---

## 🛠️ Tools & Technologies

* Python
* FastF1
* Pandas
* Matplotlib

---

## 📊 Analysis Performed

### 🔹 Race Pace Comparison

Analyzed lap-time trends of selected drivers to evaluate consistency and performance across race stints.

### 🔹 Tyre Degradation

Studied performance of different tyre compounds (Medium, Hard) to understand degradation patterns over laps.

### 🔹 Multi-Driver Comparison

Compared race pace across multiple drivers to identify variability and performance differences.

### 🔹 Gap to Leader Analysis

Calculated lap-by-lap gap to the race leader to understand position dynamics and performance changes during the race.

### 🔹 Undercut vs Overcut Strategy

Evaluated pit-stop timing differences:

* Leclerc (Lap 17) → Early pit (Undercut attempt)
* Verstappen (Lap 22) → Late pit (Overcut strategy)

---

## 🔍 Key Insights

* Most drivers followed a **one-stop strategy (Medium → Hard)**
* Medium tyres showed relatively stable performance in early stints (~20 laps)
* Hard tyres provided consistent performance for longer stints
* Early undercut attempts did not always guarantee advantage without strong out-lap pace
* Race pace consistency played a key role in maintaining track position

---

## 💡 Strategic Recommendations

* Extend medium tyre stints by 2–3 laps based on observed degradation trends
* Optimize pit timing depending on traffic and track position
* Focus on maintaining consistent lap times to minimize gap loss during pit windows

---

## 📁 Project Structure

* `japan_2026_analysis.ipynb` → Full analysis notebook
* `README.md` → Project summary and insights
* `requirements.txt` → Dependencies

---

## 🚀 Future Improvements

* Add interactive visualizations (Plotly)
* Include sector-wise performance analysis
* Expand analysis to multiple races for comparison

---
