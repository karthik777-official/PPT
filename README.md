# VISIONAID AI — AI-Powered Assistive Vision System
### College Innovation & Working-Model Evaluation Presentation Deck

An interactive, high-tech engineering presentation application tailored for college working-model evaluation and innovation competitions. Designed to showcase a 3D prototype of assistive smart glasses rather than a generic theoretical PowerPoint.

Live 3D Prototype Demo: [https://smart3-d-glasses.vercel.app/](https://smart3-d-glasses.vercel.app/)

---

## 🔌 100% OFFLINE PRESENTATION INSTRUCTIONS (NO WIFI / NO INTERNET)

This presentation is **100% self-contained and offline-ready**. You can take your laptop to a college auditorium, disconnect all WiFi, turn on Airplane Mode, and present smoothly without any errors.

### 🌟 2 Ways to Launch Offline:

#### Method 1: Local HTTP Server (Recommended)
1. Double-click `start.bat` (or open terminal and type `node server.js`).
2. Your browser opens to `http://localhost:3000`.
3. **Why this is best:** It runs on your computer's internal loopback (`127.0.0.1`), enabling the local **offline 3D model**, local scripts, audio simulator, and presenter timer seamlessly.

#### Method 2: Direct File Double-Click (Zero Setup)
1. In Windows File Explorer, simply double-click `index.html`.
2. It opens directly in Microsoft Edge, Google Chrome, or Firefox.
3. Every slide, graphic, audio simulation, and presenter note works immediately.

---

### 👓 How the 3D Prototype Works Offline:
- The entire 3D WebGL engine (`Three.js`, `OrbitControls`, `glassesModel.js`, `hotspots.js`) has been bundled locally in the `offline-3d-model/` folder.
- In Slide 4, click **`⚡ 3D Model Viewer (Offline)`** or press **`M`** on your keyboard to rotate and explode the 3D glasses model without needing any internet connection.
- A toggle button `[⚡ Source: Local (Offline) / 🌐 Cloud (Vercel)]` is provided in the 3D viewer header if you want to switch between local and cloud modes.

---

### 🔊 How the Audio Simulation Works Offline:
- When you click **"🔊 Test Audio"** on Slide 5, it uses the **local Windows / browser speech engine** (`window.speechSynthesis`).
- It does **NOT** query any cloud API, so it speaks out loud with zero latency even in airplane mode.

---

### 📄 Emergency Offline Backup (Export to PDF):
1. In Chrome or Edge, open the presentation (`http://localhost:3000`).
2. Press **`Ctrl + P`**.
3. Set **Destination** to `Save as PDF`.
4. Set **Layout** to `Landscape`.
5. Under **More Settings**, check **`Background graphics`**.
6. Click **Save**. You now have an emergency PDF version of all 7 slides!

---

## 🎮 Presentation Controls & Keyboard Shortcuts

| Key | Action | Description |
|---|---|---|
| `➔` / `Space` / `PageDown` | Next Slide | Advance to next presentation slide |
| `⬅` / `Backspace` / `PageUp` | Previous Slide | Return to previous slide |
| `1` – `7` | Direct Jump | Instantly navigate to Slide 1 through 7 |
| `F` | Fullscreen | Toggle seamless 16:9 borderless presentation mode |
| `S` | Presenter Script | Open slide-by-slide 60–90 second verbal pitch notes |
| `M` | 3D Modal | Launch the live 3D web model viewer inside the presentation |
| `Esc` | Close | Close active modal, drawer, or dialog |
| `Ctrl + P` | Export to PDF | Print all 7 slides cleanly formatted for handouts/submission |

---

## 📋 7-Slide Engineering Breakdown

1. **Slide 1 — Product Introduction**:
   - Title: `VISIONAID AI`
   - Subtitle: `AI-Powered Assistive Vision System`
   - 3D hero render with interactive parallax tilt
   - 5 component callouts: RGB Camera, Depth/ToF Sensor, Edge AI Processor, Bone-Conduction Speaker, Battery
   - Editable metadata fields: Problem Statement ID, Theme, Team ID, Team Name
   - Core one-line mission statement: *“Converting visual surroundings into understandable information for visually impaired users.”*

2. **Slide 2 — The Challenge**:
   - 4 visual problem cards: Understanding surroundings, Detecting obstacles, Reading signs/text, Navigating independently
   - Traditional assistive tools (White Cane ~1.0m ground sweep) vs. VisionAid AI (5.0m 3D situational horizon)
   - Bottom anchor: *“Our goal is to provide additional situational awareness using AI.”*

3. **Slide 3 — Our Proposed Solution**:
   - 3D smart glasses schematic with 6 numbered component callouts:
     1. RGB Camera (captures environment)
     2. Depth Sensor (estimates distance)
     3. Edge AI Processor (processes visual information)
     4. OCR Engine (reads visible text)
     5. Audio/Haptic Feedback (communicates key information)
     6. Microphone Array (enables voice interaction)
   - Engineering data pipeline: `ENVIRONMENT ➔ CAMERA + DEPTH ➔ AI PROCESSING ➔ OBJECT / TEXT / DISTANCE ➔ PRIORITY DECISION ➔ AUDIO / HAPTIC FEEDBACK`

4. **Slide 4 — 3D Prototype (Explore the Design)**:
   - 4 Visual inspection panels:
     - View 1: Assembled Wearable Form Factor
     - View 2: Exploded Component Disassembly
     - View 3: Optical Bridge & Processor Close-Up
     - View 4: Simulated AI Working Concept & HUD
   - Prominent link button: `OPEN 3D PROTOTYPE ➔` linking to [https://smart3-d-glasses.vercel.app/](https://smart3-d-glasses.vercel.app/)
   - In-slide interactive 3D modal viewer

5. **Slide 5 — From Vision to Assistance**:
   - Large horizontal animated-style flowchart (6 stages)
   - Real-world scenario 1: Obstacle proximity avoidance with live audio feedback simulation
   - Real-world scenario 2: Voice-command text reading with live audio feedback simulation
   - Built-in Web Speech API synthesized audio button for live judge demonstrations

6. **Slide 6 — Live Prototype Demo**:
   - Large video monitor frame with simulated video stream and placeholder `[INSERT PROTOTYPE VIDEO HERE]`
   - Three structured evaluation steps:
     - 01: Explore the 3D Wearable
     - 02: Inspect Individual Components
     - 03: Demonstrate AI Interaction Concept
   - Crisp, scannable QR Code for judges linking to [https://smart3-d-glasses.vercel.app/](https://smart3-d-glasses.vercel.app/)

7. **Slide 7 — Why VisionAid AI? (Impact, Feasibility & Future)**:
   - Three engineering columns: Impact, Feasibility, Future
   - Closing quote: *“WE DON'T REPLACE VISION. WE CONVERT THE VISUAL WORLD INTO UNDERSTANDABLE INFORMATION.”*
   - Evaluation closure and Q&A trigger

---

## 🎙️ Built-in 10-Minute Presenter Defense Guide
Click the **"Script (S)"** button or press **`S`** at any time during presentation to view:
- Exact allocated pitch time (60–90 seconds per slide)
- Spoken verbal script
- Slide objective
- Anticipated tough judge questions and rock-solid defense arguments
