# 🔔 Task & Event Reminder Web Application

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A lightweight, interactive web application built with vanilla JavaScript, HTML5, and CSS3 that enables users to schedule custom task reminders with native browser notifications and continuous audio alerts.

---

## ✨ Features

- 📅 **Custom Task Scheduling**: Set title, description, date, and specific time for any reminder.
- 🔔 **Native Browser Notifications**: Leverages HTML5 Web Notifications API to alert users even when the tab is running in the background.
- 🔊 **Looping Audio Alarm**: Plays an audio tone (`short-beep-countdown`) continuously until the user acknowledges the notification.
- 📋 **Active Reminders Table**: Dynamic list displaying all upcoming reminders with real-time countdown tracking.
- 🗑️ **Delete & Cancel**: Easily clear scheduled tasks, automatically stopping background timers (`clearTimeout`).
- 🎨 **Responsive Glassmorphism UI**: Stylish gradient backdrop with smooth button interactions.

---

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Brave, Safari) with Notification permissions enabled.

### Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/B-LIPIKA/Task-Reminder-.git
   cd Task-Reminder-
   ```
2. Open `index.html` directly in your browser:
   - Double-click `index.html` **OR**
   - Use VS Code extension **Live Server** (`http://127.0.0.1:5500/index.html`)

3. When prompted, allow notification permissions in your browser.

---

## 🛠️ Tech Stack & Concepts

- **Frontend**: HTML5, Vanilla CSS3 (Gradients, Flexbox, Box-Shadows)
- **Logic**: ES6+ JavaScript (`setTimeout`, `clearTimeout`, `Array` operations)
- **Web APIs**: `Notification` API, HTML5 `Audio` element

---

## 📸 How It Works

1. Enter a **Title**, **Description**, select a **Date** and **Time**.
2. Click **Schedule Reminder**.
3. The task appears in the Active Reminders table.
4. When the scheduled time arrives, an audio beep triggers continuously and a desktop pop-up notification appears.
5. Click on the notification pop-up to stop the alarm and acknowledge the task.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for details.
