# SIMPLE AGREEMENT FOR FUTURE EQUITY (SAFE)
## Pre-Money Variant with Valuation Cap

**IMPORTANT NOTICE:** This document is provided as a template for informational purposes only. Consult with qualified legal counsel before execution.

---

## 1. KEY TERMS SUMMARY

| Field | Value |
|-------|-------|
| **Agreement Type** | SAFE with Pre-Money Valuation Cap |
| **Investment Amount** | $[INVESTMENT_AMOUNT] USD |
| **Pre-Money Valuation Cap** | $[PRE_MONEY_CAP] USD |
| **Post-Money Implied Value** | ~$[PRE_MONEY_CAP + INVESTMENT_AMOUNT] USD |
| **Investor Expected Ownership** | ~[X]% of post-conversion capitalization |

---

## 2. INVESTMENT TERMS

### 2.1 Pre-Money Valuation Cap Definition

The "**Pre-Money Valuation Cap**" is $[PRE_MONEY_CAP] USD, representing the Company's valuation **before** this SAFE investment is added.

**Mathematical Relationship:**
```
Post-Money Valuation = Pre-Money Cap + SAFE Investment Amount
$[PRE_MONEY_CAP + INVESTMENT_AMOUNT] = $[PRE_MONEY_CAP] + $[INVESTMENT_AMOUNT]
```

### 2.2 Why Pre-Money Cap?

**Use Pre-Money When:**
- Comparing to convertible notes with pre-money caps
- Early-stage company valuations are higher
- Investor wants slightly more favorable terms
- Historical precedent in your funding rounds

**Example Situation:**
```
Company is raising from multiple sources:
- Two SAFEs with pre-money caps
- One convertible note with pre-money cap
- Need consistent valuation measurement across instruments
```

### 2.3 SAFE Investment
Investor invests $[INVESTMENT_AMOUNT] USD. This amount is:
- **Not a debt:** No repayment or interest obligation
- **Equity commitment:** Converts to equity in future round
- **Fully creditable:** Applied toward equity purchase price

---

## 3. CONVERSION MECHANICS

### 3.1 Qualifying Equity Financing Trigger
This SAFE converts automatically upon a "**Qualifying Equity Financing**," defined as:

A bona fide sale of Series [SERIES_LETTER] (or other) Preferred Stock resulting in gross proceeds of at least $[MINIMUM_PROCEEDS] USD, occurring after this Agreement's effective date.

**Key Triggers:**
1. **Definitive Agreements Execution** OR **Closing** - Whichever occurs first
2. Must be a genuine equity round (not ESOP or other non-equity capital raise)
3. Gross proceeds threshold must be met

### 3.2 Pre-Money Conversion Formula

**Critical Formula:**
```
SAFE Ownership % = Investment Amount / (Pre-Money Cap + Investment Amount)

Investor Shares = Fully-Diluted Pre-SAFE Shares × SAFE Ownership %

Conversion Price = Investment Amount / Investor Shares
                 = (Pre-Money Cap + Investment Amount) / Fully-Diluted Shares
```

### 3.3 Detailed Conversion Example

**Scenario Setup:**
```
Pre-Money Cap: $5,000,000
SAFE Investment: $200,000
Pre-SAFE Outstanding Shares: 1,000,000 shares
Employee Option Pool: 100,000 shares (reserved)
Fully-Diluted Shares (pre-SAFE): 1,100,000 shares

Series A Details:
- Investor purchases at: $3.50 per share
- Series A Investment: $3,500,000
- Series A Shares: $3.5M / $3.50 = 1,000,000 shares
```

**Conversion Calculation:**
```
Step 1: Calculate SAFE ownership percentage
SAFE % = $200,000 / ($5,000,000 + $200,000)
       = $200,000 / $5,200,000
       = 3.846%

Step 2: Apply percentage to pre-SAFE fully-diluted shares
SAFE Shares = 1,100,000 × 3.846%
            = 42,306 shares

Step 3: Determine effective conversion price
Conversion Price = $200,000 / 42,306 shares
                 = $4.73 per share

Alternatively:
Conversion Price = Post-Money Cap / Post-Financing Fully-Diluted Shares
Post-Money Cap = $5,000,000 + $200,000 = $5,200,000
Fully-Diluted Shares = 1,100,000 + 1,000,000 = 2,100,000
Conversion Price = $5,200,000 / 2,100,000 = $2.48 per share
```

**Key Insight:** Investor's effective cost basis depends on both the cap AND the Series A terms.

### 3.4 When Pre-Money Cap Protects Investors

**Scenario: Up Round (Company Valuation Increases)**

```
Situation: Series A priced at higher valuation than cap

Series A Pricing:
- Series A Price: $5.00 per share
- Implied Post-Money: $5M + Company's existing value = $7M+

Effect of Pre-Money Cap:
- SAFE owns 3.846% of fully-diluted shares
- Even though Series A price is $5.00, SAFE converts at lower effective price
- SAFE investor protected from dilution
```

---

## 4. CONVERSION PRICE COMPARISON TABLE

| Market Condition | Series A Price | SAFE Effective Price | Investor Benefit |
|---|---|---|---|
| **Up Round** | $5.00/share | $2.48/share | Cap protects, lower conversion |
| **Flat Round** | $4.76/share | $2.27/share | Cap applies fully |
| **Down Round** | $2.00/share | $0.95/share | Gets more shares at low price |

---

## 5. CHANGE OF CONTROL AND LIQUIDATION EVENTS

### 5.1 Change of Control Definition
A "**Change of Control**" means:
- Sale of the entire Company
- Merger or consolidation with another entity
- Sale of substantially all assets (>85%)
- Change in voting control of the board
- Change in ownership control by shareholders
- Any transaction where pre-transaction shareholders have <50% of post-transaction voting control

### 5.2 Investor's Rights in Change of Control
If Change of Control occurs before conversion into Preferred Stock:

**Investor Receives (Choose One):**

**Option A: Cash Return**
- Original investment amount: $[INVESTMENT_AMOUNT]
- Paid from acquisition proceeds
- Investor treated as unsecured creditor

**Option B: Equity in Acquirer**
- If acquisition is by share exchange, investor receives shares in acquirer
- Valuation based on acquisition terms and SAFE ownership %

**Option C: Proportional Proceeds**
- Investor receives percentage of net sale proceeds equal to:
  ```
  % = $[INVESTMENT_AMOUNT] / $[PRE_MONEY_CAP + INVESTMENT_AMOUNT]
  ```

**Option D: Most Favorable**
- Investor receives whichever option provides greatest value
- Determined based on actual transaction terms and cash available

### 5.3 Liquidation Waterfall (Dissolution/Bankruptcy)

**Payment Priority:**
1. Secured creditors and debt obligations
2. Operational expenses and wind-down costs
3. **SAFE Investor:** Return of $[INVESTMENT_AMOUNT] [OR as specified]
4. Remaining to common shareholders

**Status:** [SELECT]
- [ ] Pari passu (equal) with common shareholders
- [ ] Superior to common shareholders
- [ ] Unsecured creditor status

---

## 6. INVESTOR PROTECTIONS & RIGHTS

### 6.1 Most Favored Nation (MFN) Clause

**If the Company issues another SAFE or convertible with MORE FAVORABLE terms within [12 months]:**

Investor automatically receives the benefit of the better terms.

**Covered by MFN:**
- Lower pre-money or post-money cap
- Lower discount rate
- Additional investor rights
- Board seat rights
- Stronger liquidation preferences
- Anti-dilution protection

**NOT Covered by MFN:**
- Different valuation caps (purely negotiated items)
- Investor-specific customizations
- Terms reflecting different investment amounts

**MFN Process:**
1. Company issues SAFE to new investor with more favorable terms
2. Company notifies existing SAFE holders within 10 business days
3. Existing investors automatically receive amended terms
4. No additional negotiation required

### 6.2 Pro-Rata Participation Rights

[OPTIONAL - INCLUDE IF NEGOTIATED]

**Right of Participation:**
Upon conversion into Series [SERIES_LETTER] Preferred Stock, Investor shall have the right to purchase its pro-rata share of all future equity securities offerings, on the same terms offered to other investors.

**Pro-Rata Calculation:**
```
Investor's Pro-Rata % = Investor's Post-Conversion % of fully-diluted shares
```

**Term:** This right continues for [X years] or until [SPECIFY EVENT].

### 6.3 Information and Reporting Rights

Company shall provide Investor with:

**Quarterly:**
- Unaudited financial statements within 45 days of quarter close
- Operating metrics and key performance indicators
- Material business updates

**Annually:**
- Audited financial statements (if required) within 120 days of year end
- Updated capitalization table
- Annual business plan and budget for upcoming year
- Board resolutions on material matters

**Ad Hoc:**
- Notice of any Change of Control or dissolution events within 10 days
- Notice of any material litigation or regulatory matters
- Notice of any issuance of SAFEs or convertible instruments (including MFN notice)

### 6.4 Board Observation Rights

[OPTIONAL]
Investor shall have the right to observe all meetings of the Company's board of directors upon [5 days] advance notice. Board observer shall:
- Have access to all board materials
- Maintain confidentiality of proprietary information
- Not participate in voting or deliberations on conflicted matters

---

## 7. INVESTOR REPRESENTATIONS AND WARRANTIES

Investor represents:

### 7.1 Authority
Investor has full power and authority to enter into this Agreement.

### 7.2 Accredited Investor Status
[INCLUDE IF APPLICABLE]
Investor qualifies as an "accredited investor" under Regulation D Rule 501:
- Individual income > $200,000 (or $300,000 joint) in last 2 years, or
- Individual net worth > $1,000,000 (excluding primary residence), or
- Entity with assets > $5,000,000

Investor acknowledges the high-risk nature of private equity investments.

### 7.3 Investment Experience
Investor has experience evaluating and investing in early-stage companies and understands the significant risks involved.

### 7.4 Due Diligence
Investor has conducted independent investigation of the Company and is not relying solely on Company representations.

### 7.5 No Registration
Investor understands that securities received upon conversion are not registered under securities laws and may not be freely transferable.

---

## 8. COMPANY REPRESENTATIONS AND WARRANTIES

### 8.1 Organization and Authority
Company is validly organized, in good standing, and authorized to enter into this Agreement.

### 8.2 Accurate Capitalization
Company's capitalization table is accurate, complete, and includes:
- All issued shares
- All SAFEs, convertible notes, and warrants
- All reserved shares (option pools, etc.)
- All contingent obligations

### 8.3 No Conflicts
Execution and performance of this Agreement does not violate:
- Company's certificate of incorporation or bylaws
- Any loan agreements or financing arrangements
- Any other contracts or legal obligations
- Any laws or regulations

### 8.4 Material Accuracy
All financial information provided to Investor is accurate and fairly represents the Company's financial condition.

---

## 9. INVESTOR RIGHTS AND COMPANY RESTRICTIONS

### 9.1 No Voting Rights Pre-Conversion
Until conversion, Investor has:
- **No voting rights** in shareholder meetings
- **No governance participation**
- **No consent rights** to Company actions
- **No ability to remove directors**

### 9.2 No Board Seat
Investor is not entitled to a board seat unless separately negotiated or earned through subsequent investment.

### 9.3 Transfer Restrictions
Investor shall not transfer or assign this SAFE without Company consent, except to:
- Immediate family members
- Family trusts or partnerships
- Qualified retirement accounts (IRA, 401k, etc.)
- Charitable organizations

**Company Right to Repurchase:** [OPTIONAL]
If Investor transfers without approval, Company may repurchase the SAFE at [SPECIFY TERMS: original cost + interest, fair market value, etc.].

---

## 10. STANDARD PROVISIONS

### 10.1 Term and Conversion
This SAFE remains in effect until earliest of:
- Conversion into Preferred Stock
- Change of Control
- Dissolution/liquidation
- [OPTIONAL: Specified expiration date: [DATE]]

### 10.2 Amendments and Modifications
No amendment is valid unless in writing, signed by both Company and Investor.

### 10.3 Governing Law
Governed by laws of [STATE_OF_INCORPORATION], without conflicts of law principles.

### 10.4 Dispute Resolution
- **Venue:** [COUNTY], [STATE] courts (exclusive jurisdiction)
- **Waiver of Jury Trial:** [OPTIONAL] Each party waives right to jury trial

### 10.5 Entire Agreement
This Agreement, plus all exhibits and schedules, constitutes the entire agreement and supersedes all prior negotiations and understandings.

### 10.6 Severability
If any provision is invalid, it shall be reformed to minimum extent necessary, and all other provisions remain in full effect.

### 10.7 Notice Requirements
All required notices must be in writing and delivered by:
- Personal delivery
- Overnight courier (FedEx, UPS, etc.)
- Certified mail with return receipt
- Email with read receipt

To addresses specified in signature blocks.

---

## 11. COMPARISON: PRE-MONEY VS. POST-MONEY CAPS

| Aspect | Pre-Money Cap | Post-Money Cap |
|--------|---|---|
| **Definition** | Valuation BEFORE SAFE added | Valuation AFTER SAFE added |
| **Investor Ownership Formula** | Amount / (Cap + Amount) | Amount / Cap |
| **Ownership Clarity** | Less intuitive | More intuitive |
| **When Favorable** | When company valuation is higher | When company valuation is lower |
| **Common Use** | Convertible notes, earlier SAFEs | Standard SAFEs (now common) |
| **Math Complexity** | Slightly more complex | Simpler calculation |
| **Investor Benefit** | Slightly more favorable | Slightly less favorable |

### Example Comparison

```
SAME INVESTMENT, DIFFERENT CAP TYPES:

Scenario:
- Investment Amount: $200,000
- Company's Existing Value (estimated): $4,800,000

Pre-Money Cap Approach:
- Cap: $4,800,000 (pre-money)
- Post-Money: $5,000,000
- Investor %: $200,000 / $5,000,000 = 4%

Post-Money Cap Approach:
- Cap: $5,000,000 (post-money)
- Pre-Money: $4,800,000
- Investor %: $200,000 / $5,000,000 = 4%

Result: SAME OWNERSHIP%
(The math works out to demonstrate why both exist - investor preference varies)
```

---

## 12. SIGNATURE BLOCKS

### INVESTOR

```
Investor Name/Entity: _________________________________

Signature: ____________________________________________

Print Name: __________________________________________

Title (if entity): ____________________________________

Date: ________________________________________________

Address: ______________________________________________

         ______________________________________________

Phone: ________________________________________________

Email: ________________________________________________
```

### COMPANY

```
Company Name: [COMPANY_NAME]
             a [STATE] corporation

By: ____________________________________________________

Title: __________________________________________________

Date: __________________________________________________

Address: ________________________________________________

        ________________________________________________

Phone: __________________________________________________

Email: __________________________________________________

Secretary/CFO Acknowledgment:

I certify that this SAFE has been duly authorized by the Board of Directors
and does not violate any agreements to which the Company is party.

Signature: ___________________________________________

Title: ________________________________________________

Date: _________________________________________________
```

---

## 13. EXHIBITS

**Exhibit A - Capitalization Table**
[Current cap table with all shares, SAFEs, options, warrants, etc.]

**Exhibit B - Company Formation Documents**
[Certificate of Incorporation, Bylaws, Board Resolutions]

**Exhibit C - Financial Statements**
[Most recent financial statements (if applicable)]

**Exhibit D - Business Summary**
[One-page description of Company's business, market, and use of proceeds]

---

## 14. PRE-MONEY VS. POST-MONEY: INVESTOR DECISION GUIDE

### Choose **Pre-Money Cap** If:
- Company has completed multiple prior capital raises
- You want consistency with convertible notes
- You believe company valuation will rise significantly
- You have negotiation leverage
- You want slightly more favorable dilution protection

### Choose **Post-Money Cap** If:
- Simpler to understand and explain
- You prefer clarity on ownership percentage
- This is Company's first round
- You want standard market terms
- You prefer not to negotiate valuation methodology

### Ask Yourself:
1. Do I understand how each converts?
2. Which is more favorable given my conviction on company valuation?
3. What cap type do other investors in this round expect?
4. Have prior SAFEs used a specific cap type?

---

**Document Version:** 1.0
**Last Updated:** November 2025
**Template Type:** Pre-Money Valuation Cap SAFE
