# Engineering_Design_Project_Simulator
Made an simulator software that can do calculations and simulations for me instead of doing it manually via excel as done in university. 

An interactive engineering tool for analyzing projectile motion, static beam loading, dynamic impact loading (DMF), and material failure predictions, inspired by engineering design project coursework.
Built using Python, NumPy, Matplotlib, and a fully interactive Gradio GUI.

---

# Features:
## 1. Projectile Simulator
  -No-drag + drag trajectories
  -Comparison plot
  -Adjustable: velocity, angle, mass, Cd, air density, diameter
  -Shows both drag & no-drag ranges

## 2. Multi-Angle / Multi-Velocity Optimizer
  -Sweep angles or velocities
  -Plots all trajectories
  -Automatically highlights the maximum-range trajectory

## 3.Static Load Failure Analysis
  -Computes static bending stress and failure load
  -Supports rectangular & circular cross-sections
  -MM-based input (mm, MPa) to match lab data
  Includes:
  -Load vs Span graph
  -Load vs Square Section Size graph

## 4. Dynamic Impact (DMF) Failure Analysis
  -Impact velocity from drop height
  -Static deflection
  -DMF (Dynamic Magnification Factor)
  -Dynamic stress under sudden loading\

---
