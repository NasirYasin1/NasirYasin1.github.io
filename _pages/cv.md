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
  .cv { --cv-accent: #2f7f93; --cv-muted: #657581; --cv-rule: #dbe5e9; line-height: 1.65; max-width: 100%; }
  .cv h2 { margin: 2.1em 0 .85em; padding: 0 0 .42em; border-bottom: 1px solid var(--cv-rule); font-size: 1.32em; font-weight: 700; letter-spacing: -.015em; }
  .cv h2:first-child { margin-top: .45em; }
  .cv-entry { margin: 0 0 1.35em; }
  .cv-head { display: flex; align-items: baseline; justify-content: space-between; gap: .35em 1.3em; }
  .cv-role { min-width: 0; font-weight: 700; line-height: 1.45; }
  .cv-date { flex: 0 0 auto; white-space: nowrap; color: var(--cv-muted); font-size: .91em; font-variant-numeric: tabular-nums; }
  .cv-org { margin-top: .14em; font-style: italic; color: var(--cv-muted); }
  .cv-entry ul { margin: .45em 0 0 1.3em; padding: 0; }
  .cv-entry li, .cv-cols li { margin-bottom: .34em; padding-left: .1em; }
  .cv-group { font-weight: 700; color: var(--cv-accent); margin: 1.25em 0 .55em; }
  .cv-cols { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); column-gap: 2.1em; row-gap: .12em; margin: 0 0 1.3em; padding-left: 1.35em; }
  .cv-cols li { min-width: 0; overflow-wrap: anywhere; }
  .cv-skills { margin: 0; }
  .cv-skills dt { font-weight: 700; margin-top: .75em; }
  .cv-skills dd { margin: .12em 0 0 1.2em; }
  @media (max-width: 700px) {
    .cv-head { flex-direction: column; align-items: flex-start; gap: .1em; }
    .cv-date { white-space: normal; }
    .cv-cols { grid-template-columns: minmax(0, 1fr); }
    .cv h2 { margin-top: 1.7em; }
  }
</style>

<div class="cv" markdown="0">

<h2>Education</h2>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">Ph.D., Applied and Computational Mathematics</span><span class="cv-date">Expected 2028</span></div>
  <div class="cv-org">Old Dominion University, Norfolk, VA, USA</div>
</div>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">M.S., Applied and Computational Mathematics</span><span class="cv-date">2023 – 2025</span></div>
  <div class="cv-org">Old Dominion University, Norfolk, VA, USA</div>
  <ul><li>Thesis: <em>Entropy and Gradient Stable Scheme for Hyperbolic Burgers’ Equation</em></li></ul>
</div>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">M.S., Mathematics</span><span class="cv-date">2019 – 2021</span></div>
  <div class="cv-org">COMSATS University Islamabad, Islamabad, Pakistan</div>
  <ul><li>Research: Flow features and force statistics for flow past multiple bluff bodies</li></ul>
</div>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">B.S., Mathematics</span><span class="cv-date">2014 – 2018</span></div>
  <div class="cv-org">International Islamic University Islamabad, Islamabad, Pakistan</div>
</div>

<h2>Research Experience</h2>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">Research Assistant, Applied Fluid Laboratory</span><span class="cv-date">Apr 2022 – Aug 2023</span></div>
  <div class="cv-org">Kyungpook National University, Daegu, South Korea</div>
  <ul>
    <li>Contributed to a National Research Foundation of Korea (NRF)-funded project on energy recovery from oscillating wings.</li>
    <li>Ran high-Reynolds-number flow simulations with the Lattice Boltzmann Method (LBM).</li>
    <li>Developed GPU-accelerated C++ solvers for oscillating-wing energy-recovery applications.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">Research Assistant</span><span class="cv-date">Jan 2020 – Apr 2022</span></div>
  <div class="cv-org">COMSATS University Islamabad, Islamabad, Pakistan</div>
  <ul>
    <li>Contributed to a Higher Education Commission (HEC)-funded project on flow around multiple bluff bodies.</li>
    <li>Developed single-relaxation-time LBM (SRT-LBM) simulations in Fortran.</li>
    <li>Post-processed and visualized results in MATLAB and Tecplot.</li>
  </ul>
</div>

<h2>Teaching Experience</h2>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">Graduate Teaching Assistant, Supplemental Instruction (SI) Leader</span><span class="cv-date">Fall 2023 – Present</span></div>
  <div class="cv-org">Department of Mathematics and Statistics, Old Dominion University, Norfolk, VA, USA</div>
  <ul>
    <li>Lead structured problem-solving sessions for undergraduate mathematics courses.</li>
    <li>Support students in the Applied Calculus Lab and the SMART Room, and provide online tutoring.</li>
    <li>Courses: MATH 212 Calculus; MATH 205 Calculus for Life Sciences; MATH 200 Calculus for Business and Economics; MATH 162 Precalculus; MATH 103 College Algebra; MATH 100 Introduction to Mathematics for Critical Thinking.</li>
  </ul>
</div>

<h2>Research Projects</h2>

<div class="cv-entry"><div class="cv-head"><span class="cv-role">Stable Scheme for the Hyperbolic Burgers’ Equation</span><span class="cv-date">Jan 2024 – Present</span></div></div>
<div class="cv-entry"><div class="cv-head"><span class="cv-role">Convergence and Performance Comparison of Numerical Solvers for Sparse Resistor-Network Linear Systems</span><span class="cv-date">Dec 2023</span></div></div>
<div class="cv-entry"><div class="cv-head"><span class="cv-role">Image Processing and Compression Using Multiple Algorithms</span><span class="cv-date">Dec 2023</span></div></div>
<div class="cv-entry"><div class="cv-head"><span class="cv-role">Improved Energy Recovery Performance of Oscillating Wings Using Articulated and Flexible Bodies</span><span class="cv-date">Apr 2022 – Aug 2023</span></div></div>
<div class="cv-entry"><div class="cv-head"><span class="cv-role">Numerical Study of Wake and Thrust Around Multiple Cylinders at Moderate Reynolds Numbers for Various Configurations</span><span class="cv-date">Jan 2020 – Apr 2022</span></div></div>

<h2>Talks and Presentations</h2>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">Investigation of Flow Dynamics Around Bluff Bodies Using SRT-LBM</span><span class="cv-date">Mar 2025</span></div>
  <div class="cv-org">50th Annual New York State Regional Graduate Mathematics Conference, Syracuse University, Syracuse, NY</div>
</div>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">Flow Patterns Behind Stationary and Moving Bluff Bodies Utilizing the SRT-Lattice Boltzmann Method</span><span class="cv-date">Nov 2024</span></div>
  <div class="cv-org">SEARCDE 2024 Conference, West Virginia University, Morgantown, WV</div>
</div>

<h2>Technical Skills</h2>

<dl class="cv-skills">
  <dt>Programming</dt><dd>Python, MATLAB, R, C++, Fortran</dd>
  <dt>High-Performance Computing</dt><dd>CUDA, GPU-accelerated solvers, Linux-based scientific computing</dd>
  <dt>Numerical Methods</dt><dd>Lattice Boltzmann Method (SRT-LBM), numerical methods for PDEs, stable schemes for hyperbolic equations</dd>
  <dt>Visualization</dt><dd>Tecplot, MATLAB</dd>
</dl>

<h2>Graduate Coursework</h2>

<div class="cv-group">Machine Learning and Data Science</div>
<ul class="cv-cols">
  <li>Machine Learning</li>
  <li>Genomic Data Science</li>
  <li>Probability Theory for Data Science</li>
  <li>Statistical Theory for Data Science</li>
  <li>Modern Statistical Methods for Big Data Analytics</li>
  <li>Large-Scale Optimization</li>
</ul>

<div class="cv-group">Numerical Analysis and Computational Modeling</div>
<ul class="cv-cols">
  <li>Scientific Computing in Applied Mathematics</li>
  <li>Numerical Solution of PDEs</li>
  <li>Numerical Solution of Differential Equations</li>
  <li>Advanced Applied Numerical Methods</li>
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
