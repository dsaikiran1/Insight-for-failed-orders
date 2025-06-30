# 📉 Insights from Failed Orders – Data Science Challenge

This project investigates failed ride orders from **Gett** (formerly GetTaxi), analyzed as part of a StrataScratch take‑home assignment used in their data science recruitment process ---

## 🚗 Context

Gett is a Ground Transportation Management (GTM) platform. When a customer places an order, the system attempts to match it with available drivers. This analysis focuses on **orders that did not complete successfully**—i.e. the customer never received a ride :contentReference[oaicite:2]{index=2}.

---
## Dataset
https://platform.stratascratch.com/data-projects/insights-failed-orders
## 🎯 Objectives

1. **Failure Reason Distribution**:
   - Classify failures into:
     - Cancelled Before Driver Assignment  
     - Cancelled After Driver Assignment  
     - System Rejected  
   - Determine which category has the highest count.

2. **Hourly Failure Trends**:
   - Visualize when failures occur most frequently.
   - Identify hours with abnormal failure spikes and possible causes.

3. **Cancellation Timing**:
   - Compute average cancellation times, segmented by driver-assigned status and hour.
   - Inspect and handle outliers.

4. **ETA Analysis**:
   - Examine how average ETA varies by hour, and interpret operational implications.

5. **BONUS – Geospatial Analysis**:
   - Using H3 hexagons and Folium, determine how many hexes (size 8) contain 80% of failed orders.
   - Visualize hexes colored by failure count on an interactive map.

---

## 🧰 Tools & Technologies

- **Languages**: Python 3.x
- **Libraries**:
  - Data wrangling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `folium`, `h3`
  - Mapping: `branca` for color scales
- **Environment**:
  - Jupyter Notebook for exploratory work
  - `requirements.txt` or conda environment available

---
