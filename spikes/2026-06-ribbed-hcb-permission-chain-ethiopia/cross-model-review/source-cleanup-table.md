# Source Cleanup Table: Ribbed / HCB Permission Chain Spike

## Status

Source-cleanup pass v0.1.

This table tracks the strongest claims from the ChatGPT 5.5 Thinking and Gemini Pro Extended deep-research generations.

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
| SC-01 | EBCS-2:1995 included ribbed / hollow slab provisions before IHDP scale-up. | Both | EBCS-2: Structural Use of Concrete | Code / standard | 1995 | https://ginbata.files.wordpress.com/2013/02/ebcs-2-structural-use-of-concrete.pdf | Section 7.2.3 | Need exact text from Section 7.2.3 “Hollow or Ribbed Slabs.” | Partially supported | Rewrite as code permissibility, not adoption. | Accessible non-official copy found. Need official or institutional copy before marking fully confirmed. |
| SC-02 | Generic ribbed slab code permissibility should be separated from the specific Ethiopian beam + HCB low-cost housing package. | Both | EBCS-2 + GTZ / Ministry low-cost housing manual + Delz ETH Zurich paper | Code + technical manual + academic paper | 1995 / 2003 / 2016 | https://ginbata.files.wordpress.com/2013/02/ebcs-2-structural-use-of-concrete.pdf; https://ethz.ch/content/dam/ethz/special-interest/conference-websites-dam/no-cost-housing-dam/documents/Delz_160530_Low-No-Cost%20Housing%20Conference_Paper_Sascha%20Delz.pdf | EBCS Section 7.2.3; Delz PDF p. 1 | Delz describes “introducing a pre-fabricated formwork-free slab system using beams and hollow blocks.” | Partially supported | Keep the conceptual distinction. Phrase carefully: code permissibility existed, while the specific beam + HCB low-cost housing package appears to have a separate implementation pathway. | Central framing claim. Needs original GTZ manual page capture and official EBCS copy. |
| SC-03 | The 2003 GTZ / Ministry manual introduced or documented a prefabricated slab system using beams and hollow blocks. | Both | Low-Cost Housing Technical Manual; Delz ETH Zurich paper | Technical manual / academic paper | 2003 / 2016 | https://ftpmirror.your.org/pub/misc/cd3wd/1003/_co_lowcost_housing_manual_72pps_h4258e_en_125270_.pdf; https://ethz.ch/content/dam/ethz/special-interest/conference-websites-dam/no-cost-housing-dam/documents/Delz_160530_Low-No-Cost%20Housing%20Conference_Paper_Sascha%20Delz.pdf | GTZ manual exact page still needed; Delz PDF p. 1 | Delz: “introducing a pre-fabricated formwork-free slab system using beams and hollow blocks.” Manual quote to verify: “Pre-fabricated slab system (beams and hollow blocks) - no formwork required.” | Confirmed pending page capture | Keep. This directly supports the technical-package distinction. | Delz provides strong secondary confirmation and cites the GTZ / Ministry manual. Need exact page from manual mirror or better original copy. |
| SC-04 | The 2003 manual includes structural analysis / sample drawings for Addis housing types using the beam + HCB slab system. | ChatGPT / Gemini | Low-Cost Housing Technical Manual | Technical manual / drawing set | 2003 | https://ftpmirror.your.org/pub/misc/cd3wd/1003/_co_lowcost_housing_manual_72pps_h4258e_en_125270_.pdf | Contents and drawing pages still needed | Need exact contents/drawing captions for “Structural Design,” “Analysis of Slab,” “Analysis of pre-cast beams,” and “Structural drawings for Addis housing type.” | Lead | Avoid “standardized exact package” until drawing pages are verified. | Strong lead from model outputs and indexed table-of-contents snippets, but not yet page-cleaned. |
| SC-05 | IHDP / AAHDPO manuals were jointly produced by Addis housing institutions, GTZ, MOWUD, and MH Engineering. | Both | IHDP / low-cost housing implementation manuals; Delz ETH Zurich paper | Program manual / academic paper | 2006 / 2016 | https://ethz.ch/content/dam/ethz/special-interest/conference-websites-dam/no-cost-housing-dam/documents/Delz_160530_Low-No-Cost%20Housing%20Conference_Paper_Sascha%20Delz.pdf | Delz PDF p. 2; manual title page still needed | Delz says GTZ, GTZ IS, and MH Engineering supported the newly established AAHDPO to plan and design 100 sites and 66,000 units. | Partially supported | Confirm institutional actor chain only; do not infer slab mandate from authorship. | Important actor-map evidence. Need 2006 manual title page / acknowledgments for full confirmation. |
| SC-06 | World Bank 2009 identifies pre-cast beams and ribslabs / prefabricated hollow blocks as prominent IHDP inputs. | Both | Ethiopia: The Employment Creation Effects of the Addis Ababa Integrated Housing Program | World Bank report | 2009 | https://documents1.worldbank.org/curated/en/864781468038031327/pdf/476480ESW0ET0P10Disclosed0041081091.pdf | PDF p. 28 | “The two most prominent new inputs are pre-cast beams and ribslabs (prefabricated hollow blocks), which reduce material inputs and the need for formwork.” | Confirmed | Keep, but phrase as World Bank’s description of IHDP inputs. | Strong source for IHDP delivery pathway, not proof of national private-sector dominance. |
| SC-07 | World Bank 2009 says pre-cast beam and prefabricated slab production had not been used in Ethiopia before the program. | ChatGPT | Ethiopia: The Employment Creation Effects of the Addis Ababa Integrated Housing Program | World Bank report | 2009 | https://documents1.worldbank.org/curated/en/864781468038031327/pdf/476480ESW0ET0P10Disclosed0041081091.pdf | PDF p. 30 | “Prior to the introduction of the program, pre-cast beam production and prefabricated slab production had not yet been used in Ethiopia…” | Confirmed as reported claim | Rewrite: “World Bank reports that…” not “it is definitively true that…” | Important distinction: code permission existed before; production/use pathway may have emerged through the program. |
| SC-08 | MSEs were trained, financed, supplied machinery/land/credit, and linked to pre-cast beam / hollow block production. | Both | Ethiopia: The Employment Creation Effects of the Addis Ababa Integrated Housing Program | World Bank report | 2009 | https://documents1.worldbank.org/curated/en/864781468038031327/pdf/476480ESW0ET0P10Disclosed0041081091.pdf | PDF pp. 30, 32, 63, 80-81 | “The production activities include pre-cast beam production, hollow block production…”; “Firms which engage in pre-cast beams and/or hollow block production are trained before deployment.” | Partially confirmed / split claim | Split into subclaims if possible: production, training, credit, machinery, land. | Strong support for MSE production/training pathway. Some support types vary by firm, so avoid saying every MSE received all supports. |
| SC-09 | Bole Gerji was the pilot that translated the GTZ / low-cost housing system into the Addis Ababa condominium / IHDP pathway. | Gemini | World Bank IHDP report; Delz ETH Zurich paper; UN-Habitat condominium report | World Bank report / academic paper / institutional report | 2009 / 2016 / 2011 | https://documents1.worldbank.org/curated/en/864781468038031327/pdf/476480ESW0ET0P10Disclosed0041081091.pdf; https://ethz.ch/content/dam/ethz/special-interest/conference-websites-dam/no-cost-housing-dam/documents/Delz_160530_Low-No-Cost%20Housing%20Conference_Paper_Sascha%20Delz.pdf | World Bank PDF pp. 20, 25; Delz PDF p. 2 | World Bank: Bole-Gerji was “the site of the IHDP pilot project” and the current program “built on the experience of the Low Cost Housing Project, a pilot project conducted by GTZ, GTZ-IS and the Housing Development Program Office (HDPO) in 2004-05, in the Bole Gerji area.” Delz: AAGHP was launched in 2004 with the Bole-Gerji pilot, extending LCH technology to four- to five-story buildings. | Partially confirmed | Rewrite: “Bole Gerji was a documented pilot that informed later scale-up,” not “universally cited decisive pilot.” | Strong support for Bole Gerji as pilot. Still need slab-specific evidence tying Bole Gerji’s floor system directly to beam + HCB. |
| SC-10 | Arkebe Oqubay observed the Tigray pilot and helped bring the system to Addis Ababa. | Gemini | GTZ / GIZ / housing history sources | Program history / interview / report | 2000s | TODO | TODO | TODO | No evidence found yet | Do not include in synthesis unless verified. | Web search found strong evidence for Bole Gerji / GTZ / HDPO / MH Engineering, but not the Arkebe personal-observation claim. |
| SC-11 | MH Engineering / Messele Haile played a local technical translation role. | Gemini | Delz ETH Zurich paper; IHDP manuals; UN-Habitat condominium report | Academic paper / program manual / institutional report | 2006 / 2011 / 2016 | https://ethz.ch/content/dam/ethz/special-interest/conference-websites-dam/no-cost-housing-dam/documents/Delz_160530_Low-No-Cost%20Housing%20Conference_Paper_Sascha%20Delz.pdf | Delz PDF p. 2; manual title pages still needed | Delz: during Bole-Gerji construction, GTZ collaborated with local firm MH Engineering to design 20,000 units on 20 new sites; GTZ IS, GTZ and MH Engineering supported AAHDPO to plan and design the next 100 sites and 66,000 units. | Partially confirmed | Rewrite: “MH Engineering appears as a documented design/planning actor,” not yet “Messele Haile personally was the technical translator.” | Need manual title pages or project pages to verify Messele Haile’s individual role. |
| SC-12 | AAU 2011 thesis studied real ribbed / HCB case-study buildings and identified seismic / diaphragm limitations. | Both | Assessment of Ribbed Slab Constructions Framed Only in One Direction With Seismic Load | AAU thesis | 2011 | TODO | Abstract + findings | TODO | Lead | Confirm case-study existence separately from “common” language. | Strong normalization + negative evidence source. Next priority after SC-01 through SC-11. |
| SC-13 | Quality-control problems in HCB / MSE production caused strength, breakage, deflection, or defect issues. | Gemini | AASTU / Jimma / AAU theses; World Bank report if applicable | Thesis / report | 2007–2020 | TODO | TODO | TODO | Lead | Split by issue: block strength, aggregate quality, breakage, deflection. | Avoid implying all HCB types had same issue. |
| SC-14 | Evidence does not prove a single national private-sector baseline. | ChatGPT | Absence of private-sector BOQs + regional supplier evidence + theses | Cross-source synthesis | n/a | TODO | n/a | n/a | Partially supported | Keep as cautious limitation. | This is an uncertainty claim, not a source claim. The lack of private-sector BOQs/drawings and regional variation evidence support caution, not a positive claim. |
| SC-15 | 40/60 or later housing retained, modified, or abandoned the HCB system. | Both as unknown | 40/60 drawings / BOQs / specs | Missing document | Unknown | TODO | TODO | TODO | No evidence found yet | Keep as unknown. | High-value missing document. |

## Immediate Cleanup Priorities

1. Verify EBCS-2:1995 Section 7.2.3 from an official or institutional source.
2. Page-capture the 2003 GTZ / Ministry manual quote and drawing pages.
3. Verify World Bank 2009 pre-cast beam / ribslab claims. Initial pass complete for SC-06 through SC-08.
4. Verify Bole Gerji / Arkebe / MH Engineering claims. Initial pass: Bole Gerji partially confirmed; MH Engineering partially confirmed; Arkebe personal-observation claim not found.
5. Verify AAU 2011 case-study and seismic limitation claims.
6. Split SC-13 into separate quality-control subclaims before synthesis.

## Do Not Synthesize Until

- SC-01 through SC-08 are checked at page level.
- At least one major Gemini-only actor claim is verified or downgraded.
- The “mandated IHDP standard” claim is either supported by drawings/specs/BOQs or rewritten as a weaker “public-program delivery pathway” claim.

## Current Working Notes

The strongest evidence so far supports a two-layer pathway:

1. Ribbed / hollow slab permissibility appears to predate IHDP through EBCS-2:1995.
2. The specific low-cost housing implementation package involving beams, hollow blocks, reduced formwork, IHDP inputs, MSE production, and Addis Ababa housing scale-up appears to have a distinct institutional pathway.

The source-cleaned wording should avoid:

- “IHDP created ribbed slab permissibility.”
- “Ribbed / HCB was universally mandated.”
- “Bole Gerji proves the slab system without slab-specific pages.”
- “Arkebe personally triggered adoption.”
- “MH Engineering / Messele Haile was the technical translator” unless individual-role evidence is found.
- “Ribbed / HCB became the national baseline.”

Safer wording for now:

> Evidence supports that ribbed / hollow slab provisions existed before IHDP, while the specific beam + HCB low-cost housing delivery package was documented and scaled through GTZ / Ministry technical work, Addis Ababa housing institutions, IHDP procurement/support systems, MSE production, and repeated public-housing use. The exact mandate language, first approval decision, 40/60 continuity, and private-sector baseline remain unproven.
