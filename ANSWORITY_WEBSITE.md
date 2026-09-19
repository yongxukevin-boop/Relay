# Answority website preview

Intended domain: **answority.com**. No custom domain, DNS, registration, booking or lead capture is configured.

Open `/answority/index.html` for the marketing website and `/answority/dashboard/index.html` for the branded product demo. Locally, run `node serve.cjs` and open `http://127.0.0.1:4173/answority/index.html`.

## Design and positioning

An original ivory, violet and charcoal design with a product-led explanation of answer accuracy, approved facts and enquiry evidence. Reference sites reviewed:

- https://www.tryprofound.com — product evidence and a clear platform story.
- https://www.conductor.com — explain the connected workflow from visibility to improvement.
- https://www.gushwork.ai — connect the product to enquiries and buyer outcomes.

No competitor content, testimonials, logos, revenue claims or customer results are reused. The dashboard screenshot is captured from this project's fictional workspace. The historic Relay demos remain unchanged.

## Interactions and boundaries

- Before/after answer illustration, four workflow tabs with keyboard navigation, example audit dialog, privacy dialog, FAQ and mobile menu.
- Fully interactive branded dashboard, with local browser storage isolated from the Relay version.
- Fictional sample evidence throughout. No live AI engines, website changes, integrations, forms or analytics.
- Google Fonts is the only external website dependency; system fonts provide a fallback.
- Production booking, audits, integration services, legal policies and custom-domain hosting still need implementation before a commercial launch.

## Publish and verify

The existing GitHub workflow publishes the `demo` directory. This site lives in `demo/answority`, preserving earlier URLs. Do not add a CNAME until domain ownership and DNS configuration are confirmed.

Browser validation covers website interactions, all internal link HTTP responses, four viewport sizes, and the inherited dashboard's routes and approval/state workflows. Local QA scripts and screenshots are in `.qa` and are not published.
