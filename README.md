# Enginerig – Camera Rig Weight & Load Calculator (Balance, Mount Stress, Node Analysis)

**Enginerig** is a desktop application for **engineering analysis of camera rigs**.

It helps filmmakers, photographers, and rig builders calculate:

- total rig weight  
- center of mass  
- perceived operator load  
- rig imbalance  
- load on mounting points and joints  

The program allows you to visually build a rig scheme and instantly see how weight distribution affects the operator and equipment.

This tool is useful for anyone asking questions like:

- **How to calculate load on a camera rig?**
- **How to calculate center of mass of a camera setup?**
- **How to balance a handheld camera rig?**
- **How to estimate operator fatigue from a camera rig?**
- **How much weight can a quick-release or joint handle?**

Enginerig provides a **visual engineering model** to answer these questions.

---

# What Enginerig Does

Enginerig analyzes filming rigs such as:

- camera + lens setups  
- monopod rigs  
- handheld rigs  
- documentary shooting rigs  
- custom camera mounting systems  

The program calculates:

- **Total rig mass**
- **Center of mass**
- **Rig imbalance**
- **Operator perceived weight**
- **Load on nodes (mounts, joints, quick releases)**
- **Estimated operator working time**

The rig is built interactively on a canvas using points, connectors and nodes.

---

# Key Features

### Visual rig builder

Create a rig structure by placing:

- **Points** — cameras, handles, accessories  
- **Connectors** — rods, arms, monopods  
- **Nodes** — joints, quick releases, mounts  

You can drag elements and instantly see how the rig balance changes.

---

### Center of mass calculation

The software calculates the **center of mass relative to the support point**.

This helps determine:

- whether the rig will tip forward
- how much torque acts on the operator
- how balanced the setup is

---

### Perceived weight calculation

Enginerig estimates the **perceived weight experienced by the operator**, not just the physical mass.

The model combines:

- physical mass
- center of mass displacement
- biomechanical tendon model

This allows estimating **operator fatigue during long shooting sessions**.

---

### Rig imbalance estimation

The program calculates rig imbalance as a percentage:

| Imbalance | Meaning |
|----------|--------|
| 0–20% | Excellent balance |
| 20–50% | Slight imbalance |
| 50–100% | Noticeable tilt |
| 100–200% | Heavy front/back pull |
| 200%+ | Shoulder strap or support recommended |

---

### Load calculation on mounts and joints

Enginerig calculates **load applied to nodes** such as:

- quick release plates  
- joints  
- pivot points  
- mounting adapters  

This helps answer questions like:

- *Will my quick release break?*  
- *Is my mount overloaded?*  
- *How much force acts on the joint during movement?*

The software also includes **dynamic load simulation (+40%)** to approximate forces during walking.

---

### Real-time simulation

All calculations update instantly when you:

- move points
- change weights
- modify connectors
- change the support point

This allows quick experimentation with rig designs.

---

# Export

Enginerig can export:

- **Rig diagram** → JPG / PDF  
- **Rig composition** → PDF  
- **Rig data** → copy to clipboard  

The exported composition includes:

- all rig elements
- weights
- connector lengths
- comments
- construction relationships

---

# Internationalization

Enginerig supports **11 languages**:

- English
- Russian
- German
- Spanish
- French
- Portuguese
- Italian
- Polish
- Ukrainian
- Chinese
- Japanese

---

# Technology

Enginerig is built with:

- **Electron**
- **HTML5 Canvas**
- **JavaScript**
- **KaTeX** (math formulas)
- **jsPDF**
- **html2canvas**

---

# File Format

The file contains:

- points
- connectors
- nodes
- weights
- support point
- canvas position
- project name

The format is JSON-based.

---

# Typical Use Cases

Enginerig can be used for:

### Camera rig design

Design a rig before physically assembling it.

### Load calculation

Estimate load on mounts, adapters, and joints.

### Balance optimization

Find the best position for accessories and handles.

### Operator ergonomics

Estimate how tiring the rig will be during shooting.

### Educational purposes

Understand physics concepts like:

- center of mass
- torque
- load distribution

---

# Controls

| Action | Method |
|------|------|
Create point | Left click on canvas |
Create connector | Click point → click another point |
Create node | Click connector |
Move element | Drag |
Delete element | Right click |
Undo | Ctrl+Z |
Hide labels | Ctrl+R |

---

# Why Enginerig Exists

Camera rigs are often built by intuition.

But heavy lenses, monopods, and accessories create complex torque systems.

Enginerig provides a **simple engineering tool** to analyze these systems visually.

Instead of guessing, you can **calculate rig balance and load before shooting**.

---

# License

Open source project.

---

# Keywords (for search)

camera rig calculator  
rig balance calculator  
camera rig weight distribution  
center of mass calculator  
camera mount load calculator  
rig torque calculation  
handheld camera ergonomics  
monopod rig analysis

## License & credits

- **Enginerig** — [Herr Designer](https://www.instagram.com/herr.designer/).
- UI icons: [Lucide Icons](https://lucide.dev) (ISC License).
- Math rendering: [KaTeX](https://katex.org).

---

## Version

1.5.0
---
camera-rig
rig-calculator
rig-balance
camera-rig-design
center-of-mass
weight-distribution
camera-engineering
filmmaking-tools
camera-rig-analysis
ergonomics
physics-simulation
camera-rig-calculator
camera-mount-load
