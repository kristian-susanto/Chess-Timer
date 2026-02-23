# ⏳ Chess Timer Pro - Professional Edition

**Chess Timer Pro** is a high-performance web-based chess clock application designed for both amateur and professional tournaments. With a focus on precision and responsiveness, it brings the functionality of a physical chess clock to a digital device, with support for _Increment_, _Handicap_, and in-depth match statistics.

---

## ✨ Key Features

### 🎮 Comprehensive Game Modes

- **Normal:** Standard time control for casual play.
- **Increment (Fischer):** Automatic time increments after each move (seconds + S system).
- **Tournament:** Competition mode with a _move limit_ and visual warnings when approaching the limit.
- **Handicap:** Balanced game play with different time settings for each player (ideal for advanced players vs. beginners).

### 🛠️ Unlimited Customization

- **Dynamic Names:** Change player names directly through interactive dialogs.
- **Personalized Aesthetics:** Choose a unique color scheme for each player zone to avoid confusion while playing.
- **Dual Themes:** Supports Dark Mode (OLED Friendly) and Light Mode with data persistence via `localStorage`.

### 📊 Match Analytics & History

- **Live Move Logging:** Every move is recorded, complete with remaining time and duration per move.
- **Post-Match Statistics:** Displays average thinking time (_Average Time_) and fastest move (_Fastest Move_).
- **Export Feature:** Download the complete match history in `.txt` format for post-match analysis.

---

## 🚀 User Guide

1.  **Configuration:** Select a mode in the top navigation panel. Set the base time and additional
2.  **Initiation:** Click **Start** to begin. The first player's clock will start ticking.
3.  **Operation:** Tap the active player's screen area to pass the turn.
4.  **Personalization:** Click on the "Player 1" or "Player 2" text to rename them, or use the _color picker_ to change the zone color.
5.  **Keamanan Data:** The **Reset** button is equipped with confirmation protection (via SweetAlert2) to prevent accidental data deletion during a match.

---

## 🛠️ Technical Architecture

This application is built on the _Zero-Dependency_ principle (light and fast) with maximum performance:

- **Engine:** Vanilla JavaScript (ES6+) for precise timing logic.
- **Audio Engine:** Uses the `Web Audio API` for a high-frequency sound oscillator that remains responsive without _latency_ (instead of simply playing .mp3 files).
- **UI Components:** [SweetAlert2](https://sweetalert2.github.io/) for elegant modal interactions.
- **Layouting:** CSS Grid & Flexbox with the `clamp()` system for responsive typography across screen sizes.

---

## 📱 Mobile Optimization (UX)

This app is designed specifically for mobile devices:

- **Dynamic Viewport:** Uses the `dvh` unit to prevent the UI from being cut off by the browser's _address bar_.
- **Landscape Mode:** When the phone is tilted, the app automatically hides non-essential elements to maximize the player's touchscreen.
- **Auto-Pause:** The game will automatically pause if the user switches tabs or minimizes the browser, ensuring time integrity is maintained.

---

## 📄 License & Credits

This project is _Open Source_.

---
