# Geopolitical Event Impact Analysis

This project analyzes the impact of major **geopolitical events** (Brexit, COVID-19, Russia–Ukraine War, etc.) on **global financial markets** such as the **S&P 500, Crude Oil, Gold, Bitcoin, and USD/INR**.  

It performs **event-window analysis** to see how prices and volatility behave before and after key events.  

---

## ✨ Features  

✅ **Event-Window Analysis** → Compare returns ±5 and ±10 days around each event  
✅ **Volatility Study** → Check how market volatility spikes after events  
✅ **Heatmap Visualization** → See which assets react the most  
✅ **Monte Carlo Simulation** → Simulate future event risks  

---

## 🛠 Tech Stack  

- **Python**  
- **pandas** → data manipulation  
- **numpy** → calculations  
- **yfinance** → fetching market data  
- **matplotlib & seaborn** → visualizations  

---

## 📊 Events & Assets  

### Geopolitical Events  
- Brexit Vote (2016-06-23)  
- COVID-19 Declared Pandemic (2020-03-11)  
- 2020 US Election (2020-11-03)  
- Russia–Ukraine War Start (2022-02-24)  
- Israel–Hamas War (2023-10-07)  
- Taiwan–China Tensions (2024-01-15)  

### Market Assets  
- S&P 500 (^GSPC)  
- Crude Oil (CL=F)  
- Gold (GC=F)  
- Bitcoin (BTC-USD)  
- USD/INR (INR=X)  

---

## 🚀 How to Run  

1️⃣ Clone this repository  
```bash
git clone https://github.com/your-username/geopolitical-event-impact-analysis.git
cd geopolitical-event-impact-analysis

Install dependencies: pip install -r requirements.txt

Run the notebook: jupyter notebook Geopolitical_Event_Impact_Analysis.ipynb
