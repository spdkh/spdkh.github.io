---
title: "Anaita: UAV-Based Visual Stream Assessment"
excerpt: "Ph.D. research program on the StreamEye drone platform (RGB + LiDAR, Jetson edge deployment): benchmarking 40+ vision foundation models (anait-Bench), water-mask segmentation and litter detection (anait-Eye), and a UAV waterway dataset (anait-Shotes). The StreamEye multi-UAS proposal took 2nd place in the SICK LiDAR Challenge (USA & Canada)."
collection: portfolio
group: mine
order: 1
period: "2025 – present"
role: "Lead researcher · Ph.D. dissertation"
---

**Ph.D. dissertation · Remote Sensing Lab (RSL), University of Memphis · 2025 – present.**
**Role:** Lead researcher and first author. Advisor: Dr. E. Jacobs.

Stream assessments are usually done on foot, which is slow and limited in coverage. **Anaita** uses drones to assess streams visually, covering both drone navigation and image processing: mapping where the water is, finding litter, and producing data that environmental teams can act on.

**Platform: StreamEye.** All work runs on the StreamEye drone platform, with an RGB camera and LiDAR, and on-board edge deployment on NVIDIA Jetson.

**Subprojects**
- **anait-Bench:** an open-source framework that benchmarks **40+ promptable and open-vocabulary vision foundation models**, alone and as detector-segmenter pipelines, on UAV imagery of waterways. Models are tested under text, box, and no-prompt conditions, with uninformative-prompt controls. It measures accuracy and latency on a workstation and verifies the most promising configurations on an **NVIDIA Jetson Orin NX**.
- **anait-Eye:** stream-assessment image processing: **water-mask segmentation and litter detection**.
- **anait-Shotes:** the UAV waterway dataset generated, collected, and annotated with anait-Eye.

**Recognition:** our StreamEye proposal for multi-UAS visual stream assessment placed
[**2nd in the SICK LiDAR Challenge**](https://www.memphis.edu/herff/news/herff_students_place_lidar_competition.php) across the USA and Canada (2025–26).

**Stack:** Python (Ultralytics, PyTorch, OpenCV), promptable / open-vocabulary detection and segmentation, NVIDIA Jetson Orin NX, RGB + LiDAR data collection, embedded systems.

**Outputs**
- SPIE Defense + Security 2026: *Vision-Based Uncrewed Aerial System for Real-Time Stream Assessment and Environmental Monitoring*.
- Journal papers in preparation: *Anait-Bench* and *Anait-Eye* (target: IEEE TGRS), and *StreamEye*.

Earlier in my Ph.D. I worked on UAV navigation and geo-localization: see [TerrAInav](/portfolio/02-uav-vision-navigation/).
