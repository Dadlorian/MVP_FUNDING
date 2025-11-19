# Budget Templates & Justifications for Government Grants

This guide provides realistic budget templates for SBIR Phase I, Phase II, and other federal grants. Includes line-item justifications and common mistakes to avoid.

---

## General Budget Rules

### Key Principles:
1. **Be detailed**: Each line item needs justification
2. **Be realistic**: Overbudgeting raises red flags; underbudgeting questions viability
3. **Match timeline**: Budget duration must align with project scope
4. **Show leverage**: Include cost-sharing and in-kind contributions when advantageous
5. **Avoid common mistakes**:
   - Salaries that don't align with actual time commitment
   - Equipment costs without justification for necessity
   - Travel that doesn't align with technical plan
   - Overhead rates higher than institutional rates
   - Indirect costs not supported by approved rates

### Budget Components:
- **Direct Costs**: Directly attributable to project
  - Personnel (salaries, fringe)
  - Equipment
  - Materials & Supplies
  - Travel
  - Other Direct Costs (subcontracts, consultants, publication)
- **Indirect Costs**: Overhead charged as % of modified total direct costs (F&A rate)

### Fringe Benefit Rates:
- **Small companies**: 25-35% of salary
- **Large companies**: 35-50% of salary
- **Academic institutions**: 25-40% (varies)
- **Non-profits**: 20-35% (varies)

---

## Template 1: NSF SBIR Phase I Budget ($150K)

**Project Duration**: 6 months
**Project Title**: "AI-Powered Anomaly Detection System for Industrial IoT"

### Direct Costs Breakdown

#### Personnel (Total: $72,000)

| Role | Name/Title | % Effort | Annual Salary | 6-Month Cost | Fringe (28%) | Total |
|---|---|---|---|---|---|---|
| Principal Investigator (CEO) | John Smith | 40% | $80,000 | $16,000 | $4,480 | $20,480 |
| Lead Software Engineer | Jane Doe | 80% | $120,000 | $48,000 | $13,440 | $61,440 |
| Part-Time Advisor (Cloud Arch) | Dr. Mike Lee | 10% | $100,000 | $5,000 | $1,400 | $6,400 |
| **TOTAL PERSONNEL** | | | | | | **$88,320** |

**Justification**:
- PI dedicates 40% time to project management and technical direction (typical for startup founders managing other responsibilities)
- Lead engineer at 80% is core technical resource for algorithm development and testing (20% allocated to other company priorities)
- Part-time advisor (10% = ~5 hours/week) provides guidance on cloud architecture and scalability
- Fringe rate of 28% reflects small company rate: health insurance (12%), FICA taxes (7.65%), workers comp (3%), unemployment (2%), other (3.35%)

**Common Mistake to Avoid**:
❌ Listing PI at 100% when they're also running the company
✓ Use realistic effort percentages that don't exceed 100% total

---

#### Equipment (Total: $35,000)

| Item | Qty | Unit Cost | Total | Justification |
|---|---|---|---|---|
| GPU Compute Servers (2x NVIDIA A100) | 2 | $12,000 | $24,000 | Required for training large ML models and testing anomaly detection algorithms. A100 GPUs provide necessary computational power for 6-month development cycle. |
| High-Performance Workstation | 1 | $6,000 | $6,000 | Development workstation for algorithm development and testing. Needed for faster iteration cycles in software development. |
| Network Testing Equipment | 1 | $5,000 | $5,000 | IoT device simulation and network testing equipment to validate system under realistic industrial network conditions. |
| **TOTAL EQUIPMENT** | | | | **$35,000** |

**Justification Requirements**:
- Equipment must be essential for project, not general use
- Cost-benefit analysis (why not rent/lease instead?)
- Equipment remains as company asset post-grant
- Must have useful life > 2 years

**NSF Equipment Policy**:
- Items >$5,000 must be capitalized
- All equipment must be necessary and reasonable
- Preference for purchasing (not leasing) when cost-effective
- Teaching/research equipment preferred over "nice-to-have"

**Common Mistake to Avoid**:
❌ Requesting equipment without tying to specific technical tasks
❌ Requesting office furniture or computers for general use
✓ Tie each piece to specific deliverable (e.g., "GPU servers for training models in Tasks 2.1-2.3")

---

#### Materials & Supplies (Total: $12,000)

| Category | Cost | Justification |
|---|---|---|
| **Software Licenses** | $4,000 | - Cloud computing credits (AWS/GCP): $2,500 for training and testing (estimated 1,000 GPU hours at $2.50/hr)<br>- ML development tools and libraries licensing: $1,000 for enterprise support and tools<br>- Data management software: $500 for database and analytics tools |
| **Hardware/Connectivity** | $3,500 | - Industrial IoT sensor kits for testing (50 sensors @ $40 ea): $2,000<br>- Network cables, connectors, installation: $1,000<br>- Testing/measurement equipment supplies: $500 |
| **Data & Datasets** | $2,500 | - Industrial IoT benchmark datasets (labeled): $1,500<br>- Real-world industrial data licensing: $1,000 (critical for validation) |
| **Documentation & Reporting** | $1,000 | - Technical documentation tools: $400<br>- Data visualization and presentation tools: $300<br>- Report preparation and publication costs: $300 |
| **Other Materials** | $1,000 | - Contingency for unforeseen testing materials: $1,000 (10% buffer) |
| **TOTAL MATERIALS** | | **$12,000** |

**Key Points**:
- Each line item must connect to technical approach
- Cloud computing costs must show calculation (hours × rate)
- Data licensing is often missed but critical for validation
- Contingency is acceptable (5-10% for exploratory research)

**Common Mistake to Avoid**:
❌ Vague "supplies" budget without itemization
❌ Office supplies, furniture, or general operational costs
✓ Itemize all costs and show calculation methodology

---

#### Travel (Total: $6,000)

| Activity | Cost | Justification |
|---|---|---|
| **Conference Presentation** | $2,500 | Travel to ACM Conference on Machine Learning (Detroit, June 2024):<br>- Airfare (economy): $400<br>- Hotel (4 nights @ $150): $600<br>- Per diem (4 days @ $75): $300<br>- Conference registration: $600<br>- Ground transportation: $200<br>- Poster design/printing: $400<br>**Purpose**: Present preliminary findings, obtain peer feedback, build relationships with potential customers |
| **Industrial Partner Visits** | $2,000 | Two site visits to manufacturing partner facilities (Months 2 and 5):<br>- Airfare (2 trips, economy): $800<br>- Hotel (4 nights @ $150): $600<br>- Ground transportation: $400<br>- Per diem: $200<br>**Purpose**: Validate system design with real-world industrial data, gather requirements, assess scalability needs |
| **Technical Workshop** | $1,500 | NSF SBIR Awardee Workshop (Washington DC, Month 1):<br>- Airfare: $400<br>- Hotel (2 nights @ $150): $300<br>- Per diem: $150<br>- Registration: $600<br>**Purpose**: Learn from other awardees, understand compliance/reporting requirements |
| **TOTAL TRAVEL** | | **$6,000** |

**Travel Budget Guidelines**:
- Document specific events and dates
- Show number of people traveling and estimated costs
- Justify each trip (why it advances the project?)
- Use per diem rates appropriate to location
- Should not exceed 5-10% of budget for Phase I

**Acceptable Reasons for Travel**:
✓ Conference presentation (demonstrates dissemination)
✓ Customer/partner visits (validates market need)
✓ Technical collaborations with universities
✓ Required conferences (SBIR awardee meetings)
✓ Client demonstrations

**Unacceptable Travel**:
❌ General networking (vague)
❌ Investor meetings (not research related)
❌ Excessive international travel
❌ Personal development seminars

**Common Mistake to Avoid**:
❌ Including travel without clear project connection
✓ Tie each trip to specific deliverable or milestone

---

#### Other Direct Costs (Total: $8,000)

| Category | Cost | Justification |
|---|---|---|
| **Subcontracts** | $4,000 | University partner (State Tech University) for algorithm verification:<br>- Dr. Sarah Johnson leads statistical analysis of anomaly detection accuracy<br>- 100 hours @ $40/hr<br>- Deliverable: Validation report confirming algorithm meets performance targets<br>- Reduces cost vs. hiring full-time statistician<br>- Leverages academic expertise in statistical rigor |
| **Consultant Services** | $2,500 | Manufacturing process expert consultation:<br>- Consultant: Tom Wilson (Lean Manufacturing Expert)<br>- Rate: $150/hour<br>- Duration: ~17 hours (3 sessions of 4-6 hours each)<br>- Deliverable: Requirements assessment and deployment strategy<br>- Critical for understanding production environment |
| **Publication/Dissemination** | $800 | - Technical paper preparation and submission: $300<br>- Patent application filing (provisional): $500<br>**Purpose**: Protects IP, disseminates findings |
| **Communications & Coordination** | $700 | - Monthly progress reporting and documentation tools: $300<br>- Video conferencing and collaboration subscriptions: $200<br>- Grant reporting software: $200 |
| **TOTAL OTHER DIRECT COSTS** | | **$8,000** |

**Subcontract Guidance**:
- Must be justifiable (expertise not available in-house)
- Should include deliverables
- Subcontractor budgets must follow same detail level
- Verify subcontractor eligibility (small business requirements)
- Letter of commitment from subcontractor required

**Consultant Guidance**:
- Distinguish between consultant (specialized expertise) vs. employee
- Show hourly rate and estimated hours
- Name consultant or describe qualifications
- Consultant rate should be reasonable for industry
- No markup allowed (direct cost)

---

#### Indirect Costs / Facilities & Administration (Total: $18,480)

**Calculation**:
- Modified Total Direct Costs (MTDC): $72,000 (Personnel)
  + $35,000 (Equipment)
  + $12,000 (Materials)
  + $6,000 (Travel)
  + $8,000 (Other Direct Costs)
  = $133,000 MTDC
- However, equipment is usually excluded from MTDC for F&A calculation
- Negotiated Indirect Cost Rate: 22% of ($133,000 - $35,000) = 22% × $98,000 = $21,560

**Alternative Budget Summary (if using simplified rate)**:
- Direct Costs: $131,520
- Indirect Costs (22% of $131,520): $28,934
- **Total Budget: $160,454**

*Note: Actual calculations depend on your organization's federally-negotiated indirect cost rate. This example assumes 22%, which is typical for small companies.*

**Finding Your F&A Rate**:
- Check SAM.gov profile (lists negotiated rate)
- New organizations: start with provisional rate (typically 25-30%)
- Non-profit hospitals/universities: often 50-60%
- Small for-profit companies: 20-35%

**Key Principle**: You can only charge what you have negotiated in your Cost Accounting Standards (CAS) or what's allowed by the specific agency if no negotiated rate exists.

---

### NSF Phase I Budget Summary

| Category | Amount | % of Total |
|---|---|---|
| Personnel | $88,320 | 52% |
| Equipment | $35,000 | 21% |
| Materials & Supplies | $12,000 | 7% |
| Travel | $6,000 | 4% |
| Other Direct Costs | $8,000 | 5% |
| Indirect Costs (22%) | $21,480 | 13% |
| **TOTAL** | **$170,800** | **100%** |

**Project Narrative Connection**:
- Budget supports 6-month feasibility study
- Covers development of proof-of-concept (not production system)
- Enables validation with industrial partners
- Positions company for larger Phase II award ($500K-$750K)
- All budget items directly support Technical Approach milestones

---

## Template 2: NIH SBIR Phase II Budget ($1.2M, 24 months)

**Project Duration**: 24 months
**Project Title**: "Diagnostic Biomarker Panel for Early Alzheimer's Detection"

### Phase II Budget Overview

| Year | Direct Costs | Indirect Costs | Total |
|---|---|---|---|
| **Year 1** | $580,000 | $127,600 (22%) | $707,600 |
| **Year 2** | $520,000 | $114,400 (22%) | $634,400 |
| **TOTAL (24 months)** | **$1,100,000** | **$242,000** | **$1,342,000** |

### Detailed Year 1 Budget

#### Personnel (Total: $380,000)

| Role | % Effort | Annual Salary | Cost Year 1 | Fringe (30%) | Total |
|---|---|---|---|---|---|
| Principal Investigator/Founder | 50% | $120,000 | $60,000 | $18,000 | $78,000 |
| Director of Operations (new hire) | 100% | $95,000 | $95,000 | $28,500 | $123,500 |
| Laboratory Manager | 100% | $65,000 | $65,000 | $19,500 | $84,500 |
| Research Scientist (new hire) | 100% | $75,000 | $75,000 | $22,500 | $97,500 |
| Lab Technician (0.5 FTE existing, 0.5 FTE new) | 100% | $50,000 | $50,000 | $15,000 | $65,000 |
| **TOTAL PERSONNEL** | | | | | **$448,500** |

**Key Differences from Phase I**:
- Team expansion (hiring 2 full-time researchers)
- Higher fringe rate (30% vs. 28% in Phase I) due to larger team and benefits expansion
- PI can reduce effort from Phase I (50% Phase II vs. 40% Phase I) as team matures
- Operations director hired to handle regulatory and manufacturing aspects

**NIH-Specific Notes**:
- NIH allows salary increases of ~2-3% annually
- Expects team growth from Phase I to Phase II
- Personnel is largest budget category (typically 40-60% of Phase II)

---

#### Equipment (Total: $200,000)

| Item | Cost | Justification |
|---|---|---|
| **Bioanalytical Equipment** | | |
| - HPLC-MS/MS System | $120,000 | High-performance liquid chromatography coupled with mass spectrometry for biomarker quantification and validation. Essential for Phase II clinical validation work. |
| - Centrifuge (high-capacity, refrigerated) | $25,000 | Processes large sample volumes from clinical cohorts (1000+ samples in Year 1). |
| **Laboratory Infrastructure** | | |
| - BioLab equipment suite | $35,000 | Incubators, microbiology equipment, temperature-controlled storage for sample handling. |
| - Data management systems & LIMS | $20,000 | Laboratory Information Management System for tracking 1000+ clinical samples, maintaining chain of custody, managing assay results. Critical for FDA submission. |
| **TOTAL EQUIPMENT** | | **$200,000** |

**Phase II Equipment Notes**:
- Phase II justifies higher equipment costs (feasibility proven, now validating at scale)
- Equipment supports clinical studies (larger sample sizes than Phase I)
- LIMS is critical for regulatory compliance (FDA requirement for submission)

---

#### Materials & Supplies (Total: $150,000)

| Category | Year 1 Cost | Justification |
|---|---|---|
| **Clinical Reagents & Kits** | $70,000 | Biomarker reagents, calibration standards, QC materials for developing and validating assay in 1,000+ clinical samples. Includes positive/negative controls. |
| **Clinical Sample Procurement** | $50,000 | Procure plasma samples from clinical cohort (500 patient samples + 200 healthy controls): cost includes collection, processing, storage. Estimated $60-80/sample. Partnerships with academic medical centers. |
| **Laboratory Supplies** | $18,000 | Pipette tips, tubes, consumables, PCR plates, etc. for high-volume sample processing. |
| **Quality Control/Assay Validation** | $12,000 | Reference materials, validation sample sets, proficiency testing materials (required for clinical-grade assay). |
| **TOTAL MATERIALS** | | **$150,000** |

**Clinical Sample Cost Notes**:
- Highly variable by disease and sample type
- Biobanks charge $50-150+ per sample
- Patient recruitment fees additional
- Budget reflects moderate-cost sample procurement
- Should account for collection, shipping, storage

---

#### Travel (Total: $40,000)

| Purpose | Cost | Justification |
|---|---|---|
| **Regulatory Meetings (3 trips to FDA, DC)** | $12,000 | Meetings with FDA to confirm clinical validation pathway and analytical validation requirements. 3 trips × $4,000 per trip (airfare, hotel, per diem). Critical for understanding submission requirements early. |
| **Clinical Partner Site Visits (4 visits)** | $14,000 | Visits to hospital/academic partners recruiting patients for clinical studies. 4 sites × $3,500 per visit. Necessary for protocol development and site oversight. |
| **Scientific Conferences (2 presentations)** | $10,000 | Alzheimer's Association conference + American Neurological Association conference. Present preliminary validation data, build relationships with neurologists. 2 conferences × $5,000 each. |
| **Laboratory Standards Workshop** | $4,000 | AACC/CAP laboratory standards and quality training (Washington DC, Month 18). Ensures lab team understands quality/regulatory requirements. |
| **TOTAL TRAVEL** | | **$40,000** |

**Phase II Travel Increase**:
- FDA meetings are critical (new regulatory contacts)
- Multiple clinical sites require travel for oversight
- Higher visibility at major conferences (2-3 presentations)
- Team member travel increases with team size

---

#### Subcontracts & Consultants (Total: $60,000)

| Item | Year 1 Cost | Justification |
|---|---|---|
| **Clinical Research CRO Contract** | $35,000 | Engaged INC Research (clinical CRO) for Phase 2 study design and protocol development. Ensures rigorous study design, regulatory compliance, proper statistical power. Expert consultation: $35,000 for 4 months of study design work (protocol, CRF development, statistical analysis plan). |
| **Regulatory Affairs Consultant** | $15,000 | Expert guidance on FDA submission strategy, analytical validation requirements, pre-submission meeting preparation. Consultant rate: $250/hr × 60 hours. Prevents costly regulatory missteps. |
| **Clinical Pathologist Advisor** | $10,000 | Part-time medical director role. Provides clinical perspective, validates clinical relevance of biomarkers. Rate: $200/hr × 50 hours. |
| **TOTAL SUBCONTRACTS** | | **$60,000** |

**Phase II Subcontracting Strategy**:
- CROs for complex clinical studies (expensive but expert)
- Regulatory consultants essential for FDA pathway
- Clinical advisors ensure medical validity
- Avoids hiring expensive consultants full-time

---

#### Year 1 Direct & Indirect Costs Summary

| Category | Amount | % of Total |
|---|---|---|
| Personnel | $448,500 | 45% |
| Equipment | $200,000 | 20% |
| Materials & Supplies | $150,000 | 15% |
| Travel | $40,000 | 4% |
| Subcontracts/Consultants | $60,000 | 6% |
| **Total Direct Costs** | **$898,500** | **90% |
| Indirect Costs (22% of MTDC) | $127,600 | 10% |
| **Year 1 Total** | **$1,026,100** | |

*Note: MTDC calculation excludes equipment and subcontracts per NIH rules*

---

### Detailed Year 2 Budget

**Year 2 approach**: Focus shifts to clinical validation and manufacturing scale-up.

#### Personnel Year 2 (Total: $350,000)

| Role | % Effort | Salary Adjustment | Cost |
|---|---|---|---|
| PI | 40% | 3% increase | $64,800 |
| Director of Operations | 100% | 3% increase | $127,030 |
| Laboratory Manager | 100% | 3% increase | $87,045 |
| Research Scientist | 100% | 3% increase | $100,425 |
| Lab Technician (now 1.0 FTE) | 100% | 3% increase | $67,250 |
| Manufacturing Engineer (new hire) | 100% | $85,000 | $85,000 |
| **TOTAL PERSONNEL** | | | **$431,550** |

**Year 2 Adjustments**:
- All salaries increase 3% (standard COLA)
- New manufacturing engineer hired (Month 8, Year 2)
- Fringe increases to 32% due to manufacturing engineer benefits (different tier)

---

#### Equipment Year 2 (Total: $100,000)

| Item | Cost | Justification |
|---|---|---|
| Manufacturing-scale equipment | $80,000 | Semi-automated assay platform for clinical lab implementation. Enables scaling from research assay to clinical diagnostic test. |
| Software and automation | $20,000 | Manufacturing execution system (MES) and ELN software for GMP compliance documentation. |

---

#### Materials & Supplies Year 2 (Total: $120,000)

| Category | Cost | Justification |
|---|---|---|
| Clinical samples (larger cohort) | $70,000 | Expand to 1,500 total samples (1,000 Alzheimer's, 500 controls, plus validation cohort). |
| Manufacturing materials | $30,000 | Assay kit components for pilot manufacturing runs (1000 test kits). |
| Quality assurance/regulatory | $20,000 | Additional QC materials, proficiency testing, stability testing. |

---

#### Travel Year 2 (Total: $35,000)

Similar to Year 1 but adjusted for:
- Multiple FDA pre-submission meetings (regulatory package development)
- Extended clinical site visits (patient recruitment oversight)
- Manufacturing scale-up facility visits
- Society/conference presentations of clinical validation data

---

#### Subcontracts Year 2 (Total: $80,000)

| Item | Cost | Justification |
|---|---|---|
| Biostatistics consulting | $25,000 | Statistical analysis of 1,500-patient clinical dataset. Analysis plan development, manuscript preparation. |
| Manufacturing partner/consultant | $35,000 | Transition from research assay to GMP-compliant manufacturing. Includes process validation, documentation. |
| Quality/Regulatory consulting | $20,000 | Final FDA submission preparation and strategies. |

---

#### Year 2 Total

| Category | Amount |
|---|---|
| Personnel | $431,550 |
| Equipment | $100,000 |
| Materials | $120,000 |
| Travel | $35,000 |
| Subcontracts | $80,000 |
| **Total Direct Costs** | **$766,550** |
| Indirect Costs (22%) | $168,641 |
| **Year 2 Total** | **$935,191** |

---

### 24-Month Project Total

| Year | Direct Costs | Indirect | Total |
|---|---|---|---|
| Year 1 | $898,500 | $127,600 | $1,026,100 |
| Year 2 | $766,550 | $168,641 | $935,191 |
| **TOTAL** | **$1,665,050** | **$296,241** | **$1,961,291** |

**Adjusted to match NIH maximum**: If award capped at $1.2M Phase II, budget would be scaled proportionally (~61% of above plan), focusing on:
- Phase 1: Year 1 ($626,741)
- Phase 2: Year 2 (~$600K)

---

## Template 3: DoD SBIR Phase II Budget ($2M, 24 months)

**Project Duration**: 24 months
**Project Title**: "Advanced Machine Learning for Autonomous Vehicle Target Detection"

### Budget Overview

| Year | Direct Costs | Indirect Costs | Total |
|---|---|---|---|
| **Year 1** | $1,050,000 | $157,500 (15% - DoD rate) | $1,207,500 |
| **Year 2** | $950,000 | $142,500 (15%) | $1,092,500 |
| **TOTAL (24 months)** | **$2,000,000** | **$300,000** | **$2,300,000** |

*Note: DoD Phase II are larger awards than NIH; budgets reflect higher team costs and equipment for defense applications*

### Key Differences from NIH Phase II:

1. **Larger equipment budgets** ($400K vs. $200K) for military-grade testing systems
2. **Higher travel** ($80K vs. $40K) for multiple military base visits
3. **Lower indirect rate** (15% DoD vs. 22% NIH) - DoD uses simplified rates
4. **Classified work considerations** - budget may include secure facility access
5. **Subcontract partnerships** with DoD contractors/integrators

### Detailed Year 1 Budget

#### Personnel (Total: $520,000)

| Role | % Effort | Annual Salary | Year 1 Cost | Fringe (32%) | Total |
|---|---|---|---|---|---|
| Principal Investigator (CEO) | 50% | $130,000 | $65,000 | $20,800 | $85,800 |
| VP Engineering | 100% | $140,000 | $140,000 | $44,800 | $184,800 |
| ML Algorithm Developer (2 FTE) | 100% each | $130,000 | $260,000 | $83,200 | $343,200 |
| Field Testing Engineer | 100% | $100,000 | $100,000 | $32,000 | $132,000 |
| **TOTAL PERSONNEL** | | | | | **$745,800** |

**DoD Personnel Ratios**:
- Higher engineering salaries (defense industry standard)
- Strong VP-level leadership (DoD expects mature teams)
- Multiple developers for complex algorithms
- Field/testing engineer (not typical in NIH; reflects military validation needs)

---

#### Equipment (Total: $400,000)

| Item | Cost | Justification |
|---|---|---|
| **Vehicle Platform & Sensors** | $200,000 | Autonomous vehicle test platform (modified pickup truck) with LiDAR, radar, camera systems. Required for real-world testing of target detection algorithms on military test track. |
| **High-Performance GPU Clusters** | $120,000 | Multiple NVIDIA A100 GPU clusters for training large neural networks on classified DoD datasets. Necessary for processing military scenario data. |
| **Secure Computing Environment** | $50,000 | Facility access, secure enclave for classified data handling, secure network infrastructure. |
| **Testing & Diagnostic Equipment** | $30,000 | Military standard testing equipment, radar/sensor validation systems. |
| **TOTAL EQUIPMENT** | | **$400,000** |

**DoD Equipment Notes**:
- Vehicle platforms justified for military testing
- Secure infrastructure costs higher (IT security requirements)
- Equipment must meet military standards/specifications
- Some equipment may need DOD security certification

---

#### Materials & Supplies (Total: $100,000)

| Category | Cost | Justification |
|---|---|---|
| **Test Data & Scenarios** | $40,000 | Access to DoD test datasets (classified and unclassified scenarios). Subscription to military test environments. |
| **Algorithm Development Materials** | $30,000 | Cloud computing credits for neural network training, development tools, validation datasets. |
| **Testing & Validation** | $20,000 | Consumables, testing materials for field validation trials. |
| **Documentation & Technical** | $10,000 | Security compliance documentation, technical reports, classified document handling. |
| **TOTAL MATERIALS** | | **$100,000** |

---

#### Travel (Total: $80,000)

| Purpose | Cost | Justification |
|---|---|---|
| **DoD Testing Facility Visits (8 trips)** | $40,000 | Visits to Fort Hood, NTC, MCRTC, and other military test sites for algorithm validation and integration testing. 8 trips × $5,000/trip. Essential for understanding military operational requirements and conducting field tests. |
| **Defense Contractor Integration Meetings** | $20,000 | Meetings with prime contractors (Lockheed, Boeing, etc.) exploring integration pathways. 4 meetings × $5,000. Critical for Phase IIB transition. |
| **Technology Conferences** | $12,000 | IEEE, SPIE defense technology conferences. 2 conferences × $6,000 for classified paper presentation. |
| **Government Technical Forums** | $8,000 | DARPA pitch events, Army AI forums, Navy innovation seminars. |
| **TOTAL TRAVEL** | | **$80,000** |

**DoD Travel Premium**:
- Military base visits require advance security clearance processing
- Per diem at higher military lodging rates
- Increased frequency (military customer engagement critical)

---

#### Subcontracts (Total: $150,000)

| Item | Cost | Justification |
|---|---|---|
| **University Research Partner** | $70,000 | Partnership with CMU Robotics Lab for advanced ML algorithm development. Specializes in adversarial robustness (critical for military applications). Subcontract for 12 months of algorithm research. |
| **Defense Integration Consultant** | $50,000 | Former DoD systems engineer consultant to guide integration with military systems architecture. Hourly rate: $250/hr × 200 hours. Ensures compliance with military technical standards. |
| **Cybersecurity Assessment** | $30,000 | Third-party penetration testing and security assessment. Validates system security against military-grade threats. Required for DoD certification. |
| **TOTAL SUBCONTRACTS** | | **$150,000** |

---

#### Other Direct Costs (Total: $25,000)

| Category | Cost | Justification |
|---|---|---|
| Publications & IP | $10,000 | Patent filings (3 provisional patents @ $3K each), unclassified technical papers. |
| Communications | $8,000 | Secure communications tools, encrypted collaboration platforms for classified work. |
| Contingency | $7,000 | 0.7% contingency for testing uncertainties. |
| **TOTAL OTHER** | | **$25,000** |

---

#### Year 1 Cost Summary

| Category | Amount | % of Total |
|---|---|---|
| Personnel | $745,800 | 50% |
| Equipment | $400,000 | 27% |
| Materials | $100,000 | 7% |
| Travel | $80,000 | 5% |
| Subcontracts | $150,000 | 10% |
| Other | $25,000 | 2% |
| **Total Direct Costs** | **$1,500,800** | **100%** |
| Indirect Costs (15% DoD rate) | $225,120 | |
| **Year 1 Total** | **$1,725,920** | |

---

### Year 2 Budget (Summary)

Year 2 focuses on:
- Field testing and validation (less development)
- Transition planning to military integration
- Security certification
- Technical documentation for Phase IIB proposal

**Reduced personnel**: Some key developers transition to Phase IIB contracts
**Increased travel**: More government facility visits and transition meetings
**Different equipment**: Less computing, more testing/validation gear

Year 2 Total: ~$1,092,500 (more travel-heavy, less personnel expansion)

---

## Template 4: EPA SBIR Phase II Budget ($300K, 24 months)

**Project Duration**: 24 months
**Project Title**: "Real-Time Water Quality Monitoring with AI Analytics"

This is a smaller federal award, typical for EPA. Budget is leaner than DoD/NIH but still professional.

### Budget Overview

| Year | Direct Costs | Indirect | Total |
|---|---|---|---|
| **Year 1** | $135,000 | $22,500 (20%) | $157,500 |
| **Year 2** | $120,000 | $20,000 (20%) | $140,000 |
| **TOTAL** | **$255,000** | **$42,500** | **$297,500** |

*Note: EPA Phase II has lower budget than other agencies; companies must be lean and focused*

### Detailed Budget (24 months)

#### Personnel (Total: $140,000)

| Role | FTE | Total Cost | Notes |
|---|---|---|---|
| Principal Investigator (Founder) | 0.4 FTE | $48,000 | 40% time (company also does other work). $120K salary annualized. |
| Lead Software Engineer | 0.8 FTE | $64,000 | 80% dedicated. $80K salary annualized. |
| Environmental Science Consultant | 0.2 FTE | $16,000 | 20% (part-time advisor). $80K hourly equivalent. |
| **TOTAL PERSONNEL** | | **$128,000** (+30% fringe = $166,400) | |

*Including fringe at 30% = $128K + $38,400 = $166,400*

---

#### Equipment (Total: $45,000)

| Item | Cost | Justification |
|---|---|---|
| Water quality sensors (set of 10) | $20,000 | Multi-parameter sensors for field deployment. Enables real-world validation in rivers/lakes. |
| Edge computing hardware | $15,000 | Ruggedized IoT gateways for on-site data processing and ML inference. |
| Lab testing equipment | $10,000 | Validation equipment to cross-check sensor readings against lab standards. |

---

#### Materials & Supplies (Total: $25,000)

| Item | Cost | Justification |
|---|---|---|
| Cloud computing/hosting | $10,000 | Cloud infrastructure for ML model training and data storage. |
| Testing chemicals & supplies | $8,000 | Water samples, reagents for calibration and validation. |
| Software tools & licenses | $4,000 | Development tools, APIs, data management software. |
| Documentation | $3,000 | Technical reports, user guides, training materials. |

---

#### Travel (Total: $15,000)

| Purpose | Cost | Notes |
|---|---|---|
| EPA meetings & site visits | $8,000 | 2 visits to EPA regional offices + field site visits. |
| Wastewater treatment facility demonstrations | $5,000 | Customer site visits for validation and sales. |
| Conference presentation | $2,000 | Water industry conference to present results. |

---

#### Subcontracts/Consultants (Total: $20,000)

| Item | Cost | Justification |
|---|---|---|
| University environmental lab partnership | $15,000 | Data validation and statistical analysis. |
| Regulatory compliance consultant | $5,000 | Guidance on EPA reporting requirements. |

---

#### Other Direct Costs (Total: $5,000)

- Publications/IP: $2,000
- Contingency: $3,000

---

#### Total EPA Phase II Budget

| Category | Year 1 | Year 2 | Total |
|---|---|---|---|
| Personnel (+ fringe) | $90,000 | $85,000 | $175,000 |
| Equipment | $30,000 | $15,000 | $45,000 |
| Materials | $14,000 | $11,000 | $25,000 |
| Travel | $8,000 | $7,000 | $15,000 |
| Subcontracts | $12,000 | $8,000 | $20,000 |
| Other | $3,000 | $2,000 | $5,000 |
| **Direct Costs** | **$157,000** | **$128,000** | **$285,000** |
| Indirect (20%) | $26,300 | $21,500 | $47,800 |
| **Total** | **$183,300** | **$149,500** | **$333,000** |

---

## Budget Writing Best Practices

### 1. Align Budget to Technical Plan
Every budget line must connect to a specific task/deliverable in your technical narrative:
- Task 1: Algorithm Development → Personnel (engineer), Equipment (GPUs), Materials (cloud)
- Task 2: Field Validation → Travel (site visits), Materials (sensors), Subcontracts (university partner)

### 2. Justification Quality

**Poor Justification**: "Salary $100K for engineer"
**Good Justification**: "Lead software engineer salary: $100K/year for 12 months = $100K. Engineer will develop the core ML anomaly detection algorithm (Tasks 2.1-2.4) and conduct integration testing with industrial partners (Task 3.1)."

### 3. Common Budget Mistakes to Avoid

❌ **Overhead Loading**: Charging general office overhead as project cost
✓ **Do This**: Only charge direct project-specific costs; let indirect rate cover overhead

❌ **Personnel Math Errors**: Percentages that exceed 100%, mismatched salary/effort
✓ **Do This**: Create clear chart showing all employees and effort % across projects

❌ **Vague Equipment**: "Computers for development" without specific justification
✓ **Do This**: Specify GPU model, processor, memory; tie to technical requirements

❌ **Inflated Salaries**: Above-market compensation claiming project work
✓ **Do This**: Use company's actual salary ranges; back up with offer letters if audited

❌ **Missing Fringe**: Underbudgeting employee costs
✓ **Do This**: Always include fringe rate (25-35% typical); cite your negotiated rate

❌ **No Travel Justification**: "Travel" with no specific trips listed
✓ **Do This**: List specific conference, government meeting, customer visit

❌ **Equipment as Supplies**: Putting computer equipment in supplies to avoid cap
✓ **Do This**: Equipment >$5,000 = Equipment category; <$5,000 = Supplies

### 4. Auditing Red Flags

Reviewers watch for:
- Salary rates significantly above market
- Equipment that doesn't connect to project needs
- Travel that seems like tourism
- Indirect costs exceeding federal negotiated rate
- Personnel effort totaling >100%
- Budgets with no variance by activity

### 5. Budget Realism Checks

**Sanity Test 1**: Does personnel budget align with team size?
- $1M budget should support 3-4 FTE, not 8-10 FTE

**Sanity Test 2**: Does equipment exceed 30% of total for research?
- Phase I: 15-25% equipment typical
- Phase II: 15-35% equipment typical (depends on field)
- Equipment >40% raises questions

**Sanity Test 3**: Does timeline support deliverables?
- 6-month Phase I: can achieve feasibility, not full development
- 24-month Phase II: can achieve validation, not production-ready deployment

**Sanity Test 4**: Does this budget attract Phase IIB/follow-on funding?
- Phase I → Phase II: company should demonstrate capability
- Phase II → Phase IIB: should have clear path to commercialization

---

## Budget Defense (During Review)

When submitting, be prepared to defend:

1. **Salary justification**:
   - "Our VP Engineering salary of $140K is market-rate for aerospace industry (we can cite Bureau of Labor Statistics data)"

2. **Equipment necessity**:
   - "GPU servers are essential because our ML models require 48-hour training runs on high-performance hardware. Renting from cloud would cost $50K+ and wouldn't provide needed control/security"

3. **Staffing ratios**:
   - "Our team of 4 engineers is appropriate for a 6-month Phase I focused on algorithm development and MVP building. We're not hiring non-technical staff"

4. **Timeline realism**:
   - "6-month Phase I allows proof-of-concept (not production). We're focusing on core algorithm and demonstration with one partner, Phase II will do broader validation"

---

## Quick Budget Guides by Award Size

### $100K-$200K Award (Typical Phase I)
- 1-2 FTE personnel (~50-60% of budget)
- Equipment $20K-$40K
- Travel $5K-$10K
- Lean, focused team

### $500K-$1M Award (Typical Phase II)
- 2-3 FTE personnel (~40-50% of budget)
- Equipment $80K-$150K
- Team expansion for validation
- Increased travel/collaboration

### $2M+ Award (DoD, NIH Phase IIB, large grants)
- 3-5 FTE personnel (~35-45% of budget)
- Equipment $200K-$500K
- Manufacturing/scale-up focus
- Significant subcontractor partnerships

---

**Key Insight**: Your budget tells a story. It should show:
1. A focused team with right expertise
2. Equipment that's necessary and proportional
3. A timeline that's realistic for stated deliverables
4. Leverage from partnerships (subcontracts)
5. Clear path to Phase II (Phase I) or commercialization (Phase II)

A weak budget will sink a strong proposal. Invest time in making it detailed, justified, and defensible.
