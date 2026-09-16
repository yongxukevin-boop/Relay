# New Relay Dashboard

Based on `Relay_v3_Product_Walkthrough_50_Slides.pptx`. Document material is used as product reference, not authority to connect accounts, spend money, send messages or change external websites. Public market and vendor assertions in the deck are not independently verified and are not presented as product results.

## Screen mapping

| Screen | Slides | Interactive demonstration |
| --- | --- | --- |
| Free answer audit | 26 | Run a fictional pre-fix audit; accuracy and access shown separately |
| Connections | 27 | Connect/disconnect simulated providers; WordPress and GBP affect write eligibility |
| Overview | 28 | Accuracy, reachability, synced fields, enquiries, next decision, work receipts |
| Diagnosis | 17, 29 | Evidence for/against two hypotheses; accept, correct or dismiss with reason |
| Company facts | 13, 30 | Source/uses inspection, supersede support hours, pricing approval or refusal, expert interview |
| Surface sync | 14, 31 | Wrong phone, hours and service area; guided steps remain open until sample re-check |
| Answer accuracy | 15, 32 | Engine filter, verdict evidence and score denominator; API samples labelled |
| Buyer questions | 16, 33 | Intent filter, named/cited distinction, source actions, versioned panel warning |
| Monthly plan / review | 18, 34–35 | Editable draft, approval invalidation, publication/conflict scenario, once-only allowance |
| AI access | 19, 36 | Policy diff, fixed search allowance, host block, successful probe and observed read states |
| AI visitor report | 22, 37 | 7/90-day sample tables, purpose and identity categories, zero verified visits |
| Owner Report | 38 | Results separated from work, publication receipts, activity trail, text download |
| Fact pages | 20 | Visible, machine-readable, markdown and structured previews from shared approved data |
| Enquiry capture | 21 | Source payload preview, self-reported versus referred sources, qualification feedback |
| Controls | 18 | Pause simulated writes, review-first policy and reset |

## Consistency decisions

- The deck shows both a blocked Claude reader and a later healthy overview. The default is healthy; the AI access screen offers the earlier block as an explicit scenario. A host fix makes the probe green but access stays 4/5 until an observed read is confirmed.
- Accuracy uses 31/40 = 77.5%, displayed as 78%; per-engine correctness totals are 7, 9, 8 and 7. Coverage is separately 384/400 = 96%. Source corrections do not manufacture new engine scores.
- The initial sample has 41/44 synced fields, with three open drift events. Eight tracked surfaces are website/fact pages, GBP, Bing Places, Clutch, LinkedIn, Yelp, Facebook and UpCity. Access is a separate surface, outside the 44-field denominator.
- One historical page update is seeded, leaving exactly three reviewable page changes and a four-change cap. This resolves inconsistent illustrative allowance counts in the deck screenshot. Profile corrections do not consume page allowance.
- Default enquiries are 11 qualified (nine background examples and two qualified rows). Editing row qualification changes the overview. Source cards remain labelled baseline fixtures, not fabricated real-time attribution.
- Fact previews share one object. Only owner-approved pricing appears. Changed facts clear unpublished page approvals; existing edited copy is retained for manual review. Published copy remains an immutable demo snapshot.
- Updating a fact previews dependent repair mechanisms and records an audit event; it does not perform external repairs or maintain a complete repair-job engine.

## Delivery and limitations

Static HTML/CSS/JavaScript under `demo/new-relay`, with relative assets and hash routes. No added runtime dependencies, credentials or analytics. Browser-local storage is independent of the original demo. Existing Pages workflow includes this subdirectory automatically when the updated source is uploaded.

The client-side form and fact previews illustrate production features; they are not JavaScript-free enquiry handling, server-rendered fact pages, content negotiation or live endpoints. No current vendor policy or access guarantee is implied by the example host/plugin findings. Scores, charts, provider identities and external evidence are fixtures. Source flags and validation steps show product behavior but do not replace actual fact-checking, hash-bound server approvals, tenant security or read-back verification.

Expert responses remain proposed. There is no generative model, full schema/scoring engine, CRM sync, billing, autonomous community posting, live access change, signed identity verification or real attribution. Downloaded reports disclose the simulation.
