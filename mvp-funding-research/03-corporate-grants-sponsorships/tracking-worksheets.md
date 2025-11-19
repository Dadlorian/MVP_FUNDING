# Corporate Partnership Tracking & Worksheets

Templates, spreadsheet structures, and systems for managing corporate partnership pipelines.

---

## Table of Contents
1. Corporate Target Identification Worksheet
2. Corporate Partnership Pipeline Tracker
3. Proposal Tracking Dashboard
4. Activation & Delivery Tracker
5. Corporate Intelligence Monitor
6. Relationship Management Calendar
7. Financial Tracking Spreadsheet
8. Negotiation Checklist & Terms Tracker

---

## 1. Corporate Target Identification Worksheet

### Purpose
Systematically identify and qualify 50+ corporations for partnerships in 2-week period.

### How to Use
1. Start with 10 direct competitors/customers
2. Add 10 industry adjacencies
3. Add 10 CSR/values alignment
4. Add 10 geographic/local players
5. Add 10 international opportunities
6. Score each against fit criteria

### Worksheet Template

| Company Name | Industry | Why Relevant | Strategic Alignment | Contact Person | LinkedIn URL | Fit Score | Next Action | Status |
|---|---|---|---|---|---|---|---|---|
| Salesforce | Enterprise Software | Customer + CSR leader | DEI + Sustainability | [Name] | [URL] | 9/10 | Research programs | To Research |
| Google | Tech | Cloud provider | AI/ML + Education | [Name] | [URL] | 8/10 | Find innovation contact | Initial Contact |
| Patagonia | Retail | Values aligned | Environmental mission | [Name] | [URL] | 8/10 | Review grants program | To Research |
| Capital One | Financial Services | Potential customer | Tech innovation | [Name] | [URL] | 7/10 | Connect via employee | Initial Contact |
| | | | | | | | | |

### Scoring Criteria (1-10 scale)

**Strategic Alignment** (40% weight)
- 9-10: Direct customer/partner fit, solves their stated problems
- 7-8: Industry adjacency, relevant to their strategy
- 5-6: Values alignment but indirect business fit
- 3-4: Geographic/network connection only
- 1-2: No clear alignment

**Resource Availability** (30% weight)
- 9-10: Dedicated innovation/CSR team with $500K+ budget
- 7-8: Program exists with $200K-$500K budget
- 5-6: General grants but limited budget
- 3-4: Ad-hoc sponsorships only
- 1-2: No visible programs

**Accessibility** (20% weight)
- 9-10: Warm introduction available
- 7-8: 1-2 degrees of separation
- 5-6: Can reach via LinkedIn/email
- 3-4: Large company, hard to reach
- 1-2: No clear path to decision-maker

**Probability of Success** (10% weight)
- 9-10: Already customer/strong relationship
- 7-8: Have met key stakeholders
- 5-6: Have connected with company
- 3-4: Cold target, good fit
- 1-2: Cold target, weak fit

**Composite Score**: (Alignment × 0.40) + (Resources × 0.30) + (Accessibility × 0.20) + (Probability × 0.10)

### Priority Tiers
- **Tier 1** (Score 8-10): Pursue immediately (top 10)
- **Tier 2** (Score 6-8): Research deeply (next 15)
- **Tier 3** (Score 4-6): Background research (next 25)

---

## 2. Corporate Partnership Pipeline Tracker

### Purpose
Track all corporate prospects through pipeline stages with key information.

### CRM Integration
If using Salesforce, HubSpot, or similar:
- Custom Object: "Corporate Partnership"
- Record Type: Sponsorship, Pilot, Grant, In-Kind
- Stage: (See below)

### Pipeline Stages

```
Stage 1: Target Identified
├─ Company researched
├─ Programs identified
├─ Fit score assigned
└─ Contact info gathered

Stage 2: Initial Contact
├─ Warm intro sent or cold outreach
├─ Email/LinkedIn sent
├─ Response status tracked
└─ Next contact scheduled

Stage 3: Discovery Meeting
├─ Exploratory call completed
├─ Corporate priorities understood
├─ Budget/timeline learned
├─ Next steps agreed

Stage 4: Proposal Development
├─ Value prop customized
├─ Proposal drafted
├─ Stakeholders identified
└─ Proposal submitted

Stage 5: Negotiation
├─ Terms discussed
├─ Legal review started
├─ Minor revisions made
└─ Deal approaching close

Stage 6: Active Partnership
├─ Agreement signed
├─ Execution started
├─ Quarterly reviews scheduled
└─ Renewal timeline set

Stage 7: Renewal/Expansion
├─ Renewal discussion initiated
├─ Expansion opportunities identified
├─ New proposal submitted
└─ Relationship evolving
```

### Tracker Template (Google Sheets or Excel)

| Company | Program Type | Tier | Stage | Contact | Email | Phone | LinkedIn | Fit Score | Budget Est. | Timeline | Proposal Date | Expected Close | Probability | Amount | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Salesforce | Sponsorship | 1 | Stage 3 | John Smith | john@sf.com | 415-555-0101 | [URL] | 9 | $150K | Q1 2024 | 11/15 | 12/15 | 70% | $150K | Strong fit with DEI goals |
| Google | Pilot | 1 | Stage 2 | Jane Doe | jane@google.com | 650-555-0102 | [URL] | 8 | $250K | Q1 2024 | TBD | Q2 2024 | 50% | $250K | Awaiting response to intro |
| | | | | | | | | | | | | | | | |

### Key Metrics to Calculate
- **Pipeline Value**: Sum of (Amount × Probability) for all stages
- **Velocity**: Average time from Stage 1 → Stage 6
- **Conversion Rate**: # Closed / # In Pipeline
- **Stage Breakdown**: Count by stage (shows where deals get stuck)
- **Quarterly Forecast**: Close probability for deals likely to close this quarter

---

## 3. Proposal Tracking Dashboard

### Purpose
Monitor all submitted proposals and their status in corporate review processes.

### Template

| Proposal ID | Company | Program | Submission Date | Amount | Status | Reviewer | Due Date | Days Pending | Follow-up Date | Outcome |
|---|---|---|---|---|---|---|---|---|---|---|
| PROP-001 | Salesforce | Sponsorship | 10/15/2023 | $150K | Under Review | John Smith | 11/30/2023 | 24 | 11/22/2023 | Pending |
| PROP-002 | Google | Pilot | 10/20/2023 | $250K | Under Review | Jane Doe | 12/15/2023 | 19 | 11/30/2023 | Pending |
| PROP-003 | Microsoft | In-Kind | 09/30/2023 | $100K | Approved | Mike Jones | N/A | N/A | N/A | Won |
| PROP-004 | AWS | Partnership | 09/15/2023 | $200K | Awaiting Legal | Sarah Lee | TBD | 39 | 11/20/2023 | In Progress |
| PROP-005 | Adobe | Grant | 08/30/2023 | $50K | Rejected | Tom Brown | N/A | N/A | N/A | Lost |

### Status Definitions
- **Draft**: Not yet submitted
- **Submitted**: Awaiting initial review
- **Under Review**: Corporate team reviewing internally
- **Awaiting Legal**: Legal team reviewing terms
- **Awaiting Approval**: Final approval stage
- **Approved**: Deal approved, awaiting signature
- **Won**: Contract signed, active partnership
- **Lost**: Rejected or no decision
- **Withdrawn**: Removed from consideration

### Follow-up Timing Rules
- Days 7-10: Check in if no response
- Days 21-28: More formal follow-up
- Days 35+: Escalate or consider lost
- Days 45+: Archive if no progress

---

## 4. Activation & Delivery Tracker

### Purpose
Ensure all contractual commitments are met and tracked during active partnerships.

### Template

**Partnership**: [Company Name] | **Agreement Period**: [Start Date] - [End Date]
**Contact**: [Primary Contact] | **Amount**: $[Total]

#### Contractual Deliverables

| Deliverable | Type | Due Date | Completed Date | Status | Notes |
|---|---|---|---|---|---|
| Logo placement on website | PR/Marketing | Immediate | 10/18/2023 | Complete | Completed with prominent placement |
| Speaking slot at conference | Event | 11/15/2023 | TBD | Pending | Waiting for conference schedule |
| Case study delivery | Marketing | 12/31/2023 | TBD | In Progress | Draft sent for corporate review |
| Quarterly report (Q1) | Reporting | 01/15/2024 | TBD | Pending | Template prepared, collecting metrics |
| Annual impact summary | Reporting | 12/31/2023 | TBD | Pending | Data aggregation in progress |
| Employee volunteer days (10) | Engagement | Ongoing | 4 complete | In Progress | 4 days scheduled, 6 remaining |
| Co-marketing launch | Marketing | 10/30/2023 | TBD | Pending | Coordinating timing with partner |

#### Quarterly Business Review Tracker

| Quarter | Review Date | Attendees | Key Metrics Shared | Outcomes | Next Steps |
|---|---|---|---|---|---|
| Q1 2024 | 01/15/2024 | John Smith, Jane Doe | Revenue, Usage, Satisfaction | Positive feedback, renewal interest | Schedule Q2 review |
| Q2 2024 | 04/15/2024 | TBD | TBD | TBD | TBD |
| Q3 2024 | 07/15/2024 | TBD | TBD | TBD | TBD |
| Q4 2024 | 10/15/2024 | TBD | TBD | TBD | Renewal discussion |

#### Issue/Risk Log

| Date Logged | Issue | Severity | Owner | Status | Resolution |
|---|---|---|---|---|---|
| 10/25/2023 | Logo placement delayed | Medium | Jane | Resolved | Logo placed 10/28 |
| 11/10/2023 | Case study approval slow | Medium | Tom | In Progress | Escalated to CMO |
| 11/05/2023 | Budget reallocation at partner | High | John | Mitigating | Proposal ammendment drafted |

---

## 5. Corporate Intelligence Monitor

### Purpose
Track corporate strategic changes that affect partnership opportunities and risk.

### Dashboard Template

**Monitoring Frequency**: Weekly

| Company | Signal | Source | Date | Impact | Action |
|---|---|---|---|---|---|
| Salesforce | Announced $5B DEI initiative | Press Release | 10/20/2023 | High | Increase DEI partnership emphasis |
| Google | 15% workforce reduction | News | 10/25/2023 | Medium | Reduce expectations on employee engagement |
| Microsoft | New Satya Nadella priority: AI | Earnings Call | 10/27/2023 | High | Reposition partnership to emphasize AI |
| Adobe | New Chief Innovation Officer | LinkedIn | 11/01/2023 | Medium | Research new CIO's priorities |
| Stripe | Series F round indicates growth | Crunchbase | 11/05/2023 | Low | Monitor for partnership expansion |

### Intelligence Sources to Monitor
- **Earnings Calls** (quarterly): Search on investor relations websites
- **CSR/ESG Reports** (annual): Usually published Q1 after fiscal year-end
- **Press Releases** (ongoing): Company news/announcements
- **LinkedIn Updates** (ongoing): Job changes, new initiatives
- **Conference Speeches** (quarterly): CEO/CTO speaking engagements
- **Regulatory Filings** (annual): SEC filings for public companies
- **News Monitoring** (weekly): Set up Google Alerts for top prospects

### Key Intelligence to Track
1. **Strategic Pivots**: New business focus areas
2. **Budget Changes**: Expansion or reduction in relevant areas
3. **Leadership Changes**: New executives = new priorities
4. **Competitor Actions**: Tracking what competitors partner on
5. **Public Commitments**: ESG targets, diversity goals, innovation pledges
6. **Geographic Expansion**: New markets = new programs
7. **M&A Activity**: Acquisitions show strategic interest areas

---

## 6. Relationship Management Calendar

### Purpose
Manage relationship touchpoints and ensure consistent engagement.

### Calendar Template (Monthly View)

**November 2023**

| Week | Monday | Tuesday | Wednesday | Thursday | Friday | Notes |
|---|---|---|---|---|---|---|
| **Week 1** | | Google: Send proposal | | Salesforce: Schedule QBR | | Google proposal deadline |
| **Week 2** | AWS: Exploratory call | | Microsoft: Follow-up call | | Adobe: Send intro email | 3 calls this week |
| **Week 3** | | Salesforce: QBR meeting | | | Google: Follow-up call | QBR meeting |
| **Week 4** | | | Stripe: Cold outreach | | Deloitte: Send case study | Send updated materials |

### Relationship Cadence Recommendations

**By Partnership Stage**:

**Stage 1 (Target Identified)**
- Initial research: 1 week
- Follow-up intro: 2 weeks

**Stage 2 (Initial Contact)**
- First follow-up: 1 week
- Second follow-up: 2 weeks
- Third follow-up: 3 weeks (then pause/archive)

**Stage 3 (Discovery)**
- Initial call: Schedule within 3 days
- Follow-up: 1 week
- Next call: 2-3 weeks

**Stage 4 (Proposal)**
- Submit: Target within 1 week of discovery
- Follow-up: 1 week after submission
- Check-in: Weekly thereafter
- Escalation: Day 21 if no response

**Stage 5 (Negotiation)**
- Weekly: Review meetings
- Issue resolution: 2-3 day turnaround
- Legal review: 7-10 days typical

**Stage 6 (Active)**
- Monthly: Deliverable check-in (internal)
- Quarterly: Business review meeting
- Ad hoc: Issue resolution

**Stage 7 (Renewal)**
- 6 months before expiry: Renewal conversation
- Quarterly: Ongoing engagement

---

## 7. Financial Tracking Spreadsheet

### Purpose
Track corporate funding revenue, pipeline value, and forecasting.

### Revenue Tracking

| Month | Company | Program | Amount | Status | Revenue Recognized | Notes |
|---|---|---|---|---|---|---|
| Oct 2023 | Microsoft | In-Kind | $100K | Received | 50% (3mo agreement) | AWS credits |
| Oct 2023 | Salesforce | Sponsorship | $50K | Invoiced | 100% (received) | Cash sponsorship |
| Nov 2023 | Google | Pilot | $250K | Started | 25% (3 months elapsed) | Monthly billing |
| Nov 2023 | Adobe | Grant | $50K | Pending | 0% | Awaiting approval |

### Pipeline Forecast (Next 12 Months)

| Company | Program | Q1 | Q2 | Q3 | Q4 | Annual Total | Stage | Probability |
|---|---|---|---|---|---|---|---|---|
| Salesforce | Renewal + Expansion | $75K | $100K | $100K | $100K | $375K | Active | 90% |
| Google | Pilot Expansion | | $200K | $200K | $200K | $600K | Negotiation | 60% |
| Microsoft | New Program | | $100K | $100K | $100K | $300K | Proposal | 40% |
| Total Forecasted | | $75K | $400K | $400K | $400K | $1,275K | | |

### Metrics Dashboard

```
CORPORATE PARTNERSHIP METRICS

Pipeline Health
├─ Total Pipeline Value: $1,275K
├─ Weighted Pipeline (by probability): $765K
├─ Target (3-year): $3M/year
└─ Achievement Rate: 25% of target (realistic Year 1)

Conversion Metrics
├─ Proposals Submitted: 8
├─ Proposals Won: 3
├─ Conversion Rate: 37.5%
└─ Average Deal Size: $175K

Relationship Metrics
├─ Active Partnerships: 3
├─ Renewal Rate: 100% (limited sample)
├─ Expansion Rate: 1.5x (renewals increasing)
└─ New Partner Acquisition: 3/quarter

Efficiency Metrics
├─ Days from Discovery to Close: 45 days
├─ Proposals per Active Partnership: 2.7
├─ Contact Touchpoints per Close: 8
└─ Success Rate by Tier:
   - Tier 1: 60%
   - Tier 2: 35%
   - Tier 3: 15%
```

---

## 8. Negotiation Checklist & Terms Tracker

### Purpose
Standardize negotiation process and track key deal terms.

### Pre-Negotiation Checklist

**Information Gathering**
- [ ] Corporate budget for this program known
- [ ] Approval authority identified (who signs?)
- [ ] Timeline for decision known
- [ ] Other competing proposals known (are we in selection process?)
- [ ] Corporate risk tolerance understood (are pilots preferred?)
- [ ] Reporting requirements identified
- [ ] Exclusivity desires known

**Preparation**
- [ ] Multiple proposal versions ready (tiers of options)
- [ ] Legal review of standard terms completed
- [ ] Internal team aligned on acceptable terms
- [ ] Authority levels documented (who can approve what?)
- [ ] Walk-away terms defined
- [ ] BATNA (best alternative) identified

**Relationship Building**
- [ ] Internal champion(s) identified at corporate
- [ ] Executive sponsor relationship established
- [ ] Advisory board potential explored
- [ ] Cross-departmental relationships mapped
- [ ] Risk mitigation proposed (pilot vs. full)

### Deal Terms Tracker

| Element | Proposed | Corporate Counteroffer | Final Agreement | Status |
|---|---|---|---|---|
| **Amount** | $250K | $200K | $225K | Agreed |
| **Duration** | 24 months | 12 months | 12 months + renewal option | Agreed |
| **Payment Terms** | Monthly | Quarterly | Monthly on invoice | Agreed |
| **Deliverables** | [List] | Subset of list | Modified list | TBD |
| **Exclusivity** | None | Exclusive to category | Non-exclusive | TBD |
| **IP Ownership** | Ours | Shared | Ours (Corp gets license) | TBD |
| **Publicity** | Co-announcement | Internal use only | Standard joint announcement | TBD |
| **Termination** | 90-day notice | 30-day notice | 60-day notice | TBD |
| **Renewal Option** | Auto-renew | Manual renewal | Auto-renew with opt-out | TBD |

### Negotiation Red Flags

- [ ] Corporate won't commit to timeline
- [ ] Budget authority not at negotiation table
- [ ] Too many layers of approval (more than 3)
- [ ] Requesting unlimited exclusivity
- [ ] Excessive reporting burden (weekly reporting = red flag)
- [ ] Demanding IP ownership/royalties
- [ ] No path to renewal (one-off only)
- [ ] Requiring unlimited performance guarantees
- [ ] Excessive confidentiality restrictions (limits your marketing)

### Escalation Protocol

**If negotiation stalls:**
1. Pause and assess (48 hours)
2. Identify sticking point
3. Present 2-3 options (not ultimatums)
4. Request executive-to-executive conversation if needed
5. Walk away if terms cross BATNA

---

## Sample Google Sheets Setup

### Recommended Tabs/Sheets Structure

1. **Dashboard** (summary metrics, charts)
2. **Pipeline Tracker** (all prospects, stages)
3. **Proposals** (tracking submissions and approvals)
4. **Active Partnerships** (deliverables, metrics)
5. **Intel Monitor** (corporate intelligence signals)
6. **Financial** (revenue tracking, forecasting)
7. **Contacts** (all corporate contacts, LinkedIn, roles)
8. **Calendar** (relationship touchpoints)

### Automation Rules (if using Google Sheets)

- **Auto-calculate** pipeline value (Amount × Probability)
- **Conditional formatting** for stage colors (Red=At Risk, Yellow=At Decision, Green=Moving Forward)
- **Alerts** for overdue follow-ups (21+ days pending)
- **Monthly reports** generated automatically
- **Forecast charts** updated weekly

---

## Implementation Timeline

### Week 1: Setup
- [ ] Create master spreadsheet (pipeline tracker)
- [ ] Add first 20 target companies
- [ ] Score each company
- [ ] Set up calendar reminders

### Week 2: Enhance
- [ ] Add proposal tracking
- [ ] Set up intelligence monitoring
- [ ] Create relationship calendar
- [ ] Document internal processes

### Week 3-4: Operate
- [ ] Weekly pipeline reviews
- [ ] Track all outreach
- [ ] Monitor proposals
- [ ] Update intelligence

### Month 2+: Optimize
- [ ] Analyze conversion metrics
- [ ] Identify high-probability patterns
- [ ] Refine scoring criteria
- [ ] Expand to additional trackers

---

## Best Practices

1. **Update weekly**: Pipeline data becomes stale quickly
2. **Standardize naming**: Use consistent company names
3. **Document conversations**: Every call/meeting logged with notes
4. **Set reminders**: Automated follow-ups reduce oversight
5. **Review metrics**: Monthly analysis drives strategy adjustments
6. **Share transparency**: Team access to pipeline (enables cross-functional support)
7. **Archive regularly**: Move closed/lost deals to archive (keeps active pipeline clean)

