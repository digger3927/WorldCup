# ⚽ FIFA World Cup 2026 Dashboard

Welcome to the **FIFA World Cup 2026 Dashboard**, a modern, lightweight, and interactive web application designed to bring you the excitement of the tournament in real-time. Built entirely on standard web technologies, it delivers up-to-the-minute updates without the bloat of modern framework stacks.

---

## ✨ Features

- ⚡ **Zero Setup, Zero Dependencies**: Pure HTML5, CSS3, and Vanilla JavaScript. Just open it and watch the tournament unfold!
- 📡 **ESPN Live API Integration**: Powered directly by ESPN's soccer endpoints. Live scores, statistics, and tournament standings refresh automatically.
- ⏱️ **Auto-Refresh Engine**:
  - **Live match data** updates every **30 seconds** so you never miss a goal.
  - **Group Standings** refresh every **2 minutes**.
  - **Tournament News** updates every **10 minutes**.
- 🏆 **Interactive Knockout Bracket**: Visualize the journey from the Round of 32 to the Finals in a responsive tournament tree layout.
- 📊 **Detailed Match center**: Click on any active or completed match to view:
  - Starting lineups.
  - A chronological match timeline (goals, yellow/red cards, substitutions).
  - Advanced match stats (possession, shots, saves, fouls, corners).
- 🌍 **National Team Profiles**: Click on any country's flag to view their current tournament roster and recent match history.
- 👥 **Group Exploration**: Inspect individual group Standings, points, goals difference, and head-to-head records directly in localized modal views.
- 🎨 **Rich & Premium UI/UX**:
  - Stunning dark-mode-inspired theme with glowing animations.
  - Rainbow-animated headers for live matches.
  - Responsive grids adjusting smoothly from mobile screens up to 4K displays.
  - Glassmorphic backdrop-filter dialogs for detail modals.

---

## 🛠️ Technology Stack

This application is built with simplicity, speed, and standard compliance in mind:
- **Structure**: Semantic HTML5 (leveraging the native `<dialog>` element for seamless modal overlays).
- **Styling**: Vanilla CSS3 featuring CSS Custom Properties (Variables), Flexbox, CSS Grid layouts, and custom keyframe animations.
- **Logic**: Vanilla ES6+ JavaScript using asynchronous `Fetch API`, `async/await`, dynamic DOM injection, and robust event handling.
- **Data Source**: ESPN FIFA World Cup public API.

---

## 🚀 Getting Started

Since this is a fully client-side static application, launching it is incredibly straightforward:

### Method 1: Just Double-Click (Simplest)
1. Clone or download the repository.
2. Locate the [index.html](file:///Users/eric/Dev/WorldCup/index.html) file.
3. Double-click it to open it in your default web browser (Chrome, Safari, Firefox, Edge).

### Method 2: Local Web Server (Recommended for API robustness)
If you prefer running it on a local web server (to avoid local file system policy warnings or just for convenience):

- **Python 3**:
  ```bash
  python3 -m http.server 8000
  ```
  Then open [http://localhost:8000](http://localhost:8000) in your browser.

- **Node.js (serve)**:
  ```bash
  npx serve .
  ```
  Then open [http://localhost:3000](http://localhost:3000) in your browser.

- **VS Code extension**:
  Install and click **"Go Live"** using the **Live Server** extension.

---

## 📁 Repository Structure

```text
WorldCup/
├── index.html            # Main application (HTML markup, styling, and JS logic)
├── worldcup_banner.png   # Dashboard cover banner
├── .gitignore            # Git ignore configuration
└── README.md             # This documentation
```

---

## ⚽ Let the Games Begin!
Watch your favorite national teams compete for glory in USA, Canada, and Mexico! If you run into issues or have ideas for new widgets, feel free to open a pull request or file an issue.
