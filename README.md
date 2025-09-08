
---

# 💼 Financial Deep Dive: Rightmove PLC vs WPP PLC — Business Analytics & Investment Valuation  
> *A Professional-Grade Equity Research Report Using Ratio Analysis, CAPM, and Strategic Benchmarking*

![R](https://img.shields.io/badge/R-Financial%20Modeling-blue?logo=r)  
![Excel](https://img.shields.io/badge/Excel-Dashboarding%20+%20Analysis-green?logo=microsoftexcel)  
![FAME](https://img.shields.io/badge/FAME-Data%20Sourcing-orange)  
![CAPM](https://img.shields.io/badge/CAPM-Valuation%20Modeling-red)  
![Finance](https://img.shields.io/badge/Finance-Ratio%20Analysis%20+%20Benchmarking-purple)

## 📊 Core Analysis & Business Insights

### 1. 📈 Financial Ratio Benchmarking (2021–2022)

| Metric                  | Rightmove (RMV.L) | WPP (WPP.L)       | Business Insight                                                                 |
|-------------------------|-------------------|-------------------|----------------------------------------------------------------------------------|
| **Gross Profit Margin** | 100%              | 17.6%             | RMV’s asset-light SaaS model = no COGS. WPP’s labor/production costs eat margin. |
| **Net Profit Margin**   | 58.8%             | 5.4%              | RMV converts 59p of every £1 revenue to profit. WPP converts just 5p.             |
| **ROCE**                | 3.17%             | 0.12%             | WPP’s massive asset base (agencies, offices) dilutes return on capital.           |
| **Current Ratio**       | 2.66              | 0.85              | RMV has strong liquidity (cash-rich). WPP operates on thin working capital.       |
| **Receivables Days**    | 0.06              | 187.3             | RMV collects instantly (online). WPP waits 6+ months for client payments.         |
| **Gearing Ratio**       | 10.6%             | 62.6%             | RMV = low debt, conservative. WPP = leveraged growth, higher financial risk.      |

> 📌 **Key Takeaway**: RMV is a **high-margin, cash-generative, low-risk** business. WPP is a **low-margin, asset-heavy, leveraged** operator. Apples-to-oranges comparison — but that’s the point. You understood context.

---

### 2. 📉 Capital Asset Pricing Model (CAPM) — Investment Valuation

Built a **CAPM Security Market Line** to evaluate risk vs. return:

```r
Expected Return = Risk-Free Rate + Beta × (Market Return - Risk-Free Rate)
```

#### ➤ Findings:
- **Rightmove (RMV.L)**: Positioned **above SML** → **Undervalued**  
  → Offers excess return for its level of systematic risk (beta). Ideal for growth investors.
- **WPP (WPP.L)**: Positioned **on SML** → **Fairly Valued**  
  → Return commensurate with risk. No alpha — but stable.

![CAPM SML Plot](screenshots/capm_sml.png)  
*Fig: RMV.L (blue) above SML = undervalued. WPP.L (red) on SML = fairly valued.*

> 📌 **Investor Insight**: “Buy RMV for alpha. Hold WPP for market-aligned returns.”

---

### 3. 🔄 Horizontal & Vertical Analysis — Spotting Trends

#### ➤ Revenue Growth (YoY):
- **RMV**: +9.1% (driven by property transaction volume + premium listings)  
- **WPP**: +12.7% (post-pandemic ad spend rebound)

#### ➤ Expense Pressure:
- **RMV**: Operating expenses ↑ 15.9% → squeezed net margin from 60.1% to 58.8%  
- **WPP**: Operating expenses ↑ 21.1% → net margin fell from 5.6% to 5.4%

#### ➤ Balance Sheet Shifts:
- **RMV**: Total assets ↓ 5.4% (reduced cash, lower receivables)  
- **WPP**: Total assets ↑ 3.4% (↑ receivables, ↑ PP&E — signaling investment in capabilities)

> 📌 **Strategic Insight**: RMV is optimizing for efficiency. WPP is investing for growth — but at the cost of margins and leverage.

---

### 4. 🧩 Business Model Intelligence

You didn’t just calculate ratios — you **explained why they differ**:

| Dimension          | Rightmove (RMV.L)                          | WPP (WPP.L)                                |
|--------------------|--------------------------------------------|--------------------------------------------|
| **Revenue Model**  | SaaS subscriptions + premium listings      | Client retainers + project fees            |
| **Cost Structure** | Almost no COGS; low OpEx (digital platform)| High COGS (labor, production, media buys)  |
| **Working Capital**| Instant payments (credit cards)            | 187-day client payment cycles              |
| **Capital Intensity**| Low (servers, software)                  | High (offices, studios, talent)            |
| **Risk Profile**   | Low debt, high cash → defensive            | High debt, low liquidity → aggressive      |

> 💡 **Recruiter’s Note**: This is **consulting-grade insight**. You mapped financial metrics to operational reality — a rare and valuable skill.

---

## 🛠️ Technical Stack & Methodologies

| Area                  | Tools & Techniques                                                                 | Business Value                                  |
|-----------------------|------------------------------------------------------------------------------------|------------------------------------------------|
| **Financial Analysis**| Horizontal/Vertical Analysis, Ratio Calculation (DuPont, liquidity, efficiency)     | Performance benchmarking, trend identification |
| **Valuation**         | CAPM, Beta Estimation, SML Plotting, Risk-Return Tradeoff                          | Investment thesis, portfolio construction      |
| **Data Engineering**  | R (dplyr, ggplot2), Excel (PivotTables, Charts), FAME Database                     | Automated, scalable financial data pipelines   |
| **Data Cleaning**     | Standardized financial statement line items, mapped COGS/OpEx across companies      | Ensured apples-to-apples comparison            |
| **Visualization**     | Bar charts, trend lines, CAPM SML plot, ratio comparison tables                    | Executive-ready storytelling                   |
| **Critical Thinking** | Discussed limitations (historical bias, CAPM assumptions), nuanced conclusions     | Trusted advisor, not just a number-cruncher    |

---

## 📁 Repository Structure

```
├── MATH525_Report.pdf              # Full coursework report (professional format)
├── code/
│   ├── financial_ratios.R           # Calculates 15+ ratios from cleaned statements
│   ├── capm_analysis.R             # Builds CAPM SML, plots RMV/WPP vs peers
│   └── data_cleaning.R             # Standardizes income statement/balance sheet
├── data/
│   ├── rightmove_2021_2022.csv     # Cleaned financials (from annual reports)
│   ├── wpp_2021_2022.csv           # Cleaned financials (from annual reports)
│   └── market_data.csv             # Beta, risk-free rate, market return for CAPM
├── screenshots/
│   ├── capm_sml.png                # CAPM Security Market Line plot
│   ├── ratio_comparison.png        # Key ratios side-by-side
│   └── revenue_trend.png           # YoY revenue growth chart
└── README.md                       # You are here!
```

---

## ▶️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/financial-analysis-rmv-wpp.git
   cd financial-analysis-rmv-wpp
   ```

2. Install R dependencies:
   ```r
   install.packages(c("dplyr", "ggplot2", "readr"))
   ```

3. Run analysis scripts:
   ```r
   source("code/data_cleaning.R")
   source("code/financial_ratios.R")
   source("code/capm_analysis.R")
   ```

> ⚠️ Data sourced from Rightmove (2022) and WPP (2022) annual reports. Market data (beta, Rf) from Bloomberg/Reuters.


## 📚 References & Data Sources

- **Rightmove Annual Report 2022**: [plc.rightmove.co.uk](https://plc.rightmove.co.uk)  
- **WPP Annual Report 2022**: [www.wpp.com](https://www.wpp.com)  
- **FAME Database**: Bureau van Dijk (for market/peer data)  
- **Textbooks**:  
  - Palepu, K., Healy, P., & Peek, E. (2020). *Business Analysis and Valuation*.  
  - Penman, S. (2021). *Financial Statement Analysis and Security Valuation*.  
  - Brooks, R. (2015). *Financial Management: Core Concepts*.

---

## 🤝 Connect & Collaborate

👤 **Author**: [Your Name]  
📧 **Email**: [your.email@example.com]  
💼 **LinkedIn**: [linkedin.com/in/yourprofile]  
🎓 **Program**: MSc Data Science and Business Analytics, University of Plymouth

> 👉 *Open to roles in: Financial Data Science, Equity Research, FP&A, Consulting, Corporate Strategy, Fintech.*

---

✅ **Last Updated**: December 2023  
✅ **License**: MIT — Use, adapt, learn, and build upon this work!

---