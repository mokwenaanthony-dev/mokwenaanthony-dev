# Anthony Mokwena

**Software developer · Johannesburg, South Africa**  
Over 20 years building enterprise systems on Oracle, now building them in Python.

I've spent my career as an analyst programmer on business-critical systems in retail, financial
services, ticketing and municipal electricity metering, at companies including Pepkor, Sage, Liberty
Life, Computicket and SAAB Grintek. Most recently, at Pepkor NexTech, I worked as a Senior Analyst
Programmer on the **Merchandise Management System (MMS)**, the retail system behind buying, stock and
pricing. My background is PL/SQL, Oracle Forms and Sage X3 ERP, so I know how real businesses run on
their data. I'm now applying that experience to Python backend development.

## Featured projects

### [ERP-Intelligence](https://github.com/mokwenaanthony-dev/ERP-Intelligence)
An ERP designed to be **connected and AI-ready**, not just transactional. The goal: the current *and
future* state of the business known in real time; ML predicts, AI recommends, **people decide**
([vision](https://github.com/mokwenaanthony-dev/ERP-Intelligence/blob/main/docs/VISION.md)).

- **Core:** an SAP-style modular monolith in Django/DRF and PostgreSQL: a Universal Journal that
  every module posts to, immutable documents, business rules in a service layer, and every
  operation idempotent.
- **Modules:** Financials, stock with moving-average valuation, order-to-cash, procure-to-pay with
  three-way match, HR with South African payroll, cost and profit centres, production planning and
  orders on the ISA-95 model, CRM and SRM.
- **Intelligence:** an analytics layer with Metabase dashboards; a **Neo4j knowledge graph** fed by a
  transactional outbox (Customer 360, document flow, knowledge-graph retrieval, KG-RAG, for AI
  agents); demand forecasting in a separate **FastAPI** service; **MRP**; revenue at risk per supplier.
- **Shop floor:** a Unified Namespace (MQTT, ISA-95 topics) links the ERP to the MES below.
- **Quality:** 870+ tests, 95% coverage, CI with linting, security scanning, dependency auditing and
  contract tests between services; 16 architecture decision records; a release per wave.

[Architecture](https://github.com/mokwenaanthony-dev/ERP-Intelligence/blob/main/docs/ARCHITECTURE.md) ·
[Decisions](https://github.com/mokwenaanthony-dev/ERP-Intelligence/tree/main/docs/decisions)

### [MES-Intelligence](https://github.com/mokwenaanthony-dev/MES-Intelligence)
The shop floor that ERP-Intelligence talks to: a Python MES with store-and-forward, and **Rust edge
agents** (standard library only) reading a simulated PLC over Modbus TCP and publishing to MQTT.
A cross-language end-to-end test runs in CI.

## Tech

**Now:** Python · Django · Django REST Framework · FastAPI · PostgreSQL · Neo4j · Celery · Redis · MQTT · Docker · pytest · GitHub Actions  
**Also:** Rust (edge agents) · numpy (forecasting) · ISA-95 · Metabase  
**Background:** Oracle SQL & PL/SQL · Oracle Forms · Oracle DBA · Sage X3 · C# · VB.NET · COBOL · Jasper Reports · Azure

## Certifications

- Oracle Certified Professional: Advanced PL/SQL Developer
- Oracle Certified Professional: Oracle Forms Developer
- Oracle Certified Associate: PL/SQL Developer
- Oracle Cloud Infrastructure Foundations Associate
- Microsoft Azure Fundamentals
- Atlassian Jira Fundamentals
- PCEP: Certified Entry-Level Python Programmer (2026)
- *In progress:* PCAP: Certified Associate Python Programmer, then PCPP

**Education:** Diploma in IT (Software Development), UNISA

## Contact

[LinkedIn](https://www.linkedin.com/in/anthony-j-m-mokwena-23a66857) · ajmokwena@yahoo.co.uk
