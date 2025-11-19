# Grant Panel Interview Guide: Q&A Preparation for International Reviewers

## Overview
Comprehensive guide for preparing research teams for grant panel interviews, remote presentations, and negotiations with international funding bodies. Includes common questions, expert responses, and strategic communication approaches.

---

## 1. Pre-Interview Preparation Strategy

### Understanding the Audience

**Reviewer Types You'll Encounter**:

1. **Scientific Reviewers** (60% of panel)
   - Deep expertise in your field
   - Evaluating: Technical soundness, innovation, feasibility
   - Want to understand: Novel methodological approaches, advancement over SOTA
   - Red flags for them: Unclear methodology, unrealistic timelines, weak validation plan

2. **Interdisciplinary Reviewers** (20% of panel)
   - Related but not identical expertise
   - Evaluating: Broader impact, interdisciplinary value, communication clarity
   - Want to understand: Why your work matters beyond narrow field
   - Red flags: Over-specialized jargon, limited scope, narrow impact

3. **Lay Reviewers or Policy Representatives** (10-20% of panel)
   - Non-scientist stakeholders (policy makers, industry representatives)
   - Evaluating: Societal impact, translation potential, policy relevance
   - Want to understand: Real-world benefits, commercialization path, stakeholder engagement
   - Red flags: No clear real-world application, unclear benefits, no end-user engagement

### Pre-Interview Checklist

- [ ] **Review proposal thoroughly**: Know every section by memory, not by reading
- [ ] **Prepare for criticisms**: Anticipate weaknesses reviewers might identify
- [ ] **Practice delivery**: Rehearse presentation 5-10 times until smooth
- [ ] **Time management**: Practice staying within time limits
- [ ] **Team coordination**: Decide who answers what category of questions
- [ ] **Visual aids**: Prepare backup slides (if allowed) for complex concepts
- [ ] **Technical setup**: Test video conferencing, screen sharing, internet connection
- [ ] **Dress code**: Research program norms (formal vs. business casual)
- [ ] **Documentation**: Bring printed copies of proposal, budget, team CVs
- [ ] **Energy management**: Plan breaks, hydration, light snacks before interview

---

## 2. Common Reviewer Questions by Category

### A. Scientific Rigor & Innovation

#### Q1: "What is genuinely novel about your approach? How does it advance beyond current state-of-the-art?"

**Why reviewers ask**: Differentiating truly innovative proposals from incremental improvements
**What they're evaluating**: Whether funding represents good use of scarce resources

**Strategy for Answer**:
1. Name the specific innovation (e.g., "Integration of X and Y in a way that hasn't been done")
2. Contrast with existing approaches:
   - Current approach: [Description]
   - Its limitations: [Specific gaps it doesn't address]
   - Our innovation: [How we overcome those gaps]
   - Expected advancement: [Quantitative/qualitative improvement]
3. Provide concrete example: "Unlike Smith et al. (2022) who achieved 85% accuracy, our approach uses [method] to target 95% through [innovation]"

**Example Response** (Medical AI):
"The innovation is three-fold. First, we integrate multi-modal data [imaging + genomics] in a single model, whereas current methods use single modalities. Second, we employ federated learning—allowing hospitals to contribute data without sharing raw patient information—addressing the privacy barrier that has limited dataset size. Third, we develop an interpretability framework that identifies which features drive predictions, enabling clinicians to trust and validate the model's reasoning. The expected outcome: achieving diagnostic accuracy of 97% compared to current best-in-class of 91%, while maintaining patient privacy compliance with GDPR. This represents a genuine methodological advancement, not just incremental improvement."

**Common Pitfalls to Avoid**:
- Being too granular in technical detail (reviewers get lost)
- Claiming novelty without sufficient evidence
- Positioning innovation as "combining A + B" when this has been done before
- Failing to quantify the advancement

---

#### Q2: "How do you know your approach will actually work? What's your evidence?"

**Why reviewers ask**: Distinguishing between speculative ideas and feasible projects
**What they're evaluating**: Risk profile—is this a proof-of-concept or likely to succeed?

**Strategy for Answer**:
1. Refer to preliminary data: "We have preliminary results showing..."
2. Explain validation approach: "Our methodology is adapted from [established method] but applied to [new domain]"
3. Acknowledge risks: "The main risk is [X], which we mitigate by [approach]"
4. Describe contingency: "If [scenario] occurs, we pivot to [alternative approach]"

**Example Response** (Climate Science):
"We have two years of preliminary data from Arctic sites showing consistent acidification trends. Our modeling approach uses established oceanographic models—tested and validated in 50+ prior studies—applied to our specific geographic region and timescale. We're not inventing new methodology; we're applying proven techniques to answer a specific question where current data is insufficient. Our risk: if unforeseen oceanographic events occur, we have contingency sampling protocols. Our team has 15 years combined experience with Arctic systems. This isn't high-risk speculation; it's a well-grounded extension of existing science."

**Key Points**:
- Distinguish between innovation (new technique) and risk (unpredictable outcome)
- Show you've done homework: Know what's been tried, what worked, what failed
- Demonstrate you've thought through failure modes

---

#### Q3: "Your methodology section mentions [technique]. Why that one instead of [alternative]?"

**Why reviewers ask**: Assessing whether you've done due diligence in methodological choices
**What they're evaluating**: Scientific judgment, awareness of alternatives, justification for choices

**Strategy for Answer**:
1. Briefly acknowledge the alternative: "Yes, [technique] is also valid..."
2. Compare on relevant dimensions:
   - Accuracy/sensitivity: [Our technique] achieves X vs. Y for alternative
   - Feasibility: [Our technique] is compatible with our resources
   - Timescale: [Our technique] fits our project timeline
   - Complementarity: [Our technique] pairs well with other methods in project
3. Conclude: "We chose [technique] because [primary reason]"

**Example Response**:
"We considered both RNA-seq and single-cell RNA-seq. Single-cell would provide higher resolution data, but requires specialized equipment [€200k] that would consume 15% of our budget versus 4% for bulk RNA-seq. Given our focus on identifying population-level transcriptomic changes rather than rare cell types, bulk RNA-seq provides sufficient resolution at substantially lower cost. We're not claiming it's technically superior; we're claiming it's optimal for our specific research question and resource constraints."

**Common Pitfalls**:
- Defensiveness ("We chose this because we're right")
- Incomplete awareness of alternatives
- Making the choice sound arbitrary

---

#### Q4: "Your timeline shows completion of [milestone] in Month 12. What if you encounter delays?"

**Why reviewers ask**: Assessing risk management and realistic planning
**What they're evaluating**: Whether team has thought through contingencies or is overly optimistic

**Strategy for Answer**:
1. Acknowledge the risk: "Yes, timeline risks are real, especially with [specific risk]"
2. Describe mitigation:
   - Built-in buffers: "We've built 2-3 months contingency into Phase 2"
   - Parallel paths: "If Approach A falls behind, we can accelerate Approach B"
   - Resource flexibility: "Our team has capacity to reallocate effort"
3. Escalation plan: "If [specific milestone] misses deadline, we trigger [response]"

**Example Response**:
"The critical path is WP2 model development → WP3 validation. We know model development is unpredictable; typical ML projects experience 20% timeline overruns. We've built in 2-month buffer specifically for unexpected model tuning. We have two alternative architectures pre-designed; if primary approach underperforms, we shift resources to alternative. If we're behind schedule at Month 18 (our decision point), we reduce validation to 3,000 patients instead of 5,000, maintaining statistical power while meeting timeline. We've intentionally front-loaded risky work in Phase 1, so delays don't cascade."

**Key Elements**:
- Show you've thought through specific risks
- Don't claim you'll never experience delays
- Demonstrate adaptive management capability

---

### B. Feasibility & Resources

#### Q5: "Your budget shows only one senior researcher at 0.3 FTE for project management. Is that sufficient?"

**Why reviewers ask**: Assessing whether resources match project scope
**What they're evaluating**: Management capacity, likely project success probability

**Strategy for Answer**:
1. Provide context: "The PI at 0.3 FTE manages [X team size, Y institutions, Z deliverables]"
2. Explain division of labor: "WP leaders at each partner handle technical oversight; PM focuses on..."
3. Describe tools/systems: "We use [project management tool] with automated reporting, reducing PM overhead"
4. Benchmark: "For projects this size and complexity, 0.3-0.5 FTE PM is standard..."

**Example Response**:
"At 0.3 FTE (~1.5 days/week), our PM manages a 6-person team across 3 institutions. This is feasible because: (1) WP leaders own their technical oversight—PM doesn't duplicate this; (2) we've automated reporting through [tool], reducing administrative burden; (3) 3 months of 0-level consortium setup (Month 1-3) front-load governance, then operations become steady-state; (4) PM is supported by part-time administrative assistant. In our experience with prior Horizon projects, 1.2 PM FTE was barely sufficient; here we're learning from that. We're not under-resourced; we've just become more efficient."

**When to push back diplomatically**:
If reviewers insist PM is insufficient: "I hear your concern. We're confident in this level, but happy to discuss reallocation. We could reduce [other category] to fund additional PM time, though we think that would be suboptimal given [reason]."

---

#### Q6: "How will you ensure international partners are genuinely engaged rather than nominal?"

**Why reviewers ask**: Many international projects fail due to weak partner engagement
**What they're evaluating**: Realism about partnership management, motivation of partners

**Strategy for Answer**:
1. Explain partner roles: "Partner [X] leads WP [Y], responsible for [deliverables]"
2. Show incentive alignment: "Partner [X] benefits because [specific benefit—publications, capability, market access]"
3. Describe governance: "We have monthly partner meetings, quarterly Steering Committee, annual in-person meeting"
4. Provide evidence: "Partners have collaborated previously; see Consortium Agreement Section [X] for commitment details"

**Example Response**:
"In our prior [project], we had partners that were passive. This time, we've learned three lessons: (1) each partner leads a distinct work package, making them responsible for concrete deliverables—not just 'contributing'; (2) we've structured IP sharing such that partners benefit from publications and IP licensing revenue—they have financial incentive; (3) we've built partnership agreements into the Consortium Agreement with specific performance expectations and consequences for non-performance. Partner University A has already invested €100k in preliminary work for this project; they're committed. We've also staggered funding—partners only receive monthly payments if deliverables on track. It's not perfect alignment, but it's better than hoping people care."

---

#### Q7: "Your equipment budget shows [high-cost item]. Are you sure you can't access this through existing facilities?"

**Why reviewers ask**: Ensuring efficient use of grant funds; some items may be available through consortia/core facilities
**What they're evaluating**: Cost justification, alternatives considered

**Strategy for Answer**:
1. Acknowledge the question: "Good point—we considered shared facility access."
2. Explain why new equipment necessary:
   - Availability: "The nearest facility is [location], 500 km away; we'd lose [X% productivity] in transit"
   - Timeline: "Facility wait list is 6-8 months; our timeline critical path is 18 months"
   - Capacity: "Facility available 2 days/week; we need dedicated access"
   - Cost: "Facility cost €[X] for our usage; equipment cost €[Y], cost-effective at Month [Z]"
3. Cost-sharing: "We're partnering with [facility]; they're co-funding [% of cost]"

**Example Response**:
"We've worked extensively with the [Regional Core Facility]. They have one mass spectrometer, booked 90% of available time. For our project requiring 60+ samples/month across 3 years, shared access would: (1) create 6-8 month backlog; (2) cost €45k/year in facility fees, totaling €135k—more than equipment cost; (3) force sample batching, losing temporal resolution. The RTG facility is investing €120k in new equipment; we're contributing €80k, gaining dedicated access. After project, equipment becomes shared facility resource. This is much more cost-efficient than facility fees, and enables the research timeline."

**Key Points**:
- Show you've genuinely explored alternatives
- Compare true costs (facility fees + productivity loss vs. capital investment)
- Demonstrate equipment becomes permanent resource after project

---

### C. Impact & Significance

#### Q8: "Your proposal claims [impact claim]. How will you actually achieve this? What's your strategy?"

**Why reviewers ask**: Many proposals make grand claims without credible pathways
**What they're evaluating**: Realism of impact projections, genuine engagement with stakeholders

**Strategy for Answer**:
1. Acknowledge the claim: "Yes, we're targeting [impact], which is ambitious but achievable."
2. Describe the logic model: Research → Intermediate → End Impact
3. Specify your role: "Our role is the research; here's how others will translate it..."
4. Show stakeholder engagement: "Partner [X] is responsible for translation; they have [credibility]"
5. Timeline: "We expect initial adoption Year 3, substantial adoption by Year 5..."

**Example Response**:
"Our claim is that findings will inform policy in 5+ countries. Here's how: (1) We research the question policymakers have asked us to address—we didn't pull this out of the air. (2) We work closely with [Policy Partner] who sits on [regulatory body]. (3) We target publications in policy-accessible journals, not just specialized science journals. (4) We produce policy briefs annually summarizing findings for non-technical audience. (5) We present findings to [policy committees] at Year 3 and 4. Policy Partner has committed to incorporating findings into guidance if evidence is compelling. Will every policy body adopt? No. Will some? Based on prior experience, yes. We're not claiming we're changing the world; we're claiming good research will be heard by decision-makers."

**Avoiding Oversell**:
- Don't claim impact before research is done
- Be specific about intermediaries responsible for translation
- Show evidence that stakeholders actually care about your work
- Acknowledge what you can't control (adoption, policy decisions)

---

#### Q9: "You mention training 15 PhD students. How is this a research outcome rather than just teaching?"

**Why reviewers ask**: Some funding programs distinguish research from training; want to ensure investment focuses on research
**What they're evaluating**: Whether training is integral to research or tangential

**Strategy for Answer**:
1. Explain research contribution: "PhD students directly conduct [research activities]"
2. Show training value: "[Students] acquire skills in [methodology] that they carry forward"
3. Link to research: "[Student contributions] are necessary to research completion"
4. Future impact: "[Trained students] become future PIs, expanding field"

**Example Response**:
"PhD students aren't just learning; they're driving research. Each student leads a work package focused on [specific research question]. They're not assistants to senior researchers; they're independent researchers with their own data, their own papers, their own intellectual contributions. Yes, they're being trained—in [methodology], in [field], in scientific communication. But that training is inseparable from conducting cutting-edge research. In our field, PhD research *is* how we train next generation. These students are not overhead; they're intellectual capital producing research outputs. The training is a by-product of excellent research practice, not a separate objective."

**Key Frame**:
Show that training is integral to research execution, not parallel activity competing for resources.

---

### D. Project Management & Team Dynamics

#### Q10: "You have [X] partners from [Y] countries. How will you actually manage this complexity? How did you choose this consortium?"

**Why reviewers ask**: Large consortia often struggle with coordination and cultural differences
**What they're evaluating**: Realistic assessment of complexity, thoughtful consortium design, prior team experience

**Strategy for Answer**:
1. Justify consortium size: "We have [X] partners because each brings [distinct capability that's essential]"
2. Show selection rigor: "We didn't just invite collaborators; we went through [selection process]"
3. Prior experience: "Our team has managed similar projects; here's what we learned..."
4. Management structure: "Governance is streamlined: [Describe structure], not overly complex"
5. Mitigation strategies: "We've built in [specific measures] to manage coordination challenges"

**Example Response**:
"We have 8 partners across 6 countries. That's large, but justified: we need world-leading expertise in [field 1], [field 2], and [field 3]—and that expertise is geographically distributed. We didn't throw a party and invite everyone; we conducted targeted outreach to [X] teams, selected based on: (1) demonstrated expertise in specific area; (2) prior collaborative track record; (3) institutional commitment (they've pre-funded preliminary work). We've managed similar consortia—our prior Horizon project had 7 partners, was successful. What we learned: (1) keep governance lean—monthly WP leaders meetings, quarterly steering committee, not constant plenum; (2) clear decision rights—each WP leader owns their domain; (3) build relationships early—our first 2 months are dedicated consortium building. We're not treating this as a loose network; we're treating it as a tightly coordinated team despite geographic distribution."

**Red Flags to Avoid**:
- Making consortium seem like an accident ("we invited everyone we knew")
- Adding partners just for geographic coverage
- No prior team experience in large collaborations
- Overly complex governance requiring consensus on everything

---

#### Q11: "What happens if [key person] leaves the project?"

**Why reviewers ask**: Projects often depend critically on single individuals
**What they're evaluating**: Risk mitigation, succession planning, organizational resilience

**Strategy for Answer**:
1. Acknowledge the risk: "Leadership transitions are real risks."
2. Describe who's key: "The critical person is [PI/WP Leader] because [specific expertise]."
3. Succession plan: "If [person] becomes unavailable, [backup person] assumes role. [Backup] already knows the project, participates in [relevant meetings], could transition in [X weeks]."
4. Knowledge transfer: "We're documenting [key processes], maintaining shared [project management systems]."
5. Contingency budget: "We've allocated contingency to enable hiring replacement quickly if needed."

**Example Response**:
"The single point of failure is our AI/ML expert—that's [Person]. If they left, we're in trouble. Here's our mitigation: (1) [Person] isn't a black box—they participate in weekly team meetings, mentor postdocs who understand the work; (2) We've documented the model architecture, the code is version-controlled with comments; (3) Our postdoc [Name] understands the codebase sufficiently to maintain and iterate; (4) We could hire a replacement within 2-3 months in the AI talent market; (5) We've built 1-2 months contingency in Phase 2 specifically for personnel transitions. This isn't airtight—losing someone is disruptive—but we're not dependent on a single person being indispensable. The project is structured to survive personnel changes."

---

#### Q12: "Why should we fund your team instead of [competing proposal]?"

**Why reviewers ask**: Often asked directly; assess whether you're aware of your competitive advantages
**What they're evaluating**: Honest self-assessment, awareness of competition, distinctive contributions

**Strategy for Answer**:
1. Don't criticize competitors: "I'm not familiar with that proposal, so I can't compare directly."
2. Articulate your distinctive advantage: "What makes us strong is [specific advantage]."
3. Point to track record: "In our prior work, we've demonstrated [outcome], delivered [results]."
4. Show team cohesion: "Our team brings unique combination of [expertise A] + [expertise B] + [expertise C]."
5. Humble conclusion: "Whether we're the 'best' choice isn't for me to judge; you're the reviewers. We believe we're well-positioned to deliver impact."

**Example Response**:
"I can't evaluate competing proposals since I haven't seen them. What I can say is what makes our team distinctive: (1) We have 15 years of integrated history working together—not a new consortium assembled for funding; (2) We combine academic rigor [University], clinical credibility [Hospital], and commercial viability [Industry partner]—rare combination; (3) Our prior work has generated 6 patents and 2 licensing agreements, demonstrating we actually commercialize, not just publish; (4) We have direct relationships with [policy body] who has committed to considering findings for [specific regulation]—our research has real-world entry point. Are we the best? That's your judgment. Are we well-positioned? Yes."

**Tone Balance**:
- Confident but not arrogant
- Specific about advantages, not generic claims
- Acknowledge that funding panel makes final judgment

---

## 3. Handling Difficult Questions

### A. Questions That Challenge Your Methodology

#### Scenario: "Isn't your sample size too small? How will you achieve statistical power?"

**Prepare by**:
- Calculate power analysis for your design
- Know the minimum sample needed
- Have justification for any smaller sample (qualitative research, rare populations)
- Understand your statistical test

**Response Structure**:
"Our sample size is [X] per group. For our primary outcome with [test], this provides [power]% power to detect [effect size]. We've based this on prior literature showing effect size of [reference]. If effect size is smaller, we'd be underpowered—that's the risk. But given [justification], we believe this is appropriate. As supplementary analysis, we'll report effect sizes and 95% CIs so readers can judge clinical significance regardless of statistical significance."

**Avoid**:
- Getting defensive
- Claiming smaller sample "is enough" without statistical justification
- Changing your story (if you said N=100 in proposal, don't say N=80 now)

---

#### Scenario: "You're using [method]. But [competing method] has been shown to be superior."

**Prepare by**:
- Knowing the literature on your methodological choices
- Understanding why you chose your approach
- Knowing the competing approach and its limitations

**Response Structure**:
"You're right that [competing method] has advantages in [specific scenario]. However, our approach is optimal for [our specific scenario] because [reason]. [Competing method] requires [resource/assumption/expertise] that we don't have / that's not aligned with our research question. Both are valid; we've chosen the one that's most appropriate for our context."

**Avoid**:
- Acting surprised by the criticism
- Agreeing it's superior then defending your choice anyway
- Making it seem like you chose your method arbitrarily

---

### B. Questions About Team Composition

#### Scenario: "Your team doesn't include [expertise]. Isn't that a gap?"

**Prepare by**:
- Know what expertise you have and don't have
- Be ready to explain why missing expertise isn't critical
- Have subcontracting or advisory solution ready

**Response Structure**:
"That's a fair observation. We don't have [expertise] in-house. Here's why we can still succeed: (1) This expertise is needed for [specific task], which is [secondary/not critical] to our research question; (2) We have [subcontractor/advisory board member] with this expertise available for [frequency]; (3) [Reason why in-house expertise less critical than it appears]. We've made a deliberate choice to avoid assembling everything in-house, which would make this unmanageably large. But the expertise is accessible when needed."

**Avoid**:
- Claiming the expertise isn't needed (reviewers know your field)
- Seeming defensive about gaps
- Claiming you'll address expertise gaps after funding (credibility issue)

---

### C. Questions About Impact Claims

#### Scenario: "Your timeline says adoption by year 3. Isn't that unrealistic?"

**Prepare by**:
- Having realistic understanding of adoption timelines in your field
- Understanding the regulatory/implementation pathway
- Having evidence that stakeholders actually want your product

**Response Structure**:
"You're right to push back on timelines—adoption is slow. Let me clarify: By Year 3, we expect [smaller outcome]—[X] pilot sites testing, [Y] policy bodies reviewing, [Z] initial publications. Full adoption across [sector] would take 5-10 years, not 3. Our claim is narrower: generating evidence and getting it in front of decision-makers by Year 3. Actual policy change is beyond our control. We're setting realistic expectations for what we can control (research & dissemination) and being humble about what we can't (policy decision-making)."

**Avoid**:
- Claiming impact will happen just because research is done
- Naive timelines ignoring regulatory/implementation reality
- Refusing to clarify—if reviewers think you're naive, they'll doubt your judgment

---

## 4. Strategic Communication Approaches

### A. The "Tell Them" Strategy

**Structure any complex answer using**:
1. **Tell Them What You're Going to Tell Them** (preview)
   "I'll address three points: feasibility, timeline, and impact."

2. **Tell Them** (detailed answer)
   [Provide substantive response]

3. **Tell Them What You Told Them** (summary)
   "So to summarize: we've addressed feasibility through [X], timeline through [Y], impact through [Z]."

**Why this works**: Reviewers often get lost in technical detail. Signposting helps them follow your logic.

---

### B. The "Bridge" Technique

When asked off-topic or hostile question:
1. **Acknowledge the question**: "That's an important point..."
2. **Provide brief answer**: One sentence if possible
3. **Bridge to your message**: "What's most important for this project is..."
4. **Expand on your message**: Discuss relevant point

**Example**:
Q: "Isn't your field oversaturated? Too many people doing this work?"
A: "That's a fair concern about field saturation. There is active research in this area. [BRIDGE] What distinguishes our proposal is that we're addressing a specific gap—[gap]. Our contribution is [distinctive contribution]. That's where we believe funding is most productive."

---

### C. The "Principle" Approach

When facing values-based criticism:
1. **Identify the underlying principle**: "I hear your concern about [value]—that's important to us too."
2. **Show alignment**: "Here's how we're addressing [value]..."
3. **Acknowledge tradeoff**: "We're making tradeoffs between [value A] and [value B]; here's our reasoning..."

**Example**:
Q: "You're commercializing research developed with public funds. Isn't that unfair?"
A: "I appreciate that concern about research funding. We're committed to public access to research outputs. Here's how: (1) all publications are open access; (2) datasets are publicly available; (3) if we develop products, they're priced accessibly for developing countries. Our view: public funding enables the research, public gets access to knowledge. Someone eventually commercializes to ensure adoption—we're being intentional about how that happens and who benefits."

---

## 5. Panel Interview Logistics

### Format & Timing

**Typical Formats**:

1. **European Commission (Horizon Europe)**
   - Format: 10-minute presentation + 20-30 minute Q&A
   - Audience: 4-6 independent reviewers
   - Setup: Video conference (Skype/Teams)
   - Presentation: Usually slides (10-12 slides)
   - Outcome: Discussed in closed session immediately after

2. **UK UKRI**
   - Format: 15-minute presentation + 15 minute Q&A
   - Audience: Panel of 4-5 (mix of academics & lay members)
   - Setup: Usually in-person, some virtual options
   - Presentation: Slides optional, some panels prefer no slides (discussion-focused)
   - Outcome: Panel decides immediately, communicates next day

3. **Canadian Tri-Council**
   - Format: 20-minute presentation + 20 minute Q&A
   - Audience: Research committee of 3-4
   - Setup: Sometimes in-person, increasingly virtual
   - Presentation: Slides required, strict format
   - Outcome: Committee meets in secret after, decides within 48 hours

4. **Swiss SNSF**
   - Format: 10-minute presentation + 10 minute Q&A
   - Audience: 2-3 scientific experts + 1 lay member
   - Setup: Usually phone interview or video
   - Presentation: Often no slides; focused on discussion
   - Outcome: Not discussed in front of applicant

5. **German DFG**
   - Format: 15-minute presentation + 15 minute Q&A
   - Audience: 4-5 reviewers
   - Setup: Video conference
   - Presentation: Slides required, detailed visuals
   - Outcome: Discussed in closed session

### Presentation Strategy

**Slide Structure for 10-15 Minute Interview Presentation**:

1. **Title Slide** (30 seconds)
   - Title, team names, institution, project duration
   - No text; just key visual element

2. **The Problem** (1-2 slides, 2 minutes)
   - What's the research question?
   - Why does it matter?
   - What's currently missing?

3. **Our Approach** (2-3 slides, 3 minutes)
   - How will we solve it?
   - What's innovative?
   - Why will this work?

4. **Work Packages/Timeline** (1-2 slides, 2 minutes)
   - Major milestones
   - Work flow / dependencies
   - Key deliverables

5. **Team & Resources** (1 slide, 1 minute)
   - Who's doing the work?
   - What resources needed?
   - Why is this team capable?

6. **Impact & Outcomes** (1-2 slides, 2 minutes)
   - What will change because of this research?
   - Who benefits?
   - How will we disseminate?

7. **Budget Summary** (optional, 30 seconds)
   - High-level allocation
   - If asked: Be prepared to justify

**Slide Design Tips**:
- Keep text minimal (headlines only)
- Use visuals (diagrams, images)
- Avoid dense slides
- Use consistent color scheme
- Ensure legibility (minimum 14pt font)
- Test on different screens/connections before interview

### Managing Presentation Nerves

**Technical Preparation**:
- Test video/audio 15 minutes before call
- Have backup (phone number for audio only)
- Quiet location, professional background
- Dress professionally
- Have water nearby

**Mental Preparation**:
- Practice delivery 5+ times
- Rehearse with critical colleague who will ask tough questions
- Anticipate questions and practice answers
- Remember: Reviewers *want* projects to succeed; they're not trying to trick you
- You're the expert on your research; trust that knowledge

**During Interview**:
- Pause before answering (not silence, but brief moment to formulate)
- Speak deliberately, not too fast
- Make eye contact with camera
- Smile (reviewers can hear it in your voice)
- If you don't know answer: "That's a great question. I don't have that specific data available, but I can [research it / point you to the proposal section where it's discussed]."

---

## 6. Post-Interview Follow-Up

### What You Can Do After Interview

1. **Thank You Email** (within 24 hours)
   - Thank panel for time and thoughtful questions
   - Offer to provide any clarifying information
   - Keep it brief (3-4 sentences)

2. **Clarifications** (if allowed)
   - Some programs allow written clarifications post-interview
   - Only if explicitly invited by funder
   - Address any points you left incomplete
   - Don't re-argue or seem defensive

3. **What NOT to Do**:
   - Don't contact individual panel members
   - Don't try to influence the decision
   - Don't share the interview with unauthorized parties
   - Don't discuss other proposals' content

---

## 7. Interview Question Practice Sets

### Practice Set 1: Scientific Excellence

1. What would disprove your hypothesis?
2. How is your approach different from [competing group]'s work?
3. What's the biggest risk to your methodology, and how will you mitigate it?
4. Why is this problem worth solving now?
5. What are the limitations of your approach?

### Practice Set 2: Feasibility & Management

1. What's your project management plan?
2. How will you handle disagreements among partners?
3. What happens if a key partner underperforms?
4. How will you manage the budget if costs increase mid-project?
5. What's your contingency plan for [major risk]?

### Practice Set 3: Team & Resources

1. Why is each team member essential?
2. What expertise is missing, and why isn't it critical?
3. How will you maintain team cohesion across [X] sites?
4. What's your track record on delivering similar projects?
5. How will you train students/postdocs on this project?

### Practice Set 4: Impact & Sustainability

1. Who will actually use your research outputs?
2. How will findings affect practice/policy?
3. What's your route to commercialization (if applicable)?
4. How will research continue after grant ends?
5. What's the broader significance beyond your field?

### Practice Set 5: Difficult Questions

1. Your budget seems high/low. Why?
2. This seems risky. Are you sure it will work?
3. Your timeline seems tight. Can you really deliver?
4. How is this different from basic research?
5. Why should we fund you instead of the competing proposal?

---

## 8. Common Interview Mistakes & How to Avoid Them

| Mistake | Why It's Bad | Solution |
|---|---|---|
| Reading slides verbatim | Shows you're not confident; reviewers get bored | Know your material, use slides as prompts |
| Spending 5 min on background, 5 min on innovation | Gets cut off before reaching your strong content | Lead with innovation, background as context only |
| Technical jargon without explanation | Non-specialist reviewers get lost | Assume mixed expertise; explain terms |
| Over-committing to outcomes | Damages credibility if don't deliver | Be realistic about what you can achieve |
| Getting defensive when challenged | Comes across as insecure | Acknowledge valid points, explain your reasoning |
| Speaking too fast due to nerves | Reviewers can't follow; you run out of time | Practice deliberately; use pauses |
| No eye contact (staring at notes) | Seems unconfident, disconnected | Look at camera; have notes but don't read |
| Dismissing legitimate concerns | Damages credibility | Take concerns seriously, explain your mitigation |
| Claiming you'll "figure it out later" | Implies you haven't done due diligence | Show you've thought through challenges |
| Saying "I don't know" without offering alternative | Seems unprepared | "I don't know that specific detail, but here's what I can tell you..." |

---

## Conclusion

Grant panel interviews are high-stakes conversations with limited time. Success comes from:

1. **Thorough Preparation**: Know your proposal inside and out
2. **Clear Communication**: Explain complex ideas simply without losing rigor
3. **Honest Assessment**: Show you understand limitations and have mitigation strategies
4. **Strategic Presentation**: Lead with strength, back up with evidence
5. **Authentic Engagement**: Be genuine, not performative
6. **Gracious Response**: Address tough questions as opportunities to clarify, not threats

Remember: Reviewers want excellent research to succeed. They're looking for reasons to fund you, not reasons to reject. Your job is to make their decision easy by demonstrating scientific excellence, realistic planning, and genuine impact potential.

The most successful applicants are those who combine:
- **Confidence** in their research
- **Humility** about what they can achieve
- **Clarity** in communication
- **Competence** in their field
- **Commitment** to rigorous research

Go into that interview as the expert you are.
