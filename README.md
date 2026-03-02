# ☀️ Renewable Energy DCF Project Finance Model

![Financial Modeling](https://img.shields.io/badge/Domain-Project%20Finance-blue)
![Tool](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?logo=microsoft-excel&logoColor=white)
![Type](https://img.shields.io/badge/Model%20Type-DCF%20%7C%20Scenario%20Analysis-orange)
![Project Size](https://img.shields.io/badge/Project%20Size-%2440M%20Solar-yellow)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

A comprehensive **Discounted Cash Flow (DCF) and scenario-based financial model** built to evaluate the investment viability of a **$40 million utility-scale solar energy project**. The model simulates PPA-based revenue streams, operating cost structures, and project financing to produce investor-grade metrics including IRR, NPV, and WACC-based valuation.

---

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Key Outputs](#key-outputs)
- [Model Architecture](#model-architecture)
- [Assumptions](#assumptions)
- [Scenario Analysis](#scenario-analysis)
- [How to Use](#how-to-use)
- [Skills Demonstrated](#skills-demonstrated)
- [About the Author](#about-the-author)

---

## 📊 Project Overview

| Parameter | Detail |
|---|---|
| **Project Type** | Utility-Scale Solar (PV) |
| **Total CapEx** | $40,000,000 |
| **Revenue Model** | Power Purchase Agreement (PPA) |
| **Projection Period** | 20–25 Years |
| **Financing Structure** | Debt + Equity (Project Finance SPV) |
| **Valuation Method** | Discounted Cash Flow (DCF) |
| **Tool** | Microsoft Excel |

---

## 📈 Key Outputs

| Metric | Description |
|---|---|
| **NPV** | Present value of all project cash flows discounted at WACC |
| **IRR** | Project-level return; benchmarked against hurdle rate |
| **WACC** | Blended cost of capital across debt and equity tranches |
| **DSCR** | Debt Service Coverage Ratio — lender covenant analysis |
| **Payback Period** | Years to recover initial equity investment |
| **Equity IRR** | Levered return to equity investors post-debt service |

---

## 🏗️ Model Architecture

### 1. 📥 Inputs & Assumptions Tab
- PPA tariff rate ($/MWh) and escalation schedule
- System capacity (MW), capacity factor, and annual degradation rate (~0.5%/yr)
- CapEx breakdown: equipment, EPC, land, development costs
- Debt terms: loan amount, tenor, interest rate, amortization type
- Tax rate, depreciation schedule (MACRS / straight-line)

### 2. ⚡ Revenue Model
- Annual energy generation (MWh) = Capacity × Capacity Factor × 8,760 hrs
- Revenue = Generation × PPA tariff, adjusted for degradation over project life
- PPA escalation applied annually to reflect contractual rate increases

### 3. 💰 Cost Model
- **OpEx:** O&M, insurance, land lease, asset management fees
- **CapEx:** One-time construction and equipment spend in Year 0
- **Depreciation:** Non-cash charge reducing taxable income

### 4. 🏦 Financing & Debt Schedule
- Debt sizing based on DSCR covenant (typically 1.20x–1.35x minimum)
- Loan amortization schedule (principal + interest)
- Equity contribution = Total CapEx − Debt

### 5. 📉 DCF & Valuation
- Free Cash Flow to Project (FCFP) calculated annually
- Discounted at **WACC** to derive Project NPV
- Terminal value calculated using exit multiple or perpetuity growth method
- **Equity DCF** derived post-debt service for equity investor returns

### 6. 📊 Scenario & Sensitivity Analysis
- Three-case model: **Base, Upside, Downside**
- Sensitivity tables on IRR and NPV vs. key drivers:
  - PPA price (±10–20%)
  - Capacity factor (±5–10%)
  - Interest rate (±100–200 bps)
  - CapEx overrun (+10–20%)

---

## 🔢 Assumptions

| Assumption | Base Case Value |
|---|---|
| Installed Capacity | 20 MW |
| Capacity Factor | 22% |
| PPA Rate | $55/MWh |
| PPA Escalation | 1.5% per year |
| Panel Degradation | 0.5% per year |
| Project Life | 25 years |
| Total CapEx | $40,000,000 |
| Debt / Total CapEx | 70% |
| Loan Tenor | 18 years |
| Interest Rate | 6.5% p.a. |
| Corporate Tax Rate | 21% |
| WACC | 8.2% |
---

## 🎭 Scenario Analysis

| Scenario | PPA Rate | Capacity Factor | IRR (Project) | NPV |
|---|---|---|---|---|
| **Upside** | $62/MWh | 25% | ~14–15% | Positive |
| **Base Case** | $55/MWh | 22% | ~10–12% | Positive |
| **Downside** | $46/MWh | 18% | ~6–7% | Near Zero / Negative |

Scenarios are dynamically linked — switching between cases updates all outputs automatically via a dropdown selector.

---

## 🚀 How to Use

1. **Download** the Excel file from this repository
2. **Navigate to the `Inputs` tab** — all editable assumptions are highlighted in blue
3. **Adjust inputs** to match your project parameters
4. **Review outputs** on the `Dashboard` tab — IRR, NPV, DSCR, and Payback update automatically
5. **Run scenarios** using the dropdown to toggle between Base / Upside / Downside
6. **Sensitivity tables** are on the `Sensitivity` tab — vary two inputs simultaneously

---

## 🧠 Skills Demonstrated

- **Project Finance Modeling** — SPV-level cash flow construction, debt sculpting, DSCR analysis
- **DCF Valuation** — Free cash flow build, WACC calculation, terminal value estimation
- **Renewable Energy Finance** — PPA structures, solar degradation, capacity factor modeling
- **Scenario & Sensitivity Analysis** — Dynamic multi-case modeling with data tables
- **Excel Best Practices** — Modular structure, no circular references, color-coded inputs
- **Financial Storytelling** — Dashboard designed for investor and lender presentations

