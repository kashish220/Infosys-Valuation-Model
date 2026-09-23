# 📊 Infosys Limited — Financial Valuation Model

## 🏢 Project Overview

This project presents a comprehensive financial modeling and valuation analysis of **Infosys Limited**, a global leader in information technology, consulting, and digital services.

The model has been developed in Microsoft Excel to analyze the company's historical financial performance, forecast future financial statements, evaluate operating and financial drivers, and estimate the intrinsic value of Infosys using fundamental valuation methodologies.

The project combines **Financial Statement Analysis, Forecasting, DCF Valuation, Comparable Company Analysis, Ratio Analysis, Cost of Capital Analysis, and Sensitivity Analysis** into an integrated financial model.

---

## 🎯 Project Objective

The primary objective of this project is to build a structured financial model that can be used to:

- 📈 Analyze Infosys' historical financial performance
- 🔮 Forecast future revenues, costs, profits, and balance sheet items
- 💰 Estimate the company's intrinsic value using a Discounted Cash Flow approach
- 🏦 Calculate Cost of Equity using CAPM
- 📊 Calculate Weighted Average Cost of Capital (WACC)
- 🧮 Perform Comparable Company Valuation
- 📉 Analyze key financial and operating ratios
- 🌍 Analyze revenue performance across different geographies
- 💵 Estimate Unlevered Free Cash Flow to Firm (FCFF)
- 🔍 Perform sensitivity analysis on key valuation assumptions
- 📌 Evaluate the impact of changes in discount rate and terminal growth rate

---

# 📚 Model Structure

The workbook is organized into multiple sections covering the complete financial modeling process.

### 📥 1. Input & Assumptions

The model begins with a dedicated assumptions section containing:

- Company information
- Industry and sector information
- Share capital information
- Current market price
- Market capitalization
- Perpetual growth rate
- Bond yield assumptions
- Interest rate assumptions
- Revenue growth assumptions
- Cost assumptions
- Tax rate assumptions
- Forecasting assumptions
- Bull, Base, and Bear case scenarios

These assumptions are linked throughout the model to maintain consistency and allow the model to be updated efficiently.

---

### 📊 2. Historical Financial Analysis

Historical financial data is incorporated to understand the company's past performance.

The model includes:

- Profit & Loss Statement
- Balance Sheet
- Cash Flow Statement
- Common-size financial statements
- Historical growth analysis
- Revenue analysis
- Cost analysis
- Working capital analysis
- Financial ratio analysis

Historical information is used as the foundation for developing future projections.

---

### 📈 3. Revenue Build-up

The Revenue Build-up section analyzes Infosys' revenue performance and develops revenue forecasts.

Key areas include:

- Revenue from operations
- Other operating revenue
- Other income
- Year-over-Year revenue growth
- Revenue by geography
- North America
- Europe
- India
- Rest of the World
- IT sector growth assumptions
- Revenue segment growth assumptions

Revenue forecasts are developed using historical trends and scenario-based assumptions.

---

### 💸 4. Cost Build-up

The Cost Build-up section analyzes major operating expenses and develops assumptions for future periods.

Key components include:

- Employee benefit expenses
- Operating expenses
- Cost-to-revenue ratios
- Finance costs
- Effective tax rate
- Historical cost trends
- Forecast cost assumptions

Historical averages are used as a basis for projecting selected cost components into the forecast period.

---

### 🏭 5. Fixed Assets & Financial Statement Analysis

The model includes detailed analysis of:

- Fixed assets
- Intangible assets
- Right-of-use assets
- Capital Work-in-Progress
- Depreciation & amortization
- Asset additions
- Asset disposals

These assumptions are incorporated into the projected financial statements.

---

### 🔄 6. Working Capital Analysis

The Working Capital section analyzes operating working capital requirements.

Key components include:

- Trade receivables
- Trade payables
- Working capital movements
- Historical working capital ratios
- Forecast working capital requirements

Historical relationships between working capital items and revenue are used to support future projections.

---

### 📑 7. Financial Statements

The model includes projected financial statements covering the forecast period.

#### Income Statement
Includes:

- Revenue
- Operating expenses
- Employee costs
- EBITDA
- EBIT
- Depreciation & amortization
- Finance costs
- Profit before tax
- Tax
- Net profit

#### Balance Sheet
Includes:

- Assets
- Liabilities
- Equity
- Cash & cash equivalents
- Working capital items
- Fixed assets
- Other balance sheet items

#### Cash Flow Statement
Includes:

- Operating cash flows
- Investing cash flows
- Financing cash flows
- Capital expenditure
- Depreciation
- Working capital movements
- Free cash flow components

---

# 📊 8. Ratio Analysis

The model includes financial ratio analysis to evaluate the company's:

### Profitability
- EBITDA Margin
- EBIT Margin
- Net Profit Margin
- Return on Equity
- Return on Capital Employed

### Liquidity
- Current Ratio
- Quick Ratio

### Efficiency
- Receivable Days
- Payable Days
- Working Capital Metrics

### Leverage
- Debt-related ratios
- Interest-related metrics

The ratio analysis helps evaluate historical financial performance and provides supporting information for forecasting assumptions.

---

# 📈 9. Equity Beta & Market Data

The model incorporates market data to calculate the company's equity beta and support the Cost of Equity calculation.

The analysis includes:

- Historical share price data
- Market index data
- Stock returns
- Market returns
- Beta calculation
- Risk-free rate
- Market return
- Equity Risk Premium

The calculated beta is subsequently used in the CAPM framework.

---

# 🧮 10. Cost of Equity — CAPM

The Cost of Equity is calculated using the **Capital Asset Pricing Model (CAPM)**.

### Formula:

**Cost of Equity = Risk-Free Rate + Beta × Equity Risk Premium**

Where:

- Risk-Free Rate = Government bond yield assumption
- Beta = Equity beta calculated from market data
- Equity Risk Premium = Market Return − Risk-Free Rate

This Cost of Equity is then incorporated into the WACC calculation.

---

# 🏦 11. WACC — Weighted Average Cost of Capital

The model calculates WACC using the company's capital structure.

The calculation considers:

- Cost of Equity
- Cost of Debt
- After-tax Cost of Debt
- Equity Value
- Debt Value
- Capital Structure Weightages

### Formula:

**WACC = (Cost of Equity × Equity Weight) + (After-tax Cost of Debt × Debt Weight)**

WACC is subsequently used as the discount rate in the DCF valuation.

---

# 💰 12. DCF Valuation

The Discounted Cash Flow methodology is used to estimate the intrinsic value of Infosys.

The DCF model calculates:

- EBIT
- Tax on EBIT
- Depreciation & Amortization
- Capital Expenditure
- Change in Working Capital
- Unlevered FCFF
- WACC
- Terminal Value
- Present Value of Forecast Cash Flows
- Present Value of Terminal Value
- Enterprise Value
- Equity Value
- Intrinsic Value per Share

### Unlevered FCFF

The model calculates Free Cash Flow to Firm using:

**FCFF = EBIT − Tax on EBIT + D&A − Capex − Change in Working Capital**

The projected FCFF is discounted using WACC to arrive at the present value of future cash flows.

---

# ♾️ 13. Terminal Value

Terminal Value is calculated using the perpetual growth method.

### Formula:

**Terminal Value = Final Year FCFF × (1 + g) / (WACC − g)**

Where:

- FCFF = Final forecast year FCFF
- g = Perpetual Growth Rate
- WACC = Weighted Average Cost of Capital

The Terminal Value is then discounted to its present value.

---

# 🔍 14. Sensitivity Analysis

A sensitivity analysis is included to understand how changes in key valuation assumptions affect the estimated intrinsic value per share.

The model evaluates changes in:

- 📉 Discount Rate / WACC
- 📈 Terminal Growth Rate

This creates a valuation sensitivity matrix that helps assess how sensitive the DCF valuation is to changes in the underlying assumptions.

---

# 🏢 15. Comparable Company Analysis

The model also includes a Comparable Company Valuation approach.

Selected peer companies include:

- Tata Consultancy Services (TCS)
- HCL Technologies
- Wipro
- LTIMindtree
- Tech Mahindra
- Persistent Systems

The comparable company analysis uses market and financial information to calculate valuation multiples.

### Key Multiples

- EV / Revenue
- EV / EBITDA
- P / E

The model calculates comparable-company valuation metrics and applies relevant multiples to Infosys' financial metrics.

---

# 🛠️ Tools & Techniques Used

### 💻 Tools

- Microsoft Excel
- Advanced Excel Formulas
- Financial Modeling
- Data Analysis
- Financial Research

### 📚 Financial Techniques

- Financial Statement Analysis
- Ratio Analysis
- Revenue Forecasting
- Cost Forecasting
- Working Capital Forecasting
- CAPM
- Beta Analysis
- WACC
- DCF Valuation
- FCFF Valuation
- Comparable Company Analysis
- EV/Revenue
- EV/EBITDA
- P/E Valuation
- Sensitivity Analysis
- Scenario Analysis

---

# 📂 Workbook Structure

The Excel model contains the following major worksheets:

| Sheet | Purpose |
|---|---|
| 📑 Assumptions | Key company and valuation assumptions |
| 📊 P&L Input | Historical P&L inputs |
| 🏦 BS Input | Historical Balance Sheet inputs |
| 💵 CF Input | Historical Cash Flow inputs |
| 📐 Common Sizing | Common-size analysis |
| 📈 Revenue Buildup | Revenue forecasting |
| 💸 Cost Buildup | Cost forecasting |
| 🏭 FAS | Fixed asset analysis |
| 🔄 Working Capital | Working capital forecasting |
| 📑 Income Statement | Historical & projected income statement |
| 🏦 Balance Sheet | Historical & projected balance sheet |
| 💰 Cash Flows | Cash flow analysis |
| 📊 Ratio Analysis | Financial ratio analysis |
| 📋 Summary | Model summary |
| 📈 Charts | Visual analysis |
| 📉 Equity Beta | Beta calculation |
| 📊 Market Data | Market price and index data |
| 🏢 Comps Data | Comparable company data |
| 📊 COMPS | Comparable valuation |
| 💰 DCF Valuation | DCF, FCFF & sensitivity analysis |

---

# 🎓 Key Learning Outcomes

Through this project, I developed practical understanding of:

- Building an integrated financial model in Excel
- Linking multiple financial statements
- Forecasting financial statements using historical trends
- Developing revenue and cost assumptions
- Understanding working capital drivers
- Calculating Beta using market data
- Applying CAPM to calculate Cost of Equity
- Calculating WACC
- Building a DCF valuation model
- Calculating FCFF and Terminal Value
- Performing Comparable Company Analysis
- Using valuation multiples
- Conducting sensitivity analysis
- Structuring a professional equity research valuation model

---

# 📌 Company Information

**Company:** Infosys Limited  
**Sector:** Information Technology  
**Industry:** Computers - Software & Consulting  
**Ticker:** INFY  
**Exchange:** NSE / BSE  
**Website:** https://www.infosys.com

---

# ⚠️ Disclaimer

This financial model has been prepared for **educational, analytical, and academic purposes only**.

The assumptions, forecasts, valuation outputs, and analysis presented in this project are based on the data and assumptions incorporated in the model and should not be considered investment advice or a recommendation to buy or sell any security.

---

## 👩‍💻 Project Created By

**Kashish**

Financial Analysis | Financial Modeling | Equity Research

📊 Financial Modeling  
📈 Equity Research  
💰 Valuation  
📑 Financial Statement Analysis  
💻 Advanced Excel
