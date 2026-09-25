# Obedience Adara

**Aerospace Engineering Student building toward Autonomous Systems through Reinforcement Learning, Control, AI/ML & Simulation.**

[Portfolio](https://obedienceadara.vercel.app) · [RL Lab](https://obedienceadara.vercel.app/lab) · [LinkedIn](https://www.linkedin.com/in/obedience-adara) · [X](https://x.com/ObedienceAdara)

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square\&logo=numpy\&logoColor=white)
![SciPy](https://img.shields.io/badge/-SciPy-654FF0?style=flat-square\&logo=scipy\&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square\&logo=pytorch\&logoColor=white)
![Gymnasium](https://img.shields.io/badge/-Gymnasium-0081A5?style=flat-square)
![RocketPy](https://img.shields.io/badge/-RocketPy-111827?style=flat-square)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)

> I'm building the computational and engineering foundations for autonomous aerospace systems: model the physics, simulate the system, control it, learn from interaction, and verify the result.

---

## Direction

My long-term focus is **autonomous systems for aerospace**.

The common thread across my work is:

`Model → Simulate → Control → Learn → Verify`

I'm developing that foundation through four connected areas:

- **Aerospace engineering** — flight dynamics, propulsion, aerodynamics, stability, mission design
- **Simulation & control** — nonlinear dynamics, numerical methods, system modelling, verification
- **Reinforcement learning** — decision-making, value functions, policy learning, reward design, deep RL
- **AI/ML for engineering** — physics-informed learning, research implementation, intelligent engineering workflows

The goal is to progress from controlled learning environments toward increasingly realistic autonomous-system problems.

---

## Current Work

### Reinforcement Learning

**[RL Learning Log](https://github.com/ObedienceAdara/rl-learning-log)** · **[RL Lab ↗](https://obedienceadara.vercel.app/lab)**

A public record of moving from first-principles reinforcement learning toward autonomous control.

Current progression:

`Tabular RL → GridWorld → Deep RL → LunarLander → Continuous Control → Aerospace Autonomy`

Recent work includes:

- Q-learning from scratch in discrete environments
- CartPole experiments and evaluation
- GridWorld planning and policy visualization
- Deep RL with Lunar Lander
- Public experiment logs, results, failures, and theory notes

Longer term, I'm applying these foundations to **UAVs, robotics, and aerospace control systems**.

### Physics, Simulation & Engineering AI

My aerospace and physics-oriented work explores how computational models and learning systems can work together:

- Nonlinear aircraft flight dynamics and 6-DOF simulation
- Rocket mission design, uncertainty analysis, and recovery trade studies
- Physics-Informed Neural Networks for differential-equation problems
- Research reproduction and translation of papers into working implementations

---

## Featured Engineering Work

### [Aircraft 6-DOF Flight Dynamics Simulator](https://github.com/ObedienceAdara/nonlinear-aircraft-flight-dynamics-simulator)

A from-scratch nonlinear rigid-body aircraft simulator built around:

- **13-state** flight dynamics
- Six-degree-of-freedom equations of motion
- Quaternion attitude propagation
- Aerodynamic force and moment buildup
- Atmosphere, wind and reproducible turbulence modelling
- RK4 numerical integration
- Actuators, CSV/JSON outputs, engineering plots and verification tests

The project is structured around explicit assumptions, reproducible simulations, and a clear distinction between verification and validation.

### [Apogee](https://github.com/ObedienceAdara/apogee_v)

A systems-engineering pipeline for rocket mission design and flight-readiness analysis.

`Environment → Motor Selection → Stability → 6-DOF Monte Carlo → Recovery Trade Study → Flight-Data Comparison → Report`

Current demo evidence includes **120 Monte Carlo runs**, **19 unit tests**, a **2200 m target apogee**, and a demonstrated **0.12% apogee error** under the project's stated assumptions.

- ###[Flight Dynamics Toolkit](https://github.com/ObedienceAdara/flight-dynamics-toolkit)

A full software-engineering refactor of Robert Stengel's FLIGHTv2.m six-degree-of-freedom flight simulator — class-based architecture, JSON config, test suite, quaternion renormalization, Dryden turbulence modeling, and variable-mass/fuel-burn dynamics.

### [PINN](https://github.com/ObedienceAdara/pinn)

A reusable PyTorch implementation of a standard Physics-Informed Neural Network for learning solutions to differential equations.

The core example solves the **1D heat equation** and is benchmarked against an analytical solution, with additional example problems for thermal barriers, electronics cooling, and 1D viscous Burgers flow.

### [RL Learning Log](https://github.com/ObedienceAdara/rl-learning-log)

My public reinforcement-learning notebook in repository form: implementations, visualizations, experiments, mistakes, and measured results rather than only completed projects.

---

## Research & Systems Interests

My strongest technical interests sit at the intersection of:

**Autonomous Systems**

Reinforcement learning · autonomous flight · robotics · decision-making · intelligent control · simulation

**Computational Engineering**

Flight dynamics · numerical methods · modelling · verification · uncertainty · physics-informed learning

**AI/ML**

Deep learning · PyTorch · research implementation · AI-assisted engineering · learning-based control

I'm especially interested in systems where **physics, control, learning, and decision-making interact**.

---

## Plex Hedge

**[Plex Hedge](https://github.com/plexhedge)**

My commercial engineering track: building production AI automation and integration systems for businesses.

It has given me practical experience with:

- Workflow automation
- API integrations
- Agentic systems
- Production AI systems

This work is complementary to my core technical direction in aerospace and autonomous systems.

---

## How I Work

I learn by building and make the process visible.

**Learn → Build → Measure → Explain → Document → Iterate**

I care about more than making a model run. I try to make assumptions explicit, record measurements, examine failure modes, and understand where a result is trustworthy and where it is not.

My GitHub is intended to be evidence of what I can actually build, test, explain, and improve.

---

## Current Focus

- Reinforcement learning from first principles
- Deep RL and learning-based control
- Nonlinear simulation and system modelling
- AI/ML for engineering problems
- Building toward autonomous UAV and aerospace systems

---

## Engineering Principles

**Make assumptions visible.**

**Measure the result.**

**Study failure modes.**

**Separate verification from validation.**

**Prefer reproducible evidence over impressive claims.**

---

### Philosophy

> **“Execution is the only argument.”**

**Build the engineering foundation. Build real systems. Push toward autonomous aerospace.**
