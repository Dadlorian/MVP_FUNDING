# SIMPLE AGREEMENT FOR FUTURE EQUITY (SAFE)
## Post-Money Variant with Valuation Cap

**IMPORTANT NOTICE:** This document is provided as a template for informational purposes only. It should not be used as legal advice. Consult with qualified legal counsel in your jurisdiction before executing any investment agreement.

---

## 1. INSTRUMENT DETAILS

| Field | Value |
|-------|-------|
| **Agreement Type** | SAFE with Post-Money Valuation Cap |
| **Date of Investment** | [INVESTMENT_DATE] |
| **Parties** | [INVESTOR_NAME/ENTITY] and [COMPANY_NAME] |
| **Purchase Amount** | $[INVESTMENT_AMOUNT] USD |
| **Post-Money Valuation Cap** | $[VALUATION_CAP] USD |
| **Investor MFN Status** | [YES/NO] |

---

## 2. KEY TERMS

### 2.1 Post-Money Valuation Cap
**Definition:** The "**Post-Money Valuation Cap**" is $[VALUATION_CAP] USD, which represents the fully-diluted valuation of the Company immediately after this SAFE investment is treated as equity.

**Why Post-Money is Critical:**
- Post-money = Pre-money valuation + SAFE investment amount
- Determines investor's conversion ratio in the next round
- Lower cap = better protection for early investors
- Typical range for SAFEs: $2M-$10M for seed stage

### 2.2 SAFE Investment Amount
Investor shall invest $[INVESTMENT_AMOUNT] USD in the Company, credited toward future equity ownership upon conversion.

### 2.3 Company Information
- **Entity:** [COMPANY_NAME], a [STATE] corporation
- **Principal Business:** [BUSINESS_DESCRIPTION]
- **Registered Address:** [ADDRESS]

---

## 3. CONVERSION MECHANICS WITH POST-MONEY CAP

### 3.1 Automatic Conversion on Qualifying Equity Financing
This SAFE automatically converts into [NUMBER_OF_SHARES OR SPECIFY METHOD] of Series [SERIES_LETTER] Preferred Stock (or equivalent) when the Company conducts a "**Qualifying Equity Financing**."

**Qualifying Equity Financing Definition:**
A bona fide sale of Series [SERIES_LETTER] or other Preferred Stock of the Company resulting in gross proceeds of not less than $[MINIMUM_PROCEEDS] (e.g., $500,000-$1,000,000), conducted after the date of this Agreement.

### 3.2 Conversion Price Calculation (Post-Money)
The conversion price shall be determined by dividing the **Post-Money Valuation Cap** by the **Fully-Diluted Capitalization** immediately after the SAFE conversion.

**Formula:**
```
Conversion Price = Post-Money Valuation Cap / Fully-Diluted Shares (including SAFE)

Investor Shares = Investment Amount / Conversion Price
```

**Step-by-Step Example:**
```
Scenario:
- Post-Money Valuation Cap: $5,000,000
- SAFE Investment: $200,000
- Pre-SAFE common shares outstanding: 1,000,000
- Series A price (before cap application): $5 per share
- Minimum proceeds required: $500,000 (not triggered)

Calculation:
1. Post-money cap = $5,000,000
2. Pre-SAFE shares = 1,000,000
3. If no cap applied, post-financing shares = $5M / $5/share = 1,000,000
4. But cap applies, so:
   Conversion Price = $5M / (1M existing + new SAFE shares)

   If Series A is $3M:
   - Series A shares at Series A price = $3M / $5 = 600,000 shares
   - Post-money immediately after SAFE = $5M valuation
   - Total post-money shares = $5M / Conversion Price

   Let x = total shares including SAFE
   Conversion Price = $5,000,000 / x

   SAFE shares = $200,000 / ($5,000,000 / x) = $200,000 × x / $5,000,000
   Total shares = 1,000,000 + Series A shares + SAFE shares

   (Simplified: SAFE holder receives ~4% of post-financing capitalization)
```

### 3.3 Comparison: Post-Money Cap vs. Series A Price

| Scenario | Description | Investor Benefit |
|----------|-------------|------------------|
| **Cap Applies** | Post-Money Cap ($5M) < Implied Post-Money ($7M) | Uses lower cap, more shares |
| **Cap Doesn't Apply** | Post-Money Cap ($5M) > Implied Post-Money ($3M) | Uses actual Series A price |
| **Exact Match** | Cap equals implied post-money | Converts at actual terms |

### 3.4 Investor's Ownership Percentage
Upon conversion, Investor will own:

```
Investor % = Investment Amount / Post-Money Valuation Cap
          = $[INVESTMENT_AMOUNT] / $[VALUATION_CAP]
          = [X]%
```

This is the **maximum** ownership percentage (before pro-rata dilution in the Series A).

---

## 4. DETAILED CONVERSION SCENARIOS

### 4.1 Scenario A: Cap Protects Investor (Up Round)

**Situation:** Company raises Series A at higher valuation than the cap.

```
Pre-SAFE Conditions:
- Common shares outstanding: 1,000,000
- Post-Money Cap: $5,000,000
- SAFE Investment: $200,000

Series A Financing:
- Round Size: $3,000,000
- Series A Price: $5.00 per share
- Implied Post-Money: $3M + $5M existing = $8M

Conversion Calculation:
1. Post-money cap ($5M) < Implied post-money ($8M) → Cap applies
2. Conversion Price = $5,000,000 / (1,000,000 + x SAFE shares)
3. SAFE represents $200,000 / $5M = 4% of post-cap valuation
4. Post-cap shares = $5M / Conversion Price

   Solving for Conversion Price:
   Post-money = $5M = Pre-SAFE shares + Series A shares + SAFE shares
   $5M = 1M + ($3M / Series A price) + (200k / Conv Price)

   Simplified: SAFE holder gets ~4% ownership
   Conversion Price ≈ $3.85 (better than $5.00 Series A price)
   SAFE Shares = $200,000 / $3.85 ≈ 51,948 shares
   Investor Ownership = 51,948 / Total shares ≈ 4.0%
```

**Investor Benefit:** Gets more shares at lower price, caps upside dilution

### 4.2 Scenario B: Cap Doesn't Apply (Down Round)

**Situation:** Company raises Series A at lower valuation than the cap.

```
Series A Financing:
- Round Size: $500,000
- Series A Price: $1.50 per share
- Implied Post-Money: $500K + $1.5M existing = $2M (example, simplified)

Conversion Calculation:
1. Implied post-money ($2M) < Post-money cap ($5M) → Cap doesn't apply
2. Investor converts at Series A Price: $1.50 per share
3. SAFE Shares = $200,000 / $1.50 = 133,333 shares
4. Investor Ownership = 133,333 / Total shares ≈ 8.2%

Result: Investor still gets significant ownership at down round
```

**Investor Benefit:** Converts at the actual Series A price, better terms than cap

---

## 5. LIQUIDATION AND CHANGE OF CONTROL

### 5.1 Liquidation Preference
In the event of a Dissolution Event (dissolution, liquidation, or winding up) before conversion into Preferred Stock, Investor shall receive:

**Payment Order:**
1. All debt and preferred creditor claims
2. Return of SAFE investment ($[INVESTMENT_AMOUNT]) to Investor
3. Remainder distributed to common shareholders per their pro-rata ownership

**Priority Status:** [SELECT]
- [ ] **Pari Passu with Common:** Same priority as common shareholders
- [ ] **Senior to Common:** Preferred before common shareholders receive anything
- [ ] **Unsecured Creditor Status:** Below all creditors but before common equity

### 5.2 Change of Control
If a Change of Control occurs before conversion:

**Definition of Change of Control:**
- Sale of the Company
- Merger or consolidation with another entity
- Sale of substantially all assets (>90%)
- Change in board control
- Change in voting control (shareholders holding <50% of pre-transaction voting control)

**Investor Payment Options (Select One):**

**Option A: Return of Investment**
Investor receives $[INVESTMENT_AMOUNT] back in cash.

**Option B: Equity Participation**
Investor receives common equity representing:
```
Equity % = $[INVESTMENT_AMOUNT] / $[VALUATION_CAP]
```

**Option C: Proportional Sale Proceeds**
Investor receives [X]% of net sale proceeds based on post-money valuation cap.

**Option D: Most Favorable Treatment**
Investor receives whichever of the above is most favorable based on actual transaction terms.

---

## 6. INVESTOR PROTECTIONS

### 6.1 Most Favored Nation (MFN) Clause
If, within [12 months] of this SAFE, the Company issues another SAFE or convertible instrument with **materially better terms**, Investor automatically receives the benefit of such better terms, including:

- Lower post-money valuation cap
- Lower discount rate
- Additional investor rights
- Stronger liquidation preferences

**MFN Notice Requirement:** Company shall notify Investor within [10 business days] of issuing any subsequent SAFE or convertible instrument.

### 6.2 Pro-Rata Participation Rights
[OPTIONAL] Upon conversion, Investor shall have the right to participate pro-rata (based on ownership percentage) in all future equity rounds, on the same terms offered to other investors, for [X years] or until [SPECIFY CONDITION].

### 6.3 Information and Inspection Rights
The Company shall provide Investor with:
- **Quarterly Reports:** Within 45 days of quarter end
- **Annual Audited Financials:** Within 120 days of year end
- **Annual Budget:** Within 30 days of fiscal year end
- **Material Event Notice:** Within 10 days of material business changes
- **Board Observer Rights:** [IF APPLICABLE] Right to observe board meetings

### 6.4 Anti-Dilution Protection
[OPTIONAL - SELECT ONE]
- [ ] **No Anti-Dilution:** Standard SAFE, conversion price fixed at Series A
- [ ] **Broad-Based Weighted Average:** Adjusts conversion price in down rounds
- [ ] **Narrow-Based Weighted Average:** More investor-favorable version
- [ ] **Full Ratchet:** Converts at lowest price issued, most favorable to investor

**Formula (Broad-Based Weighted Average):**
```
New Conversion Price = (A × B + I) / (B + C)

Where:
A = Previous conversion price
B = Pre-down-round fully-diluted shares
C = New shares issued in down round
I = Proceeds from down round
```

---

## 7. INVESTOR REPRESENTATIONS

Investor represents and warrants:

### 7.1 Authority
Investor has full authority to execute this Agreement and is authorized to invest the specified amount.

### 7.2 Accredited Investor Status
[IF APPLICABLE] Investor is an "accredited investor" as defined under Regulation D Rule 501 of the Securities Act of 1933. Investor has income or net worth exceeding the minimum thresholds and understands the risks of private equity investment.

### 7.3 Investment Purpose and Risk Tolerance
- Investor is acquiring this SAFE for investment purposes
- Investor can afford to lose the entire investment amount
- Investor has conducted independent due diligence
- Investor understands no liquid market exists for these securities
- Investor intends to hold for an extended period

### 7.4 No Reliance on Registration
Investor understands that the securities into which this SAFE converts have not been registered under the Securities Act of 1933 and may not be transferable without registration or exemption.

---

## 8. COMPANY REPRESENTATIONS

The Company represents and warrants:

### 8.1 Organization
The Company is validly organized and in good standing under the laws of [STATE_OF_INCORPORATION].

### 8.2 Capitalization and Conflicts
- The Company's capitalization table is accurate and complete
- No conflicts exist that would prevent this investment
- The Company has authorized all share classes necessary for this Agreement

### 8.3 Compliance
The Company operates in material compliance with all applicable laws and regulations.

### 8.4 Financial Accuracy
All financial statements provided are accurate as of their date and fairly represent the Company's financial condition.

---

## 9. TERMS AND CONDITIONS

### 9.1 No Debt Characteristics
- This SAFE is **not** a debt instrument
- The Company has **no obligation** to pay interest or principal
- This Agreement does not create a debtor-creditor relationship

### 9.2 No Voting Rights (Pre-Conversion)
Prior to conversion, Investor has:
- **No voting rights** in Company matters
- **No governance rights** or board seats
- **No veto rights** over Company decisions

Upon conversion, Investor receives voting rights equivalent to other Series [SERIES_LETTER] Preferred Stock holders.

### 9.3 No Transferability Restriction (Optional)
Investor may not transfer this SAFE without Company consent, except to:
- Family members or family trusts
- Qualified retirement accounts
- Charitable organizations

[SELECT: Modify if Company permits free transferability]

### 9.4 Term and Duration
This SAFE shall remain in effect until the earliest of:
- Conversion into Preferred Stock
- Change of Control event
- Dissolution of the Company
- [OPTIONAL: Expiration date of [X years], at which point SAFE converts to Common Stock or is repaid]

---

## 10. AMENDMENT AND GOVERNING LAW

### 10.1 Amendments
No amendment to this Agreement is valid unless in writing, signed by both parties.

### 10.2 Governing Law
This Agreement shall be governed by the laws of [STATE], without regard to conflicts of law principles.

### 10.3 Jurisdiction
Both parties submit to the exclusive jurisdiction of the courts in [COUNTY], [STATE].

### 10.4 Entire Agreement
This Agreement, including all exhibits, constitutes the entire agreement regarding this investment and supersedes all prior discussions and understandings.

### 10.5 Severability
If any provision is found invalid, it shall be reformed to the minimum extent necessary, and all other provisions remain in full force.

---

## 11. SIGNATURE BLOCKS

### INVESTOR
```
Name/Entity: _________________________________________________

Signature: ____________________________________________________

Date: _________________________________________________________

Email: ________________________________________________________
```

### COMPANY
```
[COMPANY_NAME]
a [STATE] corporation

By: ___________________________________________________________

Title: _________________________________________________________

Date: _________________________________________________________

Email: ________________________________________________________
```

---

## 12. EXHIBITS

**Exhibit A:** Company Capitalization Table
**Exhibit B:** Company Certificate of Incorporation and Bylaws
**Exhibit C:** Financial Statements (if applicable)
**Exhibit D:** Business Plan Summary

---

## POST-MONEY VALUATION CAP EXPLAINED FOR INVESTORS

### Why Choose Post-Money?

**Advantages:**
- **Clear Ownership Math:** You know exactly what percentage you'll own post-conversion
- **Investor Friendly:** Most investors prefer post-money for simplicity
- **Standardized:** Industry standard for SAFEs (vs. pre-money)
- **Easier Comparison:** Compare multiple SAFEs and rounds easily

**Example:**
```
Post-Money Cap: $5M
Your Investment: $250,000
Your Ownership: 5% (simple calculation)
```

### Key Distinction: Post-Money vs. Pre-Money

| Aspect | Post-Money Cap | Pre-Money Cap |
|--------|---|---|
| **Definition** | Valuation after SAFE added | Valuation before SAFE |
| **Investor Ownership** | Clear: Investment / Cap | Less intuitive |
| **Calculation** | Easier to understand | Requires more math |
| **Investor Perspective** | Slightly less favorable | Slightly more favorable |
| **Market Standard** | Most common for SAFEs | Common for convertible notes |

---

**Document Version:** 1.0
**Last Updated:** November 2025
**Template Type:** Post-Money Valuation Cap SAFE
