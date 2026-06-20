# Pathfinder v0.3 Working Paper

## An Open Methodology for Managing Adoption Pathways Under Uncertainty

**Developed by The Chamber of Us**  
**Version:** 0.3 Working Paper  
**Date:** June 2026  
**Status:** Public working draft  
**Website:** [thechamberofus.org](https://thechamberofus.org)  
**Contact:** [info@thechamberofus.org](mailto:info@thechamberofus.org)  
**License:** CC BY 4.0 for text. Software components are anticipated to use permissive open-source licenses.

---

## Abstract

Promising interventions often fail in the middle. A pilot works, but does not spread. A research finding is credible, but does not reach the institution that can act on it. A funder wants impact, but cannot tell which opportunity is ready. A volunteer wants to contribute, but cannot find the right work. A community need is visible, but the pathway from evidence to implementation is unclear.

Pathfinder is The Chamber of Us’ open methodology for managing adoption pathways under uncertainty. It helps teams structure evidence, identify decision actors, classify readiness blockers, document choices, and convert uncertainty into useful work.

The central unit in Pathfinder is the **next responsible commitment**. A project does not become an adoption pathway merely because it is promising. It becomes an adoption pathway when evidence from one stage helps another actor make a meaningful next decision. This may be a second funder, contractor, engineer, procurement office, school, NGO, standards body, public agency, volunteer team, or implementation partner.

Pathfinder is not a prediction engine, a top-down coordination system, or a claim that evidence alone causes adoption. It is a structured artifact system for making adoption chains more observable. Its core artifacts are Evidence Packs, Adoption Pathway Maps, Readiness Lanes, Decision Ledgers, and Work Graphs. The TCUS Superstack, consisting of Quasar, Sentinel, Lodestar, and Libelle, is one implementation environment for creating, maintaining, and connecting those artifacts.

This v0.3 Working Paper defines the initial model, including actor profiles, uncertainty categories, adoption states, artifact interfaces, measurement concepts, failure semantics, and falsifiability tests.

---

## Executive Summary

Pathfinder began as a broad alignment architecture for a livable future. Since v0.1, TCUS’ work has become more grounded through volunteer coordination, Libelle development, education infrastructure funding, and research into how construction innovations move from demonstration to adoption.

That work sharpened the problem.

The missing layer is not only data, funding, talent, or awareness. The missing layer is the structured handoff between evidence and the next actor who must decide.

Pathfinder v0.3 reframes the work around one practical question:

**Who must say yes next, and what would make that yes responsible?**

A “yes” does not always mean scale. Sometimes the responsible decision is to continue. Sometimes it is to revise, pause, bound, or stop. Pathfinder is designed to make those transitions legible.

The methodology centers on five structured artifacts:

1. **Evidence Packs**  
   What is known, how we know it, what remains uncertain, and which decision the evidence supports.

2. **Adoption Pathway Maps**  
   Who must say yes next, what gates exist, what evidence is needed, and where the pathway may fail.

3. **Readiness Lanes**  
   A way to classify whether progress is blocked by technology, implementation, institutions, or mobilization.

4. **Decision Ledgers**  
   Records of why choices were made, what evidence was reviewed, what trade-offs were accepted, and what uncertainty remained.

5. **Work Graphs**  
   Maps of the work required to move a pathway forward, including roles, tasks, dependencies, contributors, and review points.

Together, these artifacts work like trail markers. They do not walk the path for anyone. They make the next step visible.

The TCUS Superstack supports the method:

- **Quasar** supports Evidence Packs.
- **Sentinel** supports gap, contradiction, and uncertainty analysis.
- **Lodestar** supports Decision Ledgers, ethics, consent, governance, and accountability.
- **Libelle** supports Work Graphs and mobilization.

The immediate purpose of Pathfinder is not to “align humanity” or guarantee adoption. Its immediate purpose is narrower and more testable:

**to help teams observe adoption chains, reduce avoidable uncertainty, document decision transitions, and learn from both continuation and failure.**

---

# 1. Why Pathfinder Changed Since v0.1

The original Pathfinder v0.1 frame described an “alignment engine” for a livable future. It was motivated by a real concern: humanity has many solutions, but lacks the coordination infrastructure to move them toward shared long-term goals.

That frame remains morally important, but it was too broad as an operational model.

It risked sounding like:

- a planetary operating system
- a general coordination theory
- an ethical AI platform
- a software stack in search of a method
- a civilizational aspiration without measurable transitions

Since then, TCUS has learned from more concrete work:

- building Libelle to coordinate volunteer talent
- supporting education infrastructure funding in Ethiopia
- conducting research on construction innovation adoption pathways
- studying why technically plausible systems stall after pilots
- trying to understand how evidence becomes trusted, fundable, approvable, buildable, teachable, and repeatable

Those experiences revealed a sharper mechanism:

**Good ideas often fail because evidence does not travel in a form that reduces uncertainty for the next actor who controls the next decision.**

That is the central shift from v0.1 to v0.3.

Pathfinder v0.3 is no longer primarily framed as a broad planetary alignment engine. It is framed as an adoption-pathway methodology.

---

# 2. The Problem: The Missing Middle Between Evidence and Action

Many fields are rich with ideas, pilots, reports, prototypes, and local successes. Yet many promising interventions still fail to move forward.

The failure often occurs in the middle.

A project may have enough evidence to interest its original sponsor, but not enough evidence for a second funder. A technology may work in a demonstration, but not be trusted by contractors. A research finding may be credible to specialists, but not actionable for public agencies. A volunteer may have useful skills, but the work is not structured enough for them to contribute. A partner may want to proceed, but cannot identify the next approval gate.

These are not all the same problem.

Some are evidence problems.  
Some are implementation problems.  
Some are institutional problems.  
Some are funding problems.  
Some are trust problems.  
Some are labor and coordination problems.  
Some are political or incentive problems.

Pathfinder exists because these blockers are often collapsed into vague phrases such as:

- “not ready”
- “needs more research”
- “hard to scale”
- “lacks buy-in”
- “needs funding”
- “implementation problem”
- “coordination failure”

Those phrases may be true, but they are not specific enough to guide action.

Pathfinder tries to make the adoption pathway visible enough to ask:

- What stage is this actually in?
- Who controls the next transition?
- What decision right do they hold?
- What uncertainty is blocking them?
- What evidence would matter to them?
- What work would reduce avoidable uncertainty?
- What decision was made, and why?
- Did the pathway continue, revise, pause, bound, stop, or transfer to another actor?

---

# 3. The Core Thesis: The Next Responsible Commitment

The key unit in Pathfinder is not the first pilot.

It is the next responsible commitment.

A first pilot can prove that something is possible. But an adoption pathway begins to form only when another actor, not merely the original inventor, donor, researcher, or sponsor, makes a meaningful follow-on commitment.

This is the **second decision** concept.

A second decision may include:

- a second funder supporting continuation
- a contractor agreeing to build again
- a local engineer signing off
- a school hosting a follow-on implementation
- a procurement office accepting the approach
- a standards body reviewing the method
- a public agency incorporating the practice
- an NGO adopting the model in another site
- a volunteer team moving from interest to useful contribution
- a training institution incorporating the method
- a maintainer accepting responsibility for long-term operation

A second decision is not merely enthusiasm, praise, or a meeting. It requires a new actor to accept some responsibility, risk, cost, opportunity cost, or institutional commitment.

The guiding Pathfinder question is:

**Who must say yes next, and what would make that yes responsible?**

This question is deliberately narrow.

It does not ask whether an intervention is universally good.  
It does not ask whether the world needs the idea.  
It does not assume scale is always the goal.  

It asks whether the next actor has enough decision-relevant evidence to make a responsible commitment.

---

# 4. System Boundary: What Pathfinder Is and Is Not

## 4.1 What Pathfinder Is

Pathfinder is a methodology for managing adoption pathways under uncertainty.

It is a structured way to:

- identify actors
- map decisions
- classify uncertainty
- organize evidence
- record rationale
- expose readiness blockers
- convert blockers into work
- track second decisions
- learn from continuation, revision, refusal, boundedness, and abandonment

Pathfinder is implemented through structured artifacts and can be supported by software tools. But the methodology comes first.

## 4.2 What Pathfinder Is Not

Pathfinder is not:

- a guarantee of adoption
- a general AI decision-maker
- a prediction engine
- a universal theory of institutional change
- a replacement for local judgment
- a substitute for political analysis
- a claim that better evidence always wins
- a command-and-control platform
- a way to force scale

Pathfinder does not assume that evidence alone causes adoption.

Actors may accept weak evidence or reject strong evidence because of incentives, politics, funding cycles, legal exposure, procurement rules, organizational inertia, reputational risk, staff capacity, territorial behavior, or community trust.

Pathfinder’s narrower claim is:

**When decision-relevant evidence is structured for the actor who controls the next transition, one important class of adoption failure becomes more visible and potentially more addressable.**

That is the system boundary.

---

# 5. Actor Model

Actors are the central unit of Pathfinder because adoption does not happen in the abstract.

It happens when specific actors, with specific authority, incentives, constraints, and risks, make decisions.

A Pathfinder Adoption Pathway Map should identify the major actors in the pathway and describe each actor through the following profile:

## 5.1 Minimum Actor Profile

**Actor**  
Who is the person, group, institution, or role?

**Decision right**  
What can this actor actually decide?

Examples:

- fund
- approve
- procure
- build
- host
- maintain
- regulate
- train
- replicate
- reject
- revise
- continue

**Risk exposure**  
What could go wrong for this actor if the decision is wrong?

Examples:

- safety risk
- financial risk
- reputational risk
- legal or liability risk
- political risk
- operational risk
- maintenance risk
- community trust risk

**Incentive**  
What would make action attractive or worthwhile for this actor?

Examples:

- cost savings
- improved service delivery
- institutional mandate
- public legitimacy
- technical performance
- donor alignment
- reduced burden
- community demand
- professional recognition

**Constraint**  
What prevents action even if the evidence is strong?

Examples:

- procurement rules
- limited budget
- legal uncertainty
- lack of staff capacity
- political sensitivity
- unclear ownership
- lack of standards
- unavailable materials
- misaligned incentives
- organizational inertia

**Evidence need**  
What uncertainty must be reduced before this actor can responsibly commit?

**Next possible commitment**  
What concrete action could this actor take?

The full actor model is:

**Actor → Decision Right → Risk Exposure → Incentive → Constraint → Evidence Need → Next Possible Commitment**

If these cannot be named, the adoption pathway is not yet well-defined.

---

# 6. Uncertainty Taxonomy

Pathfinder’s central mechanism depends on uncertainty reduction. Therefore, uncertainty must be classified.

Different actors tolerate different types of uncertainty.

A contractor may care most about implementation uncertainty.  
An engineer may care most about technical and liability uncertainty.  
A donor may care about financial and reputational uncertainty.  
A ministry may care about institutional and political uncertainty.  
A maintainer may care about durability and repair burden.  
A community may care about agency, trust, and long-term effects.

The initial Pathfinder uncertainty taxonomy includes seven categories.

## 6.1 Technical Uncertainty

Does the intervention work safely and reliably?

Signals may include:

- calculations
- prototype results
- field tests
- expert review
- performance data
- failure modes
- comparison to existing alternatives

## 6.2 Implementation Uncertainty

Can the intervention be delivered in real conditions?

Signals may include:

- labor skills
- installation process
- supply chain
- quality control
- local capacity
- repeatability
- training requirements
- construction or operating procedures

## 6.3 Institutional Uncertainty

Can the intervention pass through formal or informal institutional gates?

Signals may include:

- code compatibility
- standards review
- inspection pathway
- procurement eligibility
- donor requirements
- public agency acceptance
- organizational ownership
- policy fit

## 6.4 Financial Uncertainty

Can the intervention be paid for, sustained, and justified against alternatives?

Signals may include:

- capital cost
- lifecycle cost
- operating cost
- maintenance cost
- cost comparison
- affordability
- budget timing
- funding pathway

## 6.5 Reputational and Political Uncertainty

What social or institutional risk does the actor face by supporting this?

Signals may include:

- public legitimacy
- stakeholder trust
- political sensitivity
- organizational incentives
- previous failures
- contested ownership
- opposition risk
- perceived credibility

## 6.6 Maintenance and Durability Uncertainty

What happens after the first implementation?

Signals may include:

- repair burden
- spare parts
- local maintenance skills
- ownership model
- durability evidence
- long-term performance
- failure response
- user feedback

## 6.7 Ethical and Community Uncertainty

Does the intervention respect local agency, consent, equity, and long-term well-being?

Signals may include:

- community input
- consent process
- distribution of benefits
- burden shifting
- accountability
- grievance pathways
- power asymmetry
- potential unintended harms

A Pathfinder Evidence Pack should not merely say “uncertainty remains.” It should identify:

**Which uncertainty category is blocking which actor from which decision?**

---

# 7. Adoption States

Pathfinder distinguishes between stages that are often collapsed into the word “adoption.”

A pilot, a replication, an institutional commitment, and routine use are not the same outcome.

The initial adoption-state model is:

## State 0: Concept

The idea is proposed but not yet tested.

Transition indicators:

- problem statement exists
- plausible mechanism described
- initial use case identified
- initial actor or stakeholder identified

## State 1: Validated

The idea has some evidence of technical or practical viability.

Transition indicators:

- evidence pack created
- uncertainty categories identified
- early review completed
- core assumptions documented

## State 2: Piloted

The idea has been tried in a bounded setting.

Transition indicators:

- pilot context documented
- results recorded
- implementation conditions described
- limitations identified
- lessons captured

## State 3: Second Decision

A new actor, not merely the original inventor or sponsor, makes an independent follow-on commitment.

Transition indicators:

- actor independence documented
- decision right identified
- evidence used in decision recorded
- commitment type specified
- uncertainty reduced or accepted

## State 4: Replicated

The intervention is implemented again in a new site, by a new actor, or under meaningfully different conditions.

Transition indicators:

- replication context documented
- fidelity or adaptation recorded
- new constraints identified
- performance compared to pilot
- implementation learning captured

## State 5: Institutionally Adopted

The intervention becomes part of a formal or semi-formal institutional pathway.

Transition indicators:

- procurement pathway exists
- standard, manual, curriculum, budget line, or policy pathway identified
- responsible institution named
- continuation mechanism documented

## State 6: Standardized or Routinely Used

The intervention becomes repeatable without requiring exceptional sponsorship.

Transition indicators:

- routine process exists
- multiple implementations documented
- training or quality controls exist
- maintenance pathway exists
- ownership and accountability are clear

## State 7: Abandoned, Deprecated, or Bounded

The intervention does not continue, is intentionally discontinued, or remains useful only under narrow conditions.

Transition indicators:

- reason for abandonment or boundedness documented
- evidence reviewed
- blocker identified
- lessons captured
- future conditions for reconsideration stated, if relevant

This last state is essential.

Pathfinder should not only document success stories. It should preserve failed knowledge, negative evidence, dead ends, and bounded-use cases.

---

# 8. Evidence Quality Levels

Pathfinder distinguishes between the existence of evidence and the strength of evidence.

A claim may be well-sourced but still weak, context-specific, outdated, biased, incomplete, or irrelevant to the actor controlling the next decision.

The initial evidence quality scale is intentionally simple.

## Level 0: Assertion

A claim is stated but not supported by traceable evidence.

Appropriate use:

- brainstorming
- hypotheses
- early notes
- internal questions

Not appropriate for:

- adoption claims
- decision justification
- external reporting

## Level 1: Anecdotal or Single-Source Evidence

A claim is supported by one source, observation, interview, report, or direct account.

Appropriate use:

- exploration
- case reconstruction
- hypothesis generation

Limitations:

- weak generalizability
- high risk of missing context
- source bias possible

## Level 2: Documented Case Evidence

A claim is supported by documents, field records, implementation reports, photos, calculations, meeting notes, or partner confirmation from a specific case.

Appropriate use:

- pilot evaluation
- case studies
- pathway mapping

Limitations:

- may be context-specific
- may not predict replication

## Level 3: Multi-Source Corroborated Evidence

A claim is supported by multiple independent or semi-independent sources.

Appropriate use:

- stronger pathway claims
- second-decision analysis
- institutional history reconstruction

Limitations:

- source independence must be checked
- contradictions should be recorded

## Level 4: Comparative or Replication Evidence

A claim is supported across multiple cases, sites, implementations, or time periods.

Appropriate use:

- repeatability assessment
- stronger adoption claims
- readiness scoring

Limitations:

- still context-dependent
- implementation fidelity matters

## Level 5: Institutionalized or Routinely Verified Evidence

A claim is supported by routine use, formal standards, repeated procurement, curriculum inclusion, inspection pathways, maintenance records, or durable institutional practice.

Appropriate use:

- institutional adoption claims
- standardization claims
- routine-use assessment

Limitations:

- institutionalization can preserve weak practices
- continued review is still required

Each Evidence Pack should include:

- claim
- evidence level
- source list
- uncertainty category
- confidence note
- contradictory evidence
- actor relevance
- decision supported
- what would change the conclusion

The goal is not false precision. The goal is to prevent unsupported claims from being treated like demonstrated adoption evidence.

---

# 9. Core Pathfinder Artifacts

Pathfinder becomes useful through artifacts. These are the working units of the methodology.

## 9.1 Evidence Packs

Evidence Packs summarize what is known, how it is known, what remains uncertain, and which decision the evidence supports.

They are designed to make evidence portable across actors.

A good Evidence Pack does not merely collect sources. It explains why the evidence matters for a specific decision.

An Evidence Pack may include:

- core claim or finding
- evidence quality level
- source list and provenance
- uncertainty category
- confidence note
- known limitations
- contradictory evidence
- actor-specific relevance
- decision supported
- what would change the conclusion

Core question:

**What does the next actor need to know before deciding?**

## 9.2 Adoption Pathway Maps

Adoption Pathway Maps show how a promising intervention would need to move through real-world actors and gates.

They identify the sequence of commitments required for an idea to become repeatable.

An Adoption Pathway Map may include:

- current adoption state
- next actor
- decision right
- risk exposure
- incentive
- constraint
- evidence need
- readiness blocker
- decision gate
- likely failure points
- second-decision opportunities
- possible next commitments

Core question:

**Who must say yes next, and what would make that yes responsible?**

## 9.3 Readiness Lanes

Readiness Lanes classify where progress is blocked.

A project may be technically promising but institutionally blocked. It may be institutionally supported but impossible to deliver with available capacity. It may have funding but no trained actors. Readiness Lanes prevent these different failure modes from being collapsed into “not ready.”

The four initial lanes are:

- **Technology readiness:** Does it work safely and reliably?
- **Implementation readiness:** Can it be delivered in real conditions?
- **Institutional readiness:** Can it be approved, funded, procured, standardized, or governed?
- **Mobilization readiness:** Can the right people execute the next step?

Core question:

**Where is the adoption pathway actually failing?**

## 9.4 Decision Ledgers

Decision Ledgers record why a choice was made.

They prevent decisions from disappearing into memory, hierarchy, or vague consensus. They make trade-offs visible and allow future teams to understand, challenge, or revise prior choices.

A Decision Ledger may include:

- decision made
- options considered
- evidence reviewed
- uncertainty accepted
- trade-offs
- risks
- dissent or unresolved concerns
- reviewers
- conflicts of interest
- date and rationale
- follow-up conditions

Core question:

**Why did we choose this path, and what did we know at the time?**

## 9.5 Work Graphs

Work Graphs translate adoption-pathway needs into executable work.

They are not merely task boards or volunteer lists. They are dependency maps that connect evidence gaps, readiness blockers, and next decisions to the human work required to move the pathway forward.

A Work Graph may include:

- adoption pathway or project name
- current adoption state
- next actor and decision
- blocker by readiness lane
- uncertainty category
- task required to reduce uncertainty or remove blocker
- required skill
- contributor or owner
- dependency
- review requirement
- output artifact
- due date or cadence
- completion status

Core question:

**What work must be completed before the next responsible commitment can happen?**

---

# 10. Artifact Loop

Pathfinder artifacts should not exist as isolated documents. They should update one another.

The minimum loop is:

**Evidence → Pathway → Blocker → Decision → Work → Outcome → Updated Evidence**

Or, in artifact terms:

1. **Evidence Packs** identify what is known and uncertain.
2. **Adoption Pathway Maps** identify who needs that evidence and what decision comes next.
3. **Readiness Lanes** classify the blocker preventing the next transition.
4. **Decision Ledgers** record what choice was made and why.
5. **Work Graphs** turn blockers and next steps into executable work.
6. New outcomes update the Evidence Pack and Adoption Pathway Map.

The system is only useful if the loop closes.

If an Evidence Pack does not inform a decision, the loop is weak.  
If a Decision Ledger does not update the pathway, the loop is weak.  
If a Work Graph produces tasks that do not reduce a blocker, the loop is weak.  
If a failed pathway does not update the evidence base, the loop is weak.

Pathfinder is not documentation for its own sake. It is a learning loop.

---

# 11. Failure Semantics

Pathfinder is not designed to force adoption.

It is designed to make adoption pathways visible enough that teams can continue, revise, pause, bound, or stop work responsibly.

A failed transfer can still produce valuable knowledge if the blocker is documented. Negative evidence, institutional refusal, abandoned pilots, and bounded-use cases all belong in the system.

Pathfinder recognizes five basic pathway outcomes.

## 11.1 Continue

Evidence supports the next responsible commitment.

Example:

A second funder commits after reviewing pilot results and cost evidence.

## 11.2 Revise

The pathway remains promising but needs redesign.

Example:

A technical reviewer identifies a safety concern that can be addressed through redesign.

## 11.3 Pause

Uncertainty or capacity gaps are too large for continuation.

Example:

The intervention depends on a supply chain that does not yet exist locally.

## 11.4 Bound

The idea works only under narrow conditions.

Example:

A construction method is useful for small, low-risk structures but not appropriate for broader institutional use.

## 11.5 Stop

Evidence, risk, incentives, or institutional constraints make continuation unjustified.

Example:

Lifecycle maintenance costs make an intervention unsuitable for the intended users.

These outcomes prevent Pathfinder from treating every pilot as a success story.

A responsible stop is not failure of the methodology. It may be evidence that the methodology worked.

---

# 12. The TCUS Superstack

The TCUS Superstack is the reference implementation environment for Pathfinder.

The Superstack is not the point by itself. The point is the artifact loop.

## 12.1 Quasar

Quasar supports Evidence Packs.

Primary role:

- source ingestion
- provenance
- dataset structure
- versioning
- evidence traceability
- evidence-pack generation

Quasar should not decide what to do.

## 12.2 Sentinel

Sentinel supports analysis of gaps, contradictions, uncertainty, and possible next questions.

Primary role:

- compare evidence against stated goals or thresholds
- surface contradictions
- identify missing evidence
- classify uncertainty
- suggest possible next questions
- support readiness analysis

Sentinel should not make final ethical or governance decisions.

## 12.3 Lodestar

Lodestar supports Decision Ledgers, consent, ethics, and governance.

Primary role:

- decision records
- conflict-of-interest checks
- consent and data-use review
- long-term alignment criteria
- accountability workflows
- governance templates

Lodestar should not become a general analysis engine.

## 12.4 Libelle

Libelle supports Work Graphs and mobilization.

Primary role:

- contributor intake
- skills and availability matching
- role definition
- onboarding
- task assignment
- contribution tracking
- volunteer-to-work coordination

Libelle should not determine project legitimacy by itself.

## 12.5 Adoption Pathway Maps Across the Stack

Adoption Pathway Maps sit across all layers.

They connect evidence, actors, decisions, blockers, and work.

They are the central navigation artifact of Pathfinder.

---

# 13. Example Walkthrough: Stalled Construction Innovation

Imagine a low-cost building method has been demonstrated once, but has not been adopted by additional builders, funders, or institutions.

A conventional success story might say:

“The pilot worked. Now we need scale.”

Pathfinder asks a different set of questions.

## Step 1: Map the Pathway

Who must decide next?

Possible actors include:

- local engineer
- contractor
- school
- donor
- ministry
- procurement office
- standards body
- community owner
- maintenance actor

Each actor has different decision rights and risk exposure.

## Step 2: Classify the Blocker

Where is the pathway blocked?

Possible blockers:

- technical uncertainty: is it structurally safe?
- implementation uncertainty: can local contractors build it reliably?
- institutional uncertainty: is it code-compatible or approvable?
- financial uncertainty: is lifecycle cost favorable?
- reputational uncertainty: who carries blame if it fails?
- maintenance uncertainty: who repairs it?
- mobilization uncertainty: who can do the next work?

## Step 3: Create the Evidence Pack

The evidence must be formatted for the actor.

For an engineer, the Evidence Pack may need calculations, assumptions, material properties, and failure modes.

For a donor, it may need cost comparison, implementation risk, community benefit, and maintenance responsibility.

For a contractor, it may need build sequence, labor requirements, training needs, and quality-control checks.

For a public agency, it may need standards compatibility, inspection pathway, precedent, and procurement implications.

## Step 4: Record the Decision

If the actor continues, revises, pauses, rejects, or replicates the method, the Decision Ledger records why.

The decision may be:

- continue to second site
- revise technical detail
- pause until test data exists
- bound use to specific conditions
- stop because risk is too high

## Step 5: Convert Learning Into Work

If the pathway remains viable, a Work Graph translates the blocker into tasks.

Examples:

- collect structural calculations
- identify applicable code provisions
- request expert review
- document field performance
- estimate lifecycle cost
- interview contractors
- prepare training materials
- map procurement requirements
- identify second host
- prepare a decision packet for a funder

The goal is not to “sell” the method. The goal is to make the next responsible commitment possible, or to learn why it should not happen.

---

# 14. Measurement Model

Pathfinder should be evaluated at the level of adoption-chain observability and decision-transition improvement.

The initial metrics are not claims of social impact. They are indicators of whether the methodology is making pathways more visible and decisions more traceable.

## 14.1 Evidence Metrics

- percentage of Evidence Packs with source provenance
- percentage of Evidence Packs with evidence quality level
- percentage with uncertainty category identified
- percentage with named next actor
- number of evidence updates after new outcomes
- number of contradictory findings recorded

## 14.2 Actor and Pathway Metrics

- number of pathways with named next actor
- number of pathways with decision rights identified
- number of pathways with risk exposure identified
- number of pathways with incentives and constraints recorded
- number of blockers classified by readiness lane
- number of pathway maps updated after decisions

## 14.3 Decision Metrics

- number of decisions recorded in ledgers
- percentage of decisions with alternatives considered
- percentage of decisions with uncertainty explicitly recorded
- percentage of decisions with conflicts of interest reviewed where relevant
- number of decisions revised after new evidence
- number of decisions resulting in continue, revise, pause, bound, or stop

## 14.4 Second-Decision Metrics

- number of second decisions observed
- type of second decision
- actor independence documented
- evidence cited or used
- time from pilot to second decision
- time from Evidence Pack to decision
- continuation, revision, rejection, abandonment, or bounded outcome

## 14.5 Mobilization Metrics

- time from contributor intake to useful placement
- number of active contributors
- number of active Work Graphs
- number of tasks tied to readiness blockers
- contributor retention
- task completion rate
- reviewer feedback quality

## 14.6 Learning Metrics

- number of assumptions revised
- number of abandoned pathways documented
- number of failed predictions captured
- number of cases where politics, incentives, or funding dominated evidence
- number of artifacts reused by external actors

---

# 15. Falsifiability

Pathfinder can fail.

It should be revised if its artifacts do not improve real decision-making.

Possible failure tests include:

- Evidence Packs are created but not used by decision-makers.
- Adoption Pathway Maps fail to identify actual gatekeepers.
- Readiness Lanes do not predict where projects stall.
- second decisions occur without reference to structured evidence.
- decisions are driven primarily by funding, politics, relationships, or institutional power in ways Pathfinder did not model.
- Work Graphs do not reduce the time between contributor interest and useful contribution.
- Decision Ledgers become performative documentation rather than accountability tools.
- local partners experience Pathfinder artifacts as burdensome or extractive.
- external actors cannot understand or reuse the artifacts.
- the methodology becomes too abstract to guide real action.

The test of Pathfinder is not whether it explains everything. It should not.

The test is whether it helps teams observe adoption chains, reduce avoidable uncertainty, and improve the quality of specific decision transitions.

If the artifacts do not change decisions, Pathfinder must be revised.

---

# 16. Relationship to TCUS’ Livable Future Mission

Pathfinder remains connected to TCUS’ broader commitment to a livable future.

But v0.3 narrows the operational claim.

TCUS is concerned with long-term human flourishing, sustainability, equity, cooperation, and durable institutions. Pathfinder supports that mission by helping promising work move more responsibly from evidence to action.

In v0.3, terms like “alignment” and “livable future” should be understood carefully.

## Alignment

Alignment means:

**the degree to which evidence, decisions, people, and institutional actions are organized toward a stated goal without hiding uncertainty, shifting harm, or bypassing accountable decision-making.**

Alignment does not mean forced agreement, optimization, or centralized control.

## Responsible Commitment

A responsible commitment is a decision to fund, approve, build, join, host, replicate, continue, revise, reject, pause, bound, or stop an intervention after the relevant evidence, uncertainty, risk, and actor responsibility have been made explicit.

A rejection can be responsible if it prevents harm, avoids premature scaling, or redirects work toward a better pathway.

## Livable Future

In Pathfinder v0.3, “livable future” is a directional value frame, not a measured outcome claim.

It refers to TCUS’ long-term orientation toward human flourishing, sustainability, equity, cooperation, and durable institutions.

Specific projects should not claim to “advance a livable future” unless they define the measurable pathway by which they do so.

## High-Leverage

A pathway is high-leverage only relative to a defined goal, constraint, and decision context.

A claim of leverage should specify:

- goal
- actor
- intervention
- expected effect
- cost or constraint
- uncertainty
- comparison option

Without those elements, “high-leverage” remains rhetorical and should be avoided.

---

# 17. What Pathfinder Can Reasonably Claim Now

Pathfinder v0.3 can reasonably claim to help teams:

- observe adoption chains
- identify decision actors
- classify uncertainty
- document evidence quality
- make readiness blockers visible
- convert blockers into work
- record decisions and trade-offs
- track second decisions
- learn from abandonment or bounded adoption
- improve transparency around why work continued, changed, paused, or stopped

Pathfinder should not yet claim to:

- solve coordination failure generally
- predict adoption reliably
- guarantee scaling
- optimize institutional behavior
- align humanity
- prove impact across domains
- replace local judgment
- make politics disappear
- substitute for deep field knowledge

The immediate goal is disciplined observation and improvement of decision transitions in real adoption chains.

---

# 18. Current TCUS Work Relevant to Pathfinder

Pathfinder is being developed through TCUS’ active workstreams.

## 18.1 Libelle

Libelle is the people and mobilization layer.

It emerged from a practical problem: TCUS attracted more potential contributors than it could coordinate manually.

The early lesson was that volunteer coordination is not merely an administrative task. It is an infrastructure problem.

Libelle supports:

- intake
- consent-aware profiles
- resume and skill parsing
- project-role matching
- onboarding
- contribution tracking
- work assignment
- volunteer-to-project coordination

In Pathfinder terms, Libelle helps create and maintain Work Graphs.

## 18.2 Education Infrastructure Funding

TCUS’ education infrastructure work in Ethiopia helped clarify the importance of targeted commitments.

A relatively small commitment can matter when it unlocks a larger pathway, closes a funding gap, or enables another actor to proceed.

In Pathfinder terms, this is not merely “fundraising.” It is decision-chain analysis:

- What project is stalled?
- Which actor controls the next transition?
- What commitment unlocks continuation?
- What evidence supports confidence?
- What follow-on actor becomes possible?

## 18.3 Construction Innovation Adoption Research

TCUS’ research on construction innovation in Ethiopia sharpened the adoption side of Pathfinder.

The research question was not simply whether a material or method works. It was how a construction innovation moves from technical possibility to institutional use.

This required examining:

- pilots
- host institutions
- engineers
- contractors
- standards
- codes
- manuals
- procurement
- training
- maintenance
- second implementations
- reasons for boundedness or abandonment

In Pathfinder terms, construction innovation makes adoption-chain mechanics visible.

## 18.4 Superstack Development

The TCUS Superstack remains in active development.

The goal is not to build software for its own sake. The goal is to support the Pathfinder artifact loop:

**Evidence → Pathway → Blocker → Decision → Work → Outcome → Updated Evidence**

---

# 19. Roadmap

## Phase 1: Pathfinder v0.3 Working Draft

Current focus:

- publish framework page
- publish v0.3 Working Paper
- define core artifacts
- define actor model
- define uncertainty taxonomy
- define adoption states
- define measurement concepts
- connect Libelle to Work Graphs

## Phase 2: Artifact Templates

Near-term focus:

- Evidence Pack template
- Adoption Pathway Map template
- Decision Ledger template
- Work Graph template
- readiness blocker checklist
- second-decision record format
- failure semantics record

## Phase 3: Case Applications

Apply Pathfinder to real cases:

- Libelle volunteer mobilization
- education infrastructure funding
- construction innovation adoption
- selected climate or energy evidence pathways
- partner-supplied stalled pilots or implementation problems

## Phase 4: Tool Integration

Connect artifacts through Superstack components:

- Quasar for evidence structure and provenance
- Sentinel for gaps, contradictions, and uncertainty classification
- Lodestar for decision ledgers, ethics, and governance
- Libelle for work graphs and mobilization

## Phase 5: Public Review and Revision

Future work:

- public RFC process
- GitHub documentation
- partner review
- template iteration
- external use cases
- revision toward Pathfinder v0.4 and v1.0

---

# 20. Invitation

Pathfinder is an invitation to make the difficult middle more visible.

Bring a stalled pilot.  
Bring a research finding that needs an implementation path.  
Bring a dataset.  
Bring a volunteer team.  
Bring a funding question.  
Bring a construction method, education model, health intervention, climate tool, or community project that needs to survive its next decision.

Pathfinder exists to help good work move:

from evidence to trust,  
from trust to commitment,  
from commitment to implementation,  
from implementation to learning,  
and from learning to responsible adoption.

The goal is not to force scale.

The goal is to make the next responsible commitment possible.

---

# Suggested Citation

The Chamber of Us. *Pathfinder v0.3 Working Paper: An Open Methodology for Managing Adoption Pathways Under Uncertainty.* Public working draft, June 2026. The Chamber of Us.

---

# Contact

**The Chamber of Us**  
Website: [thechamberofus.org](https://thechamberofus.org)  
Email: [info@thechamberofus.org](mailto:info@thechamberofus.org)  
Join: [thechamberofus.org/join](https://thechamberofus.org/join)

---

