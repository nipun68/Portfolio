# ⚡ NIPUN KALRA — PORTFOLIO

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-LIVE-0F35FF?style=for-the-badge&logoColor=white" alt="Live Badge" />
  <img src="https://img.shields.io/badge/ARCHITECTURE-NEO--BRUTALIST-F4EFE6?style=for-the-badge&color=051024" alt="Brutalist Badge" />
  <img src="https://img.shields.io/badge/FOCUS-AI%20%2F%20ML%20%26%20SYSTEMS-012CEB?style=for-the-badge" alt="Focus Badge" />
  <img src="https://img.shields.io/badge/TECH-GSAP%20%7C%20LENIS%20%7C%20TONE.JS-FFCC00?style=for-the-badge&color=0B0B0B" alt="Tech Stack" />
</p>

<p align="center">
  <strong>An immersive, skeuomorphic & neo-brutalist personal portfolio engineered from first principles.</strong><br/>
  Featuring physics-driven typography, authentic Delhi Metro transit simulation, interactive AST execution engines, and audio-reactive micro-interactions.
</p>

---

## 🌐 Live Preview

- **Live URL**: [https://nipun68.github.io/Portfolio/](https://nipun68.github.io/Portfolio/)
- **Repository**: [https://github.com/nipun68/Portfolio](https://github.com/nipun68/Portfolio)

---

## 🧭 System Architecture & Sections

```
┌────────────────────────────────────────────────────────────────────────┐
│                          PORTFOLIO ARCHITECTURE                        │
├────────────┬─────────────────────────────┬─────────────────────────────┤
│ SECTION    │ COMPONENT                   │ INTERACTION / HIGHLIGHT     │
├────────────┼─────────────────────────────┼─────────────────────────────┤
│ 01 · HERO   │ 3D Kinetic Monogram (nK)    │ Multi-layer mouse parallax, │
│            │                             │ signature royal blue stage  │
├────────────┼─────────────────────────────┼─────────────────────────────┤
│ 02 · ORIGIN │ Realist Diary & Notebook    │ Skeuomorphic paper texture, │
│            │                             │ polaroid memory frames      │
├────────────┼─────────────────────────────┼─────────────────────────────┤
│ 03 · CARDS │ Physics Stack Cards         │ Spring cards with expand-   │
│            │                             │ to-inspect architecture     │
├────────────┼─────────────────────────────┼─────────────────────────────┤
│ 04 · TRANSIT│ Delhi Metro "Best Work" Hub │ Authentic blue sliding door │
│            │                             │ splash, 11-node route board │
├────────────┼─────────────────────────────┼─────────────────────────────┤
│ 05 · VISUAL│ Dynamic Image Trail Canvas  │ Velocity-based cursor trail │
│            │                             │ physics with UI archives    │
├────────────┼─────────────────────────────┼─────────────────────────────┤
│ 06 · SYSTEM│ Live HUD Ribbon & Terminal  │ Scroll tracking, live IST,  │
│            │                             │ Tone.js sound synthesizer   │
└────────────┴─────────────────────────────┴─────────────────────────────┘
```

---

## 🚇 Section Deep-Dives

### 01. Hero — 3D Typography & Kinetic Lighting
- **Signature Royal Blue Stage (`#0F35FF`)**: Luminous backdrop with subtle, cursor-driven radial lighting.
- **Dynamic 3D Extrusion**: Procedural multi-layer text-shadow projection reacting dynamically to mouse coordinates with real-time inertia.
- **Career Progression Annotations**:
  - `Started As`: **Competitive Programmer**
  - `Became`: **Machine Learning Engineer**
  - `Currently`: **AI/ML Developer**
- **Sound Synthesis**: Audio toggles powered by **Tone.js** synth generators for haptic audio feedback.

### 02. Origin — Skeuomorphic Diary
- Authentic spiral notebook with realistic paper crease shadows, paper fibers, and taped archival tickets.
- Raw narrative chronicling the journey from writing C++ algorithms to training deep neural architectures.

### 03. Projects — Brutalist Interactive Stack
- Card stack featuring tactile drag-and-click physics.
- Project cards expand to reveal granular system breakdowns, benchmark metrics, and links.

### 04. Best Work — Delhi Metro Transit Simulation
- **Welcome Doors Splash (`दिल्ली मेट्रो में आपका स्वागत है`)**:
  - Authentic Delhi Metro blue sliding doors with heavy mechanical easing.
  - Interactive **ENTER METRO** button with audio chime.
- **Mounted Billboard & Carriage**:
  - **Station 0 (North Campus)**: Instruction manual with swipe badges and navigation guide.
  - **Stations 1–5**: Project showcases with yellow-and-black hazard caution badge: `STEP OUT FOR DISSECTION <->`.
  - **11-Node Route Map Board**: Tilted route map featuring 6 major project stations (`ORIGIN`, `CHESS BLUNDER`, `DUELTACTIX AI`, `PLACEMENT ML`, `CODELENS`, `AI LAB`) and 5 authentic Delhi Metro interchange stations (`VISHWA-VIDYALAYA`, `GTB NAGAR`, `KASHMERE GATE`, `RAJIV CHOWK`, `MANDI HOUSE`).
  - **Full Case Study Dissection**: Clicking any project billboard or hazard badge slides open a high-density, brutalist case-study modal with architecture diagrams and live metrics.

### 05. Visuals & Archive
- Velocity-sensitive HTML5 canvas that spawns project snapshots along cursor motion trails with natural decay and scale transforms.

---

## 🛠 Featured Engineering Projects

| Project | Domain | Architecture & Tech | Highlights |
| :--- | :--- | :--- | :--- |
| **[CodeLens](https://github.com/nipun68/CodeLens)** | AST Engine & VM | Vanilla ES2020, Acorn Parser, Canvas | Deterministic AST execution visualizer, Zero `eval()`, 6-Tier Asymptotic Big-O Heatmap, Call Stack Inspector. |
| **[Chess Blunder Engine](https://github.com/nipun68/chess-blunder-system)** | AI & Search Systems | Stockfish 16, Python, Flask | Real-time tactical mistake classification, evaluation curve, <120ms engine latency. |
| **[DuelTactix AI](https://github.com/nipun68)** | Game Theory & AI | Minimax, Alpha-Beta, Bitboards | Full lookahead adversarial agent with zero-sum game trees, depth 8 optimization. |
| **[Campus Placement ML](https://github.com/nipun68/campus-placement)** | Predictive Analytics | Scikit-Learn, Random Forest, EDA | Recruitment forecasting model trained on academic data; 94.6% classification accuracy. |
| **AI Systems Lab** | Deep Learning Research | PyTorch, NumPy, Python | Algorithmic implementations, LeetCode (150+ solved), Stanford DeepLearning.AI credentials. |

---

## 💻 Tech Stack & Dependencies

- **Structure**: Semantic HTML5 (Modular & Accessible)
- **Styling**: Pure CSS3 (`styles.css`) + Tailwind CSS (Utility classes) + Custom Neo-Brutalist Design Tokens
- **Animations & Physics**:
  - [GSAP (GreenSock) 3.12](https://greensock.com/gsap/) (Timelines, ScrollTrigger, Draggable)
  - [Lenis](https://github.com/studio-freight/lenis) (Smooth Momentum Scrolling)
- **Audio Synthesis**:
  - [Tone.js](https://tonejs.github.io/) (Web Audio API Synthesizers & Chimes)
- **Typography**:
  - `Dr Sugiyama`, `Schoolbell`, `Gloria Hallelujah` (Handwritten & Signatures)
  - `Inter`, `DM Mono`, `Open Sauce One`, `Bebas Neue`, `Teko`, `Lilita One`

---

## 📂 Project Structure

```bash
Portfolio/
├── index.html       # Primary production entry point
├── portfolio.html   # Standalone portfolio view
├── styles.css       # Complete neo-brutalist stylesheet & animations
├── script.js        # Core interaction engine (GSAP, Lenis, Metro, Audio)
├── images/          # Production UI mockups and snapshots
│   ├── codelens.jpg
│   ├── campus_placement.jpg
│   ├── chess_blunder.png
│   └── image.png
└── README.md        # Documentation
```

---

## 🚀 Running Locally

Clone the repository and serve using any static web server:

```bash
# Clone the repository
git clone https://github.com/nipun68/Portfolio.git

# Navigate to project folder
cd Portfolio

# Run using a local development server
# Python:
python -m http.server 8080

# Or Node.js (npx):
npx serve .
```

Open `http://localhost:8080/` in your browser.

---

## 👤 Developer Profile

**Nipun Kalra**  
- 🎓 **B.E. Computer Science**, Chitkara University (CGPA: 8.8 / 10)
- 💻 **GitHub**: [@nipun68](https://github.com/nipun68)
- 💼 **LinkedIn**: [Nipun Kalra](https://www.linkedin.com/in/nipun-kalra-22340b317/)
- 🧠 **LeetCode**: [@nipun1236](https://leetcode.com/u/nipun1236/)
- 📬 **Email**: [kalranipun68@gmail.com](mailto:kalranipun68@gmail.com)

---

<p align="center">
  <sub>Built in New Delhi • Powered by Caffeine & First Principles • &copy; 2026 Nipun Kalra</sub>
</p>
