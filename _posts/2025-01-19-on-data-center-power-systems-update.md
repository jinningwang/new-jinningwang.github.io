---
layout: distill
title: On Data Center, a Power Systems Update
date: 2025-01-19 10:00:00
description: Data centers bring new challenges to power systems
tags: [news, power-systems, energy, data-center]
categories: power-systems-update
thumbnail:
featured: false
giscus_comments: true
bibliography: power-systems.bib
authors:
  - name: Jinning Wang
---

## Layout

<div style="text-align: ;left;">
  <img src="/assets/img/psupdate/data-center-layout.png" alt="Data Center Layout" style="width: 540px; height: auto;">
  <p><em>Data Center Layout by NERC in 2024(from <d-cite key="nerc2024datacenter"></d-cite>) </em></p>
</div>

## Load Size

Large volume of requests across the continent, concentrated in the mid-Atlantic, Upper Midwest, Texas and California, with size of 10s-100s of MW. <d-cite key="giraldez2024large"></d-cite>

## Concerns

Forecasting Considerations <d-cite key="giraldez2024large"></d-cite>:

- There is no formal forecasting model that is used today to forecast large loads, in particular data centers
- Data informing forecasting is obtained by utilities / ISOs directly from customers and developers seeking to interconnect
- No standardization in data center consumption requirements, interconnection queue, modeling, etc.

Large Data Center Loads – Key Considerations <d-cite key="shah2024interconnection"></d-cite>:

- Power Quality: Harmonics, Voltage fluctuations/flicker
- Transient Stability: Voltage recovery, frequency
- Small Signal Stability: Forced oscillations at low frequencies
- Resonance Stability: Exciting torsional modes of nearby units
- Other: Ramping rate, ride-through requirements
