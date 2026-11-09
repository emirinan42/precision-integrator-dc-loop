# Precision Integrator with DC Feedback Loop

High-precision active integrator design incorporating a DC feedback loop to attenuate offset drift, suppress low-frequency instability, and maintain closed-loop AC stability.

## Key Specifications & Hardware
- **Operational Amplifier:** LTC6268 (Low-noise, high-speed op-amp)
- **Topology:** Active integrator with reset switch network and DC feedback loop
- **EDA & Simulation Tools:** LTspice, Cadence Virtuoso, KiCad

## Simulation Results & Plots

### AC Analysis (Bode Plot)
Shows closed-loop bandwidth, low-frequency offset suppression, and phase margin stability.

<img width="1911" height="441" alt="image" src="https://github.com/user-attachments/assets/26b7b235-8d75-4113-a887-1a6bdc008620" />

---

### Transient Response
Time-domain output behavior under reset switch pulses.

<img width="1906" height="437" alt="image" src="https://github.com/user-attachments/assets/0de6b649-4716-4937-a032-443221e55271" />

## How to Run Simulations
1. Download the `.asc` simulation file from this repository.
2. Open with **LTspice**.
3. Run `.ac` analysis for stability checking or `.tran` for time-domain transient behavior.
