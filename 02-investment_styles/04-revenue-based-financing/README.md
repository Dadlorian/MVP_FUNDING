# Revenue-Based Financing (RBF) Templates & Guides

## What is Revenue-Based Financing?

Revenue-Based Financing is a hybrid funding model where investors provide capital in exchange for a **percentage of monthly revenue** until either:
- A **repayment cap** is reached (2x-3x the investment), or
- A **maximum term** expires (typically 24-60 months)

### How RBF Works: Visual Flow

```
Investor provides: $[INVESTMENT_AMOUNT]
                    ↓
Startup receives capital (same day)
                    ↓
Startup generates revenue monthly
                    ↓
Each month: Startup pays [REVENUE_SHARE%] × Revenue to investor
                    ↓
Payment continues until:
├─ Repayment cap ($[CAP_AMOUNT]) reached, OR
├─ Maximum term ([TERM_MONTHS] months) expires
                    ↓
Investor received: Cap amount OR monthly payments
Startup's equity: 0% dilution
```

### Key RBF Terms Explained

#### Revenue Share Percentage
- **Definition**: Percentage of gross monthly revenue paid to investor
- **Typical Range**: 2%-10% per month
- **Factors Affecting Rate**:
  - Investment size ($50K gets ~3%, $500K gets ~5%)
  - Revenue predictability (SaaS pays less than e-commerce)
  - Startup growth stage (Series A pays more than pre-revenue)
  - Market conditions and investor appetite

**Example**:
- Investment: $250,000
- Revenue Share: 4% monthly
- Month 1 Revenue: $100,000 → Payment: $4,000
- Month 2 Revenue: $150,000 → Payment: $6,000

#### Repayment Cap (Return Multiple)
- **Definition**: Maximum total amount investor will receive
- **Typical Range**: 1.3x - 3.0x of investment
- **Common Multiples**:
  - 1.5x: Low-risk, established revenue
  - 2.0x: Standard term (most common)
  - 2.5x: Growth-stage companies
  - 3.0x: High-risk or early-stage

**Example**:
- Investment: $500,000 at 2.0x cap
- Cap amount: $1,000,000
- When cumulative payments hit $1M, RBF terminates

#### Monthly Payments Structure
- **Definition**: Actual monthly payment amount to investor
- **Calculation**: Current Month Revenue × Revenue Share %
- **Payment Timing**: Due by [PAYMENT_DUE_DAY] of following month
- **Minimum Payment**: Often $0 (no payment if no revenue)
- **Maximum Payment**: Sometimes capped at percentage of monthly revenue

**Example**:
- Revenue: $500,000/month
- Revenue Share: 5%
- Monthly Payment: $25,000
- Cumulative Repaid: $XX,XXX toward cap

---

## Founder Risks & Pain Points

### Risk 1: Cash Flow Pressure
**The Problem**: Revenue share drains cash flow before growth reinvestment

**Real Scenario**:
- You raise $300K on 5% revenue share at 2x cap
- Month 6: You hit $200K/month revenue
- Monthly payment: $10,000 gone (could fund 1-2 more engineers)
- This continues until $600K total repaid

**Mitigation Strategies**:
- Negotiate lower revenue share for established businesses (2-3%)
- Ensure cash flow model can support 6-12 months of payments
- Maintain 3-month operating reserve separate from RBF
- Structure growth spending after RBF cap is hit

### Risk 2: Revenue Reporting Requirements
**The Problem**: Constant transparency obligations create administrative burden

**Compliance Burden**:
- Monthly revenue reports within [REPORTING_DEADLINE] days
- Detailed accounting of what counts as "revenue"
- Audit rights for investor to verify numbers
- Potential penalties or disputed payments if reporting inconsistent

**Real Impact**:
- CFO/Accountant spends 10+ hours/month on reporting
- Disputes over revenue recognition (refunds, discounts, etc.)
- Delays if investor questions numbers
- Potential misclassification of revenue types

**Mitigation Strategies**:
- Use standard revenue recognition (ASC 606)
- Automate reporting via accounting software integration
- Clearly define revenue scope upfront in agreement
- Build audit-friendly tracking from day one

### Risk 3: Multiple RBF Stacking
**The Problem**: Multiple RBF investors create unsustainable revenue obligations

**The Trap**:
- Year 1: Raise $200K at 5% (seems manageable)
- Year 2: Raise $300K at 5% more (now 10% gone)
- Year 3: Need more, raise $400K at 5% more (now 15% gone)
- Revenue grows to $500K/month, but $75K/month leaves your company
- Cannot fund growth, hire, or reinvest

**Real Case**:
```
Total RBF raised: $900K
Revenue share obligations: 15% monthly
Month 12 revenue: $300K → $45K payment
Month 24 revenue: $500K → $75K payment (15% of revenue!)
Cumulative repaid by month 36: ~$2.7M (3x raised)
Growth velocity: Severely hampered for 3 years
```

**Mitigation Strategies**:
- Limit total RBF to <10% monthly revenue share
- Structure tranches: first tranche at 4%, second at 3%, etc.
- Build cap amounts into total planning ($500K limit, then stop)
- Negotiate milestone-based triggers instead of fixed percentages

### Risk 4: Growth Constraints
**The Problem**: RBF terms can penalize rapid growth

**Scenario**:
- You're scaling fast, revenue growing 50% MoM
- RBF payment automatically scales (good for investor, bad for you)
- Scaling team adds cost, RBF removes capital
- Margin compression during growth phase

**Mitigation Strategies**:
- Cap maximum monthly payment (e.g., "not to exceed $X/month")
- Use different share rates for revenue tranches
- Negotiate reduction in share as revenue scales
- Plan for 20%+ of gross revenue going to RBF

---

## Investor Risks & Pain Points

### Risk 1: Revenue Decline Risk
**The Problem**: Rapid revenue drops mean longer payback periods

**Real Scenario**:
- Investor expects 24-month payback at current growth
- Revenue plateaus month 12, then drops 30% (customer churn)
- Now payback takes 48+ months instead of 24
- Investor's capital locked up 2x longer than expected

**Financial Impact**:
```
Expected: 2% monthly revenue = 24 month payback
Actual decline: Revenue drops to 1% by month 18
Result: Payback extends to 40+ months
Opportunity cost: Capital could have been deployed elsewhere
```

**Investor Mitigations**:
- Shorter cap periods (24 months max, not 60)
- Higher revenue share (5-8% vs 2-3%)
- Declining share: 6% months 1-12, 4% months 13+
- Annual true-ups: adjust share based on revenue performance

### Risk 2: Longer Payback Periods
**The Problem**: No mechanism to accelerate return if growth slows

**Timing Risk**:
- Expected payback: 24 months
- Actual payback: 36-48 months (common scenario)
- During this period: Company may pivot, fail, or face new competition
- Investor stuck in illiquid position

**Why This Happens**:
- Revenue growth underperforms projections (50% of deals)
- Seasonal fluctuations prolong final months to cap
- Currency/market changes affect revenue reporting
- Company faces competitive pressures reducing margins

**Investor Mitigations**:
- Faster revenue share schedules (6-10% for early payback)
- Acceleration clauses (higher share if cap not hit by month 30)
- Mandatory payment minimums (minimum $X/month regardless)
- Exit provisions (buyback option after 24 months)

### Risk 3: Limited Upside (No Equity)
**The Problem**: Investor receives 2x-3x return max vs equity's 10x-100x potential

**Comparison**:
```
Equity deal (20% stake):
- Company reaches $10M valuation: 20% = $2M return (100x on $20K)

RBF deal ($250K at 2.5x cap):
- Return: $625K fixed (2.5x)
- Even if company becomes $100M: Still only 2.5x
- Upside capped regardless of success
```

**The Regret Factor**:
- If company succeeds wildly, investor realizes they missed equity upside
- If company fails, investor at least didn't lose equity stake (has better terms)
- Creates perceived "wrong choice" feeling if exit is large

**Investor Mitigations**:
- Include warrant coverage (0.5%-2% dilutable equity as sweetener)
- Equity conversion option (convert to equity at 10x revenue multiple)
- Dividend-like proceeds after cap (monthly percentage continues at lower rate)
- Board seat or advisor rights (capture non-financial upside)

### Risk 4: Revenue Recognition Disputes
**The Problem**: Disagreements about what counts as "revenue"

**Disputed Revenue Categories**:
- Refunds: Does full refund mean reversal of prior payment?
- Discounts/Rebates: Taken off revenue, affecting payment?
- Non-cash: Barter/equity grants count as revenue?
- Cancellations: How are partial month refunds handled?
- Affiliates/Resellers: Net vs gross commission revenue?

**Real Dispute**:
```
Startup reports: $500K revenue
Investor questions:
- $50K in refunded orders (should be $450K?)
- $30K in gift card sales held as liability (not revenue until redemption)
- $20K in affiliate commissions net of fees

Revised revenue: $400K (not $500K)
Payment dispute: $5K difference on that month alone
```

**Investor Mitigations**:
- Strict revenue definition in agreement (ASC 606 GAAP standard)
- Monthly reconciliation rights
- Annual third-party audit rights
- Hold-back/escrow for disputed months

---

## Pain Points in RBF Negotiations

### Pain Point 1: Revenue Share % Negotiations
**The Sticking Point**: Both sides want optimal terms but have different risk views

**Founder Perspective**:
```
"I want 2% - that's barely noticeable"
"My projected revenue is $500K by month 12"
"2% × $500K = only $10K/month, very manageable"
```

**Investor Perspective**:
```
"I need 5% - my payback takes too long at 2%"
"Your projections always overestimate 50% of the time"
"At 2%, if you hit $250K instead of $500K, I wait 40 months"
"5% protects me against your rosy projections"
```

**The Gap**:
- Founders see published success stories (2-3% typical)
- Investors see downside cases (40+ month paybacks)
- No standard methodology for pricing risk

**Resolution Strategies**:
- **Tiered Approach**: 5% months 1-12, then 3% months 13-24
- **Milestone Rates**: Different % based on revenue milestones
  - Under $200K/month: 4%
  - $200K-$500K: 3%
  - Over $500K: 2%
- **Performance-Based**: Share decreases if cap not hit by month 30
- **Hybrid**: 4% first 18 months, 2% thereafter

### Pain Point 2: Repayment Cap Multiples
**The Negotiation**: What's a fair return multiple?

**Founder Argument**:
```
"1.3x is fair - I'm paying interest premium"
"My equity investors expect 20-30% annual returns"
"1.3x over 24 months = ~12% IRR"
"Totally reasonable vs equity risk"
```

**Investor Argument**:
```
"1.3x is too low - I lose in downside scenarios"
"If your projections miss by 50%, payback is 40+ months"
"2.5x needed because no equity upside"
"I'm taking revenue risk with no equity protection"
```

**Market Standards by Stage**:
```
Pre-revenue: 2.5x - 3.0x (high risk)
Early traction ($10K MRR): 2.0x - 2.5x
Growing ($50K+ MRR): 1.5x - 2.0x
Established ($100K+ MRR): 1.3x - 1.5x
```

**Negotiation Tactics**:
- **For Founders**:
  - "I have Series A term sheet at $10M valuation" (shows growth trajectory)
  - "Comparable RBF deals in my space are 1.5x-1.8x"
  - "I'll agree to 2.0x if you reduce revenue share to 3%"

- **For Investors**:
  - "Your growth is slower than comparable companies"
  - "Revenue concentration in 3 customers = risk"
  - "Cap must be 2.5x minimum for this revenue profile"

### Pain Point 3: Reporting and Audit Burden
**The Operational Friction**: Too much overhead, not enough clarity

**Founder Burden**:
- Monthly revenue reports (2-4 hours)
- Audit trail documentation
- Quarterly/annual audit rights (10-20 hours per audit)
- Disputes and reconciliations

**Investor Burden**:
- Can't easily verify numbers without audit
- Monthly reconciliation vs books
- No standard format for comparability
- Trust but verify dilemma

**Typical Disputes**:
```
Month 6 Report:
Founder: "Revenue is $250,000"
Investor: "I only see $200,000 in bank deposits"
Founder: "That includes deferred revenue, net refunds, accounting entries"
Investor: "Not what we defined as revenue"

Resolution: 6-week delay, legal review, negotiated compromise
```

**Solutions in Agreements**:
- **Automated Reporting**: Integrate with accounting software (Stripe, QuickBooks API)
- **Defined Metrics**: Specific to business model
  - SaaS: MRR only, after refunds/cancellations
  - E-commerce: Gross revenue, before shipping/discounts
  - Services: Invoiced hours/projects, not deferred contracts
- **Audit Rights**: Annual only, unless material discrepancy found
- **Escrow Provisions**: Disputed amounts held, reviewed quarterly
- **Certification**: CEO certifies monthly numbers personally

---

## When RBF Makes Sense vs Equity

### Choose RBF When:

✅ **You have predictable revenue** (SaaS, subscriptions)
- Clear monthly recurring revenue
- Retention metrics you understand
- Ability to forecast 6-12 months out

✅ **You're post-product-market fit**
- Validating business model, not proving it
- Monthly revenue of $10K+
- Clear path to profitability

✅ **You want to maintain control**
- Avoid board seats and equity dilution
- Keep founder voting majority
- Don't want outside investor influence

✅ **You need capital for growth, not survival**
- Not burning cash to stay alive
- Have 6+ months runway without RBF
- Capital for marketing/team acceleration

✅ **You have limited fundraising time**
- RBF closes 4-8 weeks (vs 6+ months for VC)
- Can deploy capital immediately
- Quick decision from investor

### Choose Equity When:

❌ **You have highly uncertain revenue**
- Pre-revenue or very early
- Volatile monthly numbers
- Hard to forecast 6 months ahead

❌ **You need strategic mentorship**
- First-time founders
- Building in new market
- Value board expertise more than capital speed

❌ **You're pursuing massive growth**
- Want 10x or 100x return potential
- Comfortable with founder dilution
- May need $5M+ in total capital

❌ **You have negative/declining revenue**
- Cash burn exceeds growth
- Revenue trends negative
- RBF would destroy runway

❌ **You need co-founder/strategic partnership**
- Equity aligns long-term incentives
- Want investors locked in for 5-10 years
- Building institutional investor relationships

### Hybrid Approach (Recommended)

**Best of Both Worlds**:
```
Raise $250K RBF + $100K SAFE/Convertible
├─ RBF: Fast capital (4 weeks), no equity
├─ SAFE: Lower dilution than equity, signaling mechanism
├─ Combined: $350K capital, minimal dilution (~5-8% via SAFE)
└─ Flexibility: SAFE converts if Series A funding, stays if acquired

Timeline:
├─ Month 1-2: Pitch RBF ($250K target)
├─ Month 2-4: Close RBF and start using
├─ Month 4-6: Demonstrate traction, then SAFE fundraising
├─ Month 6+: Accelerate growth with proven metrics
```

---

## RBF Structure Comparison

| Factor | RBF | Equity | Convertible | Venture Debt |
|--------|-----|--------|-------------|--------------|
| **Dilution** | 0% | 15-30% | 5-10% | 0% |
| **Payback Period** | 24-60 months | 5-10 years | At conversion | 24-36 months |
| **Interest/Multiple** | 1.3x-3.0x | None | None | 8-12% interest |
| **Control Loss** | Minimal | Significant (board) | Minimal | None |
| **Repayment if Fail** | None (like equity) | None (like equity) | None (stays note) | Debt obligation |
| **Speed to Close** | 4-8 weeks | 6-12 months | 4-8 weeks | 6-12 weeks |
| **Best For** | Growth-stage, proven revenue | Early-stage, high growth | Flexible founders | Bridge funding |
| **Founder Effort** | Reporting burden | Governance burden | Light burden | Reporting burden |

---

## Directory Structure

```
04-revenue-based-financing/
├── README.md (this file - overview and education)
├── RBF_AGREEMENT_TEMPLATE.md (legal document template)
├── TERM_SHEET_TEMPLATE.md (summary of key terms)
├── REVENUE_SHARING_CALCULATOR.md (payment calculation template)
├── FOUNDER_PERSPECTIVE.md (founder-focused guide)
├── INVESTOR_PERSPECTIVE.md (investor-focused guide)
└── PAYMENT_SCHEDULE_EXAMPLE.md (realistic payment scenario)
```

---

## Quick Start Guide

### For Founders Seeking RBF:

1. **Read**: `FOUNDER_PERSPECTIVE.md`
2. **Review**: `PAYMENT_SCHEDULE_EXAMPLE.md` (understand cash impact)
3. **Prepare**: Your 24-month revenue forecast
4. **Use**: `TERM_SHEET_TEMPLATE.md` to discuss key terms
5. **Finalize**: `RBF_AGREEMENT_TEMPLATE.md` with legal review

### For Investors Evaluating RBF:

1. **Read**: `INVESTOR_PERSPECTIVE.md`
2. **Analyze**: `REVENUE_SHARING_CALCULATOR.md` (run payback scenarios)
3. **Review**: `PAYMENT_SCHEDULE_EXAMPLE.md` (understand historical context)
4. **Evaluate**: `TERM_SHEET_TEMPLATE.md` (key terms framework)
5. **Document**: `RBF_AGREEMENT_TEMPLATE.md` (finalize agreement)

---

## Key Metrics for RBF Success

### Founder Success Metrics:
- **RBF Repayment Time**: 24-36 months (ideal: <30 months)
- **Monthly Payment Ratio**: Should be <8% of revenue (ideal: 3-5%)
- **Runway Extension**: RBF should extend runway by 12+ months
- **Growth During Term**: Achieve 2x+ revenue growth during RBF period

### Investor Success Metrics:
- **IRR (Internal Rate of Return)**: 25-35% (depending on risk)
- **Payback Period**: 24-36 months (don't exceed 48)
- **Revenue Growth Rate**: Founder should demonstrate 20%+ MoM early
- **Default Risk**: Should monitor for revenue decline signals

---

## Common RBF Terms Reference

| Term | Typical Range | Notes |
|------|--------------|-------|
| **Investment Amount** | $50K-$1M | Sweet spot: $200K-$500K |
| **Revenue Share %** | 2%-10% monthly | Median: 4-5% |
| **Repayment Cap** | 1.3x-3.0x | Median: 2.0x |
| **Term Length** | 24-60 months | Median: 36 months |
| **Reporting Frequency** | Monthly | Due within 5-10 days |
| **Closing Timeline** | 4-8 weeks | Much faster than VC |
| **Due Diligence** | Light to Medium | Financial audit needed |

---

## Legal & Compliance Notes

- **Accredited Investors**: Most RBF providers limit to accredited investors ($1M+ net worth)
- **Revenue Definition**: Must align with GAAP accounting (ASC 606 standard)
- **State Regulations**: Some states treat RBF as a security (varies by jurisdiction)
- **Tax Treatment**: Revenue payments are NOT tax-deductible (not interest)
- **Bankruptcy**: RBF may be treated as equity (not senior debt) in bankruptcy

---

## Resources & Further Reading

- **Industry Standard**: Y Combinator's RBF resource library
- **Typical Providers**: Clearco, Lighter Capital, Founderpath, Pipe
- **Legal Template**: StandardDocs (RBF agreement standard)
- **Community**: RBF founders community on Twitter/Slack for benchmarking

---

## Questions to Ask Yourself

**Before pursuing RBF:**

1. Is my monthly revenue predictable within ±20%?
2. Can I afford to pay 3-8% of revenue for 24+ months?
3. Do I need this capital within next 2 months?
4. Am I comfortable with monthly financial reporting?
5. Will multiple RBF rounds be necessary, and can I afford stacking?

**Before accepting RBF terms:**

1. What is realistic payback time given my growth rate?
2. Have I negotiated revenue share to ≤5%?
3. Is the cap multiple fair for my revenue stability?
4. Can I maintain financial reporting without major overhead?
5. What if revenue plateaus by month 18 - can I survive?

