# ⏳ Chess Timer Pro - Professional Edition

Chess Timer Pro is a responsive web-based chess clock application designed to provide a fair and functional chess playing experience. The application supports various game modes such as Normal, Increment (Fischer), Tournament, and Handicap, and is optimized for mobile devices (Portrait & Landscape).

## ✨ Key Features

- **Variety of Game Modes:**
  - **Normal:** Standard time for both players.
  - **Increment (+S):** Adds time each time a player completes a move (Fischer system).
  - **Tournament:** Comes with a move limit (_Move Limit_).
  - **Handicap:** Provides different time advantages for players of different levels.
- **Full Customization:**
  - Change player names directly.
  - Choose button color schemes for each player.
  - Persistent Dark and Light modes (auto-saved).
- **Complete Log & Statistics:**
  - Move history is automatically saved.
  - Average time and fastest move statistics.
  - Export Log (.txt) feature to save match data.
- **Audio & Visual:**
  - Heartbeat sound effect for the last 10 seconds.
  - Pulse animation when time is running out.
  - Adaptive layout (automatically adjusts when the phone is tilted).

## 🚀 How to Use

1. **Settings:** Select a game mode and set the base time in the top navigation bar.
2. **Start:** Click the **Start** button to begin. The first player's clock will be active.
3. **Play:** Tap the active player's screen area to pass the turn to the opposing player.
4. **Edit Name:** Click on the "Player 1" or "Player 2" text to change the name.
5. **Reset:** Use the **Reset** button to restart the session. A confirmation will appear if the match is in progress to prevent accidental interruptions.

## 🛠️ Technical Details

This app is built using standard web technologies without any heavy external libraries (except SweetAlert2 for the pop-up UI):

- Frontend: HTML5, CSS3 (Flexbox & Grid), JavaScript (Vanilla ES6).
- Library: SweetAlert2 for beautiful dialog boxes.
- Responsiveness: Uses custom Media Queries to detect landscape orientation on mobile devices for maximum convenience.
- Storage: LocalStorage is used to store user theme and sound preferences.

## 📱 Mobile Optimization

This app uses the `dvh` (Dynamic Viewport Height) and `clamp()` CSS features to ensure the clock remains large and isn't cut off by the browser navigation bar on Android or iOS.

## 📄 License

This project is open-source. Please feel free to use and modify it to suit your needs.

---

Developed by **Kristian Susanto**
