---
layout: page
# title: Seongcheol Baek
title: Project
---

<style>
.page h3 {
  font-style: italic;
}

/* Keep marker width but hide dot when list item starts with a checkbox. */
.page li:has(> input[type="checkbox"]),
.page li:has(> p > input[type="checkbox"]) {
  list-style: inherit;
}

.page li:has(> input[type="checkbox"])::marker,
.page li:has(> p > input[type="checkbox"])::marker {
  color: transparent;
}

/* Normalize task-list wrappers from different markdown renderers. */
.page li.task-list-item {
  margin-left: 0;
}

.page ul.task-list {
  padding-left: 0.35rem;
  margin: 0.2rem 0;
}

/* Make nested checklist levels visibly deeper than parent level. */
.page li > ul.task-list,
.page li > ul {
  padding-left: 1.1rem;
}

/* Align checkbox position and text spacing with regular bullet indentation. */
.page li > input[type="checkbox"],
.page li > p > input[type="checkbox"] {
  margin-left: -1.8em;
  margin-right: 0.35rem;
}

/* Apply compact spacing for all nested bullet/numbered lists in this page. */
.page li > ul,
.page li > ol {
  margin-top: 0.1rem;
  margin-bottom: 0.1rem;
}
</style>


### DEVELOPMENTS
2026.03.20 - Under Dev.
: **Planning a Platform Business**
> Requirements:
1. People
  - [ ] Advisors
  - [ ] Reviewers
2. Resources
  - [x] IP (Domain)
  - [ ] Identity (Service Name)
  - [ ] Foundation of something official
  - [ ] Place (for a business address)
3. Document works...
  - [ ] Overall process
  - [ ] Tax problems
  - [ ] Inquiry via the company HR team
4. Definition of Development Roles
  - [x] Objective is to establish workflow transparency
  - [ ] Designer
  - [ ] Coder
  - [ ] Reviewer
5. Workflow
  - [ ] Workflow structure
  - [ ] Design
    - [ ] ???
    - [ ] ???
  - [ ] Project Management (WBS, Gantt Chart)
  - [ ] Daily and monthly work cycles
  - [ ] Channel device for direct reviews (not a phone)


2026.03.08 - Under Dev.
: **AI Asistance** / Solo Development
> Under preparation of the followings:
1. Machine for AI (Macbook Pro 2016)
  - MacOS Update via OpenCore Legacy Patcher:
    [<a href="https://newmkka.tistory.com/entry/%EA%B5%AC%ED%98%95-Mac%EC%97%90-%EC%B5%9C%EC%8B%A0-macOS-Sequoia-%EC%84%A4%EC%B9%98%ED%95%98%EA%B8%B0-OpenCore-Legacy-Patcher-%EA%B0%80%EC%9D%B4%EB%93%9C" target="_blank">Link 1</a>]
    [<a href="https://smilewolf.tistory.com/915" target="_blank">Link 2</a>]
  - Why?: OpenClaw requires macOS 15+
    <img src="{{ site.baseurl }}{{ site.figs.project_prgm_dev_openclaw_1 }}" />
  - Version Updated: 15.4.1 Sequoia
1. AI Agent (OpenClaw)
  - Installation: 
    [<a href="https://openclaw.ai/" target="_blank">Link</a>]
    <img src="{{ site.baseurl }}{{ site.figs.project_prgm_dev_openclaw_2 }}" />
  - Configureations: Gateway Auth, Permissions (700), Session Store, Plugins, Memory Search, Channel
1. To allow OpenClaw to use GitHub Copilot CLI:
  - Activate GitHub Copilot subscription
  - Install GitHub CLI [<a href="https://cli.github.com/" target="_blank">Link</a>]
  - Install OpenClaw
  - Configure OpenClaw Provider: In OpenClaw's configuration, select the built-in github-copilot provider
  - Authenticate via GitHub CLI: The integration relies on authenticating your GitHub account through the standard GitHub CLI process.
  - How to add an agent: [<a href="https://wikidocs.net/blog/@peterai/7150/" target="_blank">Link</a>]
1. CLI Applications (Lists)
  - Google Cloud CLI: [<a href="https://docs.cloud.google.com/sdk/docs/install-sdk?hl=ko" target="_blank">Link</a>] 
1. Channel 
  - iMessage
  - Discord
1. Notes
  - Blog 1 [<a href="https://codingapple.com/blog/openclaw-install/" target="_blank">Link</a>] 
1. Making a Workflow


2025.12.27 - 2026.01.02
: **Autotrading Program** / Solo Development
> <img src="{{ site.baseurl }}{{ site.figs.project_prgm_dev_concept }}" />
The concept of program development.

2021.06.28
: **Web Application** / Solo Development
> Built a personal GitHub profile page.

2020.06.16
: **Computer Vision Algorithm** / Solo Development / Rutilea
> <img src="{{ site.baseurl }}{{ site.figs.project_alg_planar_matching }}" />
Built a <a href="https://github.com/arcwolf/planar_matching_w_homography" target="_blank">planar matching demo</a>, which is driven with key-point matching (ORB or BRISK method) and homography method.

2019.12.27 - 2020.02.10
: **Web Application** / Solo Development
> <img src="{{ site.baseurl }}{{ site.figs.project_web_dev_frontpage }}" />
Built a <a href="https://kyotoksa.com/" target="_blank">student community site</a> for Kyoto University Korean Student Association.
The project was built with WordPress (Framework), AVADA (Front Theme), and Hostinger (DB, Host Server).
<br><br>
<img src="{{ site.baseurl }}{{ site.figs.project_web_dev_wbs }}" />
The development concept idea at the initial stage of the project.

2018.11.10 - 2018.12.13
: **Parallel Computation** / Solo Development / Kyoto Innovation
> <img src="{{ site.baseurl }}{{ site.figs.project_prgm_dev_distcomp_idea }}" />
The introduction of the parallel computation solution for the part of web application.



### EXPLORATIONS
<!-- 2026.04.17
: **Coding Test** / LG SWPCT (Software Programming Competency Test)
> Evaluated software development skills through online coding test. -->

2025.06.11
: **Presentation** / Review of WBG (Wide Band Gap) Semiconductor
> <img src="{{ site.baseurl }}{{ site.figs.project_exp_wbg_research }}" />
Presented reviews on recent power conversion technology based wide band gap semiconductor solutions. The talks cover the principles and potential risks to be considered in terms of development. <br><br>
Details are classified out of the company policy.

2020.03.27
: **Presentation** / Recent Technical Reviews
> <img src="{{ site.baseurl }}{{ site.figs.project_exp_presentation_back_projection_problem_0 }}" />
<img src="{{ site.baseurl }}{{ site.figs.project_exp_presentation_back_projection_problem_1 }}" />
<img src="{{ site.baseurl }}{{ site.figs.project_exp_presentation_back_projection_problem_2 }}" />
<img src="{{ site.baseurl }}{{ site.figs.project_exp_presentation_back_projection_problem_3 }}" />
Presented "Theories and Engineering Techniques of 2D-to-3D Back-Projection Problem".

2019.07.19
: **Presentation** / Recent Technical Reviews
> <img src="{{ site.baseurl }}{{ site.figs.project_exp_presentation_gan_0 }}" />
<img src="{{ site.baseurl }}{{ site.figs.project_exp_presentation_gan_1 }}" />
<img src="{{ site.baseurl }}{{ site.figs.project_exp_presentation_gan_2 }}" />
Presented "Introduction of DiscoGAN" along with the study on theoretical background of GAN algorithm.
