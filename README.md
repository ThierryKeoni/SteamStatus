SteamStatus is for users that wanna share their listening status. Like discord rich presence

# SteamStatus 🎧

SteamStatus is a lightweight desktop application built with Electron and JavaScript that displays your live Spotify listening activity as your Steam "In-Game" status, similar to Discord's rich presence. 

Specially optimized to support Windows and macOS, this tool bridge the gap where official native integrations are missing.

---

## ✨ Features

- **Live Sync:** Automatically updates your Steam status whenever you play, pause, or skip a song on Spotify.
- **Mac Native:** Uses efficient local hooks (AppleScript) to read Spotify's playback status without draining battery.
- **Minimalistic UI:** Runs quietly in your macOS menu bar (Tray App) so it stays out of your way while gaming.
- **Privacy First:** Your login details connect directly to Steam's official network via open-source libraries.

---

## 🚀 How It Works

Steam doesn't officially allow custom text statuses, but it *does* allow you to name custom games. **SteamStatus** dynamically registers a "fake" game in your Steam client and renames it in real-time to:
`In-Game: Listening to [Song Name] • [Artist]`

---

## 🛠️ Prerequisites

Before running the application, make sure you have the following installed on your Mac:

- [Node.js](https://nodejs.org) (v16 or higher recommended)
- [Spotify Desktop App](https://spotify.com)
- [Steam Client](https://steampowered.com)

---

## 📦 Installation & Setup --COMING SOON--


---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com) if you want to contribute or report a bug.

---

## 📝 License

This project is not licensed.
