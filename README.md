# Awesome-Warehouse-Control-System

#### Top Warehouse Control System (WCS) Ecosystem

**Curated List of Commercial / SaaS Platforms & Open-Source GitHub Projects**
*Focused on Warehouse Control, Material Flow Control, Warehouse Execution, Automation Orchestration & Intralogistics*
**Last updated: August 2026**

This repository tracks notable **commercial / hosted platforms** and **open-source projects** for **Warehouse Control Systems (WCS)**, Material Flow Control (MFC), Warehouse Execution Systems (WES), and warehouse automation orchestration.

These systems sit between the **WMS/ERP layer and physical automation**, coordinating conveyors, sorters, AS/RS, shuttles, AMRs/AGVs, robotic systems, goods-to-person stations, scanners, PLCs, and other material-handling equipment.

**Examples** include Swisslog SynQ, Dematic iQ / WCS, Körber WCS / K.OneX, Made4net WCS, Mecalux Easy WMS, WITRON software, Daifuku warehouse control software, FORTNA WES/WCS, SSI SCHAEFER WAMAS, and KNAPP KiSoft.

**Open-source emphasis**: This list is deliberately weighted toward projects that can be **self-hosted, inspected, modified, integrated with custom automation, or used as foundations for building a vendor-neutral WCS/WES**. Because genuinely production-grade open-source WCS products are still rare, the list also includes strong open-source **WMS/MFC/WES, PLC, industrial-IoT, workflow, simulation, and automation building blocks** that can form part of an open warehouse-control stack.

> **Important:** Not every project in the Open-Source section is a complete WCS equivalent. Projects are identified as **Direct WCS/MFC**, **WES/WMS**, or **Automation Building Block** where appropriate.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official project repositories or vendor sites.

## Table of Contents

* [SaaS/Hosted Platforms](#saashosted-platforms)
* [Open-Source GitHub Projects](#open-source-github-projects)
* [Additional Strong Open-Source Options](#additional-strong-open-source-options)
* [Recommended Open-Source WCS Stack](#recommended-open-source-wcs-stack)
* [How to Contribute](#how-to-contribute)
* [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform / Product | Description & Capabilities | Pricing (Starting Tier) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Swisslog SynQ](https://www.swisslog.com/en-us/products-systems-solutions/software-inventory-management/synq-warehouse-management-system-wms-mfcs)** | Intelligent intralogistics platform combining WMS, WCS, and Material Flow Control (MFC) to orchestrate automated warehouses, AS/RS, AutoStore, CycloneCarrier, and robotic picking. | Starts at **$2,500/month** (~$30,000/year) for entry-tier base MFC/WCS module and single automated zone orchestration. | **30-day guided POC sandbox** trial with simulated MHE device telemetry and sample warehouse layout (no permanent free tier). |
| **[Dematic iQ / Dematic WCS](https://www.dematic.com/)** | Enterprise warehouse software ecosystem covering WCS, WES, and WMS for real-time equipment routing, Multishuttle systems, conveyor control, and high-speed sortation. | Starts at **$4,166/month** (~$50,000/year) for base WCS equipment interface and core material flow routing module. | **30-day structured pilot sandbox** with virtual warehouse emulation, simulated conveyor loops, and throughput stress testing (no perpetual free tier). |
| **[Körber WCS / K.OneX](https://www.koerber.com/)** | Vendor-agnostic warehouse control suite designed to orchestrate heterogeneous MHE, AMR/AGV fleets, AS/RS, and automated goods-to-person workflows with modular SAP integration. | Starts at **$5,000/month** (~$60,000/year) for K.OneX / K.Motion WCS base license tier. | **30-day Proof-of-Value (POV) trial** including cloud simulation tenant, sample workflow templates, and up to 5 simulated PLC/device endpoints (no perpetual free tier). |
| **[Made4net WCS / SCExpert](https://made4net.com/platform/)** | Rules-based, highly configurable WMS/WCS/WES platform with native real-time control of automated conveyors, AS/RS, shuttles, AGVs, and robotic sorting systems. | Starts at **$500/month** (~$6,000/year) for entry cloud tier (or ~$1,000/month with automation MHE add-on). | **14-day cloud sandbox trial** with full feature access, 1 test facility, up to 5 user logins, and 500 test SKU/order records (no perpetual free tier). |
| **[Mecalux Easy WMS](https://www.mecalux.com/software/easy-wms)** | Warehouse management and automation control software managing manual, semi-automated, and fully automated storage systems with integrated WCS/MFS modules. | Starts at **$500/month** (~$6,000/year) for SaaS entry Pro tier (or ~$1,200/month for automated MHE-integrated tier). | **14-day interactive cloud demo sandbox** with preloaded test catalog, 1 simulated warehouse zone, and up to 1,000 test transactions (no perpetual free tier). |
| **[WITRON](https://www.witron.com/)** | End-to-end proprietary warehouse automation and MFC software optimizing high-throughput order picking (OPM), dynamic AS/RS, and automated distribution center logistics. | Starts at **$10,000/month** (~$120,000/year) for base MFC and software controller module layer in modular enterprise deployments. | **30-day design & simulation evaluation** (digital twin throughput modeling and material-flow stress testing during engineering scoping; no perpetual free tier). |
| **[Daifuku](https://www.daifuku.com/)** | Integrated intralogistics and material-handling control software managing AS/RS stacker cranes, conveyor networks, sortation systems, and automated vehicle fleets. | Starts at **$8,000/month** (~$96,000/year) for base controller software package and standard equipment integration tier. | **30-day pre-commissioning simulation environment** with virtual PLC controllers and up to 10 automated device mappings (no perpetual free tier). |
| **[FORTNA](https://www.fortna.com/)** | Enterprise Warehouse Execution (FORTNA WES) and Control software for real-time dynamic resource allocation, automated picking, and multi-vendor MHE orchestration. | Starts at **$6,250/month** (~$75,000/year) for base WES orchestration module. | **30-day guided interactive emulation trial** with digital twin facility modeling and workflow optimization analysis (no perpetual free tier). |
| **[SSI SCHAEFER WAMAS](https://www.ssi-schaefer.com/)** | Modular logistics software suite connecting WMS, material flow control (MFC/WCS), and machine control systems (PLC) with real-time 3D visualization. | Starts at **$3,500/month** (~$42,000/year) for base WAMAS MCS/WCS instance license. | **30-day virtual commissioning test period** using WAMAS 3D Digital Twin simulation with simulated transport orders (no perpetual free tier). |
| **[KNAPP KiSoft](https://www.knapp.com/)** | Modular intralogistics software suite covering WMS, WCS, and MFC machine-control communication for shuttles, OSR Shuttle Evo, and automated picking robots. | Starts at **$4,500/month** (~$54,000/year) for entry KiSoft WCS/MFC software subscription. | **30-day guided sandbox access** with virtual emulation environment, up to 3 test workstations, and sample SKU databases (no perpetual free tier). |
| **[Manhattan Active Warehouse Management](https://www.manh.com/)** | Cloud-native, microservices-based enterprise WMS/WES combining order streaming, real-time robotics orchestration, and dynamic task management. | Starts at **$166/user/month** ($2,000/user/year) with entry cloud deployment tier starting at **$10,000/month** (~$120,000/year). | **30-day cloud test tenant** for qualified enterprise evaluations (includes preconfigured sandbox, 5 user accounts, and API sandbox access; no perpetual free tier). |
| **[Blue Yonder Warehouse Management](https://blueyonder.com/)** | Enterprise fulfillment and warehouse management platform featuring automation integration, real-time task orchestration, and robotics integration. | Starts at **$6,666/month** (~$80,000/year) per site for baseline cloud tier. | **30-day guided Proof-of-Value (POV)** sandbox environment with sample fulfillment workflows and up to 10 test operator profiles (no perpetual free tier). |
| **[SAP Extended Warehouse Management](https://www.sap.com/products/scm/extended-warehouse-management.html)** | Enterprise WMS/MFS platform with Material Flow System (MFS) capability to connect directly to PLCs, automated conveyors, and AS/RS without standalone WCS. | Basic EWM included in SAP S/4HANA (from **$1,000/month** ERP entry); Advanced EWM add-on starts at **$116/user/month** (or starting at **$5,000/month** base). | **30-day free trial** via SAP S/4HANA Cloud / SAP Discovery Center (includes preloaded best-practice warehouse data and 1 sandbox tenant; no perpetual free tier). |
| **[Oracle Warehouse Management](https://www.oracle.com/scm/logistics/warehouse-management/)** | Comprehensive cloud WMS (formerly LogFire) providing real-time automation integration, inventory tracking, task dispatching, and MHE interfacing. | Starts at **$125/user/month** (or entry cloud subscription starting at **$2,083/month** / $25,000/year base). | **30-day trial with $300 Oracle Cloud free credits** to spin up and test Oracle WMS Cloud sandboxes and APIs (no perpetual free tier). |

## Open-Source GitHub Projects

* **[openWCS](https://github.com/openwcs)**
  **Direct WCS — strongest open-source WCS candidate.**
  An open-source, vendor-neutral Warehouse Control System designed to orchestrate conveyors, AS/RS, AMRs and AutoStore-style automation. Includes transport routing, process orchestration, inventory, allocation, goods-to-person stations, slotting, replenishment, equipment adapters and a live 3D warehouse digital twin.

* **[OpenWMS.org](https://github.com/openwms/org.openwms)**
  **Direct WMS + MFC.**
  One of the most important open-source projects for this category. OpenWMS.org is an extensible warehouse-management system with a **Material Flow Control (MFC)** system for both automated and manual warehouses. Its architecture includes microservices and dedicated transport/routing functionality.

* **[OpenWMS TMS Routing](https://github.com/openwms/org.openwms.tms.routing)**
  **Direct MFC / WCS component.**
  OpenWMS routing software for automated warehouses that routes transport units through conveyor networks, selects workflows and communicates with underlying PLCs or automation devices. Supports static, hard-coded and dynamic routing strategies.

* **[Open WES](https://github.com/jingsewu/open-wes)**
  **WES / WCS-adjacent.**
  Customizable open-source Warehouse Execution System with task management, real-time monitoring, configurable rules, workflow orchestration and integration with warehouse automation technologies.

* **[WarehouseControlSystem](https://github.com/OlegLobakov/WarehouseControlSystem)**
  **Direct WCS — smaller project.**
  Open-source warehouse-control project associated with Microsoft Dynamics NAV. Useful as a reference implementation and starting point for warehouse-control concepts rather than as a direct replacement for enterprise WCS platforms.

* **[Great Blue / Open WMS](https://github.com/infiniteoo/wms)**
  **Open-source WMS.**
  A modern warehouse-management application built with Next.js, React/React Native and PostgreSQL. Useful as an open WMS layer that could be integrated with a separate WCS/MFC layer.

* **[Sentry WMS](https://github.com/hightower-systems/sentry-wms)**
  **Open-source WMS.**
  Warehouse-management system focused on barcode-driven receiving, put-away, picking, packing, shipping, cycle counting and inventory movement. Useful as a lightweight WMS foundation above an automation-control layer.

* **[ModernWMS](https://github.com/fjykTec/ModernWMS)**
  **Open-source WMS.**
  Cross-platform warehouse-management system covering inventory and warehouse operations. MIT-licensed and potentially useful for organizations building a modular WMS + WCS architecture.

* **[myTinyWMS](https://github.com/topics/warehouse-management-system)**
  **Open-source WMS.**
  Lightweight warehouse-management project aimed at inventory and warehouse operations. More suitable for smaller deployments or experimentation than industrial-scale WCS.

* **[ERPNext](https://github.com/frappe/erpnext)**
  **ERP/WMS foundation.**
  Open-source ERP platform with inventory, stock, warehouse and logistics functionality. It is not a WCS, but can serve as an upstream business/warehouse-management layer feeding an open WCS/MFC system.

* **[OpenBoxes](https://github.com/openboxes/openboxes)**
  **Open-source inventory/WMS foundation.**
  Inventory and logistics platform useful for stock, warehouse and supply-chain workflows. It does not replace a real-time industrial WCS but can provide higher-level inventory functions.

### Automation & Industrial-Control Building Blocks

* **[OpenPLC](https://github.com/thiagoralves/OpenPLC_v3)**
  **Industrial automation / PLC runtime.**
  Open-source PLC runtime implementing IEC 61131-3-oriented automation concepts. Useful when building the lower control layer of an experimental or open warehouse automation system.

* **[Eclipse 4diac](https://github.com/eclipse-4diac/4diac-ide)**
  **Industrial control framework.**
  Open-source framework for distributed industrial automation based on IEC 61499. Useful for developing distributed control logic around conveyors, machines and warehouse equipment.

* **[Apache PLC4X](https://github.com/apache/plc4x)**
  **PLC communication layer.**
  Open-source project providing a unified API for communicating with PLCs and industrial devices using multiple industrial protocols. Particularly useful for building vendor-neutral WCS/MFC equipment adapters.

* **[Node-RED](https://github.com/node-red/node-red)**
  **Industrial integration / workflow building block.**
  Flow-based programming environment that can connect PLCs, MQTT, databases, APIs, sensors and warehouse equipment. Useful for prototypes, integration gateways and event-driven automation.

* **[ThingsBoard](https://github.com/thingsboard/thingsboard)**
  **IoT / monitoring building block.**
  Open-source IoT platform for device management, telemetry, dashboards, rules and event processing. Can complement a WCS with equipment telemetry and operational monitoring.

* **[Grafana](https://github.com/grafana/grafana)**
  **Visualization / monitoring building block.**
  Open-source observability and dashboarding platform useful for WCS dashboards, equipment availability, throughput, alarms, OEE, MTBF/MTTR and material-flow analytics.

* **[InfluxDB](https://github.com/influxdata/influxdb)**
  **Time-series data layer.**
  Open-source time-series database suitable for storing PLC telemetry, equipment states, conveyor events, cycle times, alarms and WCS performance metrics.

* **[Apache Kafka](https://github.com/apache/kafka)**
  **Event backbone.**
  Distributed open-source event-streaming platform suitable for high-volume WCS events, equipment telemetry, transport events, order events and integration between WMS/WES/WCS services.

* **[Camunda](https://github.com/camunda/camunda)**
  **Workflow orchestration building block.**
  Workflow and process-orchestration platform that can be used for configurable warehouse processes and business/automation workflows.

* **[Flowable](https://github.com/flowable/flowable-engine)**
  **BPMN workflow engine.**
  Open-source workflow engine useful for modeling dynamic warehouse processes, transport workflows, exception handling and orchestration logic.

## Additional Strong Open-Source Options

The following projects are not complete enterprise WCS replacements but are valuable when constructing an **open warehouse-control ecosystem**:

* **[AS/RS Warehouse Simulators](https://github.com/topics/asrs)** for testing storage/retrieval algorithms, crane movement and warehouse-control strategies.
* **[Warehouse Simulation Projects](https://github.com/topics/warehouse-automation)** for testing conveyor, AGV, AMR and AS/RS concepts before deployment.
* **[Warehouse Management Systems](https://github.com/topics/warehouse-management-system)** for open-source inventory, receiving, put-away, picking and shipping functions.
* **[PLC Communication Libraries](https://github.com/apache/plc4x)** for connecting vendor-neutral WCS software to industrial controllers.
* **[Industrial IoT Platforms](https://github.com/thingsboard/thingsboard)** for telemetry, device management, alarms and equipment monitoring.
* **[Workflow Engines](https://github.com/flowable/flowable-engine)** for configurable warehouse and material-flow processes.
* **[Event Streaming Platforms](https://github.com/apache/kafka)** for real-time transport events and distributed WCS architectures.
* **[Observability Platforms](https://github.com/grafana/grafana)** for operational dashboards, equipment status, alarms and throughput analytics.
* **[Digital-Twin / Simulation Projects](https://github.com/topics/warehouse-simulation)** for validating material-flow logic before connecting physical automation.

## Recommended Open-Source WCS Stack

For organizations wanting to build a **vendor-neutral open-source alternative to commercial WCS platforms such as SynQ, Dematic WCS, Körber WCS, WAMAS or KiSoft**, a practical architecture could combine:

**WMS / ERP**

`ERPNext / OpenBoxes / OpenWMS.org`

↓

**WES / Orchestration**

`Open WES / Flowable / Camunda`

↓

**WCS / Material Flow Control**

`openWCS / OpenWMS MFC`

↓

**Integration & Event Layer**

`Apache Kafka / MQTT / Node-RED`

↓

**Industrial Communication**

`Apache PLC4X / OPC UA / Modbus / vendor-specific adapters`

↓

**PLC / Machine Control**

`OpenPLC / Eclipse 4diac / industrial PLCs`

↓

**Physical Automation**

`Conveyors / Sorters / AS/RS / Shuttles / AMRs / AGVs / Pick-to-Light / Robots`

**Monitoring & Analytics**

`Grafana + InfluxDB + ThingsBoard`

This architecture allows the **WMS, WES, WCS, MFC and PLC layers to remain independently replaceable**, reducing dependence on a single automation vendor.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, GitHub/official link, 1–2 sentence description, and whether it is **WCS, MFC, WES, WMS or an automation building block**.
4. Prefer projects with an active repository, clear license and usable documentation.
5. Clearly distinguish between a **complete WCS** and a **component that can be used to build one**.
6. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

* This is a **community-curated** list — not exhaustive and not an endorsement.
* Commercial warehouse-control products are often deployed as part of complete automation projects rather than as standalone SaaS products.
* **Open-source WCS software is considerably less mature and less numerous than open-source WMS software.**
* A WMS, WES, MFC and WCS are different layers, although commercial products increasingly combine several of these functions.
* Industrial warehouse automation requires appropriate safety systems, PLC engineering, cybersecurity, redundancy, testing, commissioning and operational validation.
* Open-source software should not be connected directly to production-critical machinery without appropriate engineering, safety and fail-safe controls.
* Always verify project activity, license terms, protocol support and production readiness before selecting an open-source component.

---

**Made for warehouse operators, system integrators, automation engineers, logistics technologists, developers, researchers, and companies building open intralogistics platforms.**
Let's make warehouse control more **open, vendor-neutral, interoperable, observable, and automation-ready**.

