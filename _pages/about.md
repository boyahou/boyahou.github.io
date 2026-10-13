---
permalink: /
title: "Boya Hou"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
.pub-tabs button {
  padding: 0.35em 1em; margin-right: 0.4em; background: none;
  border: 1px solid #ccc; border-radius: 6px; cursor: pointer; font-size: 0.9em;
}
.pub-tabs button.on { border-color: #52adc8; color: #52adc8; font-weight: 600; }
.pub-panel { display: none; padding-top: 0.8em; }
.pub-panel.on { display: block; }
</style>

I am a postdoctoral research associate at the University of Illinois Urbana-Champaign (UIUC), working with Prof. Maxim Raginsky and Prof. Olgica Milenkovic. Prior to this, I received my Ph.D in Electrical and Computer Engineering at UIUC advised by Prof. Subhonmesh Bose. I obtained B.Eng. in Electrical Engineering from Zhejiang University. 


# Research

My research focuses on developing machine learning methods for complex systems across science and engineering, spanning learning, probabilistic sampling, control, and stability analysis. Drawing on machine learning, operator theory, control and dynamical systems, I take a unified approach to these problems through learned operator representations that govern the evolution of functions or distributions. These operators are linear even when the underlying system is nonlinear. I construct them from trajectory data with finite-sample guarantees, and exploit their structure to design efficient algorithms for each task, with provable guarantees that black-box models do not offer. Active research directions include:

- **Operator learning with finite-sample guarantees:** learning operator representations of nonlinear dynamical systems from trajectory data, with compression, multi-agent, and online algorithms that scale to large, distributed and streaming data, applied to data-driven decision-making.
- **Operator-guided probabilistic sampling:** sampling trajectories of diffusion processes by integrating operator learning with optimal stochastic control, with applications to transition path sampling in molecular dynamics, and potential extension to problems that share its mathematical foundations, such as generative modeling with diffusion models and Schrödinger bridges.
- **Applications in scientific AI and engineering:** molecular and cellular dynamics, analysis of drug intervention, and power grid operations.
- **Dynamical systems for AI:** e.g., data attribution and unlearning for LLMs.


# Publications

\* co-first authors

<div class="pub-tabs"><button class="on" data-p="panel-sel">Selected</button><button data-p="panel-all">Full list</button></div>

<div class="pub-panel on" id="panel-sel" markdown="1">

### 📄 Nonparametric Sparse Online Learning of the Koopman Operator. 
*To appear in SIAM Journal on Control and Optimization (SICON), 2026*  [download](https://arxiv.org/abs/2405.07432)  
**B. Hou**, S. Sanjari, N. Dahlin, A. Koppel, S. Bose  

### 📄 Sparse Learning of Dynamical Systems in Reproducing Kernel Hilbert Space: An Operator-Theoretic Approach. 
*Proceedings of the 40th International Conference on Machine Learning (ICML), 2023*  [download](https://proceedings.mlr.press/v202/hou23c.html)  
**B. Hou**, S. Sanjari, N. Dahlin, S. Bose, U. Vaidya  

### 📄 Transition Path Sampling Using Koopman Operators and Exit-Time Optimal Control. 
*In submission, 2026. Short version accepted at a NeurIPS 2026 workshop.*  [download](https://arxiv.org/pdf/2610.10054) 
**B. Hou**\*, S. Wang\*, S. Ambekar, M. Raginsky, O. Milenkovic  

### 📄 Spatially-Coupled Network RNA Velocities: A Control-Theoretic Perspective. 
*In submission, 2026.*  [download](https://arxiv.org/pdf/2601.01018) 
**B. Hou**, M. Raginsky, A. Pandey, O. Milenkovic  

</div>

<div class="pub-panel" id="panel-all" markdown="1">

#### Journal Articles

- **B. Hou**, S. Sanjari, N. Dahlin, A. Koppel, S. Bose. Nonparametric Sparse Online Learning of the Koopman Operator.  
*SIAM Journal on Control and Optimization*, to appear, 2026. [download](https://arxiv.org/abs/2405.07432).  
- J. Lee, B. Hamzi, **B. Hou**, H. Owhadi, G. Santin, U. Vaidya. Kernel Methods for the Approximation of the Eigenfunctions of the Koopman Operator. *Physica D: Nonlinear Phenomena*, 2025. [download](https://www.sciencedirect.com/science/article/abs/pii/S0167278925001411).  
- A. Reddy Ramapuram Matavalam, **B. Hou**, H. Choi, S. Bose, U. Vaidya. Data-Driven Transient Stability Analysis Using the Koopman Operator.   *International Journal of Electrical Power and Energy Systems*, 2024. [download](https://www.sciencedirect.com/science/article/pii/S0142061524005301).
- **B. Hou**, A. Reddy Ramapuram Matavalam, S. Bose, U. Vaidya. Propagating Uncertainty Through System Dynamics in Reproducing Kernel Hilbert Space.  
*Physica D: Nonlinear Phenomena*, 2024. [download](https://www.sciencedirect.com/science/article/pii/S0167278924001192?via%3Dihub).
- **B. Hou**, S. Bose, L. Marla, K. Haran. Impact of Aviation Electrification on Airports: Flight Scheduling and Charging.    
*IEEE Transactions on Intelligent Transportation Systems*, 2023. [download](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10296862).

#### Conference Proceedings

- **B. Hou**, S. Sanjari, N. Dahlin, S. Bose, U. Vaidya. Sparse Learning of Dynamical Systems in Reproducing Kernel Hilbert Space: An Operator-Theoretic Approach.  
*ICML*, 2023. [download](https://proceedings.mlr.press/v202/hou23c.html). 
- **B. Hou**, S. Sanjari, N. Dahlin, S. Bose. Compressed Decentralized Learning of Conditional Mean Embedding Operators in Reproducing Kernel Hilbert Space.  
*AAAI*, 2023. [download](https://ojs.aaai.org/index.php/AAAI/article/view/25956).
- **B. Hou**, S. Bose, U. Vaidya. Sparse Learning of Kernel Transfer Operators.  
*Asilomar Conference on Signals, Systems, and Computers*, 2021. [download](https://ieeexplore.ieee.org/abstract/document/9723412)
- **B. Hou**, S. Bose, K. Haran. Powering Electric Aircraft at O'Hare Airport: A Case Study.  
*IEEE PES General Meeting*, 2020. [download](https://ieeexplore.ieee.org/abstract/document/9281871)

#### Preprints

- **B. Hou**\*, S. Wang\*, S. Ambekar, M. Raginsky, O. Milenkovic. Transition Path Sampling Using Koopman Operators and Exit-Time Optimal Control. [download](https://arxiv.org/pdf/2610.10054) 
- **B. Hou**, M. Raginsky, A. Pandey, O. Milenkovic. Spatially-Coupled Network RNA Velocities: A Control-Theoretic Perspective. [download](https://arxiv.org/pdf/2601.01018)
- **B. Hou**, M. Raginsky. A Behavioral Framework for Data-Driven Modeling of Nonlinear Systems in Vector-Valued Reproducing Kernel Hilbert Spaces.[download](../assets/Hou26b.pdf).
- P. Niu\*, E. Ma\*, **B. Hou**\*, H. Zhou, D. Zhou, H. Zhang, R. Etesami, O. Milenkovic. GUARD: Guided Unlearning and Retention via Data Attribution for Large Language Models.


</div>

<script>
document.querySelectorAll('.pub-tabs button').forEach(function (b) {
  b.addEventListener('click', function () {
    document.querySelectorAll('.pub-tabs button, .pub-panel').forEach(function (e) { e.classList.remove('on'); });
    b.classList.add('on');
    document.getElementById(b.dataset.p).classList.add('on');
  });
});
</script>

# Selected Awards
- Best Poster Award, Power Systems Engineering Research Center (PSERC), 2024
- Rising Stars in EECS, 2023
- M.A.Pai Scholarship, 2023
-	Mavis Future Faculty Fellows (MF3), 2023-2024


# Fun
Outside of mathematics and engineering, I pursue my passion for dancing. I performed contemporary ballet and dance of the Han-Tang dynasties (a subcategory of Classical Chinese Dance) with the Champaign Park District and Zhejiang Wenqin Art Troupe. 

[View rehearsal photos](/dance/)
