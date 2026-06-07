# 3-STATEMENT-MODEL

📊 3-Statement Financial Model — Built from Scratch
A fully integrated, from-scratch financial model linking the Income Statement, Balance Sheet, and Statement of Cash Flows — built in Microsoft Excel with a dedicated Fixed Assets schedule and assumption-driven projections across a 5-year period (FY2022–FY2026).

📌 Project Overview
This model simulates the financials of a small business (lemonade/beverage company) and demonstrates the complete mechanics of a 3-statement model — how net income flows into retained earnings, how CapEx feeds depreciation, how working capital changes tie into cash flow, and how the balance sheet balances at every period.
The model is structured around a historical anchor year (FY2021) and five projected years (FY2022–FY2026), with all projections driven by clearly labeled assumptions.

📁 Model Structure
SheetContentsIncome StatementRevenue → Gross Profit → EBITDA → EBIT → EBT → Net IncomeBalance SheetCurrent Assets, Fixed Assets, Liabilities, Equity — balances to zero every yearStatement of Cash FlowsOperating, Investing, and Financing activities; Net Cash FlowFixed Assets ScheduleAsset-by-asset CapEx tracking and straight-line depreciation by useful life

🧱 Income Statement
Coverage: FY2022 – FY2026

Revenue build: Gross Revenue → Discounts → Net Revenue
COGS breakdown: Raw Materials, Fulfillment, Transaction Fees → Total COGS
Profitability cascade: Gross Profit → EBITDA → EBIT → EBT → Net Income
Gross Profit Margin held consistently at ~58.9% across the projection period
Net Income grows from ~$1,685 (FY2022) to ~$9,263 (FY2026), reflecting operational leverage
Interest expense linked to the debt schedule on the Balance Sheet
Tax applied as a % of EBT


🏦 Balance Sheet
Coverage: FY2021 (historical) – FY2026

Assets: Cash (driven by CF statement), Accounts Receivable, Net Fixed Assets (from Fixed Assets schedule)
Liabilities: Accounts Payable, Deferred Revenue, Long-term Debt
Equity: Common Stock + Retained Earnings (prior period RE + Net Income)
Balance Check row confirms $0 difference (Assets = Liabilities + Equity) in every period

Key dynamics:

Cash driven entirely by the net cash flow from the Statement of Cash Flows
Accounts Receivable and Payable modeled as days-based assumptions
Debt decreases via repayments except for a new borrowing of $5,000 in FY2024


💵 Statement of Cash Flows
Coverage: FY2022 – FY2026 | Indirect method
Operating Activities:

Starts with Net Income (linked from IS)
Adds back Depreciation & Amortization (non-cash charge)
Adjusts for changes in Working Capital: Accounts Receivable, Accounts Payable, Deferred Revenue

Investing Activities:

CapEx outflows: $14,000 (FY2022), $5,000 (FY2025)
No proceeds from asset sales in projection period

Financing Activities:

Scheduled debt repayments of $500–$750/year
New borrowing of $5,000 in FY2024 to fund CapEx

Net Cash Flow feeds directly into the Balance Sheet Cash line

🔧 Fixed Assets Schedule
Three assets tracked individually with straight-line depreciation:
AssetCostUseful LifeAnnual D&ALemon Crusher$5,0003 years$1,667Ice Machine$3,0007 years$429Refrigerator$6,0007 years$857Existing Equipment——$2,000/yr (until FY2025)

Total D&A rolls up and links into both the Income Statement (EBITDA → EBIT) and the Cash Flow Statement (non-cash add-back)
A second Lemon Crusher purchased in FY2025 for $5,000 (asset replacement cycle modeled)


📐 Modeling Mechanics
Linkages (the 3-statement integration)
Net Income (IS) ──────────────────────→ Retained Earnings (BS)
Net Income (IS) ──────────────────────→ Operating Cash Flow (CFS)
D&A (Fixed Assets Schedule) ──────────→ EBIT (IS) + Add-back in CFS
CapEx (Fixed Assets Schedule) ────────→ Investing Cash Flow (CFS) + Fixed Assets (BS)
Net Cash Flow (CFS) ──────────────────→ Cash (BS)
Debt (BS) ────────────────────────────→ Interest Expense (IS)
Working Capital changes (BS) ─────────→ Operating Cash Flow (CFS)
Key Assumptions Built In

Revenue growth rate driving gross revenue projections
COGS as % of revenue (gross margin maintained)
OpEx as % of revenue
Days Sales Outstanding (DSO) → Accounts Receivable
Days Payable Outstanding (DPO) → Accounts Payable
Deferred Revenue as % of revenue
Tax rate applied to EBT
Debt repayment schedule
Asset useful lives for straight-line depreciation


💡 Key Outputs & Insights
MetricFY2022FY2026Net Revenue$23,750$47,500Gross Profit Margin58.9%58.9%EBITDA$7,750$15,500Net Income$1,685$9,263Net Income Margin7.1%19.5%Total Assets$14,413$37,136Cash-$2,872$32,423

Notable: Net income margin expands from 7.1% → 19.5% over 5 years, driven by revenue growth outpacing fixed cost base — a classic operating leverage story.


📁 Repository Structure
3-statement-model/
│
├── 3_Statement_Model.xlsx      # Full integrated model
└── README.md                   # Project documentation

🛠️ Tools Used

Microsoft Excel — Full model build, formula construction, sheet linking
Straight-line depreciation, indirect cash flow method, working capital roll-forwards


👤 Author
Teja
Aspiring Financial Analyst | Excel · Financial Modeling · FP&A
📍 Andhra Pradesh, India
