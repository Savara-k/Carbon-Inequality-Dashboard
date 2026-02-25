
# Carbon Inequality Dashboard — Global CO₂ Emissions & Climate Risk

An interactive data visualization group project exploring the intersection of carbon emissions, economic inequality, and climate vulnerability across the globe.

## Overview
The Carbon Inequality Dashboard (Global-Pulse Atlas) is an interactive analytical suite designed to reveal the dual crisis of socio-economic inequality and environmental risk. By integrating global datasets on CO₂ emissions, GDP, inequality (GINI), population, and climate vulnerability, the dashboard highlights regions that contribute the least to climate change yet face the greatest risks.
This project was developed as part of a Fall 2025 Data Visualization initiative, emphasizing storytelling through data and decision-support insights for policy, ESG strategy, and climate research.

---

## Purpose
Explore global carbon inequality patterns
Compare emissions with economic development and vulnerability
Identify regions most at risk despite low emissions
Demonstrate how interactive visualization supports policy decisions


---
## Key Features
* Interactive global dashboard
* Five linked visualizations built with Altair
* Bubble charts showing emissions vs inequality
* Heatmaps highlighting regional disparities
* Bar charts comparing country metrics
* Interactive world maps with temporal exploration
* Time slider to visualize changes from 1990–2020

---

## Analytical Insights
The dashboard reveals critical climate justice patterns:
* High-income regions produce the majority of emissions
* Low-emission regions often face higher climate vulnerability
* Socio-economic inequality amplifies environmental risk
* “Hotspots” exist where inequality and emissions intersect
These findings support ESG planning, climate policy, and resource allocation decisions.

---

## Technical Approach
## Data Sources
* Our World in Data — CO₂ emissions & population
* World Bank — GDP & GINI inequality index
* ND-GAIN — Climate vulnerability metrics
* Kaggle — Geospatial datasets

---

## Data Engineering

Real-world datasets required significant preprocessing:
* Temporal imputation using Forward-Fill and Back-Fill
* Multi-source dataset merging
* Standardization of country names across datasets
* Cleaning missing and inconsistent records
  
---

## Visualization Design (Altair)
A layered geospatial approach was used:
Ocean sphere base map
Latitude/longitude graticules
Population choropleth background
Static continent labels
Dynamic emission bubbles
Bubble size → CO₂ emissions
Bubble color → Inequality (GINI)
Interactive controls allow users to explore patterns over time.

---

## Tech Stack
* Visualization: Altair 5
* Data Processing: Python, Pandas
* Geospatial: TopoJSON, EqualEarth projection
* Environment: Python 3.x, KaggleHub


---

##  Usability Testing
User feedback was incorporated to improve:
* Color scales for accessibility
* Legend clarity
* Layout readability
* Interaction design

---

## Impact & Applications
This dashboard serves as a prototype for:
* Climate policy analysis
* ESG and CSR reporting tools
* Sustainability planning
* Educational climate data storytelling
By making complex global patterns intuitive, the project demonstrates how data visualization can support equitable climate action.
