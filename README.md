# Steel Energy Consumption Analysis

This project presents a data-driven exploration of power consumption patterns in a steel manufacturing setup. Using Python and machine learning techniques, the analysis identifies key factors contributing to high energy usage and proposes optimization strategies to enhance energy efficiency and reduce costs.

---

## Project Highlights

- Performed exploratory data analysis on real-world steel plant energy data.
- Identified high correlation between lagging reactive power and total energy usage (corr = 0.89).
- Analyzed usage patterns based on `Hour`, `NSM`, and `Load_Type` to detect peak-hour inefficiencies.
- Calculated energy shares and power factor performance across operational load categories.
- Suggested actionable optimizations like load shifting, power factor correction, and off-peak scheduling.

---

## Tools & Technologies

- **Python**: Data processing and modeling  
- **Pandas, NumPy**: Data manipulation  
- **Matplotlib, Seaborn**: Visualizations  
- **Scikit-learn**: Feature importance and modeling  
- **Jupyter Notebook**: Interactive data exploration

---

## Results

- Found strong predictors of energy usage, including reactive power and operation timing.
- Maximum load periods showed the highest average consumption; light loads were least efficient.
- Time-of-day trends revealed avoidable energy costs during peak tariff hours.
