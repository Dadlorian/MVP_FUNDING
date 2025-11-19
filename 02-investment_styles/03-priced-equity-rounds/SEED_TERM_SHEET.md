# Seed Round Term Sheet Template

**This is a non-binding summary of the proposed terms for a Series Seed preferred stock financing.**

---

## 1. SECURITIES TO BE ISSUED

| Item | Details |
|------|---------|
| **Security Type** | Series Seed Preferred Stock |
| **Aggregate Investment Amount** | $[INVESTMENT_AMOUNT] |
| **Price Per Share** | $[PRICE_PER_SHARE] |
| **Number of Shares Issued** | [NUMBER_OF_SHARES] |
| **Pre-Money Valuation** | $[PRE_MONEY_VALUATION] |
| **Post-Money Valuation** | $[POST_MONEY_VALUATION] |
| **Investor Ownership %** | [OWNERSHIP_PERCENTAGE]% |

### Calculation Examples:
- **Pre-Money**: $8,000,000
- **Investment**: $2,000,000
- **Post-Money**: $10,000,000 ($8M + $2M)
- **Investor %**: 20% ($2M / $10M)
- **Founder dilution**: From 100% to 80%

---

## 2. PRICE PER SHARE

| Item | Details |
|------|---------|
| **Calculation** | Post-Money Valuation ÷ Fully Diluted Shares Outstanding |
| **Post-Money Valuation** | $[POST_MONEY_VALUATION] |
| **Fully Diluted Shares** | [FULLY_DILUTED_SHARES] including options & RSUs |
| **Price Per Share** | $[PRICE_PER_SHARE] |

**Note**: Price per share must account for all existing equity (founder stock, employee options, RSUs, warrants, convertible instruments).

---

## 3. INVESTMENT TERMS

### Use of Proceeds (Example Breakdown)
- **Product Development**: [__]%
- **Go-to-Market/Sales**: [__]%
- **Operations/Admin**: [__]%
- **Runway**: [__] months

### Founder Commitment
- Founders commit [SPECIFIED_PERCENTAGE]% of personal capital to the round (optional but common in seed)
- Or: Founders maintaining [SPECIFIED_PERCENTAGE]% ownership post-investment

---

## 4. CAPITALIZATION TABLE (PRE-INVESTMENT)

| Holder | Common Shares | Options Outstanding | Weighted Avg Strike | % Ownership |
|--------|---------------|---------------------|-------------------|-------------|
| [FOUNDER_NAME] | [SHARES] | | | [%] |
| [FOUNDER_NAME] | [SHARES] | | | [%] |
| [EMPLOYEE_NAME] | [SHARES] | | | [%] |
| Employee Option Pool (reserved) | [SHARES] | [SHARES] | | [%] |
| TOTAL | [TOTAL_SHARES] | [OPTION_SHARES] | | 100% |

---

## 5. LIQUIDATION PREFERENCE

**Type**: [PARTICIPATING/NON-PARTICIPATING] Preferred Stock

### Non-Participating (Founder-Friendly)
- Investor receives:
  - **Either** the original investment amount back ($[INVESTMENT_AMOUNT])
  - **Or** their pro-rata share of proceeds (1/[POST_MONEY_DENOMINATOR] × proceeds)
  - Whichever is **greater**
- Upon conversion to common, investor shares in remaining proceeds like common stockholders

### Participating (Investor-Friendly)
- Investor receives:
  - **First**: their liquidation preference amount ($[INVESTMENT_AMOUNT])
  - **Then**: their pro-rata share of remaining proceeds
  - This is "double-dipping" - get back investment PLUS additional return
- Typically 1x participating (less aggressive than earlier investor preferences)

**RECOMMENDATION FOR SEED**: Non-participating preferred is more founder-friendly and appropriate for early stage.

---

## 6. ANTI-DILUTION PROTECTION

**Type**: [BROAD-BASED WEIGHTED AVERAGE / NARROW-BASED WEIGHTED AVERAGE / FULL RATCHET / NONE]

### Broad-Based Weighted Average (Founder-Friendly Default)
- Used if future financing is at lower price (down round)
- Conversion price adjustment: New CP = Old CP × √(Old Price × New Price / Current Stock)
- Example:
  - Seed price: $1.00/share
  - Down round at $0.50/share
  - Seed investor conversion adjusts downward proportionally
  - Minimizes founder dilution from down round repricing

### Narrow-Based Weighted Average (More Investor-Friendly)
- Uses only preferred shares outstanding (smaller denominator)
- More aggressive price adjustment in down rounds
- Greater protection for seed investor in down scenarios
- Greater dilution for founders in down rounds

### No Anti-Dilution (Alternative)
- Seed investor price stays fixed at $[PRICE_PER_SHARE]
- If down round occurs, investor simply doesn't participate
- Simplest approach
- Founder-friendly but signals investor confidence

**APPLIES TO**: Any subsequent financing below the price per share of this investment.

**EXCEPTIONS** (don't trigger anti-dilution):
- Issuance of shares reserved in employee option pool
- Issuance of shares upon conversion of convertible instruments
- Stock splits or stock dividends
- Issuance of shares to lenders as part of debt financing

---

## 7. BOARD COMPOSITION & BOARD SEAT RIGHTS

**Pre-Investment Board Composition**:
- [__] founder seat(s)
- [__] investor seat(s)
- [__] independent seat(s)

**Post-Investment Board Composition** (typically 3-person for seed):
- 1 Board Seat: [FOUNDER_NAME], CEO
- 1 Board Seat: [INVESTOR_NAME], Series Seed Investor (or designated representative)
- 1 Board Seat: [INDEPENDENT_DIRECTOR_NAME], [TITLE], independent director

**Board Designation Rights**:
- Series Seed investors holding [___]% of the Series Seed Preferred Stock shall have the right to designate one director so long as they own [___]% of the originally issued Series Seed shares.

**Board Observation Rights**:
- Seed investors who do not hold a seat shall have the right to attend all board meetings as observers.

**Minimum Board Meetings**: Quarterly, or more frequently as needed

**Board Committee Composition**:
- Audit Committee: [___]
- Compensation Committee: [___]
- Other: [___]

---

## 8. PROTECTIVE PROVISIONS (INVESTOR VETO RIGHTS)

The holders of Series Seed Preferred Stock shall have the following protective provisions (veto rights) on the following matters, each requiring the written consent of holders of [___]% of the Series Seed Preferred Stock:

- [ ] **Capital Structure Changes**:
  - Authorize, create, or issue new series of preferred stock
  - Increase or decrease authorized shares of any class of stock
  - Authorize any security convertible into preferred stock

- [ ] **Fundamental Changes**:
  - Sale, merger, or consolidation of the company
  - Liquidation or dissolution of the company
  - Any reorganization materially affecting the preferred stock

- [ ] **Business Operations**:
  - Change the size of the Board of Directors (unless elected by stockholders)
  - Change the business of the company in any material respect
  - Make capital expenditures exceeding $[__] in any fiscal year
  - Incur debt exceeding $[__] outside ordinary course of business

- [ ] **Compensation & Related Party**:
  - Employee salary increases >$[__] for any employee
  - Related party transactions exceeding $[__]
  - Change compensation of any Board member or executive >$[__]
  - Hire or terminate the Chief Executive Officer

- [ ] **Equity & Governance**:
  - Issue additional equity except as permitted in option pool
  - Declare or pay any dividend (except stock splits)
  - Repurchase stock except as mandated by law or agreements
  - Amend Certificate of Incorporation or Bylaws affecting preferred holders

- [ ] **Fundraising**:
  - Incur additional indebtedness exceeding $[__]
  - Authorize or issue equity financing at lower valuation than Series Seed

**BEST PRACTICE FOR SEED**: Minimize protective provisions to 3-5 items. Too many provisions can:
- Prevent future fundraising (investors won't accept stacked vetoes)
- Paralyze operations
- Create deadlock scenarios

**Suggested minimal Seed protections**:
1. Sale/merger/liquidation of company
2. Increase/create new preferred stock class
3. Change business materially
4. Hire/fire CEO

---

## 9. INVESTOR INFORMATION & REGISTRATION RIGHTS

### Information Rights
Holders of Series Seed Preferred Stock holding at least [___]% shall have the right to receive:

- **Annual Financials**: Within [__] days of fiscal year-end (audited or reviewed)
- **Quarterly Financials**: Within [__] days of quarter-end (unaudited)
- **Annual Budget**: [__] days before end of fiscal year
- **Quarterly Updates**: [__] days after quarter-end including:
  - Updated financial projections
  - Key metrics (MAU, DAU, churn, LTV, CAC, etc.)
  - Narrative of business progress
- **Monthly Updates** (optional): Simplified email updates on key metrics
- **Board Materials**: [__] days before each board meeting
- **Annual Meeting**: Right to attend annual stockholder meeting

### Inspection Rights
- Right to inspect books and records during normal business hours
- [__] hours notice required
- Right to consult with company's accountants re: financial matters

### Board Observation Rights (if not on board)
- Right to attend board meetings as observer
- Standard confidentiality & non-disclosure obligations apply

### Registration Rights (for future IPO)
- **Demand Rights**:
  - Holders of at least [___]% can demand company register stock for IPO
  - Company must use best efforts to register within [__] days
  - Holders can participate if at least [___]% of holdings registered

- **Piggyback Rights**:
  - Holders can include shares in any company-initiated registration
  - Company can cut back if underwriter limits offerings

- **Form S-3 Rights** (for more mature companies):
  - Holders can request registration on Form S-3 if available

- **Lock-Up Waiver**:
  - Founders typically locked up for 180 days post-IPO
  - Investors may negotiate reduced lock-up ([__] days)

---

## 10. PARTICIPATION & PRO-RATA RIGHTS

### Pro-Rata Participation Rights
Series Seed investors holding [___]% shall have the right to participate in future preferred stock financings to maintain their ownership percentage.

**Example**:
- Investor owns 20% post-Series Seed
- Series A is $5M
- Investor's pro-rata = 20% × $5M = $1M minimum

### How Pro-Rata Works:
- In Series A, investor can invest up to their pro-rata share
- If investor doesn't participate, they get diluted
- Pro-rata typically limited to holders of [___]% or more

### Co-Investment Right
- Holders can elect to invest additional capital in follow-on rounds
- Not a requirement, but option available

---

## 11. DRAG-ALONG & TAG-ALONG RIGHTS

### Drag-Along Rights
- Holders of [___]% of preferred stock can drag minority stockholders into company sale
- Requires same terms for all stockholders of same class
- Minority founders must sell shares if majority votes to sell

### Tag-Along Rights
- Minority stockholders can "tag along" in company sale at same price/terms
- Prevents founders from negotiating side deals
- Ensures all common stockholders get same price per share

**Example**:
- Company acquired for $100M
- Preferred stock holders are paid $X per share
- Common stock holders receive same $X per share (on pro-rata basis)
- Ensures fairness

---

## 12. VOTING RIGHTS & CONVERSION

### Voting Rights
- Each share of Series Seed Preferred Stock has [__] vote per share
- Series Seed votes with common stock on all matters except:
  - Matters specifically affecting preferred holders (covered under protective provisions)
  - Election of Preferred Stock director (Series Seed holder elects 1)

### Conversion Rights
- **Automatic Conversion**:
  - Upon IPO at valuation of at least $[__] million post-money
  - Upon written consent of holders of majority of Series Seed
  - All shares convert to Common Stock at then-current conversion price

- **Optional Conversion**:
  - At any time, holder can elect to convert Series Seed to Common Stock
  - Conversion price = original issue price (for seeds) or adjusted price

### Anti-Dilution Conversion
- Upon any event triggering anti-dilution protection, conversion price adjusts
- But shares don't automatically convert - holder can trigger conversion at new price

---

## 13. MARKET CONDITIONS & TIMING

| Item | Details |
|------|---------|
| **Target Closing Date** | [CLOSING_DATE] |
| **Conditions to Closing** | [LIST_CONDITIONS] |
| **Non-Binding Items** | Term Sheet terms (see below) |
| **Binding Items** | Confidentiality, Exclusivity, Expense |

### Non-Binding Provisions (can be modified):
- All economic terms
- Board composition
- Protective provisions
- Information rights
- Liquidation preference

### Binding Provisions (legally enforceable):
- Confidentiality & non-disclosure of terms
- Exclusivity (60-90 days typical)
  - Company can't shop to other investors
  - Exceptions for unsolicited inquiries
- Expense clause (loser pays legal fees? - rare in seed)

---

## 14. REPRESENTATIONS & WARRANTIES

### Company Representations (Founders confirm):
- [ ] Duly organized, validly existing, in good standing in [STATE]
- [ ] Authority to enter into transaction
- [ ] No conflicts with Certificate of Incorporation, Bylaws, or laws
- [ ] Capitalization table is accurate and complete
  - All outstanding stock, options, warrants listed
  - Exercise prices, vesting schedules documented
- [ ] No material undisclosed liabilities
- [ ] All employee agreements properly documented
  - IP assignments in place
  - Non-competes/non-solicits for key personnel
- [ ] No pending litigation or legal proceedings
- [ ] Financial statements accurate and complete
- [ ] No material adverse changes since [DATE]
- [ ] IP assignments from founders to company in place
  - All prior inventions documented
  - No third-party IP rights claimed
- [ ] No breaches of material contracts
- [ ] Compliance with all laws and regulations

### Investor Representations:
- [ ] Authority to invest
- [ ] Accredited investor (if applicable)
- [ ] Investment is for own account
- [ ] Investor understands risk of investment
- [ ] Can afford to lose entire investment

---

## 15. CONDITIONS TO CLOSING

Investment is conditioned upon:
- [ ] Completion of legal due diligence to investor's reasonable satisfaction
- [ ] Completion of financial/accounting due diligence
- [ ] No material adverse change in company's business
- [ ] Founder personal guarantees (if applicable): [__]
- [ ] Key person insurance (if applicable): [__]
- [ ] No litigation filed against company
- [ ] Legal documentation in form agreed to and finalized
- [ ] Board resolutions authorizing preferred stock issued
- [ ] Certificate of Incorporation amended to authorize Series Seed
- [ ] Representations & warranties of company true and correct as of closing

### Financing Conditions (Typical)
- This investment is contingent on minimum of $[__] in aggregate seed financing
- Individual investor must commit minimum of $[__]

---

## 16. LEGAL DOCUMENTATION & CLOSING

### Documents Required at Closing:
1. **Stock Purchase Agreement** - legal contract for stock purchase
2. **Stockholders' Agreement (Voting Agreement)** - board election & voting terms
3. **Investors' Rights Agreement** - information rights, registration, drag/tag
4. **Right of First Refusal & Co-Sale Agreement** - restrictions on stock sales
5. **Board Resolutions** - company board authorizing issuance
6. **Certificate of Amendment** - amending Certificate to authorize Series Seed
7. **Cap Table Amendment** - updated ownership schedule
8. **Legal Opinion** - company law firm opinion on validity of stock issuance
9. **Disclosure Schedules** - exceptions & details to reps & warranties

### Estimated Timeline:
- **Term Sheet Negotiation**: 1-2 weeks
- **Due Diligence**: 2-4 weeks
- **Document Preparation**: 1-2 weeks
- **Negotiation of Legal Docs**: 1-2 weeks
- **Total Typical Process**: 6-10 weeks

### Closing Mechanics:
- Wire funds 1-2 business days before closing
- Stock certificates issued at closing
- All documents signed and delivered
- Capitalization table updated

---

## 17. POST-CLOSING COVENANTS

### Investor Rights (Post-Closing Obligations)
- Company will file Certificate of Amendment with Delaware Secretary of State
- Company will register shares with transfer agent
- Company will amend Capitalization Table within [__] days
- Company will deliver stock certificates or book entries

### Company Obligations
- Furnish quarterly financial statements (unaudited) within [__] days
- Furnish annual financial statements (reviewed) within [__] days
- Maintain key person insurance policies (optional)
- Maintain business in accordance with business plan and projections

---

## 18. DILUTION & FUTURE ROUNDS

### Anti-Dilution Upon Future Rounds
See Section 6 for anti-dilution mechanics.

### Employee Option Pool
- [___]% of post-investment fully diluted capitalization reserved for options
- If more shares needed in future rounds, must adjust from common stock pool
- This dilutes founders further

### Expected Future Rounds
- **Series A**: Expected within [__] years at valuation of $[__]
- **Series B**: Expected within [__] years post-Series A
- Company should model equity dilution through expected Series C

---

## 19. MISCELLANEOUS TERMS

### Expenses
- Each party bears its own legal and advisory fees
- [Alternative: Loser pays winner's legal fees]
- [Alternative: Company reimburses investor legal fees if deal closes]

### Governing Law
- This term sheet governed by laws of [JURISDICTION] without regard to conflicts of law
- Venue: Courts of [COUNTY], [STATE]

### Entire Agreement
- This term sheet represents the entire agreement between parties regarding investments
- Supersedes all previous discussions, understandings, and written/oral proposals

### Confidentiality
- Both parties agree to maintain confidentiality of terms
- Exceptions:
  - Necessary disclosures to attorneys, accountants, advisors
  - Required by law or court order
  - Disclosures to existing/future investors or acquirers
  - [CUSTOMIZED EXCEPTIONS]

### Exclusivity
- For [__] days from date hereof, company agrees not to solicit or accept any other investment offers
- Company may:
  - Respond to unsolicited inquiries
  - Continue conversations with [NAMED_EXCEPTIONS]

### Amendments
- This term sheet may only be amended by written consent of both parties

---

## 20. SIGNATURES

**This term sheet is binding with respect to confidentiality, exclusivity, and expense provisions. All other terms are non-binding until legal documents are executed.**

### Company

Company Name: [COMPANY_NAME]

By: ____________________________
Name: [FOUNDER_NAME]
Title: [TITLE]
Date: [DATE]

By: ____________________________
Name: [FOUNDER_NAME]
Title: [TITLE]
Date: [DATE]


### Investor

Investor Name: [INVESTOR_NAME]

By: ____________________________
Name: [INVESTOR_SIGNATORY_NAME]
Title: [TITLE]
Date: [DATE]

---

## NEXT STEPS

1. **Within 2 days**: Both parties review and discuss any proposed changes
2. **Within 5 days**: Return signed term sheet to other party
3. **Within 7 days**: Company engages legal counsel to begin document preparation
4. **Within 14 days**: Investor completes preliminary due diligence
5. **Within 21 days**: Legal documents shared for review
6. **Within 30 days**: Legal documents finalized and executed
7. **Within 35 days**: Closing occurs (funds transferred, stock issued)

---

## APPENDICES

### Appendix A: Business Plan Summary
[Include: 1-page executive summary, key milestones, team bios]

### Appendix B: Financial Projections
[Include: 3-year revenue/expense projections, key assumptions, unit economics]

### Appendix C: Use of Proceeds
[Include: detailed allocation of capital raised]

### Appendix D: Key Metrics Dashboard
[Include: monthly metrics for past 12 months showing traction]

---

**DISCLAIMER**: This template is for educational purposes. Do not use without consulting a qualified startup attorney. Each investment involves unique terms and requires customization to your specific situation.
