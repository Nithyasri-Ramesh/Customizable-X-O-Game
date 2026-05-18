# 🌌 XO Arena — Neon Tic-Tac-Toe (Ultimate Edition)

A premium, modern arcade twist on the classic Tic-Tac-Toe game engine. Built entirely using lightweight, zero-dependency vanilla technologies, **XO Arena** scales the traditional $3\times3$ rules into massive $7\times7$ tactical board setups with customizable victory rules and an intelligent, multi-tiered AI manager.

![Cyberpunk Aesthetic](https://img.shields.io/badge/Aesthetic-Cyberpunk%20%2F%20Neon-00f5ff)
![Tech Stack](https://img.shields.io/badge/Tech%20Stack-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-yellow)
![Dependencies](https://img.shields.io/badge/Dependencies-Zero%20(None)-green)

---

## 🎮 Game Modes & Rules

* **👥 2 Player Offline (Pass & Play):** Compete head-to-head locally with dynamically tracked individual player scoring.
* **🤖 Vs AI:** Play solo against a simulated computer brain.
* **🎛️ Dynamic Board Sizing:** Instantly switch layouts ranging from classic **$3\times3$** up to macro **$7\times7$** layouts.
* **⚡ Custom Win Conditions:** Modify tactical depth by sliding or spinning the rule configuration. Require **3, 4, 5, 6, or 7** consecutive items matched in a straight line or diagonal vector to seal a victory.

---

## 🧠 AI Brain Architecture

The artificial intelligence engine employs an advanced analytical setup that balances performance and human-like errors across four different tiers:

1.  **🟢 Easy:** Operates primarily on randomized position generation ($75\%$ random probability vector), mimicking a forgetful novice player.
2.  **🟡 Medium:** Actively checks for immediate single-move win paths or defensive blocks. If no immediate hazard is found, it relies on a lower-weight randomized node logic.
3.  **🟠 Hard:** Implements an advanced turn-evaluation workflow backed by a multi-move lookahead. Uses strategic evaluation matrix rules prioritizing board center tracking to maintain pressure.
4.  **🔴 Super Hard (Deep Quantum Brain):** Combines an alpha-beta pruned **Minimax depth tree** (supporting up to 10 lookahead cycles on smaller layouts) with static heuristic proximity valuation models. It operates with zero-error analytical precision.

---

## 🎨 Premium Visuals & Audio Engineering

* **Zero-Asset Audio Synthesizer:** Built completely on a native inline **Web Audio API context module**. Generates hardware-synthesized sound waves (sine, square, sawtooth, and oscillator frequencies) for placement clicks, victory chords, and draw buzzes without loading a single audio file.
* **Viewport Bounded Layout Architecture:** Custom responsive viewport layout engines enforce tight square canvas guidelines (`max-width: 560px` with fluid column configurations). Scales fluidly down to vertical mobile viewports using advanced CSS typography limits (`clamp()`).
* **Persistent Storage Log:** Interfaces directly with browser `localStorage` variables to maintain a structured, cross-session local history feed tracking your win streaks, layout history, and chosen parameters.
* **Celebration Particle Physics:** Fires a standalone, hardware-accelerated HTML5 `<canvas>` custom confetti particle animation loop calculation following victory triggers.

---

## 🚀 Installation & Local Execution

Since this entire game ecosystem is self-contained within a **single-file design template**, setup takes less than 5 seconds:

1. Clone or download this repository.
2. Open the `index.html` file directly in any modern, standard web browser (Chrome, Safari, Edge, Firefox).
3. Select your constraints, configure custom string symbols (e.g., emojis or characters), and click **⚡ LAUNCH GAME**.

