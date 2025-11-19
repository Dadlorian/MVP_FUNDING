# Venture Debt Investor (Lender) Perspective & Due Diligence Guide

## Venture Debt as an Investment Vehicle

Venture debt funds provide capital to early-stage and growth-stage companies as loans (not equity), with the expectation of:

1. **Interest income**: 10-15% annual return from interest payments
2. **Warrant upside**: Equity participation (10-30% coverage) providing 5-10x exit returns
3. **Portfolio returns**: Need 7-8 successful exits to compensate for 30-40% failure rate

---

## Lender Investment Profile & Risk Tolerance

### Three Types of Venture Debt Lenders

#### 1. Specialized Venture Debt Funds
**Examples:** Horizon Technology Finance, Gold Hill Capital, Silicon Valley Bank
- **Focus:** Venture-backed companies with proven traction
- **Stage focus:** Series A, B, C companies
- **Loan size:** $500K - $10M+
- **Typical terms:** 10-14% interest, 10-20% warrants
- **Approach:** Lenders with venture expertise; understand tech/startup dynamics
- **Risk appetite:** Medium-high (willing to take covenant risks for portfolio)

#### 2. Traditional Banks (with VC lending arms)
**Examples:** JP Morgan, Bank of America, Wells Fargo
- **Focus:** Later-stage, high-revenue companies
- **Stage focus:** Series C+ or pre-IPO
- **Loan size:** $1M - $50M+
- **Typical terms:** 8-12% interest, 5-10% warrants
- **Approach:** Want strong financials, predictable revenue, lower risk
- **Risk appetite:** Low-medium (conservative underwriting)

#### 3. Alternative Finance Providers
**Examples:** Lighter Capital, Clearco (formerly Clearbanc)
- **Focus:** Revenue-based financing (not traditional debt)
- **Stage focus:** Early revenue, bootstrapped companies
- **Loan size:** $50K - $2M
- **Typical terms:** Fixed revenue percentage (3-10% of revenue) until repaid
- **Approach:** Algorithmic underwriting; focus on revenue data
- **Risk appetite:** Medium (more flexible covenants)

---

## Venture Debt Fund Economics

### Portfolio Expected Returns

**Scenario: $100M venture debt fund making 50 investments of $2M each**

| Outcome | # Companies | Per-Company Return | Portfolio Contribution |
|---------|-------------|------|-----|
| **Successful exits (IPO/acq >$100M)** | 5 | 10x on equity | $100M |
| **Good exits (M&A $20-100M)** | 10 | 3x on equity | $60M |
| **Break-even/modest exits** | 15 | 1-2x on equity | $22.5M |
| **Failed companies** | 20 | -100% (lose all) | $0 |
| **Total Portfolio Value** | | | **$182.5M** |
| **Portfolio Return** | | | **1.8x on $100M** |
| **Including interest income** | | | **~2.2x return** |

**Key insight:** Fund needs the successful exits to compensate for failures. Interest income alone (11% × 5 years = ~60% return) is inadequate.

---

## Underwriting Framework for Venture Lenders

### Investment Decision Flowchart

```
Does company have venture backing (VC-funded)?
  NO → Likely too risky; pass
  YES → Continue

Does company have proven product-market fit?
  NO → Wait for traction; pass for now
  YES → Continue

Does company have meaningful revenue ($[MINIMUM_REVENUE_THRESHOLD]+/month)?
  NO → Too early; pass
  YES → Continue

Does company have path to Series B in 12-18 months?
  NO → Can't repay debt; pass
  YES → Continue

Is DSCR (Debt Service Coverage Ratio) > [MINIMUM_DSCR]x?
  NO → Can't service debt; pass or reduce loan amount
  YES → Continue

Do you have competitive term sheet vs. other lenders?
  NO → Negotiate or pass
  YES → Proceed to investment committee

Does IC approve? → OFFER TERM SHEET
```

---

## Detailed Underwriting Criteria

### 1. Revenue Traction & Growth

**Key metrics lenders evaluate:**

**Absolute revenue level:**
- Minimum: $[MINIMUM_REVENUE_FOR_VENTURE_DEBT]/month
- Sweet spot: $[SWEET_SPOT_REVENUE_MIN] - $[SWEET_SPOT_REVENUE_MAX]/month
- Above $[HIGH_REVENUE]/month: Typically other funding options available

**Revenue growth rate:**
- Expected: 10%+ month-over-month
- Minimum acceptable: 5% MoM (too slow = can't grow into debt repayment)
- Red flag: <0% MoM (declining; indicates problems)

**Revenue predictability:**
- Standard deviation: <20% month-to-month variation (consistent)
- Seasonal variations: Acceptable if clearly understood and modeled
- Customer concentration: No single customer >30% of revenue (too risky)

**Revenue composition:**
- **Recurring revenue**: Highly valued (SaaS, subscriptions)
  - Predicability: Can forecast 12 months ahead
  - Growth potential: Can estimate churn + new ARR

- **Project-based revenue**: Moderate value (consulting, services)
  - Predictability: Harder to forecast
  - Growth: Depends on sales pipeline

- **Transactional revenue**: Lowest value (e-commerce, one-time sales)
  - Predictability: Difficult
  - Growth: Uneven

**Sample calculation: Debt sizing based on revenue**
```
Expected annual revenue: $2,000,000
Typical debt sizing: 30-50% of annual revenue = $600K - $1M
Lenders want: Multiple (debt ÷ annual revenue < 0.5x)
Borrower debt service: ~$15K/month (at 12% + amortization)
Monthly revenue: $166K
Debt service coverage: $166K ÷ $15K = 11x (very healthy)
→ Lender comfortable with $600K-$1M loan
```

### 2. Unit Economics

**What lenders understand:**
- **Customer Acquisition Cost (CAC)**: Cost to acquire one customer
- **Customer Lifetime Value (LTV)**: Total revenue from one customer over lifetime
- **LTV:CAC Ratio**: Should be 3:1 or better
- **Payback period**: Months to recover CAC from customer revenue

**Why it matters:**
- If CAC = $500 and LTV = $1,500 (3:1 ratio), model is sustainable
- If CAC = $500 and LTV = $600 (1.2:1 ratio), can't sustain growth
- Lender wants to see improving unit economics over time

**Lender's underwriting:**
```
CAC: $1,000
LTV: $3,000
LTV:CAC: 3:1 ✓ (acceptable)

Annual revenue per customer: $1,200
Payback period: $1,000 ÷ ($1,200/12) = 10 months
Growth sustainable for 12+ months: ✓ (yes; not burning out CAC)

Debt capacity assessment:
- Can support debt service from existing customers
- Can invest more in CAC for growth → expand revenue further
- Multiple funding options available ✓
```

### 3. Burn Rate Analysis

**Lender's perspective:**
- Not alarmed by burn rate (different than equity investors)
- Focus: Can burn rate be supported by cash raised + debt?

**Key calculations:**

**Months of runway:**
```
Current cash: $1,000,000
Monthly burn: $250,000
Current runway: 1,000,000 ÷ 250,000 = 4 months (RED FLAG)

With $500K debt financing:
Total cash: $1,500,000
New runway: 1,500,000 ÷ 250,000 = 6 months (still concerning)
```

**Lender's concern:** If company only has 4-6 months runway, will it survive long enough to grow into debt repayment?

**Acceptable scenarios:**
- 12+ months runway + debt = 18+ months total (safe)
- Growing revenue + debt = can extend runway while growing
- Clear Series B path = even if low runway, can refinance

### 4. Business Model Assessment

**Lenders prefer:**

**Recurring revenue models** (best for debt):
- SaaS with monthly/annual subscriptions
- Predictable MRR (Monthly Recurring Revenue)
- Low churn (<5% MoM)
- Ability to forecast 12 months revenue

**Examples:**
- Project management software: $[MONTHLY_ARR] ARR, 95% retention → Excellent
- Data analytics platform: $[MONTHLY_ARR] ARR, 92% retention → Good
- Consulting services: $[PROJECT_BASED] project revenue → Acceptable

**Avoid:**
- Marketplace with high churn
- Hardware sales (one-time revenue; hard to repay debt)
- Highly cyclical businesses
- Businesses dependent on single partnership

### 5. Market & Competitive Position

**Lenders analyze:**

**Market size (TAM):**
- Must be large enough for $[MINIMUM_TAM] (allows growth without commoditization)
- Too small = can't grow into debt repayment

**Competitive position:**
- Unique value prop: vs. [MAJOR_COMPETITOR], we have [DIFFERENTIATION]
- Not commoditized: Ability to command premium pricing
- Defensibility: Patent, network effects, or switching costs

**Market conditions:**
- Growing market: Better for growth
- Flat/declining market: Company must take share from competitors (harder)

### 6. Management Team Assessment

**Lender evaluates:**

**CEO/Founder qualifications:**
- Prior startup experience? (1st-time founders = higher risk)
- Industry expertise? (Domain knowledge helps execution)
- Track record of raising capital? (Ability to secure Series B matters)
- Management team stability? (Key team departures = risk)

**Team composition:**
- CEO + CTO (if tech company): Strong technical + business
- CEO + Head of Sales: Strong go-to-market
- CEO + CFO: Financial discipline (important for debt management)
- Gaps: Missing functional leaders = red flag

**Example assessment:**
```
CEO: Built and exited 2 prior startups; 15 years in space ✓
CTO: Led engineering at [MAJOR_COMPANY]; strong technical depth ✓
COO: First startup; previously consultant ✓
CMO: Recently hired from competitor; strong sales network ✓

Assessment: Strong team, experienced leadership, good functional coverage → Lower risk
```

### 7. Financial Covenants & Debt Service Coverage

**Lenders model debt service:**

**Debt service coverage ratio (DSCR):**
```
DSCR = EBITDA ÷ Debt Service

EBITDA: Earnings Before Interest, Taxes, Depreciation, Amortization
Debt Service: Principal + Interest payments (typically annual)

Minimum acceptable DSCR: 1.5x
Healthy DSCR: 2.0x+
Excellent DSCR: 3.0x+
```

**Example:**
```
Company with $2M revenue, $500K EBITDA
Debt: $500K at 12%, 4-year amortization
Annual debt service: $150K (principal) + $60K (interest) = $210K
DSCR: $500K ÷ $210K = 2.4x ✓ (healthy; lender approves)

vs.

Company with $1M revenue, $100K EBITDA
Same debt: $500K
Annual debt service: $210K
DSCR: $100K ÷ $210K = 0.48x ✗ (can't service debt; reject)
```

**What lenders do:**
- Require minimum DSCR of [MINIMUM_DSCR]x (typically 1.25-1.5x)
- If projected DSCR below threshold, reduce loan amount or decline
- May require [COVENANT_HOLIDAY] months before DSCR covenant becomes active

---

## Due Diligence Checklist for Venture Lenders

### Financial Due Diligence

**Documents required:**
- [ ] Last 24 months of audited/reviewed financials
- [ ] Latest monthly financial statements (within 30 days)
- [ ] Detailed P&L (showing revenue by customer, expense breakdown)
- [ ] Cash flow statement (understanding cash burn pattern)
- [ ] 36-month financial projections (monthly detail)
- [ ] Tax returns (last 2 years)
- [ ] Budget vs. actual variance analysis

**Analysis performed:**
- [ ] Revenue trend analysis (growth rate, consistency)
- [ ] Burn rate analysis (monthly, quarterly trend)
- [ ] Unit economics (CAC, LTV, payback period)
- [ ] Cash flow modeling (including debt service)
- [ ] Covenant compliance modeling (24 months forward)
- [ ] Stress testing (what if revenue 20% below projection?)

### Business Due Diligence

**Documents required:**
- [ ] Capitalization table (latest version, fully diluted)
- [ ] Board resolutions (approving debt financing)
- [ ] Key customer contracts (top [X] customers)
- [ ] Material supplier/vendor contracts
- [ ] Employee agreements (non-compete, IP assignment)
- [ ] Lease agreements (office, equipment)
- [ ] Insurance policies (general liability, cyber, etc.)

**Analysis performed:**
- [ ] Customer concentration analysis (% revenue from top [X] customers)
- [ ] Contract terms review (renewal dates, termination provisions)
- [ ] Customer health assessment (retention, NPS, satisfaction)
- [ ] Sales pipeline review (forecast accuracy vs. actual)
- [ ] Pricing analysis (rate of price increases, competitive positioning)

### Legal Due Diligence

**Documents required:**
- [ ] Certificate of good standing
- [ ] Articles of incorporation and bylaws
- [ ] Shareholder agreements
- [ ] Board minutes (last [X] meetings)
- [ ] Employment agreements (especially executives)
- [ ] IP assignment agreements
- [ ] List of all contracts > $[THRESHOLD]
- [ ] Litigation disclosure memo

**Analysis performed:**
- [ ] Entity structure review (single entity vs. subsidiary complications)
- [ ] Capital structure review (preferred stock rights, liquidation preferences)
- [ ] IP ownership verification (patents registered, trademarks assigned)
- [ ] Litigation risk assessment (pending or threatened claims)
- [ ] Regulatory compliance (licenses, permits, compliance status)

### Technical Due Diligence (for tech companies)

**Documents/Access required:**
- [ ] Code repository access (sample review, code quality)
- [ ] Architecture documentation (scalability assessment)
- [ ] Security audit (recent penetration testing, vulnerability assessment)
- [ ] Infrastructure overview (cloud, self-hosted, scalability)
- [ ] Product roadmap (technical risks, dependencies)

**Analysis performed:**
- [ ] Scalability assessment (can platform scale to support projected growth?)
- [ ] Technical debt assessment (how much refactoring required?)
- [ ] Security posture (is data adequately protected? GDPR compliant?)
- [ ] Key person risk (how dependent on single engineer?)
- [ ] Open source compliance (any GPL or problematic licenses?)

### Market & Competitive Due Diligence

**Research performed:**
- [ ] Market size verification (TAM analysis)
- [ ] Competitive landscape analysis (who are main competitors?)
- [ ] Company positioning analysis (unique value prop assessment)
- [ ] Customer interviews (speak with [X] customers about product/company)
- [ ] Industry trends (is market growing, flat, or declining?)

**Key questions:**
- Is the market large enough? (Need $[MINIMUM_TAM]+ TAM)
- Is the market growing? (Growth >0% annually)
- What's the competitive threat? (Can they compete against [MAJOR_COMPETITOR]?)
- How likely is market adoption? (Product resonating with customers?)

---

## Covenant Design from Lender Perspective

### Why Covenants Matter to Lenders

Covenants are the lender's **early warning system** for company distress:

- **Revenue covenant** signals market problem (customer loss, product issue)
- **Burn rate covenant** signals profitability problem (spending too much)
- **Cash balance covenant** ensures minimum liquidity to pay debt
- **Leverage ratio covenant** prevents company from taking on too much total debt

**Lender perspective:** Covenant breach = Time to intervene before full default

### Typical Covenant Structure

**Financial covenants (measured quarterly):**

1. **Minimum quarterly revenue**: $[REV_COVENANT]/quarter
   - Lender concern: Revenue stalling indicates trouble
   - Tolerance: 10-15% miss; beyond that, discuss cure plan

2. **Maximum monthly burn**: $[BURN_COVENANT]/month
   - Lender concern: Burn increasing = cash depleting faster
   - Tolerance: Temporary spike okay if explained

3. **Minimum cash balance**: $[CASH_COVENANT]
   - Lender concern: Cash <[MONTHS] months operating expense = danger zone
   - Tolerance: Zero; non-negotiable

4. **Debt service coverage**: >1.5x
   - Lender concern: EBITDA declining means less ability to repay
   - Tolerance: Temporary dip if growth trajectory still strong

**Negative covenants:**
- No additional debt without approval
- No change of control without consent
- No asset sales >$[THRESHOLD]
- No related-party transactions

**Why strict?** Lenders want to prevent founder dilution decisions that harm repayment ability.

### Covenant Breach Consequences

**Upon breach, lender has options:**

1. **Waive breach** (informal)
   - Most common for first breach
   - Shows flexibility; maintains relationship
   - Requires explanation + cure plan

2. **Formal waiver** (documented)
   - Written waiver document
   - May include conditions (e.g., higher interest rate for remainder of term)
   - Creates record

3. **Accelerate debt** (nuclear option)
   - Declare entire remaining balance due immediately
   - Only if relationship has broken down or serious concern
   - Could force company into bankruptcy

**Lender's decision framework:**
```
Is breach serious (e.g., revenue covenant -50%)?
  YES → High risk; may accelerate
  NO → Continue

Is breach founder problem or market problem?
  Founder problem (overspent, didn't plan) → Require corrective action
  Market problem (customer left, market changed) → Negotiate new covenants

Is founder responsive/transparent?
  YES → Willing to work with; waive breach, adjust plan
  NO → Founder hiding issues; escalate, consider acceleration

Has covenant been breached multiple times (2+ in 12 months)?
  YES → Pattern of non-compliance; warning sign
  NO → First/second breach; manageable
```

---

## Default Scenarios & Workout Strategy

### Scenario 1: Revenue Miss (Recoverable)

**Situation:**
- Revenue covenant: $500K/quarter
- Actual: Q2 hit $475K (5% miss, breached)
- Root cause: Major customer delayed deployment; will come online Q3

**Lender action:**
- Request detailed plan for Q3 (how will you make up shortfall?)
- Request weekly revenue updates for Q3
- Consider waiving covenant breach if Q3 recovers
- May increase monitoring (monthly calls instead of quarterly)

**Outcome:** Likely waiver; company recovers, relationship continues

---

### Scenario 2: Burn Rate Spike (Manageable)

**Situation:**
- Burn covenant: $200K/month
- Actual: $250K in one month due to bonuses
- Lender approved hiring that caused permanent increase to $220K/month

**Lender action:**
- Formally waive month with spike
- Amend covenant to $220K/month (reflecting approved hiring)
- Request employee productivity metrics/milestones achieved

**Outcome:** Negotiate and adjust; reflects business reality

---

### Scenario 3: Serious Default (Difficult)

**Situation:**
- Revenue declining month-over-month 20% from Q1 to Q3
- Product issues; key customer lost
- CEO hiding true situation, giving rosy projections
- Cash balance dropping rapidly
- Can't meet burn rate covenant

**Lender action:**
- Demand monthly (not quarterly) reporting
- Board seat / observer rights to increase oversight
- Request detailed turnaround plan
- May reduce burn covenant temporarily while monitoring
- Considering whether to accelerate loan or provide additional support

**Outcomes:**
- **Optimistic**: Company fixes product; revenue stabilizes; lender waives/adjusts covenants
- **Pessimistic**: Company fails; lender pursues personal guarantees; recovers $200K on $1M loan

---

### Scenario 4: Change of Control (Acquisition)

**Situation:**
- Company being acquired by larger company for $20M
- Loan balance: $600K remaining
- Term sheet: Acquisition structured as merger

**Lender action:**
- Warrant holder: Warants exercised or converted to equity; receives acquisition proceeds
- Loan holder: Demand immediate repayment from acquisition proceeds
- Personal guarantees: Released upon repayment

**Typical outcome:**
- Lender receives: Remaining $600K principal + accrued interest (~$70K) + pro-rata warrant proceeds (~$200K equity value)
- Total return: ~$870K on original $1M loan (1.5x+ including interest)

---

## Warrant Exercise Strategy for Lenders

### When to Exercise Warrants

#### 1. Company Raising Series B

**Trigger:** Company announces Series B funding at $[VALUATION]

**Lender decision:**
```
Series B valuation: $30M (vs. warrant exercise price of $1.00 on $10M prior valuation)
Warrant shares: 100,000 at $1.00 = $100K value (0.3% of $30M)
If not exercised: Warrants in-the-money 3,000% ✓ (definitely exercise)

Exercise method: Cashless (no capital required)
Result: Become shareholder with [WARRANT_SHARE_COUNT] shares
Value: ~$[VALUE] at Series B valuation
```

**Lender action:**
- Exercise all vested warrants immediately before or after Series B closes
- Board rights: Observe Series B investor board discussions
- Information rights: Receive financial reporting, board materials
- Liquidation preference: Junior to Series B (but senior to Common Stock)

#### 2. Company IPO

**Trigger:** Company files IPO, prices at $[PRICE]/share

**Lender decision:**
```
IPO price: $15/share
Warrant exercise price: $1.00
Warrant value (pre-exercise): (15 - 1.00) × 100,000 shares = $1.4M

Options:
a) Exercise immediately, become public shareholder
   - Get 100,000 shares worth ~$1.5M at IPO
   - Immediately subject to 180-day lock-up (if IPO underwriter requires)
   - Can sell after lock-up expires

b) Let warrants stay unexercised
   - Can exercise anytime during [WARRANT_YEARS]-year period
   - Gain from appreciation continues

Strategy: Usually exercise early to get early position; 180-day lock-up is "free" value accumulation
```

**Lender outcome:**
- Typically significant return if company IPO is successful
- Public shares held longer-term (not sold immediately)

#### 3. Company Declining (Down Round)

**Situation:**
- Company raising Series B at $[VALUATION], DOWN from prior $[HIGHER_VALUATION]
- Warrant exercise price: $[EXERCISE_PRICE] (was at-the-money before)
- Now underwater (exercise price > share price)

**Lender decision:**
```
Warrant exercise price: $1.00 (from $10M prior valuation)
Series B price: $0.50 (down-round)
Warrant value: Negative (underwater)

Action: Do NOT exercise (why pay $1.00 for $0.50 shares?)
Keep warrants and hope for recovery later
OR accept loss (lender writedown)
```

---

## Portfolio Management for Venture Debt Funds

### Portfolio Composition

**Healthy venture debt fund portfolio:**

| Company Stage | # Companies | Loan Size | Expected Return | Portfolio %|
|---------------|----------|------|------|-----|
| **Series A** | 15 | $300K-500K | 8-10x on exits | 30% |
| **Series B** | 20 | $500K-2M | 4-6x on exits | 40% |
| **Series C+** | 10 | $2M-5M | 2-3x on exits | 25% |
| **Failed** | 5 | - | -100% | -5% |

**Expected outcomes:**
- Top quartile (Series B/C with exits): 5-10x returns
- Middle quartile (Series B exits): 2-4x returns
- Bottom quartile (failed): 0x returns
- Blended portfolio: 2-2.5x return over fund life

### Concentration Risk Management

**Lender monitors:**

1. **Single company concentration**
   - Limit: No single loan > [CONCENTRATION_LIMIT]% of fund
   - Risk: If one company defaults, impacts portfolio too much

2. **Industry concentration**
   - Limit: No single industry > [INDUSTRY_LIMIT]% of fund
   - Risk: Market downturn hits multiple companies

3. **Geographic concentration**
   - Limit: No single region > [GEO_LIMIT]% of fund
   - Risk: Regional economic problems affect multiple companies

### Exit Planning

**Lender considerations:**

1. **M&A exit** (60-70% of outcomes)
   - Warrant exercised immediately before/after close
   - Loan repaid from acquisition proceeds
   - Lender gets both interest income + warrant proceeds

2. **IPO exit** (10-15% of outcomes)
   - Warrant exercised before IPO
   - Loan repaid from IPO proceeds or cash
   - Lender holds public shares post-IPO
   - Can realize significant appreciation

3. **Failed exit** (15-25% of outcomes)
   - Loan defaulted; recovery attempted
   - Warrant expired worthless
   - May recover 10-30% via asset liquidation/personal guarantees

---

## Best Practices for Venture Debt Lenders

### 1. Relationship Management

- Regular contact with borrower: Monthly calls (not just quarterly)
- Early intervention on covenant misses: Discuss before official breach
- Transparency: Lender openly discusses concerns, doesn't ambush
- Flexibility: Willing to adjust covenants if fundamentals justify

### 2. Portfolio Monitoring

- Monthly performance dashboard: Track all loans' covenant status
- Quarterly portfolio review: Discussion of problem loans
- Annual covenant adjustments: As company evolves, adjust appropriately
- Risk rating: Track each loan's health on A/B/C/D scale

### 3. Documentation

- Clear, enforceable documents: Avoid ambiguous terms
- Standard templates: Not customized for each deal (easier enforcement)
- Proper UCC filings: Secured personal guarantees properly filed
- Warrant documentation: Clear exercise terms, anti-dilution provisions

### 4. Underwriting Discipline

- Consistent criteria: Same standards for all investments
- Clear rejection reasons: Tell founders why declined (helps refine model)
- Stress testing: Model scenarios (revenue -30%, burn +50%)
- Independent verification: Don't just rely on founder projections

---

## Common Lender Mistakes

### Mistake 1: Inadequate Covenant Monitoring

**Problem:**
- Set quarterly covenants but don't follow up monthly
- Discover revenue covenant breach 3 months late
- Company already in significant distress

**Better practice:**
- Monthly check-in calls (first 12 months)
- Early warning system (revenue trending toward covenant)
- Proactive: Discuss covenant adjustment before breach

### Mistake 2: Lending to Wrong Stage

**Problem:**
- Lend to pre-revenue company (against underwriting guidelines)
- Company can't repay debt; goes bankrupt
- Lender loses principal

**Better practice:**
- Strict stage requirements: Minimum revenue threshold, growth rate
- Decline early-stage companies (let equity investors take that risk)
- Focus on companies with validated business model

### Mistake 3: Insufficient Due Diligence

**Problem:**
- Rush underwriting to close deal quickly
- Miss key risks (major customer leaving, IP liability)
- Company defaults due to unknown risk

**Better practice:**
- Adequate time for due diligence (6-8 weeks minimum)
- Independent verification (don't just ask founder)
- Customer reference calls (talk to customers, not just company)

### Mistake 4: Inadequate Personal Guarantees

**Problem:**
- Lender has personal guarantee but doesn't properly document
- Founder disputes guarantee at default
- Difficult to enforce personal guarantee

**Better practice:**
- Clear personal guarantee in loan documents
- Proper UCC filings for any pledged personal assets
- Guarantee explicitly survives bankruptcy
- Get guarantee insurance (if available)

### Mistake 5: Weak Covenant Negotiations

**Problem:**
- Accept whatever covenants founder proposes
- Covenants too loose to actually warn of problems
- Revenue covenant only 10% below forecast (no buffer)
- Discover problems too late

**Better practice:**
- Propose specific covenant numbers based on underwriting
- Build 20-30% buffer into covenants
- Monitor actual vs. projected covenant metrics
- Adjust covenants after first 12 months based on actual performance

---

## Key Takeaways for Venture Debt Lenders

1. **Venture debt portfolio returns driven by exits, not just interest**
   - Need 7-8 successful exits per failed company
   - Interest income (10-15%) must be supplemented by equity upside (warrant returns)
   - If not confident in equity appreciation, pricing/warrant coverage is insufficient

2. **Borrower success is lender success**
   - Lender benefits from company growth (warrant value increases)
   - Lender incentivized to support borrower's success
   - Covenants are guardrails, not straightjackets (adjust when appropriate)

3. **Covenant design is critical to portfolio health**
   - Early warning system for problems
   - But too restrictive = company fails; too loose = miss problems
   - Requires calibration to specific company/industry

4. **Personal guarantees often have low recovery value**
   - Founders rarely have sufficient personal assets
   - In bankruptcy, personal guarantee behind all other claims
   - Realistic recovery on guarantee: 10-30% of loan amount
   - Don't rely on guarantee as primary loss mitigation

5. **Warrant exercise timing can significantly impact returns**
   - Exercise too early = miss appreciation potential
   - Exercise too late (after exit) = miss opportunity
   - Clear, automatic exercise triggers prevent errors

---

*This investor perspective represents how venture debt funds approach lending to startups. Each fund has different risk tolerance and underwriting criteria.*
