---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .cv h2 { margin-top: 1.8em; padding-bottom: .3em; border-bottom: 1px solid var(--global-border-color); }
  .cv-entry { margin: 0 0 1.2em; }
  .cv-head { display: flex; align-items: baseline; gap: 0 1.5em; }
  .cv-role { flex: 1; font-weight: 700; }
  .cv-plain .cv-role { font-weight: 400; }
  .cv-date { flex: none; white-space: nowrap; color: var(--global-text-color-light); }
  @media (max-width: 600px) { .cv-head { flex-direction: column; } }
  .cv-org { font-style: italic; }
  .cv-org a { color: inherit; text-decoration: none; border-bottom: 1px solid #b9cbd1; }
  .cv-org a:hover, .cv-org a:focus { color: #2f7f93; border-bottom-color: #2f7f93; }
  html[data-theme="dark"] .cv-org a:hover,
  html[data-theme="dark"] .cv-org a:focus { color: #5cc6df; border-bottom-color: #5cc6df; }
  .cv-concentration { margin-top: .2em; font-size: .95em; line-height: 1.5; }
  .cv-concentration strong { font-weight: 600; }
  .cv-sup { margin-top: .1em; }
  .cv-sup a { color: #2f7f93; text-decoration: none; border-bottom: none; }
  .cv-sup a:hover { text-decoration: underline; }
  html[data-theme="dark"] .cv-sup a { color: #5cc6df; }
  .cv-entry ul { margin: .3em 0 0 1.2em; }
  .cv-entry li { margin-bottom: .2em; }
  .cv-skill { margin: 0 0 .4em; }
  .cv-group { font-weight: 700; color: #2f7f93; margin: 1.2em 0 .4em; }
  html[data-theme="dark"] .cv-group { color: #5cc6df; }
  .cv-cols { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); column-gap: 2.5em; row-gap: .3em; margin: 0 0 0 1.2em; padding: 0; }
</style>

<div class="cv" markdown="0">

<h2>Education</h2>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">Ph.D., Applied and Computational Mathematics</span><span class="cv-date">Expected 2028</span></div>
  <div class="cv-concentration"><strong>Concentration:</strong> Mathematics of Data Science</div>
  <div class="cv-org"><a href="https://www.odu.edu/" target="_blank" rel="noopener noreferrer">Old Dominion University</a>, Norfolk, VA, USA</div>
</div>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">M.S., Applied and Computational Mathematics</span><span class="cv-date">2023 – 2025</span></div>
  <div class="cv-org"><a href="https://www.odu.edu/" target="_blank" rel="noopener noreferrer">Old Dominion University</a>, Norfolk, VA, USA</div>
  <ul><li>Thesis: <em>Entropy and Gradient Stable Scheme for Hyperbolic Burgers’ Equation</em></li></ul>
</div>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">M.S., Mathematics</span><span class="cv-date">2019 – 2021</span></div>
  <div class="cv-org"><a href="https://www.comsats.edu.pk/" target="_blank" rel="noopener noreferrer">COMSATS University Islamabad</a>, Islamabad, Pakistan</div>
  <ul><li>Research: Flow features and force statistics for flow past multiple bluff bodies</li></ul>
</div>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">B.S., Mathematics</span><span class="cv-date">2014 – 2018</span></div>
  <div class="cv-org"><a href="https://www.iiu.edu.pk/" target="_blank" rel="noopener noreferrer">International Islamic University Islamabad</a>, Islamabad, Pakistan</div>
</div>

<h2>Research Experience</h2>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">Research Assistant, Applied Fluid Laboratory</span><span class="cv-date">Apr 2022 – Aug 2023</span></div>
  <div class="cv-org"><a href="https://en.knu.ac.kr/main/main.htm" target="_blank" rel="noopener noreferrer">Kyungpook National University</a>, Daegu, South Korea</div>
  <div class="cv-sup">Supervisor: <a href="https://scholar.google.com/citations?user=nBR6rDUAAAAJ&amp;hl=en" target="_blank" rel="noopener">Prof. Chang Hyun Sohn</a> · <a href="mailto:chsohn@knu.ac.kr">chsohn@knu.ac.kr</a></div>
  <ul>
    <li>Project: <em>Improved Energy Recovery Performance of Oscillating Wings Using Articulated and Flexible Bodies</em>, funded by the National Research Foundation of Korea (NRF).</li>
    <li>Performed high-Reynolds-number flow simulations using the Lattice Boltzmann Method (LBM).</li>
    <li>Developed GPU-accelerated C++ solvers for oscillating-wing energy-recovery applications.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">Research Assistant</span><span class="cv-date">Jan 2020 – Apr 2022</span></div>
  <div class="cv-org"><a href="https://www.comsats.edu.pk/" target="_blank" rel="noopener noreferrer">COMSATS University Islamabad</a>, Islamabad, Pakistan</div>
  <div class="cv-sup">Supervisor: <a href="https://scholar.google.com/citations?hl=en&amp;user=OAp3xVAAAAAJ&amp;view_op=list_works&amp;sortby=pubdate" target="_blank" rel="noopener">Prof. Shams ul Islam</a> · <a href="mailto:islam_shams@comsats.edu.pk">islam_shams@comsats.edu.pk</a></div>
  <ul>
    <li>Project: <em>Numerical Study of Wake and Thrust Around Multiple Cylinders at Moderate Reynolds Numbers for Various Configurations</em>, funded by the Higher Education Commission (HEC) of Pakistan.</li>
    <li>Developed single-relaxation-time Lattice Boltzmann (SRT-LBM) simulations in Fortran.</li>
    <li>Post-processed and visualized simulation results in MATLAB and Tecplot.</li>
  </ul>
</div>
<h2>Research Projects</h2>

<div class="cv-entry cv-plain">
  <div class="cv-head"><span class="cv-role">Stable Scheme for the Hyperbolic Burgers’ Equation</span><span class="cv-date">Jan 2024 – Present</span></div>
  <div class="cv-org">M.S. Thesis, <a href="https://www.odu.edu/" target="_blank" rel="noopener noreferrer">Old Dominion University</a></div>
</div>
<div class="cv-entry cv-plain">
  <div class="cv-head">
    <span class="cv-role">Convergence and Performance Comparison of Numerical Solvers for Sparse Resistor-Network Linear Systems</span>
    <span class="cv-date">Dec 2023</span>
  </div>
  <div class="cv-org">Graduate Coursework, <a href="https://www.odu.edu" target="_blank" rel="noopener">Old Dominion University</a></div>
</div>

<div class="cv-entry cv-plain">
  <div class="cv-head">
    <span class="cv-role">Image Processing and Compression Using Multiple Algorithms</span>
    <span class="cv-date">Dec 2023</span>
  </div>
  <div class="cv-org">Graduate Coursework, <a href="https://www.odu.edu" target="_blank" rel="noopener">Old Dominion University</a></div>
</div>

<h2>Talks and Presentations</h2>

<div class="cv-entry cv-plain">
  <div class="cv-head"><span class="cv-role">“Investigation of Flow Dynamics Around Bluff Bodies Using SRT-LBM”</span><span class="cv-date">Mar 2025</span></div>
  <div class="cv-org"><a href="https://mgo.syr.edu/conferences/past-conferences/2025-conference/" target="_blank" rel="noopener noreferrer">50th Annual New York State Regional Graduate Mathematics Conference</a>, <a href="https://www.syracuse.edu/" target="_blank" rel="noopener noreferrer">Syracuse University</a>, Syracuse, NY</div>
</div>

<div class="cv-entry cv-plain">
  <div class="cv-head"><span class="cv-role">“Flow Patterns Behind Stationary and Moving Bluff Bodies Utilizing the SRT-Lattice Boltzmann Method”</span><span class="cv-date">Nov 2024</span></div>
  <div class="cv-org"><a href="https://mathanddata.wvu.edu/searcde-2024" target="_blank" rel="noopener noreferrer">SEARCDE 2024 Conference</a>, <a href="https://www.wvu.edu/" target="_blank" rel="noopener noreferrer">West Virginia University</a>, Morgantown, WV</div>
</div>

<h2>Graduate Coursework</h2>

<div class="cv-group">Machine Learning and Data Science</div>
<ul class="cv-cols">
  <li>Large-Scale Optimization</li>
  <li>Genomic Data Science</li>
  <li>Statistical Theory for Data Science</li>
  <li>Probability Theory for Data Science</li>
  <li>Machine Learning</li>
  <li>Modern Statistical Methods for Big Data Analytics</li>
</ul>

<div class="cv-group">Numerical Analysis and Computational Modeling</div>
<ul class="cv-cols">
  <li>Scientific Computing in Applied Mathematics</li>
  <li>Advanced Applied Numerical Methods</li>
  <li>Numerical Solution of PDEs</li>
  <li>Numerical Solution of Differential Equations</li>
  <li>Numerical Linear Algebra</li>
  <li>Computational Linear Algebra</li>
  <li>Perturbation Methods</li>
  <li>Viscous Fluid Flow</li>
  <li>Heat Transfer</li>
  <li>Elastodynamics</li>
</ul>

<div class="cv-group">Mathematical Analysis</div>
<ul class="cv-cols">
  <li>Real Analysis</li>
  <li>Complex Analysis</li>
  <li>Measure Theory</li>
  <li>Applied Functional Analysis</li>
  <li>Fixed Point Theory</li>
  <li>Engineering Analysis</li>
</ul>

</div>
