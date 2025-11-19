# SIMPLE AGREEMENT FOR FUTURE EQUITY (SAFE)
## Discount Rate + Valuation Cap Variant

**IMPORTANT NOTICE:** This document is provided as a template for informational purposes only and does not constitute legal advice. Consult qualified legal counsel before execution.

---

## 1. KEY TERMS AT A GLANCE

| Term | Value |
|------|-------|
| **Agreement Type** | SAFE with Discount Rate AND Valuation Cap |
| **Investment Amount** | $[INVESTMENT_AMOUNT] USD |
| **Post-Money Valuation Cap** | $[POST_MONEY_CAP] USD |
| **Discount Rate** | [DISCOUNT_PERCENTAGE]% (e.g., 20-30%) |
| **Expected Investor Protection** | Maximum coverage from both discount and cap |

---

## 2. WHY BOTH DISCOUNT AND CAP?

### 2.1 Dual Protection Strategy

This SAFE includes **two** protective mechanisms for the investor:

| Mechanism | Purpose | Effect |
|-----------|---------|--------|
| **Valuation Cap** | Limits how much company valuation can increase | Ensures investor owns minimum percentage |
| **Discount Rate** | Rewards early investment with price reduction | Investor pays less per share than Series A |
| **Both Together** | Investor gets BEST OF BOTH PROTECTIONS | Maximum upside benefit |

### 2.2 Typical Scenarios

**Scenario A: Cap Applies (Up Round)**
- Series A values company higher than cap
- Investor uses cap, not discount
- Investor still gets favorable conversion

**Scenario B: Discount Applies (Flat/Down Round)**
- Series A values company lower than cap implies
- Investor uses discount, not cap
- Investor gets price reduction benefit

**Scenario C: Both Partially Apply**
- Complex scenario where both formulas matter
- Investor receives greater of the two protections

### 2.3 Investment Amount
Investor invests $[INVESTMENT_AMOUNT] USD:
- Not a debt instrument
- No repayment or interest obligation
- Fully creditable toward future equity
- Used to purchase shares at conversion

---

## 3. CONVERSION MECHANICS: THE DISCOUNT MECHANISM

### 3.1 Discount Rate Definition

The "**Discount Rate**" is [DISCOUNT_PERCENTAGE]%, meaning Investor purchases equity at a [DISCOUNT_PERCENTAGE]% discount to the Series [SERIES_LETTER] price paid by new equity investors.

**Discount Formula:**
```
SAFE Conversion Price = Series A Price × (1 - Discount Rate)
                      = Series A Price × (1 - [DISCOUNT_PERCENTAGE]%)
```

### 3.2 Discount Rate Examples

**Example 1: 20% Discount**
```
Series A Price: $5.00 per share
Discount Rate: 20%
SAFE Conversion Price = $5.00 × (1 - 0.20)
                      = $5.00 × 0.80
                      = $4.00 per share

Investor Benefit:
- Paid less per share than Series A investors
- More shares for same investment amount
- Shares = $200,000 / $4.00 = 50,000 shares
- Series A investor paid: $200,000 / $5.00 = 40,000 shares
- Advantage: 10,000 additional shares
```

**Example 2: 30% Discount**
```
Series A Price: $4.00 per share
Discount Rate: 30%
SAFE Conversion Price = $4.00 × (1 - 0.30)
                      = $4.00 × 0.70
                      = $2.80 per share

Investor Benefit:
- Significantly more shares due to higher discount
- More protection in down rounds
- Shares = $200,000 / $2.80 = 71,429 shares
- Series A investor paid: $200,000 / $4.00 = 50,000 shares
- Advantage: 21,429 additional shares
```

### 3.3 Common Discount Rate Ranges

| Stage | Typical Discount Range | Rationale |
|-------|---|---|
| **Pre-Seed/Seed** | 20-30% | Early risk, uncertainty |
| **Seed to Series A** | 15-25% | Established product, some traction |
| **Series A Bridge** | 10-20% | Lower risk, near-term financing |
| **Series B+ Bridge** | 5-15% | Mature company, lower risk |

---

## 4. CONVERSION MECHANICS: THE VALUATION CAP

### 4.1 Post-Money Valuation Cap Definition

The "**Post-Money Valuation Cap**" is $[POST_MONEY_CAP] USD, representing the maximum fully-diluted valuation of the Company after this SAFE investment is treated as equity.

**Cap Ensures:**
- Investor owns minimum ownership percentage
- Company valuation cannot increase beyond investor's expected stake
- Protects against excessive future valuations

### 4.2 Cap-Based Conversion Formula

When conversion price based on the cap:

```
Conversion Price (via Cap) = Post-Money Cap / Fully-Diluted Shares (including SAFE)

Investor Ownership % = Investment Amount / Post-Money Cap
```

### 4.3 Cap-Based Example

```
Post-Money Cap: $5,000,000
Investment: $200,000
Pre-SAFE Common Shares: 1,000,000
ESOP Reserved: 100,000 shares

Cap-Based Ownership % = $200,000 / $5,000,000 = 4%
Investor Shares = 1,000,000 × 4% = 40,000 shares (approximately)

If Series A raises additional capital:
Post-Money Cap limits the conversion price,
ensuring investor maintains minimum 4% ownership
```

---

## 5. DUAL PROTECTION: WHICH MECHANISM APPLIES?

### 5.1 Conversion Rule: The "Better Conversion" Approach

Investor receives the conversion that results in the MOST SHARES (most favorable to investor):

```
Use DISCOUNT if:
  Discount Conversion Price < Cap-Based Conversion Price
  (Discount results in lower effective price)

Use CAP if:
  Cap-Based Conversion Price < Discount Conversion Price
  (Cap results in lower effective price)

Investor automatically receives whichever is better
```

### 5.2 Detailed Scenario Analysis

**Scenario A: Cap Applies, Discount Doesn't**

```
Setup:
- Post-Money Cap: $5,000,000
- Discount Rate: 20%
- Investment: $200,000
- Series A: $3,000,000 at $3.50/share

Conversion Calculations:
1. Discount-based price = $3.50 × 0.80 = $2.80/share
   Shares via discount = $200,000 / $2.80 = 71,428 shares

2. Cap-based price = $5M / Implied fully-diluted shares
   (Complex calculation, results in $4.00/share effective)
   Shares via cap = $200,000 / $4.00 = 50,000 shares

3. Which is better for investor?
   71,428 shares (discount) > 50,000 shares (cap)
   → Use discount, investor gets 71,428 shares

Investor Benefit: Gets more shares due to aggressive 20% discount
```

**Scenario B: Cap Applies, Discount Creates Problem**

```
Setup:
- Post-Money Cap: $8,000,000
- Discount Rate: 20%
- Investment: $200,000
- Series A: $5,000,000 at $8.00/share (UP ROUND)

Conversion Calculations:
1. Discount-based price = $8.00 × 0.80 = $6.40/share
   Shares via discount = $200,000 / $6.40 = 31,250 shares

2. Cap-based price (due to $8M cap on up round)
   Effective price = ~$5.00/share
   Shares via cap = $200,000 / $5.00 = 40,000 shares

3. Which is better for investor?
   40,000 shares (cap) > 31,250 shares (discount)
   → Use cap, investor gets 40,000 shares

Investor Benefit: Cap protects against the discount being insufficient in large up-round
```

**Scenario C: Down Round - Both Provide Protection**

```
Setup:
- Post-Money Cap: $5,000,000
- Discount Rate: 20%
- Investment: $200,000
- Series A: $1,000,000 at $1.50/share (DOWN ROUND)

Conversion Calculations:
1. Discount-based price = $1.50 × 0.80 = $1.20/share
   Shares via discount = $200,000 / $1.20 = 166,667 shares

2. Cap-based price
   With down round, cap provides less protection
   Effective price might be $1.80/share
   Shares via cap = $200,000 / $1.80 = 111,111 shares

3. Which is better for investor?
   166,667 shares (discount) > 111,111 shares (cap)
   → Use discount, investor gets 166,667 shares

Investor Benefit: Discount helps most in down rounds
```

---

## 6. QUALIFYING EQUITY FINANCING AND CONVERSION TRIGGERS

### 6.1 Definition of Qualifying Equity Financing

A "**Qualifying Equity Financing**" means:

- **Nature:** Bona fide sale of Preferred Stock (Series [SERIES_LETTER] or other)
- **Minimum Proceeds:** Gross proceeds of at least $[MINIMUM_PROCEEDS] USD
- **Timing:** Completed after execution of this Agreement
- **Exclusions:** Does not include SAFEs, convertible notes, debt, warrants, options, or other non-equity instruments

### 6.2 Conversion Timing

Automatic conversion occurs upon the **earlier** of:
- Execution of definitive agreements for Qualifying Equity Financing
- Closing/funding of Qualifying Equity Financing

### 6.3 Anti-Avoidance Clause

[OPTIONAL] Company cannot circumvent this SAFE by:
- Issuing multiple small preferred rounds instead of one round
- Disguising debt as equity
- Using other mechanisms to avoid triggering conversion
- If Company attempts to avoid conversion, SAFE converts at a discount set by [SPECIFY MECHANISM]

---

## 7. CHANGE OF CONTROL AND LIQUIDATION RIGHTS

### 7.1 Definition of Change of Control

Includes:
- Sale of the Company
- Merger or consolidation with another entity
- Sale of substantially all assets (>85% of assets)
- Change in voting control of the board
- Change in shareholder control
- Any transaction where pre-transaction shareholders retain <50% voting control

### 7.2 Investor's Change of Control Payment Options

**Upon Change of Control before conversion:**

**Option A: Cash Return**
```
Investor receives: $[INVESTMENT_AMOUNT]
Payment source: Acquisition proceeds
Status: Unsecured creditor claim
```

**Option B: Equity Participation**
```
If acquisition is for stock in acquirer:
Investor Shares = Investment / [Specified valuation]
Investor owns percentage of acquirer equal to ownership would have been pre-conversion
```

**Option C: Proportional Sale Proceeds**
```
Investor's Share % = $[INVESTMENT_AMOUNT] / Post-Money Cap
                   = [X]%

Investor Receives = Net Sale Proceeds × [X]%
```

**Option D: Most Favorable**
```
Investor receives the option above that provides maximum value
Calculated at closing based on actual transaction terms
```

**[SELECT THE APPLICABLE OPTION(S)]**

### 7.3 Ranking in Change of Control

**Payment Priority:**
1. Debt obligations and creditors
2. Transaction expenses and fees
3. **SAFE Investor** - per selected option above
4. Remaining to equity holders pro-rata

### 7.4 Liquidation (Dissolution/Bankruptcy)

**Upon Company dissolution or bankruptcy before conversion:**

**Investor Receives:**
- [ ] Return of original investment ($[INVESTMENT_AMOUNT])
- [ ] [X]% of liquidation proceeds
- [ ] Pari passu (equal) treatment with common shareholders
- [ ] Other: [SPECIFY]

**Priority:** [SELECT]
- [ ] Senior to common shareholders
- [ ] Pari passu with common shareholders
- [ ] Unsecured creditor status

---

## 8. INVESTOR PROTECTIONS AND RIGHTS

### 8.1 Most Favored Nation (MFN) Clause

If Company issues another SAFE or convertible instrument with BETTER TERMS within [12 months]:

**Better Terms Include:**
- Lower discount rate (e.g., 15% instead of 20%)
- Lower valuation cap
- Both discount AND cap (if previous SAFE had only one)
- Additional investor rights
- Board seat or observation rights
- Stronger liquidation preferences

**Automatic Benefit:**
Investor immediately receives the better terms without renegotiation.

**MFN Notice:**
Company must notify Investor within [10 business days] of issuing a new SAFE/convertible.

### 8.2 Pro-Rata Participation Rights

[OPTIONAL]

Upon conversion into Series [SERIES_LETTER] Preferred Stock, Investor has the right to:
- Participate in all future equity financings
- Purchase pro-rata amount equal to ownership percentage
- Same terms offered to other investors
- Duration: [X years] or until [EVENT]

**Example:**
```
Post-conversion ownership: 4%
Series B raising: $5,000,000
Pro-rata participation right: $5M × 4% = $200,000
Investor can invest additional $200,000 in Series B at same price as other Series B investors
```

### 8.3 Information Rights

Company shall provide Investor:

**Quarterly (within 45 days of quarter end):**
- Unaudited financial statements
- Operating metrics and KPIs
- Material business updates

**Annually (within 120 days of year-end):**
- Audited financial statements (if applicable)
- Updated fully-diluted capitalization table
- Annual budget and business plan

**Ad Hoc:**
- Notice of Change of Control or dissolution (within 10 days)
- Notice of material litigation (within 10 days)
- Notice of any new SAFE/convertible issuance (within 10 days, MFN notice)
- Board minutes and materials (if board observer)

### 8.4 Board Observation Rights

[OPTIONAL]

Investor may observe all board of directors meetings upon [5 business days] advance notice.

**Restrictions:**
- No voting or deliberation rights
- Must maintain confidentiality
- Cannot participate on conflicted matters
- Access to all board materials

---

## 9. INVESTOR REPRESENTATIONS

Investor represents and warrants:

### 9.1 Authority and Capacity
- Investor has full authority to execute this Agreement
- If entity, properly authorized by governing documents and actions
- Investment is within Investor's authorized powers

### 9.2 Accredited Investor Status

[IF APPLICABLE - SELECT]
- [ ] Individual investor with income > $200k (or $300k joint) in last 2 years
- [ ] Individual with net worth > $1M (excluding primary residence)
- [ ] Institutional investor with assets > $5M
- [ ] Other: [SPECIFY IF NOT REQUIRED TO BE ACCREDITED]

### 9.3 Investment Sophistication and Risk Acknowledgment
- Investor has experience evaluating early-stage investments
- Investor understands and accepts the high-risk nature of this investment
- Investor can afford to lose entire investment amount
- Investor has conducted independent due diligence
- Investor is not relying solely on Company representations

### 9.4 No Public Trading
- Investor understands securities are not registered under Securities Act
- Securities may not be transferable without registration or exemption
- Investor intends to hold for extended period
- No liquid market exists for these securities

---

## 10. COMPANY REPRESENTATIONS

Company represents and warrants:

### 10.1 Organization and Authority
- Company is validly organized and in good standing
- Company has full authority to execute this Agreement
- Board has authorized this investment

### 10.2 Capitalization
- Capitalization table is accurate and complete
- All issued shares, SAFEs, options, warrants, and contingent securities are disclosed
- No omitted securities or obligations

### 10.3 No Conflicts
- This Agreement does not violate any other agreements
- No conflicting debt covenants or shareholder agreements
- Execution does not violate laws or regulations
- No liens or claims against the Company except as disclosed

### 10.4 Financial Accuracy
- All financial statements provided are accurate
- Fairly represent financial condition as of date
- No material undisclosed liabilities
- No material misrepresentations

---

## 11. TERMS AND CONDITIONS

### 11.1 Not a Debt Instrument
- This SAFE is NOT a debt
- Company has NO obligation to pay interest or principal
- No debtor-creditor relationship
- Investor is equity holder (upon conversion)

### 11.2 No Voting Rights (Pre-Conversion)
Until conversion into Preferred Stock:
- Investor has NO voting rights
- Investor has NO shareholder governance rights
- Investor has NO consent or veto rights
- Company controls all business decisions

Upon conversion, Investor receives voting rights equivalent to other Series [SERIES_LETTER] Preferred Stock.

### 11.3 No Board Seat
Investor is not entitled to a board seat unless:
- Board observation rights are included above
- Investor subsequently negotiates board seat in later round
- Board seat is otherwise provided by law or agreement

### 11.4 Transfer Restrictions

Investor may not transfer, sell, pledge, or assign this SAFE without Company written consent, except to:
- Immediate family members
- Family trusts or partnerships
- Qualified retirement accounts (IRA, 401k, etc.)
- Affiliated investment funds (if Investor is VC fund)

[OPTIONAL: Company has right to repurchase at [TERMS] if unauthorized transfer attempted]

---

## 12. TERM AND EXPIRATION

### 12.1 Duration Until Conversion
This SAFE remains in effect and convertible until earliest of:
- Conversion into Preferred Stock upon Qualifying Equity Financing
- Change of Control event
- Dissolution or liquidation of Company
- [OPTIONAL: [DATE] - specific expiration date]

### 12.2 Expiration Without Conversion
If not converted by [EXPIRATION_DATE], Investor's rights are:
- [ ] Return of investment amount with [X]% interest
- [ ] Automatic conversion to [X]% of Common Stock
- [ ] SAFE continues perpetually
- [ ] Other: [SPECIFY]

---

## 13. GOVERNING LAW AND DISPUTE RESOLUTION

### 13.1 Governing Law
Governed by laws of [STATE_OF_INCORPORATION], without regard to conflicts of law.

### 13.2 Exclusive Jurisdiction
Exclusive jurisdiction in [COUNTY], [STATE] courts. Both parties submit to jurisdiction.

### 13.3 Waiver of Jury Trial
[OPTIONAL] Each party waives right to jury trial.

### 13.4 Entire Agreement
This Agreement and exhibits constitute entire agreement. Supersedes all prior discussions and agreements.

### 13.5 Amendments
Only valid amendments are in writing, signed by both parties.

### 13.6 Severability
If any provision is invalid, it shall be reformed to minimum extent necessary. All other provisions remain in effect.

---

## 14. SIGNATURE BLOCKS

### INVESTOR
```
Investor Name/Entity: ___________________________________

Signature: _____________________________________________

Print Name: ____________________________________________

Title (if entity): _____________________________________

Date: __________________________________________________

Address: ________________________________________________

        ________________________________________________

Phone: __________________________________________________

Email: __________________________________________________
```

### COMPANY
```
Company Name: [COMPANY_NAME]
             a [STATE] corporation

By: _____________________________________________________

Title: __________________________________________________

Date: __________________________________________________

Address: ________________________________________________

        ________________________________________________

Phone: __________________________________________________

Email: __________________________________________________

Board Secretary Certification:

I certify that the Board of Directors has authorized this SAFE
and this Agreement does not violate any Company agreement.

Signature: ___________________________________________

Title: ________________________________________________

Date: _________________________________________________
```

---

## 15. EXHIBITS

**Exhibit A - Capitalization Table**
All issued shares, SAFEs, convertible instruments, options, warrants, contingent securities

**Exhibit B - Articles of Incorporation and Bylaws**
Current governing documents

**Exhibit C - Financial Statements**
Most recent financial statements (if applicable)

**Exhibit D - Business Summary**
One-page description of Company, market, use of proceeds

---

## INVESTOR GUIDE: DISCOUNT VS. CAP

### Understanding the Discount Rate

**What Does 20% Discount Mean?**
```
Example:
- Another investor buys shares at $5.00
- You buy shares at $5.00 × (1 - 0.20) = $4.00
- You get same shares as $5 investor, but for less money
- Or: same money gets you more shares
```

**Why Discount Exists:**
- Rewards early risk-taking
- Standard practice across SAFE ecosystem
- Typical range: 15-30% depending on stage

### Understanding the Valuation Cap

**What Does $5M Cap Mean?**
```
Example:
- Your investment: $200,000
- Post-money cap: $5,000,000
- Your ownership: $200k / $5M = 4%
- Series A must price such that you own at least 4%
```

**Why Cap Exists:**
- Protects against excessive future valuations
- Ensures minimum investor ownership
- Especially important if discount is insufficient

### Discount + Cap: The Perfect Combination

| Scenario | Discount Helps | Cap Helps |
|----------|---|---|
| **Small up-round** | ✓ Yes | ✗ No |
| **Large up-round** | ✗ No | ✓ Yes |
| **Down round** | ✓ Yes | ~ Minor |

**Dual protection means: Investor always gets the best outcome**

---

**Document Version:** 1.0
**Last Updated:** November 2025
**Template Type:** Discount Rate + Valuation Cap SAFE
