# Father Wounds App — Depths to Heights

**A mobile-first, offline healing companion** for those carrying wounds from absent, abusive, or distant fathers. Encounter God as **Abba Father** through Scripture, reflection, and gentle audio affirmations.

- **Website:** https://depthstoheights.org  
- **Email:** depthstoheights@gmail.com  
- **Donate:** https://www.paypal.com/donate/?hosted_button_id=8GRE7B8C3TP2U  
- **Creator:** Made by Justin (Depths to Heights)

---

## Features

- **Daily Father’s Blessing**: A curated Scripture each day expressing the Father’s heart. Save favorites and add notes.
- **7-Day Abba Father Devotional**: A guided journey (Scripture, reflection, prayer) with progress tracker.
- **Lie → Truth Reflections**: Journal “My earthly father said ___, but God says ___.” Edit, delete, export, or copy all entries.
- **Audio Affirmations**: Device voice reads short truths paired with Scripture (SpeechSynthesis). Choose voice and pace.
- **Crisis Support**: A gentle grounding exercise and clear crisis message.
- **Resources**: Scripture list, helpful practices, and quick links.
- **Background Music**: Subtle ambient pad with a one-tap toggle.
- **LocalStorage**: All data stays on the device (no accounts/servers).

---

## Installation

1. **Download** the single file `index.html`.
2. **Open** it in any modern browser (Chrome, Edge, Safari, Firefox).
3. **Install to phone** (optional):
   - **iPhone (Safari):** Share → *Add to Home Screen*
   - **Android (Chrome):** Menu ⋮ → *Add to Home Screen*

> Works fully **offline** once opened (no network required).

---

## Usage

- **Home**: Navigate to Blessings, Devotional, Reflections, and Affirmations.
- **Blessings**: Read today’s verse, save as favorite, and jot a quick note.
- **Devotional**: Tap a day to read; write a short reflection; press *Mark as Done* (progress bar updates).
- **Reflections**: Enter “Lie” and “Truth,” add Scripture, then **Save**. Edit or Delete later. Use **Download .txt** or **Copy**.
- **Affirmations**: Select a device voice and rate, then **Play All** or **Play** any item. Use headphones if possible.
- **Crisis**: Use the 4–7–8 breathing timer and read the crisis support note.
- **Resources**: Scripture list, practices, website, email, and **Donate via PayPal**.

---

## Technology

- **Single-file**: Pure **HTML + CSS + JavaScript** (no frameworks).
- **Storage**: Browser **LocalStorage**.
- **Audio**: Web Audio API (ambient background), SpeechSynthesis (affirmations).

---

## Privacy

All data (journal, notes, settings) remains **on your device**. No tracking, no accounts.

---

## Support

- Website: https://depthstoheights.org  
- Email: [depthstoheights@gmail.com](mailto:depthstoheights@gmail.com)  
- Donate: https://www.paypal.com/donate/?hosted_button_id=8GRE7B8C3TP2U

---

## License

Copyright © 2025 **Depths to Heights**
- You may use and share this app for personal and ministry purposes.
- Please keep creator credit intact. No resale.

---

## Testing Checklist

- [x] **Single HTML file** only
- [x] **No alerts/confirm/prompts**
- [x] Bottom nav always visible (Home, Crisis, Resources, Info, About)
- [x] Info & About modals open/close
- [x] **PayPal button** opens correct link
- [x] Background music toggle works
- [x] All navigation buttons work (Home, Blessings, Devotional, Reflections, Affirmations, Crisis, Resources)
- [x] Devotional progress saves/updates
- [x] Reflections save/edit/delete/export/copy
- [x] Favorites & notes save in Blessings
- [x] Audio affirmations play (where SpeechSynthesis is supported)
- [x] Mobile-responsive on iOS/Android
- [x] Crisis support message is generic/global
