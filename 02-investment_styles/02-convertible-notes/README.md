# Convertible Notes: Comprehensive Guide

## Table of Contents
1. [What Are Convertible Notes?](#what-are-convertible-notes)
2. [How They Work](#how-they-work)
3. [Key Terms Explained](#key-terms-explained)
4. [Founder Risks & Concerns](#founder-risks--concerns)
5. [Investor Risks & Concerns](#investor-risks--concerns)
6. [Common Pain Points](#common-pain-points)
7. [Convertible Notes vs SAFEs](#convertible-notes-vs-safes)
8. [Documentation Index](#documentation-index)

---

## What Are Convertible Notes?

A **convertible note** is a debt instrument that functions like a hybrid between a loan and equity investment. It's primarily used in early-stage financing to defer valuation discussions until the company is in a stronger position to be valued.

### Key Characteristics:
- **Debt instrument** - initially structured as a loan
- **Future equity conversion** - converts to equity at a predetermined event (typically a Series A round)
- **Deferred valuation** - avoids establishing a valuation at the seed/early stage
- **Fixed maturity date** - must be repaid if not converted to equity
- **Accruing interest** - accumulates interest over time (either simple or compound)

### Why Use Convertible Notes?

**For Founders:**
- Avoids premature valuation discussions
- Faster closing process than equity rounds
- Less legal complexity than priced equity rounds
- Demonstrates investor confidence

**For Investors:**
- Conversion discount - rewards early-stage risk with equity discount
- Valuation cap - limits conversion valuation
- Interest accrual - provides return if company doesn't convert
- Standardized approach - widely used in startup ecosystem

---

## How They Work

### Typical Timeline

```
Year 0-1: Seed Stage
├─ Founder needs capital ($100K-$1M)
├─ Company valuation uncertain
└─ Convertible note issued to investors

      ↓

Year 1-2: Growth Stage
├─ Company performs well
├─ Series A round initiated
├─ Valuation now established at $10M
└─ Note automatically converts to equity

      ↓

Year 2+: Post-Conversion
├─ Investor holds equity stake
├─ No debt obligation remains
└─ Standard equity governance applies
```

### Conversion Mechanics

**Scenario: $500K Convertible Note**

```
Investment Details:
  Principal: $500,000
  Interest Rate: 8% annually (simple)
  Maturity: 3 years
  Discount: 20%
  Valuation Cap: $5,000,000

After 18 months:
  Accumulated Interest = $500,000 × 8% × 1.5 = $60,000

Series A Financing Occurs:
  Series A valuation: $10,000,000

Conversion Calculation:
  Option A - Using Discount:
    Conversion price = Series A price × (1 - 20%) = $X × 0.80
    Investor gets discount advantage

  Option B - Using Valuation Cap:
    Conversion price = $5,000,000 / fully-diluted shares
    Investor is protected from high valuation

  Whichever is MORE FAVORABLE to investor is used

Result:
  Investor converts $560,000 (principal + interest) to equity shares
  Share count = $560,000 / Conversion Price
```

---

## Key Terms Explained

### Principal Amount
- **Definition**: The initial loan amount borrowed
- **Impact**: Directly determines equity stake size at conversion
- **Example**: $500K principal → converts to shares worth ~$500K (plus discount benefit)

### Interest Rate
- **Definition**: Annual percentage charged on principal
- **Typical Range**: 3-8% for seed/early-stage
- **Simple vs Compound**:
  - Simple interest = Principal × Rate × Time
  - Compound interest = Principal × (1 + Rate)^Time
- **Impact**: Increases amount converted to equity or repayment obligation

### Maturity Date
- **Definition**: Date when note must be repaid if not converted
- **Typical Duration**: 2-5 years
- **Practical Reality**:
  - If no Series A by maturity = tension point
  - May trigger mandatory repayment
  - Often extended in practice

### Conversion Mechanics

#### Discount
- **Definition**: Percentage reduction on equity purchase price
- **Typical Range**: 15-30%
- **Mechanism**: Investor buys shares at discount to Series A investors
- **Example**:
  - Series A price: $10/share
  - Discount: 20%
  - Convertible note holder pays: $8/share

#### Valuation Cap
- **Definition**: Maximum valuation for conversion calculation
- **Purpose**: Protects investor if company is valued very high
- **Example**:
  - Cap: $5M
  - Series A actual valuation: $15M
  - Uses $5M for conversion calculation
  - Gives investor significantly more shares

#### MFN (Most Favored Nation)
- **Definition**: Automatic upgrade if better terms offered
- **Mechanism**: If another investor gets better discount/cap, you automatically get it too
- **Impact**: Protects early investor from worse treatment

### Pro Rata Rights
- **Definition**: Right to invest in future rounds to maintain ownership percentage
- **Example**: 5% owner gets to invest in Series A to stay at 5%
- **Value**: Avoids dilution for early supporters

### Negative Covenants
- **Definition**: Restrictions on company activities
- **Common Examples**:
  - Cannot incur additional senior debt exceeding $X
  - Cannot change dividend policy without approval
  - Cannot enter related-party transactions above threshold
  - Cannot liquidate/sell company without notifying noteholder
- **Impact**: Limits founder operational flexibility

---

## Founder Risks & Concerns

### 1. Debt on Balance Sheet

**The Problem:**
- Convertible notes appear as debt (liability) on financial statements
- Reduces apparent financial health
- Can impact credit ratings and lender relationships

**Specific Issues:**
- **Debt-to-Equity Ratio**: Deteriorates with each note issued
- **Loan Covenants**: If you have bank debt, may violate financial covenants
- **Audit Complications**: Accountants classify as liability, creates complications
- **Valuation Impact**: Reduces enterprise value perception

**Example:**
```
Balance Sheet Impact:

Without Note:
  Assets: $500K
  Liabilities: $100K
  Equity: $400K
  Debt/Equity: 0.25

With $500K Convertible Note:
  Assets: $1M
  Liabilities: $600K
  Equity: $400K
  Debt/Equity: 1.5x
```

**Mitigation:**
- Negotiate as "convertible note" not "loan" - accounting treatment may differ
- Track likelihood of conversion vs repayment
- Plan for higher Series A valuation to absorb debt

### 2. Mandatory Repayment Obligation

**The Problem:**
- Despite "convertible" name, notes are legally DEBT
- If maturity date arrives without Series A, you MUST repay
- This can trigger existential crisis

**Specific Risks:**
- **Cash Crunch**: Must repay $500K+ on maturity date with zero notice
- **Forced M&A**: May be forced to sell company to repay investors
- **Bankruptcy Risk**: If unable to repay and no acquisition, insolvency follows
- **Investor Conflict**: Early investors can demand repayment vs reinvestment

**Example Timeline:**
```
Year 0: Raise $500K convertible note, maturity = 3 years
Year 1-3: Build product, grow revenue
Year 2.5: Series A discussions begin but move slowly
Year 3.0: Maturity date arrives
  ├─ Series A not closed yet
  ├─ Investor demands $500K+ repayment (plus interest)
  ├─ You have no cash
  └─ CRISIS: Forced acquisition or bankruptcy

Real case: Multiple startups forced to sell at unfavorable terms
when Series A didn't materialize and maturity date arrived
```

**Mitigation:**
- Negotiate longest reasonable maturity (4-5 years ideally)
- Build conversion formula favorable to early maturity closure
- Plan explicit extension clause if Series A in progress
- Ensure you can service repayment from operations by maturity

### 3. Interest Accrual

**The Problem:**
- Interest accrues whether or not company is profitable
- Increases total amount due at maturity or conversion
- Can significantly dilute equity

**Specific Concerns:**
- **Compounding Effects**: If not paid, interest-on-interest
- **Conversion Dilution**: More shares given to investor
- **Repayment Burden**: If maturity hit, must pay principal + interest
- **Long Timelines**: 5-year note at 8% increases obligation by 40%+

**Example:**
```
$500K note @ 8% simple interest over 5 years:

Year 1: $540K (80K interest)
Year 2: $580K (160K interest)
Year 3: $620K (240K interest)
Year 4: $660K (320K interest)
Year 5: $700K (400K interest)

If converted Year 5:
  Investor converts $700K instead of $500K
  You lose 40% more equity than if converted immediately

If repayment required Year 5:
  Must find $700K in cash, not $500K
```

**Mitigation:**
- Negotiate lowest reasonable interest rate (3-5%)
- Prioritize early Series A (conversion before high interest accrual)
- Track interest accumulation in financial projections
- Consider interest-only payments pre-conversion if feasible

### 4. Control Provisions

**The Problem:**
- Convertible notes often include restrictive covenants
- Limit founder operational and strategic flexibility
- Can require investor board seats or approval rights

**Specific Restrictions:**
- **Information Rights**: Required quarterly reporting (time-consuming)
- **Protective Provisions**: Cannot take actions investor disapproves:
  - Sell company
  - Declare dividends
  - Incur new senior debt
  - Change capital structure
  - Liquidate assets
- **Board Observation Rights**: Investors attend board meetings
- **Approval Requirements**: Major decisions need investor consent

**Example:**
```
Typical Control Covenant:

"Company shall not, without written consent of Noteholders
representing >50% of principal:
  1. Incur indebtedness exceeding $250K
  2. Create liens on assets
  3. Sell, merge, or liquidate company
  4. Change CEO or key executive
  5. Declare dividends or distributions
  6. Amend governance documents
```

**Impact on Founders:**
- Cannot quickly pivot strategy
- Cannot take follow-on investments from non-approved sources
- Cannot hire/fire executives without investor input
- Cannot negotiate customer contracts affecting asset use

**Mitigation:**
- Negotiate clear, specific thresholds (not vague "major decisions")
- Request information rights only, not approval rights
- Limit to truly material actions (Series A fundraising, M&A)
- Push back on CEO/hiring decisions - not investor domain
- Sunset approval rights if Series A raised by maturity-2

### 5. Negative Equity Scenario

**The Problem:**
- Interest accrual + valuation cap can create adverse outcomes
- Investor might own significant equity despite small capital
- Can force unfavorable Series A terms

**Example of Negative Equity:**
```
Scenario: 10 convertible notes @ $100K each, 8% interest, 2-year maturity

Year 2:
  Total invested: $1M
  Interest accrued: $160K
  Total due: $1.16M

Company valuation at Series A: $3M

If valuation cap is $3M (and lower than actual Series A discount):
  Each noteholder converts: $120K / cap-derived price
  10 investors convert: $1.2M total

  Company issued equity: $1.2M / $X per share
  If $X = $10/share: 120K shares to early investors on $3M valuation
  = 40% of company to people who invested total $1M

Series A investor at $3M valuation expects to own ~20-25%
But pre-seed investors already own 40%
Result: Series A terms become very expensive, may not occur
```

**Mitigation:**
- Negotiate reasonable valuation caps (3-5x seed investment)
- Limit number of convertible notes issued
- Plan Series A timing carefully
- Consider post-money SAFE instead if multiple seed rounds

---

## Investor Risks & Concerns

### 1. Default Risk

**The Problem:**
- Company might fail before Series A or maturity
- Unsecured debt (usually) - no collateral
- Early-stage companies have high failure rates

**Specific Risks:**
- **Total Loss**: If company fails, you're back of line (junior to employees, vendors)
- **No Collateral**: Unlike bank loans, usually unsecured
- **Preference Stack**: Equity holders and other creditors may come first
- **Asset Liquidation**: Little valuable assets to claim in bankruptcy

**Example:**
```
Scenario: Company fails Year 1

Liquidation waterfall:
  1. Taxes & employee wages: $500K
  2. Vendor payables: $300K
  3. Bank debt (senior): $200K
  4. Landlord obligations: $100K
  5. Convertible noteholders (junior debt): ???
  6. Equity shareholders: $0

Remaining assets: $100K
Noteholders owed: $1.16M (from example above)
Recovery: ~9% (vs equity holders = 0%)
```

**Mitigation:**
- Conduct thorough due diligence on company fundamentals
- Diversify - don't put all capital in one convertible note
- Monitor company progress quarterly
- Negotiate information rights (financial statements, updates)
- Have clear early warning indicators

### 2. Conversion Price Uncertainty

**The Problem:**
- Final equity stake depends on Series A terms you don't control
- Conversion mechanism can be complex
- Founders might negotiate unfavorable Series A pricing

**Specific Concerns:**
- **Down Rounds**: Series A at lower valuation than cap
  - You get more shares (good)
  - But company is worth less (bad - your investment worth less)

- **High Valuation**: Series A at higher than expected
  - Your conversion price is higher
  - You get fewer shares than hoped
  - May give you less ownership than anticipated

- **No Series A**: Worst case - company never raises Series A
  - Note may mature
  - Forced repayment scenario
  - Or company winds down

**Example:**
```
Invested: $100K convertible note
Cap: $5M
Discount: 20%

Scenario A - Series A at $10M:
  Uses cap: $5M / shares outstanding = conversion price
  You get more shares than if no cap

Scenario B - Series A at $3M (down round):
  Uses $3M / shares (not capped)
  You get fewer shares
  But company is in trouble (equity worth less)

Scenario C - No Series A by Year 4:
  Must repay principal + interest
  But company growing revenue
  Tempting to ask for equity stake instead
  Negotiation ensues
```

**Mitigation:**
- Understand cap/discount mechanics fully
- Model multiple Series A scenarios
- Negotiate strong anti-dilution protections
- Get MFN clause for future better terms
- Have exit timeline expectations clear

### 3. Subordination to Senior Debt

**The Problem:**
- Convertible notes are typically JUNIOR debt
- Senior debt (like bank loans) gets repaid first
- You're last in line after employees, vendors, senior creditors

**Specific Risks:**
- **Priority in Bankruptcy**: Senior creditors get paid before you
- **Covenant Restrictions**: Cannot take equity position until senior debt repaid
- **Refinancing Risk**: Company might take senior debt that you're subordinate to
- **Liquidation Waterfall**: You come after many other parties

**Scenario:**
```
Company debt structure:

Tier 1 (Senior): $2M bank loan
  ├─ Secured by assets
  └─ Gets paid first in liquidation

Tier 2 (Subordinate): $1M convertible notes
  ├─ Unsecured
  ├─ You are here
  └─ Gets paid after senior debt

If company fails with $500K assets:
  Bank gets all $500K
  You (convertible holder) get $0
```

**Mitigation:**
- Understand full capital structure (senior vs subordinate debt)
- Negotiate subordination agreement terms
- Set limits on senior debt company can incur
- Review how senior debt impacts your conversion rights
- Get information rights on senior debt covenants

### 4. Limited Governance Rights

**The Problem:**
- As noteholder (not equity holder), you have limited control
- Cannot vote on board seats
- Cannot influence major decisions
- Limited visibility into operations

**Specific Concerns:**
- **No Board Seat**: Cannot influence strategy directly
- **Information Rights Only**: Rely on company for updates (may not be detailed)
- **Preference Cascade**: Equity holders make decisions that hurt noteholders
- **Liquidation Preferences**: Cannot negotiate your seniority in down scenario

**Typical Rights Structure:**
```
Equity Shareholder:
  ✓ Board seat
  ✓ Vote on major decisions
  ✓ Receive dividends (if declared)
  ✓ Approve new capital structures
  ✓ Protective provisions on major changes

Convertible Noteholder:
  ✓ Information rights (financial statements)
  ✓ Conversion rights
  ✓ Repayment if no conversion
  ✗ No board seat
  ✗ No voting rights
  ✗ No dividend rights
  ✗ Limited approval rights
```

**Mitigation:**
- Negotiate board observation rights (attend but don't vote)
- Get strong information rights - monthly/quarterly updates
- Include protective provisions (cap on new debt, etc.)
- Get pro-rata rights for Series A (maintain ownership %)
- Build investor network with other noteholders for collective action

### 5. Maturity Date Risk (Investor Perspective)

**The Problem:**
- If Series A doesn't happen by maturity, you must decide:
  - Accept repayment (unlikely - founders don't have cash)
  - Extend note (founder-friendly, dilutes your position)
  - Convert to equity at unfavorable terms
  - Accept company sale at low valuation

**Specific Issues:**
- **Repayment Non-Payment**: Company unable/unwilling to pay
- **Forced Extension**: Maturity extended, pushing your return timeline back
- **Equity Conversion at Loss**: Forced to convert at very high prices
- **Company Stress**: Maturity creates tension, may impact operations

**Example:**
```
Timeline:

Year 0: Invest $100K, maturity Year 3
Year 1: Company growing well
Year 2: Series A discussions begin
Year 2.5: Series A stalls (market conditions, revenue miss, team issues)
Year 3.0: MATURITY DATE
  Company options:
  A) Repay $112K (+ 8% interest) - no cash, not possible
  B) Extend maturity 2 more years - delays your return
  C) Convert to equity at high price - expensive for founders
  D) Take acquisition offer - may be below expectations

Your negotiation position weakens - you need exit, they need time
May accept poor terms to move forward
```

**Mitigation:**
- Negotiate extension terms in advance (automatic 2-year extension, etc.)
- Include mandatory conversion trigger (if not converted by maturity, converts to equity)
- Get clear pathway to Series A (not vague "we'll fundraise")
- Diversify across multiple notes - some will mature badly
- Track company progress toward Series A milestones

---

## Common Pain Points

### 1. Maturity Date Extensions

**The Problem:**
- Series A often doesn't close by original maturity
- Founder scrambling, investor frustrated
- Requires bilateral renegotiation under pressure

**Why It Happens:**
- Series A timelines slip (market conditions, due diligence)
- Company slightly underperforms growth targets
- Founders delayed Series A preparation
- Multiple convertible notes create coordination problems

**How It's Resolved:**
```
Typical Extension Request:

Founder: "Series A is 2 months from closing, need maturity extension"
Investor: "For how long?"
Founder: "6 months to cover delayed timeline"
Investor: "What's my incentive? My maturity date just got pushed back"
Founder: "We'll increase interest rate 2% and give you additional shares
         as warrant coverage"

Negotiated outcome:
  New maturity: Original date + 6 months
  New interest: 8% → 10%
  Warrant coverage: 15% of conversion amount as warrant shares
```

**Mitigation:**
- Build in automatic 12-month extension clause (not ideal, but realistic)
- Trigger automatic equity conversion if not converted by maturity
- Tier interest rate increases (goes up 1% each year after initial maturity)
- Get clear Series A timeline discussion upfront

### 2. Interest Rate Negotiations

**The Problem:**
- No standard interest rate exists (3-12% across market)
- Creates tension between "fair" early-stage rate vs investor need for return
- Compound interest can become onerous

**Factors Affecting Rate:**
- **Company Stage**: Pre-revenue = higher rate (5-8%)
- **Founder Credentials**: Known team = lower rate (3-5%)
- **Market Conditions**: Boom market = lower rates; dry market = higher
- **Investor Type**:
  - Accelerators: 0-2% (favor conversion)
  - Angel investors: 4-8% (balance debt/equity)
  - Institutional: 3-6% (standardized)

**Rate Comparison:**
```
$500K @ different rates over 3 years:

3% simple: $545K owed (9% total cost)
5% simple: $575K owed (15% total cost)
8% simple: $620K owed (24% total cost)
10% simple: $650K owed (30% total cost)

10% compound: $665K owed (33% total cost)
```

**Tension Points:**
- Founder: "8% is like a predatory loan rate"
- Investor: "Early-stage risk justifies 8%+ return"
- Reality: Both parties compromise at 5-7%

**Mitigation:**
- Research market standard rates (check AngelList, Carta)
- Tier interest rate: 3% years 1-2, 5% years 2-3, 8% after maturity
- Use simple interest not compound (lower effective rate)
- Negotiate interest paid annually (not accrued) if possible
- For strong teams, push for 4-5% standard rate

### 3. Qualified Financing Thresholds

**The Problem:**
- "Qualified Financing" triggers conversion
- Different investors define this differently
- Vague definitions create disputes

**Common Definitions:**
```
"Qualified Financing shall mean a Series A or later priced equity
financing in which:
  (a) Company raises minimum [PLACEHOLDER: $500K-$2M] in one round
  (b) Investor is a professional VC firm
  (c) Company is valued at minimum [PLACEHOLDER: $3M-$10M]
  (d) Financing includes standard investor rights (board seat, etc.)

If not "qualified", note does NOT automatically convert"
```

**Pain Point Examples:**

**Scenario 1: Questionable Financing**
```
Company raises $800K from angels at $2.5M valuation
- Founder: "This is a Series A, should trigger conversion"
- Early investor: "No professional VCs, doesn't count as Qualified"
- Outcome: Note does NOT convert, remains as debt
- Problem: Company now has both seed debt + equity, balance sheet confusing
```

**Scenario 2: Multiple Small Rounds**
```
Year 1: Raise $200K from angel group (not Qualified)
Year 2: Raise $300K from more angels (not Qualified)
Year 3: Raise $500K from VC (now Qualified)

Investor dilemma:
- Convert based on latest round?
- Use average valuation?
- Apply conversion discount to historical Series A?
- Multiple conversions cause dilution
```

**Scenario 3: Down Round Triggered as Qualified**
```
Series A "down round" - company valued at $2M (less than seed)
Is this Qualified? Technically yes if meets $X minimum

Investor stuck:
- Convert at expensive price (Series A was down round)
- Hold note and hope for better Series B
- Disagree with founder on definition
```

**Mitigation:**
- Define Qualified precisely:
  - Minimum raise amount: $1.5M-$2M
  - Valuation minimum: 4-6x seed round raise
  - Lead investor requirement: Named VC firm
  - Include specific mechanics (discount applies, etc.)
- Get MFN clause: if ANY financing is better, you get that instead
- Build in clear conversion formula for non-Qualified financings
- Have pre-agreed escalation for disputes

---

## Convertible Notes vs SAFEs

### Quick Comparison

| Feature | Convertible Note | SAFE |
|---------|------------------|------|
| **Debt?** | Yes - legally binding debt | No - contractual right only |
| **Maturity Date** | Yes - must repay or convert | No - no maturity |
| **Interest Accrual** | Yes - typically 3-8% annually | No - no interest |
| **Bankruptcy Risk** | Higher - you're creditor | Lower - no debt claim |
| **Founder Accounting** | Liability on balance sheet | Off-balance sheet |
| **Founder Cash Pressure** | Higher - must service debt | Lower - no payment obligation |
| **Investor Rights** | More control (info rights, covenants) | Limited - mostly passive |
| **Timeline to Equity** | Months/years until conversion | Typically at Series A |
| **Legal Complexity** | Higher - debt documents | Lower - simpler agreement |
| **Investor Downside** | Some protection - debt payment | Minimal - only equity conversion |

### Detailed Comparison

#### Convertible Note

**Best For:**
- Founders with existing relationships who can manage investor relationships
- Companies planning to raise Series A in 18-24 months
- Situations where investors want some downside protection
- When company has recurring revenue (can potentially service debt)

**Founder Pros:**
- Investors likely to convert (not repay)
- Deferred valuation discussion
- Relatively quick closing

**Founder Cons:**
- Appears as debt on balance sheet
- Interest accrual increases equity dilution
- Maturity date creates pressure point
- Default obligations if maturity hit
- Requires balance sheet liability accounting

**Investor Pros:**
- Downside protection (interest + conversion discount)
- Debt seniority (even if junior, still debt)
- Conversion discount + cap provides multiple protections
- Information rights and covenants possible
- Higher return potential (interest + equity upside)

**Investor Cons:**
- Subordinate to senior debt
- Maturity date creates conversion uncertainty
- Only converts if company reaches Series A
- Limited governance (non-equity holder)

#### SAFE (Simple Agreement for Future Equity)

**Best For:**
- Founders who want truly no-obligation funding
- First checks in angel round (no follow-on investors yet)
- Y Combinator cohort (standard format)
- Companies uncertain about Series A timeline
- Situations where you want investor participation without debt

**Founder Pros:**
- No debt on balance sheet
- No interest accrual
- No maturity date pressure
- No repayment obligation ever
- Truly non-dilutive until Series A
- Simpler agreement (less legal work)

**Founder Cons:**
- Unclear investor rights (post-money SAFEs create equity-like rights)
- May end up with many SAFEs + later equity round = complexity
- Investor expectations may be high (for "non-dilutive" round)
- No debt seniority to investors (less protection)

**Investor Pros:**
- Simple, standardized agreement
- No maturity date (patience available)
- Lower legal costs
- Simpler to understand

**Investor Cons:**
- No debt protection (equity-like risk)
- No interest return (pure equity play)
- No conversion discount (loses advantage vs Series A investors)
- Limited governance rights
- Higher loss potential if company fails pre-Series A

### When to Use Each

**Use Convertible Notes if:**
```
✓ You have previous investor relationships (they expect notes)
✓ You want multiple protections: discount + cap + interest
✓ Series A likely in 18-24 months (clear conversion path)
✓ You're in early-stage but have some revenue traction
✓ You want faster negotiations (standardized format)
```

**Use SAFEs if:**
```
✓ This is first outside capital check
✓ Y Combinator funded or similar
✓ You genuinely don't know Series A timeline
✓ You want truly no-obligation capital structure
✓ Investors are angels comfortable with simplicity
✓ You want lower legal complexity
```

**Use Equity Round if:**
```
✓ Company has strong traction (revenue, users, etc.)
✓ You know valuation is defensible
✓ You're raising $2M+
✓ You want clarity on investor rights/governance
✓ This is Series A or later (investor expects equity)
```

### Real-World Scenarios

**Scenario 1: First Seed Round**
```
Founder raises $250K from angels

Option A - SAFE:
  ✓ Simple, quick
  ✓ No debt burden
  ✗ Investors have limited protection
  ✓ Good choice: angel investors expect simplicity

Option B - Convertible Note:
  ✓ Investors have conversion discount + cap
  ✗ More complex negotiation
  ✗ Debt on balance sheet
  ✗ Overkill for first round

Better choice: SAFE
```

**Scenario 2: Second Seed Round + Series A Planning**
```
Founder already has $300K in SAFEs
Now raising $500K more before Series A in 6 months

Option A - Another SAFE:
  ✓ Consistent with existing investors
  ✗ Multiple SAFEs create complex cap table
  ✗ Series A will be complex (many SAFEs to convert)

Option B - Convertible Note:
  ✓ Different terms for new investors
  ✓ Structured conversion mechanics
  ✓ Clearer Series A path
  ✗ Mix of SAFEs + Notes on cap table

Better choice: Convertible Note (different investor expectations)
```

**Scenario 3: Founder with VC Relationships**
```
Founder raising $1M, knows VCs, likely Series A in 18-24 months

Option A - SAFEs:
  ✓ Simpler
  ✗ VCs often expect more structured round
  ✗ Founder benefits less from investor participation

Option B - Convertible Notes:
  ✓ VCs understand structure well
  ✓ Can negotiate specific terms (cap, discount)
  ✓ More protections for early investors
  ✗ More complex negotiation

Better choice: Convertible Notes
```

---

## Documentation Index

This folder contains comprehensive Convertible Note templates and guides:

1. **CONVERTIBLE_NOTE_TEMPLATE.md** - Full legal agreement template with all standard provisions
2. **TERM_SHEET_TEMPLATE.md** - Summary term sheet for investor discussion/negotiation
3. **SUBORDINATION_AGREEMENT.md** - Template for subordinating notes to senior debt
4. **FOUNDER_PERSPECTIVE.md** - Deep dive into founder risks and negotiation strategies
5. **INVESTOR_PERSPECTIVE.md** - Deep dive into investor risks and due diligence checklist
6. **COMPARISON_SAFE_VS_NOTE.md** - Detailed comparison with when to use each
7. **README.md** - This comprehensive guide

### How to Use These Documents

**For Founders:**
1. Start with README.md to understand the full picture
2. Review FOUNDER_PERSPECTIVE.md to identify key risks
3. Use TERM_SHEET_TEMPLATE.md to set initial terms
4. Have legal counsel review CONVERTIBLE_NOTE_TEMPLATE.md before signing
5. Reference COMPARISON_SAFE_VS_NOTE.md if considering alternatives

**For Investors:**
1. Start with README.md for mechanisms overview
2. Review INVESTOR_PERSPECTIVE.md and due diligence checklist
3. Use TERM_SHEET_TEMPLATE.md to understand what's being proposed
4. Review CONVERTIBLE_NOTE_TEMPLATE.md for binding terms
5. Check SUBORDINATION_AGREEMENT.md to understand your seniority

**For Legal Counsel:**
1. Review CONVERTIBLE_NOTE_TEMPLATE.md as starting point
2. Check TERM_SHEET_TEMPLATE.md for agreed terms
3. Review SUBORDINATION_AGREEMENT.md if senior debt involved
4. Cross-reference FOUNDER_PERSPECTIVE.md and INVESTOR_PERSPECTIVE.md for context on key negotiation points

---

## Key Takeaways

**What You Need to Know:**

1. **Convertible notes are debt** - not equity - with conversion optionality
2. **Interest accrues** - increases equity dilution if converted, payment burden if repaid
3. **Maturity date is real** - creates cash pressure for founders if Series A delayed
4. **Investors get multiple protections** - interest + discount + valuation cap
5. **Defined terms matter** - small differences in "qualified financing" create big disputes
6. **SAFEs are simpler** - but notes provide more structure/investor protection
7. **Subordination is critical** - understand your position in capital structure

**For Founders:**
- Balance sheet impacts are real - understand debt liabilities
- Plan Series A timeline carefully - maturity date pressure is real
- Negotiate reasonable terms early - harder to fix later
- Track interest accrual - increases equity dilution significantly
- Consider number of notes - too many creates complexity

**For Investors:**
- Due diligence is essential - verify team, traction, financial projections
- Understand subordination - you're junior to senior debt
- Governance rights matter - notes alone don't give control
- Plan for maturity scenarios - Series A doesn't always happen on time
- Diversify - early stage has high failure rates

---

## Next Steps

1. Review the templates in this folder
2. Customize [PLACEHOLDER] fields for your specific situation
3. Have legal counsel review before signing
4. Negotiate key terms: principal, interest, cap, discount, maturity
5. Document all side letters and modifications
6. Review annually for refinancing/extension needs

---

**Last Updated:** November 2024
**Status:** Comprehensive - Ready for use with legal counsel review
