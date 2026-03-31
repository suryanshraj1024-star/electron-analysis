# Electron Source Numerical Modeling for Electric Propulsion

## Overview

This project develops a numerical model of an electron source used in electric propulsion systems. It captures key physical processes such as thermionic emission, plasma sheath formation, and one-dimensional plasma transport to simulate the behavior of electron emitters under realistic conditions.

The model is modular, physically grounded, and produces results consistent with established theoretical expectations.

---

## Key Features

* Thermionic emission modeling using the Richardson–Dushman equation
* Inclusion of Schottky effect for field-enhanced emission
* Self-consistent plasma sheath model with current balance
* One-dimensional quasi-neutral plasma column simulation
* Integrated framework combining emission, sheath, and plasma transport
* Configurable parameters for flexible experimentation

---

## Project Structure

* EmissionModel: Handles thermionic and field emission physics
* SheathModel: Computes sheath dynamics and current balance
* PlasmaColumn1D: Simulates plasma parameter variation along the column
* ElectronSourceSimulation: Integrates all modules into a unified workflow
* Visualization utilities for plotting and analysis

---

## Results

* Emission current density variation with temperature and applied voltage
* Sheath current balance under different operating conditions
* Spatial evolution of plasma properties along the discharge column

All results align with expected physical trends reported in standard plasma physics literature.

---

## Technologies Used

* Python
* NumPy
* Matplotlib

---


## Applications

* Electric propulsion (ion and Hall thrusters)
* Plasma source design
* Cathode and vacuum electronics modeling
* Computational plasma physics research

---

