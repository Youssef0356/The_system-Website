# The System — Official Game Website & Tactical Dossier

Official landing page and promotional portal for **The System: Bluffing Card Game**, a high-stakes social deduction party card game for 2–8 players developed by **The 356 Company / The 356 Developper**.

[![Google Play](https://img.shields.io/badge/Google_Play-The_System-34A853?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.the356company.the_system)
[![itch.io](https://img.shields.io/badge/itch.io-The_System_Card_Game-FA5C5C?style=for-the-badge&logo=itch.io&logoColor=white)](https://youssef356.itch.io/the-system-card-game)

---

## 🕶️ Game Overview

- **Genre:** Social Deduction, Bluffing Card Game, Party Game
- **Players:** 2 to 8 Operatives (Local Pass-and-Play) or 1v1 Online with ELO
- **Solo Mode:** Offline vs Smart AI bots with adjustable difficulty
- **Inspiration:** The traditional Tunisian card game *El Mekina*
- **Tagline:** *"A GAME OF DECEPTION."* // *"TRUST NO ONE."*

---

## 🚀 Key Website Features

1. **Neo-Brutalist Spy Dossier Aesthetic**: Direct implementation of the official design bible (halftone dot patterns, warm cream paper `#F7F2E7`, ink black outlines, signal yellow `#F5C542`, red rubber stamps, and manila folders).
2. **Official 1080p Gameplay Trailer**: Embedded HTML5 custom video player showcasing the 15-second launch trailer (`the_system_trailer.mp4`) with poster frame and custom playback controls.
3. **Interactive 7-Operative Identity Dossier**: High-resolution character artwork (Businessman, Taxman, Assassin, Marshal, Detective, Politician, Thief) with costs, abilities, and tactical counters.
4. **Authentic In-Game Captures**: Gameplay board, card peeking reveals, role claim dialogs, protocol resolution ("LIAR!" alert countdown), pass-and-play setup, and field manual.
5. **SEO & AI Search Discoverability**:
   - Comprehensive **Schema.org** JSON-LD (`VideoGame`, `SoftwareApplication`, `VideoObject`, `FAQPage`, `Organization`).
   - Open Graph (Facebook/WhatsApp/Discord) & Twitter Cards.
   - `sitemap.xml` & `robots.txt` granting explicit permission to all major search and AI crawlers (`Googlebot`, `GPTBot`, `PerplexityBot`, `ClaudeBot`).
6. **High-Converting Store Redirects**:
   - Direct link to [Google Play Store](https://play.google.com/store/apps/details?id=com.the356company.the_system)
   - Direct link to [itch.io](https://youssef356.itch.io/the-system-card-game)
   - Sticky mobile install bar for smartphone visitors
   - Fast redirect handling via `?redirect=playstore` or `?redirect=itch`
7. **Monetization & Legal Compliance**: Preserved AdMob `app-ads.txt` and full COPPA / ESRB Privacy Policy.

---

## 📁 Repository Structure

```
The_system-Website/
├── index.html                  # Main responsive landing page
├── robots.txt                  # Search engine and AI crawler rules
├── sitemap.xml                 # XML sitemap with video & image metadata
├── site.webmanifest            # PWA manifest
├── favicon.png                 # Web favicon
├── app-ads.txt                 # Google AdMob publisher verification
├── README.md                   # Repository documentation
└── assets/
    ├── video/
    │   ├── the_system_trailer.mp4   # 1080p game trailer video
    │   └── trailer_poster.jpg       # Video poster fallback image
    └── img/
        ├── branding/           # Logos and icons
        ├── characters/         # 7 Role illustrations & card backs (.webp & .png)
        └── screenshots/        # Real in-game captures and marketing slides
```

---

## 🌐 Deployment (GitHub Pages)

To publish on GitHub Pages:
1. Go to repository **Settings** > **Pages**.
2. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
3. Select branch **`main`** and folder **`/ (root)`**, then click **Save**.
4. The site will be live at: `https://youssef0356.github.io/The_system-Website/`

---

© 2026 The 356 Company. All rights reserved.
