---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

{% include base_path %}

<style>
  .research-page {
    --research-accent: #2f7f93;
    --research-muted: #657581;
    --research-rule: #dbe5e9;
    line-height: 1.65;
    max-width: 100%;
  }

  /* Main section headings */
  .research-page h2 {
    margin: 2em 0 .8em;
    padding-bottom: .42em;
    border-bottom: 1px solid var(--research-rule);
    font-size: 1.32em;
    font-weight: 700;
  }

  .research-page h2:first-child {
    margin-top: .4em;
  }

  /* Indent content below section headings */
  .research-page > .research-entry,
  .research-page > .research-interest,
  .research-page > .research-project,
  .research-page > ul,
  .research-page > p {
    margin-left: 20px;
  }

  /* Research entries */
  .research-page .research-entry {
    margin-bottom: 1.55em;
  }

  .research-page .research-head {
    display: flex;
    align-items: baseline;
    justify-content: space-between;
    gap: .4em 1.3em;
  }

  .research-page .research-title {
    min-width: 0;
    font-weight: 700;
    line-height: 1.45;
  }

  .research-page .research-date {
    flex: 0 0 auto;
    white-space: nowrap;
    color: var(--research-muted);
    font-size: .91em;
  }

  /* Research institutions */
  .research-page .research-org {
    margin-top: .18em;
    font-style: italic;
    color: var(--research-muted);
  }

  .research-page .research-org a {
    color: inherit;
    text-decoration: none;
    border-bottom: 1px solid #b9cbd1;
  }

  .research-page .research-org a:hover {
    color: var(--research-accent);
    border-bottom-color: var(--research-accent);
  }

  /* Research supervisors */
  .research-page .research-supervisor {
    margin-top: .18em;
    font-size: .95em;
  }

  .research-page .research-supervisor a {
    color: var(--research-accent);
    text-decoration: none;
  }

  .research-page .research-supervisor a:hover {
    text-decoration: underline;
  }

  /* Research lists */
  .research-page ul {
    margin-top: .45em;
    margin-bottom: 0;
    padding: 0;
  }

  .research-page .research-entry ul {
    margin-left: 1.3em;
  }

  .research-page li {
    margin-bottom: .32em;
  }

  /* Research projects */
  .research-page .research-project .research-title {
    font-weight: 400;
  }

  /* Research interests */
  .research-page .research-interest {
    margin-top: 0;
    margin-bottom: .75em;
  }

  /* Dark mode */
  html[data-theme="dark"] .research-page {
    --research-accent: #5cc6df;
    --research-muted: #acb8bf;
    --research-rule: #48555c;
  }

  html[data-theme="dark"] .research-page .research-supervisor a {
    color: #5cc6df;
  }

  /* Mobile responsiveness */
  @media (max-width: 700px) {
    .research-page .research-head {
      flex-direction: column;
      align-items: flex-start;
      gap: .1em;
    }

    .research-page .research-date {
      white-space: normal;
    }
  }
</style>

<div class="research-page" markdown="0">

  
<h2>Research Experience</h2>
<div class="research-entry">
  <div class="research-head"><span class="research-title">Research Assistant, Applied Fluid Laboratory</span><span class="research-date">Apr 2022 – Aug 2023</span></div>
  <div class="research-org"><a href="https://en.knu.ac.kr/main/main.htm" target="_blank" rel="noopener noreferrer">Kyungpook National University</a>, Daegu, South Korea</div>
  <div class="research-supervisor">Supervisor: <a href="https://scholar.google.com/citations?user=nBR6rDUAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Prof. Chang Hyun Sohn</a> · <a href="mailto:chsohn@knu.ac.kr">chsohn@knu.ac.kr</a></div>
  <ul>
    <li>Worked on <em>Improved Energy Recovery Performance of Oscillating Wings Using Articulated and Flexible Bodies</em>, funded by the National Research Foundation of Korea (NRF).</li>
    <li>Performed high-Reynolds-number flow simulations using the Lattice Boltzmann Method (LBM).</li>
    <li>Developed GPU-accelerated C++ solvers for oscillating-wing energy-recovery applications.</li>
  </ul>
</div>

<div class="research-entry">
  <div class="research-head"><span class="research-title">Research Assistant</span><span class="research-date">Jan 2020 – Apr 2022</span></div>
  <div class="research-org"><a href="https://www.comsats.edu.pk/" target="_blank" rel="noopener noreferrer">COMSATS University Islamabad</a>, Islamabad, Pakistan</div>
  <div class="research-supervisor">Supervisor: <a href="https://scholar.google.com/citations?hl=en&amp;user=OAp3xVAAAAAJ&amp;view_op=list_works&amp;sortby=pubdate" target="_blank" rel="noopener noreferrer">Prof. Shams ul Islam</a> · <a href="mailto:islam_shams@comsats.edu.pk">islam_shams@comsats.edu.pk</a></div>
  <ul>
    <li>Worked on <em>Numerical Study of Wake and Thrust Around Multiple Cylinders at Moderate Reynolds Numbers for Various Configurations</em>, funded by the Higher Education Commission (HEC) of Pakistan.</li>
    <li>Developed single-relaxation-time Lattice Boltzmann (SRT-LBM) simulations in Fortran.</li>
    <li>Post-processed and visualized simulation results in MATLAB and Tecplot.</li>
  </ul>
</div>

<h2>Graduate Course Projects</h2>

<div class="research-entry research-project">
  <div class="research-head"><span class="research-title">Convergence and Performance Comparison of Numerical Solvers for Sparse Resistor-Network Linear Systems</span><span class="research-date">Dec 2023</span></div>
  <div class="research-org">Graduate Course Project, <a href="https://www.odu.edu/" target="_blank" rel="noopener noreferrer">Old Dominion University</a></div>
</div>

<div class="research-entry research-project">
  <div class="research-head"><span class="research-title">Image Processing and Compression Using Multiple Algorithms</span><span class="research-date">Dec 2023</span></div>
  <div class="research-org">Graduate Course Project, <a href="https://www.odu.edu/" target="_blank" rel="noopener noreferrer">Old Dominion University</a></div>
</div>

</div>
