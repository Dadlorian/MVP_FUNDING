# Comprehensive Covenant Guide for Venture Debt

## What Are Covenants?

**Covenants are promises** that the borrower makes to the lender. They're contractual restrictions that protect the lender's investment and serve as early warning system for borrower distress.

### Two Types of Covenants

#### 1. Affirmative Covenants ("Shall")
- **What you MUST DO**
- Pay interest/principal timely
- Maintain insurance
- Deliver financial statements
- Maintain compliance with law

#### 2. Negative Covenants ("Shall NOT")
- **What you CANNOT DO** (without approval)
- Incur additional debt
- Sell assets
- Change control of company
- Pay dividends
- Acquire other companies
- Lease facilities beyond threshold

---

## Core Financial Covenants

### 1. MINIMUM QUARTERLY REVENUE COVENANT

**What it is:**
Requirement that company achieve minimum revenue target each quarter.

**Typical structure:**
```
Q1 2024: Minimum $[REVENUE_Q1]
Q2 2024: Minimum $[REVENUE_Q2]
Q3 2024: Minimum $[REVENUE_Q3]
Q4 2024: Minimum $[REVENUE_Q4]
Q1 2025: Minimum $[REVENUE_Q1_NEXT_YEAR]
```

**Definition of "Revenue":**
- Gross revenue from sale of products/services
- Does NOT include:
  - Refunds and returns
  - Intercompany transactions
  - Non-cash revenue
  - Customer prepayments (counted when revenue recognized, not when cash received)

**Measurement:**
- Based on quarterly financial statements
- Reported within [REPORTING_DAYS] days of quarter-end
- Calculated on accrual basis (GAAP), not cash basis

**What triggers breach:**
- Actual revenue < covenant amount
- Example: Covenant is $500K; actual revenue is $475K = BREACH

**Cure mechanism:**
- Usually allows [CURE_PERIOD_DAYS] days to cure after notice
- First breach may be waived if company explains
- Repeated breaches (2+ times in 12 months) = automatic material default

### 1.1 Negotiating Revenue Covenants

**Founder perspective:**
- Too tight → Can't navigate market changes
- Growth projections rarely 100% accurate
- Need buffer for normal business variation

**Founder negotiation tactics:**
```
Lender proposes:
Q1: $500K
Q2: $600K (+20%)
Q3: $700K (+17%)
Q4: $800K (+14%)

You counter (conservative):
Q1: $500K (match)
Q2: $525K (+5%)
Q3: $550K (+5%)
Q4: $575K (+5%)

Compromise:
Q1: $500K
Q2: $560K (+12%)
Q3: $620K (+11%)
Q4: $680K (+10%)
```

**Key negotiation points:**
- Request covenant holiday (first 12 months) while you scale
- Use 80% confidence projections, not best-case
- Request tiered increases (5-10% growth, not 20%)
- If quarterly numbers volatile, use annual instead
- Request ability to substitute lower quarter if clear recovery path in next quarter

### 1.2 Revenue Covenant Stress Test

**Model 24-month forward:**

```
Current: Q1 revenue $500K
Projection: 10% QoQ growth

Quarters ahead:
Q2: $550K (covenant $500K) ✓
Q3: $605K (covenant $550K) ✓
Q4: $665K (covenant $600K) ✓
Q5: $732K (covenant $650K) ✓
Q6: $805K (covenant $700K) ✓

Stress test (5% growth instead):
Q2: $525K (covenant $500K) ✓
Q3: $551K (covenant $550K) ✓
Q4: $579K (covenant $600K) ✗ BREACH

Recommendation: Negotiate Q4 covenant to $570K (more conservative)
```

---

### 2. MAXIMUM BURN RATE COVENANT

**What it is:**
Limit on how much cash company can burn (spend) each month.

**Typical structure:**
```
Months 1-12: Max $500,000/month burn
Months 13-24: Max $600,000/month burn
Months 25+: Max $750,000/month burn
```

**Definition of "Monthly Cash Burn":**
```
Cash burn = Cash operating expenses + Capital expenditures - Revenues collected
```

**What's included:**
- Payroll, benefits, taxes
- Vendor/supplier costs
- Rent, utilities, insurance
- Capital expenditures (equipment, software)
- Travel, marketing, professional services

**What's excluded:**
- Debt service (principal and interest) - already accounted for
- One-time charges (severance, restructuring)
- Stock-based compensation (non-cash)
- Acquisition-related costs (if lender-approved)

**Measurement:**
- Calculated monthly using rolling 90-day average (smooths month-to-month variance)
- Reported to lender monthly
- If spike expected, notify lender in advance

**Breach consequence:**
- Exceeding $[MAX_BURN] for [CONSECUTIVE_MONTHS] consecutive months = material default
- Single month spike may be waived if temporary

### 2.1 Burn Rate Covenant Strategy

**Why covenants matter:**
- Lender cares about burn rate because it determines cash runway
- If burn rate increases, cash depletes faster → Less ability to repay debt

**Founder negotiation:**
```
Lender proposes: Max $500K/month

You explain:
- Current burn: $400K/month
- Planned hiring: 5 engineers @ $50K/month = $250K total = $650K new burn
- But revenue growing $100K/month = net new burn $150K = $550K total

Counter-proposal: $550K/month initially, reduce to $450K if revenue reaches $[MILESTONE]
```

**Key points:**
- Build operational headroom (propose max burn 20% higher than forecast)
- Request relief as revenue grows (automatic increase if you hit revenue targets)
- Request temporary relief for one-time spending (equipment, hiring, expansion)
- Model realistic hiring plans; don't hide planned growth

### 2.2 Burn Rate Stress Test

**Scenario analysis:**

```
Base case (50% probability):
- Revenue: $100K → $120K → $140K (10% monthly growth)
- Expenses: $150K → $160K → $170K (fixed increase as headcount grows)
- Burn: $50K → $40K → $30K (declining as revenue grows)
- Burn covenant: $50K/month ✓ Safe

Downside case (30% probability):
- Revenue: $100K → $100K → $95K (market slowdown, churn increases)
- Expenses: $150K → $160K → $170K (already hired headcount)
- Burn: $50K → $60K → $75K (increasing as revenue declines)
- Burn covenant: $50K/month ✗ Breach in month 2

Action: Either
a) Negotiate covenant to $80K/month to accommodate downside, OR
b) Plan headcount/spending cuts in downside scenario
```

**Recommendation:**
- Model at 70% confidence (not 50% base case)
- Covenant should be 20-30% higher than expected burn
- Build flexibility into covenant (tiered increases, milestones)

---

### 3. MINIMUM CASH BALANCE COVENANT

**What it is:**
Requirement to maintain minimum unrestricted cash at all times.

**Typical structure:**
```
Maintain minimum $2,000,000 cash balance at all times
OR
Maintain minimum 180 days of operating expenses in cash (whichever is greater)
```

**Definition of "Eligible Cash":**
- Cash in operating accounts (checking, savings)
- Money market accounts
- Treasury bills, short-term securities (maturity <[DAYS] days)
- NOT: Restricted cash (customer deposits held in trust, escrow), credit card lines, undrawn credit facilities

**Measurement:**
- Based on bank statements
- Measured on last day of each month
- Includes all subsidiary and foreign accounts (consolidated)

**Breach consequence:**
- Falls below minimum at month-end = covenant breach
- Can be cured immediately by raising capital or reducing spending
- Multiple months below = material default

### 3.1 Cash Balance Covenant Negotiation

**Why lenders require it:**
- Ensures cash for debt service is available
- Prevents company from deploying cash in risky ways
- Provides cushion for operational shortfalls

**Founder concerns:**
- Ties up cash that could be invested in growth
- Restricts hiring, marketing, strategic initiatives
- Company might be sitting on cash unnecessarily

**Negotiation approach:**

```
Lender proposes: $3M minimum cash balance

You counter:
- Company does $500K/month revenue
- Average monthly cash operating expenses: $400K
- Realistic minimum for safety: 180 days = $600K
- Agreed: $600K minimum (instead of $3M)

Alternative:
- Use "days of expense" instead of fixed amount
- Covenant: 90 days of average operating expenses
- As company grows (expenses increase), covenant amount auto-increases
- More flexible; aligns with actual business needs
```

**Key negotiation points:**
- Reduce minimum to days-of-expense approach (80-120 days typical)
- Request relief once you raise Series B (can lower to 45-60 days)
- Request carve-out for customer prepayments (shouldn't count against minimum if held in trust)
- Don't accept unrealistic cash reserves (lender asking for excessive buffer)

---

### 4. DEBT SERVICE COVERAGE RATIO (DSCR)

**What it is:**
Ratio of company's earnings to debt obligations. Measures ability to service debt from operations.

**Formula:**
```
DSCR = EBITDA / Annual Debt Service

Where:
EBITDA = Earnings Before Interest, Taxes, Depreciation, Amortization
Annual Debt Service = Principal payments + Interest payments on all debt
```

**Typical covenant:**
```
DSCR must be >= 1.5x (minimum acceptable for lenders)
DSCR must be >= 2.0x (comfortable for lenders)
DSCR must be >= 3.0x (excellent; low risk)
```

**Example:**
```
Company EBITDA: $2,000,000/year
Debt service:
- Venture debt: $200K principal + $120K interest = $320K/year
- Equipment financing: $50K principal + $10K interest = $60K/year
- Total debt service: $380K/year

DSCR = $2,000,000 / $380,000 = 5.3x ✓ (excellent; well above 1.5x minimum)

vs.

Company EBITDA: $400,000/year
Debt service: $380K/year
DSCR = $400,000 / $380,000 = 1.05x ✗ (below 1.5x minimum; covenant breach)
```

**EBITDA definitions (broad):**
```
Net Income
+ Interest expense
+ Taxes
+ Depreciation & amortization
+ One-time/non-recurring items
+ Stock-based compensation
= EBITDA (adjusted for venture debt purposes)
```

**Measurement:**
- TTM (trailing twelve months) basis (smooths seasonality)
- Tested quarterly on TTM basis
- Only becomes active once company reaches profitability threshold (e.g., $[REVENUE_THRESHOLD])

### 4.1 When DSCR Covenant Becomes Active

**Typical structure:**
```
DSCR covenant only applies once company reaches:
- $[ANNUAL_REVENUE_THRESHOLD] in annual revenue, OR
- Positive EBITDA, OR
- 24 months have elapsed (whichever first)

Rationale: Early-stage companies rarely profitable; don't want to restrict growth mode
Once company matures, profitability matters for repayment ability
```

### 4.2 DSCR Covenant Implications

**For founders:**
- As company grows, EBITDA grows → More debt service capacity
- Profitable companies can take more debt
- Unprofitable companies won't be able to meet DSCR covenant

**Example of issue:**
```
Company with $2M revenue, not profitable (EBITDA = -$500K)
Lender wants to lend $1M at 12% interest (12-year term)
Annual interest: $120K
DSCR required: 1.5x → Need EBITDA of $180K minimum

Company can't achieve this without becoming profitable
Covenant would restrict growth spending to force profitability
OR
Lender reduces loan size to amount company can service:
If -$500K EBITDA now, need 2-3 years to reach $300K EBITDA
Max loan: $200K (at 1.5x DSCR with $300K EBITDA target)
```

---

### 5. LOAN-TO-VALUE (LTV) RATIO

**What it is:**
Ratio of loan amount to company valuation. Prevents over-leveraging.

**Formula:**
```
LTV = Outstanding Loan Balance / Company Valuation

Maximum covenant: LTV < 50% (or 0.5x)
```

**Example:**
```
Loan amount: $1M
Company valuation (Series B): $20M
LTV = $1M / $20M = 5% ✓ (well below 50% threshold)

vs.

Loan amount: $1M
Company valuation (Series A): $5M
LTV = $1M / $5M = 20% ✓ (acceptable)

vs.

Loan amount: $1M
Company valuation (early): $1.5M
LTV = $1M / $1.5M = 67% ✗ (above 50%; covenant breach)
```

**Valuation basis for covenant:**
- Most recent Series funding round valuation
- Annual 409A valuation
- Lender's independent valuation (used if lender believes more conservative)

**Why it matters:**
- If company doesn't grow valuation, debt becomes larger relative to company
- Prevents company from taking on debt disproportionate to size
- If company valuable, can support more debt

**Implication:**
- As company raises new funding rounds, LTV naturally decreases
- Series B at higher valuation → LTV decreases → More debt capacity
- If company doesn't grow, LTV increases → Less capacity for new debt

---

## Negative Covenants (Operational Restrictions)

### 1. NO ADDITIONAL DEBT COVENANT

**What it says:**
Company cannot incur any additional indebtedness without lender approval.

**Restrictions:**
- Bank debt or credit lines
- Equipment financing or capital leases
- Other venture debt or mezzanine financing
- Shareholder loans
- Guarantees of third-party debt
- Subordinated debt or convertible notes

**Exceptions (permitted without approval):**
- Trade payables in ordinary course (accruals to suppliers)
- Debt < $[PERMITTED_THRESHOLD]% from Lender-approved lenders
- Equipment financing < $[EQUIPMENT_LEASE_LIMIT] per transaction

**Why lender cares:**
- More debt = More debt service = Less ability to repay this loan
- Prevents company from using leverage to fund risky investments
- Keeps debt structure simple (one senior lender)

**Founder implication:**
- Can't take on second debt without approval
- Limits financing flexibility
- Must negotiate approval for planned debt (e.g., equipment financing)

---

### 2. NO CHANGE OF CONTROL COVENANT

**What it says:**
Cannot sell company, merge, or transfer control without lender approval.

**Definition of "change of control":**
- Sale of [CONTROL_THRESHOLD]%+ of voting stock
- Merger or consolidation
- Sale of [ASSET_PERCENTAGE]%+ of assets
- Change in board majority

**Trigger for mandatory prepayment:**
- If change of control occurs AND purchase price > $[THRESHOLD]
- Company must prepay loan (no prepayment penalty on M&A)

**Founder implication:**
- Can't sell company without lender consent
- If lender withholding approval, company stuck
- Likely lender will approve if realistic deal valuation

**Practical note:**
- Lender almost always approves change of control if repayment likely
- Lender's main concern: Will loan get repaid?
- If M&A proceeds sufficient to repay, lender happy

---

### 3. ASSET SALE RESTRICTIONS

**What it says:**
Cannot sell material assets without lender approval.

**What requires approval:**
- Sale of equipment/property > $[ASSET_THRESHOLD]
- Exclusive licensing of IP or technology
- Disposition of business line or division
- Sale of major contract rights

**What's permitted (no approval needed):**
- Inventory sales in ordinary course
- Used equipment sales < $[ROUTINE_THRESHOLD]
- Replacement of damaged equipment with equivalent
- Lease termination and equipment return

**Why lender cares:**
- Company assets secure repayment
- Selling off assets = Less collateral
- Lender worried about "asset stripping"

---

### 4. NO ACQUISITIONS COVENANT

**What it says:**
Cannot acquire other companies or purchase material assets without approval.

**Restrictions:**
- M&A of other companies
- Strategic investments > $[THRESHOLD]
- IP/technology purchases
- Joint ventures

**Why lender cares:**
- Acquisitions use cash (impacts cash balance covenant)
- Acquisitions add debt/liabilities (impacts leverage)
- Management distraction (impacts execution)
- Integration risk (founder focused on acquisition, not core business)

**Negotiation:**
- Request carve-out for small acquisitions (< $[SMALL_ACQUISITION])
- Request automatic approval if funded entirely by equity
- Request pre-approval for strategic targets likely to be acquired

---

### 5. NO DIVIDEND/DISTRIBUTION COVENANT

**What it says:**
Cannot pay dividends or distributions to shareholders without lender approval.

**Prohibited:**
- Cash dividends
- Special distributions
- Share buybacks
- Related-party payments

**Why:**
- Dividends deplete cash
- Lender wants cash reserved for debt service
- Prevents founder "taking money out" at company's expense

**Exception:**
- Equity grants to employees (covered under separate covenant on employee options)

---

### 6. NO RELATED-PARTY TRANSACTIONS

**What it says:**
Cannot enter material related-party transactions without lender approval.

**Restrictions:**
- Loans to officers/directors
- Transactions with founders at non-arm's-length prices
- Management fee arrangements to related entities
- Leases to/from founders

**Why:**
- Related-party deals often unfavorable to company
- Potential for founder self-dealing
- Reduces company assets available for lender repayment

**Negotiation:**
- Disclose all related-party transactions to lender
- Request pre-approval for necessary transactions (founder loan repayment, etc.)
- Ensure all transactions at fair market value

---

## Covenant Breach & Default Process

### Timeline of Breach Resolution

```
Day 1: Covenant breach occurs
- Founder doesn't realize yet
- Monthly closing in progress

Day 5: Monthly financials delivered
- Finance team realizes covenant breach
- CEO/CFO notified

Day 7: Internal discussion
- Board discusses options
- CFO calculates how to cure
- Decides whether to immediately tell lender

Day 10: Notify lender (or lender discovers from quarterly reporting)
Lender options:
a) Ignore (informal waiver; allows founder to cure naturally)
b) Request explanation/cure plan
c) Formal notice of default
d) Demand immediate cure or repayment

Days 10-30: Cure period (if applicable, usually [CURE_DAYS] days)
- Company works to improve financials
- Reports progress to lender
- Lender may grant brief extension if seeing progress

Day 30: End of cure period
If breached covenant cured: Covenant issue resolved, relationship continues
If NOT cured: Lender declares default
- Accelerates entire loan
- Pursues personal guarantees
- May force sale or bankruptcy

Days 30-45: Default enforcement
- Lender sends acceleration notice
- Company has [ACCELERATION_NOTICE_DAYS] days to cure or repay
- Lender may file suit or pursue guarantors
- Company explores options: refinance, raise equity, sell

Days 45+: Resolution
- Company repays loan (curing default)
- Company refinances with different lender
- Company files bankruptcy
- Lender recovers portion via personal guarantees
```

### Covenant Breach Negotiation

**Founder options when breach detected:**

#### Option 1: Cure Naturally (Best)
- Revenue covenant breach by 5%
- Q2 was miss; Q3 tracking to beat covenant
- Lender likely waives if trajectory correct
- Action: Provide forward guidance; stay transparent

#### Option 2: Temporary Waiver + Cure Plan (Good)
- Burn rate exceeded due to planned hiring
- Hiring was approved by lender; just happened sooner than expected
- Offset by revenue tracking above target
- Action: Explain variance; show offsetting positive; request temporary waiver

#### Option 3: Covenant Amendment (Necessary)
- Covenant too tight given market conditions
- Revenue covenant of $500K unrealistic; market only supports $450K
- Company restructuring; burn rate permanently higher
- Action: Propose new covenant levels based on new reality; lender agrees (or disagrees)

#### Option 4: Additional Collateral/Security (Last Resort)
- Covenant breach serious but relationship worth saving
- Lender demands additional personal guarantee or security
- Founder accepts additional risk to keep company operating
- Action: Agree to additional guarantees; formalize amendment

#### Option 5: Refinance or Payoff (If Necessary)
- Covenant breach irreparable
- Relationship deteriorated; lender demanding repayment
- Company seeks new lender or equity funding to repay
- Action: Line up new financing source; refinance or repay at maturity

---

## Covenant Negotiation Strategies

### Strategy 1: Propose Your Own Covenants

**Instead of accepting lender's proposal:**

```
Lender proposes:
- Min revenue: $500K/quarter
- Max burn: $300K/month
- Min cash: $2M
- DSCR: 1.5x

You counter-propose:
- Min revenue: $450K/quarter (based on YOUR projections)
- Max burn: $350K/month (reflects planned hiring)
- Min cash: $600K (80 days of expense)
- DSCR: 1.25x (only applies if revenue > $1M/quarter)
```

**Why it works:**
- Founder data often more realistic than lender template
- Lender appreciates thoughtfulness
- Shows you've modeled covenant compliance

### Strategy 2: Milestone-Based Relief

**Request covenant relief tied to achievements:**

```
Base covenants (Months 1-12):
- Min revenue: $400K/quarter
- Max burn: $300K/month

Relaxed covenants (Months 13-24) IF:
- Revenue reaches $700K/quarter: Relief to $550K min
- OR raise Series B: Covenant holiday for 6 months

Covenant elimination:
- Upon positive EBITDA
- Upon Series C funding
- If DSCR exceeds 3.0x for 2 consecutive quarters
```

**Why it works:**
- Lender sees you growing into safety
- Removes concern about tight covenants strangling growth
- Incentivizes achievement (hitting milestones = less restrictive covenants)

### Strategy 3: Request Covenant Holiday

**Push for first 12 months with relaxed covenants:**

```
Year 1: Covenant holiday
- Focus on scaling operations
- Build revenue base
- Validate unit economics

Year 2: Active covenants
- Now have 12 months data to base covenants on
- Can accurately forecast
- Can meet realistic targets
```

**Why it works:**
- Lender recognizes first-year chaos is real
- Holiday allows company to scale
- New covenants based on actual 12-month performance (more realistic)

### Strategy 4: Negotiate Cure Flexibility

**Request longer cure periods and cure-related modifications:**

```
Lender proposes: [CURE_DAYS] days to cure covenant breach

You counter:
- [COVENANT_CURE_DAYS] days if operational issue
- [LONGER_CURE_DAYS] days if market-based issue
- Or automatically waived if [SPECIFIC_CONDITION] occurs
- Or covenant increased if remedial action identified
```

**Example:**
```
Burn rate covenant exceeded due to hiring:
- Approved hiring: 3 engineers
- Salary cost: $200K/month
- But revenue tracking above target: +20% vs. projection

Request: "Waive burn rate breach, given revenue overperformance offsets hiring cost"

Alternative: "Amend covenant to $350K (from $300K) to reflect approved headcount"
```

---

## Practical Covenant Management

### Monthly Covenant Tracking

Create simple spreadsheet:

```
COVENANT TRACKING - 2024

Covenant | Target | Jan Actual | Status | Feb Projection | Alert?
---------|--------|-----------|--------|----------------|--------
Min Revenue | $400K | $395K | MISS | $420K | WARN
Max Burn | $300K | $310K | MISS | $295K | WARN
Min Cash | $500K | $580K | OK | $560K | OK
DSCR | 1.5x | N/A | N/A | N/A | N/A

Actions:
- Revenue concern: Forecast miss in Q1; discuss with lender
- Burn concern: Hiring ramp expected to ease in Feb; will recover
- Cash: Fine; no issue
```

### Red Flag Scenarios

**Scenario 1: Revenue declining**
```
Q1: $500K
Q2: $480K (covenant breach -4%)
Q3: $450K (covenant breach -10%)
Q4: $400K (covenant breach -20%)

Action: Contact lender immediately
Lender may: Waive Q1/Q2, renegotiate Q3/Q4 targets lower
Or demand: Plan to fix revenue (product changes, sales plan)
Or enforce: Acceleration of loan
```

**Scenario 2: Burn rate spiking**
```
Normal burn: $250K/month
January: $350K (hiring + bonus payout)
Covenant: Max $300K/month
Breach: 50K over

Action: Explain one-time vs. structural
If one-time: Likely waiver
If structural: Renegotiate covenant upward
```

**Scenario 3: Cash balance dropping**
```
Month 1: $1,000,000 cash
Month 2: $800,000 (burn + investment)
Month 3: $600,000 (continuing burn)
Month 4: $400,000 (large customer invoice paid, cash outflow)
Covenant: Min $500,000

Action: Raise funding before hitting covenant minimum
Or request waiver if temporary (customer payment timing issue)
```

---

## Sample Covenant Scenarios & Outcomes

### Scenario A: Company Growing Faster Than Projected

**Actual performance vs. covenants:**
```
Revenue covenant: $500K/quarter
Actual: $600K (20% beat)

Burn covenant: $300K/month
Actual: $250K (17% beat)

Cash balance: $2M minimum
Actual: $3M (50% above)

Outcome: ALL COVENANTS EXCEEDED
- Lender very happy
- Likely willing to renegotiate if tighter targets needed
- Conversation: "You're performing ahead of expectations. Want to take more debt to accelerate further?"
```

### Scenario B: Company Missing Covenant, But Obvious Why

**Actual performance:**
```
Revenue covenant: $500K/quarter
Actual: $480K (breach -4%)
Reason: Major customer delayed purchase decision by 3 weeks; will close in next quarter ($100K deal)

Burn covenant: OK
Cash balance: OK

Outcome: TECHNICAL BREACH, LIKELY WAIVED
- Lender can see forward looking; revenue clearly will recover
- Requests explanation letter and forecast for next quarter
- Waives breach; continues relationship
- Founder credibility with lender maintained (transparent explanation)
```

### Scenario C: Company Struggling, Covenant Breach Serious

**Actual performance:**
```
Revenue covenant: $500K/quarter
Actual: $350K (breach -30%)
Reason: Product quality issues; customers churning; 2 major customers lost

Burn covenant: BREACHED
Actual: $400K/month (vs. $300K covenant)
Reason: Increased support costs to retain customers

Cash balance: DECLINING RAPIDLY
Actual: $800K (down from $1.5M last quarter)

Outcome: SERIOUS DEFAULT, ENFORCEMENT LIKELY
- Lender concerned; initiates workout discussions
- May demand immediate corrective action (CEO change, restructuring, product fixes)
- May accelerate loan if confidence lost
- May force founder to raise emergency capital or seek acquisition
- Personal guarantees may come under pressure
```

---

## Key Covenant Takeaways

1. **Covenants are real constraints, not suggestions**
   - Breach = potential default
   - Default = acceleration + personal guarantee enforcement
   - Take covenant compliance seriously

2. **Communicate proactively**
   - Don't hide covenant breach until forced
   - Lender appreciates transparency
   - Early communication = more negotiating room

3. **Model covenants before accepting**
   - 24-month forward projection
   - Model downside scenarios
   - Ensure realistic compliance probability

4. **Build buffer into targets**
   - Covenant at 70-80% of projected achievement
   - Allows for 20-30% miss without breach
   - Acknowledges execution risk

5. **Relationship matters**
   - First breach may be waived if relationship good
   - Second breach in same quarter = serious problem
   - Repeated breaches = automatic material default

6. **Request relief when circumstances change**
   - If market changed, renegotiate covenants
   - If business model evolved, adjust targets
   - Lender benefits from company success; willing to work with you

---

*This covenant guide provides detailed explanation of typical venture debt covenants and how to negotiate and manage them. Each deal is unique; consult with startup attorney on specific terms.*
