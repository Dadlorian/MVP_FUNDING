# SAFE (Simple Agreement for Future Equity) Guide
## Complete Resource for Founders, Investors, and Lawyers

---

## TABLE OF CONTENTS

1. [What is a SAFE?](#what-is-a-safe)
2. [How SAFEs Work](#how-safes-work)
3. [SAFE Variants](#safe-variants)
4. [Common Terms Explained](#common-terms-explained)
5. [Founder Risks & Concerns](#founder-risks--concerns)
6. [Investor Risks & Concerns](#investor-risks--concerns)
7. [When to Use SAFEs](#when-to-use-safes)
8. [SAFEs vs. Other Instruments](#safes-vs-other-instruments)
9. [Pros and Cons Comparison](#pros-and-cons-comparison)
10. [Negotiation Checklist](#negotiation-checklist)
11. [Common Pain Points](#common-pain-points)

---

## WHAT IS A SAFE?

### Definition

A **SAFE** (Simple Agreement for Future Equity) is a **contractual agreement** between an investor and a startup company that provides the investor with the right to purchase equity in the company at a future date, typically when the company raises a priced equity round.

**Key Characteristics:**

| Feature | Details |
|---------|---------|
| **Not a Debt Instrument** | No obligation to repay principal or interest |
| **Not Equity (Initially)** | Investor does not own shares until conversion |
| **Not a Warrant** | Does not grant right to purchase at fixed price |
| **Convertible Security** | Converts to equity under specific conditions |
| **Simple Structure** | Shorter and less complex than convertible notes |
| **Quick Closing** | Can be executed and funded quickly |
| **Investor Friendly** | Originally designed with investor protections |

### Origin

- **Created by:** Y Combinator in 2013
- **Purpose:** Simple alternative to convertible notes for early-stage fundraising
- **Evolution:** Became industry standard for seed/pre-seed funding
- **Modern Use:** Over 80% of seed-stage SAFEs

---

## HOW SAFES WORK

### The SAFE Timeline

```
1. SAFE SIGNED & FUNDED
   Investor invests $X into company
   ↓
2. WAITING PERIOD
   Company uses capital for product development, market entry
   Investor waits (no voting rights, no equity yet)
   ↓
3. TRIGGERING EVENT
   Company raises Series A (or other priced round)
   ↓
4. AUTOMATIC CONVERSION
   SAFE converts to Preferred Stock at conversion price
   Investor receives equity per conversion formula
   ↓
5. INVESTOR RIGHTS ACTIVATED
   Investor gains voting rights, board seat (if applicable)
   Investor benefits from liquidation preferences
```

### Core Mechanics

**Before Conversion:**
- Investor has invested cash
- No shares or equity ownership
- No voting rights
- No governance participation
- Company must use capital for business

**Upon Conversion (at Qualifying Equity Financing):**
- SAFE automatically converts to equity
- Investor becomes shareholder
- Investor receives same preferences as new round investors
- Information and participation rights activate

**If No Qualifying Financing:**
- SAFE remains in limbo or expires
- Investment returned (if specified) or converts to common stock
- Varies by SAFE terms

### Example Scenario

```
TIMELINE EXAMPLE:

Month 0: SAFE Signed
- Investor: Tech VC
- Company: TechStartup Inc.
- Amount: $250,000
- Post-Money Cap: $2,000,000
- Discount: 20%

Months 0-18: Growth Period
- Company builds product
- Hits key milestones
- Gains user traction
- Investor receives quarterly updates but no governance

Month 18: Series A Announced
- Lead investor: Sequoia Capital
- Amount: $5,000,000
- Price: $4.00 per Series A Preferred share
- Valuation: $20M

Conversion Calculation:
1. Discount Application:
   - SAFE price = $4.00 × (1 - 0.20) = $3.20/share
   - SAFE shares = $250,000 / $3.20 = 78,125 shares

2. Cap Application:
   - Post-money cap: $2,000,000
   - SAFE ownership: $250,000 / $2,000,000 = 12.5%
   - Series A investor ownership: 25% (leading round at $4/share)
   - Post-financing, SAFE holder owns ~12% (post-dilution)

3. Investor Receives:
   - 78,125 shares of Series A Preferred (if discount applies)
   - Same rights as Sequoia investors
   - Board seat (if negotiated)
   - Participation rights in future rounds

Month 19 Forward: Shareholder
- Investor votes on major decisions
- Receives financial updates
- Participates in subsequent rounds
- Benefits from exit (IPO, acquisition)
```

---

## SAFE VARIANTS

### 1. Standard SAFE (No Cap, No Discount)

**Best For:** Late-stage pre-seed or early-seed companies

**Characteristics:**
- Investor converts at exact Series A price
- No valuation cap protection
- No discount rate benefit
- Simple conversion formula
- Lower investor protection

**When Used:**
- Company with strong traction
- Investor has high conviction
- Pre-negotiated Series A terms known
- Late-stage startups or bridge rounds

---

### 2. SAFE with Post-Money Valuation Cap

**Best For:** Early-stage seed companies, pre-product

**Characteristics:**
- Valuation cap set at $[X] post-money
- Protects investor from excessive future valuations
- Clearer ownership percentage mathematics
- Most common SAFE variant today
- Industry standard (post-money preferred over pre-money)

**Formula:**
```
Investor Ownership % = Investment Amount / Post-Money Cap
Conversion Price = Post-Money Cap / Fully-Diluted Shares (including SAFE)
```

**Typical Cap Ranges:**
- Pre-seed: $2M-$5M
- Seed: $5M-$15M
- Series A Bridge: $15M-$30M+

---

### 3. SAFE with Pre-Money Valuation Cap

**Best For:** Companies with prior funding history

**Characteristics:**
- Valuation cap set at $[X] pre-money (before SAFE added)
- Slightly more investor-favorable
- Less commonly used (post-money is standard now)
- More complex math for ownership calculations

**Formula:**
```
Post-Money Cap = Pre-Money Cap + SAFE Investment
Investor Ownership % = Investment / (Pre-Money Cap + Investment)
```

---

### 4. SAFE with Discount Rate

**Best For:** Multi-round fundraising, competing SAFEs

**Characteristics:**
- Investor gets discount on Series A price (e.g., 20% off)
- No valuation cap
- Rewards early investment
- Common when company has strong Series A demand
- Less investor protection (no cap)

**Formula:**
```
Conversion Price = Series A Price × (1 - Discount Rate)
                 = Series A Price × (1 - 20%)
```

**Discount Rate Ranges:**
- Pre-seed: 25-35%
- Seed: 15-25%
- Series A Bridge: 10-20%

---

### 5. SAFE with Discount + Cap (Most Protective)

**Best For:** Competitive, uncertain early-stage fundraising

**Characteristics:**
- Both discount AND valuation cap
- Maximum investor protection
- Investor gets whichever is more favorable
- Most complex to calculate
- Most investor-friendly

**How It Works:**
- Compare discount-based price vs. cap-based ownership
- Use whichever gives investor more shares
- Dual protection in all scenarios

---

## COMMON TERMS EXPLAINED

### Valuation Cap

**Definition:**
The maximum valuation of the company for purposes of SAFE conversion, setting a floor for investor's ownership percentage.

**Why It Matters:**
- Protects investor from excessive future valuations
- Guarantees minimum ownership stake
- Especially important in up rounds
- Investor insurance policy against company success

**Example:**
```
Company 1: No Cap
- Seed investment: $100,000
- 2 years later, Series A at $10M valuation
- Investor converts at $10M price - minimal ownership

Company 2: $3M Post-Money Cap
- Seed investment: $100,000
- 2 years later, Series A at $10M valuation
- Investor converts at $3M cap - owns 3.3% guaranteed
- Much better outcome for investor
```

**Cap Negotiation:**
- Lower cap = more investor protection
- Higher cap = more founder-friendly
- Typical negotiation range: 10-30% of Series A valuation

---

### Discount Rate

**Definition:**
A percentage discount on the Series A price, allowing early investors to purchase shares at a reduced price.

**Why It Matters:**
- Rewards early-stage risk-taking
- Aligns investor and founder interests
- Standard practice for SAFEs

**Example:**
```
Series A Price: $5.00 per share

20% Discount SAFE:
- Investor pays: $4.00 per share
- Shares for $100k: 25,000 shares

Series A Investor:
- Pays: $5.00 per share
- Shares for $100k: 20,000 shares

SAFE Investor Benefit: 5,000 extra shares
```

**Typical Discount Ranges:**
- Pre-seed: 25-35%
- Seed: 15-25%
- Series A Bridge: 10-20%

### Most Favored Nation (MFN) Clause

**Definition:**
Automatic right to receive the same terms as any subsequent investor if the company issues another SAFE or convertible with more favorable terms.

**How It Works:**
```
Scenario:
- You invest $100k at 20% discount, $5M cap
- Three months later, company issues SAFE at 30% discount, $4M cap
- Your MFN clause triggers
- You automatically receive 30% discount and $4M cap
- No renegotiation needed
```

**Investor Protection:**
- Ensures you're never left with inferior terms
- Reduces competitive disadvantage
- Automatic, no action required

**Company Perspective:**
- Creates complexity in issuing new SAFEs
- Requires tracking and notification
- Can cascade through multiple rounds

**MFN Scope Options:**
- **Broad:** Covers all better terms across all investors
- **Narrow:** Covers only specific term improvements
- **Time-Limited:** Applies only within [12] months

---

### Pro-Rata Rights

**Definition:**
Right to maintain ownership percentage in future equity rounds by participating pro-rata.

**How It Works:**
```
Example:
- Your SAFE converts to 5% ownership
- Series B: Company raises $10M
- Your pro-rata right: Can invest $500k (5% of $10M)
- Maintains 5% ownership post-Series B
- If you don't participate, ownership dilutes

Benefits:
- Control your dilution
- Participate in growth
- Maintain influence
```

**Who Has It:**
- Typically Series A+ investors (after SAFE converts)
- Often not included in initial SAFE
- Can be negotiated into SAFE terms

---

### Liquidation Preference

**Definition:**
How proceeds are distributed in a sale, merger, bankruptcy, or liquidation event.

**Common Types:**

| Type | Definition | Example |
|------|---|---|
| **Non-Participating** | Preferred investors choose between: (a) preference amount or (b) pro-rata common, whichever is greater | Investor gets $1M back or 2% of sale, whichever is higher |
| **Participating** | Preferred investors get preference PLUS pro-rata share of remaining proceeds | Investor gets $1M PLUS 2% of excess |
| **1x Multiple** | Return of investment amount | Invest $1M, get $1M back |
| **2x Multiple** | Return of investment × 2 | Invest $1M, get $2M back |

**SAFE Specific:**
- SAFEs don't have liquidation preferences until converted to Preferred Stock
- Upon conversion, SAFEs receive whatever terms Series investors receive
- In change of control before conversion, SAFE holder typically gets investment back or proportional share

---

### Fully-Diluted Capitalization

**Definition:**
Total shares outstanding including common, preferred, options, warrants, and convertible instruments as if all are converted/exercised.

**Why It Matters:**
- Determines investor ownership percentage
- Affects conversion calculations
- Critical for understanding real dilution

**What's Included:**
- All issued common shares
- All issued preferred shares
- All SAFEs and convertible notes
- All outstanding stock options
- All warrants
- Any other contingent securities

**Example:**
```
Common Shares: 1,000,000
Series A Preferred: 500,000
Employee Options: 150,000
SAFE (to convert): ~75,000
Warrants: 25,000

Fully-Diluted: 1,750,000 shares

If investor owns 100,000 shares:
Ownership % = 100,000 / 1,750,000 = 5.7%
```

---

## FOUNDER RISKS & CONCERNS

### Risk 1: Dilution Uncertainty

**The Problem:**
You don't know how much equity you'll give up in the Series A because conversion happens at a future price.

**Scenario:**
```
Founder Situation:
- Raise $500k from three SAFEs (no cap, no discount)
- Each SAFE investor: $166.67k
- You own 60% of company

Series A:
- Investor wants to price at $10M
- $2M investment from Series A
- You think: "I've always had Series A at 20-25% dilution"
- Calculation: $2M / $10M = 20% new shares

But Wait - SAFEs Convert:
- SAFE 1 converts at $10M implied post-money
- SAFE 2 converts at $10M implied post-money
- SAFE 3 converts at $10M implied post-money
- Total SAFE conversion impact: ?

Your dilution becomes 20% + SAFE dilution = 25-30%+
```

**Founder Strategies:**
1. **Aggregate SAFE caps:** Track total SAFE caps relative to Series A expectations
2. **Understand cumulative dilution:** Calculate total dilution including all SAFEs
3. **Plan for worst case:** Assume SAFEs with high discount rates and low caps
4. **Negotiate minimums:** Ensure Series A meets expectations to manage SAFE conversion

---

### Risk 2: Uncapped SAFEs

**The Problem:**
Without a valuation cap, investor converts at whatever the Series A price is, providing no protection against excessive dilution.

**Scenario:**
```
Your situation:
- Raise $100k uncapped SAFE from angel
- Plan: Series A at $5M valuation
- Expected SAFE dilution: 2% (rough math)

Reality:
- Series A at $20M (huge success!)
- Uncapped SAFE investor owns only 0.5%
- Your expectation vs. reality: 2% vs. 0.5%
- Result: Unexpected dilution from company success

With Cap at $5M:
- Same success, Series A at $20M
- SAFE investor capped at conversion = $100k / $5M = 2% ownership
- You get more predictable dilution
```

**Founder Best Practice:**
- Always require a valuation cap on SAFEs
- Cap ensures predictable dilution regardless of Series A pricing
- Uncapped SAFEs create future uncertainty

---

### Risk 3: Multiple SAFEs Stacking

**The Problem:**
As you raise from multiple SAFE investors, dilution compounds, and Series A becomes less attractive to lead investors.

**Scenario:**
```
Timeline:

Month 1: Angel SAFE #1 - $100k with $3M post-money cap, 20% discount
Month 3: Angel SAFE #2 - $150k with $3M post-money cap, 20% discount
Month 6: Institutional SAFE - $500k with $5M post-money cap, 20% discount
Month 12: Series A

Series A Investor Sees:
- Total SAFE capital: $750k
- Total SAFE dilution at caps: 25-30% of company
- Series A investment: $3M
- Fully-diluted cap table: Highly fragmented
- Series A investor gets: Minority stake even with $3M investment
- Investor reaction: "This is harder to work with than expected"

Founder Impact:
- Series A becomes harder to close
- Series A valuation suppressed (due to SAFE dilution)
- Series A investor demands more equity to get 20-25%
- You get more diluted than expected
```

**Best Practices:**
1. **Track aggregate cap:** Sum all SAFE caps + planned Series A
2. **Model scenarios:** Calculate full dilution in various Series A scenarios
3. **Limit SAFE count:** Consolidate if possible; too many creates complexity
4. **Communicate with SAFEs:** Let early investors know about planned Series A to manage expectations
5. **Negotiate minimums:** Ensure Series A raises enough to make sense given SAFE dilution

---

### Risk 4: Conversion Trigger Ambiguity

**The Problem:**
Unclear conversion triggers or what constitutes a "Qualifying Equity Financing" can lead to disputes.

**Scenario:**
```
SAFE Language:
"SAFE converts upon Qualifying Equity Financing of at least $1M"

Three Years Later:
- Company raises $800k from angel investors
- Is this a "Qualifying Equity Financing"? → Dispute
- Company raises from strategic corporate partner at premium terms
- Does this count? → Ambiguous
- Company needs capital urgently but without full Series A
- How should SAFEs be handled? → Unclear

Results:
- Legal disputes with SAFE investors
- Delays in capital deployment
- Uncertainty for everyone
```

**Best Practices:**
1. **Clear definitions:** Define "Preferred Stock" and "Qualifying Equity Financing" explicitly
2. **Minimum threshold:** Set clear minimum proceeds ($500k-$1M typical)
3. **Board consent:** Include provision for board to declare Qualifying Financing even if below minimums
4. **ESOP clarity:** Explicitly exclude employee stock purchase plans, ESOPs
5. **Debt clarity:** Explicitly exclude debt financing, SAFEs, convertibles

---

### Risk 5: MFN Clause Cascades

**The Problem:**
A more favorable SAFE to a later investor automatically extends to all previous SAFE holders with MFN clauses, cascading changes.

**Scenario:**
```
Timeline:

Month 1: Angel A - $100k, 20% discount, $3M cap, WITH MFN
Month 3: Angel B - $100k, 20% discount, $3M cap, WITH MFN
Month 6: VC Fund C - $500k, 30% discount, $5M cap, WITH MFN

Month 7: Company Issues SAFE to Angel D - $100k, 25% discount, $2.5M cap, WITH MFN

MFN Cascade:
- Angel D gets better deal: lower cap ($2.5M vs. $3M)
- Angel A's MFN triggers → gets $2.5M cap
- Angel B's MFN triggers → gets $2.5M cap
- VC Fund C's MFN triggers → gets $2.5M cap

Compounding Effect:
- All prior investors now have your most favorable terms
- Creates incentive to keep offering worse terms to new investors
- Suppresses your negotiating power in future rounds
- Makes future SAFEs harder to close

Month 8: Company Tries SAFE E - $200k at 15% discount, $2M cap
- Series A investors pre-emptively trigger MFN (if applicable)
- Entire cap table gets better terms
- Defeats the purpose of negotiating with new investors
```

**Best Practices:**
1. **Limit MFN scope:** Be specific about what terms trigger MFN
2. **Time limits:** MFN applies only within 6 or 12 months
3. **Carve-outs:** Exclude certain investors (e.g., employees, partners)
4. **Graduated terms:** Plan terms for different rounds (early vs. late seed)
5. **Communicate:** Tell investors upfront about expected MFN applicability

---

## INVESTOR RISKS & CONCERNS

### Risk 1: No Maturity Date

**The Problem:**
Unlike convertible notes with fixed maturity dates, SAFEs may never convert if no equity financing occurs.

**Scenario:**
```
Investor Situation:
- Invest $100k in SAFE in 2020
- Company doesn't raise Series A
- Years pass: 2021, 2022, 2023, 2024
- Capital is trapped in non-equity, non-debt instrument
- No rights to force conversion or return
- Company still operating, but no exit or conversion

Investor Dilemma:
- Can't force liquidation (not a debt holder)
- Can't force equity conversion (no specified trigger)
- Can't exit (non-transferable SAFE)
- Can't sell to another investor (illiquid)
- Stuck indefinitely

Result: Opportunity cost of $100k for years
```

**Investor Protection Strategies:**
1. **Specify expiration:** Require SAFE to expire at [5-7 years], convert to common at that point
2. **Auto-conversion:** If no Qualifying Financing by date X, auto-convert to [X]% common stock
3. **Board seat:** Ensure board observation rights to track company progress
4. **MFN + Pro-Rata:** Maintain leverage through MFN and ability to participate in future rounds
5. **Qualified Financing minimum:** Ensure threshold is realistic and achievable

---

### Risk 2: No Interest or Maturity Guarantee

**The Problem:**
Unlike debt, SAFEs pay no interest and have no guaranteed return date, leaving capital at risk indefinitely.

**Investor Concern:**
```
Time value of money:
- Invest $100k today
- No return for 5+ years
- Inflation erodes value
- Opportunity cost: could have invested in other companies
- No compensation for delayed returns

Example:
- $100k SAFE → converts to equity worth $150k
- Sounds good, but if 5 years elapsed:
  - $150k in 5 years, at 5% annual inflation, ≈ $117k in today's dollars
  - Real return: 17% over 5 years = 3.2% annually
  - Below stock market returns (~10% annually)
  - Below VC returns expected (3-5x multiple)
```

**Investor Mitigation:**
1. **Higher discount rates:** Negotiate 25-30% discount to compensate for time
2. **Lower valuation caps:** Ensure ownership protections
3. **Specify terms:** Clearly define conversion triggers and timelines
4. **Board observation:** Track company progress to assess time to liquidity
5. **MFN clause:** Ensure you get any better terms issued to later investors

---

### Risk 3: Subordinate to Debt

**The Problem:**
In a liquidation, all debt holders (banks, creditors) get paid before SAFE holders, leaving little for equity.

**Scenario:**
```
Company Situation:
- Raised $500k in SAFEs
- Took $200k bank loan
- Business fails, company liquidates

Liquidation Proceeds: $300k (less than liabilities)

Payment Order:
1. Bank loan ($200k) - paid in full
2. Operational creditors ($50k) - paid in full
3. SAFE investors ($500k) - get $50k total split among them
   Each SAFE investor: pennies on the dollar

Result: SAFE investor gets nothing while debt holders are satisfied
```

**Investor Protection:**
1. **Understand capital structure:** Know all debt obligations
2. **Cap total debt:** Negotiate with founders to limit total debt relative to equity
3. **Debt ratios:** Ensure debt ≤ equity to maintain SAFE priority
4. **Board observation:** Track when debt is being incurred
5. **Liquidation preferences:** Ensure SAFE specifies position relative to debt

---

### Risk 4: No Pro-Rata Rights (Initially)

**The Problem:**
SAFE holders don't automatically get pro-rata rights in future rounds, facing potential dilution.

**Scenario:**
```
Investor Situation:
- Invest $100k SAFE, converts to 5% equity in Series A
- Series B: Company raises $10M at 2x valuation
- You have NO pro-rata rights in SAFE terms
- Can't participate: Other investors participate, your ownership dilutes to 3%
- Your 5% was diluted to 3% without ability to maintain stake

vs.

With Pro-Rata Rights:
- Series B: Can invest $500k (5% of $10M) to maintain 5% ownership
- Pay same price as other Series B investors
- Maintain ownership and influence
```

**Investor Mitigation:**
1. **Negotiate pro-rata:** Include in SAFE if possible
2. **Understand dilution:** Plan for Series A + B + C dilution in advance
3. **Relationship:** Build strong relationship with founders to stay in future rounds
4. **Board presence:** Get board seat or observation to know about future rounds early
5. **Information rights:** Ensure access to cap table and financial data

---

### Risk 5: No Voting Rights or Governance

**The Problem:**
Until converted to Preferred Stock, SAFE holders have no voting rights, no veto power, no governance participation.

**Scenario:**
```
You as SAFE investor:
- Invest $500k
- Company operates 2 years without your input
- Major decisions: pivot business, hire/fire key people, spend capital
- You can't vote on any of these
- You can't veto problematic decisions
- You can't replace management
- You're dependent on founders' judgment

Company Founders' Situation:
- Have $500k of your capital
- No obligation to listen to you
- No voting rights for you to exercise
- Can run company however they want
- Can make risky decisions with your capital

Governance Gap:
- You have significant capital at risk
- You have zero governance rights
- You're powerless to influence outcomes
```

**Investor Mitigation:**
1. **Board observation rights:** Negotiate to observe board meetings
2. **Information rights:** Require regular (quarterly) updates
3. **Board seat (later):** After Series A, negotiate board seat
4. **MFN clause:** Ensure you benefit from any governance improvements
5. **Relationship:** Build trust with founders; participate informally in decisions

---

## WHEN TO USE SAFEs

### Best For: Early-Stage Companies

**Pre-Seed Stage ($100k-$500k raises)**
- Use SAFEs with post-money caps ($2M-$5M)
- Discount rate: 20-30%
- High uncertainty, need simple capital process
- Multi-investor rounds common

**Seed Stage ($500k-$2M raises)**
- Use SAFEs with post-money caps ($5M-$15M)
- Discount rate: 15-25%
- Product-market fit starting to emerge
- Ready for Series A in 12-18 months

**Series A Bridge ($1M-$5M raises)**
- Use SAFEs with post-money caps or discounts only
- Discount rate: 10-20%
- Company between Series A term sheet and close
- Quick capital bridge to hold company over

### Not Best For: Later Stages

**Series A and Beyond**
- Use Preferred Stock directly instead
- Use convertible notes if bridge needed
- SAFEs become less relevant
- Investors want voting rights, board seats, liquidation preferences
- Preferred Stock provides these clearly

**Mature Companies**
- SAFEs rarely used
- Standard equity financing preferred
- Debt instruments (bonds, bank loans) preferred for bridge
- SAFEs designed for early-stage uncertainty

---

## SAFEs VS. OTHER INSTRUMENTS

### SAFE vs. Convertible Note

| Aspect | SAFE | Convertible Note |
|--------|------|---|
| **Maturity Date** | No | Yes (typically 2 years) |
| **Interest Rate** | None | 5-8% typically |
| **Debt Status** | Equity instrument | Debt instrument |
| **Simplicity** | Very simple | More complex |
| **Length** | 2-3 pages | 10-20 pages |
| **Investor Protection** | Moderate | High (interest + maturity) |
| **Founder Burden** | Low (no interest) | Moderate (must track interest) |
| **Balance Sheet Impact** | Equity (off-balance sheet until convert) | Debt (on-balance sheet) |
| **When to Use** | Most seed rounds now | Specific situations, bridges |
| **Cost to Raise** | Low (simple documents) | Higher (more complex) |

**When to Use Each:**
- **SAFE:** Standard seed rounds, investor is comfortable with no maturity
- **Convertible Note:** Bridge round, investor wants maturity protection, debt is okay on balance sheet

---

### SAFE vs. Priced Equity Round (Seed Preferred Stock)

| Aspect | SAFE | Seed Preferred Stock |
|--------|------|---|
| **Valuation** | Implicit (set at Series A) | Explicit now |
| **Investor Ownership** | Determined at conversion | Determined immediately |
| **Governance Rights** | None until conversion | Immediate |
| **Board Rights** | No board seat | Board seat typically included |
| **Liquidation Preference** | Per Series A terms | Explicit (1x non-participating) |
| **Pro-Rata Rights** | Not in SAFE typically | Included |
| **Simplicity** | 2-3 pages | 50+ pages |
| **Timing** | Quick close | 4-8 weeks to close |
| **Documentation** | Minimal | Extensive (charter, investors rights, etc.) |
| **When to Use** | Pre-product, high uncertainty | Product-market fit, ready to hire |

**When to Use Each:**
- **SAFE:** Earliest stage, moving fast, fundraising uncertainty
- **Seed Preferred:** Later seed (12+ months in), ready for governance structure

---

### SAFE vs. Warrant (Stock Purchase Warrant)

| Aspect | SAFE | Warrant |
|--------|------|---|
| **Mechanism** | Converts to equity at future price | Right to purchase at fixed price |
| **Trigger** | Automatic at Qualifying Financing | Investor exercises when ready |
| **Pricing** | Determined at Series A | Fixed at issue |
| **Investor Control** | None (automatic conversion) | Full control (when to exercise) |
| **Time Limit** | No standard expiry | Usually 5-10 year term |
| **Valuation Cap** | Can include | No cap (fixed price) |
| **Use Case** | Seed investment | Advisor compensation, strategic partnerships |
| **Complexity** | Simple | Moderate |

**When to Use Each:**
- **SAFE:** Investor-funded seed rounds
- **Warrant:** Strategic partners, advisors, employee compensation

---

## PROS AND CONS COMPARISON

### SAFE Advantages

| Advantage | Benefit |
|-----------|---------|
| **Speed** | Quick to negotiate and sign (days vs. weeks) |
| **Simplicity** | 2-3 pages vs. 50+ page equity docs |
| **Cost** | Minimal legal fees (~$5k vs. $50k) |
| **Founder-friendly** | No interest, no debt, no maturity |
| **Investor-friendly** | Simple cap/discount protection |
| **Standardized** | Y Combinator standard forms available |
| **No Balance Sheet Liability** | Doesn't appear as debt for accounting |
| **Capital Efficiency** | Quick fundraising without lengthy process |

### SAFE Disadvantages

| Disadvantage | Issue |
|---|---|
| **No Maturity Date** | Can remain unconverted indefinitely |
| **No Interest** | No compensation for delayed returns |
| **No Voting Rights** | Investor has no governance input |
| **Conversion Ambiguity** | What triggers conversion can be disputed |
| **MFN Complexity** | Can create cascading term improvements |
| **Dilution Uncertainty** | Founder doesn't know final dilution % |
| **Stack Complexity** | Multiple SAFEs create cap table confusion |
| **Limited for Late Stage** | Not suitable for Series A+ |

### Founder Perspective: When SAFEs Work

**Best Case for Founders:**
```
Company Profile:
- Early stage (< 12 months)
- Raising $250k-$1M total
- 3-5 investors max
- Planning Series A in 12-18 months
- Need capital fast to meet milestones

SAFE Advantages:
✓ Quick closing (funds available in days)
✓ Simple documents (minimal legal cost)
✓ No interest burden
✓ No debt on balance sheet
✓ Clear conversion at Series A
✓ Investors happy with cap + discount

Result: Founders can deploy capital quickly
```

**Worst Case for Founders:**
```
Company Profile:
- Multiple SAFEs ($500k total) with low caps ($3M)
- No Series A on horizon (pre-product)
- Need board governance

SAFE Disadvantages:
✗ Multiple SAFEs create cap table fragmentation
✗ Undercapped SAFEs mean huge dilution
✗ No governance from SAFE investors
✗ Uncertainty about when/how SAFEs convert
✗ Cap table becomes complex before Series A

Result: Series A becomes harder, harder to raise, more dilution
```

### Investor Perspective: When SAFEs Work

**Best Case for Investors:**
```
Investment Profile:
- Seed-stage company with strong team
- Cap at $5M, 20% discount
- MFN clause + pro-rata rights
- Board observation
- Series A expected in 12-18 months

SAFE Advantages:
✓ Quick investment deployment
✓ Downside protection (cap + discount)
✓ Can maintain ownership through MFN/pro-rata
✓ Early-stage upside exposure
✓ Simple terms, easy to understand

Result: Investor gets good entry point with downside protection
```

**Worst Case for Investors:**
```
Investment Profile:
- Uncapped SAFE from company in uncertain market
- No discount rate
- No MFN, no pro-rata
- No information rights
- No board observation
- No specified conversion trigger or expiration

SAFE Disadvantages:
✗ No valuation protection in up round
✗ No compensation for time/risk
✗ Trapped capital with no rights
✗ Unclear if/when conversion happens
✗ No information to track progress

Result: Investor has minimal protection, high risk, no control
```

---

## NEGOTIATION CHECKLIST

### Founder Negotiation Points

**[  ] Valuation Cap**
- [ ] Propose: [SPECIFY - e.g., "$5M post-money"]
- [ ] Justification: Recent comparable raises
- [ ] Red line: Don't go below [X]% of planned Series A valuation

**[  ] Discount Rate**
- [ ] Propose: [SPECIFY - e.g., "15% discount"]
- [ ] Justification: Reward early investors appropriately
- [ ] Red line: Don't exceed 25% for seed stage

**[  ] MFN Clause**
- [ ] Propose: Time limit (e.g., "12 months")
- [ ] Scope limit: Specific terms only (e.g., "cap and discount only")
- [ ] Carve-outs: Exclude employees, strategic partners

**[  ] Pro-Rata Rights**
- [ ] Propose: "Not included in SAFE, may be negotiated later"
- [ ] If included: Time limit (e.g., "3 years or until Series B")
- [ ] Clarify: Applies only to equity rounds, not debt

**[  ] Conversion Triggers**
- [ ] Define: "Qualifying Equity Financing" = $[X]+ Preferred Stock
- [ ] Clarity: Excludes SAFEs, debt, options, warrants
- [ ] Board discretion: Board can declare financing as Qualifying even if below minimum

**[  ] Transfer Restrictions**
- [ ] Propose: "No transfer without Company consent except to family/QRAs"
- [ ] Repurchase right: "Company may repurchase at cost if unauthorized transfer"

**[  ] Expiration Terms**
- [ ] Auto-conversion: If no Qualifying Financing by [X years], convert to [X]% common
- [ ] Return option: Or return investment + [X]% interest

### Investor Negotiation Points

**[  ] Valuation Cap**
- [ ] Target: Cap should be [X]% of expected Series A valuation
- [ ] Justification: Protects against excessive future valuations
- [ ] Red line: Don't accept caps > 50% higher than your assessment of company value

**[  ] Discount Rate**
- [ ] Target: 20-25% for seed stage
- [ ] Justification: Compensates for early risk
- [ ] Combine with cap: Ensure strong protection even if discount modest

**[  ] MFN Clause**
- [ ] Demand: "Automatic if any investor gets better terms within 12 months"
- [ ] Scope: Cap, discount, and investor rights included
- [ ] No carve-outs: Don't accept exceptions for employees/strategic

**[  ] Pro-Rata Rights**
- [ ] Demand: "Right to participate pro-rata in all future equity rounds"
- [ ] Duration: "Applies until [X] years or until Company IPO/M&A"
- [ ] Terms: "Same price and terms as other investors in round"

**[  ] Information Rights**
- [ ] Quarterly: Financial statements, KPIs, updates
- [ ] Annual: Board resolutions, cap table, budget
- [ ] Board observation: Right to attend all board meetings
- [ ] Notification: Material events within 10 days

**[  ] Conversion Clarity**
- [ ] Define trigger: Unambiguous definition of Qualifying Financing
- [ ] Minimum threshold: Clear, achievable amount
- [ ] Board authority: Specify board can declare financing as Qualifying
- [ ] Conversion timing: Specify when conversion occurs (signing vs. closing)

**[  ] Liquidation Protection**
- [ ] Return of investment: Ensure at least investment back on liquidation
- [ ] Priority: Prefer senior to common shareholders
- [ ] MFN: Any better terms to later investors, you get too

**[  ] Expiration Terms**
- [ ] No indefinite limbo: Require expiration by [X years]
- [ ] Auto-conversion: If no Qualifying Financing by expiration, auto-convert to equity
- [ ] Rights preservation: If expires unconverted, SAFE holder gets [X]% common stock

---

## COMMON PAIN POINTS

### Pain Point 1: Valuation Cap Negotiations

**The Conflict:**
```
Founder's View:
- "Cap at $2M? That's too low!"
- "I'm confident in the company's potential"
- "A $2M cap means even modest Series A will heavily dilute us"
- "Our last fundraising advisor suggested $5M cap"

Investor's View:
- "Cap at $2M because you're pre-product with unproven team"
- "If you raise Series A at $10M, we want to own at least 5%"
- "$2M cap ensures minimum 5% ownership"
- "Higher cap means minimal protection for our early risk"
```

**The Math Behind the Conflict:**
```
Scenario A: $3M Post-Money Cap
- Your investment: $200,000
- Your ownership: $200k / $3M = 6.67%
- If Series A at $5M, your ownership diluted to ~4%
- You gave up ~2.67% of company from early investment

Scenario B: $5M Post-Money Cap
- Your investment: $200,000
- Your ownership: $200k / $5M = 4%
- If Series A at $5M, your ownership diluted to ~2.7%
- You only get 4%, regardless of Series A growth

Founder Observation:
- Either cap is bad for founders!
- Lower cap: Heavy ownership stake, less dilution
- Higher cap: Lighter ownership stake, more dilution
- Tradeoff: Can't have both low cap AND high ownership in up round
```

**Resolution Strategies:**

**Option 1: Tiered Caps**
```
- If Series A < $3M: Cap = $4M
- If Series A $3M-$5M: Cap = $5M
- If Series A > $5M: Cap = $6M
- Adjusts based on market conditions and round size
```

**Option 2: Graduated Investor Classes**
```
- Round 1 (Angel A): $3M cap (most risk, best protection)
- Round 2 (Angel B, 3 months later): $4M cap (less risk)
- Round 3 (Institutional, 6 months later): $5M cap (lower risk)
- Reflects investor's timing and risk level
```

**Option 3: Cap Relative to Series A**
```
- SAFE term: "Cap shall be [X]% of Series A valuation"
- Example: "Cap = 50% of Series A valuation"
- If Series A at $10M, cap = $5M
- If Series A at $5M, cap = $2.5M
- Automatically adjusts to round size
```

---

### Pain Point 2: Discount vs. Cap Decisions

**The Conflict:**
```
Investor A's Offer:
- No cap, 20% discount
- "I'm comfortable with conversion at Series A price"
- "But I want 20% off for my early risk"

Investor B's Offer:
- $5M cap, no discount
- "I want valuation protection if company explodes"
- "Willing to convert at Series A price for cap security"

Founder's Problem:
- Which is better? For investor? For company?
- If accept both, what's the aggregate protection?
- Can I negotiate one without the other?
```

**Comparing the Options:**

```
Example Setup:
- Investment: $100,000 per SAFE
- Expected Series A: $3-5M valuation

Investor A: $5M Cap, No Discount
- If Series A at $3M → Cap applies, lower conversion price
- If Series A at $5M → Cap applies, lower conversion price
- If Series A at $10M → Cap applies strongly
- Protection: Excellent for up rounds
- Simplicity: Good, no discount math

Investor B: 20% Discount, No Cap
- If Series A at $2M → Discount: $2M × 80% = $1.60, excellent for investor
- If Series A at $5M → Discount: $5M × 80% = $4M, good protection
- If Series A at $10M → Discount: $10M × 80% = $8M, minimal protection
- Protection: Excellent for down/flat, weak for up rounds
- Simplicity: Simple math (just apply discount)

Company Perspective:
- Cap investor: Better for founder if Series A large (multiple SAFEs with caps manageable)
- Discount investor: Better for founder if Series A small (discount creates more ownership loss)
- Founder's dilution depends on market conditions and Series A
```

**Decision Framework:**

| Scenario | Prefer | Reason |
|----------|--------|--------|
| **Confident in large Series A** | Cap, no discount | Cap limits dilution in success case |
| **Uncertain about Series A** | Discount, no cap | Discount acceptable risk if Series A small |
| **Want to keep both investors happy** | Both cap and discount (but adjust terms) | Provides investor protection, clear for founder |
| **Early stage, pre-product** | Cap (higher priority) | Ensures predictable dilution |
| **Late seed, near Series A** | Discount (higher priority) | Series A valuation more predictable |

---

### Pain Point 3: MFN Clause Complexity

**The Conflict:**
```
Situation:
- Investor A invests $100k at 20% discount, $5M cap, WITH MFN
- 3 months later, Investor B invests $150k at 25% discount, $4M cap, WITH MFN

Investor A's Reaction:
- "Wait, you gave better terms to Investor B!"
- "I invested first, took more risk, got worse terms?"
- "Where's my MFN protection?"
- "You owe me 25% discount and $4M cap!"

Company's Reaction:
- "Investor B had more capital, could negotiate better"
- "Your MFN kicks in, now everyone has 25% discount + $4M cap"
- "I planned to give worse terms to later investors!"
- "Now my cap table is more diluted than expected"

Series A Investor's Reaction:
- "You gave early SAFEs massive protection"
- "Discount + cap combo is very expensive"
- "Your dilution is worse than initially modeled"
- "I'm reducing my investment or demanding better terms"
```

**The MFN Cascade Problem:**
```
Timeline of MFN Triggering:

Month 1: Investor A - $100k, 20% discount, $5M cap, MFN
Month 2: Investor B - $100k, 20% discount, $5M cap, MFN
Month 3: Investor C - $100k, 20% discount, $5M cap, MFN
Month 4: Investor D - $150k, 25% discount, $4M cap, MFN

Month 4 Event:
- Investor D gets better terms
- Investor A's MFN triggers → gets 25% discount, $4M cap
- Investor B's MFN triggers → gets 25% discount, $4M cap
- Investor C's MFN triggers → gets 25% discount, $4M cap
- Company suddenly has massive dilution

Company's Realization:
- "Everyone now gets best terms"
- "My Series A dilution much higher than modeled"
- "Series A investor sees this, reduces valuation or investment"
- "All my MFN investors just became very expensive"
```

**Resolution Strategies:**

**Strategy 1: Limited MFN Scope**
```
SAFE Language:
"Investor has MFN rights for discount rates and valuation caps only.
MFN does NOT apply to:
- Board seats or governance rights
- Pro-rata participation rights
- Information rights
- Investor-specific customizations
"

Effect:
- Protects investor on pricing terms
- Allows founder to customize governance with later rounds
- Limits MFN to economically material terms
```

**Strategy 2: Time-Limited MFN**
```
SAFE Language:
"Investor has MFN rights for any SAFE issued within 12 months.
After 12 months, no MFN applies.
"

Effect:
- MFN applies only in competitive seed round period
- Allows founder to offer different terms in Series A
- Limits duration of MFN obligation
```

**Strategy 3: Investor-Class Exceptions**
```
SAFE Language:
"MFN applies to all investors in same funding round.
MFN does not apply to:
- Employee stock option recipients
- Strategic corporate partners
- Founder grants or rollovers
- Advisors receiving warrants

Effect:
- Protects core seed investors
- Allows flexibility for non-investor capital sources
- Typical and well-understood
```

**Strategy 4: Tiered Investor Classes**
```
Seed Round Classes:

Class A (Early investors): $3M cap, 20% discount, MFN
- Signed Month 1-2
- Higher risk, more protection

Class B (Mid investors): $4M cap, 20% discount, limited MFN
- Signed Month 3-4
- Less protection, appropriate for timing

Class C (Late investors): $5M cap, 15% discount, no MFN
- Signed Month 5+
- Lower protection, reflect lower risk

MFN Rules:
- Class A investors get better terms than Class B/C
- Class B investors get Class A terms only if same cap, discount
- Class C has no MFN rights

Effect:
- Rewards early risk-taking
- Allows escalating terms over round
- MFN applies within class, not across classes
```

---

### Pain Point 4: Conversion Trigger Ambiguity

**The Conflict:**
```
SAFE Language:
"SAFE converts upon Qualifying Equity Financing of Series A or later."

Two Years Later, Company Situation:
- Doesn't want full Series A yet
- Raises $800k from angel syndicate
- Not an official "Series A"
- But substantial capital for growth
- Question: Is this a Qualifying Financing?

SAFE Investor's View:
- "This is clearly a financing round!"
- "$800k is substantial capital"
- "You should trigger SAFE conversion"
- "I'm converting now"

Company's View:
- "We need more capital first"
- "This isn't a formal Series A priced by lead VC"
- "SAFE conversion now is premature"
- "We'll convert in formal Series A later"

Result: Dispute over whether conversion triggered
```

**Resolution Strategies:**

**Strategy 1: Explicit Definition**
```
SAFE Language:
"Qualifying Equity Financing means:
1. Sale of Series A Preferred Stock (or Series [X] if no Series A)
2. From professional investors (VCs, angels with $5M+ AUM)
3. With minimum proceeds of $750,000
4. With documented anti-dilution or other Preferred features
5. Explicitly designated in writing as Qualifying Financing

This definition excludes:
- SAFEs or convertible notes
- Debt financing (loans, lines of credit)
- Grants or non-dilutive capital
- Employee stock option issuances
- Officer/director equity issuances
"

Effect:
- Crystal clear what qualifies
- No ambiguity about angel rounds
- Excludes non-dilutive capital
- Professional investors know expectations
```

**Strategy 2: Board Declaration**
```
SAFE Language:
"Notwithstanding the definition above, Company's Board of Directors
may declare any financing round as a Qualifying Equity Financing,
even if below the minimum proceeds threshold, with written notice
to SAFE holders within 10 business days of such declaration.

Effect:
- Founders have flexibility
- SAFE investors get notice
- Board can accelerate if beneficial
- Prevents gaming or disputes
```

**Strategy 3: Auto-Conversion Trigger**
```
SAFE Language:
"If Company raises total debt + equity capital of $X in any
12-month period, SAFE automatically converts to equity even if
not a formal Qualifying Equity Financing.

Effect:
- Captures substantial capital raises even if informal
- Investor protects itself without requiring dispute
- Company must track total capital (debt + equity)
- Clear trigger based on objective metric
```

---

### Pain Point 5: Cap Table Fragmentation

**The Conflict:**
```
Timeline:

Month 1: Angel #1 - $50k SAFE
Month 2: Angel #2 - $75k SAFE
Month 3: Angel #3 - $100k SAFE
Month 4: Institutional Investor - $300k SAFE
Month 5: Another Institutional - $200k SAFE

Pre-Series A Cap Table:
- Common Stock: Founder 70%
- 5 SAFEs Outstanding: $725k total

Question: What is cap table after Series A?

Series A Reality:
- Series A wants to invest $3M at $10M pre-money
- Pre-money cap: $10M
- Company: 1M common shares @ $10/share = $10M
- Series A: 1M Series A shares @ $10/share = $10M post-money

SAFE Conversions (Complex):
- 5 SAFEs convert at different prices depending on terms
- Each has different cap/discount
- Each has different MFN status
- Post-SAFE conversion: Founder diluted significantly
- Series A investor confused about final cap table

Post-SAFE Cap Table (Example):
- Founder: 40% (heavily diluted from SAFEs)
- SAFE investors: 35% (collectively)
- Series A investor: 25%
- Option pool: 5% (remaining)

Series A Investor Reaction:
- "Your founder only owns 40%? That's too low!"
- "SAFE investors collectively own 35%? That's fragmented!"
- "I want founder to own at least 50% and option pool 10-20%"
- "We need to renegotiate everything"

Result: Series A delayed, negotiations reopened, cap table reworked
```

**Root Cause:**
- Founder took too many SAFEs with low caps
- Didn't model cumulative dilution
- Series A investor has different expectations
- Cap table becomes unexpectedly fragmented

**Prevention Strategies:**

**Strategy 1: Model All Scenarios**
```
Founder Pre-Fundraising:
"I'll raise max $500k in SAFEs before Series A"
- Investor #1: $100k SAFE, $3M cap
- Investor #2: $150k SAFE, $3M cap
- Investor #3: $100k SAFE, $4M cap
- Investor #4: $150k SAFE, $4M cap
- Total: $500k SAFEs

Model: What happens at Series A?
- Series A: $2M at $5M pre-money

SAFE Conversions:
- All 4 SAFEs convert at ~$3-4M cap
- Cumulative dilution: 15-20% pre-Series A
- Post-Series A founder ownership: 40-45%
- Option pool impact: 10-15%
- Final cap table: Founder 35-40%

Conclusion: "This is acceptable. Proceed with SAFE fundraising."
```

**Strategy 2: Cap SAFE Aggregate**
```
Founder's Rules:
- Max 3-4 SAFE investors per round
- Total capital: $500k-$1M
- Weighted average cap: Not below $4M
- Weighted average discount: Not above 20%

Effect:
- Limits cap table fragmentation
- Consolidates investor base
- Keeps dilution manageable
- Easier Series A negotiations
```

**Strategy 3: Graduated Cap Terms**
```
Early SAFEs (Month 1-2):
- Cap: $3M (more risk, better protection)
- Discount: 20%

Mid-Round SAFEs (Month 3-4):
- Cap: $4M (less risk, slightly less protection)
- Discount: 18%

Late-Round SAFEs (Month 5-6):
- Cap: $5M (approaching Series A assumptions)
- Discount: 15%

Effect:
- Early investors get better terms for higher risk
- Investor expectations set by timing
- Dilution increases gradually as risk decreases
- Cap table more predictable
```

---

## DECISION FRAMEWORK: SHOULD YOU USE A SAFE?

### Founder Decision Tree

```
START: "Should I raise capital via SAFE?"

Question 1: Are you pre-seed or seed stage?
├─ YES → Go to Q2
└─ NO → "Don't use SAFEs. Use Preferred Stock instead."

Question 2: Do you have a product?
├─ YES → Go to Q3
├─ NO (Pre-product) → Go to Q3 anyway
└─ N/A

Question 3: Are you raising $100k-$2M total?
├─ YES → Go to Q4
└─ NO → "Too much (>$2M use Preferred), too little (<$100k use grants)"

Question 4: Do you expect Series A within 12-18 months?
├─ YES → Go to Q5
└─ NO → "Use convertible notes (maturity protection) instead"

Question 5: Will you have 3-5 SAFE investors?
├─ YES → Go to Q6
├─ NO (more than 5) → "Use Preferred Stock, too fragmented"
└─ NO (less than 3) → Go to Q6 anyway

Question 6: Can you clearly define Qualifying Financing?
├─ YES → Go to Q7
└─ NO → "Define trigger terms explicitly"

Question 7: Ready to close quickly without lengthy docs?
├─ YES → "USE SAFEs - Good fit!"
├─ NO → "Use Preferred Stock if you want extensive docs"
└─ UNSURE → "SAFEs are simpler, consider it"
```

### Investor Decision Tree

```
START: "Should I invest via SAFE?"

Question 1: Is this a pre-seed/seed stage company?
├─ YES → Go to Q2
└─ NO (Series A+) → "Don't invest via SAFE. Use Preferred Stock."

Question 2: Is the team strong?
├─ YES → Go to Q3
└─ NO → "Don't invest. Move to better team."

Question 3: Do you have conviction on valuation?
├─ YES (can assess fair value) → Go to Q4
└─ NO (highly uncertain) → Go to Q4 anyway (that's why you want cap)

Question 4: Will you be happy with 2-3 year hold before conversion?
├─ YES → Go to Q5
└─ NO → "Use convertible note (maturity date) instead"

Question 5: Can you get strong terms (cap + discount)?
├─ YES → Go to Q6
├─ NO (weak terms) → Go to Q6 anyway or "Don't invest"
└─ UNSURE → "Negotiate for cap + discount"

Question 6: Can you get MFN clause + information rights?
├─ YES → Go to Q7
├─ NO (some missing) → Go to Q7 anyway
└─ UNSURE → "Negotiate hard for these"

Question 7: Can you get board observation?
├─ YES → Go to Q8
├─ NO → Go to Q8 anyway (lower priority than cap/discount)
└─ UNSURE → "Ask, but not critical"

Question 8: Is founder/team coachable and responsive?
├─ YES → "INVEST VIA SAFE - Good fit!"
├─ NO → "Don't invest. Founder won't listen to your input."
└─ UNSURE → "Be cautious. SAFEs require trust."
```

---

## TEMPLATES AND RESOURCES

This folder contains the following SAFE templates:

1. **SAFE_TEMPLATE.md** - Standard SAFE with no cap or discount
   - Simplest form, for companies with known Series A terms
   - Use when valuation cap and discount are not needed

2. **SAFE_POST-MONEY_TEMPLATE.md** - SAFE with post-money valuation cap
   - Most common variant in use today
   - Best for early-stage seed companies
   - Clear ownership percentage mathematics

3. **SAFE_PRE-MONEY_TEMPLATE.md** - SAFE with pre-money valuation cap
   - Slightly more investor-favorable
   - Less commonly used (post-money preferred)
   - For companies with prior funding rounds

4. **SAFE_DISCOUNT-CAP_TEMPLATE.md** - SAFE with both discount rate and valuation cap
   - Maximum investor protection
   - Most complex to calculate
   - Best for uncertain, competitive seed rounds

5. **FOUNDER_PERSPECTIVE.md** - Detailed guide for founders
   - Risks, concerns, and best practices
   - Dilution strategies and cap table management
   - Negotiation tactics

6. **INVESTOR_PERSPECTIVE.md** - Detailed guide for investors
   - Risks, concerns, and best practices
   - How to structure for downside protection
   - Governance and information rights

7. **NEGOTIATION_GUIDE.md** - Key terms to negotiate
   - For both founders and investors
   - Specific language suggestions
   - Market ranges for each term

---

## LEGAL DISCLAIMER

This resource is provided for educational purposes only and does not constitute legal, financial, or investment advice.

**Important:**
- Always consult with qualified legal counsel licensed in your jurisdiction before executing any SAFE or investment agreement
- SAFE terms vary by jurisdiction and situation
- Securities laws apply - ensure compliance with all regulations
- These templates should be customized for your specific situation
- Tax implications vary - consult a tax professional

**Resources:**
- Y Combinator SAFE Information: https://www.ycombinator.com/documents
- National Venture Capital Association: https://www.nvca.org
- Securities & Exchange Commission: https://www.sec.gov

---

**Document Version:** 1.0
**Last Updated:** November 2025
**Status:** Comprehensive SAFE Resource Guide
