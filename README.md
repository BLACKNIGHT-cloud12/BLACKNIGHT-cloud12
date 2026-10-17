<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a2e,50:1a1a4e,100:3b82f6&height=220&section=header&text=Soumik%20Ghosh&fontSize=50&fontColor=ffffff&fontAlignY=35&desc=Scientific%20Machine%20Learning%20(SciML)%20·%20Computational%20Fluid%20Dynamics%20·%20Quant&descSize=17&descAlignY=55&animation=fadeIn" width="100%" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Physics-Informed+Neural+Operators+(PINO%2C+FNO)+%26+DeepONet;Data-Driven+Turbulence+Closures+(TBNN+%2B+OpenFOAM+v2606);Sub-Millisecond+Aerodynamic+Surrogates+%26+MDAO;NTK+Spectral+Bias+Analysis+in+Physics-Informed+NNs;Where+Navier-Stokes+meets+Deep+Learning" alt="Typing SVG" />
</a>

<p align="center">
  <a href="https://linkedin.com/in/soumik-ghosh-434164377"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:soumikghosh30.03.07@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/BLACKNIGHT-cloud12"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

</div>

---

# Hey, I'm Soumik Ghosh 🧪✈️📈

I am a **Scientific Machine Learning (SciML) and Computational Engineering** practitioner working at the intersection of **fluid dynamics, physics-informed deep learning, and quantitative modeling**.

My work focuses on building architectures that do not treat physical systems as black-box interpolators, but instead respect the underlying conservation laws (Navier-Stokes mass, momentum, and energy conservation, frame indifference, and thermodynamics).

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/b/b3/Karman_vortex_street_animation.gif" alt="CFD Flow Field Simulation" width="48%" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/f5/Geometric_Brownian_Motion_paths.gif" alt="Quantitative Numerical Calculation" width="48%" />
</p>

---

## 🌟 Featured Engineering & Research Projects

<table>

<tr>
<td width="50%" valign="top">

### ✈️ [NeuroFoil: Industrial SciML Aerodynamic Platform](https://github.com/BLACKNIGHT-cloud12/NeuroFoil)
**End-to-end automated OpenFOAM-to-SciML surrogate and design platform**
* Predicts aerodynamic lift ($C_L$), drag ($C_D$), moment ($C_m$), and continuous 161-point surface pressure fields $C_p(x)$ with sub-millisecond latency ($R^2 = 0.992$).
* Coupled **Aero-Structural Wingbox Mechanics**: Sizing front/rear spar web depths, inter-spar fuel tank volume, and cross-sectional bending moment of inertia ($I_{xx}$).
* **Epistemic Uncertainty Quantification (UQ)**: Mahalanobis distance OOD detection against the training manifold covariance matrix with 95% conformal prediction bands.
* **MDAO SLSQP Optimizer**: Constrained inverse design discovering optimal profiles under combined aerodynamic and structural bounds.

`Python` `OpenFOAM v2606` `PyTorch` `SciPy` `Streamlit` `MDAO` `WSL2`

</td>

<td width="50%" valign="top">

### 🌪️ [tbnnFoam: Data-Driven Turbulence Closures in OpenFOAM](https://github.com/BLACKNIGHT-cloud12/tbnnFoam)
**Galilean-invariant Tensor Basis Neural Networks for RANS Reynolds stress anisotropy**
* Couples Pope's tensor basis representation with OpenFOAM's $k$-$\omega$ SST and RANS framework to predict the anisotropic Reynolds stress tensor discrepancy $\tau_{ij}^\Delta$.
* Enforces material frame indifference (objectivity) and Galilean invariance under spatial rotations, addressing the failure of linear eddy-viscosity Boussinesq closures under strong adverse pressure gradients.
* Integrated into OpenFOAM C++ solver loops via LibTorch runtime bindings.

`C++` `OpenFOAM` `LibTorch` `PyTorch` `Turbulence Modeling` `Tensor Algebra`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🎯 [TO-PINN-Aerodynamics: Unsupervised Aerodynamic Topology Optimization](https://github.com/BLACKNIGHT-cloud12/TO-PINN-Aerodynamics)
**Topology optimization directly governed by Navier-Stokes PDE loss constraints**
* Formulates aerodynamic shape and topology optimization as an unsupervised continuous field learning problem without relying on costly discrete adjoint CFD solvers.
* Embeds density penalty methods (SIMP) directly within Physics-Informed Neural Network (PINN) loss formulations.
* Discovers minimum drag topologies under volume fraction constraints.

`Python` `PyTorch` `PINNs` `Automatic Differentiation` `Topology Optimization`

</td>

<td width="50%" valign="top">

### 📐 [NTK-PTC: Spectral Bias Control in PINNs](https://github.com/BLACKNIGHT-cloud12/NTK-PTC-Research-Paper)
**Neural Tangent Kernel (NTK) analysis & Phase Transition Control for stiff PDEs**
* Investigates the spectral bias and eigenvalue decay of the empirical Neural Tangent Kernel in Physics-Informed Neural Networks applied to convective and stiff boundary layer problems.
* Develops dynamic loss balancing algorithms based on NTK trace alignment to prevent optimization collapse during high-frequency physical transitions.

`Python` `PyTorch` `NTK Theory` `Stiff PDEs` `Numerical Analysis`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🌊 [AeroPINO: Physics-Informed Neural Operator for Aerodynamics](https://github.com/BLACKNIGHT-cloud12/AeroPINO)
**Mesh-independent flow field mapping using Fourier Neural Operators (FNO)**
* Combines data-driven Fourier Neural Operators with physics-informed PDE residual penalties (PINO) to learn continuous velocity and pressure fields over arbitrary body geometries.
* Achieves zero-shot super-resolution and transferability across grid resolutions.

`Python` `PyTorch` `Fourier Neural Operators (FNO)` `PINO` `SciML`

</td>

<td width="50%" valign="top">

### 📈 [Real Estate LOB SSM: Continuous-Time Market Depth Simulator](https://github.com/BLACKNIGHT-cloud12/real-estate-lob-ssm)
**Deep State Space Model (SSM) for Limit Order Book counterfactual simulations**
* Uses structured state space sequences (S4/Mamba architecture) to model continuous-time order flow arrival, microstructural liquidity, and bid-ask spread dynamics.
* Nested with an interactive Next.js cockpit for counterfactual liquidity shock testing.

`Python` `PyTorch` `State Space Models (SSM)` `Next.js` `TypeScript` `FastAPI`

</td>
</tr>

</table>

---

## 🔬 Core Technical & Research Focus

| Research Domain | Core Focus | Methodologies & Tooling |
| :--- | :--- | :--- |
| **Scientific Machine Learning (SciML)** | Physics-Informed Neural Networks, Operator Learning, NTK Spectral Bias | PINNs, DeepONet, Fourier Neural Operators (FNO), PINO, JAX |
| **CFD & Turbulence Modeling** | Data-driven closures, structured boundary layer meshing, Reynolds stress | OpenFOAM (v2206/v2606), $k$-$\omega$ SST, TBNN, $y^+ \le 1$ C-Grids |
| **Aerodynamic Design & MDAO** | Parametric shape exploration, aero-structural wingbox sizing, inverse design | Kulfan CST, SLSQP, Area Moment of Inertia $I_{xx}$, Beam Sizing |
| **Uncertainty Quantification (UQ)** | Conformal prediction intervals, out-of-distribution detection in physics | Mahalanobis distance, Deep Ensembles, Covariance manifolds |
| **Foundation Models & Quant Systems** | Parameter-efficient fine-tuning, continuous-time state space models | Gemma post-training (PEFT/LoRA), S4 / Mamba, Stochastic Calculus |

---

## ⚡ Technical Stack

<table>
<tr>
<td width="50%">

**💻 Languages & Systems**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![WSL2](https://img.shields.io/badge/-WSL2-0078D6?style=flat-square&logo=windows&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

</td>
<td width="50%">

**🤖 Machine Learning & SciML**

![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![JAX](https://img.shields.io/badge/-JAX-005571?style=flat-square&logoColor=white)
![SciPy](https://img.shields.io/badge/-SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/-Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

</td>
</tr>
<tr>
<td width="50%">

**🔬 Computational Fluid Dynamics & Engineering**

![OpenFOAM](https://img.shields.io/badge/-OpenFOAM-1E90FF?style=flat-square&logoColor=white)
![Paraview](https://img.shields.io/badge/-ParaView-2C3E50?style=flat-square&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat-square&logoColor=white)
![Turbulence Modeling](https://img.shields.io/badge/-k--ω_SST_|_RANS-0284C7?style=flat-square&logoColor=white)

</td>
<td width="50%">

**⚙️ Production & Application Deployment**

![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
</tr>
</table>

---

## 📊 GitHub Analytics & Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=BLACKNIGHT-cloud12&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0B1120&title_color=38BDF8&text_color=94A3B8&icon_color=38BDF8" alt="GitHub Stats" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BLACKNIGHT-cloud12&layout=compact&theme=tokyonight&hide_border=true&bg_color=0B1120&title_color=38BDF8&text_color=94A3B8" alt="Top Languages" width="45%" />

</div>

---

## 📚 Foundational Literature & Influences

> *"The purpose of computing is insight, not numbers."* — Richard W. Hamming

| Field | Seminal Reference | Engineering Significance |
| :--- | :--- | :--- |
| **PINNs** | **Raissi et al. (2019)** — *Physics-Informed Neural Networks* | Core paradigm of embedding PDE residuals into computational loss functions. |
| **Neural Operators** | **Lu et al. (2021)** — *Learning Nonlinear Operators via DeepONet* | Universal approximation of nonlinear continuous operators across function spaces. |
| **Spectral Solvers** | **Li et al. (2020)** — *Fourier Neural Operator for Parametric PDEs* | Mesh-independent parameterization of integral kernels directly in Fourier domain. |
| **Turbulence ML** | **Ling, Kurzawski & Templeton (2016)** — *Reynolds Stress Anisotropy (TBNN)* | Embedding Galilean and rotational tensor invariance into neural turbulence closures. |
| **Data-Driven Dynamics**| **Brunton & Kutz** — *Data-Driven Science and Engineering* | Synthesis of system identification (SINDy), Koopman operator theory, and control. |
| **Quantitative Calculus**| **Paul Wilmott** — *On Quantitative Finance* | Stochastic differential equations, Fokker-Planck PDEs, and martingale pricing. |

---

<div align="center">

**Open to collaborations in Scientific Machine Learning, Physics-Informed AI, and Aerodynamic Engineering.**

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/soumik-ghosh-434164377)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:soumikghosh30.03.07@gmail.com)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/BLACKNIGHT-cloud12)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a2e,50:1a1a4e,100:3b82f6&height=120&section=footer" width="100%" />

</div>
