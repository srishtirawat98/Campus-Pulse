# CAMPUS PULSE — Signals, Not Sources
> **DESIGNOVA 2026** · Track T-01: UI Design · Problem Statement: **[PS-01] The 60-Second Campus**  
> *"You have 60 seconds. Find what you need."*

---

## 💡 The Big Idea

**Campus Pulse** is not another university portal. It is an intelligent **discovery and action layer** that sits above fragmented campus information systems.

Students currently switch between portals, noticeboards, PDFs, WhatsApp groups, and LMS platforms just to find basic, time-critical updates. Campus Pulse reorganizes information around **student intent, urgency, and physical proximity** — answering:

> **WHAT MATTERS RIGHT NOW?**  
> **WHY → WHERE → WHEN → ACTION**

---

## ⚡ The 60-Second Budget

Every interaction in Campus Pulse is calibrated against cognitive load and speed:

| Time | Goal | Action in Campus Pulse |
| :--- | :--- | :--- |
| **0–3s** | **See** | Hero card announces room shift or immediate deadline |
| **3–13s** | **Act** | Single-tap verb (`Navigate`, `Submit`, `Renew`, `Acknowledge`) |
| **13–33s**| **Find** | Ask once: search across all systems without knowing who owns it |
| **33–60s**| **Buffer** | Slack for network latency, crowded corridors, and edge cases |

---

## 🎨 Visual Identity & Design System

Inspired by bold editorial minimalism, oversized typography, and purposeful punctuation:

* **Campus Forest (`#12351F`)**: Primary brand dark for depth and authority.
* **Electric Lime (`#B8F35A`)**: Dominant accent used as punctuation on primary CTAs and active states.
* **Campus Mint (`#E8F6D8`)**: Soft highlighted canvas for problem and query flows.
* **Paper (`#FFFFFF`)**: Crisp, light editorial canvas with generous negative space.
* **Mist (`#EDF0EA`)**: Subdued secondary surfaces and cards.
* **Obsidian (`#0B0E0C`)**: Ultra-dark typography for display titles.
* **Urgent Red (`#D83B4B`)**: Reserved strictly for genuine emergencies and critical countdowns.

### Typography
* **Headline Display**: Inter 900 / Black with aggressive negative tracking (`-0.05em`) and line-height `0.88`.
* **Body / UI**: Inter 400, 500, 600, 700.

---

## 🏗️ Information Architecture

```
FRAGMENTED SOURCES
(Timetables · PDF Notices · WhatsApp · LMS · Admin · Transit)
                    ↓
              CONTEXT ENGINE
(Urgency × Course Match × Live Proximity × Open Tasks)
                    ↓
        PRIORITY SURFACES (NOW · FIND · TASKS)
                    ↓
             ONE-TAP ACTION
(Navigate · Pre-filled Submit · One-Tap Renew · Acknowledge)
```

---

## 🚀 Key Interactive Features

1. **Interactive 60-Second Timer & Focus Mode**:
   * Circular SVG progress indicator counting down from 60 seconds.
   * Activates priority focus mode: dims secondary noise and emphasizes immediate action cards.
2. **Horizontal Fragmentation Sequence**:
   * Visualizes the current chaotic student journey (`Notice → PDF → WhatsApp → Portal → LMS → Confused Student`).
   * Interactive "Collapse Fragments" synthesizes all noise into **One Clear Action**.
3. **What Matters Now? (Hero Action Card)**:
   * Real-time classroom relocation alert with live proximity wayfinding drawer.
   * Single-tap navigation and one-tap acknowledgment.
4. **Ask Once (Intelligent Query System)**:
   * Search without knowing institutional silos.
   * Intent chips: `NEXT CLASS`, `ROOM CHANGES`, `DEADLINES`, `FORMS`, `CAMPUS BUS`.
   * Expandable *"Why am I seeing this first?"* explanation drawer exposing the Context Engine metrics.
5. **Finish the Next Thing (Interactive Tasks)**:
   * Actionable items with one-tap completion, checkmark drawing animation, and instant completion states.
6. **Smart Sticky Header**:
   * Dynamically inverts between light and dark themes as the user scrolls between sections.

---

## 💻 Tech Stack

* **Zero External JS/CSS Frameworks**: Built purely with semantic HTML5, vanilla CSS3 custom properties, and modern JavaScript.
* **Typography**: Google Fonts Inter.
* **Accessibility**: Fully keyboard accessible, ARIA compliant, and WCAG AA contrast ratio compliant.
* **Responsive**: Seamless experience from mobile (360px) to ultra-wide displays.

---

## 🏃 Running Locally

Simply open `index.html` in any modern web browser or serve via:

```bash
npx http-server . -p 3000
```
Then visit `http://localhost:3000`.

---
*Created for DESIGNOVA 2026 · Track T-01 UI Design · [PS-01] The 60-Second Campus*
