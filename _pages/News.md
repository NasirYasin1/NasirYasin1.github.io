---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% include base_path %}

<style>
  .news-page {
    --news-accent: #2f7f93;
    --news-muted: #657581;
    --news-rule: #dbe5e9;
    --news-line: #b9d5dc;
    line-height: 1.65;
    max-width: 100%;
  }

  /* Timeline container */
  .news-timeline {
    position: relative;
    list-style: none;
    margin: .4em 0 0 20px;
    padding: 0;
  }

  /* Vertical timeline line */
  .news-timeline::before {
    content: "";
    position: absolute;
    top: .55em;
    bottom: 1.5em;
    left: 7px;
    width: 2px;
    background: var(--news-line);
  }

  /* Individual news entries */
  .news-timeline li {
    position: relative;
    list-style: none;
    margin: 0;
    padding: 0 0 1.0em 2.3em;
  }

  .news-timeline li + li {
    padding-top: 1.4em;
  }

  .news-timeline li:not(:last-child) {
    border-bottom: 1px solid var(--news-rule);
  }

  .news-timeline li:last-child {
    padding-bottom: 0;
  }

  /* Circular timeline markers */
  .news-timeline li::before {
    content: "";
    position: absolute;
    left: 2px;
    top: .4em;
    width: 12px;
    height: 12px;
    box-sizing: border-box;
    background: var(--news-accent);
    border: 2px solid var(--news-accent);
    border-radius: 50%;
    z-index: 1;
  }

  .news-timeline li + li::before {
    top: 1.75em;
  }

  /* News dates */
  .news-date {
    display: block;
    margin-bottom: .3em;
    color: var(--news-accent);
    font-size: .94em;
    font-weight: 700;
    line-height: 1.4;
  }

  /* News descriptions */
  .news-text {
    display: block;
    margin: 0;
    line-height: 1.65;
    overflow-wrap: break-word;
  }

  .news-text strong {
    font-weight: 700;
  }

  /* Hyperlinks */
  .news-text a {
    color: var(--news-accent);
    text-decoration: underline;
    text-decoration-thickness: 1px;
    text-underline-offset: 3px;
  }

  .news-text a:hover,
  .news-text a:focus {
    text-decoration-thickness: 2px;
  }

  /* Dark mode */
  html[data-theme="dark"] .news-page {
    --news-accent: #5cc6df;
    --news-muted: #acb8bf;
    --news-rule: #48555c;
    --news-line: #426773;
  }

  /* Mobile responsiveness */
  @media (max-width: 700px) {
    .news-timeline {
      margin-left: 10px;
    }

    .news-timeline li {
      padding-left: 1.9em;
      padding-bottom: 1.1em;
    }

    .news-timeline li + li {
      padding-top: 1.1em;
    }

    .news-timeline li + li::before {
      top: 1.5em;
    }

    .news-date {
      font-size: .92em;
    }

    .news-text {
      line-height: 1.6;
    }
  }
</style>

<!-- Add new news items at the top. -->

<div class="news-page" markdown="0">

<ul class="news-timeline">

  <li>
    <span class="news-date">Fall 2026</span>
    <span class="news-text">
      Began serving as <strong>Instructor</strong>
      for MATH 103: College Algebra at
      Old Dominion University (ODU), with full
      responsibility for the course.
    </span>
  </li>

  <li>
    <span class="news-date">Fall 2026</span>
    <span class="news-text">
      Began my <strong>Ph.D. research</strong>
      in Applied and Computational Mathematics
      at Old Dominion University.
    </span>
  </li>

  <li>
    <span class="news-date">Aug 2026</span>
    <span class="news-text">
      Passed the <strong>Ph.D. Candidacy Exam</strong>
      in Applied and Computational Mathematics
      at Old Dominion University.
    </span>
  </li>

  <li>
    <span class="news-date">Apr 2026</span>
    <span class="news-text">
      Co-organized the
      <strong>Math Awareness Conference</strong>
      at Old Dominion University for the second
      year as President of the SIAM Student
      Chapter, together with fellow students
      from the SIAM Student Chapter and the
      Math and Statistics Club.
    </span>
  </li>

  <li>
    <span class="news-date">Aug 2025</span>
    <span class="news-text">
      Completed my
      <strong>M.S. in Applied and Computational
      Mathematics</strong> at Old Dominion
      University with the thesis
      <em>Entropy and Gradient Stable Scheme
      for Hyperbolic Burgers’ Equation</em>.
    </span>
  </li>

  <li>
    <span class="news-date">Apr 2025</span>
    <span class="news-text">
      Co-organized the
      <strong>Math Awareness Conference</strong>
      at Old Dominion University as President
      of the SIAM Student Chapter, together
      with fellow students from the SIAM
      Student Chapter and the Math and
      Statistics Club.
    </span>
  </li>

  <li>
    <span class="news-date">Mar 2025</span>
    <span class="news-text">
      Presented “Investigation of Flow Dynamics
      Around Bluff Bodies Using SRT-LBM” at the
      <a href="https://mgo.syr.edu/conferences/past-conferences/2025-conference/"
         target="_blank"
         rel="noopener noreferrer">
        50th Annual New York State Regional
        Graduate Mathematics Conference
      </a>,
      Syracuse University.
    </span>
  </li>

  <li>
    <span class="news-date">Nov 2024</span>
    <span class="news-text">
      Presented “Flow Patterns Behind Stationary
      and Moving Bluff Bodies Utilizing the
      SRT-Lattice Boltzmann Method” at
      <a href="https://mathanddata.wvu.edu/searcde-2024"
         target="_blank"
         rel="noopener noreferrer">
        SEARCDE 2024
      </a>,
      West Virginia University.
    </span>
  </li>

  <li>
    <span class="news-date">Sep 2024</span>
    <span class="news-text">
      Elected <strong>President</strong> of the
      <a href="https://www.odu.edu/math/club"
         target="_blank"
         rel="noopener noreferrer">
        ODU Student Chapter of the Society
        for Industrial and Applied Mathematics
        (SIAM)
      </a>.
    </span>
  </li>

  <li>
    <span class="news-date">Fall 2023</span>
    <span class="news-text">
      Joined Old Dominion University, began
      <strong>graduate research</strong>
      in computational mathematics, and started
      serving as a Supplemental Instruction
      (SI) Leader for undergraduate
      mathematics courses.
    </span>
  </li>

</ul>

</div>
