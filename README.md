# Digital Clock (Logisim Evolution)

A fully featured digital clock designed from the ground up in **Logisim Evolution** as part of an introductory university Digital Electronics project.

The project implements a modular digital system capable of functioning as a:

- Digital clock
- Alarm clock
- Stopwatch
- Countdown timer

All logic was designed using sequential and combinational digital circuits rather than built-in clock components.

---

## Features

- 24-hour and 12-hour (AM/PM) display
- User-adjustable time
- Configurable alarm
- Stopwatch (up to 99:59:59)
- Countdown timer
- Visual flashing alarm indication
- Simple five-button user interface
- Modular hierarchical circuit design

---

## Demonstration

A demonstration of every operating mode is included below.

![Demo](images/demo.gif)

Alternatively watch:

demo.mp4

---

## Design Highlights

This project was built using a hierarchical approach with reusable Logisim subcircuits.

Key design components include:

- Ripple counters
- Synchronous counters
- T, JK and D flip-flops
- Multiplexers/Demultiplexers
- Comparators
- Seven-segment display drivers
- Finite-state control logic

Particular attention was given to reducing transistor count by selecting appropriate flip-flop implementations and simplifying logic using Karnaugh maps.

---

## Repository Contents

| File | Description |
|------|-------------|
| DigitalClock.circ | Complete Logisim Evolution project |
| demo.mp4 | Demonstration video |
| docs/Design_Report.pdf | Full design documentation |
| docs/User_Manual.pdf | User operating guide |

---

## Running the Project

1. Install **Logisim Evolution**
2. Open `DigitalClock.circ`
3. Start simulation (`Ctrl + K`)
4. Use the on-screen buttons to navigate between operating modes.

---

## Skills Demonstrated

- Digital logic design
- Sequential circuit design
- Counter design
- Finite state machines
- Hierarchical circuit design
- Karnaugh map optimisation
- Debugging complex digital systems
- Team software/hardware development

---

## Authors

Developed by:

- Gavin Mac Aonghusa
- Conor Murphy
