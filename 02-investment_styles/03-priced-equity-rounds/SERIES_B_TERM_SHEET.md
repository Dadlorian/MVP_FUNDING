# Series B Term Sheet Template

**This is a non-binding summary of the proposed terms for a Series B preferred stock financing.**

---

## 1. SECURITIES TO BE ISSUED

| Item | Details |
|------|---------|
| **Security Type** | Series B Preferred Stock |
| **Aggregate Investment Amount** | $[INVESTMENT_AMOUNT] |
| **Price Per Share** | $[PRICE_PER_SHARE] |
| **Number of Shares Issued** | [NUMBER_OF_SHARES] |
| **Pre-Money Valuation** | $[PRE_MONEY_VALUATION] |
| **Post-Money Valuation** | $[POST_MONEY_VALUATION] |
| **Series B Investor Ownership %** | [OWNERSHIP_PERCENTAGE]% |

### Fully Diluted Cap Table Post-Series B:
| Holder | Ownership % |
|--------|------------|
| Founders (Common) | [__]% |
| Series Seed Investors | [__]% |
| Series A Investors | [__]% |
| Series B Investors | [__]% |
| Employee Option Pool | [__]% |
| TOTAL | 100% |

### Post-Series B Founder Ownership Progression:
- After Seed: ~83%
- After Series A: ~67%
- After Series B: ~45-50%

---

## 2. INVESTMENT CONTEXT & STAGE

### Series B is for Growth-Stage Companies:

**Typical Requirements**:
- [ ] Proven product-market fit (strong retention metrics)
- [ ] Revenue of $[__]/month or [__]% year-over-year growth
- [ ] Unit economics validated (LTV > 3x CAC, or similar)
- [ ] Strong founding team with proven execution
- [ ] Clear path to profitability or major milestone
- [ ] Market size validated at $[__]B+
- [ ] [__] headcount reached

**Series B Objectives**:
- Geographic expansion: [__] new markets/countries
- Product expansion: New features/verticals
- Sales team build-out: [__] sales reps
- Marketing efficiency: Reduce CAC to $[__]
- Achieve [__]M ARR by [__] (end of year 2 post-Series B)

**Time Since Series A**: Typically 18-36 months

---

## 3. LIQUIDATION PREFERENCES & WATERFALL

**Type**: [PARTICIPATING/NON-PARTICIPATING] Preferred Stock

### Typical Series B Structure: 1x Participating Preferred

**Liquidation Preference Hierarchy** (in order of payment upon liquidity event):

1. **Series B** (newest investors): First priority
   - Receives their investment back ($[INVESTMENT_AMOUNT])

2. **Series A** (prior investors): Second priority
   - Receives their investment back ($[__] total)

3. **Series Seed** (early investors): Third priority
   - Receives their investment back ($[__] total)

4. **Common Stock** (founders): Last priority
   - Gets whatever remains

### Example Waterfall at $100M Exit:

**Assuming**:
- Seed: $2M investment
- Series A: $10M investment
- Series B: $30M investment
- Founders: ~45% common ownership

**Payoff**:
1. Series B preferred: Gets $30M back
2. Series A preferred: Gets $10M back
3. Seed preferred: Gets $2M back
4. Remaining: $100M - $30M - $10M - $2M = $58M
5. Common stock (founders): Gets $58M (58% of proceeds despite owning 45%)

### Example Waterfall at $50M Exit (Down Round Case):

**Payoff**:
1. Series B preferred: Gets $30M back
2. Series A preferred: Gets $10M back
3. Series Seed: Gets $10M (only $10M left, but preference was $2M)
4. Remaining: $0
5. Common stock (founders): Get NOTHING

**Outcome**: Founders own company on paper, get nothing in down exit

### Example Waterfall at $25M Exit (Very Down Case):

**Payoff**:
1. Series B preferred: Gets $25M (full investment recovered)
2. Series A preferred: $0
3. Series Seed: $0
4. Common stock (founders): $0

**Outcome**: Only newest investors recover capital

---

## 4. ANTI-DILUTION & DOWN ROUND PROTECTION

**Type**: [BROAD-BASED WEIGHTED AVERAGE / NARROW-BASED WEIGHTED AVERAGE / FULL RATCHET]

### Series B Anti-Dilution (Standard: Broad-Based Weighted Average)

**Trigger**: Any future equity financing below Series B price per share

**Formula**:
```
New Conversion Price = Old CP × √[(Old Price × New Price) / (Current Price²)]
```

**Series B Down Round Example**:
- Series B price: $10/share
- Series C at: $8/share (20% down)
- New CP = $10 × √[($10 × $8) / ($10²)]
- New CP = $10 × √[0.8]
- New CP = **$8.94/share**

**Impact on Founders**:
- Series B investors' shares re-price downward
- But this is applied across entire common pool
- Reduces shares available for founders (net dilution increase)
- Founders bear burden of down round

### Anti-Dilution vs. Down Round Risk

**Series B Investor Perspective**:
- Already has 1x participating preference
- Broad-based weighted average provides reasonable downside protection
- But dilution from future rounds is real

**Series B vs Series A Anti-Dilution Stacking**:
- Series A has broad-based weighted average from their investment
- Series B adds another broad-based weighted average layer
- In severe down round, both adjust downward
- Compounding effect can be dramatic

**Series C Down Round Example**:
- Series A @ $5/share, anti-dilution triggers
- Series B @ $10/share, anti-dilution triggers
- Series C @ $4/share (severe down round)
- Both Series A and B re-price
- Founders face maximum dilution

---

## 5. BOARD COMPOSITION & GOVERNANCE

**New Board Structure** (typically 5-7 members for Series B):

| Seat | Holder | Title |
|------|--------|-------|
| 1 | [FOUNDER/CEO_NAME] | CEO/Founder |
| 2 | [FOUNDER_NAME] (optional) | Founder |
| 3 | [SERIES_B_INVESTOR_NAME] | Series B Lead Investor |
| 4 | [SERIES_A_INVESTOR_NAME] | Series A Investor |
| 5 | [INDEPENDENT_DIRECTOR_1] | Independent Director |
| 6 | [INDEPENDENT_DIRECTOR_2] | Independent Director (optional) |
| 7 | [MUTUAL_DIRECTOR] | Agreed upon director (optional) |

### Board Seat Designations

| Investor Class | Voting Power | Board Seat Right | Threshold |
|----------------|--------------|------------------|-----------|
| Series B | [__] votes/share | Designate [1-2] directors | [__]% ownership |
| Series A | [__] votes/share | Designate [0-1] director | [__]% ownership |
| Seed | [__] votes/share | Observer rights | [__]% ownership |
| Common | [__] votes/share | CEO seat | N/A |

### Board Designation Rights Mechanics:
- Series B lead investor designates [__] director
- Series A lead investor may designate [__] director (if [___]% threshold)
- Founders control CEO seat + 1 additional if possible
- Independent directors chosen by consensus
- Board size should be odd (3, 5, 7) to avoid deadlock

### Founder Considerations:
- Founder should keep CEO seat at all costs
- Negotiate for second founder seat or strong ally
- Independent directors should be favorable
- Board composition can determine company direction

### Board Meeting Structure:
- Monthly board meetings (required)
- [__] hour meetings typical
- Board materials 5 business days in advance
- Executive sessions: without management present
- Committee meetings: separate from full board

### Board Committees:

| Committee | Purpose | Members |
|-----------|---------|---------|
| Audit | Financial statements, controls, compliance | 3 independent |
| Compensation | Executive pay, incentives, option pool | 2-3 including investor |
| Nominating/Governance | Board composition, corporate governance | 2-3 including independent |

---

## 6. PROTECTIVE PROVISIONS (VETO RIGHTS)

Series B investors holding [___]% of Series B Preferred Stock shall have the right to approve the following matters:

### Complete Protective Provisions List (Series B Typical: 10-15 items)

1. **Capitalization Structure** (Comprehensive)
   - Create, authorize, or issue any new series of stock
   - Increase or decrease authorized shares of any class
   - Adjust conversion rates of any preferred stock
   - Repurchase or redeem stock (except lapse of options)
   - Declare or pay any dividend or distribution
   - Recapitalize or reclassify stock
   - Create any class of stock with senior rights

2. **Business Fundamentals** (Core Operations)
   - Sale of company, merger, consolidation, liquidation
   - Acquisition of another company (material)
   - Liquidate or wind down assets
   - Change business in any material way
   - Acquire assets outside ordinary course (>${__])
   - Enter/exit any material market or business line

3. **Compensation & Personnel** (Detailed Control)
   - Hire, fire, or change compensation of CEO
   - Hire, fire, or change compensation of CFO or CTO
   - Establish or change Board compensation
   - Approve salary increases >$[__] for any executive
   - Establish or change bonus pools
   - Approve any related-party transactions >${__}
   - Provide loans to officers or directors

4. **Budget & Financial Controls**
   - Approve annual operating budget
   - Approve material variance from budget (>$[__] or >20%)
   - Approve material capital expenditures (>${__})
   - Approve annual financial forecast
   - Make any single expenditure >$[__] not in budget

5. **Debt & Obligations**
   - Incur debt >$[__] (excluding trade payables)
   - Assume guarantees or contingent liabilities >$[__]
   - Create liens on assets
   - Refinance existing debt
   - Change debt terms

6. **Equity & Compensation**
   - Issue stock options or RSUs (outside approved pool)
   - Change vesting schedules
   - Grant accelerated vesting
   - Issue equity to founders/employees >$[__] annually
   - Create new class of equity for employees

7. **Governance & Structure**
   - Change size of Board of Directors
   - Amend Certificate of Incorporation or Bylaws
   - Change voting rights or preferences of any stock
   - Change any protective provisions for preferred stock
   - Merge into holding company

8. **Affiliate Transactions**
   - Any transaction with founders, officers, or affiliates
   - Lease agreements with related parties
   - Service agreements with related parties
   - Investments in related party entities

9. **Material Contracts** (Discretionary)
   - Approve contracts outside ordinary course >$[__]
   - Customer concentration: loss of >$[__] revenue/year
   - Supplier concentration: >$[__] of inputs from one supplier
   - Strategic partnerships or alliances >$[__]

10. **Financing & Funding**
    - Additional equity or preferred stock issuance
    - Convertible debt or debt with equity features
    - IPO or public offering
    - Secondary sales of company stock
    - Refinancing of existing capital structure

### Scope & Mechanics:
- **Voting Threshold**: [___]% of Series B preferred holders
  - Often 50% (majority)
  - Sometimes higher for more severe items
  - Sometimes different thresholds for different items

- **Board Delegation**: Often delegated to board (board makes decisions subject to investor veto)

- **Timing**: Investor veto must be exercised within [__] days
  - If no response within timeframe, deemed approved

- **Exceptions**: Some provisions may have "baskets" (don't require approval if <$[__])

### Founder Negotiation Points for Protective Provisions:
1. Request higher ownership threshold (25% instead of 15%)
2. Limit protective provisions to truly material items
3. Carve out R&D spending and product development
4. Carve out hiring within approved budget
5. Exclude strategic initiatives from "material change"
6. Request mutual consent provisions (not unilateral investor veto)
7. Sunset certain provisions after milestones
8. Request approval timeline (deemed approval if no response)

---

## 7. INVESTOR RIGHTS AGREEMENT & INFORMATION RIGHTS

### Information & Reporting Rights

**Holders of [___]% of Series B Preferred Stock shall receive**:

**Quarterly (within [__] days of quarter close)**:
- Unaudited financial statements (P&L, Balance Sheet, Cash Flow)
- [__]-page narrative covering:
  - Key business metrics (revenue, growth, churn, etc.)
  - Progress vs. plan
  - Market developments
  - Risk updates
  - Quarterly milestones
- Updated capitalization table
- Board meeting minutes (within [__] days)

**Annually (within [__] days of fiscal year-end)**:
- Audited or reviewed financial statements (audited by year 2+)
- Annual budget and [__]-year forecast
- Annual business plan update
- Annual meeting attendance

**Monthly (optional but common in Series B)**:
- 1-2 page email with key metrics:
  - Monthly revenue / ARR growth
  - Churn, customer acquisition
  - Burn rate, cash position, runway
  - Headcount and hiring progress
  - Major wins/losses

**Upon Request**:
- Access to books, records, contracts
- Right to meet with company management
- Right to consult with auditors/accountants
- Right to speak with key employees (optional)

### Board Meeting & Access Rights
- Attend all board meetings (Series B investor seat on board)
- Receive board materials 5 days before meetings
- Attend any investor meetings or pitches
- Quarterly [__]-minute investor update calls
- Annual investor day/conference

### Investor Interaction Norms:
- Primary contact: [SERIES_B_INVESTOR_PERSON_NAME]
- Communication protocol: [WEEKLY/BI-WEEKLY/MONTHLY]
- Board meetings: [DAY_OF_MONTH]
- Investor update calls: [DAY/TIME]

### Reps & Warranties (what company certifies):
See Section 11 for comprehensive list

---

## 8. PARTICIPATION & PRO-RATA RIGHTS

### Pro-Rata Participation Right (Right to Maintain Ownership)

**Holders of [___]% of Series B Preferred Stock have the right to participate in future preferred stock financings pro-rata to their ownership.**

**Mechanics**:
- Series C financing announced at $[X]M
- Series B investor with 20% ownership gets first right to invest 20% of Series C
- If investor commits, gets shares at Series C price
- If investor declines, their ownership dilutes in Series C

**How to Exercise**:
- Company offers participation letter: "You have right to invest up to $[__]"
- Investor has [__] days to accept or decline
- If accepted, investor commits capital by [__] date
- Funds received, shares issued same as other Series C investors

### Mechanics of Dilution:
- Series B investor owns 20% of company pre-Series C
- Series C raises $30M at $50/share pre-money valuation
- Pro-rata = 20% × $30M = $6M
- If investor participates: ownership stays ~20%
- If investor declines: ownership drops to ~16% (diluted)

### Pro-Rata Right Importance:
- **Most valuable right** to Series B investor
- Without pro-rata, investors dilute in Series C, D, E
- With pro-rata, can maintain ownership if capital available
- Allows investors to keep "pace" with company growth

### Pro-Rata Carve-Outs (don't apply to):
- Secondary/management equity
- Employee option pool
- Strategic equity deals
- Debt with warrants
- Convertible instruments

### Co-Investment Right:
- Beyond pro-rata, investors can opt to invest additional capital
- Not required, but available opportunity
- Often used if investor particularly bullish on company

---

## 9. DRAG-ALONG & TAG-ALONG RIGHTS

### Drag-Along Rights (Majority Forces Minority to Sell)

**If holders of [___]% of preferred stock approve a sale**, all other shareholders (including founders) must sell on same terms.

**Typical triggers for drag-along**:
- Acquisition for $[__]M+
- IPO
- Merger
- Liquidation

**Protection for Founders**:
- Drag-along requires approval of majority of [PREFERRED/COMMON] stock
- Prevents single investor from forcing bad sale
- Board must recommend deal

### Tag-Along Rights (Minority Can Force Inclusion in Sale)

**If majority shareholders (Series B investors) sell company, minority can force inclusion at same price/terms.**

**Typical scenario**:
- Series B investor holds 25%
- Gets acquisition offer for their stake
- Other holders can "tag along" requiring buyer to purchase their shares too

**Price Protection**:
- All shareholders get same price per share (pro-rata)
- Founder can't be left behind while investors sell

### Drag/Tag Example Scenario:

**Company Facts**:
- Series B investor: 25% ownership, wants to sell
- Series A investor: 20% ownership
- Founders: 45% ownership
- Buyer offers $200M for entire company

**With Drag-Along/Tag-Along**:
- Majority (Series B + Series A = 45% > threshold) approves sale
- Series B drags minority shareholders along
- Founders must sell shares
- All get same $200M / (shares) per share
- Founders get 45% of proceeds ($90M)

**Without Drag-Along**:
- Series B tries to sell their 25%
- Founders could refuse (own 45%, can block)
- Negotiations break down
- No sale occurs

---

## 10. VOTING, CONVERSION & REGISTRATION RIGHTS

### Voting Rights

**Each share of Series B Preferred Stock has [__] vote per share**

**Voting on matters**:
- All matters affecting all shareholders (amendment of Certificate)
- Matters affecting preferred stock class
- Election of directors (preferred holders elect 1-2, depending on structure)

**One Series B Share = [__] Common Share equivalent for voting on most matters**

### Conversion Rights

**Automatic Conversion Upon IPO**:
- All Series B Preferred converts to Common Stock at effective time of IPO
- Ratio typically 1:1 (adjusted for splits/recaps)
- Conversion is automatic (no election needed)

**Conversion Price Adjustments**:
- Anti-dilution adjustments apply (see Section 4)
- If down round occurs, conversion price may adjust
- Upon conversion, investor owns adjusted number of shares

**Voting Upon Conversion**:
- Once converted to Common, no longer preferred shareholder
- Loses protective provisions
- Loses liquidation preferences
- Gains registration rights (can demand registrations in IPO process)

### Redemption Rights (Rare)

**Some Series B term sheets include redemption right**:
- After [__] years (e.g., year 7), if no IPO or acquisition
- Company must repurchase shares at [FMV/FORMULA/ORIGINAL_PRICE]
- Creates liability on balance sheet
- Very rare in modern venture financing
- Creates pressure to exit on timeline

### Registration Rights (for eventual IPO)

**Demand Registration Rights** (if holders own [___]%):
- Can demand company register shares for IPO
- Company must use best efforts to register within [__] days
- Only [__] demand rights available

**Piggyback Registration Rights**:
- If company registers shares, investor can include shares
- Applies to any company-initiated registration

**Form S-3 Rights** (for companies with $75M+ public float):
- Can demand registration on Form S-3 (faster/cheaper than S-1)
- Trigger: [__] demand rights per year

**Lock-Up Release**:
- Post-IPO, shareholders typically locked up 180 days
- Investor can negotiate reduced lock-up: [__] days
- Or staggered release

---

## 11. REPRESENTATIONS, WARRANTIES & CONDITIONS

### Company Representations & Warranties

**Organization**:
- [ ] Duly organized and validly existing in [STATE]
- [ ] Good standing in all jurisdictions
- [ ] Authority to execute agreements
- [ ] No conflicts with Certificate, Bylaws, law

**Capitalization** (comprehensive):
- [ ] Capitalization table is true, complete, accurate
- [ ] All stock, options, RSUs, warrants, convertibles listed
- [ ] No outstanding rights to purchase equity
- [ ] Vesting schedules and exercise prices documented
- [ ] All employee/advisor option agreements signed
- [ ] No repurchase rights or call provisions outstanding

**Financial Statements & Condition**:
- [ ] Financial statements prepared per GAAP (or consistent basis)
- [ ] Accurately reflect financial condition
- [ ] No undisclosed liabilities (current or contingent)
- [ ] No material adverse changes since [DATE]
- [ ] Cash position, receivables, payables as represented
- [ ] Inventory valued at lower of cost or market

**Contracts & Obligations**:
- [ ] All material contracts listed and disclosed
- [ ] No breaches of material contracts
- [ ] All customer contracts available
- [ ] All vendor/supplier agreements documented
- [ ] No liens, security interests, or claims on assets
- [ ] Debt obligations fully documented and disclosed

**Intellectual Property**:
- [ ] All IP owned by company (not licensed from third parties)
- [ ] Proper assignments from all founders, employees, contractors
- [ ] All prior inventions/IP documented
- [ ] Trademarks registered or applications pending
- [ ] No third-party claims to IP
- [ ] No infringement of third-party IP rights
- [ ] Proper open-source license compliance

**Employees & Contractors**:
- [ ] All employment agreements signed
- [ ] Founders have waived prior invention claims
- [ ] Key employees have non-competes/non-solicits (where applicable)
- [ ] No pending departures or knowledge
- [ ] Compensation is market-rate
- [ ] No promises of equity outside option pool

**Compliance & Legal**:
- [ ] Compliance with all laws and regulations
- [ ] No pending or threatened litigation
- [ ] No regulatory investigations
- [ ] Tax filings current and accurate
- [ ] No IRS disputes or audits
- [ ] All required licenses and permits obtained

**No Undisclosed Liabilities**:
- [ ] No off-balance sheet arrangements
- [ ] No contingent liabilities
- [ ] No product warranties beyond disclosed
- [ ] No environmental liabilities
- [ ] No indemnification obligations

### Investor Representations:
- [ ] Authority to make investment
- [ ] Accredited investor (if required)
- [ ] Investment for own account
- [ ] Sophisticated investor with startup experience
- [ ] Understands risks
- [ ] Able to afford loss of investment

### Conditions to Closing

**Legal Conditions**:
- [ ] Due diligence satisfactory (legal, financial, market, technical)
- [ ] Certificate of Incorporation amended for Series B
- [ ] Board resolutions authorizing issuance
- [ ] No material adverse change (MAC clause)
- [ ] All agreements in final form
- [ ] Legal opinion delivered

**Financial Conditions**:
- [ ] Financial statements and projections provided
- [ ] Accounting review completed
- [ ] Cap table finalized and agreed
- [ ] Key metrics and financial covenants acceptable

**Other Conditions**:
- [ ] Minimum aggregate Series B investment of $[__] received
- [ ] Key employee non-departures
- [ ] Major customer retention
- [ ] Key contracts in place
- [ ] Insurance coverage confirmed
- [ ] References/background checks satisfactory

---

## 12. POST-CLOSING COVENANTS

### Company Obligations (Post-Closing)

**Reporting & Governance**:
- File Certificate of Amendment with Secretary of State
- Register shares with transfer agent
- Update cap table within [__] days
- Deliver stock certificates (or book entries)
- Provide quarterly financial statements (within [__] days)
- Provide annual financials (within [__] days)

**Business Operations**:
- Operate per approved business plan
- Notify board immediately of material issues:
  - Customer/partner loss
  - Key employee departure
  - Litigation
  - Regulatory issues
  - Financial misses
  - Material contract issues

**Equity Management**:
- Maintain option pool at [___]% of fully diluted
- Board approval of all option grants
- No grants outside of pool without investor consent
- Vesting schedules per standard plan

**Financial Controls**:
- Maintain bank accounts in company name
- Monthly reconciliations
- Annual external review (year 2+) or audit (year 3+)
- Quarterly forecasting
- Annual budgeting

---

## 13. USE OF PROCEEDS

| Use | Amount | % of Total | Timeline |
|-----|--------|-----------|----------|
| Product Development | $[__] | [__]% | [MONTH] |
| Engineering Hiring | $[__] | [__]% | [MONTH] |
| Sales & Marketing | $[__] | [__]% | [MONTH] |
| Sales Hiring | $[__] | [__]% | [MONTH] |
| Operations/Admin | $[__] | [__]% | [MONTH] |
| Facilities/Infrastructure | $[__] | [__]% | [MONTH] |
| Working Capital/Reserves | $[__] | [__]% | [MONTH] |
| **TOTAL** | **$[TOTAL]** | **100%** |  |

### Financial Projections:
- Monthly burn rate: $[__]
- Months of runway (post-Series B): [__] months
- Expected cash-flow positive: Month [__], Year [__]
- Path to profitability: [DESCRIPTION]

### Contingencies:
- If burn >20% above plan, triggers board discussion
- If revenue <20% below plan, triggers fundraising discussions
- If key milestone missed, may trigger Series C timeline adjustment

---

## 14. ANTI-DILUTION MECHANICS & CALCULATIONS

### Example: Series B to Series C Down Round

**Series B Facts**:
- Price: $10/share
- Series B investors own 25%

**Series C Down Round**:
- Price: $7/share (30% down)
- New Series C shares issued: [X]

**Anti-Dilution Calculation** (Broad-Based Weighted Average):
```
New CP = $10 × √[($10 × $7) / ($10²)]
New CP = $10 × √[0.7]
New CP = $10 × 0.837
New CP = $8.37/share
```

**Impact on Founders**:
- Founders' shares effectively worth less
- But overall founder dilution increases from both anti-dilution AND Series C issuance

### Stacked Anti-Dilution Scenario (Worst Case)

**Series A Down Round Impact**:
- Series A investors' shares re-price downward
- This increases Series A ownership (from fixed stake perspective)
- Dilutes founders

**Then Series B Down Round Impact**:
- Series B investors' shares re-price downward
- PLUS Series B's own expansion
- Cumulative dilution to founders

**Series A + Series B stacking example**:
- Original: Founder 60%, Series A 20%, Series B 20%
- Series C down round at 50% of Series B price
- Both Series A and Series B anti-dilution triggers
- Result: Founder dilution to ~45-50% (massive)

---

## 15. TERM SHEET TIMELINE & NEXT STEPS

| Activity | Target Date | Duration |
|----------|------------|----------|
| Term Sheet Signature | [DATE] | Days 1-7 |
| Legal Counsel Engaged | [DATE] | Days 1-7 |
| Financial Due Diligence | [DATE] | Days 1-21 |
| Technical/Product Due Diligence | [DATE] | Days 1-21 |
| Reference Checks | [DATE] | Days 7-21 |
| Legal Documents Drafted | [DATE] | Days 7-28 |
| Document Negotiations | [DATE] | Days 14-35 |
| Final Due Diligence Review | [DATE] | Days 21-42 |
| Document Execution | [DATE] | Days 42-50 |
| Closing | [DATE] | Days 50-60 |

---

## 16. BINDING VS. NON-BINDING TERMS

### Binding (Legally Enforceable):
- Confidentiality of terms
- Exclusivity provisions ([__] days)
- Expense clause
- Representations & warranties (if in SPA)

### Non-Binding (Until Definitive Agreements):
- All economic terms
- Liquidation preferences
- Anti-dilution mechanics
- Board composition
- Protective provisions
- Investor rights
- Use of proceeds

---

## 17. CLOSING DOCUMENTS REQUIRED

1. Stock Purchase Agreement
2. Investors' Rights Agreement
3. Stockholders' Agreement (Voting)
4. ROFR & Co-Sale Agreement
5. Board Resolutions
6. Capitalization Table
7. Certificate of Amendment
8. Legal Opinions
9. Disclosure Schedules
10. Financial Statements

---

## 18. SIGNATURES

### Company

Company Name: [COMPANY_NAME]

By: ____________________________
Name: [FOUNDER/CEO_NAME]
Title: CEO
Date: [DATE]

By: ____________________________
Name: [FOUNDER_NAME]
Title: [TITLE]
Date: [DATE]


### Series B Lead Investor

Investor Name: [INVESTOR_NAME]

By: ____________________________
Name: [INVESTOR_SIGNATORY_NAME]
Title: [TITLE]
Date: [DATE]


### Additional Series B Investors

[Repeat for each investor]

---

## 19. KEY TERMS COMPARISON: SEED vs. SERIES A vs. SERIES B

| Term | Seed | Series A | Series B |
|------|------|----------|----------|
| Funding | $500K - $2M | $2M - $15M | $10M - $50M |
| Pre-Money Valuation | $2M - $10M | $10M - $100M | $50M - $500M |
| Investor Ownership | 10-20% | 15-25% | 20-30% |
| Board Size | 3 | 5 | 5-7 |
| Investor Board Seats | 1 | 1-2 | 1-2 |
| Liquidation Preference | 1x Non-Participating | 1x Participating | 1x Participating |
| Anti-Dilution | Broad-based | Broad-based | Broad-based |
| Protective Provisions | 3-5 items | 8-12 items | 10-15 items |
| Pro-Rata Rights | Maybe | Yes | Yes |
| Drag/Tag Along | No/Yes | Yes/Yes | Yes/Yes |
| Information Rights | Quarterly | Monthly + Quarterly | Monthly + Quarterly |
| Timeline to Close | 6-10 weeks | 8-12 weeks | 10-16 weeks |
| Founder Ownership Post | ~80% | ~65% | ~45-50% |

---

**DISCLAIMER**: This template is educational only. Do not use without consulting qualified startup attorney. Series B financing involves complex legal and financial implications requiring customization to your specific circumstances.
