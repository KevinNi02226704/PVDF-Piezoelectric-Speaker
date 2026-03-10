# 🔊 PVDF Speaker

This project investigates a **PVDF membrane loudspeaker** driven by piezoelectric-like excitation.  
A multiphysics simulation was developed in **COMSOL Multiphysics** to analyze the acoustic frequency response of a thin PVDF film acting as a sound radiator.

The repository also includes a **demonstration video of a fabricated PVDF speaker prototype**.

---

# 📌 Project Overview

Polyvinylidene fluoride (PVDF) is a flexible polymer with strong piezoelectric properties.  
When an electric field is applied across the polarized PVDF film, the material undergoes mechanical deformation, generating acoustic waves.

Because PVDF membranes are extremely lightweight and flexible, they are well suited for:

- thin-film loudspeakers  
- distributed acoustic radiators  
- flexible audio devices  

This project models the **acoustic radiation behaviour of a PVDF membrane** and evaluates its **frequency response in the audible range**.

---

# 🧪 COMSOL Simulation

The acoustic behaviour of the PVDF membrane was simulated using **COMSOL Multiphysics**.

Two physics interfaces were coupled:

### Pressure Acoustics
Models the propagation of sound waves in the surrounding air domain.

### Electric Currents in Layered Shells
Used to represent the electrically driven PVDF membrane and approximate the piezoelectric actuation of the thin film.

The electric excitation induces mechanical vibration of the PVDF membrane, which radiates sound into the air domain.

The simulation allows analysis of:

- acoustic pressure distribution
- resonance behaviour of the membrane
- frequency response of the speaker

---

# 📂 Simulation File

The complete COMSOL model file can be downloaded here:

https://drive.google.com/file/d/1cucjNWUc4PI5Xn2MXHE5h17-gurCGMGb/view?usp=drive_link


---

# 🎥 Experimental Demonstration

A physical prototype of the PVDF speaker was fabricated and tested.

The repository includes a **video demonstrating the sound emission of the PVDF membrane speaker**.

---
