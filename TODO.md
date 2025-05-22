# 📋 TODO: Stack Calc Project Roadmap

Welcome to the stack! This document tracks the design, development, and deployment milestones for the Stack Calc project.

We're starting with the **K–6 prototype version**—a tactile, visual calculator that embodies stack-based thinking. Future phases will scale into more advanced models and networked classroom applications.

---

## 🔧 Hardware

### ☐ Finalize Keypad Layout
- [ ] Decide on number of buttons (likely 4×4)
- [ ] Choose symbols / pictograms for stack operations
- [ ] Plan color-coding or overlays
- [ ] Document matrix wiring pinout

### ☐ KiCAD: Logic Board
- [ ] RP2040 (Pico footprint or COB-ready design)
- [ ] JST header or pads for keypad input
- [ ] DRV2605L haptic motor driver + LRA output
- [ ] E-Ink SPI interface (test with Waveshare 4.2")
- [ ] Power input (USB-C for now; battery optional)
- [ ] Silkscreen labels + test pads

### ☐ KiCAD: Keypad Layer
- [ ] Button grid layout
- [ ] Trace matrix or dome pad footprint
- [ ] Option for flex-ribbon or pogo pin stack join

### ☐ Printables
- [ ] STL for top faceplate with button cutouts
- [ ] STL for backplate with standoff sockets
- [ ] SVG overlay for printed button legends
- [ ] Snap-fit or screw-post fit between PCB layers

---

## 🧠 Firmware

### ☐ MicroPython Stack Engine
- [ ] Define stack object (push, pop, peek)
- [ ] Arithmetic operation handling (`+`, `–`, `×`, `÷`)
- [ ] Undo buffer / history
- [ ] Stack overflow/underflow logic

### ☐ Keypad Interface
- [ ] Matrix scanner for GPIO input
- [ ] Debounce logic
- [ ] Mapping from keys → stack actions

### ☐ Display Driver
- [ ] Connect to e-ink via SPI
- [ ] Render 4-line stack view
- [ ] Indicate active operation, result line
- [ ] Refresh optimization (partial updates?)

### ☐ Haptic Feedback
- [ ] I2C interface to DRV2605L
- [ ] Assign effects to actions (push, op, undo, error)
- [ ] Silent mode toggle

---

## 🏫 Classroom Pipeline

### ☐ Document Build Steps for Students
- [ ] Printable guides (color, scale, labels)
- [ ] Assembly instructions (hands-on kit)
- [ ] Suggested age-mods (e.g. 3D print variants for younger grades)

### ☐ Develop Cross-Grade Pilot Framework
- [ ] Older students print or assemble for younger peers
- [ ] Include labeling ("Made by ____ for ____")
- [ ] Feedback forms or reflections for builders + users

---

## 📚 Documentation

### ☐ README polish (in progress)
- [ ] Add media (photos, renderings, demos)
- [ ] Link to manifesto / philosophy notes

### ☐ Hardware Docs
- [ ] Wiring diagrams
- [ ] Component sourcing (BOM)
- [ ] PCB ordering guide

### ☐ Educational Docs
- [ ] Stack metaphors in K–6 language
- [ ] “From Process to Product” curriculum draft
- [ ] Classroom usage scenarios

---

## 🔜 Future Phases

- [ ] ESP32-based “Pro” version with wireless sync
- [ ] Classroom dashboard to monitor usage, learning metrics
- [ ] Unit conversion / dimensional analysis module
- [ ] Stack-as-code visualizer / web simulator
- [ ] Networked “stack battles” game mode

---

## 📬 How to Contribute

Feel free to open:
- 📂 PRs for hardware/firmware/docs
- 🐞 Issues for bugs or questions
- 💡 Discussions for design ideas, classroom applications, or pilot leads

Let’s build something that changes how people think.

🌀
