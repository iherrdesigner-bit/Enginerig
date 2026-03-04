# Enginerig – Camera Rig Weight & Load Calculator (Balance, Mount Stress, Node Analysis)

**Enginerig** is a desktop camera rig weight calculator and load analysis tool for videographers, cinematographers, and camera operators.

It helps you calculate:

- Camera rig balance and center of mass
- Load on mounts, quick releases, hot shoe adapters, and articulating arms
- Perceived weight (operator fatigue model)
- Monopod and connector stress
- Rig imbalance in grams and percent
- Inertia-adjusted load for fast walking

Enginerig simulates real-world mechanical stress in camera setups including camera, lens, monopod, counterweights, connectors, and mounting nodes.

This tool is designed for camera rig builders, documentary operators, event videographers, and anyone who wants to analyze rig safety and balance before shooting.

---

## What problem does it solve?

Modern camera rigs often overload:

- Hot shoe mounts  
- Quick release plates  
- 1/4" threads  
- Articulating arms  
- Monopod connections  

Manufacturers list static load limits, but real shooting involves dynamic movement, inertia, and torque.  
Enginerig calculates effective load with a +40% inertia factor to simulate fast walking and real operating conditions.

---

## Core Features

- **Camera rig balance calculator** — center of mass and imbalance percentage  
- **Node load analysis** — color-coded stress levels (safe / moderate / overload)  
- **Mount stress simulation** — quick release, hot shoe, threaded mounts  
- **Perceived weight model** — hybrid biomechanical operator fatigue estimation  
- **Monopod load simulation** — connector length and torque influence  
- **Rig schematic editor** — visual point/connector/node modeling  
- **.rig project format** — save and load custom setups  
- **Export** — JPG (FHD) and vector PDF  
- **Multilingual UI** — 11 languages  

---

## Who is it for?

- Documentary camera operators  
- Event videographers  
- Steadicam and monopod users  
- Camera rig engineers  
- Cinematographers  
- Broadcast technicians  
- Gear reviewers  

---

## Keywords

camera rig calculator, camera rig weight calculator, rig balance tool, camera mount stress analysis, monopod load calculator, quick release load, hot shoe stress test, perceived weight calculator, camera operator fatigue tool
---

## Download

Get the latest **Windows (x64) build** from the [Releases](https://github.com/YOUR_USERNAME/YOUR_REPO/releases) page.  
Download the EXE installer, run it, and follow the setup. No compilation required.

---

## Features

- **Rig schematic** — Points (counterweights), support (camera/grip), connectors (monopod, lens), nodes (quick releases, mounts). Everything is drawn on a canvas and wired into the calculation model.
- **Calculation model** — Actual weight + perceived weight (hybrid operator and tendon model). Imbalance in percent and in grams.
- **Load on nodes** — Color-coded risk levels, including inertia for fast walking.
- **Work duration estimate** — Guidelines for novice (up to ~2 h) and experienced operator (up to ~8 h).
- **Projects** — Save and load in `.rig` format; file association with the app on Windows.
- **Export** — JPG (FHD) and vector PDF for drawings and reports.
- **Multilingual UI** — 11 languages: English, Russian, German, Spanish, French, Portuguese, Italian, Polish, Ukrainian, Chinese, Japanese.
- **Weight reminders** — On-screen hints when support point, points, or connectors have no weight entered.

---

## System requirements

| Item | Requirement |
|------|--------------|
| **OS** | Windows 10 (x64) or newer |
| **RAM** | 512 MB minimum (1 GB recommended) |
| **Disk** | ~200 MB for installation |
| **Display** | 1280×800 minimum (1920×1080 recommended for FHD export) |
| **Mouse** | Required (drag, LMB/RMB) |

If your antivirus blocks save/open dialogs, the app can save to the Downloads folder and will suggest retrying. Adding the app to antivirus exclusions is recommended.

---

## Controls

| Action | How |
|--------|-----|
| Create point | Left-click on canvas |
| Create connector | Left-click on point → left-click on another point/support |
| Create node on connector | Left-click on connector |
| Move elements | Select “Move elements” → drag |
| Delete element | Right-click on element |
| Change connector length | Click connector → enter length → Ctrl+Enter |
| Undo | Ctrl+Z |
| Show/hide labels | Ctrl+R |

You can open `.rig` files by double-clicking them or by dragging them into the app window.

---

## License & credits

- **Enginerig** — [Herr Designer](https://www.instagram.com/herr.designer/).
- UI icons: [Lucide Icons](https://lucide.dev) (ISC License).
- Math rendering: [KaTeX](https://katex.org).

---

## Version

1.05
