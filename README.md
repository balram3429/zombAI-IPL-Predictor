# ⚡ ZOMB.AI — IPL ORACLE

> **AI-Powered Indian Premier League Predictive Intelligence Engine**
> Advanced match analysis, win probability modeling, and historical data visualization for every IPL Final.

---

```
███████╗ ██████╗ ███╗   ███╗██████╗       █████╗ ██╗
╚══███╔╝██╔═══██╗████╗ ████║██╔══██╗     ██╔══██╗██║
  ███╔╝ ██║   ██║██╔████╔██║██████╔╝     ███████║██║
 ███╔╝  ██║   ██║██║╚██╔╝██║██╔══██╗     ██╔══██║██║
███████╗╚██████╔╝██║ ╚═╝ ██║██████╔╝     ██║  ██║██║
╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚═════╝      ╚═╝  ╚═╝╚═╝
         IPL ORACLE · POWERED BY ZOMBAI · @balram3429
```

---

## 📖 Overview

**ZOMB.AI — IPL Oracle** is a fully self-contained, single-page predictive analytics tool built around the complete history of the Indian Premier League (2008–present). It combines historical match data, venue intelligence, and weighted probabilistic modeling to simulate Final match outcomes between any two IPL franchises.

No backend. No database. No frameworks. Just one `.html` file.

---

## ✨ Features

### 🏟️ Hero Landing
- Cinematic full-screen entry with stadium arc rings, scanline overlay, and radial vignette
- IPL franchise abbreviations floating in the background as ambient watermarks
- Cricket emoji elements (🏏 🏆 ⚡) scattered with CSS float animations
- Ambient **stadium crowd noise** generated via the **Web Audio API** (no blocked external audio sources)
- Sound toggle button — enable/disable live crowd atmosphere

---

### 📋 Last 5 IPL Finals — Hero Banner Cards

Interactive scorecard banners for the **5 most recent IPL Finals**:

| Year | Winner | Runner-Up | Venue | MOM |
|------|--------|-----------|-------|-----|
| 2024 | KKR 🏆 | SRH | MA Chidambaram Stadium, Chennai | Ajinkya Rahane |
| 2023 | CSK 🏆 | GT | Narendra Modi Stadium, Ahmedabad | Devon Conway |
| 2022 | GT 🏆 | RR | Narendra Modi Stadium, Ahmedabad | Hardik Pandya |
| 2021 | CSK 🏆 | KKR | Dubai International Stadium | Faf du Plessis |
| 2020 | MI 🏆 | DC | Dubai International Stadium | Ishan Kishan |

**Tap any card** to open a full **Team Formation Modal** showing:
- All 11 players with shirt numbers and roles
- MVP badge for standout performers
- Full scorecard (both innings)
- Match result summary

---

### 🧠 AI Predictive Engine

**Select and configure:**

| Input | Options |
|-------|---------|
| **Team 1** | All 10 current IPL franchises |
| **Team 2** | All 10 current IPL franchises |
| **Tournament Stage** | Final · Qualifier 1 · Qualifier 2 · Eliminator |
| **Venue** | 15 stadiums across India, UAE, and South Africa |

**Algorithm factors:**
- Historical team win rate (2008–2024)
- Head-to-head record (all-time encounters)
- Venue-specific modifiers
- Pitch type suitability
- Dew factor & chasing advantage
- Finals experience weighting
- Randomised form variance

---

### 📊 Analysis Output

#### Win / Lose Probability Panel
- Full-width animated probability banner per team
- Color-coded: Gold = favourite · Dim = underdog
- Animated progress bar indicating relative probability split

#### Head-to-Head Record
- All-time wins for each team
- Total matches played between the two sides

#### 12 Match Factor Cards
Each factor is rated **HIGH / MED / LOW** impact:

| Factor | Description |
|--------|-------------|
| 🏏 Pitch Type | Surface condition (flat, spin, seam, bouncy) |
| 🌡️ Temperature | Match day temperature at venue city |
| 💧 Humidity | Affects swing and dew probability |
| 💨 Wind Speed | Direction & speed — impacts ball flight |
| 🌦️ Conditions | Clear / Overcast / Cloudy / Windy |
| 🌙 Dew Factor | Evening dew risk — major chasing advantage |
| 🔄 Spin Assist | Spinner effectiveness on the surface |
| ⚡ Pace Factor | Seam & pace conditions |
| 🏆 Team 1 Finals Exp. | Number of finals & titles |
| 🏆 Team 2 Finals Exp. | Number of finals & titles |
| 📍 Home Advantage | Neutral / Home ground indicator |
| 📊 Avg. First Innings | Historical average score at the venue |

#### Chasing vs Defending Analysis
- Venue-specific **chase win %** and **defend win %**
- Contextual dew and pitch notes per stadium

#### AI Verdict
- Final declared prediction with rationale
- References H2H history, venue, pitch, and team win probability

---

### 📈 Charts & Visualizations (Chart.js v4.4)

| Chart | Type | Description |
|-------|------|-------------|
| Win Probability Comparison | Bar Chart | Side-by-side win % for both teams |
| Head to Head History | Doughnut Chart | All-time wins split with team colors |
| Venue Advantage Analysis | Bar Chart | Avg score, chase %, defend % at selected stadium |
| Factor Impact Radar | Radar Chart | 6-dimension comparison: Batting Form, Bowling Form, Finals Exp., H2H Advantage, Pitch Suitability, Chasing Ability |

---

## 🏟️ Supported Venues

### 🇮🇳 India
| Stadium | City | Pitch Profile |
|---------|------|---------------|
| Wankhede Stadium | Mumbai | Flat / High-scoring |
| Narendra Modi Stadium | Ahmedabad | Balanced |
| MA Chidambaram Stadium | Chennai | Spin-friendly |
| Eden Gardens | Kolkata | Balanced / Seamer-friendly |
| Chinnaswamy Stadium | Bengaluru | Flat / Batting paradise |
| Rajiv Gandhi Intl. Stadium | Hyderabad | Flat |
| Arun Jaitley Stadium | Delhi | Balanced |
| Sawai Mansingh Stadium | Jaipur | Spinner-friendly |
| PCA IS Bindra Stadium | Mohali | Seam-friendly |
| HPCA Stadium | Dharamsala | Seam-friendly |

### 🇦🇪 UAE
| Stadium | City | Pitch Profile |
|---------|------|---------------|
| Dubai International Stadium | Dubai | Low & Slow |
| Sharjah Cricket Stadium | Sharjah | Small Ground / Flat |
| Sheikh Zayed Stadium | Abu Dhabi | Slow / Spin-friendly |

### 🇿🇦 South Africa
| Stadium | City | Pitch Profile |
|---------|------|---------------|
| SuperSport Park | Centurion | Bouncy / Pacer-friendly |
| Newlands Stadium | Cape Town | Swing / Seam |

---

## 🎨 Design System

### Typography
| Role | Font | Usage |
|------|------|-------|
| Display / Hero | `Bebas Neue` | Large headings, year stamps, probability numbers |
| Headings | `Space Mono` | Section labels, meta text, badges |
| Body | `JetBrains Mono` | Stats, descriptions, factor values |
| Alternate | `Barlow Condensed` | Team names, UI labels |

### Color Palette
| Token | Hex | Purpose |
|-------|-----|---------|
| `--black` | `#0a0a0a` | Primary background |
| `--white` | `#f5f5f0` | Body text |
| `--yellow` | `#FFD700` | Primary accent — gold luxury |
| `--yellow-dim` | `#c9a227` | Gradient companion |
| `--red` | `#e63946` | High-impact indicators |
| `--gray` | `#1a1a1a` | Card backgrounds |
| `--gray2` | `#252525` | Nested elements |

### Visual Effects
- CSS `clip-path` polygon chamfered corners on all cards and buttons
- Scanline overlay on hero section
- Radial vignette gradient
- Stadium arc rings (pure CSS `border-radius: 50%`)
- Shimmer sweep animation on hover (pseudo-element)
- Floating background logo animation (`@keyframes floatLogo`)
- Gold scrollbar via `::-webkit-scrollbar`

---

## 🏏 IPL Teams Included

| Short | Full Name | Titles |
|-------|-----------|--------|
| CSK | Chennai Super Kings | 5 |
| MI | Mumbai Indians | 5 |
| KKR | Kolkata Knight Riders | 3 |
| RR | Rajasthan Royals | 2 |
| GT | Gujarat Titans | 2 |
| SRH | Sunrisers Hyderabad | 1 |
| RCB | Royal Challengers Bengaluru | 1 |
| DC | Delhi Capitals | 0 |
| PBKS | Punjab Kings | 0 |
| LSG | Lucknow Super Giants | 0 |

---

## 🛠️ Tech Stack

```
Single HTML File · Zero Dependencies (runtime)
├── HTML5
├── CSS3
│   ├── CSS Custom Properties (variables)
│   ├── CSS Grid & Flexbox
│   ├── clip-path polygon shapes
│   ├── @keyframes animations
│   └── CSS backdrop-filter (glassmorphism)
├── Vanilla JavaScript (ES6+)
│   ├── Web Audio API (crowd noise generator)
│   ├── Chart.js 4.4.0 (via CDN)
│   └── Google Fonts (via CDN)
└── External CDN Dependencies
    ├── Chart.js — https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.0/chart.umd.min.js
    └── Google Fonts — Space Mono · JetBrains Mono · Bebas Neue · Barlow Condensed
```

> **No build step. No npm. No framework.** Open `ZombAI-IPL.html` in any modern browser.

---

## 🚀 Getting Started

```bash
# Clone or download the file
git clone https://github.com/balram3429/zombai-ipl.git

# Navigate to project
cd zombai-ipl

# Open directly in browser (no server required)
open ZombAI-IPL.html
```

Or simply **double-click** `ZombAI-IPL.html` in your file manager.

---

## 🔧 Usage

1. **Landing** — Allow the loading animation to complete. The crowd ambient sound activates automatically (toggle with the button, top-right).
2. **Finals Archive** — Browse the last 5 IPL Finals cards. Tap any to see full team formations and scorecards.
3. **Predictor** — Select two teams, choose a tournament stage, and pick a stadium venue.
4. **Analyse** — Click **⚡ RUN PREDICTIVE ANALYSIS**. Watch the neural engine processing steps animate through.
5. **Results** — Review win/lose probability, head-to-head record, 12 match factors, chasing stats, 4 charts, and the AI verdict.

---

## 📁 Project Structure

```
ZombAI-IPL/
│
├── ZombAI-IPL.html       ← Entire application (single file)
└── README.md             ← This file
```

---

## ⚠️ Disclaimer

> This tool is built for **entertainment and analytical exploration** purposes only. All win probabilities are generated using weighted historical data models and are **not** a guarantee of real-world match outcomes. IPL results depend on live conditions, player form, toss, and many unmodeled variables.

---

## 👤 Author

**ZombAI** · [@balram3429](https://github.com/balram3429)

---

## 📄 License

```
MIT License — Free to use, modify, and distribute.
Credit appreciated: Powered by ZombAI · @balram3429
```

---

<div align="center">

**ZOMB.AI — IPL ORACLE**
*The most aggressive IPL prediction tool on the internet.*

⚡ `BLACK + WHITE + YELLOW = POWER` ⚡

</div>
