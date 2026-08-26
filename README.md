# Awesome-Occupancy-Intelligence-Platform

## Top Occupancy Intelligence Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Space Utilization, People Counting, Workplace Analytics, Privacy-Aware Presence Sensing & Real Estate Portfolio Insights*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Occupancy Intelligence**. These systems use sensors (radar, thermal, computer vision, Wi-Fi, etc.) and analytics to measure how spaces are used — supporting workplace design, energy optimization, cleaning schedules, and portfolio decisions.

**Examples** include Density, XY Sense, VergeSense, Butlr, Locatee, Occuspace, PointGrab, Infogrid, Openpath Presence, and Disruptive Technologies (the category leaders).

**Open-source emphasis**: Enterprise occupancy intelligence platforms are largely commercial. Open-source work exists mainly in research and home/DIY contexts — computer-vision seat detection, thermal presence sensors, Wi-Fi CSI sensing, and Home Assistant integrations. This section lists the most relevant open projects while noting the gap versus production workplace systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Density](https://www.density.io/)** | Radar-based people-counting and occupancy analytics platform with doorway and area sensors plus unified Atlas analytics. | Hardware from **$229/sensor** (or $149 starting); Software from **$2.50/desk/mo** or **$8.00/room/mo** (billed annually; $15/unit monthly) | **30-day pilot program** limited to 1–2 test floors / designated zones; no free forever plan |
| **[XY Sense](https://xysense.com/)** | Workplace occupancy and utilization platform using ceiling sensors to deliver space-level insights for real estate teams. | Software & sensor access starting at **~$0.05/sq. ft./month** (based on standard 16,000 sq. ft. office deployment) | **30-day structured pilot trial** limited to 1 floor / test area with live demo setup; no free forever plan |
| **[VergeSense](https://www.vergesense.com/)** | Occupancy intelligence platform combining computer-vision sensors with analytics, benchmarking, and AI space-planning. | Hardware starting from **~$149/sensor**; Software subscription starting from **~$0.03–$0.06/sq. ft./month** | **30–60 day proof-of-concept pilot** scoped to high-value test areas/rooms with free site survey; no free forever plan |
| **[Butlr](https://www.butlr.com/)** | Thermal (heat-based) occupancy sensing platform that is privacy-first (no cameras, no PII), wireless, and API-oriented. | Hardware from **$149/sensor** (Heatic 2+); Software/API subscription starting at **$2.50/desk/mo** to **$8.00/room/mo** (~$280/yr starter renewal) | **30-day Starter Kit evaluation trial** limited to 5–10 Heatic sensors and cloud dashboard/API access; no free forever plan |
| **[Locatee](https://www.locatee.com/)** | Workplace analytics platform focused on occupancy and utilization insights across office portfolios using network data. | Software starting from **~$0.02–$0.05/sq. ft./year** (or **~$1.50–$3.00/employee/year** based on Wi-Fi/LAN data ingest) | **30-day proof-of-concept pilot** limited to 1 building/floor baseline analysis; no free forever plan |
| **[Occuspace](https://www.occuspace.io/)** | Plug-and-play occupancy and space-utilization platform using wide-area Bluetooth/Wi-Fi signal monitors (Macro sensors). | Starts at **$600/year** for spaces under 5,000 sq. ft. (~$0.12–$0.20/sq. ft./year; 1 sensor covers 2,500–5,000 sq. ft.) | **30-day turnkey pilot kit program** limited to 1–2 Macro sensors covering test zone with ROI audit; no free forever plan |
| **[PointGrab](https://www.pointgrab.com/)** | AI-powered optical sensing and CogniPoint edge-computing sensors for desk and room occupancy tracking in commercial buildings. | Software license starting from **~$15.37/device/month** ($768.75/50 devices via marketplace) + hardware | **30–60 day CogniPoint 2 Flex pilot trial** limited to 1 pilot room / test installation; no free forever plan |
| **[Infogrid](https://www.infogrid.io/)** | Smart-building platform combining IoT occupancy, environmental, and cleaning efficiency sensors with AI analytics. | Starting from **~$0.03–$0.05/sq. ft./month** (or **~$100–$250/building/month** base tier for sensor suite) | **30-day guided pilot deployment** limited to select facility zones / 1 test floor; no free forever plan |
| **[Openpath / Avigilon Alta](https://www.openpath.com/)** | Cloud access control and presence/occupancy sensing ecosystem with mobile credentials and reader hardware. | Software starting from **$5.00/reader/month** (Basic tier, ~$60/door/year) + hardware starting **~$300/reader** | **30-day integrator pilot evaluation** limited to 1–2 test doors/entryways; no free forever plan |
| **[Disruptive Technologies](https://www.disruptive-technologies.com/)** | Miniature wireless sensor ecosystem (peel-and-stick desk & motion sensors) with DT Studio cloud integration. | **$999 one-time** for Sensor Starter Kit (includes Cloud Connector gateway + 10 sensor credits) + DT Studio at **~$2–$5/sensor/month** | **30-day DT Studio cloud trial** included with Starter Kit bundle (limited to 10 kit sensors & 1 gateway); no free forever plan |

## Open-Source GitHub Projects
- **[Computer-vision office seat occupancy projects](https://github.com/)**  
  Research and prototype systems using YOLO and similar models to detect people and chairs for real-time seat occupancy tracking and utilization analysis.

- **[RuView / Wi-Fi CSI spatial sensing](https://github.com/ruvnet/ruview)**  
  Open approach that turns commodity Wi-Fi (CSI) into presence, occupancy, and even vital-sign sensing without cameras — useful for privacy-sensitive experiments.

- **[Thermal camera occupancy for home automation](https://github.com/paxswill/r-u-still-there)**  
  Open-source thermal-camera presence detection that integrates with Home Assistant / MQTT, detecting stationary as well as moving people.

- **[Raspberry Pi and embedded occupancy sensors](https://github.com/)**  
  DIY room-occupancy systems based on Pi, motion, light, or simple presence sensors with APIs for status and notifications.

- **[Home Assistant occupancy and presence integrations](https://www.home-assistant.io/)**  
  Extensive open ecosystem of presence detection (Bluetooth, Wi-Fi, motion, mmWave, etc.) that can be adapted for small-scale workplace pilots.

- **[mmWave and radar open firmware / drivers](https://github.com/)**  
  Community drivers and examples for low-cost radar and mmWave modules used in anonymous occupancy sensing.

- **[Occupancy data pipelines and dashboards](https://github.com/)**  
  Open scripts that ingest sensor events into time-series databases (InfluxDB, Prometheus) and visualize utilization in Grafana.

- **[Privacy-preserving counting research code](https://github.com/)**  
  Academic implementations of anonymous people counting and density estimation that avoid storing identifiable imagery.

- **[MQTT / event-driven occupancy brokers](https://github.com/)**  
  Lightweight open brokers and schemas for publishing room or zone occupancy state to building systems.

- **[Space utilization analytics notebooks](https://github.com/)**  
  Open analysis notebooks for turning raw occupancy time series into peak, average, and under-utilized space metrics.

### Additional Strong Open-Source Options
- Combining low-cost mmWave or thermal sensors with Home Assistant or Node-RED for small offices.
- Using OpenTelemetry or simple MQTT + Grafana for occupancy telemetry pipelines.
- Open computer-vision pipelines (OpenCV, YOLO) for research or non-production pilots (with strong privacy controls).
- Public datasets and benchmarks for occupancy detection model training.
- Integration patterns between open sensor data and open IWMS / desk-booking tools.

**Frameworks for building custom systems**: For pilots or small sites, deploy privacy-aware sensors (thermal, mmWave, or carefully configured CV), publish events via MQTT, store time series in an open database, and visualize in Grafana or Metabase. For Wi-Fi-based experiments, explore CSI projects such as RuView. These stacks are useful for learning and limited deployments. Enterprise portfolio-scale occupancy intelligence — with validated accuracy, privacy reviews, multi-site analytics, and integrations into IWMS/BMS — remains the domain of commercial platforms (Density, VergeSense, Butlr, XY Sense, Locatee, etc.).

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Occupancy sensing can raise significant privacy and employee-relations issues. Camera-based systems in particular often require legal, works-council, and security review. Prefer anonymous sensing (thermal, radar, aggregated counts) where possible, minimize data retention, and be transparent with occupants. Open-source prototypes are not substitutes for production-grade, privacy-assessed commercial systems in most workplace settings.
- Always comply with applicable privacy, labor, and building regulations.

---
**Made for workplace, real-estate, and facilities teams seeking clearer insight into how space is actually used.**
Let's encourage privacy-aware, open approaches to occupancy data where they are appropriate.
