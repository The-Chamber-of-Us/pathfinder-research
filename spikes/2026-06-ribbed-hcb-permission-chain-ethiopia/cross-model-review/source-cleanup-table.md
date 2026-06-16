# Source Cleanup Table: Ribbed / HCB Permission Chain Spike

## Status

Scaffold.

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
|---|---|---|---|---|---:|---|---:|---|---|---|---|
| SC-01 | EBCS-2:1995 included ribbed / hollow slab provisions before IHDP scale-up. | Both | EBCS-2: Structural Use of Concrete | Code / standard | 1995 | TODO | Section 7.2.3 | TODO | Lead | Rewrite as code permissibility, not adoption. | Need official or high-quality copy. |
| SC-02 | Generic ribbed slab code permissibility should be separated from the specific Ethiopian beam + HCB low-cost housing package. | Both | EBCS-2 + GTZ/Ministry low-cost housing manual | Code + technical manual | 1995 / 2003 | TODO | TODO | TODO | Lead | Keep as conceptual distinction if both sources support. | Central framing claim. |
| SC-03 | The 2003 GTZ / Ministry manual introduced or documented a prefabricated slab system using beams and hollow blocks. | Both | Low-Cost Housing Technical Manual | Technical manual | 2003 | TODO | TODO | “Pre-fabricated slab system (beams and hollow blocks)” or exact equivalent | Lead | If quote is found, mark confirmed. | Core source-cleaning target. |
| SC-04 | The 2003 manual includes structural analysis / sample drawings for Addis housing types using the beam + HCB slab system. | ChatGPT / Gemini | Low-Cost Housing Technical Manual | Technical manual / drawing set | 2003 | TODO | TODO | TODO | Lead | Avoid “standardized exact package” until drawing pages are verified. | Need drawing page capture if possible. |
| SC-05 | IHDP / AAHDPO manuals were jointly produced by Addis housing institutions, GTZ, MOWUD, and MH Engineering. | Both | IHDP / low-cost housing implementation manuals | Program manual | 2006 | TODO | Title page / acknowledgments | TODO | Lead | Confirm institutional authorship only; do not infer slab mandate from authorship. | Important actor-map evidence. |
| SC-06 | World Bank 2009 identifies pre-cast beams and ribslabs / prefabricated hollow blocks as prominent IHDP inputs. | Both | World Bank IHDP employment / MSE report | World Bank report | 2009 | TODO | TODO | TODO | Lead | If exact quote found, mark confirmed. | High-value adoption-pathway source. |
| SC-07 | World Bank 2009 says pre-cast beam and prefabricated slab production had not been used in Ethiopia before the program. | ChatGPT | World Bank IHDP employment / MSE report | World Bank report | 2009 | TODO | TODO | TODO | Lead | Rewrite carefully: “World Bank reports…” not absolute fact unless corroborated. | Must reconcile with 1995 code permissibility. |
| SC-08 | MSEs were trained, financed, supplied machinery/land/credit, and linked to pre-cast beam / hollow block production. | Both | World Bank report + GTZ / ministry manuals | Report / manual | 2003–2009 | TODO | TODO | TODO | Lead | Separate support types: training, credit, machinery, production. | Do not collapse into one mega-claim unless all parts verified. |
| SC-09 | Bole Gerji was the pilot that translated the GTZ / Tigray low-cost housing system to Addis Ababa. | Gemini | GTZ / GIZ / housing history sources | Program history / report | 2000s | TODO | TODO | TODO | Lead | Treat as promising lead, not finding. | Needs direct source. |
| SC-10 | Arkebe Oqubay observed the Tigray pilot and helped bring the system to Addis Ababa. | Gemini | GTZ / GIZ / housing history sources | Program history / interview / report | 2000s | TODO | TODO | TODO | Lead | Do not include in synthesis unless verified. | Potentially important actor chain. |
| SC-11 | MH Engineering / Messele Haile played a local technical translation role. | Gemini | Manual title pages / project reports | Manual / project record | 2003–2006 | TODO | TODO | TODO | Lead | Verify exact role: author, consultant, designer, implementer. | Important for permission-chain map. |
| SC-12 | AAU 2011 thesis studied real ribbed / HCB case-study buildings and identified seismic / diaphragm limitations. | Both | Assessment of Ribbed Slab Constructions Framed Only in One Direction With Seismic Load | AAU thesis | 2011 | TODO | Abstract + findings | TODO | Lead | Confirm case-study existence separately from “common” language. | Strong normalization + negative evidence source. |
| SC-13 | Quality-control problems in HCB / MSE production caused strength, breakage, deflection, or defect issues. | Gemini | AASTU / Jimma / AAU theses; World Bank report if applicable | Thesis / report | 2007–2020 | TODO | TODO | TODO | Lead | Split by issue: block strength, aggregate quality, breakage, deflection. | Avoid implying all HCB types had same issue. |
| SC-14 | Evidence does not prove a single national private-sector baseline. | ChatGPT | Absence of private-sector BOQs + regional supplier evidence + theses | Cross-source synthesis | n/a | TODO | n/a | n/a | Partially supported | Keep as cautious limitation. | This is an uncertainty claim, not a source claim. |
| SC-15 | 40/60 or later housing retained, modified, or abandoned the HCB system. | Both as unknown | 40/60 drawings / BOQs / specs | Missing document | Unknown | TODO | TODO | TODO | No evidence found yet | Keep as unknown. | High-value missing document. |

## Immediate Cleanup Priorities

1. Verify EBCS-2:1995 Section 7.2.3.
2. Verify the 2003 GTZ / Ministry manual quote and drawing pages.
3. Verify the World Bank 2009 pre-cast beam / ribslab claims.
4. Verify Bole Gerji / Arkebe / MH Engineering claims.
5. Verify AAU 2011 case-study and seismic limitation claims.

## Do Not Synthesize Until

- SC-01 through SC-08 are checked at page level.
- At least one major Gemini-only actor claim is verified or downgraded.
- The “mandated IHDP standard” claim is either supported by drawings/specs/BOQs or rewritten as a weaker “public-program delivery pathway” claim.
