# RectifierLab Lite

**An interactive web-based simulator for single-phase and three-phase rectifiers.**

[**Live Demo**](https://rajatkatiyar95124-bit.github.io/Rectifier-Lab/) · [**GitHub Repository**](https://github.com/rajatkatiyar95124-bit/Rectifier-Lab)

RectifierLab Lite is an interactive educational tool for exploring the operation of diode and thyristor rectifiers. It visualizes circuit conduction, output waveforms, load current, and key performance parameters under different operating conditions.

## Features

- **Multiple Rectifier Topologies:** Single-phase half-wave, single-phase bridge, and three-phase bridge rectifiers.
- **Device Selection:** Compare diode and thyristor operation, including three-phase semi-converter operation.
- **Configurable Loads:** Resistive (R), resistive-inductive (RL), resistive-inductive-back-EMF (RLE), and DC current source loads.
- **Interactive Controls:** Adjust source voltage, firing angle, resistance, inductance, back EMF, and freewheeling diode settings.
- **Circuit Visualization:** Observe conducting devices and circuit conduction paths as the electrical angle changes.
- **Waveform Analysis:** Visualize source voltage, rectifier output voltage, load current, and source current.
- **Harmonic Analysis:** Explore source-current harmonics and total harmonic distortion (THD).
- **Performance Metrics:** View average DC output voltage and current, RMS values, output power, ripple factor, power factor, displacement factor, and apparent power.
- **Quick Presets:** Explore predefined operating conditions, including diode bridges, three-phase rectifiers, and DC motor loads.
- **Responsive Interface:** Use the simulator on desktop and mobile browsers, with light and dark theme support.

## Technology Stack

- HTML5
- CSS3
- JavaScript
- HTML Canvas and SVG for waveform plotting and circuit visualization

## Getting Started

### Run locally

1. Clone this repository:

   ```bash
   git clone https://github.com/rajatkatiyar95124-bit/Rectifier-Lab.git
   ```

2. Open the project folder.
3. Open `index.html` in your web browser.

No additional software installation or build process is required.

### Use the live simulator

Visit the [RectifierLab Lite Live Demo](https://rajatkatiyar95124-bit.github.io/Rectifier-Lab/).

## Learning Objectives

This project can help students explore:

- Controlled and uncontrolled rectification.
- The influence of firing angle on rectifier output.
- Continuous and discontinuous load-current conduction.
- Freewheeling diode operation with inductive loads.
- Three-phase rectifier conduction sequences.
- Ripple, power factor, and source-current harmonics.

## Project Information

- **Project:** RectifierLab Lite
- **Developer:** Rajat Katiyar
- **Institution:** IIT Kharagpur

## Disclaimer

This simulator is intended for educational purposes. Its numerical results are based on an idealized simulation model and may differ from practical circuits due to device voltage drops, switching dynamics, parasitic components, and other non-ideal effects.

---

If you find this project useful for learning power electronics, feel free to explore the simulator and the source code.
