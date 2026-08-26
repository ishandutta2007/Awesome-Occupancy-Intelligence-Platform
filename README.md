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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Density](https://www.density.io/)**  
  Radar-based people-counting and occupancy analytics platform with doorway and area sensors plus a unified analytics layer (Atlas) for workplace and building automation use cases.

- **[XY Sense](https://xysense.com/)**  
  Workplace occupancy and utilization platform using ceiling sensors to deliver space-level insights for real estate and facilities teams.

- **[VergeSense](https://www.vergesense.com/)**  
  Occupancy intelligence platform combining computer-vision sensors with analytics, benchmarking, and AI-assisted space-planning recommendations.

- **[Butlr](https://www.butlr.com/)**  
  Thermal (heat-based) occupancy sensing platform that is privacy-first (no cameras, no PII), wireless, and API-oriented for integration into IWMS, BMS, and energy systems.

- **[Locatee](https://www.locatee.com/)**  
  Workplace analytics platform focused on occupancy, utilization, and employee experience insights across office portfolios.

- **[Occuspace](https://www.occuspace.io/)**  
  Occupancy and space-utilization solution aimed at understanding real-time and historical use of rooms and floors.

- **[PointGrab](https://www.pointgrab.com/)**  
  AI-powered occupancy and workplace sensing solutions for commercial buildings.

- **[Infogrid](https://www.infogrid.io/)**  
  Smart-building platform that includes occupancy and environmental sensing for facilities optimization.

- **[Openpath Presence / related access + occupancy](https://www.openpath.com/)**  
  Presence and access-related capabilities within broader workplace and security platforms.

- **[Disruptive Technologies](https://www.disruptive-technologies.com/)**  
  Wireless sensor ecosystem (including occupancy-related sensing) used in smart-building and workplace deployments.

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
