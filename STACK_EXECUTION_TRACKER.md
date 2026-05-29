# Stack Execution Tracker

This tracker converts the KingRwaz GitHub stack into execution workstreams.

Issues are currently disabled on `KingRwaz/oh-my-codex`, so execution is being tracked through this Markdown file.

## Workstream 1: Stack Governance

Status: `ACTIVE`
Priority: High
Owner: KingRwaz

### Objective
Create a ranked, governed inventory of repositories and decide which tools become active production systems.

### Tasks

- [ ] Confirm top 30 repositories for immediate triage.
- [ ] Assign every priority repo one state: `USE_NOW`, `STUDY_LATER`, `ARCHIVE_REFERENCE`, or `REVIEW_FIRST`.
- [ ] Score repos from 1 to 5 across usefulness, deployment ease, documentation quality, maintenance, security trust, and business leverage.
- [ ] Create master repository inventory table.
- [ ] Identify risky repos requiring license, privacy, or security review.
- [ ] Decide which repos become active production systems.

### Deliverable
`STACK_REPOSITORY_INVENTORY.md`

---

## Workstream 2: Amphora Foods / Tribesmen Brand System

Status: `ACTIVE`
Priority: Very High
Target repo: `KingRwaz/Amphora-Foods`

### Objective
Turn `Amphora-Foods` into the structured working home for Tribesmen and Amphora Foods commercial assets.

### Proposed folder structure

```text
/brand-profile
/product-lines
/export-offers
/buyer-intake
/packaging-copy
/market-mix
/photos-and-assets
/compliance-documents
/templates
```

### Tasks

- [ ] Create brand profile folder.
- [ ] Create individual product profiles for coffee, cocoa, fresh fruit, vegetables, fruit juices, tomato paste, ginger paste, onion paste, and whipped honey.
- [ ] Create market-mix documents for international markets.
- [ ] Create buyer intake sheet.
- [ ] Create first shipment readiness matrix.
- [ ] Create export offer template.
- [ ] Create packaging copy template.

### Deliverables

- `BRAND_PROFILE_MASTER.md`
- `PRODUCT_LINE_DEPTH.md`
- `BUYER_INTAKE_SHEET.md`
- `FIRST_SHIPMENT_READINESS_MATRIX.md`
- `EXPORT_OFFER_TEMPLATE.md`

---

## Workstream 3: Finance, Trading, and Commodity Intelligence

Status: `ACTIVE`
Priority: High
Relevant repos:

- `KingRwaz/FinceptTerminal`
- `KingRwaz/TradingAgents`
- `KingRwaz/awesome-ai-in-finance`
- `KingRwaz/the-wisdom-of-trade-stocks`

### Objective
Create a commodity intelligence layer for gold, coffee, cocoa, non-ferrous metals, buyer readiness, export pricing, and transaction risk.

### Tasks

- [ ] Create commodity intelligence playbook.
- [ ] Create gold transaction readiness checklist.
- [ ] Create coffee export pricing intelligence template.
- [ ] Create buyer and seller profile scoring sheet.
- [ ] Create customs, broker, refinery, and logistics checklist.
- [ ] Create investor memo format for commodity deals.

### Deliverables

- `COMMODITY_INTELLIGENCE_PLAYBOOK.md`
- `GOLD_TRANSACTION_READINESS.md`
- `COFFEE_EXPORT_PRICING_TEMPLATE.md`
- `BUYER_SELLER_SCORING.md`

---

## Workstream 4: CAD, Design, and Infrastructure

Status: `ACTIVE`
Priority: High
Relevant repos:

- `KingRwaz/FreeCAD`
- `KingRwaz/awesome-blender`

### Objective
Create reusable design workflows for stadiums, packhouses, tissue culture labs, agro-processing facilities, greenhouses, hydroponics, product mockups, and investor visuals.

### Tasks

- [ ] Create site layout brief template.
- [ ] Create room schedule template.
- [ ] Create structural element schedule template.
- [ ] Create FreeCAD modeling prompt template.
- [ ] Create Blender render prompt template.
- [ ] Create investor presentation visual brief template.

### Deliverables

- `INFRASTRUCTURE_DESIGN_WORKFLOW.md`
- `FREECAD_MODELING_PROMPT.md`
- `BLENDER_RENDER_PROMPT.md`
- `ROOM_AND_SITE_SCHEDULE_TEMPLATE.md`

---

## Workstream 5: Geospatial and Field Intelligence

Status: `ACTIVE`
Priority: High
Relevant repo:

- `KingRwaz/Awesome-Geospatial`

### Objective
Create field intelligence systems for Mityana South, agriculture, water, roads, parishes, villages, project sites, and political/community mobilization.

### Proposed folder structure

```text
/geospatial
  /boundaries
  /water
  /roads
  /agriculture
  /population
  /project-sites
  /maps-output
```

### Tasks

- [ ] Create geospatial data governance notes.
- [ ] Define parish and village mapping standards.
- [ ] Define water access mapping standards.
- [ ] Define agriculture zoning standards.
- [ ] Define project-site suitability scoring.
- [ ] Define map output formats for reports and dashboards.

### Deliverables

- `GEOSPATIAL_FIELD_INTELLIGENCE.md`
- `MITYANA_SOUTH_MAPPING_STANDARD.md`
- `PROJECT_SITE_SCORING_TEMPLATE.md`

---

## Workstream 6: Automation, Dashboards, and Deployment

Status: `ACTIVE`
Priority: High
Relevant repos:

- `KingRwaz/awesome-n8n-templates`
- `KingRwaz/awesome-docker`
- `KingRwaz/dashy`

### Objective
Build a command-center layer for AI agents, business projects, document production, commodity intelligence, agriculture, exports, and design workflows.

### Tasks

- [ ] Create dashboard sitemap.
- [ ] Define n8n automation candidates.
- [ ] Define Docker/self-hosting requirements.
- [ ] Create document automation workflow.
- [ ] Create project tracking workflow.
- [ ] Create brand asset production workflow.

### Deliverables

- `COMMAND_DASHBOARD_PLAN.md`
- `N8N_AUTOMATION_CANDIDATES.md`
- `DOCKER_DEPLOYMENT_BASELINE.md`

---

## Workstream 7: Prompt Engineering and Knowledge Systems

Status: `ACTIVE`
Priority: High
Relevant repos:

- `KingRwaz/awesome-prompts`
- `KingRwaz/awesome-notebookLM-prompts`
- `KingRwaz/awesome-generative-ai-guide`
- `KingRwaz/awesome-nano-banana-pro-prompts`

### Objective
Convert prompt collections into a governed prompt library for repeated high-quality outputs.

### Proposed folder structure

```text
/prompts
  /business-strategy
  /proposal-writing
  /brand-and-marketing
  /agriculture
  /finance-and-commodities
  /cad-and-design
  /document-analysis
  /executive-communications
  /risk-review
```

### Tasks

- [ ] Create master prompt index.
- [ ] Create prompt quality standard.
- [ ] Create proposal-writing prompt pack.
- [ ] Create product-branding prompt pack.
- [ ] Create document-analysis prompt pack.
- [ ] Create CAD/design prompt pack.
- [ ] Create risk-review prompt pack.

### Deliverables

- `PROMPT_LIBRARY_GOVERNANCE.md`
- `MASTER_PROMPT_INDEX.md`
- `PROPOSAL_WRITING_PROMPTS.md`
- `BRAND_MARKETING_PROMPTS.md`

---

## Workstream 8: Security, Risk, and Secrets

Status: `REVIEW_FIRST`
Priority: Critical
Relevant repos:

- `KingRwaz/awesome-threat-detection`
- `KingRwaz/awesome-threat-intelligence`
- `KingRwaz/awesome-pentest-cheat-sheets`
- `KingRwaz/CloakBrowser`
- `KingRwaz/sakura-secretmanager-simulator`
- `KingRwaz/neko-api-key-tool`

### Objective
Use security-related repositories only for defensive protection, privacy, business continuity, safe coding, and secret management.

### Tasks

- [ ] Create GitHub secrets policy.
- [ ] Create `.env` and `.env.example` rules.
- [ ] Create public/private repo rules.
- [ ] Create license review checklist.
- [ ] Create defensive security usage policy.
- [ ] Create business document privacy policy.

### Deliverables

- `SECURITY_AND_SECRET_HANDLING_POLICY.md`
- `LICENSE_REVIEW_CHECKLIST.md`
- `PUBLIC_PRIVATE_REPO_RULES.md`
- `DEFENSIVE_SECURITY_POLICY.md`

---

## Execution rule

A repository is promoted to `USE_NOW` only if it supports one of these outputs:

- Document
- Dashboard
- Automation
- Product
- Client deliverable
- Financial decision
- Infrastructure design
- Field operation
- Security protection
- Repeatable workflow
