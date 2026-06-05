# 🗺️ Canadian Merchandise Trade Flow — HS6

An interactive trade flow visualisation tool for exploring Canada's international merchandise trade economy. Built on Statistics Canada's CIMT dataset, this app maps export and import relationships at the HS6 commodity level — by product, province, and partner country — giving researchers, analysts, and policymakers a clear picture of how Canada trades with the world.

---

## 📌 Overview

This tool is designed as a **research and exploration platform** for understanding Canada's trade economy. Rather than presenting a fixed dashboard, it lets you slice the data the way you need it — by commodity, province, trade direction, time period, and trading partner — and see the relationships visualised as a chord diagram with proportional arc thickness.

**Data source:** Statistics Canada — Canadian International Merchandise Trade (CIMT)
**Coverage:** 1990 to 2026 | All Canadian provinces | 200+ partner countries | HS6 commodity level

---

## 🔍 What It Does

- **Trade flow mapping** — visualises the share of exports and imports between Canada and its partner countries as a chord diagram, where arc thickness represents trade volume on a log scale
- **HS6 commodity filtering** — drill down from broad trade sections to specific HS6 commodity headings to understand what Canada is trading and with whom
- **Provincial breakdown** — filter by province to understand regional trade patterns and how different parts of Canada engage with global markets
- **Partner country filtering** — isolate specific trading relationships to compare performance across partners
- **Time period selection** — explore trade patterns from 1990 to 2026 to track how Canada's trade economy has evolved
- **Top N filtering** — focus on the top 10, 20, or 50 trading partners to cut through noise and surface the most significant relationships
- **Trade direction toggle** — switch between exports, imports, or both to understand Canada's trade balance at a granular level

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| HTML / CSS / JavaScript | Core application |
| D3.js | Chord diagram and arc visualisation |
| Statistics Canada CIMT | Trade data source |
| Netlify | Deployment and hosting |

---

## 🌐 Live App

**[cimt-tradeflowmap.netlify.app](https://cimt-tradeflowmap.netlify.app/)**

---

## 📊 How to Use

1. **Select trade flow** — choose exports, imports, or both
2. **Set the time period** — use the from/to sliders to define your analysis window
3. **Filter by province** — select a specific province or view all of Canada
4. **Choose a commodity** — narrow down from section → chapter → heading → HS6 code
5. **Set Top N partners** — filter to the top 10, 20, or 50 trading partners for clarity
6. **Read the chord diagram** — thicker arcs indicate higher trade volume; darker shading indicates higher relative value on a log scale

---

## 📄 Data Source

Statistics Canada — Canadian International Merchandise Trade Database (CIMT)
[www.statcan.gc.ca](https://www.statcan.gc.ca)

---

*Developed by Farhaz Kolathoor — Data Analytics, SAIT*# Canadian-Merchandise-Trade-Flow-HS6
