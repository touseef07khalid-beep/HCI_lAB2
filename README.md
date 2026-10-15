# 🌌 CHRONO·SURGE: Quantum Gravitational Wave Synthesizer & Spacetime Cartographer

**CHRONO·SURGE** is an interactive, browser-based astrophysics laboratory and audiovisual instrument. It combines real-time general relativistic spacetime simulation with a Web Audio sonification engine, rendering black hole accretion dynamics, gravitational lensing, and gravitational-wave strain acoustics directly in the browser.

---

## ⚡ Features

### 1. Spacetime Cartographer (Visual Simulation Engine)
- **Gravitational Lensing & Einstein Rings**: Dynamically refracts background starfields and cosmic microwave background (CMB) grids using deflection approximations ($\theta \propto \frac{4GM}{c^2 b}$).
- **Kerr Ergosphere & Frame-Dragging**: Simulates spacetime rotation around spinning black holes, including Doppler beaming (approaching accretion matter appears brighter and blueshifted).
- **Accretion Disk & Relativistic Jets**: High-temperature particle simulation exhibiting differential Keplerian motion, turbulent accretion flow, and magnetic polar ejection.
- **Dynamic Geodesics & Probes**: Spawns orbital test particles, photons, and probes with gravitational capture and tidal spaghettification.

### 2. Quantum Acoustic Synthesizer (Web Audio API)
- **Authentic Gravitational Chirp**: Mathematically models binary inspiral sweep acoustics according to general relativity:
  $$f_{\text{GW}}(t) \propto (t_c - t)^{-3/8}$$
  with exponential post-merger quasinormal mode ringdown.
- **Sub-Bass Curvature Resonance**: Generates ultra-low frequency sub-bass ($30\text{–}60\,\text{Hz}$) corresponding to local metric curvature tension.
- **Pulsar Radio Beacons**: Millisecond pulse synthesis with variable spin frequency and pulse widths.
- **Hawking/Cosmic Pink Noise**: Procedural pink noise generator mimicking quantum vacuum fluctuations at event horizons.

### 3. Metric Engine & Scientific Telemetry
- **Multiple Spacetime Metrics**:
  - **Schwarzschild**: Static, non-rotating spherical black hole.
  - **Kerr**: Rotating black hole with ergosphere and spin parameter $a \in [0, 1)$.
  - **Alcubierre**: Theoretical warp bubble geometry with negative energy density contours.
- **Live Stress-Energy Matrix ($T_{\mu\nu}$)**: Real-time calculation of energy density, momentum flux, and anisotropic shear stress components.
- **Strain Telemetry ($h_+(t)$)**: Dual-polarization gravitational strain oscilloscope measuring signal deflection in units of $10^{-21}$ strain.
- **Time Dilation Clock ($\tau$)**: Displays relative proper time dilation vs. asymptotic coordinate time at infinity.

---

## 🎛️ Quick Start & Controls

### Running the App
1. Open `chrono-surge.html` in any modern web browser (Chrome, Edge, Firefox, Brave, Safari).
2. Click **"INITIALIZE AUDIO ENGINE"** in the top navigation bar to unlock the Web Audio API context.

### Interaction Controls
- **Click / Drag on Spacetime Canvas**: Reposition the primary gravitational singularity or manipulate local metric curvature.
- **"Spawn Probe"**: Injects a test particle at the cursor position to trace relativistic geodesics.
- **"Trigger Chirp"**: Initiates a binary black hole inspiral, merger, and gravitational ringdown audio sweep.
- **"Capture Snapshot"**: Exports a high-resolution PNG image of the current simulation view and telemetry state.

### Preset Configurations
- **GW150914 (Binary Merger)**: The historic first direct gravitational wave detection ($36\,M_\odot + 29\,M_\odot$).
- **Gargantua (Kerr Extreme)**: Supermassive black hole with near-extremal spin ($a \approx 0.998$) and intense accretion disk.
- **Magnetar FRB**: Rapidly rotating, hyper-magnetized neutron star emitting periodic microsecond radio bursts.
- **Alcubierre Bubble**: Metric warp configuration demonstrating negative-energy stress-energy distribution.

---

## 🔬 Mathematical & Physical Foundations

| Parameter | Mathematical Formulation | Description |
| :--- | :--- | :--- |
| **Schwarzschild Radius** | $r_s = \frac{2GM}{c^2}$ | Event horizon radius for a non-rotating mass |
| **Inspiral Chirp Frequency** | $f_{\text{GW}}(\tau) = \frac{1}{\pi}\left(\frac{5}{256\,\tau}\right)^{3/8}\left(\frac{G\mathcal{M}}{c^3}\right)^{-5/8}$ | Frequency evolution of binary inspirals |
| **Gravitational Time Dilation** | $t_0 = t_f \sqrt{1 - \frac{r_s}{r}}$ | Proper time ratio in static Schwarzschild field |
| **Einstein Ring Radius** | $\theta_E = \sqrt{\frac{4GM}{c^2} \frac{D_{LS}}{D_L D_S}}$ | Characteristic angular radius of gravitational ring |

---

## 🛠️ Tech Stack & Architecture

- **Rendering**: HTML5 Canvas 2D / procedural pixel shader approximations.
- **Audio Engine**: Pure Native Web Audio API (`AudioContext`, `BiquadFilterNode`, `GainNode`, `PeriodicWave`, `AudioBuffer`).
- **Styling**: Cybernetic telemetry aesthetic inspired by laboratory instrumentation and CRT oscilloscopes.
- **Dependencies**: None (Zero external libraries, single portable HTML file).

---

## 📄 License
This project is open-source under the **MIT License**. Free for educational, research, audio-synthesis, and creative experiments.
