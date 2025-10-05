# 🌞 Solar Eclipse Analysis (1901–2100)

## Description
This project analyzes historical and predictive solar eclipse data from 1901 to 2100. It focuses on eclipse durations, identifying the longest events, calculating averages per eclipse type, and filtering upcoming eclipses. Visualizations are included to illustrate key trends and findings.

---
## Technologies & Libraries
- Python 3.x  
- Pandas (data cleaning and manipulation)  
- Matplotlib (visualizations)  
- Google Colab (interactive notebook)

---
## Features
- Cleans and transforms the `duration` column into `total_seconds`.  
- Identifies the **longest eclipse overall**: 1955-12-14 (12 minutes 09 seconds, 729 seconds).  
- Identifies the **longest total eclipse**: 1955-06-20 (7 minutes 08 seconds, 428 seconds).  
- Calculates **average eclipse duration per type**:  
  - Annular: 288.51 seconds  
  - Hybrid: 30.77 seconds  
  - Total: 211.96 seconds  
- Analyzes trends in total eclipse durations over decades.  
- Filters and displays **upcoming eclipses**, e.g., the total eclipse on 2026-08-12 (2 minutes 18 seconds, 138 seconds).  
- Generates bar charts and line plots for duration analysis and trends.

---

## Usage
1. Clone the repository:
```bash
git clone https://github.com/Gabriel-Matos13/solar-eclipse-analysis.git
