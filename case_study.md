# Meesho Operations Case Study (Expanded)

## Executive Summary
This consulting-style case study analyzes Meesho's operational challenges—primarily logistics inefficiencies and seller onboarding drop-offs—and proposes high-impact solutions (micro-fulfillment centers, digital KYC, COD & returns optimization) with estimated business impact.

## Data & Methodology
- Synthetic logistics dataset (`data/synthetic_logistics.csv`) simulates monthly order volumes, average delivery days, and return rates across regions for 12 months.
- Visualizations (in `visuals/`) showcase delivery times, return rates, monthly order trends, and seller funnel metrics.
- Financial and operational impact estimated using conservative assumptions based on simulated improvements.

## Key Findings
- Average delivery days vary by region; southern and eastern regions show longer delivery times in the simulation.
- Return rates cluster between 8% and 22% across regions—higher than ideal benchmarks.
- Seller onboarding funnel shows significant drop-offs after registration; only ~25% become active sellers in the simulated funnel.

## Recommendations
1. **Regional Micro-Fulfillment Centers (MFCs)** – Deploy MFCs in top Tier-2 regions to reduce last-mile distance and average delivery days by ~15%.
2. **Digital Seller Onboarding & KYC Automation** – Implement guided onboarding and document OCR to reduce drop-offs and improve onboarding success by ~20%.
3. **COD & Returns Optimization** – Encourage prepaid orders via discounts, implement quality checks before dispatch, and partner with local reverse logistics providers to reduce return costs by 10–12%.
4. **Pilot & Scale** – Run 3-month pilots in 3 regions, measure KPIs (delivery days, return rates, seller activation), then scale rollout based on pilot results.

## Financial Impact (Estimates)
- Logistics cost savings: **8–10%** (from reduced delivery times and improved routing).
- Seller onboarding increase: **~20%** (improved funnel conversion).
- Customer retention uplift: **~7–10%** leading to higher LTV.

## Implementation Roadmap
- Month 0–3: Pilot MFCs in 3 regions; implement KYC automation for new sellers.
- Month 4–9: Analyze pilot data, optimize routing algorithms, partner with local reverse logistics.
- Month 10–18: Scale MFCs to additional regions and fully automate seller onboarding.

## Files & How to Use
- `data/synthetic_logistics.csv` – use to reproduce plots or load into Tableau.
- `visuals/` – PNGs of dashboard charts and SWOT image.
- `presentation.pptx` – slide deck for interviews and stakeholder presentations.

---


## Key KPIs Tracked
- **Average Delivery SLA** (days to deliver an order across regions).
- **Seller Conversion Rate** (registered → active sellers).
- **Return Rate %** (percentage of orders returned by customers).
- **Customer Retention %** (repeat purchases over months).
- **Logistics Cost per Order** (simulated cost impact by region).

## Future Recommendations
- **AI-driven Demand Forecasting**: Use ML to predict order surges and optimize inventory placement in MFCs.
- **Dynamic Pricing & Incentives**: Offer region-specific COD/prepaid incentives based on behavior patterns.
- **Advanced Seller Analytics**: Provide dashboards to sellers for performance tracking and suggestions.
