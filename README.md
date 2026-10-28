# Solar Resource Mapping for Green Hydrogen 
# Production Potential in Northern Nigeria

**Author:** Elijah J. Monte  
**Data Source:** NASA POWER (2015–2023)  
**Tool:** Python (requests, pandas, matplotlib)  
**Date:** October 2026

---

## Overview
This project uses NASA satellite-derived solar 
irradiance and temperature data to map solar 
energy resources across 7 key locations in 
Northern Nigeria, and estimates their potential 
for green hydrogen production via solar-powered 
electrolysis.

This work is a direct extension of the **Hybrid 
Adaptive Climate Infrastructure Framework (HACIF)**
— an ongoing research initiative exploring 
sustainable energy infrastructure for Sub-Saharan 
Africa.

---

## Locations Analysed
- Sokoto, Kano, Maiduguri, Kaduna, 
  Zaria, Dutse, Gusau

---

## Data
- **Parameters:** Solar Irradiance 
  (kWh/m²/day), Temperature (°C)
- **Period:** 2015–2023 (monthly)
- **Records:** 819 data points
- **API:** NASA POWER Climatology API

---

## Key Findings
- **Best location:** Sokoto — 
  5.98 kWh/m²/day average solar irradiance
- **Peak month:** April (6.6 kWh/m²/day)
- **Lowest period:** July–August (rainy season)
- **Hydrogen potential:** Up to 16.73 kg H₂/day 
  per 1,000 m² solar field (Sokoto)

---

## Assumptions (Hydrogen Calculation)
| Parameter | Value |
|---|---|
| Solar panel area | 1,000 m² |
| Panel efficiency | 20% |
| Electrolyser efficiency | 70% |
| Energy per kg H₂ | 50 kWh |

---

## Output Files
- `solar_data.csv` — Full NASA POWER dataset
- `solar_chart.png` — Average solar irradiance 
   by location
- `sokoto_monthly.png` — Monthly solar trend 
   for Sokoto
- `hydrogen_potential.png` — Estimated H₂ 
   production potential by location

---

## Connection to HACIF Research
This project strengthens the HACIF framework 
by providing location-specific solar resource 
evidence for green hydrogen production sites 
in Northern Nigeria, supporting evidence-based 
infrastructure planning for clean energy 
transition in Sub-Saharan Africa.
