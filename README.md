# 🏎️ F1 Race Strategy Case Study — Japanese GP 2026

## 🚀 Key Insight

Race pace consistency and optimal pit timing had a greater impact on race outcome than aggressive undercut strategies.

---

## 📌 Overview

This project presents a race strategy case study using FastF1 data from the Japanese Grand Prix 2026.
The analysis focuses on tyre degradation, race pace consistency, and pit-stop decision-making to understand how strategy influences race performance.

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

Studied performance of different tyre compounds (Medium, Hard) to understand degradation patterns.
Medium tyres showed relatively stable performance with approximately **0.05–0.08 sec/lap degradation** in early stints (~20 laps).

### 🔹 Multi-Driver Comparison

Compared race pace across multiple drivers to identify variability, consistency, and strategic differences.

### 🔹 Gap to Leader Analysis

Calculated lap-by-lap gap to the race leader to understand position dynamics and performance changes during the race.

### 🔹 Undercut vs Overcut Strategy

Evaluated pit-stop timing differences:

* Leclerc (Lap 17) → Early pit (Undercut attempt)
* Verstappen (Lap 22) → Late pit (Overcut strategy)

---

## 🔍 Key Insights

* Most drivers followed a **one-stop strategy (Medium → Hard)**
* Medium tyres offered balanced performance in early stints (~20 laps)
* Hard tyres provided consistent long-run performance
* Early undercut attempts did not guarantee advantage without strong out-lap execution
* Race pace consistency played a key role in maintaining track position

---

## 💡 Strategic Recommendations

* Extend medium tyre stints by **2–3 laps** based on observed degradation trends
* Optimize pit timing based on traffic conditions and track position
* Focus on maintaining consistent lap times to minimize gap loss during pit windows

---

## 📊 Visual Insights

![Tyre Analysis](tyre_analysis.png)

![Gap to Leader](gap_analysis.png)

---

## 🧠 Final Conclusion

Leclerc attempted an early undercut (lap 17), but Verstappen’s extended stint (lap 22) and consistent race pace allowed him to maintain track advantage.
This highlights that long-run pace and consistency can outweigh aggressive pit timing strategies.

---

## 📁 Project Structure

* `japan_2026_analysis.ipynb` → Full analysis notebook
* `README.md` → Project summary and insights
* `requirements.txt` → Dependencies

---

## 🚀 Future Improvements

* Add interactive visualizations using Plotly
* Perform sector-wise performance analysis
* Extend analysis across multiple races for comparative insights

---
