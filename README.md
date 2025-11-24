# ThinkClock Battery R&D Assignment

This repository contains three battery–embedded engineering tasks involving:
- Raspberry Pi Pico signal control
- PWM level shifting using analog circuits
- Battery pack topology analysis from a BMS perspective

---

## 📌 Summary Table

| Question | Problem Statement | Theory / Concept | Simulation Link |
|----------|------------------|-----------------|-----------------|
| **Q1** | Blink LED on Raspberry Pi Pico exactly **10, 20, 30 times per minute** and toggle sequence using button latch | [Explanation](https://github.com/ShravanaHS/assignment/blob/main/question1.md) | [sim1]() |
| **Q2** | Shift **0–3.3V PWM** to **±1.65V**, then level shift back to 0–3.3V using passive RC circuits |  [Explanation](https://github.com/ShravanaHS/assignment/blob/main/question2.md) |  |
| **Q3** | Compare two **battery pack topologies** and relate to **BMS** requirements |  [Explanation](https://github.com/ShravanaHS/assignment/blob/main/question3.md) |  |

---
![Simulation Result](https://github.com/ShravanaHS/assignment/blob/main/images/q1b.png)
> This image represents the led is blinking in normal order with push button pressed the press is detected using buildin led
- [Simulate NOW](https://wokwi.com/projects/445351244852802561)

![Simulation Result](https://github.com/ShravanaHS/assignment/blob/main/images/q1b2.png)
> This image represents the led is blinking in reverse order with no push button pressed.

- [Simulate NOW](https://wokwi.com/projects/445351244852802561)
### 🧠 Key Highlights

| Feature | Explanation |
|---------|-------------|
| **Latch-based control** | Prevents mode change during active timing cycle (used in measurement systems) |
| **Passive level shifting** | Uses capacitive coupling + resistive biasing, low-cost approach |
| **Pack topology impact** | Influences BMS balancing complexity and fault tolerance |

---

### 🛠️ Tools Used
- Multisim / LTspice (Analog PWM shifting)
- Markdown + Mermaid diagrams (Documentation)
- Wokwi (simulation)

---



---

### 👨‍🔬 Author
**Shravana H S** 
-shravanahs97@gmail.com

---


