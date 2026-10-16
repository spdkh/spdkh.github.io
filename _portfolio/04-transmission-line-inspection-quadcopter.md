---
title: "Autonomous Quad-copter with Auto-Charging for Transmission-Line Inspection"
excerpt: "Team project (six people) to build a quad-copter that inspects transmission lines and recharges on its own. My subproject, and B.Sc. thesis (A+): on-board autonomous landing on a marker pad using OpenCV and ArUco markers on a Raspberry Pi."
collection: portfolio
group: mine
order: 8
period: "2016 – 2018"
role: "Team member · team of 6 · autonomous-landing subproject (B.Sc. thesis)"
---

**Control of Multi-Vehicle Systems (CMVS) Lab, Amirkabir University of Technology · 2016–2018.**
**Role:** Member of a six-person team. I developed the autonomous-landing subproject as my B.Sc. thesis. Advisor: Dr. F. Abdollahi.

The project goal was a quad-copter that can inspect power transmission lines and return to a charging pad by itself, so inspections are not limited by battery life or a pilot on site.

**My subproject: indoor autonomous landing with video processing (B.Sc. thesis, graded A+)**

Closed-loop landing of the quad-copter on a fiducial-marked pad, entirely on-board, with no external positioning system. Landing precisely on the pad is what lets the drone dock and recharge without a pilot.

- **Vision:** Raspberry Pi running OpenCV with **ArUco markers** to estimate the landing pad's pose in the camera frame (Python and C++).
- **Control:** independent **PID controllers** for each degree of freedom of the airframe.
- **Toolchain:** bridged the C++ vision code into MATLAB / Simulink for control synthesis, offline analysis, and tuning.

**Stack:** Python, C++, OpenCV, ArUco, Raspberry Pi, MATLAB / Simulink.

**Also in the CMVS Lab:** collaborated on the full implementation of a custom **VTOL drone** design.
