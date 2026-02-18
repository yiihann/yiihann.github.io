---
title: Demand-Staffing Optimizer
date: 2025-02-10
links:
  - type: pdf
    url: "/projects/demand-staffing-optimizer/Report.pdf"
    name: report
  - type: site
    url: "https://github.com/yiihann/demand-staffing-optimizer"
tags: []
---

A **demand forecasting and dynamic staffing optimization pipeline** for capacity planning, combining **time-series forecasting** (7-day moving average + Prophet) with a **Genetic Algorithm (GA)** to produce hire/fire decisions that maximize net profit under real-world constraints: 60-day service backlog, 1-month agent ramp-up, and labor efficiency.

The system guides the user from raw event data through **aggregation and MA7 smoothing**, **Prophet-based demand forecasts** (with optional per-region calibration and grid search), and **GA-driven staffing plans** that balance revenue, salary, hiring/firing costs, and lost revenue from unmet demand—enabling scenario-based capacity planning with a 60-day backlog and 1-month agent ramp.

<!--more-->
