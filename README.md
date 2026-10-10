# Hi, I'm Varad 👋

**Quant trading · Python · Systematic research**

I build and run algorithmic trading systems for gold (XAUUSD), FX and crypto. Most of 2026 has gone into one production system: data pipeline, strategies, backtesting, regime modelling and risk engineering, all in Python. I also trade prop-firm funded accounts under strict daily-loss and drawdown rules.

Open to **quant research, quant developer and trading roles**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Varad%20Bandekar-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/varad-bandekar-4654932a9)
[![Email](https://img.shields.io/badge/Email-varadbandekar22%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:varadbandekar22@gmail.com)

---

## ⭐ Featured: [Quant_Trading](https://github.com/vrd07/Quant_Trading)

A multi-strategy algorithmic trading system on MetaTrader 5, built to survive prop-firm risk rules.

- **13 strategies**: Kalman regime, momentum, VWAP mean-reversion, structure-break retest, SMC order blocks, calendar drifts, volatility squeeze and more, each regime-, symbol- and session-gated
- **Data pipeline**: ticks → bars across 5 timeframes → indicators and features
- **Backtesting**: 2.5 years of Dukascopy history under an identical per-trade risk budget, so strategies are compared fairly
- **ML regime classifier**: Random Forest + Markov-chain smoother + performance feedback, re-weighting strategies nightly across TREND / RANGE / VOLATILE
- **Risk engine**: 16 checks with veto power over every order (kill switch, circuit breaker, daily-loss budget, drawdown, exposure, per-trade risk)
- **Documentation**: a 15,500-word research paper covering every subsystem

| Strategy (XAUUSD, Jan 2025 – Mar 2026) | Return | Profit factor | Max DD | Trades |
|---|---:|---:|---:|---:|
| Kalman Regime | +4.62% | 1.15 | −2.74% | 1,252 |
| Momentum | +4.68% | 1.10 | −5.33% | 2,023 |
| Breakout | +1.23% | 1.02 | −5.60% | 907 |
| Mini Medallion v1 | −3.44% | 0.85 | −4.07% | 668 |

*Mini Medallion v1 was disabled after this run, retuned, and re-enabled only after holding up on a fresh 12-month sample (51% win rate, PF 1.31).*

---

## 🧰 Toolkit

**Languages & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**Quant**

![Backtesting](https://img.shields.io/badge/Backtesting-1F2937?style=for-the-badge)
![Regime Classification](https://img.shields.io/badge/Regime%20Classification-1F2937?style=for-the-badge)
![Kalman Filters](https://img.shields.io/badge/Kalman%20Filters-1F2937?style=for-the-badge)
![Risk & Drawdown Modelling](https://img.shields.io/badge/Risk%20%26%20Drawdown%20Modelling-1F2937?style=for-the-badge)
![Performance Analytics](https://img.shields.io/badge/Performance%20Analytics-1F2937?style=for-the-badge)

**Infra**

![MetaTrader 5](https://img.shields.io/badge/MetaTrader%205-0B5CAB?style=for-the-badge)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Certifications**

![eJPT](https://img.shields.io/badge/eJPT-INE-C8102E?style=for-the-badge)
![Google Cybersecurity](https://img.shields.io/badge/Google-Cybersecurity%20Certificate-4285F4?style=for-the-badge&logo=google&logoColor=white)

## 📂 Other projects

- [**Ai_Tutor**](https://github.com/vrd07/Ai_Tutor): FastAPI + Streamlit tutoring app with SQLite and local LLMs (Mixtral, DeepSeek via Ollama)
- [**PentestTool_for_macOs**](https://github.com/vrd07/PentestTool_for_macOs) and [**Port_scanner**](https://github.com/vrd07/Port_scanner): Bash tools for service enumeration and port scanning

## 🎓 Education

- MBA, Indira Gandhi National Open University (in progress)
- BCA, Gogte College of Commerce, Belagavi · CGPA 8.6
</div>

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api?username=vrd07&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&cache_seconds=86400" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=vrd07&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=vrd07&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

## 🎯 What's Next

```python
class CurrentGoals:
    learning = ["Quantitative Finance", "Statistical Modelling & ML", "Market Microstructure"]
    building = ["Algorithmic Trading Systems", "Backtesting & Risk Engines", "Regime Detection Models"]
    seeking = "Quant Researcher / Quant Developer / Trading Opportunities"
```

## 🤝 Let's Connect

I'm always open to collaborating on security projects, CTF teams, open-source security tools, or trading strategy research. If you're working on something interesting, let's talk.

**Looking for:** Security Engineer roles · Open-source collaborations · CTF team opportunities · Quant trading discussions

---
<div align="center">
*"Security is not a product, but a process." — Bruce Schneier*

![Profile Views](https://komarev.com/ghpvc/?username=vrd07&color=blue&style=flat-square)
