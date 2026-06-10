# Global Air Pollution Evolution (PM2.5): 1990–2020

An interactive data visualization and analytics dashboard project created by students at the **Bucharest University of Economic Studies (ASE)**. This project leverages historical environmental records to analyze global trends, regional disparities, and specific national updates in air quality over a 30-year span.

---

## 👥 Project Contributors (Students)
* Constantin Teodor-Vasile
* Erhan Teodora-Miruna
* Nițu Vlad-Cristian

---

## 📌 Context & Importance
* **Public Health Crisis:** Air pollution stands as one of the most severe environmental and public health hazards globally. Fine particulate matter (PM2.5) deeply affects populations, showing strong statistical links to severe respiratory and cardiovascular conditions.
* **Core Objective:** Map, visualize, and track the evolution of global PM2.5 concentrations from 1990 to 2020 to highlight regional progress, identify persistent pollution hotspots, and uncover long-term global air quality trends.
* **Target Audience:** Public health analysts, environmental researchers, policy decision-makers, and citizens interested in ecological protection.

---

## ❓ Key Analytical Questions Addressed
1. How has global air pollution evolved over time across different decades?
2. Are there statistically significant variations in pollution levels between distinct continents or geographical regions?
3. Which countries or zones remain the most affected by hazardous PM2.5 concentrations?

---

## 📊 Dataset Specifications
* **Metric Focused:** PM2.5 annual mean concentration ($\mu g/m^3$).
* **Temporal Scope:** 1990 to 2020 (30 Years of historical coverage).
* **Granularity:** Country-level data grouped dynamically into global and continental macro-regions.

---

## 🖼️ Dashboard Architecture & Visual Elements
The tracking interface is organized into modular interactive structures designed for progressive disclosure:

### 1. High-Level Metrics (BANs)
* **Big Angry Numbers (BAN):** Dedicated indicators showing global average, minimum, and maximum pollution figures at a glance.

### 2. Analytical & Spatial Charts
* **Global Continental Map:** A geospatial visualization showing the geographical distribution of air pollution across world countries.
* **Temporal Line Chart:** Highlights the historical relationship between the timeline (years) and global average particulate concentrations.
* **Continental Bar Chart:** A segmented breakdown comparing internal differences within countries grouped by their respective continents.
* **Extreme Outliers Tracker (Top 15):** Bar charts identifying the top 15 most polluted countries alongside the top 15 least polluted countries globally.

---

## 🎨 Visualization & UX Principles Applied
The analytical dashboard was developed under the philosophy of **"Less is More"** using strict professional design benchmarks:
* **Clarity First:** Implementation of simple, intuitive charts with distinct titles, clearly labeled axes, and explicit units of measurement ($\mu g/m^3$).
* **Color Coding:** Integrated heatmaps and strategic color gradients that guide user attention directly to critical risk values.
* **Visual Contrast:** High-contrast color palette (dark text elements over clean white backgrounds) to avoid cognitive overload.
* **Progressive Disclosure:** Information is revealed contextually and dynamically through custom Tableau actions, keeping the initial viewport clean and scannable.

---

## 📈 Key Analytical Conclusions (1990–2020)
* **Persistent Hotspots:** Countries like **Qatar** and **Niger** continuously ranked among the top most polluted nations globally throughout the entire 30-year observation span.
* **Consistent Baselines:** Scandinavian nations, North America, Australia, and sectors of Latin America successfully maintained low, stable PM2.5 baselines.
* **European Transition:** Multiple European nations achieved substantial progress, actively reducing their ambient air pollution from historical high alerts to safer, controlled levels.
* **Significant Improvements:** **Peru** and **Bolivia** displayed strong downward trajectories, successfully reducing average PM2.5 concentrations from peak levels around ~80 $\mu g/m^3$ down to approximately ~22 $\mu g/m^3$.
* **The Asian Context:** Most Asian territories displayed an encouraging downward or plateauing pollution curve up until the year 2010, which was followed by a sharp, abrupt increase in particulate concentration through the final decade of the study.
