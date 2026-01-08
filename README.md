# Selected Research Projects in Experimental and Computational Photonics
### Hua Tu
#### Reader's Guide

This document presents three research projects in **hybrid quantum systems, nonlinear
photonics, and electro-optical engineering**, unified by a system-level philosophy that tightly
integrates optical dynamics, electronic interfaces, and control or learning algorithms.

**Part I** investigates chip-scale quantum noise detection through **shot-noise-limited balanced homodyne detection for thin-film lithium niobate (TFLN) squeezing experiments**. I
identified optical coupling, not electronic noise, as the dominant bottleneck and addressed it
through co-designed fiber-to-chip edge couplers, free-space mode matching, wideband RF
readout electronics, and common-mode rejection techniques to achieve shot-noise-limited
performance.

**Part II** develops a **hardware-in-the-loop nonlinear photonic computing platform** based on
second-harmonic generation. To enable gradient-based learning on non-differentiable optical
hardware, I introduced a framework combining a noise-aware, differentiable digital twin with
constraint-aware optimization. Using this approach, I demonstrated 85% accuracy on a vowel
recognition task, validating end-to-end trainable nonlinear optics.

**Part III** addresses **state-dependent dynamic control in precision photonic systems, using
microwave-to-optical (M2O) transduction** as a case study. I diagnosed repeated **Pound Drever Hall (PDH)** lock-unlock failures in **multi-cavity filter** chains as control-path mismatches. I combined hardware
and software, enabling robust, repeatable dynamic pump filtering. This capability is essential
for future single-photon-level quantum transduction.

Each part is self-contained and can be read independently.

Contents

Part I. **Shot-Noise-Limited BaIanced Homodyne Detection for TFLN Squeezing** (Page 2-8)
1. Bottlenecks in Integrated Squeezing Detection System
2. Fiber-to-Chip and Free-Space Coupling Optimization
3. Wideband RF Balanced Detector and Shot-Noise, CMRR Verification
4. 
Part II. **Hardware-in-the-Loop NonIinear Photonic Computing via SHG** (Page 9-14)
1. Fist Principle SHG-Based Physical Forward Operator
2. Noise-Aware Digital Twin and Surrogate Gradients
3. Lagrangian Constraint Optimization
4. Vowel Recognition Demonstration (85% accuracy)
5. Conclusions and Generalization
   
Part III. **Robust Dynamic Laser CIeaning for Microwave-to-Optical Transduction** (Page 15-
20)
1. Problem Statement: Dynamic Lock–Unlock Failure Modes
2. State-dependent Control Strategy and Software Interface
3. Custom Summing and Filtering Hardware
4. System-Level Performance and Implications

#### Technical Skills Demonstrated
Simulation/Design: Full 3D FDTD/EME simulations, KiCad PCB Layout, FreeCAD fabrication layouts. 
Software/AI: PyTorch, TensorFlow, Physics-Aware Training, surrogate gradient learning, automated lab control (Python/telnetlib). 
Hardware: Micro-soldering (castellated pads), RF impedance matching, analog circuit design.

These projects exemplify a **systems-first approach** to next-generation photonic technologies, where optical physics, electronics, and neural networks converge to unlock new capabilities in computation and sensing.

