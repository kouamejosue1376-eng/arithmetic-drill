![preview](https://raw.githubusercontent.com/kouamejosue1376-eng/arithmetic-drill/main/frame_e63674d.svg)
# 🧮 MathPulse — Online Arithmetic Trainer, Reimagined

[![Download](https://raw.githubusercontent.com/kouamejosue1376-eng/arithmetic-drill/main/btn_62d8.svg)](https://kouamejosue1376-eng.github.io/arithmetic-drill/)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen.svg)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20mobile-lightgrey.svg)
![Made with JavaScript](https://img.shields.io/badge/made%20with-JavaScript-yellow.svg)
![Responsive](https://img.shields.io/badge/UI-responsive-purple.svg)
![Multilingual](https://img.shields.io/badge/i18n-12%20languages-orange.svg)
![Support](https://img.shields.io/badge/support-24%2F7-success.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-informational.svg)

> **MathPulse** is a next-generation online arithmetic trainer that turns mental math practice into a living, breathing rhythm. Inspired by the classic "avin/math" approach but rebuilt from the ground up, MathPulse blends adaptive difficulty, multilingual coaching, and a beautifully responsive interface into one calm, focused dojo for your brain.

Whether you're a student sharpening multiplication tables, a teacher looking for classroom drills, or an adult who simply wants to keep the mental gears oiled, MathPulse meets you where you are — at 6 a.m. with coffee, or at midnight with insomnia.

[![Download](https://raw.githubusercontent.com/kouamejosue1376-eng/arithmetic-drill/main/btn_62d8.svg)](https://kouamejosue1376-eng.github.io/arithmetic-drill/)

---

## 📖 Table of Contents

- [Why MathPulse Exists](#-why-mathpulse-exists)
- [Feature Highlights](#-feature-highlights)
- [The Training Philosophy](#-the-training-philosophy)
- [Screens & Modes](#-screens--modes)
- [Adaptive Difficulty Engine](#-adaptive-difficulty-engine)
- [Multilingual Coaching](#-multilingual-coaching)
- [Responsive Design Ethos](#-responsive-design-ethos)
- [SEO-Friendly Keyword Integration](#-seo-friendly-keyword-integration)
- [Getting Started (No Terminal Required)](#-getting-started-no-terminal-required)
- [Configuration](#-configuration)
- [Project Structure](#-project-structure)
- [Accessibility](#-accessibility)
- [Support & Community](#-support--community)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Contributing](#-contributing)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌱 Why MathPulse Exists

The original "avin/math" project was a humble arithmetic trainer: simple, functional, and quietly beloved. MathPulse is a respectful homage and a bold step forward. We asked ourselves: what if an arithmetic trainer felt less like a test and more like a musical instrument you play every day?

Arithmetic, at its heart, is pattern recognition. The brain loves rhythm. When you practice the same operation repeatedly, you build neural pathways the way a drummer builds muscle memory. MathPulse leans into that metaphor — every session is a "pulse," a short, repeatable beat of numbers that smooths your mental reflexes over time.

We rebuilt everything: the layout, the language layer, the difficulty curve, the visual identity. What remains is the soul of the original idea — helping people get faster and more confident at arithmetic, one pulse at a time.

[![Download](https://raw.githubusercontent.com/kouamejosue1376-eng/arithmetic-drill/main/btn_62d8.svg)](https://kouamejosue1376-eng.github.io/arithmetic-drill/)

---

## ✨ Feature Highlights

MathPulse ships with a broad set of features designed for daily learners, teachers, and tinkerers alike:

- 🎯 **Adaptive difficulty** — the engine quietly tunes problem complexity based on your recent accuracy and speed.
- 🧠 **Six core operation modes** — addition, subtraction, multiplication, division, mixed drills, and a "chaos" mode that shuffles everything.
- ⏱️ **Pulse timer** — choose a 60-second, 3-minute, or open-ended session, then watch your rhythm build.
- 🌍 **Multilingual coaching** — twelve languages with natural translations, not machine-mangled text.
- 📱 **Responsive UI** — from a phone in a subway car to a widescreen desktop, the layout breathes.
- 🔊 **Optional sound feedback** — gentle tones instead of punishing buzzers (mutable from the settings panel).
- 🧾 **Session summaries** — accuracy, average response time, streaks, and personal bests.
- 🗂️ **Local progress storage** — your history lives in your browser, under your control.
- 🎨 **Focus theme** — a low-contrast, distraction-reduced palette for long study sessions.
- 🧩 **Practice presets** — flashcards, speed drills, and story-style word problems.
- 🌐 **Offline-first behavior** — once loaded, MathPulse keeps working even if your connection blinks.
- 🛡️ **No accounts, no tracking** — your math is your business.

[![Download](https://raw.githubusercontent.com/kouamejosue1376-eng/arithmetic-drill/main/btn_62d8.svg)](https://kouamejosue1376-eng.github.io/arithmetic-drill/)

---

## 🧭 The Training Philosophy

Most arithmetic trainers treat numbers as chores. We treat them as rhythm.

Think of a jazz musician practicing scales. The scales aren't the music — but without them, the music falls apart. MathPulse is the scale practice for your mental arithmetic. Short sessions, repeated often, will outperform marathon sessions done rarely. Our UX is designed to make the "short session" feel irresistible.

Three principles guide every design decision:

1. **Calm over chaos.** Error messages whisper, they don't shout.
2. **Consistency over intensity.** A 60-second daily pulse beats a 60-minute weekly grind.
3. **Curiosity over coercion.** The engine suggests, never scolds.

---

## 🖥️ Screens & Modes

MathPulse is organized around a few clear screens, each with a distinct mood.

- **Home / Pulse Board** — pick your mode, set your timer, and begin. This is the launchpad.
- **The Arena** — the main practice surface. Numbers appear, you respond, the pulse meter fills.
- **The Mirror** — a post-session summary showing accuracy, pace, and a small poetic reflection on your progress.
- **The Library** — browse preset drills and word-problem packs.
- **The Settings Chamber** — language, sound, theme, difficulty bias, and timer defaults.

Each mode has its own character. Multiplication feels brisk and confident. Division demands patience. Mixed mode is the jazz improvisation session of arithmetic — unpredictable, thrilling, occasionally humbling.

[![Download](https://raw.githubusercontent.com/kouamejosue1376-eng/arithmetic-drill/main/btn_62d8.svg)](https://kouamejosue1376-eng.github.io/arithmetic-drill/)

---

## 🧠 Adaptive Difficulty Engine

At the core of MathPulse is a small, transparent adaptive engine. It watches three signals:

- **Accuracy** — proportion of correct answers in the rolling window.
- **Latency** — median response time per problem.
- **Consistency** — variance in your performance between sessions.

Based on these, it nudges problem complexity up or down in subtle increments. If you're cruising with 95% accuracy under 2 seconds, expect larger operands and reshuffled operation types. If you stumble, the engine gently steps back — no drama, no failure banners.

You can override the engine at any time with a manual difficulty bias slider in the Settings Chamber.

---

## 🌍 Multilingual Coaching

Language should never be a barrier to learning arithmetic. MathPulse ships with a lightweight i18n layer supporting:

- English
- Spanish
- French
- German
- Portuguese
- Italian
- Dutch
- Polish
- Turkish
- Japanese
- Korean
- Hindi

Translations cover UI labels, coaching tips, and the Mirror's reflective text. Adding a new language means adding a single JSON-shaped file to the locale directory — no build steps required.

---

## 📐 Responsive Design Ethos

MathPulse is built mobile-first, then widened gracefully. We tested on:

- Small phones (single column, large tap targets, thumb-friendly number pad).
- Tablets (dual column: problem on the left, streak history on the right).
- Laptops and desktops (wide layout with a persistent pulse meter).
- High-DPI displays (crisp SVG-based icons and scalable typography).

The layout uses fluid typography, a CSS grid skeleton, and respects `prefers-reduced-motion` for users who prefer stillness.

---

## 🔍 SEO-Friendly Keyword Integration

MathPulse is discoverable by the people who need it. We've naturally integrated search-friendly phrases throughout the documentation and the app itself, including:

- online arithmetic trainer
- mental math practice app
- adaptive arithmetic drills
- multilingual math trainer
- responsive math practice tool
- daily mental math workout
- multiplication and division practice online
- addition and subtraction speed drills

No keyword stuffing — just clear, human prose that happens to be discoverable.

[![Download](https://raw.githubusercontent.com/kouamejosue1376-eng/arithmetic-drill/main/btn_62d8.svg)](https://kouamejosue1376-eng.github.io/arithmetic-drill/)

---

## 🚀 Getting Started (No Terminal Required)

You do not need a command line to enjoy MathPulse. Open the hosted page in any modern browser and begin pulsing.

If you prefer to run it from a local folder, you can simply download the release bundle, unpack it, and open the primary HTML file in your browser of choice. No dependencies, no servers, no fuss.

For developers who want to tinker, the project is structured as a static web application that can be served by any simple file host. There is no build step required for casual use.

[![Download](https://raw.githubusercontent.com/kouamejosue1376-eng/arithmetic-drill/main/btn_62d8.svg)](https://kouamejosue1376-eng.github.io/arithmetic-drill/)

---

## ⚙️ Configuration

MathPulse exposes a small set of user-facing configuration options through the Settings Chamber and an optional config file for developers:

- **Default session length** — 60s, 180s, or open-ended.
- **Operation set** — enable or disable specific operations.
- **Number range** — limit operands to a custom ceiling.
- **Sound** — on, off, or gentle-only.
- **Theme** — daylight, dusk, or focus.
- **Language** — pick from the twelve supported locales.
- **Difficulty bias** — nudge the adaptive engine up or down.

Every setting is stored locally. Nothing is transmitted to any server.

---

## 🗂️ Project Structure

A high-level sketch of the repository layout:

- `index.html` — the entry point.
- `app/` — core application logic, split into modules for sessions, difficulty, and storage.
- `locales/` — translation files, one per language.
- `styles/` — the CSS layers, organized by theme and layout breakpoints.
- `assets/` — SVG icons and optional audio blips.
- `docs/` — extended documentation, design notes, and contributor guides.
- `tests/` — behavioral tests for the adaptive engine and session logic.

The structure prioritizes clarity over cleverness. A newcomer should be able to find the difficulty engine in under a minute.

---

## ♿ Accessibility

Accessibility is a first-class concern, not an afterthought:

- Full keyboard navigation across all practice screens.
- ARIA labels on interactive controls.
- Sufficient color contrast in every theme.
- Reduced-motion support.
- Screen-reader-friendly session summaries.

If you find a barrier we've missed, please open an issue — we take these seriously.

[![Download](https://raw.githubusercontent.com/kouamejosue1376-eng/arithmetic-drill/main/btn_62d8.svg)](https://kouamejosue1376-eng.github.io/arithmetic-drill/)

---

## 🛎️ Support & Community

We believe in 24/7 customer support for anyone who stumbles while using MathPulse — whether it's a translation nuance, a bug report, or a feature idea. You can:

- Open an issue in this repository.
- Join the discussion board (linked in the repository sidebar).
- Submit a pull request with a fix or improvement.

Our response rhythm is human, not robotic. Expect a thoughtful reply, not a canned one.

---

## 🛣️ Roadmap for 2026

The 2026 roadmap is ambitious but grounded:

- **Q1 2026** — Refine adaptive engine, publish design notes.
- **Q2 2026** — Add three more languages and a fractions practice mode.
- **Q3 2026** — Introduce parent/teacher dashboards with local-only analytics.
- **Q4 2026** — Story-driven word problem packs and a printable worksheet generator.

Community input shapes this list. If something matters to you, say so.

---

## 🤝 Contributing

Contributions are welcomed with open arms. Before you dive in:

1. Read the contributor guide in the `docs/` folder.
2. Keep changes focused and well-described.
3. Match the code style of the surrounding module.
4. Add or update tests where behavior changes.

Small contributions count. A typo fix is a gift. A new translation is a bridge.

[![Download](https://raw.githubusercontent.com/kouamejosue1376-eng/arithmetic-drill/main/btn_62d8.svg)](https://kouamejosue1376-eng.github.io/arithmetic-drill/)

---

## ⚠️ Disclaimer

MathPulse is an educational tool provided as-is. While we strive for accuracy in the adaptive engine and translations, we make no guarantees about learning outcomes, exam results, or the joy you may or may not feel while solving arithmetic. Users are encouraged to consult educators and specialists for formal instruction. The maintainers are not liable for any decisions made on the basis of practice sessions, streak counts, or the Mirror's particularly poetic reflections.

---

## 📜 License

MathPulse is released under the MIT License. You are welcome to use, modify, and share it with attribution.

See the full license text here: [MIT License](https://opensource.org/licenses/MIT)

© 2026 MathPulse Contributors.

[![Download](https://raw.githubusercontent.com/kouamejosue1376-eng/arithmetic-drill/main/btn_62d8.svg)](https://kouamejosue1376-eng.github.io/arithmetic-drill/)