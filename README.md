# Andrey Bogatyrev

### Senior Technical Project Manager | Cloud Infrastructure & Platform Reliability | Stakeholder Management | EdTech | AI in Project Management

Program / Project Manager with 5+ years of experience in cloud infrastructure, digital transformation and EdTech. Lead cross-team initiatives across ~300 services, focusing on reliability, observability, high availability and large-scale migrations. Experienced in remote cross-functional delivery and enterprise stakeholder management. English — C1.

---

## Key Achievements

- 18,000 VM migrated with zero downtime
- 99.95% HA achieved across IaaS, Kubernetes and DBaaS
- ~300 services under program management
- 10+ engineering teams aligned simultaneously
- 108 legal entities migrated into unified ERP (~10,000 users)
- EdTech: 5,000+ subscribers, 200+ students, launched from scratch

---

## Experience

### VK Cloud — Program / Project Manager (2023 — Present)

**VK Tech Infrastructure Migration (2025 — Present)**
- Led migration of core platform components (control-plane and data-plane)
- Zero downtime for critical services; coordinated 5+ cross-functional teams
- Owned planning, execution, communication and risk management

`Nova` `Neutron` `Cinder` `Glance` `Keystone` `Managed Kubernetes` `PostgreSQL` `MySQL` `Redis` `ClickHouse` `Jira` `Confluence` `Terraform` `Ansible`

---

**X4 Program — Product Scaling Readiness (2025)**
- Led cross-company program to enable self-deployment and operation of enterprise products by clients and partners
- Managed 4 parallel tracks: self-deployer, customer portal & distribution, release documentation (Shift Right), unified observability
- Drove reduction of vendor-assisted deployment cycles and L3/L4 support load

`Jira` `Confluence`

---

**High Availability (2023 — 2024)**
- Drove 3 AZ control-plane migration program: coordinated 54 engineering tasks across DEV and SRE tracks
- **Neutron / SDN:** fullsync runbook and fencing mechanisms; Neutron DB isolation; OVS flow persistence on hypervisors; Sprut (SDN) adopted as default, replacing Neutron for new users; Neutron → Sprut migration utility
- **Compute:** Nova graceful degradation on network unavailability; VM auto-recovery after hypervisor failure; VM evacuation optimization; API read-only mode during incidents
- **Data layer:** Stolon/PostgreSQL Keeper auto-start fix; RabbitMQ queue auto-recreation; multi-DC Temporal cluster
- **PaaS / Storage:** HighIOPS HA; Ceph/Cinder failure handling; Kubernetes container audit across AZs
- **Platform:** IAM AZ failure tolerance; Billing components HA (charge engine, cashflow engine); Octavia healthcheck shutdown on mass entity loss; Status Page HA

→ [openstack-ha-3az](https://github.com/tarasytch/openstack-ha-3az) — full program documentation · [openstack-dr-playbook](https://github.com/tarasytch/openstack-dr-playbook) — DR process built on top of this HA foundation

`Nova` `Neutron` `Sprut` `Octavia` `Ceph` `Stolon` `RabbitMQ` `Temporal` `IAM` `Kubernetes`

---

**Observability (2023–2024)**
- Designed SLI/SLO framework covering 10 business scenarios across IaaS and PaaS (VM uptime, new VM creation, UI availability, Billing, Backup, K8s, DBaaS, Analytical DB, ML, S3)
- Defined per-scenario measurement methodology: error budget, 30-day rolling windows, escalation thresholds per client tier
- Implemented centralized monitoring for 10+ core services; consolidated fragmented tools into a unified metrics space

→ [sli-slo-framework](https://github.com/tarasytch/sli-slo-framework) — published methodology

`Grafana` `SLI/SLO` `VK WorkSpace (alerting)`

---

**Disaster Recovery Process (2023)**
- Designed and implemented DR process from scratch
- Formalized incident response at platform level
- Led DR tests on Stage and Production; established regular DR testing practices

`Confluence` `Manual + Automated DR Testing`

---

### IBS — Project Manager (2021 — 2023)

**ERP 2.0 Implementation (1C)**
- Led migration functional block across 108 legal entities with heterogeneous chart-of-accounts structures into a unified ERP
- ~10,000 users; team of up to 15 engineers; delivered on time under enterprise commercial contract
- Onboarded intern cohort from IBS Career Reboot program — 80%+ successfully integrated into the project team
  
`1С:ERP` `MS Project`

---

**Government Analytics Dashboards** (NDA project)
- Delivered analytics system for monitoring government programs (~5,000 users)

`Power BI`

---

**IT Localization - Ball Beverage Packaging (2022)**
- Led IT separation of Ball Corporation's Russian business (~800 IT users, 5 sites) from global corporate infrastructure under 2022 sanctions
- Built independent hybrid-cloud environment on Russian providers; migrated Active Directory, replaced Cisco telephony, Symantec AV, and all globally-managed services
- Delivered on time with zero production downtime; managed international stakeholder environment under extreme deadline pressure

`MS Active Directory` `Hybrid Cloud` `Infrastructure Migration` `InfoSec`

---
**IT Localization - Michelin (2022)**
- Led full-cycle IT localization for Michelin's Russian operations exiting the country under 2022 sanctions
- Scope: audit, architecture design, and deployment of AD, network (LAN/WiFi/VPN), InfoSec, backup, virtualization, and telephony
- Delivered on time with zero production downtime; coordinated international stakeholders across Russian and French teams

`MS Active Directory` `Network Infrastructure` `InfoSec` `Virtualization`

---

### Omnitech / Zavkom Group — Project Specialist (2014 — 2021)
- End-to-end delivery of complex industrial equipment projects
- Led tenders, negotiations, logistics and contract execution

---

## Side Project

**SABI — Founder / Project Lead (2024 — Present)**
- Built a cross-model multi-agent AI content production system from scratch on Anthropic Claude Code Agent SDK
- Designed 6-agent decomposition (Opus + Sonnet + Haiku) with exclusive write-access boundaries per agent — refactored from a 280-line monolith after conflict analysis
- 14 composable skill pipelines: Instagram carousels, longform articles, YouTube localization (ElevenLabs voice clone), competitor research
- Cross-model image generation: GPT-Image-2 + Grok Imagine via FAL.AI; Figma API for carousel assembly; 5-channel publishing automation
- Designed HITL lessons loop: agents propose structured lessons (What/Why/Rule), owner confirms, lessons accumulate per-agent — compounding institutional memory without code changes
- 2-layer quality system: 29-pattern anti-slop lint + verbatim source ratio enforcement (≥55%)
- 5,000+ subscribers, 2 markets (EN/ES), 5 publication channels

→ [sabi-ai-pipeline](https://github.com/tarasytch/sabi-ai-pipeline) — system architecture and pipeline documentation

`Claude Opus` `Claude Sonnet` `GPT-Image-2` `Grok Imagine` `ElevenLabs` `FAL.AI` `Figma API` `Apify` `Python`

---

## Stack

**Methodologies:** Agile · Scrum · Kanban · Waterfall

**PM Tools:** Jira · Confluence · Miro · Notion · MS Project

**Languages:** Russian (native) · English (C1)

---

## Contact

- Email: i@abogatyrev.com
- Website: [abogatyrev.com](https://abogatyrev.com)


---

## Projects on GitHub

- [openstack-dr-playbook](https://github.com/tarasytch/openstack-dr-playbook) — Production DR framework: 15+ OpenStack components, quarterly AZ failure tests
- [vktech-dc-migration](https://github.com/tarasytch/vktech-dc-migration) — DC migration playbook: 18,000 VM, 11 stages, multi-AZ, zero downtime
- [sli-slo-framework](https://github.com/tarasytch/sli-slo-framework) — SLI/SLO methodology: 10 business scenarios across IaaS and PaaS, error budget approach
- [openstack-ha-3az](https://github.com/tarasytch/openstack-ha-3az) — 3 AZ HA program: 54 tasks across Neutron/SDN, compute, data layer, billing, platform
- [sabi-ai-pipeline](https://github.com/tarasytch/sabi-ai-pipeline) — 6-agent cross-model AI content system: Claude + GPT-Image-2 + Grok + ElevenLabs, HITL lessons loop
- [product-scaling-readiness](https://github.com/tarasytch/product-scaling-readiness) — Program framework: self-deployment, distribution, release docs, observability across enterprise products


