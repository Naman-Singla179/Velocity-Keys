# Velocity Keys ⚡

A sleek, modular typing speed application built with **Vanilla JavaScript**, **HTML**, and **CSS**. Velocity Keys provides a distraction-free environment to test your typing speed or build muscle memory through a randomized practice mode.

## 🚀 Features

*   **Test Mode:** Choose from Easy, Medium, or Hard difficulty levels with predefined time limits.
*   **Practice Mode:** Select a word count (10, 25, or 50) and type over "Ghost Text" with real-time error highlighting.
*   **Live Analytics:** Real-time WPM (Words Per Minute) and character tracking.
*   **Detailed Reports:** Post-session diagnostics including accuracy, valid strings, and anomalies.
*   **Personal Stats:** A dedicated dashboard featuring:
    *   WPM Progress over time (visualized with Chart.js).
    *   A Top-10 Leaderboard.
    *   Full session history stored locally in your browser.
*   **Glassmorphism UI:** A modern, dark-themed aesthetic with smooth CSS transitions.

## 🛠️ Built With

*   **HTML5 & CSS3:** Semantic structure and custom responsive styling.
*   **Vanilla JavaScript:** Core logic, stopwatch/timer engines, and DOM manipulation.
*   **Chart.js:** Data visualization for performance analytics.
*   **Google Fonts:** 'Outfit', 'Playfair Display', and 'JetBrains Mono'.

## 📁 Project Structure

*   `index.html`: The landing page and mode selection.
*   `levels.html`: Test difficulty selection.
*   `test.html`: The core competitive typing engine.
*   `practice-setup.html`: Practice mode word count selection.
*   `practice.html`: The "Ghost Text" practice engine.
*   `results.html`: Session report and performance diagnostics.
*   `stats.html`: Long-term analytics, history, and leaderboard.
*   `passages.json`: The data source for typing prompts.

## 🚦 Getting Started

### Prerequisites
To ensure the typing passages load correctly from the JSON file, you **must** run this project using a local web server due to browser security (CORS) policies.

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/velocity-keys.git](https://github.com/YOUR-USERNAME/velocity-keys.git)
