---
title: Demand Forecasting for Staffing Decisions
date: 2025-02-10
links:
  - type: pdf
    url: "/projects/demand-staffing-optimizer/Report.pdf"
    name: report
  - type: site
    url: "https://github.com/yiihann/demand-staffing-optimizer"
tags: []
---

How should a service team adjust headcount when demand shifts, new hires take a month to ramp up, and requests can stay in the backlog for up to 60 days? I used Prophet to forecast demand and a genetic algorithm to compare hiring and staffing plans by projected net profit, accounting for labor costs and revenue lost to unmet demand.

The system guides the user from raw event data through **aggregation and MA7 smoothing**, **Prophet-based demand forecasts** (with optional per-region calibration and grid search), and **GA-driven staffing plans** that balance revenue, salary, hiring/firing costs, and lost revenue from unmet demand—enabling scenario-based capacity planning with a 60-day backlog and 1-month agent ramp.

<!--more-->
