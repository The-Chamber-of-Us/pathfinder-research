# Claims Needing Verification

## Status

Verification queue for the Nebyu vaulted floor partner-readiness spike.

## Inputs

- `../prompt.md`
- `../model-generations/chatgpt-deep-research.md`
- `../model-generations/gemini-pro-extended.md`
- `model-comparison.md`
- `cleaned-findings.md`

## Purpose

This file lists claims, assumptions, and inferred decision points that should not be treated as accepted findings yet.

The purpose is to protect the spike from turning plausible model synthesis into institutional fact.

A claim appearing in this file does **not** mean it is false. It means the claim needs source cleanup, local technical review, or partner validation before it is used in a partner-facing deck, technical packet, or final brief.

## Verification Status Labels

Use these labels as the file is updated:

- **Open**: not yet checked
- **Partially supported**: some evidence exists, but not enough for partner-facing use
- **Supported**: evidence is adequate for internal use
- **Partner-facing with caution**: usable externally only with careful wording
- **Needs local review**: requires Ethiopian engineer, contractor, permitting, or institutional review
- **Do not use yet**: too uncertain or too high-risk to include in outreach
- **Retire**: unsupported, contradicted, or not useful

## Priority Labels

- **P0**: Must verify before serious partner outreach
- **P1**: Should verify before technical review or partner-specific packet
- **P2**: Useful but not required for first discovery conversations
- **P3**: Downstream / later-gate claim

---

# 1. Nebyu Current Technical Status

## Claim 1.1: The system is beyond thesis-only status

**Claim:** Nebyu’s vaulted floor system has advanced beyond concept/thesis-only status.

**Why it matters:** This changes the framing from “interesting academic idea” to “tested research system needing partner-readiness review.”

**Current basis:** Raw model outputs cite MIT thesis, IASS paper, 3 m prototype, and MIT-reported 15 m² full-scale test.

**Verification needed:**

- Confirm thesis title, author, year, advisor, institution.
- Confirm IASS paper status and details.
- Confirm whether a 2025 SSRN/preprint exists and what it adds.
- Confirm 3 m prototype details.
- Confirm 15 m² full-scale Addis Ababa test details.

**Evidence to collect:**

- MIT thesis PDF
- IASS 2024 paper
- MIT Architecture 2025 article
- SSRN/preprint, if relevant
- Any test report or unpublished technical dossier Nebyu can share

**Status:** Partially supported  
**Priority:** P0  
**Partner-facing caution:** Safe to say “public evidence indicates the system has advanced beyond thesis-only status.” Do not say “ready for building deployment.”

---

## Claim 1.2: A 15 m² full-scale slab was tested in Addis Ababa and withstood design loads

**Claim:** MIT publicly reports that Nebyu completed design, construction, and full-scale testing of a 15 m² unreinforced barrel-vaulted floor slab system in Addis Ababa, and that the prototype withstood design loads.

**Why it matters:** This may be the strongest public-status update in the whole spike.

**Current basis:** ChatGPT generation cites an MIT Architecture article.

**Verification needed:**

- Confirm exact wording of the MIT article.
- Determine whether the test was a slab element, a building component, or a building-like prototype.
- Determine what “all design loads” means.
- Determine loading protocol, factors, duration, instrumentation, and acceptance criteria.
- Determine who witnessed or reviewed the test.
- Determine whether a full test report is available.

**Evidence to collect:**

- MIT Architecture article
- test photos
- load protocol
- sensor/instrumentation data
- drawings
- summary report
- reviewer comments
- EiABC / AAU involvement details

**Status:** Partially supported  
**Priority:** P0  
**Partner-facing caution:** Usable as “MIT reports a 15 m² full-scale test that withstood design loads.” Do not use as proof that partner-grade safety questions are closed.

---

## Claim 1.3: A detailed public test dossier exists for the 15 m² test

**Claim:** A detailed public test dossier exists for the 15 m² Addis Ababa test.

**Why it matters:** A public test dossier would substantially strengthen technical review.

**Current basis:** Neither raw model found clear public evidence of a detailed public test dossier.

**Verification needed:**

- Search public sources.
- Ask Nebyu directly.
- Ask whether an internal MIT/EiABC report can be shared privately.
- Confirm if a journal or conference paper is forthcoming.

**Evidence to collect:**

- PDF test report
- thesis supplement
- conference paper
- lab notebook summary
- field report
- unpublished partner-shareable memo

**Status:** Open  
**Priority:** P0  
**Partner-facing caution:** Do not imply such a dossier exists until confirmed.

---

## Claim 1.4: The 3 m prototype validates the system for real building conditions

**Claim:** The 3 m prototype validates the system for real building conditions.

**Why it matters:** This is an easy overclaim.

**Current basis:** Both models refer to the 3 m prototype, but the prototype appears to validate short-term, bounded structural behavior, not full building deployment.

**Verification needed:**

- Confirm prototype geometry.
- Confirm load cases.
- Confirm support/restraint details.
- Confirm observed deflection and support movement.
- Confirm what the authors say the prototype does and does not prove.

**Evidence to collect:**

- thesis prototype chapter
- IASS prototype section
- photos
- loading protocol
- limitations section

**Status:** Open  
**Priority:** P0  
**Partner-facing caution:** Safer wording: “The prototype supports technical feasibility under tested conditions.” Avoid “validated for buildings.”

---

## Claim 1.5: The support settlement observed in the prototype is a decisive blocker

**Claim:** The 6.6 mm horizontal settlement or related support movement from the prototype is a decisive structural blocker.

**Why it matters:** Gemini treats this as a major liability point. It may be important, but the exact significance must be reviewed by a structural engineer.

**Current basis:** Gemini describes it forcefully. ChatGPT treats unresolved support/restraint behavior as important but less conclusively.

**Verification needed:**

- Confirm the exact settlement/deflection values and context.
- Confirm whether the thesis treats it as a flaw, expected behavior, setup issue, or design iteration.
- Ask Nebyu whether the 15 m² test addressed the issue.
- Ask a structural reviewer what the settlement means for real detailing.

**Evidence to collect:**

- thesis passage
- IASS passage
- 15 m² test details
- Nebyu explanation
- independent engineer comment

**Status:** Needs local review  
**Priority:** P0  
**Partner-facing caution:** Do not say “the system has a fatal settlement flaw.” Say “support restraint and boundary detailing are key review questions.”

---

# 2. Cost, Carbon, and Baseline Claims

## Claim 2.1: The system can reduce embodied carbon by up to 74%

**Claim:** The system can reduce embodied carbon by up to 74% compared with a typical concrete flat slab.

**Why it matters:** This is compelling, but can become misleading if presented without assumptions.

**Current basis:** IASS paper reports up to 74% reduction compared to a concrete flat slab.

**Verification needed:**

- Confirm exact baseline.
- Confirm material assumptions.
- Confirm whether steel ties, formwork, waterproofing, finishes, transport, and local block production are included.
- Confirm whether the claim applies to all typologies or one selected typology.
- Confirm whether comparison is to flat slab only, not ribbed/HCB.

**Evidence to collect:**

- IASS LCA/carbon table
- thesis cost/carbon chapter
- assumptions list
- local benchmark data

**Status:** Partially supported  
**Priority:** P1  
**Partner-facing caution:** Use only with baseline and assumptions. Avoid presenting as project outcome.

---

## Claim 2.2: The system can reduce cost by up to 62%

**Claim:** The system can reduce cost by up to 62% compared with a typical concrete flat slab.

**Why it matters:** Cost claims will attract NGOs and donors but also invite hard scrutiny.

**Current basis:** IASS paper reports up to 62% reduction against a flat slab baseline.

**Verification needed:**

- Confirm cost baseline.
- Confirm what labor rates were used.
- Confirm whether contractor overhead, risk premium, formwork, supervision, training, quality control, waterproofing, and rework are included.
- Confirm whether the estimate is contractor-priced or model/interview-based.
- Compare against Ethiopian ribbed/HCB or beam-and-block alternatives, not only flat slab.

**Evidence to collect:**

- IASS cost table
- thesis cost assumptions
- Ethiopian QS review
- contractor quote
- local BOQ
- ribbed/HCB comparison

**Status:** Partially supported  
**Priority:** P1  
**Partner-facing caution:** Present as “modeled potential cost reduction,” not guaranteed project savings.

---

## Claim 2.3: The correct Ethiopian comparison baseline is a flat slab

**Claim:** The correct comparison baseline is a concrete flat slab.

**Why it matters:** If local practice often uses ribbed/HCB or beam-and-block systems, a flat-slab-only comparison may not answer partner questions.

**Current basis:** ChatGPT says public paper comparison uses flat slab. Earlier TCUS work suggests ribbed/HCB is an important Ethiopian floor-system precedent.

**Verification needed:**

- Confirm the paper’s comparison baseline.
- Confirm typical floor systems for target Ethiopian building types.
- Determine whether partners will expect ribbed/HCB comparison.
- Determine whether schools, clinics, low-rise housing, and multi-story housing use different baselines.

**Evidence to collect:**

- IASS paper
- Ethiopian building manuals
- local engineer review
- BOQ comparisons
- target-building drawings

**Status:** Open  
**Priority:** P1  
**Partner-facing caution:** Do not claim “cheaper than Ethiopian practice” until local baselines are compared.

---

# 3. Structural and Engineering Claims

## Claim 3.1: The system is compression-only and unreinforced

**Claim:** The system is an unreinforced compression-based vaulted floor system.

**Why it matters:** This is technically central, but may be misunderstood.

**Current basis:** MIT and IASS sources describe unreinforced barrel-vaulted earthen floor systems. However, prototype details may include steel angles, ties, or other restraint hardware.

**Verification needed:**

- Clarify “unreinforced” means no reinforcement inside the vault masonry, not necessarily no steel in supports/ties.
- Confirm thrust restraint strategy.
- Confirm whether future typologies require ties, edge beams, or steel details.
- Confirm what should be said to non-technical partners.

**Evidence to collect:**

- thesis drawings
- IASS prototype section
- 15 m² test drawings
- Nebyu explanation

**Status:** Partially supported  
**Priority:** P0  
**Partner-facing caution:** Avoid “no steel” unless verified. Say “vaulted masonry floor using compression behavior, with support/restraint details requiring technical review.”

---

## Claim 3.2: Seismic behavior is unresolved

**Claim:** Seismic behavior remains unresolved or not publicly demonstrated.

**Why it matters:** Ethiopia has seismic zones, and floor-system adoption depends on lateral-load behavior and compatibility with the structural frame.

**Current basis:** Model outputs identify seismic response as an unresolved issue.

**Verification needed:**

- Confirm whether thesis/IASS paper identifies seismic behavior as future work.
- Confirm whether 15 m² test included dynamic or lateral loading.
- Ask Nebyu whether seismic analysis exists.
- Ask local engineer whether first-build use case requires seismic review.

**Evidence to collect:**

- thesis limitations/future work
- IASS future research section
- seismic analysis, if any
- Ethiopian code requirements
- local technical review

**Status:** Open  
**Priority:** P0/P1 depending on target building  
**Partner-facing caution:** Do not imply seismic safety is resolved. Say it is a review item.

---

## Claim 3.3: Long-term creep / sustained loading behavior is unresolved

**Claim:** Long-term behavior under sustained loads remains unresolved.

**Why it matters:** A short load test does not fully answer long-term serviceability and deformation questions.

**Current basis:** Both models flag long-term performance as a trust gap.

**Verification needed:**

- Confirm whether any sustained load testing exists.
- Confirm material creep data for CSEB / earthen masonry vaults.
- Determine whether the 15 m² test included sustained load duration.
- Ask what monitoring period is needed.

**Evidence to collect:**

- test protocol
- material data
- post-test monitoring report
- thesis limitations
- external literature

**Status:** Open  
**Priority:** P1  
**Partner-facing caution:** Present as monitoring need, not proven weakness.

---

## Claim 3.4: Waterproofing and moisture durability are unresolved

**Claim:** The system’s moisture and waterproofing strategy is unresolved.

**Why it matters:** Earthen materials are vulnerable to water-related concerns, and Ethiopian partners may be sensitive to durability failures in alternative materials.

**Current basis:** Gemini strongly emphasizes moisture risk. ChatGPT includes waterproofing/maintenance as a trust gap. Detailed project waterproofing evidence was not identified.

**Verification needed:**

- Confirm material stabilization level and water sensitivity.
- Confirm waterproofing layer proposed in thesis/paper.
- Confirm whether 15 m² Addis test included weather exposure.
- Confirm whether system is intended as intermediate floor, roof, or both.
- Distinguish construction-phase moisture risk from long-term service risk.

**Evidence to collect:**

- thesis detailing
- IASS paper
- 15 m² test documentation
- CSEB standards
- local materials expert review

**Status:** Open  
**Priority:** P0/P1  
**Partner-facing caution:** Do not claim moisture is solved. Do not imply it is fatal without review.

---

## Claim 3.5: Fire, acoustic, vibration, and MEP integration are unresolved

**Claim:** Fire rating, acoustic separation, vibration/serviceability, and MEP integration remain unresolved for occupied buildings.

**Why it matters:** These are likely later-stage building-code and habitability issues.

**Current basis:** Gemini flags them. ChatGPT frames them as downstream issues unless occupied use is proposed.

**Verification needed:**

- Confirm what is addressed in thesis/paper.
- Determine which are required for first test bay or auxiliary building.
- Determine which are required for housing/classroom use.
- Ask local code reviewer.

**Evidence to collect:**

- thesis
- code requirements
- local engineer/architect review
- target use-case requirements

**Status:** Open  
**Priority:** P2 for test bay, P0/P1 for occupied buildings  
**Partner-facing caution:** Do not foreground these in first discovery unless the proposed building is occupied.

---

# 4. Ethiopian Approval / Permitting / Liability Claims

## Claim 4.1: Ethiopian permitting would reject the system categorically

**Claim:** Addis Ababa or Ethiopian permitting bodies would reject the system categorically.

**Why it matters:** This could scare partners unnecessarily if overstated.

**Current basis:** Gemini sometimes implies strong refusal. ChatGPT is more cautious and frames permitting as a likely review/consultant problem.

**Verification needed:**

- Identify the actual permit pathway for a low-risk, non-occupied, restricted-use, or research structure.
- Determine whether alternative compliance or special approval pathways exist.
- Ask local architects/engineers who have permitted non-standard buildings.
- Determine whether the first build could avoid routine occupancy permit pathways.

**Evidence to collect:**

- Ethiopian building proclamation
- Addis Ababa directives
- business portal permit requirements
- local professional review
- precedent cases

**Status:** Needs local review  
**Priority:** P0  
**Partner-facing caution:** Do not say “permitting will reject it.” Say “permit pathway is unknown and should be tested through pre-consultation.”

---

## Claim 4.2: A licensed Ethiopian engineer would refuse to stamp the system under current conditions

**Claim:** No Ethiopian engineer would stamp this system now.

**Why it matters:** This may be directionally plausible but too absolute.

**Current basis:** Gemini states refusal strongly. ChatGPT frames local engineer review as a central unknown.

**Verification needed:**

- Identify whether any Ethiopian licensed structural engineer is willing to review the current evidence.
- Clarify difference between informal review, peer review, design responsibility, and stamping a specific project.
- Determine what evidence would change willingness.
- Confirm liability norms in Ethiopia.

**Evidence to collect:**

- local engineer interviews
- EiABC/AAU faculty review
- professional registration requirements
- project-specific permit requirements
- consultant agreement requirements

**Status:** Needs local review  
**Priority:** P0  
**Partner-facing caution:** Say “local engineer review is the next gate,” not “engineers will refuse.”

---

## Claim 4.3: A low-risk test bay or restricted-use auxiliary build could avoid the hardest permitting pathway

**Claim:** A controlled test bay or restricted-use auxiliary building may face less permitting friction than occupied housing/classroom use.

**Why it matters:** This supports the staged first-build strategy.

**Current basis:** ChatGPT uses Addis Ababa risk-level logic; Gemini also favors test bay first.

**Verification needed:**

- Confirm actual permit requirements for a test bay, temporary structure, campus research structure, or auxiliary building.
- Confirm whether site type matters: university campus, private compound, NGO land, government land.
- Confirm whether non-occupied status changes requirements.
- Confirm whether structural testing structures require permit at all.

**Evidence to collect:**

- Addis directives
- local architect/permit advisor
- university facility office input
- contractor input

**Status:** Partially supported as inference  
**Priority:** P0  
**Partner-facing caution:** Phrase as “likely lower-friction option to investigate,” not confirmed path.

---

## Claim 4.4: Insurance/liability coverage is unavailable

**Claim:** Insurers would not cover the system.

**Why it matters:** This may matter later, but is probably speculative unless a real insurer or legal advisor is consulted.

**Current basis:** Gemini includes insurer refusal logic. ChatGPT treats insurer/liability holder as relevant if applicable.

**Verification needed:**

- Determine whether insurance is relevant for the first-build type.
- Ask local partner how they manage construction and post-occupancy risk.
- Determine whether professional liability insurance exists for EORs.
- Determine whether site-owner liability is the key issue instead.

**Evidence to collect:**

- local legal/insurance review
- partner risk policy
- donor/NGO requirements
- construction contract norms

**Status:** Open / Needs local review  
**Priority:** P2 for test bay, P1 for occupied building  
**Partner-facing caution:** Do not lead with insurance unless partner raises it.

---

# 5. Partner / Habitat / NGO Claims

## Claim 5.1: Habitat or an NGO may consider hosting a restricted-use auxiliary build

**Claim:** Habitat-style partners may consider a restricted-use auxiliary build or monitored test.

**Why it matters:** This affects outreach strategy.

**Current basis:** Both models treat this as plausible but not confirmed.

**Verification needed:**

- Confirm Habitat Ethiopia’s current program priorities.
- Confirm whether they have a history of structural material pilots.
- Ask whether they would ever host non-beneficiary-facing test structures.
- Identify who controls technical review and risk approval.

**Evidence to collect:**

- Habitat Ethiopia public materials
- direct partner conversation
- program staff feedback
- prior pilot examples

**Status:** Open  
**Priority:** P0/P1  
**Partner-facing caution:** Do not assume willingness. First conversation should ask what they would need.

---

## Claim 5.2: A first Habitat-style conversation should avoid occupied housing

**Claim:** A first Habitat-style conversation should not ask for occupied housing deployment.

**Why it matters:** Prevents burning trust by asking too much too early.

**Current basis:** Strong model convergence, supported by current evidence gap.

**Verification needed:**

- Confirm with Habitat or similar partners.
- Ask local advisors whether any beneficiary-facing build would be categorically rejected.
- Determine if an auxiliary or training structure is more plausible.

**Evidence to collect:**

- partner feedback
- NGO safeguarding policy
- risk review requirements

**Status:** Strong inference  
**Priority:** P0  
**Partner-facing caution:** Safe as internal guidance.

---

## Claim 5.3: A partner discovery deck is sufficient to begin pilot negotiations

**Claim:** A partner discovery deck alone is enough to begin pilot negotiations.

**Why it matters:** This is likely false or at least misleading.

**Current basis:** Both models reject deck-only approach.

**Verification needed:**

- Confirm partner expectations through outreach.
- Determine whether a technical memo is required before or after first call.
- Test whether deck-only triggers overclaiming or confusion.

**Evidence to collect:**

- partner feedback
- review of Nebyu deck draft
- TCUS/Robel feedback

**Status:** Do not use yet  
**Priority:** P0  
**Partner-facing caution:** Use a deck as an opener only. Pair with technical readiness and trust-gap artifacts.

---

# 6. First-Build / Pilot Claims

## Claim 6.1: The first build should be a test bay or structural mock-up

**Claim:** The best first gate is an instrumented full-scale test bay or controlled structural mock-up.

**Why it matters:** This is the clearest staged-path recommendation.

**Current basis:** Strong convergence across both models.

**Verification needed:**

- Confirm whether 15 m² test already fulfills this role.
- Determine what evidence remains after that test.
- Ask Nebyu whether another test bay is redundant or necessary.
- Ask local engineer what the next physical test should be.

**Evidence to collect:**

- 15 m² test dossier
- engineer feedback
- instrumentation plan
- Nebyu’s next-build goals

**Status:** Strong inference, pending 15 m² details  
**Priority:** P0  
**Partner-facing caution:** If the 15 m² test already served as a full-scale test bay, the next step may be a restricted-use auxiliary build instead.

---

## Claim 6.2: A pavilion would be a weak first build

**Claim:** A pavilion may look impressive but fail to prove the core floor-system use case.

**Why it matters:** Prevents a dead-end demo.

**Current basis:** Both models caution against symbolic demos.

**Verification needed:**

- Determine whether a pavilion could be loaded and instrumented as a floor-like system.
- Determine whether partners would value public visibility.
- Confirm Nebyu’s learning objectives.

**Evidence to collect:**

- first-build concept options
- partner feedback
- technical review

**Status:** Partially supported as reasoning  
**Priority:** P1  
**Partner-facing caution:** Do not categorically reject pavilion if it is designed as an instrumented structural test. Reject purely symbolic pavilion.

---

## Claim 6.3: A classroom, clinic, or housing unit is premature

**Claim:** Occupied, public, or beneficiary-facing buildings are premature as first external build.

**Why it matters:** Protects partner trust and user safety.

**Current basis:** Strong model convergence and current evidence gaps.

**Verification needed:**

- Confirm whether any full-scale test or hidden dossier changes risk profile.
- Ask local engineer/partner what building types are categorically off-limits.
- Determine whether temporary, non-occupied, or restricted-use versions exist.

**Evidence to collect:**

- partner risk feedback
- permit advisor feedback
- local technical review

**Status:** Strong inference  
**Priority:** P0  
**Partner-facing caution:** Safe as internal guidance.

---

## Claim 6.4: A first build can be designed as an evidence-generating gate

**Claim:** The first build should be designed around evidence needed for the next decision gate.

**Why it matters:** Prevents disposable demos.

**Current basis:** Strong model convergence.

**Verification needed:**

- Define actual next gate.
- Identify evidence required by engineer, partner, site host, and funder.
- Tie monitoring plan to those decisions.

**Evidence to collect:**

- partner discovery notes
- engineer review notes
- monitoring plan

**Status:** Supported as strategy  
**Priority:** P0  
**Partner-facing caution:** This is good language: “evidence-generating first build.”

---

# 7. Artifact Claims

## Claim 7.1: Nebyu needs audience-specific packets, not one general deck

**Claim:** Partner-readiness requires multiple artifacts tailored to different decision-makers.

**Why it matters:** Prevents deck overload and misframing.

**Current basis:** Strong model convergence.

**Verification needed:**

- Review Nebyu’s draft deck.
- Identify intended first audience.
- Test whether partner asks are technical, funding, site-hosting, or discovery.

**Evidence to collect:**

- Nebyu deck draft
- Robel review
- partner feedback

**Status:** Strong inference  
**Priority:** P0  
**Partner-facing caution:** Safe internal guidance.

---

## Claim 7.2: Technical readiness memo is needed before serious review

**Claim:** A technical readiness memo is required to make the system reviewable.

**Why it matters:** Engineers will not evaluate a pitch deck.

**Current basis:** Strong model convergence.

**Verification needed:**

- Ask local engineer what format is useful.
- Collect required technical materials.
- Confirm if a test dossier can serve as the memo basis.

**Evidence to collect:**

- engineer feedback
- thesis/IASS/test summary
- calculations
- drawings

**Status:** Strong inference  
**Priority:** P0  
**Partner-facing caution:** Safe.

---

## Claim 7.3: Trust-gap matrix is the most useful internal artifact

**Claim:** A trust-gap matrix should be created before or alongside the deck.

**Why it matters:** Aligns TCUS, Nebyu, Robel, and reviewers on what is known vs unknown.

**Current basis:** Strong synthesis finding.

**Verification needed:**

- Build matrix from actual claims.
- Review with Nebyu and Robel.
- Update after local technical review.

**Evidence to collect:**

- all source-cleaned claims
- reviewer notes

**Status:** Supported as internal process  
**Priority:** P0  
**Partner-facing caution:** Can be internal first, then selectively partner-facing.

---

## Claim 7.4: A contractor constructability packet is needed before first build pricing

**Claim:** Contractors need a method statement and constructability packet before reliable pricing.

**Why it matters:** Academic cost estimates are not contractor prices.

**Current basis:** Strong model convergence.

**Verification needed:**

- Ask a contractor / foreman / QS.
- Define construction sequence.
- Identify formwork, decentering, tolerances, labor assumptions.

**Evidence to collect:**

- contractor feedback
- BOQ template
- method statement
- construction sequence

**Status:** Strong inference  
**Priority:** P1  
**Partner-facing caution:** Safe.

---

# 8. Language and Framing Claims

## Claim 8.1: “Experimental system” should not be used externally

**Claim:** “Experimental system” is risky language for NGOs, regulators, engineers, and site owners.

**Why it matters:** Language can trigger rejection before substance is reviewed.

**Current basis:** Strong model convergence.

**Verification needed:**

- Test language with Robel, Nebyu, and local reviewers.
- Ask partner contacts what wording feels acceptable.
- Determine whether academic contexts can tolerate “experimental” while partner contexts cannot.

**Status:** Strong inference  
**Priority:** P1  
**Partner-facing caution:** Avoid externally.

---

## Claim 8.2: “Pilot” is not always positive

**Claim:** The word “pilot” may trigger liability concern.

**Why it matters:** TCUS often uses “pilot” positively; institutions may not.

**Current basis:** Strong model convergence.

**Verification needed:**

- Ask partner contacts.
- Determine whether “monitored first build,” “research build,” or “test structure” is safer.

**Status:** Strong inference  
**Priority:** P1  
**Partner-facing caution:** Use “monitored first build” or “evidence-generating first build” when safer.

---

## Claim 8.3: “Earthen floor” may be misleading

**Claim:** “Earthen floor” may sound like a dirt floor or low-status material.

**Why it matters:** It may create wrong mental models for partners and users.

**Current basis:** Gemini emphasis; plausible.

**Verification needed:**

- Ask Ethiopian reviewers how the phrase sounds in English and Amharic/local language contexts.
- Determine whether “earthen masonry floor system,” “compressed earth masonry,” or “vaulted masonry floor” is better.

**Status:** Needs local review  
**Priority:** P1  
**Partner-facing caution:** Avoid plain “earthen floor” as headline language.

---

# 9. Comparative Analogue Claims

## Claim 9.1: Ribbed/HCB is the most relevant Ethiopian floor-system precedent

**Claim:** Ribbed/HCB adoption is more relevant than wall-material cases because it is a floor-system precedent.

**Why it matters:** This determines the comparison frame.

**Current basis:** Earlier TCUS spike and current model logic.

**Verification needed:**

- Confirm HCB/ribbed slab adoption pathway.
- Verify manuals, code references, institutional sponsors, and standard drawings.
- Determine what lessons transfer and what does not.

**Evidence to collect:**

- prior ribbed/HCB spike
- GTZ/GIZ manual
- Ethiopian codes
- local engineer review

**Status:** Partially supported  
**Priority:** P1  
**Partner-facing caution:** Good internal comparison, but do not overclaim direct equivalence.

---

## Claim 9.2: Agrostone creates local institutional trauma around alternative materials

**Claim:** Agrostone’s durability/moisture issues create institutional skepticism that may affect Nebyu.

**Why it matters:** This shapes partner language and moisture evidence.

**Current basis:** Gemini emphasizes this strongly. Needs source cleanup.

**Verification needed:**

- Confirm actual Agrostone adoption and failure modes.
- Confirm whether Ethiopian engineers/contractors today connect Agrostone to earthen/CSEB systems.
- Determine if this is a real institutional memory or model overreach.

**Evidence to collect:**

- Agrostone studies
- local practitioner interviews
- prior construction innovation spike

**Status:** Open / Needs local review  
**Priority:** P2  
**Partner-facing caution:** Do not state “institutional trauma” externally unless validated.

---

## Claim 9.3: SUDU is a direct analogue for Nebyu

**Claim:** SUDU / EiABC / ETH Zurich provides a direct analogue for Nebyu’s pathway.

**Why it matters:** Could help identify first-build and university trust logic.

**Current basis:** Gemini treats SUDU as a direct analogue. Needs careful source check.

**Verification needed:**

- Confirm SUDU design, materials, floor/vault details, occupancy/use, and whether it scaled.
- Determine whether SUDU involved floor systems comparable to Nebyu.
- Determine what institutional lessons transfer.

**Evidence to collect:**

- SUDU manuals / papers
- Block Research Group page
- EiABC sources
- local review

**Status:** Open  
**Priority:** P2  
**Partner-facing caution:** Use as “useful analogue,” not direct precedent, unless verified.

---

## Claim 9.4: Nubian Vault / Auroville / ETH Block Research Group lessons transfer to Ethiopia

**Claim:** Global vaulted/earth construction precedents offer useful lessons for Nebyu.

**Why it matters:** These cases may help identify training, certification, manuals, and repeatability needs.

**Current basis:** Both models use them as analogues.

**Verification needed:**

- Separate roof vaults from intermediate floor systems.
- Separate rural single-story adoption from urban multi-story floor systems.
- Identify what applies: training, manuals, certification, monitored build sequence.
- Identify what does not apply: loads, codes, use categories, climate, contractors.

**Evidence to collect:**

- Nubian Vault Association reports
- Auroville Earth Institute manuals/programs
- ETH/HiLo/Block Research Group papers
- local review

**Status:** Partially supported as analogy  
**Priority:** P2  
**Partner-facing caution:** Use analogues only for institutional behavior patterns, not proof of readiness.

---

# 10. Funding / Budget Claims

## Claim 10.1: A $20,000–$50,000 test-bay grant is realistic

**Claim:** A test bay might be funded for roughly $20,000–$50,000.

**Why it matters:** This number appeared in model output but may be invented or weakly grounded.

**Current basis:** Gemini suggests this range. No evidence has been verified.

**Verification needed:**

- Build actual budget.
- Ask Nebyu what the 15 m² test cost.
- Ask local contractor / QS.
- Include sensors, site prep, supervision, materials, labor, reporting, contingency.
- Identify donor minimum grant sizes.

**Evidence to collect:**

- BOQ
- contractor quote
- prior test cost
- donor program budgets

**Status:** Open  
**Priority:** P2  
**Partner-facing caution:** Do not use this range yet.

---

# Highest-Priority Verification Queue

## P0: Verify before serious partner outreach

1. What exactly was tested in the 15 m² Addis Ababa slab test?
2. Is a detailed test dossier available?
3. What does the 3 m prototype support movement actually mean?
4. What local Ethiopian engineer or faculty reviewer can review the system?
5. What is the least-risky first build that still generates useful evidence?
6. What evidence would Habitat-style partners require before considering any engagement?
7. What should Nebyu explicitly not claim yet?

## P1: Verify before technical packet or partner-specific brief

1. Cost reduction assumptions and local BOQ
2. Carbon reduction assumptions and baseline
3. Comparison against ribbed/HCB or local floor-system alternatives
4. Waterproofing / moisture strategy
5. Construction sequence and decentering method
6. QA / inspection checklist
7. Seismic review requirements
8. Permit/risk category for test bay or auxiliary build

## P2: Verify later but track

1. Fire/acoustic/MEP integration for occupied buildings
2. Insurance requirements
3. SUDU lessons and limits
4. Agrostone institutional memory
5. Nubian Vault / Auroville transferability
6. Donor budget ranges
7. Standards-body pathway

---

# Recommended Source Cleanup Steps

## Step 1: Nebyu technical packet cleanup

Ask Nebyu for:

- 15 m² test summary
- drawings
- load protocol
- material specs
- instrumentation data
- photos
- observed cracks/deflections/settlements
- lessons learned
- current unresolved technical questions
- any forthcoming paper/report

## Step 2: Local engineering review

Ask Robel / Nebyu:

- Which Ethiopian engineer or EiABC/AAU faculty member could review this?
- What would they need to see before saying the system is reviewable?
- Would they review a test bay differently from an occupied building?
- What wording should be avoided?

## Step 3: Partner discovery validation

Ask Habitat-style partners:

- What building types are categorically too risky?
- What evidence would be needed before considering a restricted-use monitored build?
- Who internally would need to review?
- What past alternative-material pilots created caution?

## Step 4: Contractor constructability check

Ask a contractor / foreman / QS:

- Can this be sequenced?
- What is the hardest step?
- What would make pricing impossible?
- What tolerances matter?
- What formwork/decentering risks exist?
- How much supervision is needed?

## Step 5: Permit / site-host reality check

Ask local architect / permitting advisor:

- Is a test bay treated differently from a building?
- Can a university host a research structure?
- What approvals are needed for restricted-use auxiliary structures?
- What documentation would be required?

---

# Claims to Avoid in Partner-Facing Materials for Now

Do not say:

- “The system is ready for housing.”
- “The system is ready for Habitat.”
- “The system is already proven safe for occupied buildings.”
- “It is 62% cheaper.”
- “It is 74% lower carbon.”
- “It requires no steel.”
- “Permitting should be straightforward.”
- “A first pilot can be a school or house.”
- “A deck is enough to move partners.”
- “Contractors can build it repeatably.”
- “Waterproofing is solved.”
- “Seismic behavior is solved.”
- “Ethiopian engineers will approve it.”

Safer wording:

- “Public evidence indicates the system has advanced beyond thesis-only status.”
- “A reported 15 m² full-scale test is an important readiness milestone.”
- “A detailed partner-review packet is still needed.”
- “The next step is partner discovery and technical due diligence.”
- “The first build should be evidence-generating and bounded.”
- “Local engineering review is the next gate.”
- “Cost and carbon benefits are promising but assumption-sensitive.”
- “The system is not yet being proposed for occupied housing deployment.”

---

# Bottom Line

The main claim needing verification is not whether the idea is promising.

The main claim needing verification is whether the current evidence can be converted into a decision-grade package that a real institution can review.

Until that is done, partner outreach should stay in discovery mode.
