# 🎲 Monte Carlo Simulation Analysis

## 📊 Overview
This project contains a data-driven Monte Carlo Simulation designed to forecast operational performance and financial outcomes across four distinct business scenarios. By using random probability distributions, the model predicts outcomes for supply chain demands, service queues, financial profit & loss, and equipment maintenance. 

## 📁 Dataset & Scenarios
The simulation is divided into four main sheets, each representing a unique analytical case:

1. **Milk Profit Forecasting**
   * **Purpose:** Simulates daily demand vs. supply for milk to optimize inventory and calculate profitability.
   * **Key Data Points:** Quantity, Demand, Sold, Remaining, Total Revenue, Cost, and Profit.
2. **Car Service Remaining Forecast**
   * **Purpose:** Forecasts the queue of cars in a service center by simulating daily arrivals and service completion rates.
   * **Key Data Points:** Cars Arrived, Car Servicing Completed, and Remaining (Queue).
3. **Profit & Loss Forecasting**
   * **Purpose:** Estimates financial viability by running probabilities on variable variables: Variable Cost, Fixed Cost, Selling Price, and Output (Volume).
   * **Key Data Points:** Batch runs and randomized revenue/cost factors.
4. **Tuscon Mills (Maintenance & Downtime)**
   * **Purpose:** Models machine breakdown frequencies and repair times to estimate total operational downtime.
   * **Key Data Points:** Time Between Breakdowns, Service Time, Waiting Time, and Total Downtime.

---

## 📈 Key DAX Measures
If you are importing this data into **Power BI** or **Excel Power Pivot**, you can use the following DAX (Data Analysis Expressions) formulas to create dynamic calculations for your dashboard:

### 1. Milk Profitability
```dax
// Calculate overall profit across all simulated days
Total Milk Profit = SUM('Milk Profit forecasting'[Profit])

// Calculate lost revenue opportunities when Demand exceeds Supply
Lost Revenue = SUM('Milk Profit forecasting'[Revenue(Demand<Supply)]) ## ### & (Area (Cars (Clustered (Gantt (Histogram (Tuscon (`RAND()`) (in * **Downtime **Milk **P&L **Power **Service *Category:* *Columns:* *Insight:* *Line:* *Values:* *X-Axis:* *Y-Axis:* + --- / // 1. 2. 3. Average Avg BI**, Bar):** Bins Breakdown Car Cars Center Chart Chart):** Charts Column Completed]) DAX Days Demand Distribution Downtime Efficiency Equipment Excel) Forecasti'[Car Forecasti'[Remaining]) Frequency Highlights Hit How Identifies Instance Line Mills'[Downtime]) Mills'[Waiting Mills) Number Occurrence Open Profit Quantity Queue Queue) Ramaining Random Recommended Remaining Repair Scenario Service Serviced="SUM('Car" Servicing Shows Stacked Supply Time="Total" Time]) To Total Tracking Use Visualizations Visualizes Waiting `.xlsx` `F9` ``` ```dax a above. across all an and apply are at backlog based between breakdowns build buildup cars caused charts connect correlation dashboard data, day delays. determine distributions downtime end events experienced file following for from generate generation highly impactful in inventory likely limits. maintenance margin matching measures, month most needs. new of on operational or outlined over peak probability profit profitability. random randomized range recalculate recommended: repairs review scenario. serviced severe simulated simulation staffing start successfully suggested the this to variables variables. visualize, vs. which workbook 📊 🚀>