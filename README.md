<div align="center">
  <img src="public/logo_256.png" alt="SkyVal Logo" width="128" />
  <h1>SkyVal</h1>
  <p><strong>The Ultimate Desktop Companion & Tracker for Valorant</strong></p>

  <img src="https://img.shields.io/badge/Version-1.0.0-blue.svg" alt="Version" />
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6.svg?logo=windows&logoColor=white" alt="Windows" />
  <img src="https://img.shields.io/badge/Electron-31.0.0-47848f.svg?logo=electron&logoColor=white" alt="Electron" />
  <img src="https://img.shields.io/badge/React-18.0-61DAFB.svg?logo=react&logoColor=black" alt="React" />
</div>

<br />

SkyVal is a blazingly fast, modern desktop application built from the ground up for competitive Valorant players. Designed to seamlessly integrate with your Riot Client without interrupting your gameplay, SkyVal gives you unprecedented access to live match data, in-depth player statistics, and real-time account tracking directly on your desktop. 

Unlike heavy web-based trackers that inject overlays, SkyVal securely communicates entirely through the local Riot Client API, ensuring that your account remains 100% safe while pulling the most accurate and up-to-date information possible with zero impact on your game's framerate.

---

## ✨ Features

- 👁️ **Live Lobby Scouting** — Instantly view the hidden ranks, account levels, win rates, and party groupings of everyone in your lobby during the pre-game Agent Select phase. Never go into a match blind again.
- 📊 **Deep Match History** — Dive into your past performances with beautifully formatted match cards, load-more pagination, and detailed score breakdowns (K/D/A, ACS, HS%, and RR changes).
- 🔍 **Global Player Search** — Look up any player's career statistics and current rank to see exactly who you are up against.
- 🛒 **Daily Store Tracker** — Check your rotating Valorant daily store and current skin offers without having to boot up the heavy game client.
- 🎮 **Discord Rich Presence (RPC)** — Automatically broadcast your live Valorant status, current map, party size, and score directly to your Discord profile to let your friends know when you're in a match.
- 🎨 **Enemy Skin Visibility** — See exactly which skins your enemies have equipped while you are in the match.
- ⚡ **Lightning Fast** — Built with React Query and Zustand to cache your data locally. Zero lag, zero stutter.

---

## 🚀 Installation & Usage

SkyVal is currently available for **Windows**.

1. Navigate to the [Releases](#) tab on this GitHub repository.
2. Download the latest `SkyVal Setup.exe`.
3. Run the installer. 
4. Launch SkyVal! **Make sure your Riot Client or Valorant is open** so SkyVal can automatically connect and pull your data.

> [!NOTE]
> Because SkyVal is a brand-new indie application, Windows Defender SmartScreen might flag the installer as an "Unrecognized App". This is normal! Simply click **More Info -> Run Anyway**.

---

## 🔒 Safety & Security

**Is SkyVal safe to use?**
Yes. SkyVal is 100% safe and will **not** result in a ban. 
- SkyVal does **not** read game memory.
- SkyVal does **not** inject files into your game client.
- SkyVal merely reads the local Riot Lockfile generated on your PC to fetch data directly from Riot's servers, utilizing the exact same endpoints that the official client uses.

> [!WARNING]  
> **Disclaimer:** SkyVal is an independent, community-driven fan project and is **not** endorsed by, directly affiliated with, maintained, authorized, or sponsored by Riot Games. 

---

## 🛠️ For Developers

SkyVal is an open-source project and welcomes community contributions! The application is built entirely on modern web technologies.

### Tech Stack
- **Core:** Electron 31, TypeScript 5, React 18, Vite
- **State Management:** Zustand
- **Data Fetching:** `@tanstack/react-query`
- **Animations & Styling:** Framer Motion, Vanilla CSS (Valorant aesthetic)
- **Packaging:** `electron-builder`

### Building from Source

Ensure you have **Node.js 18+** installed.

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/skyval.git
cd skyval

# Install dependencies
npm install

# Start the development server (Hot Reloading)
npm run dev

# Build the final production .exe installer
npm run build
```

---

<div align="center">
  <p>Made with ❤️ by the SkyVal Dev Team</p>
</div>
SkyVal — The Ultimate Valorant Companion App
SkyVal is a blazingly fast, modern desktop companion application built from the ground up for competitive Valorant players. Designed to seamlessly integrate with your Riot Client without interrupting your gameplay, SkyVal gives you unprecedented access to live match data, in-depth player statistics, and real-time account tracking directly on your desktop.

At its core, SkyVal securely communicates with the local Riot Client API, ensuring that your account remains 100% safe while pulling the most accurate and up-to-date information possible. Whether you're in the main menu, queueing for a match, or locked into a tense Agent Select screen, SkyVal keeps you informed.

Core Features
Live Lobby Scouting: Instantly view the hidden ranks, account levels, and match histories of everyone in your lobby during the pre-game phase. Never go into a match blind again.
Deep Match History: Dive into your past performances with beautifully formatted match cards, load-more pagination, and detailed score breakdowns that help you analyze your climb.
Global Player Search: Look up any player's career statistics and current rank to see who you are up against.
Daily Store Tracker: Check your rotating Valorant daily store and current offers without even having to boot up the heavy game client.
Discord Rich Presence (RPC): Automatically broadcast your live Valorant status, current map, party size, and score directly to your Discord profile to let your friends know when you're in a match.
Built For Performance
SkyVal is meticulously engineered for maximum performance and a minimal footprint. Built on a modern tech stack featuring Electron, React 18, Vite, and Zustand, the app is incredibly lightweight. By leveraging @tanstack/react-query for aggressive background caching and intelligent API chunking, SkyVal prevents rate-limiting and ensures that your data loads instantly—meaning your PC's resources stay dedicated to keeping your frames high in-game.

Experience Valorant tracking done right. Download the latest version of SkyVal today and take control of your climb!
