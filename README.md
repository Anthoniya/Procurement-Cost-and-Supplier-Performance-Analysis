# Procurement Cost and Supplier Performance Analysis

## Project Overview
This project simulates a full procurement analytics cycle for a 
construction company, covering supplier performance tracking, 
spend analysis, competitive bid evaluation, and material cost 
forecasting.

The analysis mirrors the core responsibilities of a Procurement 
Analyst or Junior Buyer — identifying cost-saving opportunities, 
evaluating supplier risk, and supporting data-driven purchasing 
decisions.

---

## Business Problem
Construction procurement teams face pressure to control costs, 
ensure on-time material delivery, and select the right suppliers. 
This project addresses those challenges by:
- Tracking delivery performance across 5 suppliers and 21 orders
- Benchmarking prices paid against market averages to 
  identify overpayments
- Evaluating competing bids using a weighted scoring matrix
- Forecasting short-term material prices to support 
  contract timing decisions

---

## Tools and Technologies
- **Microsoft Excel** — PivotTables, FORECAST.ETS, weighted 
  scoring matrix, KPI dashboard, conditional formatting
- **Procurement frameworks** — OTIF tracking, supplier risk 
  rating, spend analysis, RFQ evaluation

---

## Dataset
- 21 purchase orders across 5 suppliers and 6 materials
  (Cement, Steel, Gravel, Bricks, Pipes, Sand)
- Total procurement spend analysed: €60,317.79
- Fields include: order quantities, unit prices, expected 
  vs actual delivery dates, on-time flags, and delay days

---

## Key Analysis Areas

### 1. Purchase Order Review and Delivery Performance
Calculated delivery delays by comparing expected vs actual 
delivery dates and flagged orders as On-Time or Delayed.

**Key Findings:**
- Overall OTIF rate was just 48% — only 10 of 21 orders 
  delivered on time — highlighting a systemic 
  delivery performance issue
- SUP01 achieved 75% on-time delivery with zero average 
  delay — the most reliable supplier in the portfolio
- SUP05, the highest spend supplier at €26,389.31, had 
  the worst on-time rate at just 25% — a significant 
  supply chain risk

### 2. Spend Analysis and Market Benchmarking
Calculated total spend per supplier and per material, then 
benchmarked unit prices against market averages to 
Identify overpayments.

**Key Findings:**
- Cement accounted for the highest material spend at €29,207.25
- Steel was overpaid by 7.5% above the market rate — 
  representing a potential saving of €1,294
- Pipes were overpaid by 6.7% above market — 
  an additional €196 saving opportunity
- Combined cost saving opportunity identified: €1,490 
  on Steel and Pipes alone
- SUP01 consistently priced Cement below market rate, 
  making them the preferred low-cost, reliable supplier

### 3. Supplier KPI Dashboard
Built a supplier performance dashboard tracking on-time 
delivery rate, average delay, total spend, cost per order 
and risk rating across all 5 suppliers.

| Supplier | On-Time Rate | Avg Delay | Risk Level |
|----------|-------------|-----------|------------|
| SUP01 | 75% | 0 days | Low |
| SUP02 | 67% | 0 days | Medium |
| SUP03 | 33% | 1 day | High |
| SUP04 | 50% | 0.5 days | Medium |
| SUP05 | 25% | 1 day | High |

### 4. Bid Evaluation — Weighted Scoring Matrix
Evaluated three competing quotes for Steel using a weighted 
scoring matrix across price, lead time, warranty, and 
compliance criteria.

**Key Finding:**
- SUP05 offered the lowest price but failed compliance 
  requirements — highlighting that the lowest cost is not 
  always lowest risk
- SUP02 was the only fully compliant supplier with a 
  balanced price and lead time offering
- Recommended: prioritise SUP02 where compliance is 
  a critical procurement requirement

### 5. Material Cost Forecasting
Applied FORECAST.ETS to project 5-period forward prices 
for Cement, Steel, and Gravel to support the contract 
timing decisions.

**Key Findings:**
- Cement forecast showed a steady price decline toward 
  €4.95 — recommending early contract lock-in before 
  market stabilises
- The steel forecast showed high volatility, peaking at 
  €6.91 before declining — recommending delayed 
  high-volume purchasing until prices stabilise
- Gravel showed a consistent upward trend — 
  recommending prompt purchasing before further 
  price increases

---

## Key Recommendations
- Increase order allocation to SUP01 for critical materials 
  Given their price competitiveness and delivery reliability
- Enforce SLA compliance with SUP05 and SUP03 or 
  Reduce dependency given high-risk ratings
- Renegotiate Steel and Pipes pricing — both materials 
  are being purchased above market rate
- Use weighted bid scoring for all future RFQ evaluations 
  to ensure objective supplier selection
- Lock in Cement contracts early while the forecast 
  shows a favourable declining trend

---

## Business Impact
- Identified €1,490 in immediate cost-saving opportunities 
  across Steel and Pipes procurement
- Flagged that the highest spend supplier (SUP05 at €26,389) 
  carries the highest delivery risk — a key finding for 
  supplier relationship management
- Demonstrated that price alone is insufficient for the supplier 
  selection — compliance and reliability must be weighted 
  in all bid evaluations

---

## Future Development
- Expand analysis to a full year of purchase order data
- Build a real-time supplier KPI dashboard in Power BI
- Automate PO tracking using Power Query
- Incorporate inventory data to link procurement 
  decisions to stock availability

---

## Project Status
Complete — open to feedback and collaboration
