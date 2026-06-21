# Claude Generation

## Model

Claude (Opus 4.8, 1M context) — Claude Code, with multi-agent fan-out research.

## Date

2026-06

## Status

Raw model generation. Research lead only. Not verified. Evidence-traceable but **not** field-validated.

## Prompt

See `../prompt.md`.

## Tooling & Method Note (for the operator)

This generation was produced with **both** the Kagi Search MCP (`kagi_search_fetch`, `kagi_summarizer`) **and** the built-in WebSearch / WebFetch tools, cross-checking every major claim across at least two retrieval paths.

**Kagi status: working well, no tweaks needed.** Kagi out-performed generic web search on this task specifically — it surfaced the higher-tier Ethiopian primary sources (the CES 24 compulsory standard, the GTZ/GIZ technical manuals, the GIZ IHDP Volume I management manual, AAU/AASTU/Jimma theses, and Amharic practitioner content) that English `.com` search tends to bury. The `kagi_summarizer` was used to extract text from PDFs that WebFetch could not parse (scanned or compressed government PDFs). Where a figure came only from the summarizer and could not be independently re-confirmed, it is flagged as **single-witness** below.

The work was run in the prompt's intended phases (search → evidence table → uncertainty register → memo → implications) across five parallel research lanes: (1) government housing-program origin, (2) Ethiopian university/engineering evidence, (3) standards & codes, (4) current baseline & supply chain, (5) Amharic sources + Nebyu's baseline.

---

## Headline (read this first)

The honest answer is **"partially supported, with a framing problem."**

1. **What is solidly documented:** Ethiopia ran a large, top-down, donor-seeded housing program (GTZ Low-Cost Housing 1999–2006 → Integrated Housing Development Program / IHDP 2005+) that **prescribed a precast-beam + hollow-concrete-block (HCB) rib slab** specifically to *eliminate formwork and skilled-carpenter demand*, and built it at scale (170,000+ condominium units by 2014). HCB blocks and beam tiles are governed by a **compulsory Ethiopian standard (CES 24:2013)**, and ribbed/hollow-block slabs are a **code-recognized, code-dimensioned system** (EBCS-2:1995 → ES EN 1992-1-1:2015). The product is a routine purchasable SKU today. This is real **institutional + implemented adoption** within the condominium pathway.

2. **What does NOT hold up:** the stronger reading of Robel's observation — that ribbed/HCB is *now the dominant baseline across Ethiopian construction generally*, the result of a recent *shift away* from poured slabs. The most authoritative **recent** (2023–2025) Tier-A sources — including a 2023 peer-reviewed mass-housing study and **Nebyu Haile's own 2024 MIT thesis** — still call **cast-in-place / solid reinforced-concrete flat slab** the "conventional" Ethiopian system. No dated time-series source documents a directional shift. And the condominium program that institutionalized the HCB rib slab was publicly called a **"mistake"** by the responsible federal minister in 2026.

3. **The decision-critical catch for TCUS:** **Nebyu benchmarks his vaulted floor against the concrete FLAT slab, not the ribbed/HCB slab.** If Ethiopian condos predominantly use ribbed/HCB (which already removes concrete vs a solid flat slab), then his headline ~74% carbon / ~62% cost reductions are an **upper bound** measured against the *wrong incumbent*. Resolving "flat slab vs ribbed/HCB as the fair comparator" is the single highest-value action this spike surfaces.

Available sources do not support a complete, clean adoption history. They support a **partial model**: a documented government-mandated institutional adoption in the low-cost/condo segment, weaker evidence for market-wide dominance, and a terminology trap (precast-beam HCB vs cast-in-situ ribbed-with-HCB) that earlier syntheses blur.

---

# 1. Evidence Table (primary artifact)

Tiers: **A** = govt/standard/code/university/official manual · **B** = donor/industry/firm/price-aggregator · **C** = news/blog/social/forum.
Epistemic: **Fact** (directly supported) · **Reported** (stated by a source, not independently verified) · **Interpretation** (reasoned inference) · **Unknown**.
Adoption level: **Impl** = implemented/built · **Inst** = institutional (program/standard/code) · **Conc** = conceptual (paper/proposal only).

| # | Claim | Source (title · author/body · year) | URL | Type | Tier | Epistemic | Lang | Quote / snippet (verbatim) | Confidence | Adoption | Mechanism | Notes | Needs Robel? |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| C1 | The GTZ Low-Cost Housing Project ran 1999–2006 in two phases, implemented by the Ethiopian Ministry of Federal Affairs with GTZ. | GTZ/MoFA, *Low-cost Housing Technical Manual* (~2006) | https://ftpmirror.your.org/pub/misc/cd3wd/1003/_co_gtz_Low_Cost_Housing_Technical_Manual_en_124570_.pdf | Official manual | A | Fact | EN | "It is implemented by the Ethiopian Ministry of Federal Affairs with the support of GTZ … After a first phase (2/1999 – 1/2002) the Project has entered into a second phase which ends in July, 2006." | High | Inst | — | Sets the origin date of the system. | No |
| C2 | The program manual **prescribes a precast-beam + HCB rib slab explicitly to avoid formwork and reduce skilled carpenters**. | GTZ/MoFA *Low-cost Housing Technical Manual* (~2006) | (same as C1) | Official manual | A | Fact | EN | "Pre cast beams and HCB rib systems are used to avoid slab-/beam formwork and to reduce the number of skilled carpenters. For up to G+1 buildings no column formwork is required as the columns are embeded in the Concrete Hollow Blocks." | High | Inst | formwork elimination; construction speed; skilled-labor reduction | The single most important "why" quote. Mechanism is **formwork**, not "it was cheaper." | No |
| C3 | IHDP was initiated by the Ministry of Works & Urban Development in 2005, continuing the Addis Ababa Grand Housing Programme under PASDEP. | UN-Habitat, *Condominium Housing in Ethiopia* (2011) | https://unhabitat.org/sites/default/files/download-manager-files/Condominium%20Housing%20in%20Ethiopia.pdf | UN/donor report | A/B | Fact | EN | "the Integrated Housing Development Programme (IHDP), initiated by the Ministry of Works and Urban Development (MWUD) in 2005 … a continuation of the 'Addis Ababa Grand Housing Programme'." | High | Inst | govt housing program | Implementing ministry differs from C1 (MoFA → MWUD); do not conflate the two programs. | No |
| C4 | IHDP's stated targets bundled housing output with job creation and MSE development. | UN-Habitat (2011) | (same as C3) | UN/donor | A/B | Fact (targets) | EN | "construct 400,000 condominium units, create 200,000 jobs, promote the development of 10,000 micro- and small-enterprises…" | High | Inst | MSE job-creation | These are **targets**, not achieved figures. | No (targets) / Yes (achievement) |
| C5 | The IHDP management manual treats HCB production and precast-beam production by MSEs as explicit program components. | MWUD/HDPO/GTZ, *IHDP Volume I: Management Manual* (~2009) | https://mia.giz.de/dokumente/bib/06-1244.pdf | Govt/donor manual | A | Fact (that these are documented sections) | EN | TOC: "Creation of MSE and role of contractors to job creation … HCB production … Precast Beam" | Medium | Inst | MSE job-creation; supply chain | PDF is glyph-encoded; cover/TOC readable. The *causal* claim "slab chosen because it suits MSEs" is **Interpretation**, not in primary text. | No (for TOC) / Yes (for causal intent) |
| C6 | The IHDP physically built ~170,000+ condominium units (well below its 400k target). | UN-Habitat (2011); UN-DESA/UNPSA (2015) | https://publicadministration.desa.un.org/integrated-housing-and-development-program | UN/govt | A | Fact | EN | "it has built 171,000 housing units to date" (2011); "As of 2014 … more than 170,000 condominium units." | High | **Impl** | cost pressure; MSE | Confirms real built use at scale. | No |
| C7 | A 2018 AAiT thesis documents the laid precast-beam-and-slab-HCB floor system in actual 20/80 condominium projects. | Dendir Shemsu (adv. A. Dinku), *Study on Potential Cost Reduction Mechanisms in 20/80 Condominium Building Projects in Addis Ababa*, AAiT (2018) | https://etd.aau.edu.et/items/b1ef7d2e-e74b-42e4-8e36-9c579f6afee9 | University thesis | A | Fact | EN | Figure captions: "Laid Precast Beams and slab HCB"; "Support posts for precast beams and HCB slab." | High | **Impl** | formwork elimination; cost | **Correction to prior syntheses:** author is **Dendir Shemsu**, not "Tessema." | No |
| C8 | The GTZ program self-reported up to 40% construction-cost and 30% waste reduction. | JFI/*Phenomenal World* (2022) restating GTZ; GTZ manual | https://reports.phenomenalworld.org/addis-ababa-ihdp/ | Journalism restating A | B | Reported | EN | "achieved a 40 percent reduction in construction costs and 30 percent reduction in waste." | Medium | Inst | cost pressure | Program self-report. See C9 for the contradiction. | Yes |
| C9 | **In the IHDP pilot, only ~12% of the cost reduction was attributable to the technology; ~38% to management/finishes.** | UN-Habitat (2011) | (same as C3) | UN/donor | A/B | Fact (as reported) | EN | "12 per cent of this reduction in construction costs was due to the type of technology used, and 38 per cent … due to the management and level of internal finishes." | High | Inst | cost pressure (partly NOT the slab tech) | **Key contradiction vs C8.** The slab/precast technology's isolated cost contribution is far smaller than the 40% headline. | Yes |
| C10 | Engineering cost comparisons of ribbed vs solid range widely (~3.5% to ~18%) and are contested. | Kebede, AAU (2009); *J. Eng. Research & Reports* (2023) | https://etd.aau.edu.et/items/d3b66038-17c7-4124-9cec-ef3702428e94 ; https://journaljerr.com/index.php/JERR/article/view/969 | University / journal | A/A-B | Fact (figures) / Reported | EN | "pre-cast beam-slab system is not widely used for construction of most buildings" (Kebede 2009, ~3.46% margin); "using rib slab saves 17.95% … compared to solid slab" (2023). | Medium | Conc | cost rationale | Different scopes/spans; treat ~18% as upper bound, ~3–8% conservative. | No |
| C11 | CES 24:2013 is a **compulsory** Ethiopian Standard for hollow concrete blocks and beam tiles. | Ethiopian Standards Agency, *CES 24* (2013) | https://www.scribd.com/document/778023288/HCB-Standard | Standard | A | Reported (snippet only) | EN | "CES 24 Compulsory Ethiopian Standard First Edition 2013 Hollow Concrete Blocks and Beam tiles ICS:91.100.10 … Ethiopian Standards Agency." | Medium | Inst | standards acceptance | Full PDF not accessible (Scribd bot-blocked); corroborated by C12. Standardizes the **product**, not the slab-system design. | Yes |
| C12 | CES 24-2013 appears on Ethiopia's official list of compulsory standards/regulated products. | Bureau Veritas/Verigates (mirror of Ethiopian regulator list) | https://verigates.bureauveritas.com/sites/verigates/files/2019-06/Ethiopia-Compulsory%20Standards%20and%20Regulated%20Products.pdf | Govt/industry list | A/B | Fact | EN | "24. 6810. Hollow Concrete Blocks and Beam tiles. CES 24-2013." | High | Inst | standards acceptance (mandatory) | Two-witness confirmation of CES 24's compulsory status. | No |
| C13 | An Ethiopian HCB/beam-tile standard predates CES 24, back to ES C.D3.301-1973. | *ES C.D3.301-1973* (via AAU/Studocu) | https://www.studocu.com/row/document/addis-ababa-university/industrial-management/es-cd3301-1973-standard-for-hollow-concrete-blocks-and-beam-tiles/140774379 | Standard | A | Reported | EN | "This standard specifies requirements for hollow concrete blocks and beam tiles manufactured from Portland cement and suitable aggregates." | Low-Med | Inst | standards acceptance | Pushes the HCB-product standardization timeline back decades — predates the condo program. | Yes |
| C14 | **EBCS-2:1995 explicitly covers ribbed slabs with permanent hollow blocks**, with rib-spacing and topping rules. | EBCS-2 (MWUD, 1995), via two independent university extractions (AAU; Jimma) | https://etd.aau.edu.et/bitstreams/760c6a96-2666-40de-a93c-6aa2c6319142/download ; http://ndl.ethernet.edu.et/bitstream/123456789/87977/2/Chapter%202.pdf | National code | A | Fact | EN | "Ribbed slabs are in-situ concrete ribs with hollow blocks or voids. The rib spacing shall not exceed 1.0m. The thickness of topping shall not be less than 40mm…" | High (two-witness) | Inst | code acceptance | The rib/HCB slab is a **code-recognized, code-dimensioned** system since 1995. Minor numeric discrepancy (rib spacing ≤1.0 m vs centers ≤1.5 m) = different clauses; pin to primary §7.2.3. | No (existence) / Yes (exact clause) |
| C15 | ES EN 1992-1-1:2015 (Ethiopian adoption of Eurocode 2) supersedes EBCS-2; ribbed-slab design continues under it. | *ES EN 1992-1-1:2015* (via EOPCW) | https://eopcw.com/find/downloadFiles/220 | Standard/code | A | Fact | EN | "It supersedes part of 'Design of Concrete Structures - EBCS-2 1995' which is withdrawn." | High | Inst | code acceptance (Eurocode transposition) | Institutional continuity, not proof of built use. | No |
| C16 | The government program standardized condominium blocks into I-type, L-type, T-type typologies, built at scale. | ACASH summary of UN-Habitat; UN-Habitat (2011) | https://www.acash.org.pk/topics/ethiopias-low-cost-housing-program/ | Govt/donor program doc | A/B | Fact | EN | "adjusted the housing block compositions into three basic types (I-type, L-type, and T-type) … In 2006 … renamed the Integrated Housing Development Program (IHDP)." | High | **Impl** (typology) | procurement convenience; standardization | Standardized **typologies** built at scale; the specific 28cm/6cm slab dimensions were NOT found in any located source. | Yes (slab dimensions) |
| C17 | **By ~2011, ribbed slabs with hollow blocks were "common" Ethiopia-wide** (engineering normalization). | Misrak Tefera, *Assessment of Ribbed Slab Constructions…*, AAU (2011) | https://etd.aau.edu.et/items/7de192ed-4fa4-4bcd-b063-4c140702e2d4 | University thesis | A | Fact | EN | "Construction of buildings using ribbed slabs, with hollow blocks, is common from low to high seismic regions of Ethiopia." | High | **Impl** + Inst | engineering normalization | Strongest single normalization quote. Note: "ribbed slab with hollow blocks" (cast-in-situ) is broader than "precast-beam HCB" (see C18). | No |
| C18 | The **factory-precast-beam** variant was "not widely used" as of 2009 — a terminology distinction earlier syntheses blur. | Matheas Kebede, *…Precast Beam-Slab System*, AAU (2009) | https://etd.aau.edu.et/items/d3b66038-17c7-4124-9cec-ef3702428e94 | University thesis | A | Reported | EN | "in our country pre-cast beam-slab system is not widely used for construction of most buildings." | Medium-High | Conc→Inst | — | **Reconciliation:** cast-in-situ ribbed-with-HCB became common (C17); the *factory-precast-beam* variant lagged. "HCB rib slab" ≠ one single system. | No |
| C19 | Built ribbed-slab condo-type buildings show structural limitations (weak diaphragm, drift, punching shear, seismic). | Misrak Tefera, AAU (2011); 2nd AAU stability thesis | https://etd.aau.edu.et/items/7de192ed-4fa4-4bcd-b063-4c140702e2d4 | University thesis | A | Interpretation | EN | "the stiffness of such slabs is not sufficient to act as a rigid diaphragm in the longitudinal direction of the ribs"; "the buildings do not perform adequately to insure the safety of their dwellers at their earth quake design level." | Medium-High | **Impl** (studies real buildings) | defect/limitation | The system is normalized but **not without engineering reservations**. | No |
| C20 | HCB/precast production quality (largely MSE-made) is a documented weak point in condo supply chains. | Tesfaalem Kahsay, *…Quality Control for…RC and HCB (Addis Ababa Housing Projects)*, AAU (2014) | http://thesisbank.jhia.ac.ke/8072/ | University thesis | A | Reported | EN | study finds QC deficient; "careful ingredient selection, adherence to scientific processes, and consistent quality checks are essential." | Medium | **Impl** | quality/defect (MSE production) | The explicit word "MSE" was not confirmed verbatim in what was read — verify the MSE linkage. | Yes |
| C21 | **The most recent peer-reviewed mass-housing source (2023) calls cast-in-place slab — not ribbed/HCB — the "widely used" conventional system.** | Mahmud et al., *A comparative study on conventional RC and prefabricated concrete floor slab systems for mass housing in Ethiopia*, AIP Conf. Proc. 2766 (2023) | https://pubs.aip.org/aip/acp/article/2766/1/020075/2894983 | Conference proceedings | A | Reported | EN | "Conventional concrete-cast-in-place floor slab construction is widely used in our country and requires a long time and a lot of materials." | High | — | — | **Key counter-evidence to "ribbed/HCB is the baseline."** | Yes |
| C22 | "Hollow Cement Block – Ribbed (HCB): 24cm" is a routine, individually-priced catalog SKU (supply-chain normalization). | 2Merkato Construction Market Watch (2024); TenderEthio (current) | https://con.2merkato.com/prices/material/4/63 ; https://tenderethio.com/product/hollow-cement-block-ribbed-hcb-24cm-thick/ | Price aggregator / supplier | B | Fact | EN | "Hollow Cement Block - Ribbed (HCB): 24cm thick … 40.00 Br per pcs … Mar 1, 2024" (2Merkato); "20.00 Br pcs" (TenderEthio). | High | **Impl** (product available) | supply-chain availability | Two-witness on availability. **Proves the block is sold — NOT that the slab system is dominant.** Price discrepancy = stale/regional. | No (availability) / Yes (current price) |
| C23 | Some Ethiopian studies find solid slabs use ~5% *fewer* materials than ribbed — ribbed superiority is contested. | RG 354918127; RG 322600455 | https://www.researchgate.net/publication/354918127 | University | A | Reported | EN | "buildings with solid slabs requires fewer materials in terms of concrete and steel by about 5% as compared to buildings with ribbed slab." | Medium | Conc | — | Undercuts a purely cost-rational "ribbed obviously wins" story. | No |
| C24 | Newer total-precast / prestressed hollow-core systems for Ethiopian mass housing remain **conceptual**, not deployed. | Mahmud et al. (2023) | https://www.researchgate.net/publication/371387507 | Conference proceedings | A | Interpretation | EN | "The new system is a total precast concrete floor system that consists of continuous columns, prestressed rectangular beams, prestressed hollow-core planks, and cast-in-place composite topping." | Medium-High | **Conc** | — | Answers "are newer systems displacing rib slab?" — not yet; on paper. | No |
| C25 | The condominium program that institutionalized the HCB rib slab was publicly called a "mistake" by the federal minister in 2026. | Ethiopia Insider (2026) | https://ethiopiainsider.com/2026/17082/ | News | C | Reported | AM | "ላለፉት ዓመታት … የጋራ መኖሪያ ቤቶች (ኮንዶሚኒየም) መርሃ-ግብር 'ስህተት' እንደነበር … ጫልቱ ሳኒ ተናገሩ" (≈ "Minister Chaltu Sani said the condominium program implemented over past years 'was a mistake.'") | Low-Med | — | — | Policy context: "the baseline going forward" is in flux. Tier C — lead only. | Yes |
| C26 | Nebyu Haile proposes an unreinforced barrel-vaulted earthen-masonry (CSEB) floor and built/tested a 15 m² prototype in Addis. | MIT Architecture News (Aug 2025) | https://architecture.mit.edu/news/low-cost-and-low-carbon-floor-slabs-using-local-materials-addis-ababa-ethiopia | Institutional/academic | A | Fact | EN | "completed the design, construction, and full-scale testing of a 15 m² unreinforced barrel-vaulted floor slab system in Addis Ababa … without relying on conventional high-carbon materials like steel reinforcement." | High | **Conc**/prototype | — | The system this spike supports. | No |
| C27 | **Nebyu's declared comparison baseline is the conventional concrete FLAT slab — not ribbed/HCB.** | N. Haile, *Low-Cost Masonry for the Design of Barrel-Vaulted Flooring Systems*, MIT thesis (2024) | https://dspace.mit.edu/handle/1721.1/157352 | Academic thesis | A | Fact | EN | "…proposing the implementation of unreinforced barrel-vaulted earthen floor systems as an alternative to conventional concrete flat slabs, which are often cost-prohibitive in LEDCs." | High | Conc | — | **Decision-critical.** Same baseline restated in his 2021 predecessor thesis and IASS 2024 paper. | Yes (reconcile with Robel) |
| C28 | Nebyu's vault achieves up to ~74% embodied-carbon and ~62% cost reduction **vs a concrete flat slab**. | N. Haile & J. Ochsendorf, *Low-Cost Vaulted Earthen Masonry Floor Systems*, IASS 2024 (Paper 105) | https://iass2024.org/web/wp-content/uploads/2024/09/IASS_2024_Paper_105.pdf | Peer-reviewed conf. paper | A | Fact (authors' results) | EN | "showcasing up to a 74 …[% reduction]"; summarizer: "up to a 74% reduction in embodied carbon and a 62% decrease in costs compared to conventional concrete methods." | Med-High | Conc | — | **74% is two-witness; 62% is single-witness (summarizer only)** — confirm from PDF before quoting. Delta is vs flat slab → upper bound. | Yes (62% figure) |
| C29 | Earthen vaulted slabs are "affordable but often limited by stiffness" — a real serviceability limitation. | Haile & Ochsendorf, *Stiffness-Based Failure of…Vaulted Floor Slabs*, SSRN (2025) | https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5731889 | Preprint | B | Fact (authors' framing) | EN | "low-strength materials such as earthen masonry, which are affordable but often limited by stiffness." | Medium | Conc | — | A fair baseline comparison should weight serviceability, not just cost/carbon. | No |
| C30 | Ribbed-slab-with-HCB is a named, mainstream construction practice in Amharic practitioner content. | Amharic YouTube/Facebook construction channels (2026) | https://www.youtube.com/watch?v=0oUIZG4BxNc | Social/practitioner | C | Reported | AM | "የሪብ ስላብ ብሎኬት አደረደር / Placing of Ribbed hcb"; "ሶሊድ ስላብ (Solid Slab) እና ሪብድ ስላብ (Ribbed/Joist Slab)" | Low | **Impl** (practice exists) | engineering normalization | Establishes only ambient current practice — **not** the condo→slab causal claim. Tier C. | Yes |

---

# 2. Uncertainty Register

*(Completed before the memo, per the prompt.)*

### Documented facts (Tier A/B, Fact, two-witness where noted)
- The GTZ Low-Cost Housing Project (1999–2006) developed and the IHDP (2005+) scaled a **precast-beam + HCB rib slab** floor system. [C1, C2, C3]
- The system was **explicitly chosen to eliminate slab/beam formwork and reduce skilled-carpenter demand** — a labor/process mechanism, not a bare "it was cheaper." [C2]
- The program **built 170,000+ condominium units** — real, large-scale implemented use. [C6, C7]
- HCB + beam tiles are governed by a **compulsory Ethiopian standard, CES 24** (2013, with a 1973 predecessor), and ribbed/hollow-block slabs are a **code-dimensioned system** under EBCS-2:1995 → ES EN 1992-1-1:2015. [C11, C12, C13, C14, C15]
- Ribbed-slab-with-HCB was described as **"common"** Ethiopia-wide in engineering literature by ~2011. [C17]
- Ribbed HCB blocks are a **routine purchasable product** today. [C22]
- **Nebyu Haile's baseline is the conventional concrete flat slab**, restated consistently across three of his works (2021, 2024, IASS 2024). [C26, C27, C28]

### Reported but not independently verified
- The **"40% cost / 30% waste"** reduction figure (program self-report; partly contradicted by the 12%/38% pilot breakdown). [C8 vs C9]
- The condominium program being a "**mistake**" (2026 minister statement, Tier C, Amharic news). [C25]
- HCB/precast **quality-control deficiencies** tied to MSE production (documented for QC generally; the explicit MSE linkage not verbatim-confirmed). [C20]
- CES 24's full scope (snippet-only; full PDF not accessible). [C11]

### Plausible interpretations (reasoned, not directly stated by a source)
- The slab system was **chosen partly because it could be decentralized to MSEs** for job creation (documented that MSEs made the components; the *causal intent* is inference, appearing mainly in secondary syntheses). [C5]
- The "ribbed/HCB became dominant" narrative blurs two distinct systems — **cast-in-situ ribbed-with-HCB (common)** vs **factory-precast-beam HCB (lagged)**. [C17 vs C18]
- Nebyu's ~74%/~62% advantages are an **upper bound** because they are measured against the flat slab, not the (lighter) ribbed/HCB slab. [C27, C28]

### Unknowns / not supported by available evidence
- Whether ribbed/HCB is the **dominant baseline in private/commercial** (non-program) Ethiopian construction. **No source establishes this.**
- Whether a **dated, directional shift FROM poured/solid TOWARD ribbed/HCB** actually occurred. **No time-series source found.**
- The specific **28cm slab depth / 6cm topping** figures cited in some syntheses — **not found in any located primary source.**
- Whether contractors use ribbed/HCB **by preference vs mandate/supply-convenience** (evidence leans mandate/convenience, not free choice).

### Contradictory evidence (most important section)
1. **Cost magnitude:** 40% headline (C8) vs only 12% attributable to technology (C9) vs 3.5–18% in engineering studies (C10). The slab tech's *isolated* cost contribution is modest.
2. **What IS the conventional system:** older low-cost-housing canon says precast-beam+HCB rib (C2); the most recent Tier-A sources (C21, C27) say cast-in-place / solid RC flat slab. These coexist because they describe **different segments and eras**.
3. **Does ribbed even save material:** some Ethiopian studies say solid uses ~5% *fewer* materials (C23).
4. **"Common" (2011, C17) vs "not widely used" (2009, C18):** reconciled only by separating cast-in-situ ribbed-with-HCB from factory-precast-beam HCB.

### What would change our mind
- A **dated procurement/market survey** (e.g., Ethiopian Construction Authority or a contractors' association) showing the share of condo/private projects using ribbed/HCB vs solid RC over time → would convert "partial" to "supported."
- A **primary IHDP/MWUD design specification** stating the mandated slab system and the MSE rationale verbatim → would upgrade C5 from Interpretation to Fact.
- Robel or an Ethiopian engineer **confirming which incumbent (flat slab vs ribbed/HCB) actually dominates today** → would resolve the baseline-fairness question for Nebyu.

### Items requiring Robel / local-expert validation
C4 (achievement), C5 (causal intent), C8/C9 (cost reconciliation), C11 (CES 24 scope), C16 (slab dimensions), C20 (MSE-quality link), C21/C27 (which incumbent dominates), C25 (policy reversal), C28 (62% figure), C30 (Amharic practitioner sources).

---

# 3. Short Case Memo

**What appears to have happened.** Ethiopia did not drift into ribbed/HCB slabs through bottom-up contractor optimization. The pathway is a **top-down, donor-seeded, program-driven institutionalization**: GTZ and the Ethiopian government (1999–2006) engineered a precast-beam + HCB rib slab whose primary purpose was to *remove timber formwork and skilled-carpentry from the critical path*, then the IHDP (2005+) scaled it to 170,000+ condominium units while deliberately routing component manufacture (HCB blocks, precast beams) to micro and small enterprises for job creation.

**What is documented.** The program origin and dates; the formwork-elimination rationale (verbatim in the technical manual); the built scale; the compulsory product standard (CES 24) and the code recognition of ribbed/hollow-block slabs (EBCS-2 → ES EN); and the engineering-literature description of ribbed-with-HCB as "common" by 2011. These are Tier-A, mostly two-witness.

**What is reported but not fully verified.** The marketing-grade "40% cost reduction" (the program's own pilot data attributes only ~12% to the technology itself); the MSE-quality defect story; and the 2026 political framing of the condo program as a "mistake."

**How adoption may have occurred (working model, with uncertainty visible).** *Institutional mandate* (program + standards + code) → *supply-chain build-out* (MSE manufacture, now a routine SKU) → *engineering normalization* (taught, code-dimensioned, "common" in the literature). The dominant **mechanisms are formwork/skilled-labor elimination and MSE-linked job creation**, with cost as a contributing but over-stated factor — explicitly *not* a simple "it was cheaper."

**Which actors mattered.** The permission chain was **centralized and state-led**: a reform mayor/state-minister (Arkebe Oqubay) and MWUD set the program; GTZ supplied the technology and manuals; the Ethiopian Standards Agency standardized the product; universities (AAU, AASTU, Jimma) provided ongoing structural validation *and* documented the system's limitations; MSEs manufactured; contractors largely assembled a pre-specified system.

**What evidence supports the working model.** C1–C7 (program + built use), C11–C16 (standards/code), C17 (normalization) — a coherent, well-sourced spine for the **condominium / low-cost segment specifically**.

**What remains uncertain.** Whether this extends to **market-wide dominance** today; whether a **dated shift** away from poured slabs occurred; and — critically — **which incumbent actually dominates now**, given that the most authoritative recent sources still call **cast-in-place solid RC the conventional system**, and the program itself is being politically disowned. 

> Available sources do not support a complete adoption history. They support a documented, program-driven institutional + implemented adoption in the condominium pathway, weaker evidence for market-wide dominance, and no evidence of a clean, dated "shift." A partial model is the honest output.

---

# 4. Decision Implications for Nebyu / TCUS

### A. Comparison baseline (highest priority)
- **The baseline is contested, and it matters more than any other finding here.** Nebyu benchmarks his vault against the **concrete flat slab** [C27]; Robel observes the field has moved to **ribbed/HCB** [C17, C22]; the most recent literature still calls **cast-in-place solid RC** conventional [C21]. These are three different comparators.
- **Recommendation: use *multiple* baselines, and lead with the ribbed/HCB one for the condo/mass-housing market.** A ribbed/HCB slab already removes concrete vs a solid flat slab, so Nebyu's ~74% carbon / ~62% cost advantages [C28] are an **upper bound** measured against the *softest* incumbent. The defensible, decision-useful number is the delta **vs the ribbed/HCB slab**, which will be smaller. Reporting only the flat-slab delta risks a strawman that an Ethiopian engineer-reviewer will immediately discount.
- **Formwork is the competitive battleground.** The incumbent's whole reason for existing is *formwork/skilled-labor elimination* [C2]. If Nebyu's vault needs complex centering/formwork or slow curing, that is its critical weakness against ribbed/HCB regardless of carbon. Quantify vault formwork/labor explicitly.
- **Weight serviceability, not just cost/carbon.** Nebyu's own work flags earthen-vault **stiffness limits** [C29]; the ribbed/HCB literature flags **diaphragm/drift** limits [C19]. A credible comparison scores both on deflection/serviceability.

### B. Permission-chain lessons (what transfers)
- **Adoption here was institutional, not organic.** The lever was a **government program + standard + code + MSE supply chain**, not contractor preference. For Nebyu, the realistic path to scale likely runs through **program/standard/university channels**, not winning contractors one at a time.
- **University validation is the standard entry rite.** AAU/AASTU/Jimma routinely test these systems [C7, C17, C19, C20]. **Sponsoring a structural validation + load test with an Ethiopian university (EiABC is already a project partner) is the highest-leverage, lowest-cost next step** — and mirrors exactly how ribbed/HCB earned trust.
- **MSE-manufacturability is a feature, not a footnote.** The system scaled because MSEs could make the components and it created jobs [C4, C5]. If Nebyu's CSEB/earthen blocks can be MSE-produced with simple presses, that is a **political-economy argument as strong as the carbon one** — and it speaks the language the housing program already rewards.

### C. What probably does NOT transfer
- The **top-down mass-mandate pathway** may be closed: the condominium program is being politically disowned (2026) [C25]. Don't assume a future national program will simply adopt a mandated slab the way IHDP did.
- The **"cheaper" framing**: cost was over-stated even for the incumbent [C9] and is contested [C10, C23]. Nebyu should not lead with cost alone; lead with **carbon + local-material + labor/MSE** and treat cost as one of several axes.

### D. Questions to ask Nebyu next
1. Is your baseline the **flat slab or the ribbed/HCB slab**? Can you re-run the carbon/cost deltas against ribbed/HCB so the headline number survives expert scrutiny? [C27, C28]
2. What is the vault's **formwork/centering and labor requirement** vs the formwork-free HCB rib system? [C2]
3. How does vault **serviceability/stiffness** compare to ribbed/HCB at condominium spans? [C29, C19]

### E. Questions to ask Robel next
1. When you say condos "shifted to ribbed/HCB," do you mean **cast-in-situ ribbed-with-HCB** or **factory-precast-beam HCB**? (The evidence treats these as different and diverging.) [C17 vs C18]
2. In **private/commercial** (non-program) construction today, what actually dominates — solid RC, ribbed/HCB, or a mix? [C21 vs C22]
3. Did you observe a **dated shift**, or is ribbed/HCB simply normal now? (No source documents a directional change.)

### F. Questions requiring an Ethiopian engineer / university / contractor / housing-program actor
1. **(Engineer/EiABC):** Confirm the dominant current slab system and obtain a real Ethiopian condo **BOQ** showing the slab line item — to settle the baseline empirically. [C16, C22]
2. **(Standards/Authority):** Obtain the **full CES 24 PDF** and the **primary IHDP/MWUD slab specification** to verify scope and the MSE rationale. [C5, C11]
3. **(Contractor):** Is ribbed/HCB used by **preference or supply-chain convenience/mandate**? [C2, C20]
4. **(Housing-program/policy):** Given the 2026 "mistake" statement, what slab system is favored for the **next** housing push? [C25]

---

# 5. Source Directory

**Government / donor / program (Tier A–B)**
1. GTZ/MoFA — *Low-cost Housing Technical Manual* (~2006): https://ftpmirror.your.org/pub/misc/cd3wd/1003/_co_gtz_Low_Cost_Housing_Technical_Manual_en_124570_.pdf
2. GTZ — 72pp Low-cost Housing Manual variant: https://ftpmirror.your.org/pub/misc/cd3wd/1003/_co_lowcost_housing_manual_72pps_h4258e_en_125270_.pdf
3. MWUD/HDPO/GTZ — *IHDP Volume I: Management Manual* (~2009): https://mia.giz.de/dokumente/bib/06-1244.pdf
4. UN-Habitat — *Condominium Housing in Ethiopia: The IHDP* (2011): https://unhabitat.org/sites/default/files/download-manager-files/Condominium%20Housing%20in%20Ethiopia.pdf
5. UN-DESA/UNPSA — IHDP initiative profile (2015): https://publicadministration.desa.un.org/integrated-housing-and-development-program
6. JFI/*Phenomenal World* — *A New Public Housing Model: Addis Ababa's Urban Transformation* (2022): https://reports.phenomenalworld.org/addis-ababa-ihdp/
7. ACASH — *Ethiopia's Low-Cost Housing Program*: https://www.acash.org.pk/topics/ethiopias-low-cost-housing-program/

**Standards & codes (Tier A)**
8. *CES 24:2013 — Hollow Concrete Blocks and Beam tiles* (snippet): https://www.scribd.com/document/778023288/HCB-Standard
9. Bureau Veritas/Verigates — Ethiopia compulsory standards list: https://verigates.bureauveritas.com/sites/verigates/files/2019-06/Ethiopia-Compulsory%20Standards%20and%20Regulated%20Products.pdf
10. *ES C.D3.301-1973* (predecessor HCB standard): https://www.studocu.com/row/document/addis-ababa-university/industrial-management/es-cd3301-1973-standard-for-hollow-concrete-blocks-and-beam-tiles/140774379
11. EBCS-2:1995 ribbed-slab provisions (via AAU): https://etd.aau.edu.et/bitstreams/760c6a96-2666-40de-a93c-6aa2c6319142/download — and Jimma chapter: http://ndl.ethernet.edu.et/bitstream/123456789/87977/2/Chapter%202.pdf
12. *ES EN 1992-1-1:2015* (Eurocode 2 adoption): https://eopcw.com/find/downloadFiles/220

**University / engineering (Tier A)**
13. Dendir Shemsu — *Cost Reduction in 20/80 Condominiums*, AAiT (2018): https://etd.aau.edu.et/items/b1ef7d2e-e74b-42e4-8e36-9c579f6afee9
14. Misrak Tefera — *Assessment of Ribbed Slab Constructions…*, AAU (2011): https://etd.aau.edu.et/items/7de192ed-4fa4-4bcd-b063-4c140702e2d4
15. Matheas Kebede — *Precast Beam-Slab System*, AAU (2009): https://etd.aau.edu.et/items/d3b66038-17c7-4124-9cec-ef3702428e94
16. Tesfaalem Kahsay — *QC for RC and HCB (Addis Ababa Housing)*, AAU (2014): http://thesisbank.jhia.ac.ke/8072/
17. Mahmud et al. — *Conventional RC vs prefabricated floor slabs for mass housing in Ethiopia*, AIP Conf. Proc. 2766 (2023): https://pubs.aip.org/aip/acp/article/2766/1/020075/2894983
18. *Comparative Cost… Solid, Ribbed and Waffle Slab*, J. Eng. Research & Reports (2023): https://journaljerr.com/index.php/JERR/article/view/969
19. *Solid vs Ribbed using HCB under seismic loading* (RG, 2018): https://www.researchgate.net/publication/322600455

**Nebyu Haile / TCUS baseline (Tier A–B)**
20. MIT Architecture News (2025): https://architecture.mit.edu/news/low-cost-and-low-carbon-floor-slabs-using-local-materials-addis-ababa-ethiopia
21. N. Haile — MIT MS thesis (2024): https://dspace.mit.edu/handle/1721.1/157352
22. *Vaulted Earthen Floor Systems for Low-Cost Housing* — MIT thesis (2021): https://dspace.mit.edu/handle/1721.1/139007
23. Haile & Ochsendorf — *Low-Cost Vaulted Earthen Masonry Floor Systems*, IASS 2024 (Paper 105): https://iass2024.org/web/wp-content/uploads/2024/09/IASS_2024_Paper_105.pdf
24. Haile & Ochsendorf — *Stiffness-Based Failure…*, SSRN (2025): https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5731889

**Supply chain / market / news (Tier B–C)**
25. 2Merkato — ribbed HCB 24cm price watch: https://con.2merkato.com/prices/material/4/63
26. TenderEthio — ribbed HCB 24cm listing: https://tenderethio.com/product/hollow-cement-block-ribbed-hcb-24cm-thick/
27. Ethiopia Insider (2026) — condominium "mistake" statement (Amharic): https://ethiopiainsider.com/2026/17082/
28. Amharic practitioner content (ribbed-slab placement): https://www.youtube.com/watch?v=0oUIZG4BxNc

---

# Appendix — Search Lanes & Amharic Terms (transparency)

**Retrieval paths used:** Kagi MCP (`kagi_search_fetch`, `kagi_summarizer`) + WebSearch + WebFetch, cross-checked. Kagi was the stronger tool for Ethiopian primary sources and PDF extraction.

**English/international lanes:** IHDP/GTZ origin & cost; AAU/AASTU/Jimma ribbed-vs-solid theses; CES 24 / EBCS-2 / ES EN; current baseline & precast hollow-core; Nebyu Haile vaulted floor.

**Ethiopian-domain lanes:** `etd.aau.edu.et`, `eopcw.com`, `ndl.ethernet.edu.et`, `ethiostandards.org`, `con.2merkato.com`, `tenderethio.com`.

**Amharic terms actually searched:** ሪብድ ስላብ (ribbed slab); ባዶ ብሎኬት / የኮንክሪት ብሎክ ወለል (hollow block / concrete floor); ኮንዶሚኒየም ወለል ግንባታ ኢትዮጵያ (condominium floor construction Ethiopia); የጋራ መኖሪያ ቤቶች 20/80 40/60 ሪብድ ስላብ (condominium 20/80 40/60 ribbed slab); አነስተኛና ጥቃቅን ተቋማት ግንባታ ብሎክ (MSE construction block); ሪብድ ስላብ ከሶሊድ ስላብ ሌላ አነስተኛ ወጪ (ribbed vs solid lower cost); ኮንዶሚኒየም ግንባታ ሪብድ ስላብ የግንባታ ዘዴ ለውጥ HCB (condo construction ribbed-slab method change).

**Honest Amharic result:** local-language search surfaced (a) practitioner how-to content confirming ribbed-HCB is named, normal practice [C30], and (b) condominium program news (lotteries, policy, the 2026 "mistake" statement [C25]) — but **nothing** tying the condo program to a slab-method change, and nothing on Nebyu. The central "condo program → ribbed/HCB adoption" causal claim is therefore **English-only / single-witness** and was *not* corroborated in Amharic. Several Facebook practitioner sources were search-snippet-only (platform blocked fetching) and need a logged-in local reviewer.

**Two-witness gaps flagged for re-pull:** CES 24 full PDF (Scribd-blocked); core.ac.uk theses (Negash composite-vs-RC; AASTU composite slab — 403/500); IASS 2024 PDF body (62% cost figure single-witness); the 28cm/6cm slab dimensions (not found in any primary source).
