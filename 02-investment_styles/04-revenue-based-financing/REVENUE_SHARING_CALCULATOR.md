# Revenue Sharing Calculator Template

**For Revenue-Based Financing Deal Analysis**

---

## PURPOSE

This template helps founders and investors:
1. Calculate monthly payments under various RBF scenarios
2. Understand cash flow impact of revenue sharing
3. Model different revenue growth assumptions
4. Optimize terms (revenue share %, cap multiple, term length)

---

## SECTION 1: BASIC INPUTS

### Enter Your Deal Parameters:

**Investment Amount:**
- Investment Amount: **$[XXX,XXX]**
- Number of Tranches: **[1 / 2 / 3]**
- Tranche 1 Amount: **$[XXX,XXX]** (on close)
- Tranche 2 Amount: **$[XXX,XXX]** (on [milestone])
- Tranche 3 Amount: **$[XXX,XXX]** (on [milestone])

**Revenue Sharing Terms:**
- Revenue Share Percentage: **[X]%** per month
- Repayment Cap Multiple: **[X]x** (e.g., 2.0x = investor receives max cap amount)
- Repayment Cap Amount: **$[XXX,XXX]** (= Investment × Cap Multiple)
- Agreement Term Length: **[X] months** (or "until cap reached")
- Start Date: **[DATE]**

**Optional Adjustments:**
- [ ] Variable revenue share (tiered by revenue level)
- [ ] Declining revenue share over time
- [ ] Minimum monthly payment: **$[X]** (if applicable)
- [ ] Maximum monthly payment: **$[X]** (if applicable)

---

## SECTION 2: REVENUE PROJECTIONS

### Enter Your 24-Month Revenue Forecast

| Month | Projected Monthly Revenue | Notes |
|-------|--------------------------|-------|
| Month 1 | $[AMOUNT] | Current month baseline |
| Month 2 | $[AMOUNT] | Growth rate: [X]% |
| Month 3 | $[AMOUNT] | |
| Month 4 | $[AMOUNT] | |
| Month 5 | $[AMOUNT] | |
| Month 6 | $[AMOUNT] | Mid-year checkpoint |
| Month 7 | $[AMOUNT] | |
| Month 8 | $[AMOUNT] | |
| Month 9 | $[AMOUNT] | |
| Month 10 | $[AMOUNT] | |
| Month 11 | $[AMOUNT] | |
| Month 12 | $[AMOUNT] | Year 1 total |
| Month 13 | $[AMOUNT] | Year 2 starts |
| Month 14 | $[AMOUNT] | |
| Month 15 | $[AMOUNT] | |
| Month 16 | $[AMOUNT] | |
| Month 17 | $[AMOUNT] | |
| Month 18 | $[AMOUNT] | |
| Month 19 | $[AMOUNT] | |
| Month 20 | $[AMOUNT] | |
| Month 21 | $[AMOUNT] | |
| Month 22 | $[AMOUNT] | |
| Month 23 | $[AMOUNT] | |
| Month 24 | $[AMOUNT] | Year 2 total |

### Revenue Projection Scenario Builder

**If you don't have detailed month-by-month forecast, use scenarios:**

#### Scenario A: Conservative (50% of expectations)
```
Month 1 Revenue:        $50,000
Month-over-Month Growth: 8%
Year 1 Total Revenue:   $650,000
Year 2 Total Revenue:   $1,100,000
```

#### Scenario B: Base Case (Expected performance)
```
Month 1 Revenue:        $100,000
Month-over-Month Growth: 15%
Year 1 Total Revenue:   $1,800,000
Year 2 Total Revenue:   $3,200,000
```

#### Scenario C: Optimistic (If everything goes right)
```
Month 1 Revenue:        $150,000
Month-over-Month Growth: 20%
Year 1 Total Revenue:   $2,900,000
Year 2 Total Revenue:   $5,800,000
```

---

## SECTION 3: AUTOMATED PAYMENT CALCULATION

### Monthly Payment Schedule (AUTO-CALCULATED)

| Month | Revenue | Revenue Share % | Payment | Cumulative Paid | % of Cap | Cap Remaining |
|-------|---------|-----------------|---------|-----------------|----------|---------------|
| **Month 1** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 2** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 3** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 4** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 5** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 6** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Year 1 Subtotal** | **$[TOTAL]** | -- | **$[TOTAL]** | **$[TOTAL]** | **[X]%** | **$[CALC]** |
| **Month 7** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 8** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 9** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 10** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 11** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 12** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 13** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 14** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 15** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 16** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 17** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 18** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 19** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 20** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 21** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 22** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 23** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |
| **Month 24** | $[AMOUNT] | [X]% | **$[CALC]** | **$[CALC]** | **[X]%** | **$[CALC]** |

**Key Metrics:**
- **Total 24-Month Revenue**: $[CALCULATED]
- **Total 24-Month Payments**: $[CALCULATED]
- **Reached Cap?**: [YES / NO]
- **Months to Repay Cap**: [X] months
- **Average Monthly Payment**: $[CALCULATED]

---

## SECTION 4: KEY PERFORMANCE INDICATORS

### For Founders: Cash Flow Impact

| Metric | Value |
|--------|-------|
| **Average Monthly Revenue** (Year 1) | $[CALC] |
| **Average Monthly Payment** (Year 1) | $[CALC] |
| **Payment as % of Revenue** (Year 1) | **[X]%** |
| **Monthly Cash Retained** (after payment) | $[CALC] |
| **Monthly Cash for Operations** | [X]% of revenue |
| **Growth Headroom** | [X]% of revenue available for growth |

**Interpretation:**
- Payment <5% of revenue: **HEALTHY** ✓
- Payment 5%-8% of revenue: **MODERATE** ⚠️
- Payment >8% of revenue: **CONCERNING** ✗

### For Investors: Return Analysis

| Metric | Value |
|--------|-------|
| **Investment Amount** | $[AMOUNT] |
| **Repayment Cap** | $[AMOUNT] |
| **Expected Payback Months** | [X] months |
| **Payback Period** | [X] months |
| **IRR (Internal Rate of Return)** | **[X]%** |
| **Annual Return on Investment** | [X]% per year |
| **Risk: Downside Scenario** | If revenue is 50% of forecast |
| **Payback in Downside** | [X] months |
| **IRR in Downside** | [X]% |

**IRR Calculation Formula:**
```
If 24-month payback: IRR ≈ 30%-40% annually (attractive)
If 36-month payback: IRR ≈ 20%-30% annually (moderate)
If 48-month payback: IRR ≈ 10%-20% annually (risky)
```

---

## SECTION 5: SCENARIO COMPARISON

### Compare Multiple Deal Scenarios

#### Scenario 1: Conservative Terms (Founder Friendly)

**Inputs:**
- Investment: $250,000
- Revenue Share: 3%
- Cap Multiple: 1.5x ($375,000)
- Term: 48 months

**Results:**
```
Month 6 Payment:        $12,000
Year 1 Total Payments:  $120,000
Payback Period:         ~31 months
Investor IRR:           ~23% annually
Founder Retains:        97% of revenue for growth
```

#### Scenario 2: Market Standard Terms

**Inputs:**
- Investment: $250,000
- Revenue Share: 4%
- Cap Multiple: 2.0x ($500,000)
- Term: 36 months

**Results:**
```
Month 6 Payment:        $16,000
Year 1 Total Payments:  $160,000
Payback Period:         ~24 months
Investor IRR:           ~35% annually
Founder Retains:        96% of revenue for growth
```

#### Scenario 3: Aggressive Terms (Investor Friendly)

**Inputs:**
- Investment: $250,000
- Revenue Share: 6%
- Cap Multiple: 2.5x ($625,000)
- Term: 24 months

**Results:**
```
Month 6 Payment:        $24,000
Year 1 Total Payments:  $240,000
Payback Period:         ~18 months
Investor IRR:           ~52% annually
Founder Retains:        94% of revenue for growth
```

### Scenario Comparison Table

| Factor | Conservative | Market | Aggressive |
|--------|--------------|--------|-----------|
| **Revenue Share %** | 3% | 4% | 6% |
| **Cap Multiple** | 1.5x | 2.0x | 2.5x |
| **Expected Payback** | 31 months | 24 months | 18 months |
| **Investor IRR** | 23% | 35% | 52% |
| **Founder Cash Retained** | 97% | 96% | 94% |
| **Founder Preference** | ✓✓✓ Best | ✓✓ OK | ✗ Difficult |
| **Investor Preference** | ✗ Weak | ✓✓ Good | ✓✓✓ Best |

---

## SECTION 6: SENSITIVITY ANALYSIS

### How Sensitive Is the Deal to Revenue Changes?

#### Base Case: $100K Month 1, 15% MoM Growth

```
Expected Payback:       24 months
Expected Investor IRR:  35%
```

#### Sensitivity Scenarios:

##### A. What if revenue is 20% lower than forecast?

```
Month 1 Revenue:        $80,000 (instead of $100,000)
Monthly Growth:         15% (same)
New Payback Period:     29 months (vs 24 expected)
New Investor IRR:       28% (vs 35% expected)
Impact:                 -5 months, -7% IRR
```

**Interpretation:** Deal becomes moderately less attractive, but still acceptable.

##### B. What if growth slows to 8% after month 6?

```
Months 1-6:             15% monthly growth
Months 7-24:            8% monthly growth
New Payback Period:     38 months (vs 24 expected)
New Investor IRR:       16% (vs 35% expected)
Impact:                 +14 months, -19% IRR
```

**Interpretation:** Deal becomes risky. Investor should negotiate higher revenue share (5% instead of 4%) to offset growth risk.

##### C. What if revenue actually grows faster (20% monthly)?

```
Month 1 Revenue:        $100,000
Monthly Growth:         20% (vs 15% forecast)
New Payback Period:     21 months (vs 24 expected)
New Investor IRR:       42% (vs 35% expected)
Impact:                 -3 months, +7% IRR
```

**Interpretation:** Deal upside exceeds expectations (but investor still capped at 2.0x multiple).

### Sensitivity Table: How Revenue Changes Affect Payback

| Revenue Scenario | Year 1 Total | Payback Period | Investor IRR | Deal Quality |
|------------------|-------------|-----------------|--------------|-------------|
| **80% of forecast** (downside) | $1,440,000 | 34 months | 20% | ⚠️ Risky |
| **90% of forecast** | $1,620,000 | 29 months | 27% | ⚠️ OK |
| **100% of forecast** (base) | $1,800,000 | 24 months | 35% | ✓ Good |
| **110% of forecast** | $1,980,000 | 21 months | 42% | ✓✓ Excellent |
| **120% of forecast** (upside) | $2,160,000 | 19 months | 48% | ✓✓✓ Exceptional |

---

## SECTION 7: CASH FLOW ANALYSIS

### Company's Net Cash Position with RBF

**Assumptions:**
- Starting Monthly Revenue: $100,000
- Monthly Burn Rate (operating costs): $80,000
- Revenue Share Payment: 4%
- Starting Cash: $100,000

| Month | Revenue | Burn | RBF Payment | Net Cash | Running Total |
|-------|---------|------|------------|----------|---------|
| **Month 0** | -- | -- | -- | -- | **$100,000** |
| **Month 1** | $100,000 | -$80,000 | -$4,000 | +$16,000 | **$116,000** |
| **Month 2** | $115,000 | -$80,000 | -$4,600 | +$30,400 | **$146,400** |
| **Month 3** | $132,000 | -$80,000 | -$5,280 | +$46,720 | **$193,120** |
| **Month 4** | $152,000 | -$80,000 | -$6,080 | +$65,920 | **$259,040** |
| **Month 5** | $175,000 | -$80,000 | -$7,000 | +$88,000 | **$347,040** |
| **Month 6** | $201,000 | -$80,000 | -$8,040 | +$112,960 | **$460,000** |

**Key Insight:** Even with RBF payments, company is cash flow positive and building runway.

**Compare: Without RBF**
- Month 6 cash position: **$366,000**
- Difference: Only **$94,000 less** due to 6 months of RBF payments

**Conclusion:** RBF payments are manageable and shouldn't prevent growth investment.

---

## SECTION 8: RISK ANALYSIS

### What Could Go Wrong?

#### Risk 1: Revenue Plateau
**Scenario:** Revenue hits $250K/month by month 8, then stays flat

```
Expected: 2-Year Revenue = $2,000,000+
Actual: 2-Year Revenue = $1,000,000

Impact:
- Payback period: 38 months (vs 24 expected)
- Investor IRR: 16% (vs 35% expected)
- Founder's RBF burden: 4% of revenue indefinitely
```

**Mitigation:**
- Negotiate revenue share reduction if growth slows (e.g., 3% after month 18)
- Include performance-based acceleration (increase to 6% if not at cap by month 30)
- Early repayment clause for founders to exit if growth stalls

#### Risk 2: Customer Concentration
**Scenario:** 50% of revenue from one customer who leaves month 9

```
Expected: $250,000/month by month 9
Actual: $150,000/month (50% drop)

Impact:
- Customer loss: -$125,000/month revenue
- New payback: 45+ months (vs 24 expected)
- Investor may invoke remedy clause (increase rate, demand acceleration)
```

**Mitigation:**
- Diversify customer base before raising RBF
- Include protective covenant: "No customer >30% of revenue"
- Build customer churn metrics into reporting

#### Risk 3: Market Downturn
**Scenario:** Recession causes all customer cohorts to reduce spending by 40%

```
Expected: $300,000/month by year 2
Actual: $180,000/month

Impact:
- Revenue down 40%
- Investor only receives 60% of expected returns
- Payback period extends to 36-48 months
```

**Mitigation:**
- Use shorter cap period (not perpetual)
- Fixed term clause: "If cap not reached in 36 months, obligation ends"
- Escape clause for founders: right to buy out for [2.5x] cap if downside scenario triggers

#### Risk 4: Reporting Disputes
**Scenario:** Investor questions whether $50K in refunds should reduce revenue

```
Founder reports: $300,000 revenue (before processing refunds)
Investor views: $250,000 revenue (after refunds)

Dispute result:
- $2,000 discrepancy in payment for that month
- Requires audit to resolve (expensive, time-consuming)
- Damaged trust relationship
```

**Mitigation:**
- Define revenue recognition precisely in agreement (use ASC 606)
- Example: "Revenue = Gross Sales - Refunds - Chargebacks - Credit Card Fees"
- Automate reporting via accounting software integration
- Monthly reconciliation calls with investor

---

## SECTION 9: QUICK REFERENCE FORMULAS

### Manual Calculation Formulas

#### Basic Monthly Payment
```
Monthly Payment = Monthly Revenue × Revenue Share %

Example:
$250,000 Revenue × 4% = $10,000 payment
```

#### Repayment Cap Amount
```
Repayment Cap = Investment Amount × Cap Multiple

Example:
$250,000 Investment × 2.0x = $500,000 cap
```

#### Payback Period (Estimate)
```
Payback Period ≈ Cap Amount ÷ Average Monthly Payment

Example:
$500,000 Cap ÷ $15,000 Avg/Month = 33 months
```

#### Investor's Internal Rate of Return (IRR)
```
Simple Approximation:
Annual IRR ≈ (Cap Multiple - 1) ÷ (Payback Years)

Example (2.0x cap, 24-month payback):
(2.0 - 1) ÷ (24/12) = 1.0 ÷ 2 = 50% annually*

*More precise calculation requires financial calculator
```

#### Cash Retained by Company
```
Cash Retained Each Month = Revenue - (Revenue × Revenue Share %)

Example:
$250,000 Revenue - ($250,000 × 4%) = $240,000 retained
```

#### Total Cost of RBF vs. Equity
```
RBF Cost: Investment × Cap Multiple = $250K × 2.0x = $500K total cost
Equity Cost: If raised 20% equity at $10M valuation = $2M worth given up

RBF is 4x cheaper in this scenario
```

---

## SECTION 10: DECISION FRAMEWORK

### Should You Accept These RBF Terms?

**Founder Decision Tree:**

```
START: Considering RBF Terms
│
├─ Question 1: Is Monthly Payment <5% of Revenue?
│  ├─ YES → Proceed to Question 2
│  └─ NO → Renegotiate revenue share down OR increase cap multiple
│
├─ Question 2: Can You Reach Cap in <30 Months?
│  ├─ YES → Proceed to Question 3
│  └─ NO → Renegotiate better terms OR seek equity instead
│
├─ Question 3: Do You Have 6+ Months Runway After Payments?
│  ├─ YES → Proceed to Question 4
│  └─ NO → Don't take RBF, conserve cash
│
├─ Question 4: Will This Capital Unlock 3x+ Revenue Growth?
│  ├─ YES → Proceed to Question 5
│  └─ NO → Use savings/grants instead of RBF
│
├─ Question 5: Are You Comfortable with Monthly Reporting Burden?
│  ├─ YES → ACCEPT TERMS ✓
│  └─ NO → Negotiate simpler reporting requirements

DECISION: Accept / Renegotiate / Reject
```

**Investor Decision Tree:**

```
START: Evaluating RBF Deal
│
├─ Question 1: Payback in <30 Months Likely?
│  ├─ YES → Proceed to Question 2
│  └─ NO → Reject (too slow, too risky)
│
├─ Question 2: Expected IRR >25% Annually?
│  ├─ YES → Proceed to Question 3
│  └─ NO → Increase revenue share OR cap multiple
│
├─ Question 3: Company Revenue Predictable/Stable?
│  ├─ YES → Proceed to Question 4
│  └─ NO → Increase cap multiple OR reject
│
├─ Question 4: Founder Track Record Proven?
│  ├─ YES → Proceed to Question 5
│  └─ NO → Invest smaller amount OR reject
│
├─ Question 5: Revenue Declining or Flat?
│  ├─ DECLINING → Reject (too risky)
│  ├─ FLAT → Increase revenue share to 6%+ (offset risk)
│  └─ GROWING → ACCEPT TERMS ✓

DECISION: Invest / Negotiate / Reject
```

---

## SECTION 11: TEMPLATES FOR COMPARISON

### RBF vs. Alternative Funding

| Factor | RBF | Equity | Convertible | Venture Debt |
|--------|-----|--------|-------------|-------------|
| **Capital Received** | $250,000 | $250,000 | $250,000 | $250,000 |
| **Dilution** | 0% | 15-20% | 5-8% | 0% |
| **Total Paid Back** | $500,000 (2x cap) | $2M+ (if exit) | Interest only if debt | $300,000 (with interest) |
| **Payback Period** | 24 months | 5-10 years | 5-10 years | 36 months |
| **Cash Burden/Month** | $15,000 avg | $0 now, $2M later | $0 now | $7,000 (interest) |
| **Control Loss** | Minimal | Significant (board) | Minimal | None |
| **Best For** | Proven revenue | Pre-revenue growth | Flexible terms | Bridge funding |
| **Founder Preference** | ✓✓✓ | ✗ | ✓✓ | ✓ |

---

## SECTION 12: USING THIS CALCULATOR

### Step-by-Step Instructions:

1. **Fill in Section 1**: Deal parameters (investment amount, revenue share %, cap)
2. **Fill in Section 2**: Your 24-month revenue forecast
3. **Review Section 3**: Auto-calculated payment schedule appears
4. **Check Section 4**: Key metrics tell you if deal is viable
5. **Compare Section 5**: Different scenarios for negotiation
6. **Analyze Section 6**: How sensitive is deal to revenue changes
7. **Use Section 9**: Reference formulas for quick calculations
8. **Decide Section 10**: Decision framework helps you accept/reject

### Making Changes & Iterations:

```
Iteration 1: Input base case terms
Result: Payment is 6% of revenue (too high)

Iteration 2: Reduce revenue share to 3%
Result: Payment is 3% of revenue (better)

Iteration 3: Increase cap multiple to 2.5x
Result: Investor gets enough return at lower monthly rate

Iteration 4: ACCEPT - Found balanced terms
```

---

## EXAMPLES

### Example 1: SaaS Company, $100K Starting MRR

**Inputs:**
```
Investment:              $300,000
Revenue Share:           4% monthly
Cap Multiple:            2.0x
Cap Amount:              $600,000
Starting Monthly Revenue: $100,000
Monthly Growth:          12%
```

**Results:**
```
Month 6 Payment:         $18,000
Month 12 Payment:        $30,000
Year 1 Payments:         $216,000
Year 2 Payback:          Yes, cap reached month 29
Investor IRR:            ~32% annually
Founder Retains:         96% of revenue
Outcome:                 ✓ Good deal for both parties
```

### Example 2: E-commerce Company, $50K Starting Revenue

**Inputs:**
```
Investment:              $150,000
Revenue Share:           5% monthly
Cap Multiple:            2.0x
Cap Amount:              $300,000
Starting Monthly Revenue: $50,000
Monthly Growth:          10%
```

**Results:**
```
Month 6 Payment:         $8,300
Month 12 Payment:        $11,600
Year 1 Payments:         $95,000
Year 2 Payback:          Yes, cap reached month 32
Investor IRR:            ~28% annually
Founder Retains:         95% of revenue
Outcome:                 ✓ Acceptable, but tight cash flow early
```

### Example 3: B2B Services, Struggling Growth

**Inputs:**
```
Investment:              $200,000
Revenue Share:           4% monthly
Cap Multiple:            2.0x
Cap Amount:              $400,000
Starting Monthly Revenue: $150,000
Monthly Growth:          3% (struggling)
```

**Results:**
```
Month 6 Payment:         $9,900
Month 12 Payment:        $10,900
Year 1 Payments:         $115,000
Year 2 Payback:          No, cap reached month 48+
Investor IRR:            ~15% annually (TOO LOW)
Founder Burden:          4% of revenue for 4+ years
Outcome:                 ✗ Bad deal - negotiate better terms or skip RBF
```

---

## SUMMARY WORKSHEET

### Final Deal Summary

```
INVESTMENT TERMS:
├─ Amount: $[XXX,XXX]
├─ Revenue Share: [X]%/month
├─ Cap Multiple: [X]x = $[CAP]
└─ Term: [X] months / until cap

FINANCIAL PROJECTIONS:
├─ Month 1 Revenue: $[AMOUNT]
├─ Year 1 Total Revenue: $[AMOUNT]
├─ Average Monthly Payment: $[AMOUNT]
└─ Expected Payback: [X] months

KEY METRICS:
├─ Payment as % of Revenue: [X]%
├─ Investor Expected IRR: [X]%
├─ Cash Retained by Company: [X]%
└─ Deal Quality: [✓ Good / ⚠ OK / ✗ Poor]

DECISION:
[ ] ACCEPT - Terms are favorable
[ ] RENEGOTIATE - Need better terms
[ ] REJECT - RBF not right for us
```

---

**END OF REVENUE SHARING CALCULATOR TEMPLATE**

