# Iotricity-Season3-Portal
Official registration uplink for Iotricity Season 3. Features a cinematic terminal boot sequence, neural UI effects, and automated Google Sheets data synchronization.

# ⚡ IOTRICITY SEASON 03 | Official Uplink Portal

![Status](https://img.shields.io/badge/Status-Live-00f2ff?style=for-the-badge)
![Tech](https://img.shields.io/badge/Tech-HTML5_/_Tailwind_/_JS-orange?style=for-the-badge)
![Database](https://img.shields.io/badge/Database-Google_Sheets-green?style=for-the-badge)

> **The digital gateway for SCEE's flagship Hardware Hackathon.** > Featuring a cinematic 15-second terminal boot sequence, neural UI effects, and automated cloud synchronization.



## 🛠️ System Architecture

This portal is designed to be a lightweight, serverless solution for high-traffic event registration.

- **Cinematic Loader:** A custom 15-second "Cyber-Terminal" sequence that simulates system diagnostics and module injection.
- **Dynamic Idea Matrix:** A responsive, searchable grid featuring 30+ industrial IoT project tracks.
- **Neural UI:** Interactive "spotlight" cursor effect and smooth intersection-observer reveal animations.
- **Google Sheets Backend:** Utilizes Google Apps Script (GAS) as a serverless API to handle POST requests and log participant data in real-time.
- **Custom Typography:** Integrated with **Doto** and **JetBrains Mono** for a specialized technical aesthetic.

## 🚀 Quick Start

### 1. Database Setup (Google Sheets)
1. Create a Google Sheet with headers: `Timestamp`, `Lead_Name`, `Team_Name`, `Email`, `Project_Idea`, `Project_Link`.
2. Go to **Extensions > Apps Script** and deploy the `doPost` function.
3. **Important:** Set deployment access to **"Anyone"**.
4. Copy your **Web App URL**.

### 2. Local Configuration
1. Clone the repository.
2. Open `index.html`.
3. Locate the `const SCRIPT_URL` and paste your Web App URL there.

### 3. Deployment
Simply host the `index.html` file via  **Vercel**.



## 📂 Project Structure
```text
├── index.html          # Main cinematic portal & logic
├── README.md           # Documentation
└── (Legacy)            # Formspree/WhatsApp versions (Optional)
