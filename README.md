<h1 align="center">Munir Isa-Osori</h1>
<p align="center">
Mechatronic & Robotic Engineering student, University of Sheffield<br/>
Vehicle dynamics · closed-loop control · embedded systems · simulation
</p>
<p align="center">
📧 munirisaosori@gmail.com &nbsp;|&nbsp;
🔗 <a href="https://www.linkedin.com/in/munir-isa-osori">LinkedIn</a> &nbsp;|&nbsp;
📍 Sheffield, United Kingdom
</p>

---

### About

First-year Mechatronic and Robotic Engineering student (First Class Honours) with hands-on project experience across the full V-model — mathematical modelling, MATLAB/Simulink simulation, and embedded C implementation. This page collects the engineering projects behind my CV, with code, write-ups and demo videos for each.

*Note: project folders and demo videos are being added over the next couple of days — check back soon if a link below isn't live yet.*

---

### Engineering Projects

#### 🚗 Drag Race Performance & Cost-Benefit Analysis — ICE vs EV
Led a 3-person team through a longitudinal vehicle dynamics simulation comparing ICE and EV drag-race performance, then independently proposed and led a cost-benefit extension comparing long-term ownership costs.
- Built a drag/rolling-resistance model with gear-ratio and torque-curve interpolation, plus an EV powertrain model with battery power/energy constraints
- **ICE ~30s / ~219km/h** vs **EV ~36s / ~184km/h** over a 1km run
- EV found to be **~65% cheaper to run** (£386.85/yr vs £1,113.74/yr), with a ~14-year break-even against its purchase premium
- **Tools:** MATLAB
- 📁 [Code](#) · 🎥 [Demo/write-up](#)

#### 🔧 Quarter-Car Suspension Model — Sports & Cruise Modes
Built a quarter-car suspension model from first principles (driver, seat, chassis, wheel) with two selectable damping/stiffness profiles.
- Tuned spring stiffness and damping across a 16-point parameter sweep, cutting overshoot from over 90% to **68.8%**
- Benchmarked Sports vs Cruise mode: **17% faster rise time**, **36% shorter settling time**
- Validated wheel-to-road tracking using RMSE/MAE error metrics against a simulated bumpy-track profile
- **Tools:** MATLAB, Simulink
- 📁 [Code](#) · 🎥 [Demo/write-up](#)

#### 🤖 PID-Based Self-Driving Robot Car with Automatic Braking
Led a 3-person team through the full V-model lifecycle to deliver a closed-loop line-following robot with adaptive braking.
- Derived closed-loop transfer functions via Laplace transforms and implemented a proportional (Kp) controller
- Built an I2C interface to an 8-sensor IR array (Sparkfun SX1509), driving 10-bit PWM motor outputs
- Designed an autobraking routine that scales motor speed proportionally to obstacle distance
- **Tools:** Embedded C, PIC18F2221, I2C, PWM
- 📁 [Code](#) · 🎥 [Demo video](#)

#### 📡 Beacon-Guided Autonomous Robot
Obstacle-avoiding, beacon-seeking robot built from schematic to a working breadboard prototype.
- Programmed IR-based obstacle avoidance and dual-sensor beacon detection in embedded C
- Timer0-interrupt-driven encoder counting for precise turns and PWM-based differential drive
- Circuit designed and soldered from schematic using VeeCAD
- **Tools:** Embedded C, PIC18F2221, VeeCAD
- 📁 [Code](#) · 🎥 [Demo video](#)

#### 🌡️ Two-Room Thermal System Model
Modelled
