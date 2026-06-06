# 🌌 Celestial Portal — Cosmic Tarot & Angelic Sanctuary

A premium, interactive web application designed to help beginners and experienced tarot readers cultivate intuition, learn card meanings, and track spiritual readings with modern design aesthetics.

This application is fully self-contained (HTML, CSS, JS), requires zero external downloads or installations, and runs locally in any web browser.

---

## 🌟 Features

### 1. 🔮 Interactive Spread Room
* **Intention Focus:** State your question to ground your energy before dealing.
* **Staggered dealing:** Beautiful dealing physics and 3D card flipping animations.
* **Upright & Reversed Readings:** Cards have a 25% chance of being dealt reversed. Visual graphics automatically rotate, and the corresponding inverted interpretation is presented.
* **Three Layouts:**
  * **Single Card Focus:** Daily advice or simple yes/no guidance.
  * **Three-Card Progression:** Past, Present, and Future context.
  * **Five-Card Elements:** Spirit, Fire (Action), Water (Emotion), Air (Intellect), and Earth (Stability) spreads.

### 2. 📖 Cosmic Codex (Card Encyclopedia)
* **Comprehensive Meanings:** Complete definitions for all 75 custom cards (25 Major Arcana and 50 Minor Arcana divided into Stars, Moons, Comets, Worlds, and Angels).
* **Keywords & Advice:** Every card has 3 primary keywords and actionable advice tailored for Love & Relationships and Career & Growth.
* **Search & Filters:** Search for specific terms, elements, or filter by suit.

### 3. 🕊️ Angelic Sanctuary
* **Grounding Guide:** An interactive Box Breathing bubble (4s Inhale, 4s Hold, 4s Exhale, 4s Hold) to calm the mind before starting a reading.
* **Ethereal Guidance:** Draw a daily angelic energy card for spiritual comfort.
* **Angel Numbers:** Generate your daily synchronicity number and read its message.

### 4. 📝 Reader's Journal
* **Local Storage Tracking:** Readings are automatically saved directly inside your browser's local storage.
* **Reflection Logs:** Review previous questions, card draws, dates, and input custom reflection notes as situations develop.

### 5. 🎓 Beginner's Academy
* **Empowered Questions:** Learn to phrase open-ended questions that focus on self-growth rather than passive prediction.
* **Minor Arcana Mechanics:** Understand elements, suits, and reversed card dynamics.
* **Intuition Building:** Quick tips to help you read imagery before searching for books.

---

## 🛠️ Architecture & Aesthetics

* **Self-Contained SVGs:** Since the codebase doesn't rely on local images for cards, the front and back of each card are rendered dynamically using inline SVGs and glowing HSL CSS gradients.
* **Synthesized Audio:** Mystical chimes, cards sliding, and deep breathing hums are synthesized entirely in real-time using the **Web Audio API**. Enable sound in the header control to hear them.
* **Premium Theme:** Dark, glassmorphic layout styled with elegant `Cinzel` (serif headings) and clean `Outfit` (sans-serif body text) typography.

---

## 🚀 How to Run

1. Clone or download this repository.
2. Locate the [index.html](file:///c:/Users/dhudz/Documents/cosmicoraclecard/index.html) file in the root directory.
3. Double-click the file to open it in Google Chrome, Microsoft Edge, Mozilla Firefox, or Apple Safari.
4. Click **🔊 Sound Off** in the header to activate chimes and breathing guides.
