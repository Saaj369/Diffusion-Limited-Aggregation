# Diffusion-Limited-Aggregation
This project explores DFA and fractal analysis using langevin dynamics simulation. The project was done by my group which consisted of my friend Hridhay and me,  as part of final project for course "Computational Physics." 

This project demonstrates **Diffusion-Limited Aggregation (DLA)** of particles using **Langevin Dynamics**. It simulates how particles performing Brownian motion aggregate over time to form complex fractal-like structures. The model incorporates realistic thermal noise and damping using the underdamped Langevin equation.

## 📁 Files

- `CP_PROJECT_DLA_FINAL.ipynb`  
  This notebook contains implementation of Witter and Sander method which uses Monte Carlo techniques on a 2D lattice. For more information look at the report.

- `Langevin_method.ipynb`  
  This notebooks attempts to solve the langevin equation to simulate brownian motion of particles using BAOAB method.

- `Comp_final_report_Sajan_hridhay.pdf`  
  Final project report with theory, implementation details, results, and conclusions.

## 🧠 Key Concepts

- **Witter and Sander method** implementation.
- **Langevin Dynamics** for modeling Brownian motion.
- **Stochastic Differential Equations** to capture thermal noise and inertia.
- **Diffusion-Limited Aggregation (DLA)** to simulate aggregation of particles.
- **Fractal growth** observed in the final structures.
  
## Videos
<video src="simulation_videos/agg.mp4" controls width="500"></video>
<video src="simulation_videos/1000P.mp4" controls width="500"></video>
<video src="simulation_videos/5000P.mp4" controls width="500"></video>

## Authors
  - Hridhay Alat
  - Sajan Daheriya
    
## 🛠️ Requirements

Install the necessary packages with:

```bash
pip install numpy matplotlib
