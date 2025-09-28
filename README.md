## 🧰 How to Use This Template    

Click the green **"Use this template"** button at the top of the page, then choose **"Create a new repository"**.   

This will create your own copy of this project, which you can modify freely — no need to fork!   

---

***Table of Contents***


---    

## 1. About this repository

This repository contains the research article **“Temperature Distribution in a Gaussian End-Pumped Nonlinear KTP Crystal: the Temperature Dependence of Thermal Conductivity and Radiation Boundary Condition”**, together with supporting source code, numerical results, and reproducibility assets.  


Continuous-wave (CW) second harmonic generation in nonlinear crystals is strongly affected by heat dissipation. This work analyzes the **transient temperature distribution** in a KTP crystal under Gaussian end-pumping by solving the nonlinear, inhomogeneous heat equation. Unlike many earlier models, the study incorporates:  

- **Temperature-dependent thermal conductivity** of KTP  
- **Convective and radiative boundary conditions** at crystal surfaces  

A finite difference method (FDM) solver was implemented to numerically evaluate the system. Results show that neglecting thermal conductivity variations leads to significant temperature prediction errors, and while radiative effects are negligible in thin crystals, they become relevant for larger geometries with wide pump beams. These findings improve modeling accuracy for **thermal lensing, phase mismatching, and efficiency reduction** in nonlinear optical systems.  

---



## 2. Directory Structure

```
Folder PATH listing
+---1. Cite Us                    <-- Contains citation materials and papers
│       1_Heat-Equation_Continu…  <-- Heat equation analytical paper
│       2_Heat-Equation_Continu…  <-- Heat equation continuous wave paper
│       3_Heat-Equation_Pulsed-…  <-- Heat equation pulsed wave paper
│       4_Phase-Mismatch_Pulsed…  <-- Phase mismatch pulsed wave paper
│       5_Ideal_Continuous-Wave…  <-- Ideal continuous wave paper
│       6_Ideal_Pulsed-Wave_Be…   <-- Ideal pulsed wave Bessel paper
│       7_Coupled_Continuous-Wa…  <-- Coupled continuous wave paper
│       README.md                 <-- Citation guidelines and information
│
+---2. Code_Results               <-- Contains source code and results
│       2_Heat-Equation_Continu…  <-- Fortran finite difference solver
│       +---2_Results             <-- Numerical simulation results
│       │       ST_085_time_1_T_r.plt  <-- Radial temperature data
│       │       ST_085_time_1_T_t.plt  <-- Transverse temperature data
│       │       ST_085_time_1_T_z.plt  <-- Axial temperature data
│       │
│
│       2_Heat-Equation_Continu…  <-- Main research paper PDF
│       CITATION.cff              <-- Citation metadata file
│       LICENSE                   <-- Project license information
│       README.md                 <-- Project overview and documentation
│

```

## 3. How to Cite Us
Please refer to the [**0. Cite Us**](https://github.com/Mostafa-M-Rezaee/SHG__Second_Harmonic_Generation/tree/main/0.%20Cite%20Us) folder for accurate citations. It contains essential guidelines for accurate referencing, ensuring accurate acknowledgement of our work.


## 4. For Additional Questions
If you have questions that are not covered in the resources above, the best way to reach [Mostafa Rezaee](https://www.linkedin.com/in/mostafa-rezaee/).    
- Gmail: mostafa.mohammadrezaee@gmail.com       
- [Linkedin](https://www.linkedin.com/in/mostafa-rezaee/)        
