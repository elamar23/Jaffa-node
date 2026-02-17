# Unit 8200 & the Digital Breadcrumbs of Stealth

> Pillar article #2 — detail the methodology behind the Ironclad score. Swap in fresh numbers before publishing.

## From “Gut Feel” to Quantified Velocity
Ironclad Radar doesnt guess. We score movements by chaining together telemetry we can measure:

1. **Career Velocity** – Track how quickly a founder moves from Unit 8200 discharge to their next formation. A sudden compression (e.g., 9 months vs. the historical 22) is a stealth tell.
2. **GitHub Commit Surges** – We fingerprint repos tied to alumni pods. When private repos flicker public or mirrored forks spike 5×, we flag it.
3. **Sub-Sector Clustering** – Our watchlist YAML encodes 70+ sub-themes (agentic browsers, zero-trust OT, post-quantum). When multiple alumni land in the same cluster within 30 days, the score jumps.
4. **Procurement + Domain Exhaust** – WHOIS and Israeli registrar filings give away the LLC shells long before PR hits.

## How the Ironclad Score Works
- **Raw inputs**: Title, summary, canonical URL, domain reputation, historical exit data.
- **Model heuristics**: Weighted scoring (0–1000) for novelty, pedigree density, capital efficiency, and rumor corroboration.
- **Output**: Three deliverables per run — enriched events, tagged events, public-safe highlights.

All of this sits in `common.py` utilities and the orchestrator (`instaradar.py`). The collector doesnt just scrape RSS; it normalizes everything into the same JSON structure so enrichment + digesting stay deterministic.

## Why This Matters to LPs and Strategics
When we say “Score 780,” it means:
- The signal triggered at least **three** independent sensors (news, social, filings).
- The alumni density is >1.4 founders per cohort (rare).
- Theres adjacent M&A appetite (tracked via Palo Alto / CyberArk / Google Cloud announcements within ±7 days).

Traditional analysts show you a slide after the deal is priced. Ironclad shows you the breadcrumbs _while_ the founders are still naming the repo.

> _CTA placeholder: “Want the methodology brief + raw schema? Request access to the private docs.”_
