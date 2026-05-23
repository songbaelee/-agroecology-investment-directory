# Agroecology Investment Directory

A living reference directory of funds, cooperatives, and investment vehicles with portfolio activity aligned to agroecological principles.

## What this is

This is a personal research project and public resource tracking financial vehicles — investment funds, cooperative credit funds, accelerators, and lending vehicles — that have any meaningful connection to agroecology in their portfolio or mandate.

It is a learning resource, not investment advice. Funds are included if any part of their portfolio follows agroecological principles, whether that is an explicit mandate, an aligned strategy, or adjacent practice. The alignment level is noted on each entry.

## What is agroecology?

Agroecology is a holistic approach to food and farming that integrates ecological principles into agricultural systems. It draws on the FAO's 13 principles of agroecology and encompasses practices including soil health, biodiversity, Indigenous knowledge systems, cooperative governance, and food sovereignty. It is distinct from — and broader than — organic certification or regenerative agriculture, though these often overlap.

## What's in here

- `funds.json` — the primary data file. One object per fund, with fields covering geography, financial details, agroecology alignment, impact metrics, portfolio organizations, governance, notable quotes, and sources.
- `index.html` — a static directory site that reads from `funds.json` and renders filterable fund cards. Hosted via GitHub Pages.

## Current funds documented

| Fund | Geography | Type | Alignment |
|---|---|---|---|
| The Reciprocity Fund | Latin America | Impact lending | Aligned |
| FINAPOP | Brazil | Cooperative credit | Explicit mandate |
| NESsT Lirio Fund | Andes-Amazon | SME debt fund | Aligned |
| Barka Fund | Sub-Saharan Africa | Venture + accelerator | Aligned |
| Pachamama Coffee Cooperative | Global / California | Farmer cooperative | Aligned |
| Neycha Accelerator & Fund | Uganda & Kenya | Revolving loan + accelerator | Explicit mandate |

## How data is structured

Each fund entry in `funds.json` captures:

- **Organizational** — name, manager, legal structure, founding year, website, headquarters
- **Geographic** — HQ, countries of operation, target regions
- **Financial** — fund size, total disbursed, ticket size range, interest rate, investor access
- **Agroecology alignment** — explicitness of mandate, principles represented, certifications referenced
- **Impact** — enterprises funded, people reached, hectares preserved or restored
- **Portfolio** — notable investee organizations with descriptions and value chain positions
- **Governance** — key funders, partner organizations, governance model, key people
- **Context** — narrative summary, notable quotes, source URLs, last verified date

Fields are `null` where information is not yet known — these represent research gaps to fill over time.

## Roadmap

- [ ] Grow to ~20 funds
- [ ] Add filtering by agroecology principle
- [ ] Add a "research gaps" view highlighting funds with incomplete data
- [ ] Explore whether a simple contribution process makes sense

## Data sources

All data is sourced from public records including fund websites, ImpactAlpha, Stanford Social Innovation Review, Business Wire, WRI Africa, Biovision Foundation, and other impact media. Each fund entry links to its primary sources. Last verified date is noted on every entry.

## Contributing

This is currently maintained by one person. If you know of a fund that should be included, or have more accurate data for an existing entry, feel free to open an issue.

---

*This directory is not affiliated with any of the funds listed. It does not constitute investment advice.*
