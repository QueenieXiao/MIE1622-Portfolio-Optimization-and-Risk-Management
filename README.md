# Portfolio Optimization & Risk Management

> **Developed and evaluated multiple portfolio construction strategies, including Equal Risk Contribution (ERC), Maximum Sharpe Ratio, Robust Mean-Variance Optimization, and Benchmark Tracking under normal and stressed market conditions.**

---

## Overview

Portfolio construction requires balancing expected return, diversification, and downside risk under uncertain market conditions.

This project implements and compares **nine portfolio allocation strategies**, ranging from classical mean-variance optimization to modern risk-based portfolio construction techniques. Performance is evaluated under three representative market environments:

* **Normal market (2024–2025)**
* **Global Financial Crisis (2008–2009)**
* **Volatile market (2022)**

The project investigates portfolio performance, robustness, drawdown behaviour, and dynamic asset allocation across different market regimes.

---

## Portfolio Strategies

Implemented portfolio construction strategies include:

* Buy and Hold
* Equally Weighted Portfolio
* Minimum Variance Portfolio
* Maximum Expected Return Portfolio
* Maximum Sharpe Ratio Portfolio
* Equal Risk Contribution (ERC)
* Leveraged Maximum Sharpe Portfolio
* Robust Mean-Variance Optimization
* Benchmark Tracking Portfolio

---

## Optimization Techniques

The project incorporates multiple quantitative investment techniques, including:

* Mean-Variance Optimization
* Equal Risk Contribution (ERC)
* Robust Optimization
* Maximum Sharpe Ratio
* Benchmark Tracking
* Dynamic Portfolio Rebalancing
* Transaction Cost Modelling

---

# Results

## Portfolio Performance (2024–2025)

<p align="center">
<img src="Xiangyin_Xiao_Code_and_Pictures_Assignment_2/2.1 Daily Portfolio Value (2024_2025).png" width="850">
</p>

The comparison under recent market conditions demonstrates the trade-off between return maximization and risk control. Risk-based portfolio construction methods achieve smoother performance while maintaining competitive returns.

---

## Stress Testing During the 2008–2009 Financial Crisis

<p align="center">
<img src="Xiangyin_Xiao_Code_and_Pictures_Assignment_2/3.1 Daily Portfolio Value (2008_2009).png" width="850">
</p>

Historical stress testing evaluates portfolio resilience during the Global Financial Crisis. Diversified strategies such as Equal Risk Contribution and Robust Optimization exhibit significantly stronger downside protection than return-maximizing portfolios.

---

## Portfolio Performance During the 2022 Market Downturn

<p align="center">
<img src="Xiangyin_Xiao_Code_and_Pictures_Assignment_2/4.1 Daily Portfolio Value (2022).png" width="850">
</p>

Evaluation under the volatile 2022 market further validates the robustness of diversified portfolio construction techniques under adverse market conditions.

---

## Dynamic Portfolio Allocation

<p align="center">
<img src="Xiangyin_Xiao_Code_and_Pictures_Assignment_2/4.3 Dynamic Portfolio Allocation (Strategy 8 - Robust).png" width="850">
</p>

Robust optimization dynamically adjusts portfolio weights in response to changing market conditions while maintaining diversified exposure and reducing excessive portfolio turnover.

---

## Key Findings

* Robust Mean-Variance Optimization achieves a strong balance between return and downside risk.
* Equal Risk Contribution effectively improves portfolio diversification.
* Maximum Expected Return portfolios generate higher returns but experience substantially larger drawdowns.
* Stress testing highlights the importance of diversification during severe market downturns.
* Dynamic portfolio rebalancing improves allocation stability across different market environments.

---

## Repository Structure

```text
.
├── portf_optim2.ipynb
├── MIE1622_Assignment_2_Report.pdf
├── README.md
├── .gitignore
├── adjclose_2008_2009.csv
├── adjclose_2022.csv
├── adjclose_2024_2025.csv
├── sp30_daily_weights_2008_2009.csv
├── sp30_daily_weights_2022.csv
├── sp30_daily_weights_2024_2025.csv
└── Xiangyin_Xiao_Code_and_Pictures_Assignment_2/
    ├── 2.1 Daily Portfolio Value (2024_2025).png
    ├── 3.1 Daily Portfolio Value (2008_2009).png
    ├── 4.1 Daily Portfolio Value (2022).png
    └── 4.3 Dynamic Portfolio Allocation (Strategy 8 - Robust).png
```

---

## Technologies

* Python
* NumPy
* Pandas
* SciPy
* Matplotlib
* Jupyter Notebook

---

## Skills Demonstrated

* Portfolio Optimization
* Risk Management
* Mean-Variance Optimization
* Robust Optimization
* Equal Risk Contribution (ERC)
* Benchmark Tracking
* Quantitative Finance
* Portfolio Analytics
* Financial Modeling
* Data Visualization

---

## Future Improvements

Potential extensions include:

* Black–Litterman portfolio optimization
* Risk parity portfolio construction
* Bayesian return estimation
* Multi-period portfolio optimization
* ESG-aware portfolio optimization

---

## Author

**Xiangyin (Queenie) Xiao**

Master of Engineering, University of Toronto

Interested in **Risk Analytics, Quantitative Finance, Portfolio Optimization, Actuarial Science, and Machine Learning**.
