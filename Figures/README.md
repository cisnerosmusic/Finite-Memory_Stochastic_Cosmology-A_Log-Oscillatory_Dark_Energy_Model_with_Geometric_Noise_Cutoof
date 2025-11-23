# Figures for *Finite-Memory Stochastic Cosmology (v3.2)*

This directory contains all publication-quality figures accompanying the preprint:

**Finite-Memory Stochastic Cosmology:  
A Log-Oscillatory Dark Energy Model with Geometric Noise Cutoff (v3.2)**

The figures illustrate the core components of the model:  
log-oscillatory dark energy, geometric noise suppression, and the finite-memory resilience valley.

---

## 📁 Contents

### **1. figura1_wz_amplitudes.pdf**
Equation of state \( w(z) \) for several oscillation amplitudes \( A \).  
Shows how finite-memory log-oscillations depart smoothly from \(\Lambda\)CDM.

### **2. figura2_cutoff_geometrico.pdf**
Geometric sigmoidal cutoff \( S(z) \) regulating stochastic noise activation around \( z_c \sim 4 \).  
Ensures early-universe smoothness and late-time stochastic activation.

### **3. figura3_valle_resiliencia.pdf**
3D resilience valley in the \((\tau H_0, \omega)\) parameter space.  
Displays the stability region where the product \( R = \tau H_0 \omega \in [0.5, 3.5] \) minimizes attractor variance.

### **4. figures_script.py**
Python script used to generate all figures (PDF + PNG).

---

## 🔧 How to Reproduce the Figures

Run the script:

```bash
python3 figures_script.py
