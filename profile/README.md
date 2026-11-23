🟢 **Open to work** · [LinkedIn](https://www.linkedin.com/in/workwithrana) · [Email](mailto:work@withrana.com)

### Senior Full-Stack Engineer | Rust • Go • Python • Node.js • React/Next.js

I build resilient backend systems, AI integrations, and high-performance tooling. My focus is on distributed architecture, zero-downtime database migrations, deterministic auditing, and shipping production-ready AI agents on edge networks like Cloudflare.

> **20+ Certifications** across AWS, Google Cloud, Meta, and Intel  
> **30+ Google Skill Badges** validating applied, hands-on expertise

---

### Stack

- **Languages:** Rust · Go · Python · TypeScript · JavaScript
- **Backend:** Node.js · FastAPI · NATS JetStream · OpenAPI · SCIM/OIDC
- **Frontend:** React · Next.js · Tailwind · D3 · ECharts · MapLibre GL · WebGL2
- **Databases:** PostgreSQL (PostGIS, pgvector, RLS) · SQLite · DuckDB · Cloudflare D1 · KV · Firestore
- **Cloud & Edge:** Cloudflare Workers/R2 · AWS · GCP · Docker
- **Observability:** OpenTelemetry · Tempo
- **AI & ML:** LangGraph · PyTorch · MLX · llama.cpp · LoRA fine-tuning · RAG · LightGBM
- **Testing & QA:** Deterministic replay · fault injection · LLM evaluation · contract testing

---

### Featured Engineering

I've published over **65+ open-source projects**.

- **[zero-downtime-db-migrations](https://github.com/ranajahanzaib/zero-downtime-db-migrations):** Production-grade zero-downtime PostgreSQL schema migrations in Go, with phased rollouts, backfills, and automated verification.
- **[background-job-recovery](https://github.com/ranajahanzaib/background-job-recovery):** Go reference architecture for crash-safe background job recovery using PostgreSQL fencing tokens, a transactional outbox, and NATS JetStream.
- **[usage-based-billing](https://github.com/ranajahanzaib/usage-based-billing):** Go billing engine with exact-decimal math, proration, graduated tiers, and a PostgreSQL schema.
- **[ai-agent-permission-enforcer](https://github.com/ranajahanzaib/ai-agent-permission-enforcer):** Rust-based trusted authorization gateway and Cedar policy engine for securing AI agent tool calls.
- **[WaiChat](https://github.com/ranajahanzaib/waichat):** Fully open-source AI chat platform running entirely on the edge using Cloudflare Workers, D1, and Workers AI.
- **[rico](https://github.com/ranajahanzaib/rico):** High-performance Rust CLI for bulk image conversion and background removal. Runs in CI, processing thousands of assets for production environments.

---

### Professional Experience

- **Independent Full-Stack Engineer** _(Dec 2023 - Present)_
  - Designed and shipped production backend systems including crash-safe background job recovery, usage-based billing engines, and SCIM/OIDC multi-tenant provisioning.
  - Shipped local LLM fine-tuning pipelines on Apple Silicon and built agent authorization architectures.
  - Delivered 60+ full-stack web applications and storefronts across client and self-initiated builds.
- **Lead Frontend Engineer @ Züs (0Chain)** _(Mar 2022 - Sep 2023)_
  - Set technical direction for 30+ engineers across 6 blockchain products.
  - Raised 1,500+ PRs (7x the next highest contributor) and coordinated cross-platform releases (Web, iOS, Android, macOS, Windows).
- **Lead Software Engineer @ LMS Company** _(Jun 2021 - Aug 2021)_
  - Led performance optimization on a legacy e-learning platform, optimizing SQL to cut latency.
- **Full Stack Engineer @ IoT Tracking Solutions** _(Apr 2021 - Jun 2021)_
  - Worked on real-time location tracking systems (Go, PostgreSQL, React) for construction sites handling live GPS and Link Labs hardware telemetry.

---

### Full Project Index

<details>
<summary><b>65+ Systems, Backend, & AI Projects (Open Source)</b></summary>
<br>

**AI Agents & Business Automation**

- **[business-operations-agent](https://github.com/ranajahanzaib/business-operations-agent):** Python, local-first AI business operations reference system with LangGraph, human approvals, and SQLite verification.
- **[ecommerce-support-automation](https://github.com/ranajahanzaib/ecommerce-support-automation):** Python, policy-grounded ecommerce support ticket investigation and human-in-the-loop refund automation.
- **[ai-agent-permission-enforcer](https://github.com/ranajahanzaib/ai-agent-permission-enforcer):** Rust, trusted authorization gateway and Cedar policy engine for AI agent tool calls.
- **[ai-workflow-cost-analyzer](https://github.com/ranajahanzaib/ai-workflow-cost-analyzer):** Python, local economics engine to measure the true cost of verified AI workflow outcomes, retries, and human labor.
- **[multi-tenant-rag](https://github.com/ranajahanzaib/multi-tenant-rag):** Python, production reference for multi-tenant, permission-aware RAG using PostgreSQL row-level security, FastAPI, and React.
- **[workers-aide](https://github.com/ranajahanzaib/workers-aide):** Open-source business AI agents powered by Cloudflare. Deploy to your own free Cloudflare account, configure your business, and automate customer interactions.

**Local LLM Fine-Tuning & Inference**

- **[llm-finetuning-and-serving](https://github.com/ranajahanzaib/llm-finetuning-and-serving):** Python, local workbench for fine-tuning, evaluating, and serving LLMs on Apple Silicon with MLX-LM and FastAPI.
- **[llm-feedback-finetuning-pipeline](https://github.com/ranajahanzaib/llm-feedback-finetuning-pipeline):** Python, local-first pipeline that turns business feedback and corrections into specialized MLX models on Apple Silicon, with traceable datasets, LoRA fine-tuning, and regression gating.
- **[kv-cache-quality-benchmark](https://github.com/ranajahanzaib/kv-cache-quality-benchmark):** Python, local benchmark harness and dashboard for evaluating KV-cache compression in llama.cpp.

**AI Agent & LLM Evaluation**

- **[agent-tool-response-fault-tester](https://github.com/ranajahanzaib/agent-tool-response-fault-tester):** Python, local-first tool for testing how AI agents handle faulty tool responses through scripted and Ollama replays.
- **[agent-tool-selection-tester](https://github.com/ranajahanzaib/agent-tool-selection-tester):** Python, evaluates how reliably language models select and use tools as names, descriptions, schemas, and ordering change.
- **[finetuning-regression-tester](https://github.com/ranajahanzaib/finetuning-regression-tester):** Python, evaluates fine-tuned language models for task gains and behavioral regressions with paired tests.
- **[llm-chat-template-compatibility](https://github.com/ranajahanzaib/llm-chat-template-compatibility):** Python, investigates chat template, tokenization, and inference differences across local LLM runtimes.
- **[llm-fallback-compatibility-tester](https://github.com/ranajahanzaib/llm-fallback-compatibility-tester):** Rust, automated contract testing to ensure LLM provider failover preserves application behavior and safety.

**Machine Learning & Data Science**

- **[retail-demand-forecasting](https://github.com/ranajahanzaib/retail-demand-forecasting):** Python, production-grade retail demand forecasting and model reliability laboratory with FastAPI and React. Covers LightGBM, time-series modeling, and backtesting.
- **[marketplace-learning-to-rank](https://github.com/ranajahanzaib/marketplace-learning-to-rank):** Python, local learning-to-rank lab comparing rules, semantic search, and LightGBM LambdaMART on two-sided marketplace discovery.
- **[industrial-visual-defect-detection](https://github.com/ranajahanzaib/industrial-visual-defect-detection):** Python, unsupervised visual defect detection and inspection workbench for industrial QA/QC, built with PyTorch and FastAPI.
- **[cross-runtime-inference-tester](https://github.com/ranajahanzaib/cross-runtime-inference-tester):** Python, verifies ML inference parity, numerical drift, and latency across Python and browser ONNX runtimes.
- **[grid-disturbance-analysis](https://github.com/ranajahanzaib/grid-disturbance-analysis):** Python, production-grade signal processing and machine-learning engine for synchrophasor disturbance analysis, forced oscillation discrimination, modal damping estimation, and grid disturbance diagnostics, built with PyTorch and SciPy.

**Payments, Billing & Blockchain QA**

- **[usage-based-billing](https://github.com/ranajahanzaib/usage-based-billing):** Go, exact-decimal usage-based billing engine with proration, graduated tiers, storage accrual, and a PostgreSQL schema.
- **[payment-reconciliation](https://github.com/ranajahanzaib/payment-reconciliation):** Go, account-scoped payment reconciliation with provider snapshot simulation, deterministic mismatch detection, and JSON/CSV/HTML reporting.
- **[invoice-discrepancy-detector](https://github.com/ranajahanzaib/invoice-discrepancy-detector):** Python, local-first invoice reconciliation and discrepancy detection tool with deterministic matching.
- **[bitcoin-rbf-settlement-qa](https://github.com/ranajahanzaib/bitcoin-rbf-settlement-qa):** Local Go QA framework for Bitcoin merchant settlement. Tests real RBF replacements, confirmations, and chain reorganizations on Bitcoin Core regtest.
- **[ledger-to-chain-reconciler](https://github.com/ranajahanzaib/ledger-to-chain-reconciler):** Read-only Go CLI that reconciles deposit ledgers with ERC-20 transfers, detects discrepancies, and generates evidence-backed audit reports.
- **[indexer-replay-oracle](https://github.com/ranajahanzaib/indexer-replay-oracle):** Deterministic replay testing for blockchain event consumers, covering duplicate delivery, crash recovery, and SQLite/PostgreSQL state comparison.
- **[event-abi-guard](https://github.com/ranajahanzaib/event-abi-guard):** Offline Rust CLI that checks smart contract event ABI changes against declared consumer expectations. Detects signature and indexed-layout breaks, with JSON, Markdown, and GitHub Actions reports.

**Distributed Systems & SaaS Backend**

- **[background-job-recovery](https://github.com/ranajahanzaib/background-job-recovery):** Go reference architecture for crash-safe background job recovery using PostgreSQL fencing tokens, a transactional outbox, and NATS JetStream.
- **[distributed-request-debugger](https://github.com/ranajahanzaib/distributed-request-debugger):** Go, distributed request debugging and latency root-cause analysis with OpenTelemetry and Tempo.
- **[enterprise-user-provisioning](https://github.com/ranajahanzaib/enterprise-user-provisioning):** Go, multi-tenant SCIM v2 user provisioning and OIDC authentication service built on PostgreSQL.
- **[customer-data-export](https://github.com/ranajahanzaib/customer-data-export):** Go, tenant-scoped customer data export service with PostgreSQL job queuing, S3 storage, and offline archive verification.

**PostgreSQL & Database Reliability**

- **[zero-downtime-db-migrations](https://github.com/ranajahanzaib/zero-downtime-db-migrations):** Go, production-grade zero-downtime PostgreSQL schema migrations with phased rollouts, backfills, and verification.
- **[postgres-performance-analyzer](https://github.com/ranajahanzaib/postgres-performance-analyzer):** Rust, evidence-backed PostgreSQL performance investigations. Inspects query statistics, diagnoses EXPLAIN plans, tracks lock contention, and compares workload regressions.
- **[postgres-concurrency-tester](https://github.com/ranajahanzaib/postgres-concurrency-tester):** Rust, controlled PostgreSQL concurrency experiments to detect contention, lock waits, and pool starvation before production.
- **[postgres-backup-restore-checker](https://github.com/ranajahanzaib/postgres-backup-restore-checker):** Rust CLI that tests and validates PostgreSQL logical dumps inside disposable Docker containers.

**Cloudflare & Backend Reliability Tooling**

- **[d1-preflight](https://github.com/ranajahanzaib/d1-preflight):** Offline Rust CLI that analyzes Cloudflare D1 migrations against disposable SQLite snapshots. Detects schema risks, data loss, integrity failures, and query plan regressions.
- **[cf-quota-lab](https://github.com/ranajahanzaib/cf-quota-lab):** Tests Cloudflare Workers resource budgets before production. Runs representative local workloads, measures D1 and KV usage, projects consumption, and tests dependency failures with deterministic fault injection. No Cloudflare credentials needed.
- **[tenant-fence](https://github.com/ranajahanzaib/tenant-fence):** Tests tenant isolation in multi-tenant APIs using verified fixtures, safe mutation checks, and reproducible reports.
- **[api-backward-compatibility-tester](https://github.com/ranajahanzaib/api-backward-compatibility-tester):** Rust, catches breaking API changes before production with OpenAPI contract diffing and scenario replay.
- **[firestore-listener-ledger](https://github.com/ranajahanzaib/firestore-listener-ledger):** Local-first Firestore listener profiler. Analyzes subscription behavior and estimates read usage with explicit assumptions.

**Security & Infrastructure Auditing**

- **[security-assessment-coverage-reporter](https://github.com/ranajahanzaib/security-assessment-coverage-reporter):** Offline Rust CLI for auditing security assessment coverage from Nmap, OWASP ZAP, and Nuclei artifacts.
- **[webhook-security-tester](https://github.com/ranajahanzaib/webhook-security-tester):** Rust, local conformance testing for webhook signature validation, replay protection, and duplicate processing.
- **[network-exposure-policy-checker](https://github.com/ranajahanzaib/network-exposure-policy-checker):** Rust CLI that compares Docker Compose network exposure policies with configuration and TCP probe evidence.
- **[ai-media-provenance-checker](https://github.com/ranajahanzaib/ai-media-provenance-checker):** Rust CLI that checks whether embedded C2PA Content Credentials survive image processing. Runs the same JPEG/PNG pipeline as an unsigned raw branch and a provenance-aware reissue branch, then validates each output and its parent ingredient with the official C2PA SDK. Gives CI-ready evidence of where credentials get dropped.

**Scientific Data & Simulation Audits**

- **[conservation-ci](https://github.com/ranajahanzaib/conservation-ci):** Audits physics simulation trajectories against declared conservation laws. Local Rust CLI, API, and React dashboard with CI-ready reports.
- **[crater-seam](https://github.com/ranajahanzaib/crater-seam):** Audits and visualizes coordinate convention issues in planetary datasets. Rust CLI and local web app for Parquet/CSV, normalization, importer simulations, and regression checks.
- **[marsquake-mapcheck](https://github.com/ranajahanzaib/marsquake-mapcheck):** Provenance-aware audit of placeholder coordinates in NASA InSight's Marsquake catalog, with interactive maps comparing naive plotting to audited locations.
- **[transit-shortcut](https://github.com/ranajahanzaib/transit-shortcut):** Audits dataset shortcuts in exoplanet transit classification with reproducible metadata and raw-photometry baselines.
- **[reaction-variance](https://github.com/ranajahanzaib/reaction-variance):** Explores how reported yields vary across matched published C-N coupling experiments, with transparent comparisons of recorded conditions.
- **[particle-trace](https://github.com/ranajahanzaib/particle-trace):** Python, end-to-end investigation tool for tracing an individual particle through a simulated detector, built for high-energy physics and collider ML workflows.
- **[fireball-observatory](https://github.com/ranajahanzaib/fireball-observatory):** Rust, visual meteor observation analysis platform exploring 3.7M+ meteor trajectories and fireballs from the Global Meteor Network, running on Cloudflare Workers with ECharts.
- **[scientific-volume-viewer](https://github.com/ranajahanzaib/scientific-volume-viewer):** Python, inspects scientific Zarr datasets with an interactive WebGL2 3D viewer, chunk reads, slice previews, and access telemetry, backed by FastAPI.

**Genomics & Bioinformatics**

- **[genomic-ai-benchmark](https://github.com/ranajahanzaib/genomic-ai-benchmark):** Python, reproducible research demo for evaluating genomic foundation models, sequence baselines, biological generalization, and potential data leakage.
- **[genome-quality-inspector](https://github.com/ranajahanzaib/genome-quality-inspector):** Python, fast, local-first nucleotide sequence quality auditing for FASTA and FASTQ datasets.
- **[genome-assembly-studio](https://github.com/ranajahanzaib/genome-assembly-studio):** Python & Rust, explore, evaluate, and benchmark genome assemblies with interactive Circos, dot plots, and quality metrics built on D3.
- **[comparative-genome-observatory](https://github.com/ranajahanzaib/comparative-genome-observatory):** Python, local comparative genomics workbench for exploring alignment evidence (PAF), inspecting genomic intervals, and visualizing chromosome-scale relationships.
- **[gene-content-atlas](https://github.com/ranajahanzaib/gene-content-atlas):** Python, local comparative genomics workspace for exploring gene family presence, strain similarity, and pangenome statistics, with optional RefSeq and Panaroo workflows.
- **[microbial-ecology-map](https://github.com/ranajahanzaib/microbial-ecology-map):** Python, map-first atlas for exploring public environmental microbiome records, with MGnify ingestion, provenance-aware analysis, and an interactive global map.

**Geospatial & Earth Observation**

- **[satellite-infrastructure-change-ledger](https://github.com/ranajahanzaib/satellite-infrastructure-change-ledger):** Go & Python, open-source geospatial platform for monitoring, detecting, documenting, and verifying physical infrastructure changes from multi-temporal satellite imagery, with PostGIS.
- **[flood-impact-assessment](https://github.com/ranajahanzaib/flood-impact-assessment):** Python, multi-sensor satellite Earth observation platform to reconstruct, measure, and document flood extent and infrastructure impact, using PyTorch, GDAL, and Copernicus data.
- **[urban-infrastructure-auditor](https://github.com/ranajahanzaib/urban-infrastructure-auditor):** Go & Python, street-level infrastructure intelligence platform combining computer vision embeddings (SigLIP 2 and DINOv2), PostGIS spatial analysis, pgvector similarity search, and human-in-the-loop verification.
- **[maritime-anomaly-detection](https://github.com/ranajahanzaib/maritime-anomaly-detection):** Python, trajectory intelligence and anomaly detection platform for AIS maritime data. Features kinematic feature extraction, temporal deep sequence models (PyTorch TCN), DuckDB analytics, and MapLibre GL.

**Market Intelligence & Network Analytics**

- **[steam-publisher-observatory](https://github.com/LaymanMax/steam-publisher-observatory):** Go, market intelligence and portfolio concentration analytics for video game publishers on Steam.
- **[steam-developer-graph](https://github.com/LaymanMax/steam-developer-graph):** Rust, interactive network intelligence and entity resolution platform mapping business relationships across Steam developers, publishers, and games.
- **[steam-cohort-bench](https://github.com/LaymanMax/steam-cohort-bench):** Go, distribution-based market intelligence and cohort benchmarking for Steam games using DuckDB, Parquet, Go, and React.
- **[steam-storefront-linter](https://github.com/LaymanMax/steam-storefront-linter):** Rust, deterministic Steam store listing completeness auditor and descriptive peer benchmarking tool for indie game developers.
- **[steam-localization-atlas](https://github.com/LaymanMax/steam-localization-atlas):** Go, research workstation analyzing text and voice audio localization gaps across Steam games using Go, DuckDB, and React.
- **[venture-graph](https://github.com/ranajahanzaib/venture-graph):** Rust, explore investor co-investment networks with interactive graph analysis, source-aware data, and a Rust API.

</details>

<details>
<summary><b>65 Live Web Projects</b></summary>
<br>

React, Next.js, TypeScript, and Tailwind, deployed on Cloudflare Workers.

#### Landing Pages & Brand Websites (51)

**Beauty, Cosmetics & Fragrance (17)**

- [Vesper Botanicals](https://vesper-botanicals-cosmetics.work.withrana.com)
- [Pigment Proof Lipsticks](https://pigment-proof-lipsticks.work.withrana.com)
- [Rouge Archive Lipsticks](https://rouge-archive-lipsticks.work.withrana.com)
- [Material Labs](https://material-laboratory-cosmetics.work.withrana.com)
- [Blue Otherwise](https://blue-otherwise-cosmetics.work.withrana.com)
- [Scent Atlas Perfume](https://scent-atlas-perfume.work.withrana.com)
- [Still Hour Perfume](https://still-hour-perfume.work.withrana.com)
- [Aurel Cosmetics](https://aurel-cosmetics.work.withrana.com)
- [SoftMatter Cosmetics](https://soft-matter-cosmetics.work.withrana.com)
- [Verdant Labs](https://verdant-laboratory-cosmetics.work.withrana.com)
- [Aqua Studies](https://aqua-studies-cosmetics.work.withrana.com)
- [Amesi Clare](https://amesi-clare-cosmetics.work.withrana.com)
- [Solace Cosmetics](https://solace-storefront-cosmetics.work.withrana.com)
- [Morrow Cosmetics](https://morrow-cosmetics.work.withrana.com)
- [Aure Foundation](https://aure-foundation-cosmetics.work.withrana.com)
- [The Impossible Fragrance](https://the-impossible-fragrance.work.withrana.com)
- [Solstice Sunscreen](https://solstice-sunscreen-brand.work.withrana.com)

**Fashion, Footwear & Accessories (6)**

- [Hoodies Sale](https://form-study-new-year-sale-2027-hoodies.work.withrana.com)
- [Hoodies Landing Page](https://form-objects-hoodies.work.withrana.com)
- [Footwear Brand](https://roam-landing-page.preview.withrana.com/)
- [Gravity Rewritten Heels](https://gravity-rewritten-heels.work.withrana.com)
- [Step 001 Heels](https://step-001-heels.work.withrana.com)
- [Veyra Luxury Watches](https://veyra-luxury-watches.work.withrana.com)

**Luxury, Travel & Hospitality (5)**

- [Serein Private Residence](https://serein-private-residence.work.withrana.com)
- [Aeren Private Flight](https://aeren-private-flight.work.withrana.com)
- [Serein Lofoten Resort](https://serein-lofoten-luxury-resort.work.withrana.com)
- [The World Unfolds](https://the-world-unfolds-luxury-travel-agency.work.withrana.com)
- [Beyond the Edge](https://beyond-the-edge-adventure-tourism-brand.work.withrana.com)

**Outdoor, Sports & Lifestyle (9)**

- [Ridgeline Mountain Bikes](https://ridgeline-terrain-machine-mountain-bikes.work.withrana.com)
- [Northline Camping Gear](https://northline-field-equipment-outdoor-camping-gear.work.withrana.com)
- [Vector Tennis Rackets](https://vector-tennis-rackets.work.withrana.com)
- [Orison Hiking Backpack](https://orison-field-equipment-hiking-backpack.work.withrana.com)
- [Afterimage Coffee](https://afterimage-coffee-brand.work.withrana.com)
- [Forme of Light Candles](https://forme-of-light-luxury-candles.work.withrana.com)
- [Vesper Kitchenware](https://vesper-kitchenware.work.withrana.com)
- [Book Sales](https://lucent-landing-page.preview.withrana.com/)
- [Concept Device](http://pixelmint-landing-page.preview.withrana.com/)

**Art, Culture & Creative Studios (7)**

- [The Lucid Between](https://the-lucid-between-digital-art-exhibition.work.withrana.com)
- [Aperture Fieldwork](https://aperture-fieldwork-architecture-studio.work.withrana.com)
- [The Tide Keeps Its Rooms](https://the-tide-keeps-its-rooms-film-premiere.work.withrana.com)
- [Nacre Museum](https://nacre-museum.work.withrana.com)
- [Still Here Photography](https://still-here-photography-studio.work.withrana.com)
- [Creative Agency](https://ember-studio-landing-page.preview.withrana.com/)
- [Design Agency](https://fernway-landing-page.preview.withrana.com/)

**Technology & Services (7)**

- [Morrow Image Studio](https://morrow-image-studio-ai-img-generation.work.withrana.com)
- [Forme No-Code Builder](https://forme-no-code-website-builder.work.withrana.com)
- [Kernel Developer API](https://kernel-field-developer-api-platform.work.withrana.com)
- [Form Field Packaging](https://form-field-sustainable-packaging-startup.work.withrana.com)
- [AI Workflow Automation](https://autoloom-landing-page.preview.withrana.com/)
- [Link in Bio Tool](https://perch-landing-page.preview.withrana.com/)
- [Dental Clinic](https://meridian-dental-landing-page.preview.withrana.com)

#### Storefronts (10)

- [Footwear Shop](https://ferrous-footwear.work.withrana.com/)
- [Clothing Store](https://meridian-clothing-store.work.withrana.com)
- [Kidswear Shop](https://marlowe-n-finch-kidswear-store.work.withrana.com)
- [Sunglasses Store](https://sunspot.work.withrana.com)
- [Furniture Shop](https://atelier-grove.work.withrana.com)
- [Handbags Store](https://maison-ore.work.withrana.com)
- [Sana Clothing Shop](https://maison-sana.work.withrana.com)
- [Elemara Clothing Store](https://elemara.work.withrana.com)
- [LUME Cosmetics](https://lume.work.withrana.com)
- [Hair Oil & Serum Store](https://verre-or.work.withrana.com)

#### Websites (4)

- [Seaside Luxury Hotel](https://marejada-seaside-hotel.work.withrana.com)
- [Y2K Editorial Fashion](https://y2k-editorial-fashion.work.withrana.com)
- [Art Gallery](https://solstice-gallery.work.withrana.com)
- [Therapy Practice](https://solace-collective-landing-page.preview.withrana.com/)

</details>
