# Stack Calc 🧮  
**Reimagining Problem Solving Through the Stack Calculator**

Stack Calc is an open-source educational calculator designed to teach **how to think**, not just what to compute. It brings the principles of **stack-based thinking**—drawn from Reverse Polish Notation (RPN)—into a form that's tactile, visual, and intuitive for learners of all ages.

> "The steps are the structure, and structure is the root of meaning."

---

## 🚀 Why Stack Thinking?

Most calculators hide process. Stack Calc reveals it.

- 🧠 **Visible thinking**: Every operation builds on the last, step by step  
- ✍️ **Process over product**: Kids learn *how* math happens, not just answers  
- 🧱 **Structured logic**: Aligns with coding, dimensional analysis, and systems thinking  
- 🤲 **Multi-sensory learning**: Physical buttons, tactile haptics, and e-ink displays bring the stack to life  

---

## 🔨 Hardware Overview

The calculator is built around:

- **RP2040 (Raspberry Pi Pico)** microcontroller  
- **4.2" SPI E-Ink display** for a visible, persistent stack  
- **4×4 tactile keypad** with printed or membrane overlay  
- **LRA motor with DRV2605L** haptic driver for expressive feedback  
- **Stacked PCB design** (keypad / logic / display) with a printable enclosure  

All components are chosen for classroom durability, low power usage, and future expandability.

---

## 🎓 Designed for Classrooms

We’re starting with a K–6 version: simple, playful, and approachable.  
Later versions will expand into high school and beyond, supporting full RPN functionality.

> Imagine: older students CAD and print enclosures for younger classes.  
> A math tool made *by students, for students*—that teaches thinking at every step.

---

## 📁 Repo Structure
```
hardware/ - KiCAD files, STLs, and case design
firmware/ - MicroPython stack engine, display logic, keypad scanning
docs/ - Design philosophy, educational writeups, wiring guides
classroom/ - Templates, build instructions, cross-grade activities
```


---

## 📌 Roadmap Highlights

- [ ] Finalize keypad layout (K–6 version)
- [ ] Create first stacked PCB set (KiCAD)
- [ ] Print working enclosure + button overlay
- [ ] Implement MicroPython firmware (stack logic + haptics)
- [ ] Document classroom pilot workflow

See [`TODO.md`](TODO.md) for more details.

---

## 🤝 Contributing

Whether you're a teacher, hacker, parent, or student—we welcome your help!

- 💡 Improve the calculator design  
- 🧠 Expand curriculum guides or activities  
- 🖨️ Adapt printable parts for different grades  
- 🎛️ Hack new features (wireless syncing? LED stack depth? Who knows!)

---

## 📜 License

MIT License. Build freely. Teach widely.

---

## 💬 Credits & Inspiration

This project was born from a single question:

> *"What if a calculator didn't just give you the answer—what if it taught you how to think?"*

Inspired by:
- Reverse Polish Notation (HP, engineers, legends)
- Stack metaphors in programming and logic
- Every kid who ever asked “*why does that work?*”
