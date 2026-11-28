---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
  .archive > .page__title { display: none; }
  .cv-document { font-family: Georgia, "Times New Roman", serif; font-size: 16px; line-height: 1.45; }
  .cv-document .cv-header { text-align: center; margin-bottom: 1.1em; }
  .cv-document .cv-name { margin: 0 0 .15em; font-size: 1.9em; }
  .cv-document .cv-contact { margin: 0; font-size: .9em; }
  .cv-document h2 { margin: 1em 0 .4em; padding-bottom: .15em; border-bottom: 1px solid currentColor; font-size: 1.1em; font-variant: small-caps; }
  .cv-document p { margin: .25em 0 .5em; }
  .cv-document .cv-entry { margin-bottom: .65em; }
  .cv-document .cv-row { display: flex; align-items: baseline; justify-content: space-between; gap: .8em; }
  .cv-document .cv-row > :first-child { min-width: 0; }
  .cv-document .cv-meta { flex-shrink: 0; text-align: right; }
  .cv-document .cv-detail, .cv-document .cv-note { font-size: .92em; }
  .cv-document .cv-detail { font-style: italic; }
  .cv-document .cv-note { margin-bottom: .65em; font-style: italic; }
  .cv-document ul { margin: .25em 0 .6em; padding-left: 1.3em; }
  .cv-document li { margin-bottom: .15em; }
  .cv-document sup { font-size: .65em; }
  @media (max-width: 640px) {
    .cv-document .cv-row { display: block; }
    .cv-document .cv-meta { display: block; text-align: left; }
  }
</style>

<div class="cv-document">
  <header class="cv-header">
    <h1 class="cv-name">Zhaozi Wang</h1>
    <p class="cv-contact"><a href="mailto:zw4460@nyu.edu">zw4460@nyu.edu</a> · +1 551-371-2906 · New York, NY · <a href="/">ocmykr2.github.io</a></p>
  </header>

  <h2>Research Interests</h2>
  <p>LLM, AI safety, AI for mathematical discovery; online and approximation algorithms; scheduling; distributed algorithms.</p>

  <h2>Education</h2>
  <div class="cv-entry">
    <div class="cv-row"><strong>Courant Institute of Mathematical Sciences, New York University</strong><span class="cv-meta">New York, NY</span></div>
    <div class="cv-row cv-detail"><span>Ph.D. Student in Computer Science; advised by <a href="https://cs.nyu.edu/~anupamg/"><strong>Prof. Anupam Gupta</strong></a></span><span class="cv-meta">Sep. 2024 – Present</span></div>
  </div>
  <div class="cv-entry">
    <div class="cv-row"><strong>ACM Class, Shanghai Jiao Tong University</strong><span class="cv-meta">Shanghai, China</span></div>
    <div class="cv-row cv-detail"><span>B.S. in Computer Science</span><span class="cv-meta">Sep. 2020 – Jun. 2024</span></div>
  </div>

  <h2>Publications and Manuscripts</h2>
  <p class="cv-note">On papers marked TCS (theoretical computer science), authors are listed alphabetically by surname, with no implied ranking of contributions.</p>
  <div class="cv-entry">
    <strong><a href="https://proceedings.mlr.press/v306/mang26a.html">FrontierCS: Evolving Challenges for Evolving Intelligence</a></strong>
    <div class="cv-row cv-detail"><span>with Qiuyang Mang, Wenhao Chai, et al.</span><strong class="cv-meta">ICML 2026</strong></div>
  </div>
  <div class="cv-entry">
    <strong><a href="/publication/flow-time-dual-fitting">An Optimal Online Algorithm for Robust Flow Time Scheduling</a> <sup>TCS</sup></strong>
    <div class="cv-row cv-detail"><span>with Anupam Gupta, Amit Kumar, and Debmalya Panigrahi</span><strong class="cv-meta">SODA 2026</strong></div>
  </div>
  <div class="cv-entry">
    <strong><a href="/publication/long-arm-nashian-allocation">The Long Arm of Nashian Allocation in Online <i>p</i>-Mean Welfare Maximization</a> <sup>TCS</sup></strong>
    <div class="cv-row cv-detail"><span>with Zhiyi Huang, Chui Shan Lee, and Xinkai Shu</span><strong class="cv-meta">ICALP 2025 (Track A)</strong></div>
  </div>
  <div class="cv-entry">
    <strong><a href="/publication/online-makespan-dynamic-locking">Online Makespan Minimization: Beat LPT by Dynamic Locking</a> <sup>TCS</sup></strong>
    <div class="cv-row cv-detail"><span>with Zhiwei Ying and Yuhao Zhang</span><strong class="cv-meta">WINE 2025</strong></div>
  </div>
  <div class="cv-entry">
    <strong><a href="/publication/robust-flow-time-related-machines">Robust Flow Time Scheduling for Related Machines</a> <sup>TCS</sup></strong>
    <div class="cv-row cv-detail"><span>with Anupam Gupta, Amit Kumar, and Debmalya Panigrahi</span><span class="cv-meta">In submission</span></div>
  </div>
  <div class="cv-entry">
    <strong><a href="/publication/distributed-load-balancing-unrelated-machines">Distributed Load Balancing on Unrelated Machines</a> <sup>TCS</sup></strong>
    <div class="cv-row cv-detail"><span>with Aaron Bernstein and Anupam Gupta</span><span class="cv-meta">In submission</span></div>
  </div>

  <h2>Research Projects</h2>
  <div class="cv-entry">
    <strong><a href="https://after42.org/research/can-ai-propose-interesting-research-questions/">After42: Can AI Propose Interesting Research Questions?</a></strong>
    <p>Core team: Fan Nie, Zihao Wang, Kaiyue Wen, Garrett Wen, <strong>Zhaozi Wang</strong>, Hai-Yang Wang, Denny Wu, Theodor Misiakiewicz, Joan Bruna, James Zou, Andrea Montanari, and Percy Liang.</p>
    <p><i>Research post, 2026.</i> <a href="https://after42.org/">Project website</a></p>
    <p>Redesigned parts of the LLM-based research-problem generation pipeline for theoretical computer science, and iteratively refined it based on our assessment of the online-algorithms problems it produced. Designed domain-specific criteria for formulating and evaluating problems.</p>
  </div>

  <h2>AI Safety Training</h2>
  <div class="cv-entry">
    <div class="cv-row"><strong>ARENA Working Group, Collider NYC</strong><i class="cv-meta">Oct. 2026 – Present</i></div>
    <p>Studied and reproduced key works in AI alignment.</p>
  </div>

  <h2>Competitive Programming</h2>
  <div class="cv-row"><strong>Team Captain, Team Willow, Shanghai Jiao Tong University</strong><i class="cv-meta">2020 – 2023</i></div>
  <ul>
    <li><strong>Programming language:</strong> C++.</li>
    <li><strong>Honorable Mention</strong>, 2023 ICPC World Finals, Luxor.</li>
    <li><strong>Champion</strong>, 2022 ICPC Hong Kong Regional Contest.</li>
    <li><strong>4-time Gold Medalist</strong>, ICPC Asia East Continent Final Contest, 2020–2023.</li>
    <li><strong>2-time Gold Medalist</strong>, CCPC Finals, 2022–2023.</li>
    <li><strong>10-time Gold Medalist</strong>, ICPC/CCPC Regional Contests, 2020–2023.</li>
  </ul>

  <h2>Invited Talks</h2>
  <div class="cv-entry">
    <div class="cv-row"><strong><a href="/talks/2026-01-sjtu-robust-flow-time">An Optimal Online Algorithm for Robust Flow Time Scheduling</a></strong><span class="cv-meta">Dec. 2025</span></div>
    <div class="cv-row cv-detail"><span>Shanghai Jiao Tong University (one-hour invited talk)</span><span class="cv-meta">Shanghai, China</span></div>
  </div>

  <h2>Professional Service</h2>
  <p><strong>External Reviewer:</strong> ISAAC 2026, FOCS 2026, ESA 2026, STACS 2026, ICALP 2026, ICALP 2024, and SODA 2024.</p>
</div>
