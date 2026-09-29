# Awesome-Carbon-Capture-Monitoring

## Top Carbon Capture Monitoring Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Carbon Accounting, Emissions Monitoring & MRV for CCS*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Carbon Capture Monitoring**. These tools measure, track, and verify greenhouse gas emissions and removals, supporting carbon accounting for corporate sustainability, carbon capture and storage (CCS) projects, and land-sector emissions monitoring.



**Examples** include CarbonChain, Emitwise, Persefoni, Watershed, Sweep, Normative, SINAI Technologies, Greenly, Plan A, and IBM Envizi (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom emission factor management, and transparent carbon calculations — ideal for organizations, researchers, and developers building vendor-independent carbon monitoring solutions. The open-source ecosystem offers a range of options from desktop-first GHG inventory tools to specialized CCS risk assessment models and land-sector MRV platforms.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[CarbonChain](https://www.carbonchain.com/)**  

  Carbon accounting platform specialized in carbon-intensive supply chains including metals, energy, and commodities. Provides CBAM compliance, Product Carbon Footprints (PCF), Corporate Carbon Footprints (CCF), and portfolio emissions tracking for corporates, banks, and traders. SGS-validated methodology aligned with GHG Protocol .



- **[Emitwise](https://www.emitwise.com/)**  

  Supply chain carbon accounting platform for measuring and reporting Scope 3 emissions with automated data extraction.



- **[Persefoni](https://persefoni.com/)**  

  Climate management and accounting platform (CMAP) for enterprise carbon accounting and regulatory reporting.



- **[Watershed](https://watershed.com/)**  

  Enterprise climate platform for carbon accounting, disclosure, and decarbonization strategy with audit-ready data.



- **[Sweep](https://www.sweep.net/)**  

  Carbon management platform helping organizations measure, track, and reduce emissions across scopes.



- **[Normative](https://normative.io/)**  

  Carbon accounting engine for calculating corporate emissions with science-based methodology.



- **[SINAI Technologies](https://www.sinaitechnologies.com/)**  

  Carbon accounting platform for decarbonization strategy and financial planning.



- **[Greenly](https://greenly.earth/)**  

  Carbon accounting platform designed for SMEs and mid-market companies with automated data collection.



- **[Plan A](https://plana.earth/)**  

  Carbon accounting and ESG management software with automated reporting.



- **[IBM Envizi](https://www.ibm.com/products/envizi)**  

  ESG reporting and carbon accounting platform for enterprise sustainability management.



## Open-Source GitHub Projects



- **[NRAP-Open-IAM](https://gitlab.com/NRAP/OpenIAM)**  

  Open-source software from the U.S. Department of Energy enabling quantification of containment effectiveness and leakage risk at geological carbon storage (GCS) sites. Comprises reduced-order and analytical models of GCS system components, potential leakage pathways, and receptors of concern including groundwater and atmospheric impacts. Supports stochastic simulation, time stepping, uncertainty quantification, and scenario/risk-performance evaluation. Used for Area of Review evaluation, monitoring requirements, and post-injection site care planning. Windows, Mac, and Linux supported .



- **[FLINT (Full Lands Integration Tool)](https://github.com/moja-global/FLINT)**  

  Moja Global's flagship open-source software for measuring, reporting, and verifying (MRV) greenhouse gas emissions and removals from forestry, agriculture, and other land uses (AFOLU). Modular, highly flexible architecture that integrates spatial and aspatial data without losing information. Manages huge volumes of remote sensing data. Implementations include GCBM (Canada, Mexico), INCAS (Indonesia), and SLEEK (Kenya). Operates under the Linux Foundation umbrella .



- **[CarbonInk](https://github.com/lxzxl/carbonink)**  

  Free, open-source, local-first GHG carbon accounting for desktop (macOS + Windows). Import utility bills, fuel receipts, and travel documents; AI extracts activity data; produces one-click ISO 14064-1 inventory report entirely offline. No account, no cloud, no subscription. Features Scope 1/2/3 inventory, emission factor pinning with audit-grade snapshots, supplier questionnaires, and built-in MCP server for AI agent integration. MIT licensed .



- **[GEOS](https://github.com/GEOS-DEV/GEOS)**  

  Multiphysics, exascale-ready, open-source simulator for carbon capture and storage. 77 contributors, 4,820 commits, C++ based. Features I/O stabilization, in-situ visualization, on-prem and cloud portability, scale study with large models (1G cells), and uncertainty quantification workflows. Includes near-well geochemistry, induced seismicity, thermal modeling, hydrogen storage capabilities, and geophysical solvers for surveillance and monitoring. Developed with TotalEnergies .



- **[SimCCS2.0](https://github.com/SimCCS/SimCCS)**  

  Open-source software for designing CO₂ capture, transport, and storage infrastructure that optimally links CO₂ sources (power plants) with CO₂ sinks (saline aquifers, depleted oil fields). The only software that optimizes across the entire CCS value chain. Identifies real-world pipeline routes, maximizes carbon tax credits, and supports scenario modeling for cap-and-trade and dynamic network evolution. Won two R&D 100 Awards in 2019 .



- **[GreenOps](https://github.com/cherryaugusta/greenops-carbon-accounting-platform)**  

  Full-stack ESG carbon accounting platform with Django REST Framework backend and React frontend. Tracks employee travel and energy usage, calculates CO₂e using emission factors, and provides manager approval workflows. Features full audit trail via django-simple-history, JWT authentication, Swagger/OpenAPI documentation, dashboard with charts and KPIs, multi-step validated forms, and drag-and-drop report builder. Docker Compose deployment .



- **[Re-Emission](https://github.com/ReEmission/Re-Emission)**  

  Free, open-source Python library (GPL-3.0) for estimating, visualizing, and reporting reservoir GHG emissions. Implements the state-of-the-art G-res model validated against G-res Tool v3.31. Supports CO₂ and CH₄ emissions through multiple pathways with gross and net emissions over 100-year horizons. Integrates with GeoCARET for automated regional-to-national scale inventories. Supports batch processing and customization .



- **[OpenGHG Carbon Calculator](https://github.com/mindsongreen/OpenGHG)**  

  Open-source, transparent carbon footprint calculator designed for robust, auditable, methodology-driven inventories. Key principles: separation of data domains, federated database architecture for customer-hosted data, explicit unit algebra, no black-box calculations, full traceability. Backend: PHP with PostgreSQL. Supports user-defined mapping and scopes with explicit formulas. Releases twice per year .



- **[HyperGas](https://github.com/SRON/HyperGas)**  

  Open-source system from SRON for converting raw hyperspectral satellite observations into greenhouse-gas plume concentrations and emission estimates. Provides end-to-end workflow from radiance data to plume detection and emission-rate estimation. Supports EMIT, EnMAP, and PRISMA instruments; extensible to future missions. Interactive interface for visualizing GHG plumes and identifying emission sources. Validated using controlled releases .



- **[Open-Source Proxy Tool for CO₂ Injection & Storage](https://cordis.europa.eu/project/id/101151733)**  

  EU-funded research project (MSCA, NTNU) developing an open-access smart tool to predict performance of CO₂ injection and storage in Norwegian Continental Shelf mature fields. Considers geochemical and geomechanical parameters for leakage risk quantification. Uses machine learning (PINN, ANN, SVR, XGBoost) for proxy modeling. Integration planned as a module into MRST open-access software .



### Additional Strong Open-Source Options



- **AURORA AI Svr CO₂ Analytics** — Proof-of-concept CCS facility monitoring service using simulated IoT data. Features live performance metrics, actionable insights via ridge regression, and proactive anomaly alerts. Blockchain integration for verifiable analytics storage. gRPC-based service architecture .

- **greenfeedr** — R package for processing and reporting GreenFeed emissions data from livestock. Functions for downloading, processing, and generating daily/final reports of methane and CO₂ emissions. Applicable to all livestock species and housing systems .



**Frameworks for building custom carbon monitoring solutions**: For CCS leakage risk assessment, **NRAP-Open-IAM** provides the most comprehensive U.S. DOE-validated modeling framework . For land-sector MRV, **FLINT** offers production-grade modular architecture with country implementations . For CCS infrastructure optimization, **SimCCS2.0** delivers end-to-end capture-transport-storage design . For reservoir emissions, **Re-Emission** provides G-res validated calculations . For satellite-based emissions monitoring, **HyperGas** enables hyperspectral plume detection and quantification . For corporate GHG inventory, **CarbonInk** (desktop) and **OpenGHG** (web) offer transparent, auditable calculation engines . Note that full enterprise carbon accounting with automated data ingestion and regulatory disclosure workflows remains primarily commercial territory; open-source stacks provide specialized CCS models, MRV frameworks, and calculation engines that require integration for complete monitoring systems.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Carbon monitoring tools must comply with applicable standards (GHG Protocol, ISO 14064, EPA Subpart RR for CCS, EU CBAM) and regional regulatory requirements.

- Self-hosted open-source solutions require proper infrastructure, emission factor database maintenance, and ongoing methodology updates. CCS-specific tools require geological and reservoir engineering expertise for correct application.

- The open-source ecosystem provides strong specialized tools for CCS risk assessment, land-sector MRV, and corporate carbon inventory, but full enterprise carbon accounting platforms with automated data ingestion and regulatory reporting remain primarily commercial offerings.



---



**Made for sustainability managers, CCS engineers, ESG analysts, and carbon monitoring technologists.**  

Let's make carbon capture monitoring more open, transparent, and verifiable.
