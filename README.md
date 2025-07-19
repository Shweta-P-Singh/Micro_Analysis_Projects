# Micro_Analysis_Projects
Micro data analysis portfolio 
# Micro-Analysis: UK Inflation Trends
This project performs a comparative analysis of two financial instruments:
- `^FTSE` (FTSE100 Index)
- `WISE.L` (Wise Plc)
Using Python, we assess daily returns, open vs. close behaviour, and rolling volatility for July 2023.
## Objectives

- Compare daily percentage returns between the FTSE100 and WISE.L
- Contrast open vs close return behaviour for intraday vs overnight insights
- Visualise rolling volatility (30-day, annualised)
- Use `yfinance`, `pandas`, and `seaborn` to present insights

## 🔬 Key Findings
### Daily Returns
- WISE.L shows **greater volatility and return spikes**, reflecting sensitivity to market news.
- FTSE100 provides **stable, modest returns** across the month.

### Open vs Close Analysis
- WISE.L’s open returns often diverge from close, indicating strong **overnight effects**.
- FTSE100 shows **tight alignment**, consistent with a passive index.

### 30-Day Rolling Volatility
- WISE.L peaks at **43% annualised volatility**.
- FTSE100 stays between **10–18%**, confirming its lower-risk profile.
## 📦 Tools Used
- yfinance – download stock market data
- pandas – data transformation
- seaborn – visualisation
- matplotlib – plot rendering
## 🔄 Future Work
- Add technical indicators (MACD, RSI)
- Compare more tickers (FTSE250, S&P500)
- Build a Streamlit app for real-time interaction

---

### 👤 Author: Shweta Singh
📅 Project Date: July 2023  
----------------------------------------------------------------------------------------------------------------------
