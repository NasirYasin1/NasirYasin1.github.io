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
  .cv { --cv-accent: #2f7f93; --cv-muted: #657581; --cv-rule: #dbe5e9; line-height: 1.6; }
  .cv h2 {
    margin: 1.8em 0 .75em;
    padding-bottom: .35em;
    border-bottom: 1px solid var(--cv-rule);
    font-size: 1.26em;
    font-weight: 700;
  }
  .cv h2:first-child { margin-top: .45em; }
  .cv h2::before {
    content: "•";
    color: var(--cv-accent);
    font-size: .75em;
    margin-right: .6em;
    vertical-align: middle;
  }
  .cv-entry { margin: 0 0 1.25em; }
  .cv-head { display: flex; align-items: baseline; justify-content: space-between; gap: .3em 1.3em; }
  .cv-role { min-width: 0; font-weight: 700; line-height: 1.4; }
  .cv-date { flex: 0 0 auto; white-space: nowrap; color: var(--cv-muted); font-size: .92em; }
  .cv-concentration { margin-top: .15em; }
  .cv-org { font-style: italic; }
  .cv-org a { color: inherit; text-decoration: none; border-bottom: 1px solid #b9cbd1; }
  .cv-org a:hover, .cv-org a:focus { color: var(--cv-accent); border-bottom-color: currentColor; }
  .cv-entry ul { margin: .3em 0 0 1.3em; padding: 0; }
  .cv-entry li { margin-bottom: .2em; }
  .cv-award a { color: var(--cv-accent); text-decoration: none; border-bottom: 1px solid #b9cbd1; }
  .cv-award a:hover, .cv-award a:focus { border-bottom-color: currentColor; }
  .cv-award-desc { margin-top: .15em; color: var(--cv-muted); }
  .cv-group { margin: 1.2em 0 .5em; color: var(--cv-accent); font-weight: 700; }
  .cv-cols {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    column-gap: 2.2em;
    row-gap: .25em;
    padding-left: 1.25em;
    margin: 0 0 1.1em;
  }
  .cv-cols li { min-width: 0; overflow-wrap: break-word; }
  html[data-theme="dark"] .cv { --cv-accent: #5cc6df; --cv-muted: #acb8bf; --cv-rule: #48555c; }
  @media (max-width: 700px) {
    .cv-head { flex-direction: column; align-items: flex-start; gap: .1em; }
    .cv-date { white-space: normal; }
    .cv-cols { grid-template-columns: minmax(0, 1fr); }
  }
</style>

<div class="cv" markdown="0">

<h2>Education</h2>

<div class="cv-entry">
  <div class="cv-head">
    <span class="cv-role">Ph.D., Applied and Computational Mathematics</span>
    <span class="cv-date">Expected 2028</span>
  </div>
  <div class="cv-concentration"><strong>Concentration:</strong> Mathematics of Data Science</div>
  <div class="cv-org"><a href="https://www.odu.edu/" target="_blank" rel="noopener noreferrer">Old Dominion University</a>, Norfolk, VA, USA</div>
</div>

<div class="cv-entry">
  <div class="cv-head">
    <span class="cv-role">M.S., Applied and Computational Mathematics</span>
    <span class="cv-date">2023 – 2025</span>
  </div>
  <div class="cv-org"><a href="https://www.odu.edu/" target="_blank" rel="noopener noreferrer">Old Dominion University</a>, Norfolk, VA, USA</div>
  <ul><li>Thesis: <em>Entropy and Gradient Stable Scheme for Hyperbolic Burgers’ Equation</em></li></ul>
</div>

<div class="cv-entry">
  <div class="cv-head">
    <span class="cv-role">M.S., Mathematics</span>
    <span class="cv-date">2019 – 2021</span>
  </div>
  <div class="cv-org"><a href="https://www.comsats.edu.pk/" target="_blank" rel="noopener noreferrer">COMSATS University Islamabad</a>, Islamabad, Pakistan</div>
  <ul><li>Research: Flow features and force statistics for flow past multiple bluff bodies</li></ul>
</div>

<div class="cv-entry">
  <div class="cv-head">
    <span class="cv-role">B.S., Mathematics</span>
    <span class="cv-date">2014 – 2018</span>
  </div>
  <div class="cv-org"><a href="https://www.iiu.edu.pk/" target="_blank" rel="noopener noreferrer">International Islamic University Islamabad</a>, Islamabad, Pakistan</div>
</div>

<h2>Honors &amp; Awards</h2>

<div class="cv-entry cv-award">
  <a href="https://www.hec.gov.pk/english/services/students/pmnls/Pages/default.aspx" target="_blank" rel="noopener noreferrer">Prime Minister's Laptop Scheme</a>
  <div class="cv-award-desc">Awarded in recognition of academic performance, Pakistan.</div>
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
