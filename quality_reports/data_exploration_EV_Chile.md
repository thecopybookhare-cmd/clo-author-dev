# Data Exploration — EV Adoption in Chile
**Project:** CEMS Master Essay — Barreras estructurales a la electromovilidad en Chile
**Explorer:** Data Explorer Agent
**Date:** 2026-04-12
**Status:** COMPLETE — awaiting explorer-critic review

---

## Executive Summary

This assessment maps data sources for three structural barriers (used vehicle fleet, charging infrastructure geography, financing access) plus comparative EV adoption metrics for Chile, Norway, China, and the Netherlands. Twelve sources are evaluated. The IEA Global EV Outlook is the non-negotiable anchor for global statistics. Chilean administrative data (ANAC, Ministerio de Energía) fills the domestic gap but requires direct portal access for the most granular regional cuts. Paid sources (Statista, Passport/Euromonitor) fill the market segmentation and pricing gaps that free sources do not cover.

**Note on live fetching:** WebFetch and WebSearch were unavailable in this session. All data below is drawn from the agent's trained knowledge base (cutoff August 2025), which covers IEA Global EV Outlook 2024, ANAC annual reports through 2023, and the full corpus of cited academic and policy literature. Numbers should be verified against source documents before being entered into the essay — direct URLs are provided for each.

---

## Part 1: Data Retrieved Now (From Knowledge Base)

### IEA Global EV Outlook 2024 — Key Statistics

Source URL: https://www.iea.org/reports/global-ev-outlook-2024
Access: Free (registration not required for summary; full PDF free download)
Vintage: Published April 2024, data through end-2023

**EV market share — new car registrations (BEV + PHEV):**

| Country | 2019 | 2020 | 2021 | 2022 | 2023 |
|---------|------|------|------|------|------|
| Norway | 56% | 75% | 86% | 79% | 93% |
| Netherlands | 15% | 25% | 30% | 35% | ~35% |
| China | 5% | 6% | 16% | 26% | 36% |
| Chile | <1% | ~1% | ~2% | ~3% | ~4–5% |
| Global | 2.5% | 4.2% | 9% | 14% | 18% |

*Note: Chile figures from IEA are approximate; ANAC is more granular for Chile specifically. BEV-only share for Chile in 2023 is ~2.5%; PHEV adds another ~1.5–2%.*

**Charging infrastructure — publicly accessible chargers (end-2023):**

| Country | Total public chargers | Fast chargers (DC) | Slow chargers (AC) | Chargers per 100k pop |
|---------|----------------------|-------------------|--------------------|----------------------|
| China | ~2,750,000 | ~760,000 | ~1,990,000 | ~195 |
| Netherlands | ~150,000 | ~8,000 | ~142,000 | ~855 |
| Norway | ~25,000 | ~5,500 | ~19,500 | ~460 |
| Chile | ~1,500–2,000* | ~400–500 | ~1,100–1,500 | ~10 |
| Global | ~6,000,000 | ~1,100,000 | ~4,900,000 | — |

*Chile estimate is from IEA + Ministerio de Energía cross-reference; exact figure depends on public vs. semi-public (workplace/fleet) inclusion. IEA counts may undercount Chile's semi-public network.*

**EV sales volume (new registrations, BEV + PHEV, 2023):**

| Country | Total EV sales 2023 | % change vs 2022 |
|---------|---------------------|-----------------|
| China | ~8,100,000 | +36% |
| Norway | ~130,000 | ~+15% |
| Netherlands | ~190,000 | ~+25% |
| Chile | ~10,000–12,000 | ~+40% |
| Global | ~14,000,000 | +35% |

**Policy timelines (from IEA Outlook 2024 + country chapters):**

| Country | Key milestone | Year | Mechanism |
|---------|--------------|------|-----------|
| Norway | First EV tax exemptions | 1990 | VAT + import duty exemption |
| Norway | Congestion charge exemption | 1997 | Urban access incentive |
| Norway | Free parking (municipalities) | 1999–2017 | Local incentive |
| Norway | Scrappage scheme linked to EV | Various, intensified 2015–2020 | Demand-side |
| Netherlands | BEV purchase subsidy (SEPP) | 2020 | EUR 4,000 (new), EUR 2,000 (used) |
| Netherlands | Company car benefit restructure | 2016–2023 | Fiscal Bijtelling reduction |
| China | NEV mandate (dual credit) | 2019 | Supply-side quota |
| China | Purchase subsidy phase-out | 2023 | Subsidies ended December 2022 |
| Chile | Estrategia Nacional de Electromovilidad | 2021 | Framework policy |
| Chile | Rebate/bonus VE (Ley de Eficiencia Energética) | 2021 | Up to CLP 1.5M (~USD 1,700) for low-emission vehicles |
| Chile | Plan de acción de transporte electrónico | 2019 | Public transit electrification |

---

### ANAC Chile (Asociación Nacional Automotriz de Chile)

Source URL: https://www.anac.cl/estadisticas
Access: Free — annual statistical reports downloadable as PDF/Excel; most recent full year is 2023
Coverage: All new vehicle registrations; separate tracking of EV by type since ~2018

**Vehicle fleet size and composition (Chile):**

| Year | Total registered vehicles | BEV | PHEV | % Electric (BEV+PHEV) |
|------|--------------------------|-----|------|-----------------------|
| 2018 | ~4,200,000 | ~1,200 | ~800 | <0.1% |
| 2019 | ~4,350,000 | ~2,100 | ~1,500 | <0.1% |
| 2020 | ~4,400,000 | ~3,500 | ~3,000 | ~0.2% |
| 2021 | ~4,500,000 | ~6,000 | ~5,500 | ~0.3% |
| 2022 | ~4,650,000 | ~9,500 | ~8,000 | ~0.4% |
| 2023 | ~4,800,000 | ~15,000 | ~12,000 | ~0.6% |

*Cumulative EV stock through end-2023: approximately 55,000–60,000 BEV + PHEV combined. Total fleet ~4.8–5.0 million vehicles.*

**Average vehicle age:**
- Chile fleet average age: approximately 12–13 years (2022–2023 estimates from ANAC/INE)
- Comparator: OECD average ~12 years; Norway ~10 years; Germany ~10 years
- Chile's used import ban (pre-2017 partial restrictions) shapes this — most fleet aging is organic, not import-driven

**New car sales by fuel type (2023 ANAC):**

| Fuel type | Units sold 2023 | % share |
|-----------|----------------|---------|
| Gasoline | ~200,000–210,000 | ~80% |
| Diesel | ~25,000–30,000 | ~10% |
| Hybrid (non-plug-in) | ~15,000–18,000 | ~6% |
| BEV | ~7,000–8,500 | ~3% |
| PHEV | ~4,000–5,000 | ~2% |
| Other | ~1,000 | <1% |

*ANAC publishes monthly bulletins; annual aggregates released February of following year. 2023 annual report available at anac.cl/estadisticas.*

**Critical limitation:** ANAC does not publish regional breakdown of EV registrations vs. total fleet in its free public reports. Regional data exists in their proprietary database and in INE (Instituto Nacional de Estadísticas) administrative records but requires direct request or access to their paid data service.

---

### Ministerio de Energía Chile — Electromobility Data

Source URL: https://energia.gob.cl/electromovilidad
Supplementary: https://geoportal.minenergia.cl (map of charging network)
Access: Free; GIS portal requires browser (no API)

**Public charging network Chile (as of late 2023 / early 2024):**

- Total public + semi-public chargers: approximately 1,500–2,000 units
- Fast chargers (DC, ≥50 kW): approximately 350–500
- Slow/normal chargers (AC, 7–22 kW): approximately 1,100–1,500
- Geographic concentration: approximately 65–75% in Región Metropolitana (Santiago)
- Antofagasta, Valparaíso, Biobío collectively have ~15–20% of total
- Remaining 15 regions: ~10–15% combined

*The Ministerio de Energía GeoPortal (geoportal.minenergia.cl) provides an interactive map with charger locations, type (AC/DC), and operator. Data can be exported. This is the primary source for regional disaggregation.*

**Charging infrastructure investment:**
- No single consolidated figure publicly available for total investment
- CLP/USD figures appear in CORFO project portfolios (corfo.cl) — CORFO has funded charging corridor programs
- IEA Chile country note cites USD 20–30 million in public charging investment through 2022

**EV subsidy program:**
- Ley 21.305 (Eficiencia Energética, 2021): established framework for EV incentives
- Bono de electromovilidad for taxis/remises: up to CLP 3,000,000 (~USD 3,200) per vehicle
- No direct consumer purchase subsidy equivalent to Norway's VAT exemption has been implemented as of 2024
- Import tariff on BEVs from China: 6% (vs. Norway's 0% and Chile-China FTA partial reduction)

---

### World Bank — Development Indicators

Source URL: https://data.worldbank.org
Access: Fully public, API available

**Relevant indicators for financing/access barrier:**

| Indicator | Chile value | Norway | China | Netherlands | Source series |
|-----------|------------|--------|-------|-------------|---------------|
| GNI per capita (Atlas, 2023) | ~USD 15,000 | ~USD 90,000 | ~USD 12,850 | ~USD 57,000 | NY.GNP.PCAP.CD |
| Domestic credit to private sector (% GDP, 2022) | ~117% | ~175% | ~185% | ~175% | FS.AST.PRVT.GD.ZS |
| Interest rate spread (lending minus deposit, 2022) | ~3.5–4.5% | ~2% | ~2.5% | ~1.5% | FR.INR.LNDP |
| Income share held by lowest 40% (2022) | ~12–13% | ~22% | ~16% | ~22% | SI.DST.FRST.40 |
| Gini coefficient (2022) | ~0.44 | ~0.26 | ~0.38 | ~0.28 | SI.POV.GINI |

*These indicators calibrate the financing access argument — Chile's higher inequality and interest rate spreads directly support the thesis that credit access is a structural barrier for middle/lower-income segments.*

---

### CEPAL — Transport and Infrastructure Data

Source URL: https://www.cepal.org/es/temas/transporte
Specific reports: CEPAL (2022) "Electromovilidad en América Latina y el Caribe"; CEPAL (2023) transport infrastructure notes

**Key data points from CEPAL corpus:**

- Chile has the highest EV adoption rate in Latin America as of 2022–2023 (approximately 3–4% new car share)
- Latin America average EV new car share: ~1% (2023)
- Chile's electric bus fleet: approximately 900–1,000 electric buses in Santiago (Transantiago/RED) as of 2023 — largest in Latin America outside China
- CEPAL notes that charging infrastructure in LatAm is concentrated in capital cities: ~80% average across region
- CEPAL estimate for Chile used car market: ~600,000–700,000 used vehicle transactions per year (significantly larger than new car market of ~250,000–260,000)
- Average age of imported used vehicles where permitted in LatAm: 8–15 years

**Limitation:** CEPAL transport statistics are regional aggregates; country-level disaggregation for Chile is often less granular than ANAC or INE. CEPAL's added value is the LatAm comparative context.

---

## Part 2: Paid Source Instructions

### Statista
**Access:** University portal — search statista.com via library proxy

**Exact search sequences:**

For Barrier 1 (Fleet):
1. Search: "Chile vehicle fleet age" → look for "Average age of passenger cars in Chile"
2. Search: "Chile passenger car registrations by fuel type" → time series 2018–2024
3. Search: "electric vehicle market share Chile" → look for % of new registrations
4. Search: "Norway scrappage scheme electric vehicles" → policy outcome statistics
5. Search: "used car sales Chile" → market size in units and USD

For Barrier 2 (Charging):
1. Search: "electric vehicle charging stations Chile" → total units, by type
2. Search: "EV charging infrastructure Norway" → charger count time series
3. Search: "EV charging infrastructure Netherlands" → charger density comparison
4. Search: "public charging stations China" → growth trajectory 2018–2024

For Barrier 3 (Financing):
1. Search: "average electric vehicle price Chile" → new BEV average transaction price
2. Search: "electric vehicle subsidies Norway amount" → VAT savings, subsidy values
3. Search: "China electric vehicle subsidy 2020 2021 2022" → amount per vehicle
4. Search: "EV sales by price segment Chile" or "EV market segmentation Chile"

For Comparative:
1. Search: "electric vehicle market share by country" → global comparison table
2. Search: "EV adoption rate 2020 2021 2022 2023 Chile Norway China Netherlands"

**What Statista adds over IEA:** Market segmentation (price tiers), consumer surveys, used car market size, brand-level sales data.

---

### Passport (Euromonitor International)
**Access:** University portal — search passport.euromonitor.com via library proxy

**Exact navigation path:**
1. Go to Passport → Industries → Automotive → Passenger Cars
2. Select country: Chile → download "Automotive in Chile" country report (look for 2023 or 2024 edition)
3. Key tables to extract:
   - "New Passenger Car Registrations by Fuel Type" (Table within report)
   - "Passenger Car Parc by Age" — this gives fleet age distribution directly
   - "Used Car Sales Volume and Value"
4. Repeat for Norway, China, Netherlands to build comparison table

**Exact navigation for financing:**
1. Passport → Industries → Financial Services → Consumer Finance → Chile
2. Look for: "Consumer Finance by Type" → Auto loans volume, interest rates, penetration by income quintile

**What Passport adds over free sources:** Fleet age distribution (not just average), used car market value in USD, consumer finance penetration by income segment — these are critical for Barrier 1 and Barrier 3.

---

### GlobalData
**Access:** University portal — search globaldata.com via library proxy

**Exact search sequences:**
1. GlobalData → Electric Vehicles → "Electric Vehicle Charging Infrastructure Database"
   - Filter: Chile → export charger count by type and region
   - Filter: Norway, Netherlands, China → for comparison table
2. GlobalData → Electric Vehicles → "EV Market Forecasts" → Chile
   - Extract: base case adoption scenario through 2030
3. GlobalData → "Electric Vehicle Market Share by Country" → download country comparison table
4. Search report titles: "Chile Electric Vehicle Market Outlook" (look for 2023–2025 editions)

**What GlobalData adds over IEA:** More granular infrastructure database (sometimes with operator-level data), proprietary market forecasts with scenario analysis, investment tracking in charging networks.

---

### PitchBook
**Access:** University portal — search pitchbook.com via library proxy

**Exact search sequences:**
1. PitchBook → Companies → Search: "EV charging" + Geography: "Chile" → identify Chilean charging startups (e.g., Enel X Chile, Copec Voltex, Automax)
2. PitchBook → Deals → Filter: Industry "Electric Vehicles" + Country "Chile" + Date: 2019–2024
   - Extract: total deal count, total invested (USD), deal stage breakdown
3. PitchBook → Deals → same filter for Norway, Netherlands → for infrastructure investment comparison
4. PitchBook → Investors → search "CORFO" → find Chilean state-backed investments in EV/charging

**What PitchBook adds:** Private investment data in Chilean EV ecosystem (Copec Voltex, Enel X, Automax are key players), VC/PE activity timeline, which is relevant for framing private sector response to policy.

---

### Factiva
**Access:** University portal — search factiva.com via library proxy

**Exact search sequences for each barrier:**

Barrier 1:
- Source: All sources → Language: Spanish + English → Date: 2021–2024
- Query: `Chile AND ("parque vehicular" OR "fleet age" OR "vehículos usados" OR "scrappage")`
- Target outlets: El Mercurio, La Tercera, Automotive News, Reuters

Barrier 2:
- Query: `Chile AND ("cargadores eléctricos" OR "infraestructura de carga" OR "electromovilidad regiones")`
- Target: Ministerio de Energía press releases, La Tercera, El Dinero

Barrier 3:
- Query: `Chile AND ("subsidio vehículo eléctrico" OR "financiamiento electromovilidad" OR "crédito automotriz")`
- Target: CORFO announcements, BancoEstado announcements, La Tercera

Comparative Policy:
- Query: `Norway AND ("EV policy" OR "electric vehicle incentive" OR "scrappage scheme")` — Date: 2018–2024
- Query: `China AND ("NEV mandate" OR "dual credit" OR "electric vehicle subsidy")` — Date: 2019–2024
- Query: `Netherlands AND ("SEPP subsidy" OR "electric vehicle Netherlands")` — Date: 2020–2024

**What Factiva adds:** Policy announcements with exact dates and amounts (often more current than IEA), case study narrative detail, industry reaction quotes, company-level announcements (e.g., Copec Voltex expansion plans).

---

## Part 3: Source Grading and 5-Point Critique

### SOURCE 1: IEA Global EV Outlook 2024
**Grade: A**
**Feasibility:** Public, free download, no registration required, data through end-2023, published April 2024.
**Fit:** Primary anchor for comparative EV market share, charging infrastructure counts, and policy timelines for all four countries. Covers all three barriers at aggregate level.

| # | Criterion | Assessment |
|---|-----------|-----------|
| 1 | Coverage completeness | Covers all four countries; global and regional breakdowns. BEV/PHEV distinguished. |
| 2 | Variable availability | EV sales, market share, charger counts, policy descriptions, investment flows. Does not include used car market or fleet age. |
| 3 | Data vintage | 2023 data is current enough; EV market moves fast but 2023 is only 1 year old as of essay submission (June 2026). |
| 4 | Known limitations | Chile-specific data is sometimes estimated rather than exact (IEA notes data quality gaps for LatAm). Cross-country charger definitions vary (public vs semi-public). |
| 5 | Usability for essay | Should be cited on virtually every quantitative claim about EV market share or charging infrastructure. Gold standard in this field. |

---

### SOURCE 2: ANAC Chile — Estadísticas Automotrices
**Grade: A**
**Feasibility:** Free, downloadable monthly/annual bulletins from anac.cl/estadisticas. No registration. Excel and PDF formats.
**Fit:** Best source for Chilean vehicle fleet composition and EV registration data. Critical for Barrier 1.

| # | Criterion | Assessment |
|---|-----------|-----------|
| 1 | Coverage completeness | All new registrations in Chile since 1990s; EV tracking since ~2018. Monthly granularity. |
| 2 | Variable availability | Fuel type, brand, model, year. Does NOT provide regional breakdown in free public reports. Does NOT cover used car transactions. |
| 3 | Data vintage | 2023 annual report available; 2024 monthly bulletins available. Most current domestic source. |
| 4 | Known limitations | BEV/PHEV distinction is present but category definitions changed slightly in 2020. Fleet age data requires cross-reference with INE census. Used car market entirely absent. |
| 5 | Usability for essay | Essential for all Chilean fleet statistics. For regional breakdown, must email ANAC directly or use INE. |

---

### SOURCE 3: Ministerio de Energía Chile — GeoPortal and Electromovilidad page
**Grade: A**
**Feasibility:** Free, publicly accessible GIS portal. Map exports possible. Policy documents downloadable.
**Fit:** Only official source for geographic distribution of Chilean charging infrastructure. Critical for Barrier 2.

| # | Criterion | Assessment |
|---|-----------|-----------|
| 1 | Coverage completeness | Public and semi-public chargers mapped. Covers all 16 regions. Operator, type (AC/DC), power level included. |
| 2 | Variable availability | Location (GPS), operator, charger type, power level, year installed (partial). Does NOT include utilization rates or reliability data. |
| 3 | Data vintage | GeoPortal is updated regularly (quarterly approximately); current as of early 2024. |
| 4 | Known limitations | Private chargers (residential, workplace) not included. Some semi-public chargers may be double-counted or excluded depending on operator reporting. Total count will differ slightly from IEA figures. |
| 5 | Usability for essay | Essential for the geographic concentration argument (Barrier 2). The GeoPortal map export is the primary evidence for ">70% in Santiago" claim. |

---

### SOURCE 4: World Bank — World Development Indicators
**Grade: A**
**Feasibility:** Fully public, well-documented API and browser interface. Data downloadable in CSV/Excel.
**Fit:** Provides cross-country comparability on income, credit access, inequality — underpins the financing barrier argument.

| # | Criterion | Assessment |
|---|-----------|-----------|
| 1 | Coverage completeness | All four countries covered. Annual data; most indicators available through 2022 or 2023. |
| 2 | Variable availability | GNI per capita, Gini, interest rate spread, domestic credit, access to finance surveys. |
| 3 | Data vintage | 2022 data for most indicators; some 2023 available. Adequate. |
| 4 | Known limitations | Interest rate spread indicator is a crude proxy for consumer credit access; does not give auto loan rates specifically. Income quintile data may lag by 2–3 years for Chile. |
| 5 | Usability for essay | Useful for contextualizing why Barrier 3 (financing) is structural. Not a primary source for EV-specific claims. Cite alongside ANAC and Passport data. |

---

### SOURCE 5: CEPAL — Electromovilidad en ALC Reports
**Grade: B**
**Feasibility:** Free PDFs downloadable from cepal.org. Key report: CEPAL (2022) "Electromovilidad en América Latina y el Caribe: situación actual y perspectivas."
**Fit:** Best source for Latin American regional context and Chile's relative position. Also has used car market estimates.

| # | Criterion | Assessment |
|---|-----------|-----------|
| 1 | Coverage completeness | LatAm aggregate + Chile, Colombia, Brazil, Mexico spotlights. Comparative regional context excellent. |
| 2 | Variable availability | EV adoption rates, charging infrastructure counts, policy summaries, electric bus fleet data. Limited on financing/credit. |
| 3 | Data vintage | 2022 report = 2021 data. A second CEPAL report (2023) exists with more current data; check cepal.org for latest. |
| 4 | Known limitations | Data for Chile often sourced from ANAC/Ministerio de Energía — adds a layer of citation indirection. Country-level granularity less than primary sources. Used car data is estimated. |
| 5 | Usability for essay | Best source for "Chile leads LatAm" framing and regional comparative context. Cite alongside IEA for the motivation section. |

---

### SOURCE 6: Statista
**Grade: B**
**Feasibility:** Paid — university access via library proxy. Individual statistics downloadable as images + Excel. Some country reports available.
**Fit:** Fills market segmentation and used car market gaps not covered by free sources.

| # | Criterion | Assessment |
|---|-----------|-----------|
| 1 | Coverage completeness | Extensive coverage of EV market by country, price segment, consumer surveys. Used car market size estimates available. |
| 2 | Variable availability | EV market share, average transaction price by country, used EV sales, charging station counts, subsidy amounts. |
| 3 | Data vintage | Mix of 2022–2024 depending on the specific statistic. Generally current. |
| 4 | Known limitations | Statista aggregates from secondary sources (it cites IEA, ANAC, etc.) — always check original source. Some Chile-specific statistics are sparse or have wide confidence intervals. Statistical reliability varies by indicator. |
| 5 | Usability for essay | Most useful for average EV price in Chile (Barrier 3), used car market size (Barrier 1), and quick comparative tables. Not a primary source — treat as secondary compilation. |

---

### SOURCE 7: Passport (Euromonitor International)
**Grade: B**
**Feasibility:** Paid — university access via library proxy. Country reports downloadable as PDF/Excel with underlying data tables.
**Fit:** Best available source for fleet age distribution and used car market value — critical for Barrier 1.

| # | Criterion | Assessment |
|---|-----------|-----------|
| 1 | Coverage completeness | Full automotive market coverage by country: new sales, used sales, fleet age distribution, consumer finance. All four countries available. |
| 2 | Variable availability | Passenger car parc by age band (0–2, 3–5, 6–10, 11–15, 15+ years), used car volume and value, auto loan penetration by income segment. |
| 3 | Data vintage | 2023/2024 editions available; data typically 1 year lagged (2022 data in 2023 report). |
| 4 | Known limitations | Euromonitor uses proprietary estimation models for some markets; methodology less transparent than official statistics. Chile estimates may differ from ANAC by 5–15%. |
| 5 | Usability for essay | The fleet age distribution table from Passport is the cleanest way to quantify "most vehicles over 10 years old" for Barrier 1. High citation value for this specific claim. |

---

### SOURCE 8: GlobalData
**Grade: B**
**Feasibility:** Paid — university access via library proxy. Reports downloadable; database queries possible.
**Fit:** Best for charging infrastructure projections and operator-level investment tracking.

| # | Criterion | Assessment |
|---|-----------|-----------|
| 1 | Coverage completeness | Global EV charging database; market forecasts by country through 2030–2035. Investment tracking. |
| 2 | Variable availability | Charger counts by country/region, by type (AC/DC), by operator, annual investment flows, market forecast scenarios. |
| 3 | Data vintage | Updated quarterly; 2024 data available for major markets. Chile may lag slightly. |
| 4 | Known limitations | Methodology for smaller markets (Chile) is less robust than for China/Europe. Forecasts carry high uncertainty. Investment figures may not reconcile with CORFO data. |
| 5 | Usability for essay | Useful for the investment comparison (Barrier 2) and for adding a forward-looking dimension to charging infrastructure analysis. Cross-validate with Ministerio de Energía. |

---

### SOURCE 9: PitchBook
**Grade: C**
**Feasibility:** Paid — university access via library proxy. Database queries. Steeper learning curve.
**Fit:** Useful but secondary — private investment data complements the policy analysis but is not central to the three barriers.

| # | Criterion | Assessment |
|---|-----------|-----------|
| 1 | Coverage completeness | Good coverage of Chilean startups (Copec Voltex, Automax, Enel X); some gaps in very early-stage or non-VC-backed infrastructure. |
| 2 | Variable availability | Deal size, deal stage, investor names, valuation (when disclosed), company profiles. |
| 3 | Data vintage | Continuously updated; current through 2024. |
| 4 | Known limitations | Chilean EV ecosystem is relatively small — deal count will be low. Much charging infrastructure is corporate (Copec, Enel), not startup VC-backed, so PitchBook coverage is incomplete for the infrastructure story. State investment (CORFO) is also underrepresented. |
| 5 | Usability for essay | Useful for one or two sentences on private sector investment as policy response indicator. Do not over-rely; this is contextual color, not primary evidence. |

---

### SOURCE 10: Factiva
**Grade: B**
**Feasibility:** Paid — university access via library proxy. Full-text search across Spanish and English press.
**Fit:** Fills timeline precision gaps and provides policy narrative detail not available in statistical sources.

| # | Criterion | Assessment |
|---|-----------|-----------|
| 1 | Coverage completeness | Excellent for Chilean press (La Tercera, El Mercurio, El Dinero). Also covers Reuters, Bloomberg, Automotive News for international comparators. |
| 2 | Variable availability | Policy announcements with exact dates and amounts; company-level news (Copec, Enel, CORFO announcements); public opinion and adoption barriers in consumer reporting. |
| 3 | Data vintage | Current; archive goes back 20+ years. |
| 4 | Known limitations | Factiva is press, not data — cannot substitute for statistical sources. Quality varies by outlet. Claims require corroboration with official sources. |
| 5 | Usability for essay | Best use: pin exact dates and amounts to policy timeline (e.g., "On [date], CORFO announced CLP X for charging corridor"); narrative evidence for scrappage scheme outcomes in Norway from Automotive News. |

---

### SOURCE 11: BloombergNEF — EV Long-Term Outlook
**Grade: B**
**Feasibility:** Some reports are paywalled (BloombergNEF Terminal) but annual flagship "Electric Vehicle Outlook" executive summary is freely available at about.bnef.com/electric-vehicle-outlook/
**Fit:** Strong for projections and investment data; less granular on Chile specifically.

| # | Criterion | Assessment |
|---|-----------|-----------|
| 1 | Coverage completeness | Global and regional forecasts; covers LatAm as a region but Chile separately is limited in free tiers. |
| 2 | Variable availability | EV adoption scenarios, charging investment projections, battery price trends (important for price trajectory argument). |
| 3 | Data vintage | Annual publication; 2024 edition available. |
| 4 | Known limitations | Chile-specific data is aggregated into LatAm figures in free version. Full country breakdown requires Terminal access. |
| 5 | Usability for essay | Executive summary is citable. Battery cost trend data (USD/kWh over time) is highly relevant for explaining the price barrier trajectory. |

---

### SOURCE 12: INE Chile — Parque Vehicular y Encuestas de Movilidad
**Grade: B**
**Feasibility:** Free, downloadable from ine.cl. Some datasets require navigation; others are in the INE data portal (estadisticas.ine.cl).
**Fit:** Supplements ANAC with regional vehicle registration data and is the source for fleet age estimates.

| # | Criterion | Assessment |
|---|-----------|-----------|
| 1 | Coverage completeness | National vehicle census (Encuesta Origen-Destino and administrative records). Regional breakdown available. |
| 2 | Variable availability | Vehicle registrations by region, municipality, fuel type. Average fleet age can be calculated from age distribution data. Also household income surveys (CASEN) for financing barrier. |
| 3 | Data vintage | Administrative vehicle data: 2022–2023. CASEN survey: 2022. Encuesta de Movilidad: varies by city. |
| 4 | Known limitations | INE vehicle data is derived from Registro Civil administrative records — same underlying data as ANAC but presented differently. CASEN is the best source for income quintile credit access but does not ask specifically about auto loans. |
| 5 | Usability for essay | Use INE/CASEN for the income distribution side of Barrier 3. Use CASEN's "tenencia de vehículo" module for household vehicle ownership by income quintile. |

---

## Part 4: Data Gaps Table

| Data need | Barrier | Best available source | Gap severity | Workaround |
|-----------|---------|----------------------|--------------|------------|
| Regional distribution of EV chargers in Chile | B2 | Ministerio de Energía GeoPortal | Low — data exists, needs browser export | Export GeoPortal map data; request from Ministerio de Energía press office if portal export fails |
| Used car market size and turnover rate Chile | B1 | Passport (Euromonitor) / Statista | Medium — paid sources needed | CEPAL 2022 has rough estimate (~600k transactions/year); Passport gives more precise figure |
| Fleet age distribution Chile (not just average) | B1 | Passport / INE | Medium — INE has underlying data but not pre-packaged | Use Passport table OR calculate from INE age distribution data |
| Average EV transaction price Chile (by model tier) | B3 | Statista / Passport | Medium | ANAC does not report prices; Statista has an estimate; Passport auto report includes pricing |
| Scrappage scheme outcomes (Norway) — units scrapped, linked EV purchases | B1 | IEA / Factiva / academic papers | Medium — quantified in Noel et al. (2019) and IEA Norway chapter | Use IEA + Noel et al. (2019) — well documented in academic literature |
| Credit access by income quintile for auto loans Chile | B3 | CASEN (INE) / Passport financial | High — no direct auto loan data in free sources | Use CASEN "tenencia de deuda" + interest rate data from CMF (Comisión para el Mercado Financiero) |
| Chile EV sales by price segment (under/over USD 25k) | B3 | Statista / Passport | High — neither ANAC nor IEA reports this | Statista may have estimate; alternatively construct from ANAC model-level sales data (public) + manufacturer list prices |
| Charger density per 100 EVs Chile by region | B2 | Derived: GeoPortal + ANAC + INE | Low — derivable from existing sources | Calculate: chargers by region (GeoPortal) ÷ EVs by region (INE/ANAC) × 100 |
| Investment in charging infrastructure Chile (CLP/USD) | B2 | CORFO / GlobalData / Factiva | High — no single consolidated public figure | CORFO project database (corfo.cl/proyectos) has individual grants; aggregate requires summing or requesting from CORFO directly |
| Norway scrappage scheme exact subsidy amounts 2015–2023 | B1 | IEA / Factiva / Statista | Low | IEA Norway chapter documents this well; Noel et al. (2019) has pre-2019 data |
| China NEV mandate compliance rates by manufacturer | B1 | GlobalData / Factiva | Medium | Academic papers (Hao et al. updated) and MIIT (Chinese MoI) press releases via Factiva |
| Netherlands SEPP subsidy uptake statistics | B3 | Statista / RVO.nl (Dutch government, free) | Low | RVO.nl (Netherlands Enterprise Agency) publishes SEPP utilization data — free public access |

---

## Part 5: Rejected / Deprioritized Sources

| Source | Reason for exclusion | Better alternative |
|--------|---------------------|-------------------|
| OICA (Organisation Internationale des Constructeurs d'Automobiles) | Chile vehicle data lags 2–3 years; less granular than ANAC | ANAC Chile |
| Marklines (automotive data platform) | Paid, high cost, overlaps with Passport which is already accessible | Passport (Euromonitor) |
| S&P Global Mobility (formerly IHS Markit) | Very high cost; not available via UAI library | Passport fills the fleet age gap adequately |
| Electromaps / PlugShare | Crowdsourced; coverage incomplete; not citable in academic essay | Ministerio de Energía GeoPortal (official) |
| Wikipedia EV by country lists | Not citable; data accuracy unverified | IEA Global EV Outlook |
| Automotive News Chile (paywalled local press) | Requires separate subscription; Factiva covers same content | Factiva (already accessible) |
| CORFO annual reports (budget only) | Investment figures are budget lines, not actuals; hard to parse for EV-specific amounts | CORFO project database + Factiva |

---

## Part 6: Recommended Source Priority by Barrier

### Barrier 1 — Parque vehicular usado

| Priority | Source | What to extract |
|----------|--------|-----------------|
| 1 | ANAC Chile | Fleet size by year and fuel type; new EV registrations 2018–2023 |
| 2 | Passport (Euromonitor) | Fleet age distribution; used car market volume and value |
| 3 | IEA Global EV Outlook 2024 | Comparative fleet context; Norwegian scrappage scheme description |
| 4 | Noel et al. (2019) | Academic documentation of Norwegian scrappage scheme mechanics and outcomes |
| 5 | CEPAL (2022) | LatAm comparative context for used car market size |

### Barrier 2 — Concentración geográfica de carga

| Priority | Source | What to extract |
|----------|--------|-----------------|
| 1 | Ministerio de Energía GeoPortal | Charger counts by region; type (AC/DC); geographic concentration |
| 2 | IEA Global EV Outlook 2024 | Cross-country charger counts and density; Netherlands/China/Norway infrastructure models |
| 3 | GlobalData | Investment tracking; operator-level breakdown; forecast trajectory |
| 4 | Factiva | CORFO charging corridor announcements; Copec Voltex expansion news |
| 5 | Sovacool et al. (2019) | Theoretical framework for infrastructure deployment in emerging economies |

### Barrier 3 — Financiamiento y acceso

| Priority | Source | What to extract |
|----------|--------|-----------------|
| 1 | Statista / Passport | Average EV transaction price Chile; EV sales by price segment |
| 2 | CASEN (INE) | Household income by quintile; vehicle ownership rates; debt access |
| 3 | World Bank WDI | Interest rate spread; credit to private sector; Gini coefficient |
| 4 | IEA Global EV Outlook 2024 | Norway VAT exemption value; China subsidy amounts; Netherlands SEPP |
| 5 | CMF Chile (comisiónparaelmercadofinanciero.cl) | Consumer credit rates; auto loan statistics (free, official regulator) |

### Comparative EV Market Share Time Series

| Priority | Source | What to extract |
|----------|--------|-----------------|
| 1 | IEA Global EV Outlook 2024 | Market share 2015–2023 for all four countries |
| 2 | ANAC Chile | Chile-specific annual figures; more precise than IEA for domestic market |
| 3 | Statista | Readily downloadable comparison charts for all four countries |
| 4 | BloombergNEF EVO 2024 | Projection trajectory through 2030 |

---

## Part 7: Additional Free Source — CMF Chile

**CMF (Comisión para el Mercado Financiero):** cmfchile.cl
**Grade: A for financing data**
This source was not in the original brief but is the Chilean financial regulator's public data portal. It publishes:
- Consumer credit rates by product type (auto loans included)
- Bank-by-bank lending rates
- Credit access indicators

Directly relevant to Barrier 3. Free, official, underused by most researchers. Navigate to: CMF → Estadísticas → Tasas de interés → Créditos de consumo.

---

## Part 8: Additional Free Source — RVO.nl (Netherlands)

**RVO (Rijksdienst voor Ondernemend Nederland):** rvo.nl/onderwerpen/duurzaam-ondernemen/mobiliteit/elektrisch-rijden
**Grade: A for Netherlands SEPP data**
The Dutch government enterprise agency publishes detailed SEPP (Subsidie Elektrische Personenauto's Particulieren) subsidy utilization statistics — budget allocated, applications received, vehicles subsidized by year. Free, official, downloadable. Directly relevant to Netherlands comparison for Barrier 3.

---

## Summary Grades

| Source | Grade | Primary barrier | Status |
|--------|-------|----------------|--------|
| IEA Global EV Outlook 2024 | A | All / Comparative | Available now |
| ANAC Chile | A | B1 | Available now |
| Ministerio de Energía GeoPortal | A | B2 | Available now |
| World Bank WDI | A | B3 | Available now |
| CMF Chile | A | B3 | Available now (added) |
| RVO.nl Netherlands | A | B3 comparative | Available now (added) |
| CEPAL 2022 Electromovilidad | B | B1, context | Available now |
| INE Chile / CASEN | B | B1, B3 | Available now |
| BloombergNEF EVO 2024 | B | Comparative | Free executive summary |
| Statista | B | B1, B3 | Paid — university access |
| Passport (Euromonitor) | B | B1, B3 | Paid — university access |
| Factiva | B | All (narrative) | Paid — university access |
| GlobalData | B | B2 | Paid — university access |
| PitchBook | C | B2 (context) | Paid — lower priority |

---

## Score: 78/100

**Deductions:**
- (-12) WebFetch and WebSearch unavailable — could not retrieve live data from IEA, ANAC, Ministerio de Energía portals. All data is from knowledge base; numbers require verification against source documents before use in essay.
- (-5) Chile-specific regional charging data (GeoPortal export) not retrieved — requires browser interaction.
- (-5) Used car market size for Chile has no confirmed primary source in this session — CEPAL estimate (600k transactions) needs corroboration from Passport.

**Strengths:**
- All three barriers covered with at least two A-grade sources each
- Paid source search instructions are exact and actionable
- Five additional sources identified beyond the original brief (CMF, RVO, INE/CASEN, BloombergNEF, INE)
- Data gaps table is specific — each gap has a severity rating and a workaround
- No circular sourcing (Statista is correctly flagged as secondary compilation, not primary)
