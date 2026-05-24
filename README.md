# 🏙️ Skylines Utilities Calc

A free, single-file web tool for **Cities: Skylines** players to plan, compare, and optimise city utility layouts — no server, no install, no account required.

🔗 **Live app:** [https://basicwombat.github.io/skylines-utilities-calc/](https://basicwombat.github.io/skylines-utilities-calc/)

---

## Features

- **Multi-utility build planner** — add any combination of utilities to a single build (e.g. 1× Nuclear Plant + 3× Wind Turbines + 2× Water Treatment Plants) and see combined totals instantly
- **Cost & efficiency calculator** — build cost, monthly upkeep, output-to-cost efficiency ratio, and population coverage per category
- **Pollution impact** — air, water, noise, and ground pollution displayed per build with an overall safety rating
- **Budget slider** — simulate running utilities at 50–150% funding to see the effect on output and costs
- **Compare all tab** — side-by-side cards for every power plant and water facility with colour-coded pollution tiers
- **Data reference tab** — full sortable, filterable table of all 29 buildings across every utility category
- **Save builds** — save named build configurations to local storage and revisit them later
- **GitHub Pages ready** — entirely self-contained in a single HTML file, no backend required

---

## Utility Categories Covered

| Category | Buildings |
|---|---|
| ⚡ Power Plants | Coal, Oil, Wind Turbine, Large Wind Turbine, Solar, Nuclear, Fusion, Geothermal |
| 💧 Water / Sewage | Water Tower, Pumping Station, Large Water Pump, Sewage Outlet, Drain Pipe, Treatment Plant |
| 🗑️ Waste Management | Landfill, Incineration Plant, Recycling Centre, Waste Transfer Facility |
| 🏥 Healthcare | Medical Clinic, Hospital, Helicopter Depot, Sauna |
| 🎓 Education | Elementary School, High School, University, Library |
| 🚒 Fire Services | Fire Station, Fire Helicopter Depot |
| 👮 Police | Police Station, Police Helicopter Depot |

---

## How to Use

1. Go to the **Calculator** tab
2. Select a utility **category** and **building type**
3. Set the **quantity** and **budget %**
4. Enter your approximate **city population**
5. Click **+ Add to Build** — repeat for as many different utilities as you need
6. View combined costs, output, coverage, and pollution in the results panel
7. Optionally **💾 Save Build** to store your layout for later

---

## Running Locally

No build step needed. Just clone the repo and open the file in your browser:

```bash
git clone https://github.com/BasicWombat/skylines-utilities-calc.git
cd skylines-utilities-calc
open index.html
```

---

## Tech Stack

- Vanilla HTML, CSS, and JavaScript — zero dependencies, zero frameworks
- Google Fonts (Rajdhani, Share Tech Mono, Exo 2) loaded via CDN
- `localStorage` for saving builds between sessions
- Single file — the entire app is `index.html`

---

## License

MIT © [BasicWombat](https://github.com/BasicWombat)

Game data (building names, costs, statistics) is based on **Cities: Skylines** by Colossal Order / Paradox Interactive. This tool is unofficial and is not affiliated with or endorsed by the game developers.

---

## Built With

Built using [Claude AI](https://claude.ai) by Anthropic.
