# R&D Tax Credit Documentation Templates

## Overview
Proper documentation is the difference between claiming R&D credits and defending them in an audit. This guide provides ready-to-use templates for the three critical documentation categories: Project Catalog, Time Tracking, and Personnel Forms.

**Pro Tip**: The best documentation is created QUARTERLY, not compiled at year-end. Use these templates during your regular sprint cycles.

---

## Section 1: R&D Project Catalog

This is your primary document describing which projects qualify for R&D credits. Each project needs a narrative explaining the technical work, uncertainties, and experiments.

### Template 1.1: Project Overview Form

**Instructions**: Complete one form per significant R&D project per quarter

```markdown
# R&D PROJECT DOCUMENTATION FORM

## Basic Information
Project Name: [Project Name]
Quarter/Period: [Q1/Q2/Q3/Q4 Year]
Department: [Engineering / Hardware / Data Science / etc.]
Primary Owner: [Engineer Name]
Secondary Team Members: [Names of others who contributed]

## Project Description
**Objective**:
[2-3 sentences describing what the project aims to accomplish]
Example: "Develop machine learning model to improve recommendation engine accuracy from 78% to 85%+ while maintaining <200ms latency for user-facing API calls."

**Business Impact**:
[What problem does this solve? Why is it important?]
Example: "Poor recommendation accuracy results in low conversion and user churn. This improves core product value."

## Technical Uncertainty (CRITICAL)
[Describe the technical challenges/uncertainties you faced. This is what makes it qualify.]

What we didn't know at the start:
- [ ] Best algorithm approach (if multiple options tested)
- [ ] Optimal model architecture
- [ ] Required training data volume
- [ ] Performance optimization techniques
- [ ] Integration/compatibility challenges
- [ ] Scalability requirements
- [ ] Other: [specify]

**Detailed Explanation**:
[Explain each uncertainty. Why wasn't this known? What made it unclear?]

Example:
"We were uncertain whether LSTM or Transformer architecture would better balance accuracy with inference speed. Three approaches were viable but each had trade-offs:
1. LSTM: Proven, fast inference, lower accuracy expected
2. Transformer: Highest accuracy, slower inference, untested at our scale
3. Hybrid: Middle ground, architecture unknown in literature
We needed to experimentally validate which approach met our constraints."

## Experimentation & Iterations
[Describe the experiments you ran, iterations tried, and learnings]

| Experiment/Iteration | Approach Tested | Duration | Result/Learning |
|---------------------|-----------------|----------|-----------------|
| Iteration 1 | Basic LSTM baseline | 2 weeks | 76% accuracy, too slow (500ms) |
| Iteration 2 | LSTM with pruning | 1.5 weeks | 77% accuracy, 250ms (better) |
| Experiment 1 | Transformer-base | 2 weeks | 82% accuracy, 600ms (too slow) |
| Experiment 2 | Transformer with quantization | 1 week | 81% accuracy, 180ms (acceptable!) |
| Iteration 3 | Ensemble: LSTM+Transformer | 1.5 weeks | 83% accuracy, 220ms (good trade-off) |
| Final optimization | Model distillation | 1 week | 82% accuracy, 150ms (final) |

**Key Learnings**:
- Transformer was technically superior but required optimization we hadn't anticipated
- Quantization degraded accuracy less than expected
- Ensemble approach provided best balance (was not our initial plan)

## Outcomes & Results
**Final Result**: [What did you achieve?]
Example: "Achieved 82% recommendation accuracy with 150ms latency, exceeding both constraints."

**Was R&D successful?**: YES / NO / PARTIAL
[Even if R&D didn't succeed, it still qualifies for credits]

**Artifacts Created**:
- [ ] GitHub commits (link to branch/PR: ___________________)
- [ ] Design documents (location: ___________________)
- [ ] Technical specifications (location: ___________________)
- [ ] Test results/benchmarks (location: ___________________)
- [ ] Architecture diagrams (location: ___________________)
- [ ] Model training logs (location: ___________________)
- [ ] Performance reports (location: ___________________)

## Personnel & Time Allocation

| Team Member | Primary Role | Time Spent | % on this Project |
|-------------|-------------|-----------|-------------------|
| [Name] | [Role] | [hours/days] | [%] |
| [Name] | [Role] | [hours/days] | [%] |
| [Name] | [Role] | [hours/days] | [%] |

**Total Project Hours**: [Total hours]
**Total Person-Months**: [hours ÷ ~160 hrs/month]

## Code & Documentation References
Link to actual code developed:
- Repository: [GitHub link]
- Branches/PRs related to this project: [Links]
- Commit timeline: [From-To dates]

## Qualification Assessment
**Does this project qualify for R&D credits?** YES / NO

**Reasoning**:
- Technological in nature: YES / NO
- Involved experimentation: YES / NO
- Addressed technical uncertainty: YES / NO
- Attempted to improve product: YES / NO

[If NO to any, explain why we're including/excluding]

## Approvals
Prepared by: _________________ Date: _______
Reviewed by (Technical Lead): _________________ Date: _______
Approved for credit claim: _________________ Date: _______
```

### Template 1.2: Project Catalog Summary (Quarterly)

Complete this at the END of each quarter to summarize all projects:

```markdown
# QUARTERLY R&D PROJECT SUMMARY
Quarter: [Q1/Q2/Q3/Q4 Year]
Company: [Company Name]
Reporting Period: [Date Range]
Prepared by: [Name]

## Project List

| Project # | Project Name | Owner | Team Size | Primary Focus | Status | Est. Hours |
|-----------|---|---|---|---|---|---|
| 1 | [Project] | [Owner] | [#] | [Focus] | Complete/In Progress | [Hours] |
| 2 | [Project] | [Owner] | [#] | [Focus] | Complete/In Progress | [Hours] |
| 3 | [Project] | [Owner] | [#] | [Focus] | Complete/In Progress | [Hours] |

## Quarter Highlights
[2-3 sentences on major R&D achievements]

## QRE-Relevant Metrics
- Total engineers: [#]
- Total engineering hours: [hours]
- Estimated R&D time: [#] hours ([%] of total)
- New projects initiated: [#]
- Projects completed: [#]

## Key Technologies/Areas
- Software/Cloud: [technologies used]
- Data Science/AI: [algorithms/models]
- Infrastructure: [systems work]
- Hardware: [hardware projects]
- Integration: [integrations worked on]

## Challenges & Innovations
List novel technical challenges solved this quarter:
1. [Challenge/Innovation]
2. [Challenge/Innovation]
3. [Challenge/Innovation]

## Carry-Forward Projects
Projects continuing into next quarter:
- [Project name]: [Status/next steps]
- [Project name]: [Status/next steps]

## Completeness Check
- [ ] All major projects documented
- [ ] All detailed project forms completed
- [ ] Artifacts/references verified
- [ ] Time allocations reviewed
- [ ] QRE calculations drafted
- [ ] Technical review completed
```

---

## Section 2: Time Tracking Documentation

### Template 2.1: Weekly Time Allocation Log

Use this template to track engineer time on R&D vs. non-R&D work:

```markdown
# WEEKLY TIME ALLOCATION TRACKING
Employee Name: [Name]
Title/Role: [Title]
Week of: [Monday - Friday dates]
Manager: [Manager Name]

## Daily Breakdown

### Monday [Date]
| Project/Activity | Activity Type | Duration | R&D? | Notes |
|-----------------|---|---|---|---|
| [Project X] | Feature development | 3 hrs | YES | Implemented feature Y |
| [Project X] | Code review | 1 hr | YES | Reviewed PR from teammate |
| Meetings | Team standup | 0.5 hrs | NO | General team sync |
| [Project Y] | Bug fix | 1.5 hrs | NO | Production bug, not R&D |
| Other | Admin/email | 1 hr | NO | - |

### Tuesday [Date]
| Project/Activity | Activity Type | Duration | R&D? | Notes |
|-----------------|---|---|---|---|
| [Project X] | Testing | 2.5 hrs | YES | Unit tests for new feature |
| [Project Z] | Experimentation | 3 hrs | YES | Testing new ML library |
| Meeting | Architecture review | 1 hr | YES | Design discussion on new system |
| Other | Email/admin | 0.5 hrs | NO | - |

### Wednesday [Date]
[Continue for each day]

## Weekly Summary

| Category | Hours | % of 40 hrs | Qualified R&D? |
|----------|-------|-----------|---|
| R&D Development | [hours] | [%] | YES |
| R&D Testing/Experimentation | [hours] | [%] | YES |
| Meetings (R&D-related) | [hours] | [%] | YES |
| Code Review (R&D work) | [hours] | [%] | YES |
| Bug Fixes (Production) | [hours] | [%] | NO |
| Meetings (Non-R&D) | [hours] | [%] | NO |
| Admin/Other | [hours] | [%] | NO |
| **TOTAL R&D HOURS** | **[hours]** | **[%]** | - |

## Employee Notes
[Any special circumstances? Vacation? PTO? Special projects?]

## Manager Verification
Manager Review: [ ] Approved [ ] Needs Revision
Manager Signature: _________________ Date: _______

---

**Notes for Calculation**:
- R&D time: Anything involving development, testing, experimentation on products/features
- NOT R&D: Routine bug fixes, customer support, sales engineering, meetings about operations
- If uncertain, discuss with tax specialist

**Expected allocation for roles**:
- Full-time engineer: 70-90% R&D time typical
- Tech lead: 50-80% R&D time (some management)
- Product manager: 30-50% R&D time (only technical work)
- QA: 20-60% R&D time (only advanced testing)
```

### Template 2.2: Monthly Time Allocation Summary

Summary form completed at end of each month:

```markdown
# MONTHLY TIME ALLOCATION SUMMARY
Month: [Month/Year]
Department/Team: [Engineering / Product / Data Science / etc.]

## Individual Summary

| Employee | Total Hours | R&D Hours | R&D % | Notes |
|----------|------------|-----------|-------|-------|
| [Name] | 160 | 128 | 80% | Mostly feature dev |
| [Name] | 160 | 144 | 90% | Pure engineering |
| [Name] | 160 | 96 | 60% | Product mgmt, partial R&D |
| [Name] | 160 | 48 | 30% | Operations/support |

## Team Totals
- Total Hours Worked: [hours]
- Total R&D Hours: [hours]
- Team R&D Percentage: [%]

## Major Activities This Month
- [Project/Activity]: [Hours]
- [Project/Activity]: [Hours]
- [Project/Activity]: [Hours]

## Adjustments from Weekly Logs
[Any corrections or clarifications from weekly tracking]

## Manager Certification
I certify that the above time allocations are accurate and represent actual work performed:

Signed: _________________ Date: _______
Manager: _________________
```

### Template 2.3: Annual Time Allocation Report

Consolidates all months/weeks into annual view:

```markdown
# ANNUAL R&D TIME ALLOCATION REPORT
Year: [Year]
Company: [Company Name]
Reporting Manager: [Manager]

## Employee-Level Summary

| Employee | Title | Annual Hours | R&D Hours | R&D % | W-2 Wages | Qualified Wages |
|----------|-------|-------|-------|-------|-------|-------|
| [Name] | Senior Engineer | 2,080 | 1,872 | 90% | $150,000 | $135,000 |
| [Name] | Mid Engineer | 2,080 | 1,664 | 80% | $120,000 | $96,000 |
| [Name] | Product Manager | 2,080 | 624 | 30% | $130,000 | $39,000 |
| [Name] | Junior Engineer | 1,976 | 1,383 | 70% | $85,000 | $59,500 |
| **TOTALS** | - | **8,316** | **5,543** | **67%** | **$485,000** | **$329,500** |

## Methodology
[Describe how time allocation was determined - actual tracking, estimates, benchmarks, etc.]

## Variance Analysis
[Explain any significant changes from prior year]

## Supporting Documentation
The following documentation supports these allocations:
- [ ] Weekly time logs (all 52 weeks)
- [ ] Monthly summaries (all 12 months)
- [ ] GitHub/Jira commit analysis
- [ ] Manager interviews/validation
- [ ] Project timelines

## Certification
I certify that:
1. These time allocations represent actual work performed on R&D activities
2. All calculations are accurate and complete
3. Supporting documentation is available for audit

Prepared by: _________________ Date: _______
Reviewed by: _________________ Date: _______
Approved by: _________________ Date: _______
```

---

## Section 3: Personnel Documentation Forms

### Template 3.1: Personnel Qualification Form

Document each employee who performed R&D work:

```markdown
# PERSONNEL QUALIFICATION FORM

## Employee Information
**Name**: [Full Name]
**Title**: [Job Title]
**Department**: [Engineering/Data Science/etc.]
**Start Date**: [Date]
**Reports To**: [Manager Name]
**2024 W-2 Wages**: $[Amount]

## Role & Responsibilities
**Primary Job Functions**:
1. [Function]
2. [Function]
3. [Function]

**R&D Activities Performed** (percentage of time):
- Feature development/coding: [%]
- Architecture/design work: [%]
- Technical research/experimentation: [%]
- Testing/QA (advanced/novel): [%]
- Code review: [%]
- Other R&D: [%]
- **Total R&D Time**: [%]

## Educational Background
**Degree(s)**:
- [Degree, Field, School]
- [Degree, Field, School]

**Relevant Experience**:
- [Years] years of [Field] experience
- [Certifications or specialized training]

## Qualification Assessment
Is this employee qualified to perform R&D activities?

**Technical Expertise**: [ ] YES [ ] NO
Description: [What technical skills qualify them?]

**Performs R&D Work**: [ ] YES [ ] NO
Description: [What R&D activities do they perform?]

**Can Allocate Time to R&D**: [ ] YES [ ] NO
Description: [How is their time allocated?]

## Projects Worked On (This Year)
| Project | Role | Time Allocation |
|---------|------|-----------------|
| [Project] | [Role] | [#] hours or [%] |
| [Project] | [Role] | [#] hours or [%] |
| [Project] | [Role] | [#] hours or [%] |

## Calculation of Qualified Wages
```
W-2 Wages (Year): $[Amount]
× R&D Time Allocation: [%]
= Qualified Wages: $[Amount]
```

## Documentation Supporting This Form
- [ ] Job description on file
- [ ] Résumé/CV
- [ ] Time tracking records
- [ ] Project assignments
- [ ] Manager confirmation
- [ ] Payroll records

## Approvals
**Prepared by (HR/Payroll)**: _________________ Date: _______
**Confirmed by (Manager)**: _________________ Date: _______
**Approved by (R&D Tax Specialist)**: _________________ Date: _______
```

### Template 3.2: Team Roster & Qualification Summary

One-page summary of all qualified personnel:

```markdown
# R&D TEAM QUALIFICATION ROSTER
Year: [Year]
Company: [Company Name]
Department(s): [List departments]
Prepared by: [Name]

## Qualified Personnel Summary

| # | Name | Title | Dept | W-2 Wages | R&D % | Qualified Wages | Qualifications |
|---|------|-------|------|-----------|--------|--------|-------|
| 1 | [Name] | Engineer | Eng | $150K | 90% | $135K | BS CS, 8yr exp |
| 2 | [Name] | Engineer | Eng | $120K | 80% | $96K | BS CE, 5yr exp |
| 3 | [Name] | Data Sci | Data | $140K | 100% | $140K | MS ML, 4yr exp |
| 4 | [Name] | QA Engineer | Eng | $85K | 40% | $34K | Advanced testing |
| 5 | [Name] | Product Mgr | Prod | $130K | 30% | $39K | Technical PM |

## Team Metrics
- **Total Qualified Personnel**: [#]
- **Total W-2 Wages**: $[Amount]
- **Total Qualified Wages**: $[Amount]
- **Average R&D Allocation**: [%]

## By Role Breakdown

| Role Category | Count | Total W-2 | Total Qualified | R&D Allocation |
|--------------|-------|-----------|-----------------|-------|
| Full-time Engineers | [#] | $[X] | $[Y] | [%] |
| Data Scientists | [#] | $[X] | $[Y] | [%] |
| Product Managers (Technical) | [#] | $[X] | $[Y] | [%] |
| QA/Testing (Advanced) | [#] | $[X] | $[Y] | [%] |
| **TOTAL** | **[#]** | **$[X]** | **$[Y]** | **[%]** |

## Qualifications Notes
- All personnel have relevant technical education/experience
- Roles align with R&D activities
- Time allocations supported by tracking documentation
- No non-technical or pure management personnel included

## Verification
This roster accurately reflects:
- [ ] All personnel performing R&D work
- [ ] Accurate W-2 wage information from payroll
- [ ] Realistic R&D time allocations
- [ ] Appropriate qualification for roles
- [ ] Complete supporting documentation

**Prepared by**: _________________ Date: _______
**Approved by**: _________________ Date: _______
```

### Template 3.3: Organizational Chart (for Audit Defense)

Show reporting structure and R&D vs. non-R&D roles:

```markdown
# ORGANIZATIONAL CHART - R&D CLASSIFICATION
Year: [Year]
Company: [Company Name]

[Use text or upload visual org chart]

## Role Classifications

### R&D Roles (Qualified)
- Senior Engineers: [Names]
- Mid-level Engineers: [Names]
- Junior Engineers: [Names]
- Data Scientists: [Names]
- Technical Product Managers: [Names]
- QA/Test Engineers (advanced): [Names]

### Support Roles (Not Qualified)
- HR/Admin: [Names]
- Finance/Accounting: [Names]
- Sales: [Names]
- Marketing: [Names]
- Customer Support: [Names]
- Operations: [Names]

### Partial-Allocation Roles (Qualified if time-tracked)
- Technical Product Managers: [Names] - qualified for [%] of time
- Engineering Manager (if technical): [Names] - qualified for [%] of time
- QA Engineers (if advanced): [Names] - qualified for [%] of time

## Notes
[Any special circumstances - new hires, departures, role changes during year]
```

---

## Section 4: Master Documentation Checklist

Use this checklist to ensure you have everything needed for an audit defense:

```markdown
# R&D TAX CREDIT DOCUMENTATION CHECKLIST

## Financial Documentation
- [ ] Payroll records (W-2s, payroll reports)
- [ ] Detailed wage reports by employee
- [ ] General ledger entries for R&D expenses
- [ ] Supply invoices and cost tracking
- [ ] Cloud service invoices (AWS, Azure, GCP)
- [ ] Software license purchases
- [ ] Hardware/equipment purchases
- [ ] Contractor invoices (with descriptions of work)
- [ ] Financial statements (for revenue/gross receipts)

## Project Documentation
- [ ] Quarterly project summaries (all 4 quarters)
- [ ] Detailed project forms (1 per major project)
- [ ] GitHub repositories/commit logs
- [ ] Jira/issue tracking data
- [ ] Design documents
- [ ] Technical specifications
- [ ] Architecture diagrams
- [ ] Test results and benchmarks
- [ ] Email chains discussing technical work
- [ ] Meeting notes about R&D activities

## Personnel Documentation
- [ ] Team roster with roles
- [ ] Organizational chart
- [ ] Job descriptions for qualified personnel
- [ ] Résumés of key technical staff
- [ ] Time tracking records (all employees, all weeks)
- [ ] Monthly time summaries
- [ ] Annual time allocation report
- [ ] Personnel qualification forms

## Time Tracking Documentation
- [ ] Weekly time logs (52 weeks)
- [ ] Monthly summaries (12 months)
- [ ] Manager certifications
- [ ] Any tool-based tracking (Jira, GitHub, etc.)
- [ ] Methodology documentation (how time was determined)

## Calculation Documentation
- [ ] QRE calculation spreadsheets
- [ ] Federal credit calculation (ASC or Regular method)
- [ ] State credit calculations
- [ ] Contract research allocation methodology
- [ ] Supply cost allocation (if relevant)
- [ ] All supporting schedules

## Compliance & Filing
- [ ] Form 6765 (completed and signed)
- [ ] Form 8974 (if claiming payroll tax offset)
- [ ] Supporting schedules and documentation
- [ ] Tax return copies (Form 1120, 1040, etc.)
- [ ] State return filings
- [ ] Amendment filings (if prior years claimed)

## Signatures & Approvals
- [ ] Tax specialist sign-off
- [ ] CPA signature
- [ ] Company officer signature
- [ ] Engineering manager verification
- [ ] All approvals dated

## Organization
- [ ] Master documentation binder prepared
- [ ] Index/table of contents
- [ ] Cross-references between documents
- [ ] Digital backup of all documentation
- [ ] Organized by project/month/employee as applicable

---

## Tips for Using These Templates

**Timing**:
- Use project forms AT THE END OF EACH PROJECT SPRINT/QUARTER
- Use time tracking WEEKLY
- Compile monthly and quarterly summaries

**Completeness**:
- More detail is better than less (for audit defense)
- Include links/references to actual work (GitHub, Jira, etc.)
- Get manager sign-offs as you go (don't wait until year-end)

**IRS Standards**:
- These templates align with IRS Form 6765 requirements
- Documentation should be "contemporaneous" (created during year, not year-end)
- Keep for minimum 3 years (7 years is safer)

**Audit Readiness**:
- A reviewer should be able to understand your R&D activities from these documents
- Each credit dollar claimed should be traceable to documented work
- Gaps in documentation = reduced credits allowed
```

---

## Digital Tools for Documentation

While these templates can be completed manually, consider these tools to streamline:

### Time Tracking
- **Toggl Track**: Simple time logging by project/task
- **Clockify**: Free time tracking for teams
- **Jira Time Tracking**: If already using Jira for project management
- **Harvest**: Invoicing + time tracking

### Project Documentation
- **GitHub/GitLab**: Commits and PRs already document work
- **Jira**: Issue tracking with detailed descriptions
- **Notion/Confluence**: Central documentation hub
- **Linear**: Modern alternative to Jira

### Calculations & Consolidation
- **Excel/Google Sheets**: Traditional approach (works fine)
- **MainStreet Platform**: Automated R&D credit platform
- **Clarus R+D**: Dedicated R&D credit management software

### Storage & Organization
- **Google Drive/OneDrive**: Central folder with organized subfolders
- **Box**: Enterprise document management
- **Dropbox**: File storage and version control

**Best Practice**: Whatever tool you choose, the golden rule is: **Document as you work, not at year-end.** Quarterly review and compilation is infinitely better than emergency documentation scramble in December.

---

## Final Notes

- Keep these templates on file and reuse quarterly
- Update annually as team/structure changes
- Share with your R&D tax specialist early
- Have engineering leads confirm accuracy
- Back up digital files regularly
- Keep paper/electronic copies for 7 years minimum

Proper documentation is your defense against IRS audit challenges. Invest in it quarterly, and claiming R&D credits becomes straightforward.
