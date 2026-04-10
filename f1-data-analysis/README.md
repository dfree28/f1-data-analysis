# The Speed of Evolution: F1 Performance Metrics (1950-2018)

## Project Overview
This data analytics project utilizes a historical Formula 1 SQLite database to analyze driver performance, constructor dominance, and technical efficiency across 69 years of racing history. 

The project demonstrates a full data pipeline: **SQL** for complex data extraction, **Python (Pandas)** for data cleaning and normalization, and **Seaborn/Matplotlib** for advanced statistical visualization.

## 🛠️ Tech Stack
- **Database:** SQLite (Relational structure with 13+ tables)
- **Language:** Python 3.10+
- **Key Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Analysis Techniques:** SQL Joins, Correlation Heatmaps, Box Plot Variance, Time-Series Analysis.

## Key Insights & Visualizations

### 1. The Dominance Paradox (Drivers)
Analyzing the "Hall of Fame" reveals that while modern drivers like Hamilton lead in total wins, historical legends like Juan Manuel Fangio achieved a 46% win rate. 
> **Business Logic:** Raw counts reward longevity; win percentage rewards dominance within an era's specific competitive context.

### 2. Qualifying vs. Race Outcome
Through a correlation heatmap of grid positions vs. final order, the data confirms a **~70% correlation** between starting on the front row and finishing on the podium.
> **Insight:** This highlights the structural difficulty of overtaking and suggests that for most teams, R&D spend is more effectively used on "single-lap" qualifying pace.

### 3. Pit Stop Efficiency (Operational Analytics)
Using Box Plots to analyze pit stop variance, we identified which constructors have the most consistent crews. 
> **Insight:** Consistency is as valuable as speed. A team with a 22s average stop but high variance is more "at risk" than a team with a 23s average and low variance.

## How to Run the Analysis
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/f1-data-analysis.git](https://github.com/yourusername/f1-data-analysis.git)