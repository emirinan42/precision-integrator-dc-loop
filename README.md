# Precision Integrator with DC Feedback Loop

High-precision active integrator design incorporating a DC feedback loop to attenuate offset drift, suppress low-frequency instability, and maintain closed-loop AC stability.

## Key Specifications & Hardware
- **Operational Amplifier:** LTC6268 (Low-noise, high-speed op-amp)
- **Topology:** Capacitor feedback integrator with active DC loop
- **EDA & Simulation Tools:** LTspice, Cadence Virtuoso, KiCad

## Features & Analyses
- **DC Offset Suppression:** Attenuates low-frequency drift to ensure high dynamic range.
- **AC & Transient Stability:** Analyzed gain-bandwidth product (GBW), phase margin, and step response.
- **Power & Noise Characterization:** Evaluated input-referred noise spectral density and total power consumption.

## How to Run Simulations
1. Download the `.asc` simulation file from this repository.
2. Open with **LTspice**.
3. Run `.ac` analysis for stability checking or `.tran` for time-domain transient behavior.
