# Source Cleanup Table: Ethiopia Floor-System Antecedents Spike

## Status

Scaffold v0.1.

This table tracks the highest-priority claims from the cross-model review of the ChatGPT 5.5 Thinking and Gemini Pro Extended deep-research generations.

The goal is to convert model claims into page-level, audit-ready evidence.

Raw model outputs are not evidence. Each claim needs source title, institution, year, URL, page number, exact quote, support level, and downgrade decision.

## Evidence Status Labels

- `Confirmed` — direct source quote/page supports the claim.
- `Partially supported` — source supports part of the claim, but not the full wording.
- `Lead` — plausible claim from model output, but not yet source-cleaned.
- `Overstated` — source may support a weaker version only.
- `Contradicted` — source or another source weakens/rejects the claim.
- `No evidence found yet` — searched but not verified.

## Source Cleanup Table

| ID | Claim | Model Source | Expected Source | Source Type | Year | URL | Page Needed | Exact Quote Needed | Current Status | Downgrade / Rewrite | Notes |
|---|---|---|---|---|---:|---|---|---|---|---|---|
| ASC-01 | ESCP-2:1983 existed as Ethiopia’s pre-1995 structural-concrete code. | Both | Ethiopian Standard Code of Practice for Structural Use of Concrete | Code / standard | 1983 | TODO | Title page / reference-list page | Exact title, issuing institution, and year. | Lead | Keep as “ESCP-2:1983 existed” until original code or institutional reference is recovered. | Search results and model outputs point to a 1983 Ministry of Construction structural-concrete code, but original full text still needs retrieval. |
| ASC-02 | ESCP-2:1983 included ribbed slab / hollow slab provisions before EBCS-2:1995. | Both, but more cautious in ChatGPT | ESCP-2:1983 full text; ESCP-2 Part II Design Aids; later teaching notes citing ESCP-2/83 | Code / design aid / teaching material | 1983 / 1991 / later | TODO | Slab chapter / ribbed slab section | Exact ESCP-2/83 slab text, if it exists. | Lead | Do not claim explicit 1983 ribbed/hollow slab permission until original pages are found. | This is a key source-cleaning target. Current evidence supports ESCP-2 existence more than specific ribbed/hollow slab content. |
| ASC-03 | 1991 Limit State Design Aids according to ESCP-2 existed. | Both | Limit State Design Aids for Reinforced Concrete Members According to ESCP-2 | Design aid | 1991 | TODO | Title page / reference-list page | Exact title, institution, year, and scope. | Lead | Keep as “a 1991 design-aid publication existed” until original document is recovered. | Search results point to the title and issuer, but not the full document contents. |
| ASC-04 | The 1991 Limit State Design Aids included slab design aids or helped engineers design ribbed/hollow slabs. | Both, but more inferential in Gemini | Limit State Design Aids for Reinforced Concrete Members According to ESCP-2 | Design aid | 1991 | TODO | Slab tables / examples / contents | Exact table of contents or slab-design provisions. | Lead | Treat as inferred until original design-aid contents are found. | The mechanism is plausible, but title/issuer alone is not enough. |
| ASC-05 | EBCS-2:1995 Section 7.2.3 explicitly covered hollow or ribbed slabs. | Both | EBCS-2: Structural Use of Concrete | Code / standard | 1995 | https://ginbata.files.wordpress.com/2013/02/ebcs-2-structural-use-of-concrete.pdf | Section 7.2.3; PDF p. 84 if copy pagination holds | Exact text under “7.2.3 Hollow or Ribbed Slabs,” including size, topping, rib, reinforcement, and transverse rib provisions. | Partially supported | Rewrite as code permission, not built practice. | Accessible non-official copy found. Search result exposes “7.2.3 Hollow or Ribbed Slabs.” Need page capture and preferably official copy. |
| ASC-06 | EBCS-2:1995 proves code permission but not widespread pre-IHDP practice. | Both | EBCS-2:1995 + absence of pre-1995 built-project evidence | Cross-source synthesis | 1995 | https://ginbata.files.wordpress.com/2013/02/ebcs-2-structural-use-of-concrete.pdf | Section 7.2.3 plus built-project evidence search | Code text plus negative evidence register. | Partially supported | Keep as limitation: “permission is not practice.” | This is an evidence-logic claim. It depends on both confirmed code text and lack of pre-1995 built ribbed/HCB examples. |
| ASC-07 | IMS / PBPPE was established in the 1980s with Yugoslav technical assistance. | Both | AAU thesis item; IMS technology-transfer paper; PBPPE/ECWC records | Thesis / technology-transfer paper / institutional record | 1983–1986 | https://etd.aau.edu.et/items/c036d100-d8e8-40dd-a0b2-3829eb2ea565; https://etd.aau.edu.et/items/a766a116-9bea-4260-b6d6-586ea6d657e0 | Thesis item page / abstract / intro | Exact establishment date and Yugoslav-assistance wording. | Partially supported | Use date range until primary records settle chronology. | Search results support 1984 establishment with Yugoslav assistance; other sources give 1983, 1985, 1986 production start, or 1987. |
| ASC-08 | IMS / PBPPE was a precast skeleton / flat-slab / post-tensioned system, not a ribbed/HCB beam-and-block system. | Both | AAU PBPPE thesis; IMS system descriptions | Thesis / technical history | 1980s–1998 | https://etd.aau.edu.et/items/c036d100-d8e8-40dd-a0b2-3829eb2ea565 | System description pages | Exact description of IMS structural system, components, slabs, columns, post-tensioning, or assembly. | Lead | Keep as “institutional antecedent, not typological ancestor” once verified. | Central distinction. Needs exact thesis or IMS paper quote. |
| ASC-09 | PBPPE provided an institutional template for state-led prefabrication and industrialized building production. | Both | AAU PBPPE thesis; IMS transfer paper; ECWC/PBPPE records | Thesis / institutional record | 1984–1998 | https://etd.aau.edu.et/items/c036d100-d8e8-40dd-a0b2-3829eb2ea565 | Thesis intro / conclusions | Exact evidence for factory production, state enterprise, manuals, training, catalogs, QC, or standard details. | Lead | Phrase as institutional precedent, not direct causal reuse by IHDP. | Strong causal hypothesis. Direct reuse by later programs is not yet proven. |
| ASC-10 | PBPPE built-project evidence includes Bole Road 150-flat project or other early prefabricated buildings. | ChatGPT | AAU thesis / retrospective thesis / PBPPE project records | Thesis / project record | 1980s–1990s | TODO | Project-history pages | Exact project name, date, system, number of flats, and source basis. | Lead | Treat as retrospective unless primary project records are found. | Important for “actually built” evidence, but model outputs suggest current evidence is retrospective and date-conflicted. |
| ASC-11 | 1999 Standard School Project HBC variant existed. | ChatGPT | Standard School Project final drawings and BOQs; JICA reference lists | Government drawing / BOQ / reference list | 1999 | TODO | Reference-list page / drawing title page | Exact title mentioning “HBC Variant.” | Lead | Keep as alternative-construction variant, not HCB slab evidence. | HBC may refer to hollow concrete block construction generally, not slab systems. |
| ASC-12 | 1999 Standard School Project prefab concrete variant existed. | ChatGPT | Standard School Project final drawings and BOQs; JICA reference lists | Government drawing / BOQ / reference list | 1999 | TODO | Reference-list page / drawing title page | Exact title mentioning “Prefab Concrete Variant.” | Lead | Keep as ministry-standardized prefab pathway, not ribbed/HCB proof. | Useful evidence for pre-IHDP institutional openness to variants. |
| ASC-13 | The 2003 GTZ / Ministry low-cost housing manual documented a pre-fabricated slab system using beams and hollow blocks. | Both | Low-cost Housing Technical Manual | Technical manual | 2003 | https://ftpmirror.your.org/pub/misc/cd3wd/1003/_co_lowcost_housing_manual_72pps_h4258e_en_125270_.pdf | Introduction / technological concept section | “Pre-fabricated slab system (beams and hollow blocks) - no formwork required.” | Confirmed pending page capture | Keep. This is direct evidence for the specific beam + HCB package. | Search result exposes the exact phrase and table of contents. Need page capture / PDF page number. |
| ASC-14 | The 2003 GTZ manual includes slab HCB, precast beams, structural design, analysis of slab, analysis of pre-cast beams, and structural drawings. | Both | Low-cost Housing Technical Manual | Technical manual / drawing set | 2003 | https://ftpmirror.your.org/pub/misc/cd3wd/1003/_co_lowcost_housing_manual_72pps_h4258e_en_125270_.pdf; https://www.coursehero.com/file/88334207/en-low-cost-housing-ethiopia-technical-manual-Ipdf/ | Table of contents; pp. for Slab HCB, Precast Beams, Structural Design, Analysis of Slab, Structural Drawings | Exact TOC lines and page references. | Partially supported | Keep as manual-content claim. Do not yet infer standardization across all IHDP. | Indexed source exposes the TOC lines. Need exact PDF page capture from manual. |
| ASC-15 | Bole-Gerji was the pilot / bridge into the Addis Ababa low-cost housing / condominium pathway. | Both, especially Gemini | World Bank IHDP report; Delz ETH Zurich paper; GTZ / housing records | World Bank report / academic paper / program history | 2004–2009 / 2016 | https://documents1.worldbank.org/curated/en/864781468038031327/pdf/476480ESW0ET0P10Disclosed0041081091.pdf; https://ethz.ch/content/dam/ethz/special-interest/conference-websites-dam/no-cost-housing-dam/documents/Delz_160530_Low-No-Cost%20Housing%20Conference_Paper_Sascha%20Delz.pdf | World Bank pilot pages; Delz pp. 1–2 | Exact wording identifying Bole-Gerji as the pilot and linking it to later scale-up. | Lead | Use “documented pilot / bridge,” not “decisive tipping point,” until page-cleaned. | Prior permission-chain source cleanup partially confirmed this, but this spike still needs its own table entry. |
| ASC-16 | Bole-Gerji specifically used the beam + hollow-block slab system. | Gemini | GTZ manual; Delz; Bole-Gerji project drawings / reports | Manual / project record / academic paper | 2003–2004 | https://ethz.ch/content/dam/ethz/special-interest/conference-websites-dam/no-cost-housing-dam/documents/Delz_160530_Low-No-Cost%20Housing%20Conference_Paper_Sascha%20Delz.pdf | Bole-Gerji project/system pages | Exact quote linking Bole-Gerji to beams + hollow blocks, not just low-cost housing generally. | Lead | Do not claim slab-specific Bole-Gerji use unless source explicitly ties the system to the site. | High-value but dangerous claim. |
| ASC-17 | AAU 1998 thesis studied PBPPE / prefabrication / IMS in Ethiopia. | Both | Prefabrication of Structural Elements: A Case Study | AAU thesis | 1998 | https://etd.aau.edu.et/items/c036d100-d8e8-40dd-a0b2-3829eb2ea565 | Thesis abstract / intro / conclusion | Exact thesis title, author, year, and PBPPE/IMS scope. | Partially supported | Keep as university-normalization evidence for prefabrication, not ribbed/HCB. | AAU item page confirms thesis presence and abstract snippet. Need full thesis quote. |
| ASC-18 | AAU 2004 thesis studied composite concrete slab systems using hollow blocks and precast slab/beam members. | Both | Use of Composite Concrete Slab System Using Hollow Blocks and Precast Slab/Beam Member | AAU thesis | 2004 | https://etd.aau.edu.et/bitstreams/5c2178e8-539a-4e99-b706-a1419d6bb8b4/download | Thesis title page / abstract / design comparison pages | Exact thesis title, abstract text, and any ribbed slab / hollow-block / precast beam design comparison language. | Lead | Keep as academic boundary-band normalization. Do not claim it directly validated GTZ/MH unless thesis says so. | Search result points to hollow concrete blocks used for ribbed slabs and cost/design comparison. Needs page-cleaning. |
| ASC-19 | Formwork, timber scarcity, cost, or deforestation drove interest in beam + HCB / formwork-free systems. | Both, especially Gemini | GTZ manual; Delz; AAU 2004 thesis; low-cost housing reports | Manual / thesis / academic paper | 2003–2004 / 2016 | https://ftpmirror.your.org/pub/misc/cd3wd/1003/_co_lowcost_housing_manual_72pps_h4258e_en_125270_.pdf; https://ethz.ch/content/dam/ethz/special-interest/conference-websites-dam/no-cost-housing-dam/documents/Delz_160530_Low-No-Cost%20Housing%20Conference_Paper_Sascha%20Delz.pdf | GTZ rationale / environmental considerations / thesis intro | Exact wording about no formwork, timber, cost, construction delay, or deforestation. | Lead | Use as causal driver only after exact quote. | Manual phrase “no formwork required” is found; broader timber/deforestation cost driver needs exact support. |
| ASC-20 | University teaching or design culture normalized ribbed/HCB or related nontraditional systems before 2004. | Both | AAU theses; RC lecture notes; ESCP/EBCS teaching materials | Thesis / course note / design report | 1998–2004 | https://smartaau.files.wordpress.com/2014/03/rcs-i-lecture-note.pdf | Thesis pages / course-note pages | Exact evidence of teaching, thesis supervision, design examples, or use of ESCP/EBCS design aids. | Lead | Separate prefabrication teaching from ribbed/HCB teaching. | Strongest current evidence is thesis work by 1998 and 2004; broader teaching normalization still needs documents. |

## Immediate Cleanup Priorities

1. Find the full ESCP-2:1983 text and check whether it includes ribbed or hollow slab provisions.
2. Find the full 1991 Limit State Design Aids according to ESCP-2 and check whether it includes slab or ribbed-slab tables/examples.
3. Page-capture EBCS-2:1995 Section 7.2.3 “Hollow or Ribbed Slabs.”
4. Page-clean the IMS / PBPPE AAU 1998 thesis and settle the establishment-date/system-typology claims.
5. Search for primary or near-primary PBPPE built-project evidence, especially Bole Road 150-flat project.
6. Locate 1999 Standard School Project HBC and prefab concrete variant drawings/BOQs.
7. Page-capture the 2003 GTZ manual beam + HCB slab text, slab HCB / precast beam sections, structural analysis pages, and drawings.
8. Page-clean Bole-Gerji as pilot and separately verify whether the beam + HCB floor system is explicitly tied to Bole-Gerji.
9. Page-clean AAU 2004 composite slab thesis.
10. Source-clean the formwork/timber/deforestation cost driver.
11. Distinguish university thesis evidence from broader teaching/curriculum evidence.
12. Keep all claims separated by system family: ribbed slab, hollow-block slab, precast beam + block, IMS, steel-deck composite, hollow-core.

## Do Not Synthesize Until

- ASC-01 through ASC-05 are checked at page level.
- ASC-07 through ASC-10 clarify the IMS/PBPPE chronology and system typology.
- ASC-13 through ASC-16 confirm the GTZ/Bole-Gerji beam + HCB pathway without overclaiming.
- ASC-18 verifies the AAU 2004 thesis title, abstract, and system family.
- The “pre-code antecedent” story is explicitly separated from the “1999–2004 beam + HCB transfer” story.

## Current Working Notes

The strongest current framing is:

1. The evidence does not justify a forced 1960s origin story.
2. The pre-permission trail appears to begin mainly with 1980s Ethiopian structural-code development and imported prefabrication institutions.
3. EBCS-2:1995 clearly matters for ribbed/hollow slab code permission, but ESCP-2:1983 and the 1991 design aids may be the earlier design-culture layer.
4. IMS/PBPPE is an institutional prefabrication antecedent, not a direct ribbed/HCB typological ancestor.
5. The specific beam + HCB package appears most clearly in the 1999–2003 GTZ low-cost housing pathway and the 2004 AAU thesis boundary band.
6. Code permission, design aids, teaching, pilot construction, and actual practice must remain separate.

Safer wording for now:

> The pre-IHDP acceptability of ribbed / HCB and related nontraditional floor systems in Ethiopia appears to have emerged from multiple antecedent mechanisms rather than a single origin. The evidence does not currently support a 1960s starting point. The strongest trail begins in the 1980s with domestic structural-code formation and Yugoslav-assisted prefabrication, continues through the 1991 ESCP-2 design-aid layer and EBCS-2:1995 ribbed/hollow slab provisions, and then becomes specific to the beam + HCB floor package through the 1999–2003 GTZ low-cost housing transfer and 2004 AAU thesis work. The direct continuity between these mechanisms remains partly inferred and requires page-level source cleanup.
