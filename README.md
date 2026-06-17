# Andrey Bogatyrev — Program / Project Manager
### Cloud Infrastructure & EdTech

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
- Led migration of 108 legal entities into unified ERP system
- Impact: ~10,000 users; team of up to 15 engineers; delivered on time

`1С:ERP` `MS Project`

---

**Government Analytics Dashboards**
- Delivered analytics system for monitoring government programs (~5,000 users)

`Power BI`

---

**IT Localization (Import Substitution Program)**
- Full-scale migration of IT systems to local infrastructure (~4,000 users)
- Replaced foreign solutions; designed new network and infrastructure architecture

`Russian infrastructure platforms`

---

### Omnitech / Zavkom Group — Project Specialist (2014 — 2021)
- End-to-end delivery of complex industrial equipment projects
- Led tenders, negotiations, logistics and contract execution

---

## Side Project

**SABI — Founder / Project Lead (2024 — Present)**
- Launched online education platform from scratch
- 5,000+ subscribers, 200+ students, 3 courses
- Built and manage a team of 6; responsible for product, marketing and operations

`Custom-built platform`

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
- [product-scaling-readiness](https://github.com/tarasytch/product-scaling-readiness) — Program framework: self-deployment, distribution, release docs, observability across enterprise products


