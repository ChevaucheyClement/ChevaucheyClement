# Hi, I’m Clément Chevauchey

Electrical Engineering student focusing on **power systems analysis**, **measurement & instrumentation** and **fault detection**.  
I try to turn messy engineering problems into reproducible, readable pipelines.
 
 You can explore my academic portfolio:
  <a href="https://ChevaucheyClement.github.io/academic-portfolio/" target="_blank" rel="noopener noreferrer">
    <img alt="Portfolio Page"
         src="https://img.shields.io/badge/Academic_Portfolio_Website-blue">
  </a>
   or its repository:
  <a href="https://github.com/ChevaucheyClement/academic-portfolio" target="_blank" rel="noopener noreferrer">
    <img alt="Portfolio Repo"
         src="https://img.shields.io/badge/GitHub-Repo-white?logo=github">

---

## Selected projects

- **MV Feeder Study (pandapower)** - baseline load flow/short circuit (IEC 60909), OLTC analysis, shunt capacitor sweep, targeted rebalancing, automated scenario ranking.  
  
- **PlantWeb - CS50 Final Project** 
  <a href="https://ChevaucheyClement.github.io/Final-Project-CS50/" target="_blank" rel="noopener noreferrer">
    <img alt="Project Page"
         src="https://img.shields.io/badge/Page-Project-1f77b4?style=flat&labelColor=555">
  </a>
  <a href="https://final-project-cs50.onrender.com/" target="_blank" rel="noopener noreferrer">
    <img alt="Live Demo"
         src="https://img.shields.io/badge/Live-Demo-f97316?style=flat&labelColor=555">
  </a>
  <a href="https://github.com/ChevaucheyClement/Final-Project-CS50/releases/latest" target="_blank" rel="noopener noreferrer">
    <img alt="Latest Release"
         src="https://img.shields.io/github/v/release/ChevaucheyClement/Final-Project-CS50?display_name=tag&color=10b981&label=Release&style=flat&labelColor=555">
  </a>
  Track your houseplants, store photos, and never miss a watering. Built with **Python**, **Flask** and **SQLite** for CS50.
  - Add plants with either an uploaded image or a stock image from `static/stock/`
  - Images are resized server-side to fast thumbnails; album images are **lazy-loaded** with fixed dimensions
  - Due-date logic: next watering is computed from the last watering or the added date
  - Auth (register/login) with hashed passwords and server-side sessions
  - **CSRF protection** on all POST forms
  - Clean Bootstrap UI with empty state and due-status badges

## Selected university work
- **Electronics II (7 labs)** - Rectifiers, clippers, BJT single/cascade, op-amp labs validated against specs.  
  _Stack_: LTspice/Proteus, biasing & small-signal, gain/bandwidth, measurement planning.

- **Electrical Measurements (7 labs)** - Instrument class, R/Z, single/three-phase power (3A/3V, wattmeter/Aron), Type A/B uncertainty.  
  _Stack_: metrology, phasors/PF, Python analysis.

- **Logic systems — Traffic Lights (Proteus)** - Moore FSM + timing divider, debounced, deterministic phase timing.

- **Thermo cycle studies** - Rankine (superheat vs no superheat; ideal vs real), and Otto/Diesel/Dual (η_th vs compression ratio).

---

## How I structure projects

I try to make my projects **repeatable** and consistently **organised**:

```
project/
├─ report.pdf        # final report in English (when available)
├─ es/               # final report in Spanish
├─ data/             # CSVs, raw/processed data
├─ figures/          # plots/diagrams used in the report
├─ code/             # scripts/notebooks
└─ README.md         # short context + how-to-run
```

---

## Toolbox

- **Power systems**: pandapower (LF, IEC 60909 SC), scenario design, Volt-VAR & curtailment concepts  
- **Electronics & Measurements**: LTspice/Proteus, DMM/oscilloscope workflows, Type A/B uncertainty  
- **Data & visualisation**: Python, pandas, matplotlib  
- **Documentation & site**: Markdown, LaTeX snippets, Jekyll/Liquid
