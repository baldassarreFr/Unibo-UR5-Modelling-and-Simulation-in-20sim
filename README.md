# UR5 — Modelling & Simulation in 20-sim

**Author:** Francesco Baldassarre — 2025

## What this is
Compact project that models a UR5-like 6-DOF arm in **20-sim**, implements joint-space trajectory generation and basic feedback control via PID, and provides simulation scenarios.

## Key highlights
- Rigid-body kinematics & dynamics (DH-based parameters).  
- Quintic trajectory generator + PID (optional computed-torque).  
- Scenarios: trajectory tracking, disturbance, payload change.  

## Run (high-level)
1. Open one of the model files in **20-sim** (requires a license).  
2. Select an experiment (in `sim/`) and run.
