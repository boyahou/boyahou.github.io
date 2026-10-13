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
.research-tagline { font-size: 1.1em; margin-bottom: 1em; }
.research-grid { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 0.8em; margin-bottom: 1.5em; }
.research-card { border: 1px solid #ddd; border-left: 4px solid #52adc8; border-radius: 6px; padding: 0.7em 0.9em; }
.research-card h3 { margin: 0 0 0.3em; font-size: 1em; }
.research-card p { margin: 0 0 0.5em; font-size: 0.88em; }
.research-card .tags { margin: 0; font-size: 0.78em; color: #777; }
.pub { margin-bottom: 1.3em; padding-left: 0.8em; border-left: 3px solid #e5e5e5; }
.pub-title { font-weight: 700; line-height: 1.35; }
.pub-authors, .pub-venue { font-size: 0.9em; line-height: 1.5; }
.pub-venue i { color: #555; }
.pub-summary { font-size: 0.85em; color: #666; margin-top: 0.25em; }
.pub-btn { display: inline-block; font-size: 0.8em; padding: 0 0.55em; margin-left: 0.3em;
  border: 1px solid #52adc8; border-radius: 4px; text-decoration: none !important; }
@media (max-width: 600px) { .research-grid { grid-template-columns: 1fr; } }
</style>

I am a postdoctoral research associate at the Coordinated Science Laboratory, UIUC, working with Prof. Maxim Raginsky and Prof. Olgica Milenkovic. I received my Ph.D. in ECE from UIUC in 2024 (advisor: Prof. Subhonmesh Bose) and my B.Eng. from Zhejiang University.

**I am on the 2026–2027 academic job market.** [CV](../assets/CV.pdf) · [Research statement](../assets/research_statement.pdf)

# Research

<p class="research-tagline">Machine learning with provable guarantees for complex dynamical systems, built on <b>learned operator representations</b>.</p>

<div class="research-grid">
  <div class="research-card">
    <h3>Operator Learning</h3>
    <p>Linear operator models of nonlinear systems, learned from data with finite-sample guarantees.</p>
    <p class="tags">compression · decentralized · online</p>
  </div>
  <div class="research-card">
    <h3>Probabilistic Sampling</h3>
    <p>Steering diffusion processes toward rare events via optimal stochastic control.</p>
    <p class="tags">transition path sampling · molecular dynamics</p>
  </div>
  <div class="research-card">
    <h3>Applications</h3>
    <p>Scientific and engineering systems.</p>
    <p class="tags">cellular dynamics · drug intervention · power grids</p>
  </div>
  <div class="research-card">
    <h3>Dynamical Systems for AI</h3>
    <p>Dynamical-systems tools for understanding model training.</p>
    <p class="tags">data attribution · LLM unlearning</p>
  </div>
</div>

# Publications

\* co-first authors

<div class="pub-tabs"><button class="on" data-p="panel-sel">Selected</button><button data-p="panel-all">Full list</button></div>

<div class="pub-panel on" id="panel-sel">
  <div class="pub">
    <div class="pub-title">Transition Path Sampling Using Koopman Operators and Exit-Time Optimal Control</div>
    <div class="pub-authors"><b>B. Hou</b>*, S. Wang*, S. Ambekar, M. Raginsky, O. Milenkovic</div>
    <div class="pub-venue"><i>In submission, 2026 · Short version at a NeurIPS 2026 workshop</i> <a class="pub-btn" href="LINK">Preprint</a></div>
    <div class="pub-summary">Samples rare molecular transitions by solving a single convex problem, with no neural-network training. Validated on alanine dipeptide.</div>
  </div>
  <div class="pub">
    <div class="pub-title">Nonparametric Sparse Online Learning of the Koopman Operator</div>
    <div class="pub-authors"><b>B. Hou</b>, S. Sanjari, N. Dahlin, A. Koppel, S. Bose</div>
    <div class="pub-venue"><i>SIAM Journal on Control and Optimization (SICON), to appear, 2026</i> <a class="pub-btn" href="https://arxiv.org/abs/2405.07432">Preprint</a></div>
    <div class="pub-summary">The first online algorithm for learning linear operators with provable guarantees.</div>
  </div>
  <div class="pub">
    <div class="pub-title">Sparse Learning of Dynamical Systems in Reproducing Kernel Hilbert Space: An Operator-Theoretic Approach</div>
    <div class="pub-authors"><b>B. Hou</b>, S. Sanjari, N. Dahlin, S. Bose, U. Vaidya</div>
    <div class="pub-venue"><i>International Conference on Machine Learning (ICML), 2023</i> <a class="pub-btn" href="https://proceedings.mlr.press/v202/hou23c.html">Paper</a></div>
    <div class="pub-summary">The first finite-sample guarantees for learning these operators from trajectory data.</div>
  </div>
  <div class="pub">
    <div class="pub-title">Spatially-Coupled Network RNA Velocities: A Control-Theoretic Perspective</div>
    <div class="pub-authors"><b>B. Hou</b>, M. Raginsky, A. Pandey, O. Milenkovic</div>
    <div class="pub-venue"><i>Under review at IEEE Transactions on Control of Network Systems, 2026</i> <a class="pub-btn" href="LINK">Preprint</a></div>
    <div class="pub-summary">A network model of cell dynamics that couples gene regulation with cell–cell interactions, developed in collaboration with AbbVie.</div>
  </div>
</div>

<div class="pub-panel" id="panel-all" markdown="1">

#### Journal Articles

- **B. Hou**, S. Sanjari, N. Dahlin, A. Koppel, S. Bose. [Nonparametric Sparse Online Learning of the Koopman Operator](https://arxiv.org/abs/2405.07432). *SIAM Journal on Control and Optimization*, to appear, 2026.
- J. Lee, B. Hamzi, **B. Hou**, H. Owhadi, G. Santin, U. Vaidya. Kernel Methods for the Approximation of the Eigenfunctions of the Koopman Operator. *Physica D: Nonlinear Phenomena*, 2025.
- A. Reddy Ramapuram Matavalam, **B. Hou**, H. Choi, S. Bose, U. Vaidya. Data-Driven Transient Stability Analysis Using the Koopman Operator. *International Journal of Electrical Power and Energy Systems*, 2024.
- **B. Hou**, A. Reddy Ramapuram Matavalam, S. Bose, U. Vaidya. Propagating Uncertainty Through System Dynamics in Reproducing Kernel Hilbert Space. *Physica D: Nonlinear Phenomena*, 2024.
- **B. Hou**, S. Bose, L. Marla, K. Haran. Impact of Aviation Electrification on Airports: Flight Scheduling and Charging. *IEEE Transactions on Intelligent Transportation Systems*, 2023.

#### Conference Proceedings

- **B. Hou**, S. Sanjari, N. Dahlin, S. Bose, U. Vaidya. [Sparse Learning of Dynamical Systems in Reproducing Kernel Hilbert Space: An Operator-Theoretic Approach](https://proceedings.mlr.press/v202/hou23c.html). *ICML*, 2023.
- **B. Hou**, S. Sanjari, N. Dahlin, S. Bose. [Compressed Decentralized Learning of Conditional Mean Embedding Operators in Reproducing Kernel Hilbert Space](https://ojs.aaai.org/index.php/AAAI/article/view/25956). *AAAI*, 2023.
- **B. Hou**, S. Bose, U. Vaidya. Sparse Learning of Kernel Transfer Operators. *Asilomar Conference on Signals, Systems, and Computers*, 2021.
- **B. Hou**, S. Bose, K. Haran. Powering Electric Aircraft at O'Hare Airport: A Case Study. *IEEE PES General Meeting*, 2020.

#### Preprints

- **B. Hou**\*, S. Wang\*, S. Ambekar, M. Raginsky, O. Milenkovic. Transition Path Sampling Using Koopman Operators and Exit-Time Optimal Control. In submission, 2026. Short version accepted at a NeurIPS 2026 workshop.
- **B. Hou**, M. Raginsky, A. Pandey, O. Milenkovic. Spatially-Coupled Network RNA Velocities: A Control-Theoretic Perspective. Under review at *IEEE Transactions on Control of Network Systems*, 2026.
- **B. Hou**, M. Raginsky. [A Behavioral Framework for Data-Driven Modeling of Nonlinear Systems in Vector-Valued Reproducing Kernel Hilbert Spaces](../assets/Hou26b.pdf). Under revision at *IEEE Transactions on Automatic Control*, 2026.
- P. Niu\*, E. Ma\*, **B. Hou**\*, H. Zhou, D. Zhou, H. Zhang, R. Etesami, O. Milenkovic. GUARD: Guided Unlearning and Retention via Data Attribution for Large Language Models. In submission, 2026.

#### Monograph (in preparation)

- **B. Hou**, S. Bose, N. Dahlin, U. Vaidya. Kernel Method for Learning Dynamical Systems. [Sample chapters](LINK).

#### Workshops and Posters

- **B. Hou**, M. Raginsky, A. Pandey, O. Milenkovic. Multi Network RNA Velocity. *NITMB MathBio Convergence Conference*, 2025.
- **B. Hou**, A. Reddy Ramapuram Matavalam, S. Bose, U. Vaidya. Propagating Uncertainty Through System Dynamics in Reproducing Kernel Hilbert Space. Late-breaking poster, *American Control Conference*, 2023.

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

[Google Scholar](LINK)

# Awards

- NITMB Early Career Travel Award, 2025
- Best Poster Award, PSERC Industry Advisory Board Meeting, 2024
- Mavis Future Faculty Fellow, UIUC, 2023–2024
- Rising Stars in EECS, 2023
- M. A. Pai Scholarship, UIUC, 2023
- AAAI Student Scholarship, 2023
- Second Place, USAEE Case Competition, 2019

# Fun
Outside of mathematics and engineering, I pursue my passion for dancing. I performed contemporary ballet and dance of the Han-Tang dynasties (a subcategory of Classical Chinese Dance) with the Champaign Park District and Zhejiang Wenqin Art Troupe. 

[View rehearsal photos](/dance/)

