<p align="center">
  <img src="screenshots/01_home_fii_dii_date.png" alt="FII & DII Data Dashboard" width="100%">
</p>

<h1 align="center">📊 FII & DII Data — Institutional Money Matrix</h1>

<p align="center">
  <strong>Live Dashboard for tracking Foreign Institutional Investor (FPI/FII) and Domestic Institutional Investor (DII) flows in Indian equity markets.</strong>
</p>

<p align="center">
  <a href="https://fii-diidata.mrchartist.com/"><img src="https://img.shields.io/badge/🌐_Live_Dashboard-Visit-2563EB?style=for-the-badge" alt="Live Dashboard"></a>
  <a href="https://twitter.com/mr_chartist"><img src="https://img.shields.io/badge/𝕏_Twitter-@mr__chartist-000000?style=for-the-badge&logo=x" alt="Twitter"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-059669?style=for-the-badge" alt="MIT License"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-2.0.0-blue?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/node-%3E%3D18-brightgreen?style=flat-square&logo=node.js" alt="Node.js">
  <img src="https://img.shields.io/badge/express-4.19-black?style=flat-square&logo=express" alt="Express">
  <img src="https://img.shields.io/badge/chart.js-v3-ff6384?style=flat-square" alt="Chart.js">
  <img src="https://img.shields.io/badge/PWA-installable-5A0FC8?style=flat-square" alt="PWA">
  <img src="https://img.shields.io/badge/SEO-optimized-E34F26?style=flat-square" alt="SEO">
</p>

---

## 📈 GitHub Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=MrChartist&repo=fii-dii-data&theme=react-dark&hide_border=true&area=true&custom_title=FII%20DII%20Data%20—%20Commit%20Activity" alt="GitHub Activity Graph" width="100%">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MrChartist&show_icons=true&theme=react&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" height="165">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MrChartist&theme=react&hide_border=true" alt="GitHub Streak" height="165">
</p>

---

## ✨ Features at a Glance

<table>
  <tr>
    <td width="50%">
      <h3>⚡ Real-Time Flows</h3>
      Latest FII/DII net buy/sell with flow strength meter, streak trackers, and 45-day GitHub-style heatmaps
    </td>
    <td width="50%">
      <h3>📊 FPI Macro Analytics</h3>
      Daily, monthly, quarterly & yearly FPI investment trends from NSDL (2005–present)
    </td>
  </tr>
  <tr>
    <td>
      <h3>🌐 Sector Allocation</h3>
      Fortnightly NSDL FPI data with gradient sparklines and interactive spaghetti chart
    </td>
    <td>
      <h3>🤿 Deep Dive Module</h3>
      Country-wise AUC donut chart, trade-wise ISIN-mapped flows, debt utilisation & ODI/PN
    </td>
  </tr>
  <tr>
    <td>
      <h3>🎲 Live F&O Derivatives</h3>
      Participant-wise Open Interest — FII/DII futures, calls & puts with sentiment engine
    </td>
    <td>
      <h3>🗄️ Historical Databases</h3>
      Daily, Weekly, Monthly & Annual archives with magnitude bars, filters & CSV export
    </td>
  </tr>
  <tr>
    <td>
      <h3>📑 Data Source Citations</h3>
      Every tab has clickable source badges linking to official NSE/NSDL/SEBI pages
    </td>
    <td>
      <h3>🌙 Dark Mode + PWA</h3>
      OLED black dark theme, full-page export, Post to 𝕏, installable PWA with offline support
    </td>
  </tr>
</table>

---

## 📸 Dashboard Preview

<table>
  <tr>
    <td align="center"><img src="screenshots/01_home_fii_dii_date.png" width="100%"><br><b>⚡ Live NSE</b></td>
    <td align="center"><img src="screenshots/05_sectors.png" width="100%"><br><b>🌐 Sectors</b></td>
  </tr>
  <tr>
    <td align="center"><img src="screenshots/02_fno_positions.png" width="100%"><br><b>🎲 F&O Derivatives</b></td>
    <td align="center"><img src="screenshots/03_databases_matrices.png" width="100%"><br><b>🗄️ Databases</b></td>
  </tr>
  <tr>
    <td align="center"><img src="screenshots/04_history.png" width="100%"><br><b>📊 FPI Macro</b></td>
    <td align="center"><img src="screenshots/06_docs.png" width="100%"><br><b>📖 Docs</b></td>
  </tr>
</table>

---

## 🗺️ Tab-by-Tab Walkthrough

<details>
<summary><b>⚡ Tab 1 — Live NSE (Home)</b></summary>

The default landing view covering immediately actionable institutional activity.
- **Hero Card**: FII/FPI Net vs DII Net with visual aggression borders
- **Flow Strength Meter**: `FII_NET / (|FII_NET| + |DII_NET|) × 100` — split of FII aggression vs DII support
- **Streak Trackers**: Consecutive buying/selling days with cumulative capital velocity
- **45-Day Heatmaps**: GitHub-style concentration matrices — FII sell-off depth & DII absorption density
- **Quick Stats**: 5-Year cumulative flows, SIP run-rate (₹26,500 Cr/mo), FII NSE500 ownership %
- **Source**: `📡 NSE TRDREQ Daily Reports`
</details>

<details>
<summary><b>📊 Tab 2 — FPI Macro</b></summary>

Macro-level historical trajectories and systemic liquidity shifts sourced from NSDL.
- **FPI Daily Summary**: Latest equity, debt, and hybrid net investment with summary cards
- **Institutional Flow Canvas**: Chart.js canvas with Daily / Weekly / Monthly / Annual toggles
- **Quarterly FPI Breakdown**: Quarter-over-quarter equity & debt allocations (2015–present)
- **Yearly & Monthly Heatmap**: Multi-year monthly data (2005–2026) revealing cyclical patterns
- **Source**: `📊 NSDL FPI Daily` · `📅 NSDL Yearwise` · `📡 NSE TRDREQ`
</details>

<details>
<summary><b>🌐 Tab 3 — Sectors</b></summary>

Fortnightly FPI allocation tracking from NSDL/CDSL to spot smart-money industry rotation.
- **24 Sector Cards**: AUM %, FII Ownership %, gradient sparklines, and momentum alpha
- **Spaghetti Chart**: Interactive 8-sector comparative trend line (on-hover focus fading)
- **Scoreboard**: Top 8 inflows/outflows ranked by cumulative net flow + progress bars
- **Sort Modes**: Total AUM · Fortnight Δ · 1-Year Net Flow · A–Z
- **Source**: `📑 NSDL Fortnightly Reports` · `🏛️ BSE Sector Classification`
</details>

<details>
<summary><b>🤿 Tab 4 — Deep Dive</b></summary>

Advanced datasets bridging macroeconomic demographics and debt discipline thresholds.
- **Trade-Wise Engine**: Granular monthly flow tracking mapped to Nifty 500 via ISIN cross-referencing
- **Country AUC**: Donut chart of FPI capital sources (USA, Singapore, Luxembourg, Mauritius, etc.)
- **ODI / P-Notes**: Offshore Derivative Instrument tracking — capital via P-Notes rather than direct FPI
- **Debt Utilisation**: FPI debt investment limits vs actual utilisation with progress indicators
- **Source**: `🏦 NSDL Trade-wise ZIPs` · `🌍 NSDL Country AUC` · `⚖️ SEBI ODI/Debt`
</details>

<details>
<summary><b>🗄️ Tab 5 — Databases</b></summary>

Complete institutional flow archives with Bloomberg-terminal grade tabular rendering.
- **4 Timeframes**: Daily (Last 15) · Weekly (12W) · Monthly (24M) · Annual Tracker
- **Preset Filters**: FII Bloodbath (< -₹5k Cr) · DII Absorption (> +₹5k Cr) · Extreme Divergence
- **Date Range Picker**: Custom FROM/TO with instant CSV download
- **Visual Magnitude Bars**: Proportional green/red bar indicators per row
- **Source**: `🏛️ NSE Cash Market Reports`
</details>

<details>
<summary><b>🎲 Tab 6 — F&O Derivatives</b></summary>

Live participant-wise Open Interest from NSE `participant-wise-open-interest` API.
- **OI Breakdown**: FII/DII Long vs Short for Index Futures, Stock Futures, Index Calls & Puts
- **Sentiment Engine**: Heuristic scoring → *Highly Bullish / Mildly Bullish / Neutral / Mildly Bearish / Highly Bearish*
- **Historical Chart**: 20-period trajectory for FII Futures, Calls, Puts, and DII Futures
- **3-Tier Proxy**: Express server → `corsproxy.io` → `allorigins.win` fallback chain
- **Source**: `🎯 NSE Participant-wise OI`
</details>

<details>
<summary><b>📖 Tab 7 — Docs</b></summary>

Built-in user manual with 8 detailed sections covering every feature, formula, and data source in the dashboard.
</details>

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/MrChartist/fii-dii-data.git
cd fii-dii-data

# Install dependencies
npm install

# Start the server
node server.js

# Open in browser
open http://localhost:3000
```

> **No server?** Simply open `fii_dii_india_flows_dashboard.html` in any browser — all data falls back to local JSON files.

---

## 💻 Installation Guide

<details>
<summary><b>🍏 macOS</b></summary>

```bash
# 1. Install prerequisites (via Homebrew)
brew install node git

# 2. Clone & install
git clone https://github.com/MrChartist/fii-dii-data.git
cd fii-dii-data && npm install

# 3. Start the server
node server.js
# Dashboard at http://localhost:3000
```
</details>

<details>
<summary><b>🪟 Windows</b></summary>

```cmd
REM 1. Install Node.js from https://nodejs.org
REM    Install Git from https://git-scm.com

REM 2. Clone & install
git clone https://github.com/MrChartist/fii-dii-data.git
cd fii-dii-data
npm install

REM 3. Start the server
node server.js
REM Dashboard at http://localhost:3000
```
</details>

<details>
<summary><b>🐧 Linux (Ubuntu/Debian)</b></summary>

```bash
# 1. Install prerequisites
sudo apt update && sudo apt install -y nodejs npm git

# 2. Clone & install
git clone https://github.com/MrChartist/fii-dii-data.git
cd fii-dii-data && npm install

# 3. Start the server
node server.js
# Dashboard at http://localhost:3000
```
</details>

---

## ☁️ Deployment

### Hostinger VPS (Recommended)

```bash
# SSH into your server
ssh root@your-vps-ip

# Clone & install
git clone https://github.com/MrChartist/fii-dii-data.git
cd fii-dii-data && npm install --production

# Start with PM2 (auto-restart on crash)
npm install -g pm2
npm run pm2
pm2 save && pm2 startup
```

### Vercel (Serverless)

```bash
npx vercel --prod
```

The included `vercel.json` handles routing automatically.

### Static Hosting

Upload the entire folder to any web host. The dashboard works without Node.js — all API calls fall back to `/data/*.json` files.

---

## 🌳 Project Structure

```
📁 fii-dii-data/
│
├── 📄 fii_dii_india_flows_dashboard.html   # Main Single-Page Application (261 KB)
├── 📄 server.js                            # Express backend + API proxy + cron jobs
├── 📄 package.json                         # Dependencies & PM2 scripts
├── 📄 ecosystem.config.js                  # PM2 process manager config
├── 📄 .htaccess                            # Apache → Node.js reverse proxy
├── 📄 manifest.json                        # PWA Web App Manifest
├── 📄 sw.js                                # Service Worker for offline support
├── 📄 robots.txt                           # Search engine crawler rules
├── 📄 sitemap.xml                          # XML sitemap for SEO
├── 📄 LICENSE                              # MIT License
│
├── 📁 data/                                # JSON Fallback Data Store
│   ├── latest.json                         # Latest NSE cash + F&O snapshot
│   ├── history.json                        # Historical daily session data
│   ├── sector_latest.json                  # Latest fortnightly sector data
│   ├── sector_history.json                 # 24-fortnight sector allocation history
│   ├── fpi_daily.json                      # NSDL daily FPI investment data
│   ├── fpi_quarterly.json                  # Quarterly equity/debt breakdown
│   ├── fpi_yearly_monthly.json             # Multi-year monthly data (2005–2026)
│   ├── fpi_monthly_history.json            # Monthly historical FPI flows
│   ├── country_auc.json                    # Country-wise Assets Under Custody
│   ├── debt_utilisation.json               # FPI debt limit vs utilisation
│   └── odi_pn.json                         # Offshore Derivative Instruments / P-Notes
│
├── 📁 scripts/                             # Automation & Data Pipeline
│   ├── fetch_data.js                       # Main data fetcher (NSE TRDREQ + scraping)
│   ├── fetch_nsdl.js                       # Puppeteer NSDL .aspx grid scraper
│   ├── fetch_nsdl_daily_backfill.js        # Historical daily FPI backfill
│   ├── fetch_tradewise_backfill.js         # Trade-wise monthly ISIN extraction
│   ├── build_isin_map.js                   # Nifty 500 ISIN-to-Symbol mapper
│   ├── backfill_analytics.js               # Analytics backfill pipeline
│   ├── append_2015_2019.js                 # Historical data append (2015–2019)
│   ├── append_2010_2014.js                 # Historical data append (2010–2014)
│   └── append_2005_2009.js                 # Historical data append (2005–2009)
│
├── 📁 icons/                               # PWA Icons
│   ├── icon-192.png                        # 192×192 app icon
│   └── icon-512.png                        # 512×512 app icon
│
├── 📁 screenshots/                         # Tab screenshots for README
│
└── 📁 .github/                             # GitHub Actions (auto-fetch workflow)
```

---

## 🛠️ Technology Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **Frontend** | HTML5 / CSS3 / Vanilla JS | Zero-dependency SPA with custom properties, OLED dark mode, glassmorphism |
| **Charts** | Chart.js v3 | Spaghetti lines, donut charts, bar combos, gradient sparklines |
| **Backend** | Node.js + Express | API routing, static serving, CORS proxy, cron scheduling |
| **Scraping** | Puppeteer | Headless Chrome for NSDL `.aspx` grid scraping |
| **Process Mgmt** | PM2 | Production process management with auto-restart |
| **Export** | html2canvas | Full-page screenshot export with watermarks |
| **PWA** | Service Worker + Manifest | Offline support, installable web app |
| **SEO** | JSON-LD + Open Graph | Structured data, Twitter Cards, canonical URLs |

---

## 📡 Data Sources

| Source | Data | Frequency | URL |
|--------|------|-----------|-----|
| **NSE TRDREQ** | FII/DII cash market buy/sell/net | Daily (market hours) | [nseindia.com/report-detail](https://www.nseindia.com/report-detail/display-reports) |
| **NSE Participant OI** | F&O Open Interest by participant | Daily (EOD) | [nseindia.com/fo_participant](https://www.nseindia.com/report-detail/fo_participant) |
| **NSDL FPI Reports** | Equity, Debt, Hybrid investment | Daily / Monthly | [fpi.nsdl.co.in](https://www.fpi.nsdl.co.in/web/Reports/Latest.aspx) |
| **NSDL Sector Allocation** | Fortnightly BSE sector-wise FPI holdings | Fortnightly | [fpi.nsdl.co.in](https://www.fpi.nsdl.co.in/web/Reports/Fortnightly.aspx) |
| **NSDL Country AUC** | Country-wise Assets Under Custody | Monthly | [fpi.nsdl.co.in](https://www.fpi.nsdl.co.in/web/Reports/Latest.aspx) |
| **NSDL Debt Utilisation** | FPI debt limit vs utilisation | Monthly | [fpi.nsdl.co.in](https://www.fpi.nsdl.co.in/web/Reports/Latest.aspx) |
| **SEBI ODI/PN** | Offshore Derivative Instruments | Monthly | [sebi.gov.in](https://www.sebi.gov.in/) |

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────┐
│                     Client (Browser)                 │
│  ┌──────────────────────────────────────────────┐   │
│  │   fii_dii_india_flows_dashboard.html (SPA)    │   │
│  │   ├── Vanilla JS State Management             │   │
│  │   ├── Chart.js v3 Rendering Engine            │   │
│  │   ├── html2canvas Screenshot Export           │   │
│  │   └── Service Worker (Offline Cache)          │   │
│  └──────────────┬──────────────┬────────────────┘   │
│                 │              │                     │
│          Tier 1 │       Tier 3 │ (Static Fallback)   │
│     ┌───────────┘              └──────────┐         │
│     ▼                                      ▼         │
│  Express API                         /data/*.json    │
│  /api/data                          (Local JSON)     │
│  /api/fno                                            │
│  /api/nsdl/*                                         │
│     │                                                │
│     │ Tier 2 (CORS Proxy Fallback)                   │
│     ├── corsproxy.io                                 │
│     └── allorigins.win                               │
└──────────────────────┬──────────────────────────────┘
                       │
        ┌──────────────┼──────────────┐
        ▼              ▼              ▼
   NSE APIs       NSDL Portal     SEBI Portal
   (TRDREQ)      (FPI Monitor)   (ODI Reports)
   (Participant OI) (Sector AUC)
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🔗 Links

<p align="center">
  <a href="https://fii-diidata.mrchartist.com/"><img src="https://img.shields.io/badge/🌐_Live_Dashboard-fii--diidata.mrchartist.com-2563EB?style=for-the-badge" alt="Live Dashboard"></a>
  <a href="https://github.com/MrChartist/fii-dii-data"><img src="https://img.shields.io/badge/GitHub-MrChartist%2Ffii--dii--data-181717?style=for-the-badge&logo=github" alt="GitHub"></a>
  <a href="https://twitter.com/mr_chartist"><img src="https://img.shields.io/badge/𝕏-@mr__chartist-000000?style=for-the-badge&logo=x" alt="Twitter"></a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%">
</p>

<p align="center">
  <b>Built for professional traders. Made with ❤️ by <a href="https://twitter.com/mr_chartist">Mr. Chartist</a></b><br>
  <i>Institutional Money Matrix — Mapping where the smart money flows.</i>
</p>
