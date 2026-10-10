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
  .cv-entry ul { margin: .3em 0 0 1.2em; }
  .cv-entry li { margin-bottom: .2em; }
  .cv-skill { margin: 0 0 .4em; }
  .cv-group { font-weight: 700; margin: .9em 0 .2em; }
  .cv-cols { columns: 2 16em; column-gap: 2em; margin: 0 0 0 1.2em; }
  .cv-cols li { break-inside: avoid; }
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
    <li>Project: <em>Improved Energy Recovery Performance of Oscillating Wings Using Articulated and Flexible Bodies</em>, funded by the National Research Foundation of Korea (NRF).</li>
    <li>Performed high-Reynolds-number flow simulations using the Lattice Boltzmann Method (LBM).</li>
    <li>Developed GPU-accelerated C++ solvers for oscillating-wing energy-recovery applications.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-head"><span class="cv-role">Research Assistant</span><span class="cv-date">Jan 2020 – Apr 2022</span></div>
  <div class="cv-org">COMSATS University Islamabad, Islamabad, Pakistan</div>
  <ul>
    <li>Project: <em>Numerical Study of Wake and Thrust Around Multiple Cylinders at Moderate Reynolds Numbers for Various Configurations</em>, funded by the Higher Education Commission (HEC) of Pakistan.</li>
    <li>Developed single-relaxation-time Lattice Boltzmann (SRT-LBM) simulations in Fortran.</li>
    <li>Post-processed and visualized simulation results in MATLAB and Tecplot.</li>
  </ul>
</div>

<h2>Research Projects</h2>

<div class="cv-entry cv-plain">
  <div class="cv-head"><span class="cv-role">Stable Scheme for the Hyperbolic Burgers’ Equation</span><span class="cv-date">Jan 2024 – Present</span></div>
  <div class="cv-org">M.S. Thesis, Old Dominion University</div>
</div>

<div class="cv-entry cv-plain">
  <div class="cv-head"><span class="cv-role">Convergence and Performance Comparison of Numerical Solvers for Sparse Resistor-Network Linear Systems</span><span class="cv-date">Dec 2023</span></div>
  <div class="cv-org">Old Dominion University</div>
</div>

<div class="cv-entry cv-plain">
  <div class="cv-head"><span class="cv-role">Image Processing and Compression Using Multiple Algorithms</span><span class="cv-date">Dec 2023</span></div>
  <div class="cv-org">Old Dominion University</div>
</div>

<h2>Talks and Presentations</h2>

<div class="cv-entry cv-plain">
  <div class="cv-head"><span class="cv-role">“Investigation of Flow Dynamics Around Bluff Bodies Using SRT-LBM”</span><span class="cv-date">Mar 2025</span></div>
  <div class="cv-org">50th Annual New York State Regional Graduate Mathematics Conference, Syracuse University, Syracuse, NY</div>
</div>

<div class="cv-entry cv-plain">
  <div class="cv-head"><span class="cv-role">“Flow Patterns Behind Stationary and Moving Bluff Bodies Utilizing the SRT-Lattice Boltzmann Method”</span><span class="cv-date">Nov 2024</span></div>
  <div class="cv-org">SEARCDE 2024 Conference, West Virginia University, Morgantown, WV</div>
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

<h2>Technical Skills</h2>

<div class="cv-entry">
  <p class="cv-skill"><strong>Programming Languages:</strong> Python, MATLAB, R, C++, Fortran</p>
  <p class="cv-skill"><strong>High-Performance Computing:</strong> CUDA, GPU-Accelerated Computing, Linux</p>
  <p class="cv-skill"><strong>Numerical Methods:</strong> Lattice Boltzmann Method, Numerical Methods for Partial Differential Equations</p>
  <p class="cv-skill"><strong>Scientific Visualization:</strong> Tecplot, MATLAB</p>
</div>

<h2>Graduate Coursework</h2>

<div class="cv-group">Machine Learning and Data Science</div>
<ul class="cv-cols">
  <li>Machine Learning</li>
  <li>Probability Theory for Data Science</li>
  <li>Statistical Theory for Data Science</li>
  <li>Modern Statistical Methods for Big Data Analytics</li>
  <li>Large-Scale Optimization</li>
</ul>

<div class="cv-group">Numerical Analysis and Computational Modeling</div>
<ul class="cv-cols">
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
