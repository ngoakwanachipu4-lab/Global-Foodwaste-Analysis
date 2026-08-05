# Global-Foodwaste-Analysis
Analysis of the globa foodwaste from household, retail and food services over 214 countries.Most food-waste dashboards stop at "here's the tonnage." This one is built to answer the questions an ESG or sustainability lead actually gets asked:

- Where does the waste concentrate — geographically and by source?
- Is this a supply-chain problem or a consumer-behaviour problem?
- **How much should we trust these numbers before they go into a report?**

That last question drives the design. The dataset's confidence ratings are treated as a first-class metric, not a footnote — because in ESG reporting, an unreliable number cited confidently is a bigger risk than a wide range disclosed honestly.

## Key findings

| Metric | Value |
|---|---|
| Global food waste | **930.9M tonnes/year** |
| Per-capita waste | **121 kg/year** |
| Household share of waste | **66.5%** (largest source in 212/214 countries) |
| Countries covered | **214** |
| Estimates rated Low/Very Low confidence | **91%** (only 10 countries are High Confidence) |

**Reading for leadership:**
- **Intervention point** — Household waste (569M t) is ~2.4× retail and food service combined. Upstream/supply-chain loss-reduction programmes alone won't move the needle without consumer behaviour change.
- **Concentration risk** — China, India, and Nigeria together account for roughly 38% of global tonnage. Any global target's credibility rests on measurement quality in these three markets.
- **Data governance** — With 91% of country estimates in the Low/Very Low confidence bands, this dataset is fit for materiality screening and target-setting direction — not for citing country rankings in assurance-grade disclosures without corroboration.

## What's inside

- **KPI strip** — global total, per-capita average, Countries in Scope, data-confidence flag
- **Regional breakdown** — total tonnage by UN region
- **Source split** — household vs. retail vs. food service, as a share-of-waste stream
- **Top 15 contributors** — absolute tonnage, colour-coded by per-capita intensity
- **ESG insight panel** — three framed takeaways for a leadership or board-level readout

## Tools

- Databricks SQL, to clean, prepare and explore the data
- PowerBI to generate the dashboard and ER Diagram
- Miro, to generate a workflow

## Data source

Country-level food waste estimates (household, retail, food service — kg/capita/year and tonnes/year), population, and confidence ratings, structured in the style of the **UNEP Food Waste Index**.


*Built by Ngoakwana Sonia Chipu — Environmental & Social Manager  — applying data analytics to ESG, SHE governance, and environmental monitoring

