# Quantum Simulation & Error Mitigation Projects 

This repository contains advanced simulations of Open Quantum Systems and Many-Body Physics, developed using **Qiskit**. The projects focus on benchmarking digital quantum simulation techniques (Trotterization), exploring exotic phases of matter (Quantum Scars), and implementing hybrid Quantum-Classical error mitigation strategies.

**Author:** Tomás Caetano  
**Stack:** Python, Qiskit, Scikit-Learn, NumPy, Matplotlib

---

##  Featured Projects

### 1. AI-Driven Error Mitigation on the Ising Model

An investigation into correcting hardware noise in NISQ devices using Machine Learning, compared against traditional physical mitigation methods.

* **Physics:** Transverse Field Ising Model (TFIM) time dynamics.
* **Techniques:**
    * **Trotterization:** First-order decomposition for time evolution.
    * **Zero-Noise Extrapolation (ZNE):** Implemented via Unitary Folding and Richardson Extrapolation.
    * **Deep ZNE (AI):** Trained a **Random Forest Regressor** to map noisy expectation values to ideal results.
* **Key Result:** The AI-driven approach significantly reduced the Root Mean Square Error (RMSE) compared to standard ZNE, effectively filtering out statistical variance while correcting bias.

### 2. Quantum Scars in the PXP Model (Rydberg Atoms)

A study of weak ergodicity breaking in constrained quantum systems, specifically modeling Rydberg atom arrays.

* **Physics:** PXP Hamiltonian (Rydberg Blockade mechanism).
* **Techniques:**
    * **Exact Diagonalization:** Benchmarking ground truth dynamics.
    * **Digital Simulation:** Implementing multi-controlled gates to mimic the kinetic constraints of the PXP model.
* **Key Result:** Successfully observed **Quantum Many-Body Scars**—periodic revivals of fidelity and magnetization when initializing the system in the Néel state ($|1010...\rangle$), violating the Eigenstate Thermalization Hypothesis (ETH).


##  Concepts Covered
* **Open Quantum Systems** & Decoherence
* **Hamiltonian Simulation** (Suzuki-Trotter)
* **Topological Order** & Surface Codes (Theoretical background)
* **Supervised Learning** for Quantum Error Correction

