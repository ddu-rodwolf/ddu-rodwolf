
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
Hands-on demonstration for quick exploration and visualization of **NetCDF-based ocean color data** from the SIOS-InfraNor remote sensing component.

<details>
<summary>Click to expand project summary</summary>
&nbsp;

🧭 This project showcases how to explore and analyze remote sensing data stored in **NetCDF4** format using Python, with a focus on **phytoplankton biomass estimation** via **Chlorophyll-a (CHL-a)** concentrations.  
📡 The dataset used is the **first remote sensing product released** by [NERSC](https://nersc.no/) under the **SIOS-InfraNor** initiative — a distributed research infrastructure for long-term environmental monitoring in Svalbard.  
📈 The script includes spatial plotting and a basic biomass estimation using a user-defined mixed layer depth (MLD), meant for exploratory and illustrative purposes.

**Key components:**  
- Loading remote sensing CHL-a data via NetCDF4  
- Plotting spatial distribution with masked invalid data  
- Estimating biomass using CHL-a × MLD × grid cell area  
- Minimal setup, reusable for similar Arctic datasets  

**Focus:** Fast prototyping, accessibility of Arctic Earth Observation data, and educational outreach.

</details>

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

### 🦊 [**Firefox Session Preview & Restore**](https://github.com/ddu-rodwolf/Firefox-Session-Preview-Restore) ![Bash](https://img.shields.io/badge/language-Bash-green) ![Python](https://img.shields.io/badge/language-Python-blue)
A terminal-based toolkit for safely previewing, inspecting and restoring Firefox browser sessions.  
<details>
<summary>Click to expand project summary</summary>
&nbsp;

This project provides a color-coded, structured preview of saved Firefox sessions so you can inspect windows, tab groups and URLs before restoring them. It is aimed at power users who want fine-grained control over session recovery and backup workflows.

**Key features:**  
- 📂 **Session selection** by profile and date (supports `_pre-restore` snapshots)  
- 🖥 **Interactive preview** of windows, groups and tabs with 256-color ANSI highlighting and configurable palettes  
- 🧩 `jq`-powered structured parsing via `jq_preview_with_groups.jq` for robust extraction of windows/groups/tabs  
- 🐍 **Python decoder** `decode_jsonlz4.py` to safely decompress Firefox `*.jsonlz4` session files (uses `lz4.block`)  
- 💾 **Safe restore flow** — backs up the current session before restoring and offers confirm prompts  
- 📄 **Markdown export** option for saved previews (good for documentation or audit trails)  
- 🛠 Modular scripts: `preview_firefox_session.sh`, `restore_firefox_session.sh`, and supportive helpers

**Implementation detail — decoder:**  
The included Python utility decodes Firefox LZ4-compressed session files to plain JSON so `jq` can parse them. It handles the Firefox `mozLz40\0` header, decompresses with `lz4.block`, and prints UTF‑8 JSON to stdout. It also installs a SIGPIPE handler so piping into other tools is safe.

</details>

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

