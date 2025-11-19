# SBIR/STTR Grant Application Template

**Small Business Innovation Research & Small Business Technology Transfer**

---

## Program Information

| Field | Details |
|---|---|
| **Program Type** | [SBIR Phase I / SBIR Phase II / STTR Phase I / STTR Phase II] |
| **Funding Agency** | [NSF / DOD / DOE / NASA / NIH / NIST / EPA / USDA / DHS / DOT] |
| **Topic Area** | [TOPIC_NUMBER - TOPIC_NAME] |
| **Solicitation Number** | [SOLITATION_NUMBER] |
| **Deadline Date** | [DATE] |
| **Expected Award Amount** | Phase I: $[150,000-225,000] / Phase II: $[500,000-750,000] |
| **Project Duration** | Phase I: [6 months] / Phase II: [24 months] |

---

## Section 1: Project Narrative - Technical Approach (15 pages max)

### 1.1 Problem Statement (1-1.5 pages)

**Objective:** Clearly define the technical problem and its significance

#### Market Problem
- **What problem are you solving?**
  - [DESCRIBE THE SPECIFIC TECHNICAL CHALLENGE]
  - [INCLUDE INDUSTRY/MARKET CONTEXT]
  - [QUANTIFY THE PROBLEM IF POSSIBLE]

**Example:** *Healthcare providers spend 15% of operational costs ($2B industry-wide) on manual claims processing, with 85% error rates requiring manual re-work. Current solutions cost $100K-$500K to implement.*

#### Technical Gap
- **What's missing in current solutions?**
  - [COMPARE EXISTING APPROACHES]
  - [IDENTIFY TECHNICAL LIMITATIONS]
  - [SHOW WHY CURRENT SOLUTIONS ARE INADEQUATE]

**Example:** *Existing RPA solutions require 6+ months of custom training per facility. ML-based alternatives lack accuracy (78-82%) for complex scenarios.*

#### Significance & Impact
- **Why does this matter?**
  - Cost savings: [QUANTIFIED BENEFIT]
  - Time savings: [HOURS/DAYS SAVED]
  - Quality improvement: [SPECIFIC METRICS]
  - Market opportunity: [$X MARKET SIZE]

### 1.2 Solution Overview (1-1.5 pages)

**Objective:** Present your innovative approach at high level

#### Core Innovation
- **What is your unique technical approach?**
  - [DESCRIBE NOVEL ALGORITHM/TECHNOLOGY]
  - [EXPLAIN THE INNOVATION vs. PRIOR ART]
  - [HIGHLIGHT COMPETITIVE ADVANTAGES]

**Example:** *We propose a hybrid ML system combining transfer learning on BERT models with rule-based validation layers, achieving 96%+ accuracy while requiring <4 weeks implementation per facility (10x faster than alternatives).*

#### Feasibility
- **Why is this achievable?**
  - Prior proof-of-concept results: [DESCRIBE POC OUTCOMES]
  - Team expertise: [RELEVANT BACKGROUND]
  - Resource availability: [HARDWARE, DATA, PARTNERSHIPS]
  - Timeline reasonableness: [6-MONTH ACHIEVABILITY]

#### Preliminary Results (if applicable)
- **What evidence supports feasibility?**
  - Lab results: [SPECIFIC DATA POINTS]
  - Prototype performance: [METRICS]
  - Customer feedback: [VALIDATION]
  - Benchmarking: [COMPARISON TO COMPETITORS]

---

### 1.3 Technical Plan & Approach (4-5 pages)

**Objective:** Detailed technical roadmap with measurable milestones

#### Phase Structure
Use this structured approach:

```
PHASE I: Feasibility Study (6 months, $[AMOUNT])
├─ Task 1: [SPECIFIC TECHNICAL OBJECTIVE]
│  └─ Deliverable: [MEASURABLE OUTPUT]
│     Months: 1-2
│     Budget: $[AMOUNT]
│
├─ Task 2: [SPECIFIC TECHNICAL OBJECTIVE]
│  └─ Deliverable: [MEASURABLE OUTPUT]
│     Months: 2-4
│     Budget: $[AMOUNT]
│
├─ Task 3: [SPECIFIC TECHNICAL OBJECTIVE]
│  └─ Deliverable: [MEASURABLE OUTPUT]
│     Months: 4-6
│     Budget: $[AMOUNT]
│
└─ Task 4: Phase II Proposal Development
   └─ Deliverable: Phase II proposal based on Phase I findings
      Months: 5-6
      Budget: Included above
```

#### Detailed Task Breakdown

**Task [X]: [CLEAR TASK TITLE]**
- **Objective:** [WHAT WILL BE ACCOMPLISHED]
- **Approach:**
  - Step 1: [SPECIFIC ACTIVITY]
  - Step 2: [SPECIFIC ACTIVITY]
  - Step 3: [SPECIFIC ACTIVITY]
- **Timeline:** [DURATION AND MILESTONES]
- **Success Criteria:**
  - Metric 1: [MEASURABLE OUTCOME]
  - Metric 2: [MEASURABLE OUTCOME]
  - Metric 3: [MEASURABLE OUTCOME]
- **Key Risks:**
  - Risk: [POTENTIAL PROBLEM]
    Mitigation: [HOW YOU'LL ADDRESS IT]

#### Example Task Breakdown

**Task 1: Data Pipeline Development & Validation**
- **Objective:** Build robust data pipeline supporting 10M+ daily transactions
- **Approach:**
  - Develop ETL processes using Apache Airflow
  - Implement data quality checks (validation rules)
  - Create real-time monitoring dashboards
  - Validate against 6+ data sources
- **Timeline:** Months 1-2
- **Success Criteria:**
  - 99.9%+ pipeline uptime
  - Sub-second latency for queries
  - Data quality score >98%
- **Key Risks:**
  - Risk: Data quality issues delay testing
    Mitigation: Implement validation rules iteratively; partner with [CUSTOMER] for early feedback

**Task 2: ML Model Development & Training**
- **Objective:** Develop and train ML models achieving >95% accuracy
- **Approach:**
  - Prepare training dataset (500K+ samples)
  - Develop baseline models (SVM, Random Forest)
  - Implement deep learning models (LSTM, Transformer)
  - Cross-validation and hyperparameter tuning
  - Benchmark against 3 commercial solutions
- **Timeline:** Months 2-4
- **Success Criteria:**
  - Accuracy: >95% on test set
  - Latency: <100ms per prediction
  - Interpretability: Human-readable decision paths
- **Key Risks:**
  - Risk: Insufficient training data
    Mitigation: Use transfer learning; [CUSTOMER] committed to providing 1M+ samples

**Task 3: System Integration & Prototype Development**
- **Objective:** Build end-to-end prototype integrated with customer systems
- **Approach:**
  - API development for customer system integration
  - Build pilot deployment infrastructure
  - Deploy in 2 customer environments
  - Collect performance data and feedback
- **Timeline:** Months 4-5
- **Success Criteria:**
  - Successful integration with 2 customer systems
  - <4 hours implementation time
  - Customer satisfaction: >4/5 rating
- **Key Risks:**
  - Risk: Integration complexity higher than expected
    Mitigation: Allocate [X%] contingency time; involve [CUSTOMER] IT early

**Task 4: Phase II Proposal Development**
- **Objective:** Develop comprehensive Phase II proposal based on Phase I results
- **Approach:**
  - Document all Phase I findings and learnings
  - Define Phase II commercialization strategy
  - Plan go-to-market approach
  - Develop financial projections
- **Timeline:** Months 5-6
- **Success Criteria:**
  - Phase II proposal submitted before deadline
  - Clear path to commercialization defined
  - Customer commitments secured for Phase II
- **Key Risks:**
  - Risk: Unexpected technical findings delay Phase II planning
    Mitigation: Begin Phase II planning in Month 4; adaptively revise based on findings

---

### 1.4 Innovation & Competitive Advantage (1-1.5 pages)

**Objective:** Demonstrate why your approach is novel and differentiated

#### Technical Innovation
- **What makes this technically novel?**
  - [COMPARE TO PUBLISHED PRIOR ART]
  - [EXPLAIN NOVEL COMBINATION/APPROACH]
  - [CITE PATENTS OR PUBLICATIONS IF APPLICABLE]

#### Competitive Positioning
- **How do you compare to existing solutions?**

| Feature | Your Solution | Competitor A | Competitor B | Competitor C |
|---|---|---|---|---|
| **Accuracy** | 96% | 78% | 82% | 90% |
| **Implementation Time** | 2-4 weeks | 3-6 months | 2-4 months | 1-2 months |
| **Cost** | $[X/month] | $[X/month] | $[X/month] | $[X/month] |
| **Customization Required** | Minimal | Extensive | Some | Minimal |
| **Integration Effort** | 4 hours | 200+ hours | 100+ hours | 40 hours |
| **Regulatory Compliance** | [CERTIFICATIONS] | [CERTIFICATIONS] | [CERTIFICATIONS] | [CERTIFICATIONS] |

#### Intellectual Property
- **What IP will result from this project?**
  - Patent applications: [PLANNED CLAIMS]
  - Trade secrets: [PROTECTED METHODOLOGIES]
  - Software IP: [PROPRIETARY ALGORITHMS]
  - Data assets: [DATASETS CREATED]

---

### 1.5 Team & Qualifications (0.5-1 page)

**Objective:** Demonstrate team capability to execute

#### Key Personnel

**[NAME] - [TITLE] - [% TIME ALLOCATION]**
- **Relevant Experience:**
  - [YEARS] years in [RELEVANT DOMAIN]
  - [SPECIFIC ACCOMPLISHMENT]
  - [RELEVANT EDUCATION/CERTIFICATION]
- **Role in Project:**
  - [SPECIFIC RESPONSIBILITIES]
  - [DECISION-MAKING AUTHORITY]

**Example:**
**Dr. Jane Smith - Principal Investigator (100%)**
- **Relevant Experience:**
  - 8 years developing ML systems for healthcare
  - Led development of claims processing system at [COMPANY] (used by 500+ hospitals)
  - PhD in Machine Learning, Stanford University
  - 4 published papers in top-tier ML conferences
- **Role in Project:**
  - Overall project leadership and technical strategy
  - ML model development and validation
  - Customer relationships and deployment

**[NAME] - [TITLE] - [% TIME ALLOCATION]**
- **Relevant Experience:**
  - [YEARS] years in [RELEVANT DOMAIN]
  - [SPECIFIC ACCOMPLISHMENT]
  - [RELEVANT EDUCATION/CERTIFICATION]
- **Role in Project:**
  - [SPECIFIC RESPONSIBILITIES]

#### Supporting Resources
- **Advisory Board:**
  - [NAME] - [TITLE] - [COMPANY] - [RELEVANT EXPERTISE]
  - [NAME] - [TITLE] - [COMPANY] - [RELEVANT EXPERTISE]
- **Partner Commitments:**
  - [PARTNER NAME]: [SPECIFIC COMMITMENT]
  - [CUSTOMER NAME]: [SPECIFIC COMMITMENT]
- **Consultant Support:**
  - [CONSULTANT NAME]: [AREA OF EXPERTISE]

---

### 1.6 Risk Analysis & Mitigation (0.5-1 page)

**Objective:** Demonstrate thoughtful planning and contingency

#### Technical Risks

| Risk | Probability | Impact | Mitigation Strategy |
|---|---|---|---|
| **[SPECIFIC RISK]** | [High/Med/Low] | [High/Med/Low] | [MITIGATION APPROACH] |
| Data availability insufficient | Medium | High | [CUSTOMER] committed 1M+ samples; contingency plan uses synthetic data |
| ML model accuracy <95% | Medium | High | Transfer learning from [PRIOR PROJECT]; multiple model architectures tested |
| Integration complexity | Low | Medium | Early integration with [CUSTOMER] IT; modular architecture reduces dependencies |

#### Commercialization Risks

| Risk | Probability | Impact | Mitigation Strategy |
|---|---|---|---|
| **[SPECIFIC RISK]** | [High/Med/Low] | [High/Med/Low] | [MITIGATION APPROACH] |
| Customer adoption slower than expected | Medium | Medium | Pre-Phase II customer commitments; pilot deployments secured |
| Regulatory barriers emerge | Low | High | [REGULATORY EXPERT] advising; compliance embedded in design |
| Competitive response | High | Medium | Fast-track Phase II; patent applications filed in Month 3 |

---

### 1.7 Commercialization Plan (1 page, Phase II focus)

**Objective:** Show path from SBIR to sustainable business

#### Target Market
- **Primary Market:** [MARKET SEGMENT]
  - Total Addressable Market: $[BILLION/MILLION]
  - Serviceable Market: $[MILLION]
  - Target Customers: [# OF COMPANIES]
  - Average Deal Size: $[VALUE]
- **Secondary Market:** [MARKET SEGMENT]
  - Potential: [BRIEF DESCRIPTION]

#### Go-to-Market Strategy
- **Phase II (Months 1-24):**
  - Pilot deployments with [# CUSTOMERS]
  - Full product development
  - Regulatory compliance (if needed)
  - Beta customer acquisition
- **Phase III (Year 2-3+):**
  - Product launch with Phase III funding
  - Sales & marketing team hired
  - Channel partnerships (if applicable)
  - Target: $[REVENUE] by Year 3

#### Revenue Model
- **SaaS Model:** $[X/month] per customer, targeting [Y] customers = $[REVENUE] Year 3
- **Licensing Model:** $[X/transaction], [Y] annual transactions = $[REVENUE]
- **Hybrid Model:** [DESCRIBE COMBINATION]

#### Customer Validation
- **Existing Commitments:**
  - [CUSTOMER]: Letter of intent for pilot
  - [CUSTOMER]: Committed to [SPECIFIC COMMITMENT]
  - [PARTNER]: Distribution partnership letter
- **Projected Adoption:**
  - Year 1: [# customers]
  - Year 2: [# customers]
  - Year 3: [# customers]

---

## Section 2: Project Budget & Financial Narrative (2-3 pages)

### 2.1 Budget Summary

**Phase I SBIR: [6 months], Total: $[AMOUNT]**

| Category | Year 1 | Year 2 | Total | % of Budget |
|---|---|---|---|---|
| **Personnel** | $[X] | $[X] | $[X] | [X%] |
| **Equipment** | $[X] | $[X] | $[X] | [X%] |
| **Materials & Supplies** | $[X] | $[X] | $[X] | [X%] |
| **Travel** | $[X] | $[X] | $[X] | [X%] |
| **Other Direct Costs** | $[X] | $[X] | $[X] | [X%] |
| **Indirect Costs (F&A)** | $[X] | $[X] | $[X] | [X%] |
| **TOTAL** | $[X] | $[X] | $[X] | 100% |

### 2.2 Detailed Budget Justification

#### Personnel Costs ($[AMOUNT])

| Name | Title | Rate/Year | Months | Cost |
|---|---|---|---|---|
| [NAME] | [TITLE] | $[X] | [X] | $[COST] |
| [NAME] | [TITLE] | $[X] | [X] | $[COST] |
| [NAME] | [TITLE] | $[X] | [X] | $[COST] |
| **Subtotal Personnel** | | | | $[TOTAL] |

**Justification:** Detailed explanation of each role's necessity and rate reasonableness

#### Equipment & Software ($[AMOUNT])

- **[ITEM]:** $[COST] - Justification: [NEEDED FOR SPECIFIC TASK]
- **[ITEM]:** $[COST] - Justification: [NEEDED FOR SPECIFIC TASK]
- **[ITEM]:** $[COST] - Justification: [NEEDED FOR SPECIFIC TASK]

#### Materials & Supplies ($[AMOUNT])

- **Cloud Computing (AWS/GCP):** $[COST] - 6 months GPU compute for model training
- **Data Procurement:** $[COST] - [DESCRIPTION]
- **Prototype Materials:** $[COST] - [DESCRIPTION]

#### Travel ($[AMOUNT])

- **[LOCATION] - Customer Site Visits:** [# TRIPS] x $[COST/TRIP] = $[TOTAL]
  - Justification: Meet with customers for requirements gathering and feedback
- **[LOCATION] - Conference:** [# ATTENDANCE] x $[COST] = $[TOTAL]
  - Justification: Present preliminary findings, network with peers

#### Other Direct Costs ($[AMOUNT])

- **Subcontracts/Consultants:** $[COST]
  - [CONSULTANT]: [SPECIFIC EXPERTISE] - $[COST]
- **Publication/Data Costs:** $[COST]

---

## Section 3: Supporting Documents & Certifications

### 3.1 Required Attachments

- **Current & Pending Support:** List of all current and pending funding sources
- **Key Personnel CVs:** 2-page CVs for PI and key personnel
- **Letters of Support:**
  - Customer commitment letters (2-3 min)
  - Partner commitment letters
  - Advisory board member letters
  - University partnership letters (for STTR)
- **Company Information:**
  - Incorporation documents
  - Proof of small business status
  - Business registration
- **References:**
  - Bibliography of prior work
  - Patent references if applicable

### 3.2 Certifications & Compliance

**[Applicant Certification](select applicable):**
- [ ] All information in this proposal is complete and accurate
- [ ] PI is committed to project success
- [ ] Company meets small business requirements
- [ ] No conflict of interest exists
- [ ] Proper accounting and record-keeping procedures in place
- [ ] Funds will be used for authorized purposes only

**For STTR:**
- [ ] University partnership documentation included
- [ ] 40% of research will be conducted at university
- [ ] University commitment letter signed

---

## Section 4: Evaluation Criteria Scorecard

Use this to self-score before submission:

| Criterion | Weight | Self-Score | Notes |
|---|---|---|---|
| **Technical Merit** | 35-40% | [8/10] | Innovation, feasibility, approach |
| **Commercialization Potential** | 30-35% | [8/10] | Market size, competitive advantage, revenue potential |
| **Team Capability** | 15-20% | [9/10] | Experience, credentials, track record |
| **Feasibility & Cost** | 10-15% | [8/10] | 6-month achievability, realistic budget |
| **Overall Reviewer Appeal** | - | [8/10] | Clear writing, compelling narrative |

**Target Score:** 35-40 out of 40 points

---

## Section 5: Pre-Submission Checklist

### Writing Quality
- [ ] Technical narrative is clear and free of jargon
- [ ] All abbreviations are defined on first use
- [ ] Narrative flows logically from problem → solution → impact
- [ ] Font is 12pt minimum, margins are 1" minimum
- [ ] Page count is within limits (15 pages for narrative)
- [ ] Figures and tables are labeled and referenced

### Technical Content
- [ ] Problem statement includes quantified market/technical need
- [ ] Solution is clearly differentiated from existing approaches
- [ ] Detailed timeline with monthly milestones provided
- [ ] Success criteria are specific and measurable
- [ ] Risk analysis addresses key technical challenges
- [ ] Budget aligns with technical approach

### Team & Support
- [ ] Key personnel CVs demonstrate relevant expertise
- [ ] Letters of support from customers/partners included
- [ ] Commitment letters show strong partnerships
- [ ] Advisory board includes recognized experts
- [ ] For STTR: University commitment letter included

### Commercialization
- [ ] Target market is clearly defined
- [ ] Customer validation documented (pilots, LOIs)
- [ ] Competitive advantage articulated
- [ ] Revenue projections are realistic
- [ ] Go-to-market timeline is detailed
- [ ] Phase II commercialization plan outlined

### Compliance & Admin
- [ ] Budget justification supports all costs
- [ ] Indirect rate is correctly applied
- [ ] All required certifications are signed
- [ ] Proposal follows agency formatting requirements
- [ ] PDF is searchable and properly formatted
- [ ] All attachments are included and labeled

---

## Tips for Success

### Writing Strategy
1. **Lead with Impact** - Start each section with the most compelling information
2. **Use Data** - Replace adjectives with specific metrics ("96% accuracy" not "highly accurate")
3. **Tell a Story** - Connect problem → solution → validation → commercialization
4. **Address Concerns Proactively** - Acknowledge limitations and explain mitigations
5. **Make it Memorable** - Use clear language, strong visuals, compelling narratives

### Common Mistakes to Avoid
- Overstating technical readiness or market potential
- Weak or absent commercialization plan
- Unrealistic timeline or budget
- Vague success criteria ("develop prototype" vs. "achieve 95% accuracy")
- Insufficient focus on broader impacts
- Weak team credentials or expertise gaps

### Revision Process
1. **Technical Review** (Week 1-2): Validate approach with technical experts
2. **External Review** (Week 2-4): Get feedback from non-expert readers
3. **Strategic Review** (Week 4): Ensure clear alignment with agency priorities
4. **Final Polish** (Week 5): Format, proofread, validate compliance
5. **Submission** (Week 6): Submit 24 hours before deadline

---

**Created:** [DATE]
**Last Updated:** [DATE]
**Status:** Ready for Customization

