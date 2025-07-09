# capstone-project-2025
# 🚗 Dynamic Pricing for Urban Parking Lots
**Summer Analytics 2025 – Capstone Project**

This project implements an intelligent, data-driven dynamic pricing engine for urban parking lots, developed as part of the Summer Analytics 2025 challenge hosted by CnA Club × Pathway.

---

## 📌 Objective

Design a real-time pricing model for 14 parking lots based on:
- **Occupancy patterns**
- **Queue lengths**
- **Traffic conditions**
- **Special days**
- **Vehicle type**
- **Competitor pricing (location-aware)**

Prices start at a base value of `$10` and should be:
- **Realistic and explainable**
- **Smoothly updated over time**
- **Responsive to demand and competition**

---

## 🏗️ Models Implemented

### 🧮 Model 1: Baseline Linear Model
Price increases linearly with occupancy:

### 📈 Model 2: Demand-Based Price Function
Price responds to computed demand:

### 🧭 Model 3: Competitive Pricing (Location-Aware)
- Computes distance to nearby lots using latitude & longitude
- Adjusts prices based on nearby occupancy and competitor prices
- Optionally suggests rerouting vehicles

---

## 🛠️ Technologies Used

- **Python** with `pandas`, `numpy`
- **Pathway** for real-time data simulation
- **Bokeh** for interactive visualization
- **Google Colab** for development & deployment

---

## 🧪 Dataset

- Data collected over **73 days**, 18 time points/day
- Features: `Occupancy`, `Capacity`, `VehicleType`, `QueueLength`, `TrafficConditionNearby`, `IsSpecialDay`, `Latitude`, `Longitude`

---

## 🧰 How to Run

1. Open `Dynamic_Pricing_SA2025.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Run all cells sequentially
3. Modify model parameters (`α`, `β`, `λ`, etc.) to experiment
4. Bokeh visualizations will render real-time pricing trends

---

## 📊 Visualizations

Includes:
- Real-time price tracking
- Competitor comparisons
- Demand heatmaps (optional)

---

## 📄 Report Section

The notebook includes:
- Model assumptions
- Justification of parameters
- Observed behavior across different scenarios

---

## 🔗 References

- [Pathway: Real-time data platform](https://pathway.com)
- [Summer Analytics 2025](https://www.caciitg.com/sa/course25/)

---

## 📬 Contact

For any questions or collaboration requests, feel free to reach out!

