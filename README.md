# Macro-Shock Logistics & Sensitivity Engine

An interactive macroeconomic simulation engine that uses **Python (Scikit-Learn/Pandas)** to isolate operational vulnerabilities to fuel price inflation, feeding a native **Power BI** "What-If" scenario matrix to calculate risk outlooks on unit economics.

---

## 🛠️ The Technical Stack
* **Econometric Modeling:** Python, Scikit-Learn (Linear Regression), NumPy
* **Data Processing & ETL:** Pandas
* **Business Intelligence Design:** Power BI Desktop (Dynamic DAX Modeling)
* **Development Environment:** VS Code

---

## 📊 Core Business Problems Solved

### 1. Macro-Inflationary Cost Isolation
* Engineered a synthetic operations data tracking pipeline modeling 365 days of dispatch volume, baseline shipping expenses, and domestic diesel/petrol price volatility (₹85 - ₹105/L).
* Applied an algorithmic regression model to isolate the exact fuel surcharge multiplier coefficient, calculating precisely how much an external fuel shock scales daily overhead.

### 2. Interactive "What-If" Risk Simulation
* Developed a dynamic **Fuel Price Selector Parameter Slider** within Power BI allowing operational leaders to test forward-looking scenarios manually (₹80 to ₹120/L).
* Wrote defensive DAX measures (`Projected Logistics Cost Override`) that dynamically recalculate and broadcast projected operational cost limits in real-time as the slider moves.

### 3. Linear Correlation Mapping
* Structured side-by-side analytical grids: A **Scatter Plot** mapping un-summarized daily data points with an automated trend line proving the linear cost trajectory, positioned directly next to a monthly baseline-vs-total cost line chart to visualize margin compression.

---

## 📂 Project Structure & Deliverables
* 🐍 [View Regression Modeling Code](operations_sensitivity.ipynb) — Opens your predictive Python notebook directly on GitHub.
* 🛠️ [Download Sensitivity Dashboard Layout (.pbix)](Logistics_Sensitivity_Model.pbix) — For testing the live interactive scenario slider framework.
