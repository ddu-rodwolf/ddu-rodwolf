
<!--
**ddu-rodwolf/ddu-rodwolf** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## 📁 Personal Projects & Contributions  
*(Public, Private, or In Progress)*

---

### 🛰️ [**SIOS-InfraNOR-Ocean-Color**](https://github.com/ddu-rodwolf/SIOS-InfraNOR-Ocean-Color) ![Python](https://img.shields.io/badge/language-Python-blue)

  - Visualizes Arctic ocean color data (1 km resolution) to estimate **phytoplankton biomass** from **Chlorophyll-a (CHL-a)** observations around Svalbard.
  - Demonstrates how to use remote sensing datasets in **netCDF** format under Python for environmental analysis — including spatial plotting and biomass proxy calculations.

---

### 🔧 [**Python Object Explorer**](https://github.com/ddu-rodwolf/Python-Object-Explorer) ![Python](https://img.shields.io/badge/language-Python-blue)
A CLI-based utility for recursive structural analysis of Python objects.  
<details>
<summary>Click to expand project summary</summary>
&nbsp;

This project provides a structured, richly formatted exploration of Python objects, suitable for researchers and developers working with unfamiliar libraries or dynamically generated code.

**Key features:**  
- 🔍 Deep introspection of objects, classes, modules, and inheritance chains  
- 🧩 Recursively traverses attributes and `__mro__`  
- 🌈 Colored, indented, and grouped output via [rich](https://github.com/Textualize/rich)  
- 📚 Markdown export and optional file output for documentation or sharing  
- 🧪 Usable within notebooks or as a shell utility  

Originally developed as a personal research tool to complement RE workflows and ontology inspection tasks.

**Project status:** 🧪 Internal project, preparing for publication  
**Tech stack:** 🔬 Python, `rich`, reflection tools, RE-friendly CLI

</details>

---

### 📤 [**Global-Riverine-N₂O-Emissions Processor**](https://github.com/ddu-rodwolf/Global-Riverine-N2O-Emissions)  ![R](https://img.shields.io/badge/language-R-blue)
Data processing pipeline in **R** to handle geospatial raster datasets from the CMS project on global nitrous oxide emissions (1900–2016).

**Key components:**  
- Summarized annual raster stacks using two aggregation methods  
- Geospatial filtering and masking using shapefiles (`sf`, `raster`, `rgdal`)  
- Automated processing and visualization of GeoTIFF layers by stream order and emission category  
- Output comparison of cumulative estimates as maps and GeoTIFFs  

**Goal:** Gain hands-on experience with large raster datasets and automate N₂O emission analysis across decades.

---

### 🐦 Arctic-Tern-Predators-Model ![R](https://img.shields.io/badge/language-R-blue)
![Status](https://img.shields.io/badge/status-private-yellow)  
Contribution to a project led by **Kr. Kr.**, investigating predation risk to **Arctic tern nests** in relation to spatial nest placement, predator visitation, and interspecies interactions (e.g., with barnacle geese).
<details>
<summary>Click to expand project summary</summary>
&nbsp;

🧠 The analytical approach and model architecture were conceived and developed by **Kr. Kr.**  
🧩 Contribution was provided through a utility that trialed parameter combinations — combining loops and convergence controls — to identify stable model configurations and resolve convergence issues.

**Key methods:**  
- Survival analysis using **Cox Proportional Hazards Models** with time-dependent covariates  
- Predator visitation modeled with **Zero-inflated Binomial GLMs**  
- Model fitting via **Maximum Likelihood Estimation**, selection using **AIC**  
- R packages: `survival`, `survminer`, `optim`  

**Focus:** Investigating how predator pressure varies with goose behavior and proximity to Arctic tern colonies.

</details>

---

➡️ *More will be made public soon.* <!-- — feel free to [get in touch](mailto:your.email@example.com) for details. -->

