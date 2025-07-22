# 🌊 Dijk van een Wijf — Virtual AI Tour Guide

**Live Demo:** [https://ALYTIC5.github.io/dijk-tour/](https://ALYTIC5.github.io/dijk-tour/)  
**Scan QR Code to Visit on Mobile**  
*(Optimized for phone-first experience)*

---

## 🧭 Project Description

This web experience transforms the Wadden Sea into an **AI-powered conversational tour guide**, speaking through the voice of the sculpture **“Dijk van een Wijf.”**  

Users select their preferred language — **English**, **Dutch**, or **Friesian** — and are immediately immersed in a sound-rich environment where the **sea itself tells its story**.

The app is intended for **visitors and locals** exploring the coast, offering poetic insights, historical references, and ecological reflections through natural language conversation.

---

## ✨ Core Features

- 🗣️ **Conversational AI** powered by ElevenLabs' widget (voice interface).
- 🌐 **Multilingual tour options**: English 🇬🇧, Dutch 🇳🇱, Friesian 🐚.
- 🎵 **Seasonal soundscapes** loop in the background (Lente → Zommer → Herfst → Winter).
- 📱 **Mobile-first layout** that adapts perfectly to smaller screens.
- 🎨 **Brand-aligned UI**:
  - Soft corners
  - Semi-transparent glassmorphic interface
  - Orange-accented buttons (`#EE7440`)
  - Brand font: **Circular Std**
- 🔇 **Mute toggle** styled to match the overall aesthetic.
- 🖼️ Integrated **logo and texture** from brand identity documents.

---

## 🧱 Tech Stack

| Feature               | Technology                            |
|----------------------|----------------------------------------|
| Conversational Agent | [ElevenLabs Convai Widget](https://elevenlabs.io) |
| Hosting              | [GitHub Pages](https://pages.github.com/) |
| Language             | HTML5 + CSS3 + Vanilla JavaScript      |
| Audio Control        | HTML `<audio>` + JavaScript playlist   |
| Font & Design        | Circular Std (loaded via local system or Google fallback) |

---

## 📁 File Overview

| File                          | Purpose                                     |
|-------------------------------|---------------------------------------------|
| `index.html`                  | Main web page and all embedded logic       |
| `background.jpg`              | Branded background image                   |
| `Dijk_van_een_Wijf_Logo.png`  | Wordmark/logo used top-right               |
| `*.mp3`                       | Seasonal soundscapes (looped in order)     |

---

## 🧠 Brainstormed Improvements

Here are ways to further polish and professionalize the project:

### UI/UX Polish
- [ ] **Fade-in transitions** on audio and widget load (for smoother experience)
- [ ] **Animated background particles** (e.g., sea mist, wind) for ambient life
- [ ] Add **loading state or spinner** when widget is loading
- [ ] Replace buttons with **icon-enhanced** pill-shaped controls (🔊/🔇, 🌍)
- [ ] **Dark/light mode toggle** for better daytime/nighttime viewing

### Accessibility
- [ ] Add **ARIA labels** for screen reader compatibility
- [ ] Include **keyboard navigation** for all controls
- [ ] Support **subtitles or captions** for spoken responses

### Content & Engagement
- [ ] Connect ElevenLabs widget to **custom backend agent** trained on Wadden Sea and “Dijk van een Wijf” material for deeper interaction
- [ ] Add a **visual map overlay** showing location-based storytelling
- [ ] Include **fact cards or images** that pop up based on user input (e.g. tides, wildlife)

### Technical
- [ ] **Service Worker** for offline caching (PWA support)
- [ ] Add **meta tags** for SEO and social media previews
- [ ] Compress and optimize **audio** and **image assets**
- [ ] Bundle JS into modules and separate concerns into files

### Hosting & Distribution
- [ ] Register a **custom domain** (e.g. `tour.dijkvaneenwijf.nl`)
- [ ] Add **Analytics** to understand user behavior
- [ ] Include a **downloadable offline version** (USB/exhibition kiosk mode)

---

## 🛠 How to Run Locally

1. Clone the repository  
   `git clone https://github.com/ALYTIC5/dijk-tour.git`

2. Navigate into the directory  
   `cd dijk-tour`

3. Open `index.html` in your browser  
   (No server required — static site)

4. Or use VSCode’s Live Server extension
