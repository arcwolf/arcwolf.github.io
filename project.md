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


### PROJECT COMMIT ACTIVITY

<div id="gh-heatmap-wrap" style="margin-bottom:2rem;">
<style>
#gh-heatmap-wrap .gh-row { display:flex; align-items:center; margin-bottom:4px; }
#gh-heatmap-wrap .gh-label { width:200px; font-size:11px; color:#7d8590; text-align:right; padding-right:10px; white-space:nowrap; overflow:hidden; text-overflow:ellipsis; }
#gh-heatmap-wrap .gh-label a { color:#58a6ff; text-decoration:none; }
#gh-heatmap-wrap .gh-cells { display:flex; gap:2px; flex:1; }
#gh-heatmap-wrap .gh-cell { flex:1; height:14px; border-radius:2px; min-width:8px; cursor:default; }
#gh-heatmap-wrap .gh-cell[data-level="0"] { background:#ebedf0; }
#gh-heatmap-wrap .gh-cell[data-level="1"] { background:#9be9a8; }
#gh-heatmap-wrap .gh-cell[data-level="2"] { background:#40c463; }
#gh-heatmap-wrap .gh-cell[data-level="3"] { background:#30a14e; }
#gh-heatmap-wrap .gh-cell[data-level="4"] { background:#216e39; }
#gh-heatmap-wrap .gh-header { display:flex; margin-bottom:6px; }
#gh-heatmap-wrap .gh-header-label { width:200px; }
#gh-heatmap-wrap .gh-header-dates { display:flex; flex:1; }
#gh-heatmap-wrap .gh-date-lbl { flex:1; font-size:9px; color:#7d8590; text-align:center; }
#gh-heatmap-wrap .gh-legend { display:flex; align-items:center; gap:4px; font-size:11px; color:#7d8590; margin-top:8px; }
#gh-heatmap-wrap .gh-legend-cell { width:12px; height:12px; border-radius:2px; }
#gh-heatmap-wrap .gh-total-row { margin-top:10px; border-top:1px solid #d0d7de; padding-top:8px; }
</style>
<div id="gh-heatmap"></div>
<div class="gh-legend">
  Less
  <div class="gh-legend-cell" style="background:#ebedf0"></div>
  <div class="gh-legend-cell" style="background:#9be9a8"></div>
  <div class="gh-legend-cell" style="background:#40c463"></div>
  <div class="gh-legend-cell" style="background:#30a14e"></div>
  <div class="gh-legend-cell" style="background:#216e39"></div>
  More &nbsp;·&nbsp; <span id="gh-range-label" style="color:#7d8590"></span>
</div>
</div>
<script>
(function(){
var DATA=[{"name":"fin-kamikaze","url":"https://github.com/arcwolf/fin-kamikaze","dates":["2026-06-29","2026-06-29","2026-06-29","2026-06-29","2026-06-30","2026-06-30","2026-06-30","2026-06-30","2026-06-30","2026-06-30","2026-06-30","2026-06-30","2026-06-30","2026-07-01","2026-07-01","2026-07-01","2026-07-01","2026-07-01","2026-07-01","2026-07-01","2026-07-01","2026-07-02","2026-07-02","2026-07-02","2026-07-03","2026-07-03","2026-07-03","2026-07-03","2026-07-03","2026-07-04","2026-07-04","2026-07-04","2026-07-04","2026-07-04","2026-07-04","2026-07-04","2026-07-04","2026-07-04","2026-07-05","2026-07-05","2026-07-05","2026-07-05","2026-07-05","2026-07-05","2026-07-06","2026-07-06","2026-07-06","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-08","2026-07-08","2026-07-08","2026-07-08","2026-07-09","2026-07-09","2026-07-09","2026-07-09","2026-07-10","2026-07-10","2026-07-10","2026-07-11","2026-07-11","2026-07-11","2026-07-11","2026-07-12","2026-07-12","2026-07-12","2026-07-12","2026-07-13","2026-07-13","2026-07-13","2026-07-13","2026-07-13","2026-07-13","2026-07-13","2026-07-13","2026-07-14","2026-07-14","2026-07-14","2026-07-15","2026-07-15","2026-07-15","2026-07-16","2026-07-16","2026-07-16","2026-07-17","2026-07-17","2026-07-17","2026-07-18","2026-07-18","2026-07-18","2026-07-19","2026-07-19","2026-07-19","2026-07-20","2026-07-20","2026-07-20"]},{"name":"fin-autotrade-f1","url":"https://github.com/arcwolf/fin-autotrade-f1","dates":["2026-07-06","2026-07-06","2026-07-06","2026-07-06","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-08","2026-07-08","2026-07-08","2026-07-08","2026-07-08","2026-07-08","2026-07-08","2026-07-09","2026-07-09","2026-07-09","2026-07-09","2026-07-09","2026-07-09","2026-07-09","2026-07-10","2026-07-10","2026-07-10","2026-07-10","2026-07-10","2026-07-10","2026-07-10","2026-07-11","2026-07-11","2026-07-11","2026-07-11","2026-07-11","2026-07-11","2026-07-11","2026-07-12","2026-07-12","2026-07-12","2026-07-12","2026-07-12","2026-07-12","2026-07-12","2026-07-13","2026-07-13","2026-07-13","2026-07-13","2026-07-13","2026-07-13","2026-07-13","2026-07-14","2026-07-14","2026-07-14","2026-07-14","2026-07-14","2026-07-14","2026-07-14","2026-07-15","2026-07-15","2026-07-15","2026-07-15","2026-07-15","2026-07-15","2026-07-15","2026-07-16","2026-07-16","2026-07-16","2026-07-16","2026-07-16","2026-07-16","2026-07-17","2026-07-17","2026-07-17","2026-07-17","2026-07-17","2026-07-17","2026-07-18","2026-07-18","2026-07-18","2026-07-18","2026-07-18","2026-07-18","2026-07-18","2026-07-19","2026-07-19","2026-07-19","2026-07-19","2026-07-19","2026-07-19","2026-07-20","2026-07-20","2026-07-20","2026-07-20","2026-07-20","2026-07-20","2026-07-20"]},{"name":"paper-insight-builder","url":"https://github.com/arcwolf/paper-insight-builder","dates":["2026-06-21","2026-06-21","2026-06-22","2026-06-22","2026-06-22","2026-06-22","2026-06-22","2026-06-22","2026-06-22","2026-06-22","2026-06-22","2026-06-22","2026-06-22","2026-06-22","2026-06-22","2026-06-22","2026-06-22","2026-06-29","2026-06-29","2026-06-29","2026-07-02","2026-07-06","2026-07-06","2026-07-06","2026-07-06","2026-07-06","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-07","2026-07-08","2026-07-08","2026-07-08","2026-07-08","2026-07-09","2026-07-09","2026-07-10","2026-07-10","2026-07-10","2026-07-15","2026-07-16","2026-07-16","2026-07-16","2026-07-16","2026-07-16","2026-07-16","2026-07-16","2026-07-19","2026-07-19","2026-07-19","2026-07-19","2026-07-20","2026-07-20","2026-07-20","2026-07-20"]},{"name":"coding-test","url":"https://github.com/arcwolf/coding-test","dates":["2026-06-20","2026-06-21","2026-06-22","2026-06-22","2026-06-23","2026-06-23","2026-06-23","2026-06-23","2026-06-23","2026-06-24","2026-06-25","2026-06-25","2026-06-26","2026-06-26","2026-06-27","2026-06-28","2026-06-29","2026-06-30","2026-07-01","2026-07-02","2026-07-03","2026-07-04","2026-07-05","2026-07-06","2026-07-07","2026-07-08","2026-07-09","2026-07-10","2026-07-11","2026-07-12","2026-07-13","2026-07-14","2026-07-15","2026-07-16","2026-07-17","2026-07-18","2026-07-19","2026-07-20","2026-07-21"]},{"name":"arcwolf.github.io","url":"https://github.com/arcwolf/arcwolf.github.io","dates":["2026-06-20","2026-06-21","2026-06-22","2026-06-23","2026-06-24","2026-06-25","2026-06-26","2026-06-27","2026-06-27","2026-06-27","2026-06-27","2026-06-27","2026-06-27","2026-06-28","2026-06-29","2026-06-30","2026-07-01","2026-07-02","2026-07-03","2026-07-04","2026-07-05","2026-07-06","2026-07-07","2026-07-08","2026-07-09","2026-07-10","2026-07-11","2026-07-12","2026-07-13","2026-07-14","2026-07-15","2026-07-16","2026-07-17","2026-07-18","2026-07-19","2026-07-20"]},{"name":"sec-finance","url":"https://github.com/arcwolf/sec-finance","dates":["2026-06-20","2026-06-21","2026-06-21","2026-06-21","2026-06-22","2026-06-23","2026-06-24","2026-06-25","2026-06-26","2026-06-27","2026-06-28","2026-06-29","2026-06-30","2026-07-01","2026-07-02","2026-07-03","2026-07-04","2026-07-05","2026-07-06","2026-07-07","2026-07-08","2026-07-09","2026-07-10","2026-07-11","2026-07-12","2026-07-13","2026-07-14","2026-07-15","2026-07-16","2026-07-17","2026-07-18","2026-07-19","2026-07-20"]},{"name":"embedded-engineering-note","url":"https://github.com/arcwolf/embedded-engineering-note","dates":["2026-06-20","2026-06-21","2026-06-22","2026-06-23","2026-06-24","2026-06-25","2026-06-26","2026-06-27","2026-06-28","2026-06-29","2026-06-30","2026-07-01","2026-07-02","2026-07-03","2026-07-04","2026-07-05","2026-07-06","2026-07-07","2026-07-08","2026-07-09","2026-07-10","2026-07-11","2026-07-12","2026-07-13","2026-07-14","2026-07-15","2026-07-16","2026-07-17","2026-07-18","2026-07-19","2026-07-20"]},{"name":"rev-patents","url":"https://github.com/arcwolf/rev-patents","dates":["2026-06-23","2026-06-23","2026-06-23","2026-06-23"]},{"name":"doc-game-idea","url":"https://github.com/arcwolf/doc-game-idea","dates":["2026-07-19","2026-07-19"]},{"name":"md2pdf","url":"https://github.com/arcwolf/md2pdf","dates":["2026-06-22"]}];
var end=new Date(),start=new Date(end);start.setDate(end.getDate()-31);days=[];
for(var d=new Date(start);d<=end;d.setDate(d.getDate()+1))days.push(d.toISOString().slice(0,10));
document.getElementById('gh-range-label').textContent=days[0]+' ~ '+days[days.length-1];
var repoMaps=DATA.map(function(r){var m={};r.dates.forEach(function(d){m[d]=(m[d]||0)+1;});return{name:r.name,url:r.url,map:m,total:r.dates.length};});
function lvl(c,mx){if(!c)return 0;if(c<=mx*.15)return 1;if(c<=mx*.35)return 2;if(c<=mx*.65)return 3;return 4;}
var wrap=document.getElementById('gh-heatmap');
// header
var hdr=document.createElement('div');hdr.className='gh-row';
var hl=document.createElement('div');hl.className='gh-label';hdr.appendChild(hl);
var hc=document.createElement('div');hc.className='gh-cells';
days.forEach(function(d,i){var l=document.createElement('div');l.className='gh-date-lbl gh-cell';l.style.height='14px';l.style.background='none';
if(i%7===0){var dt=new Date(d);l.textContent=(dt.getMonth()+1)+'/'+(dt.getDate());}hc.appendChild(l);});
hdr.appendChild(hc);wrap.appendChild(hdr);
// rows
repoMaps.forEach(function(r){
var mx=Math.max.apply(null,days.map(function(d){return r.map[d]||0;}));
var row=document.createElement('div');row.className='gh-row';
var lbl=document.createElement('div');lbl.className='gh-label';
lbl.innerHTML='<a href="'+r.url+'" target="_blank">'+r.name+'</a> <span style="color:#7d8590;font-size:10px;">('+r.total+')</span>';
var cells=document.createElement('div');cells.className='gh-cells';
days.forEach(function(d){var c=r.map[d]||0;var el=document.createElement('div');el.className='gh-cell';el.dataset.level=lvl(c,mx||1);
el.title=d+(c?' — '+c+' commits':'');cells.appendChild(el);});
row.appendChild(lbl);row.appendChild(cells);wrap.appendChild(row);});
// total row
var totRow=document.createElement('div');totRow.className='gh-row gh-total-row';
var totLbl=document.createElement('div');totLbl.className='gh-label';totLbl.textContent='전체 활동';
var totCells=document.createElement('div');totCells.className='gh-cells';
var totByDay={};days.forEach(function(d){totByDay[d]=repoMaps.reduce(function(s,r){return s+(r.map[d]||0);},0);});
var maxTot=Math.max.apply(null,Object.values(totByDay));
days.forEach(function(d){var c=totByDay[d];var el=document.createElement('div');el.className='gh-cell';el.dataset.level=lvl(c,maxTot);el.style.height='18px';el.title=d+(c?' — total '+c+' commits':'');totCells.appendChild(el);});
totRow.appendChild(totLbl);totRow.appendChild(totCells);wrap.appendChild(totRow);
})();
</script>

### DEVELOPMENTS
2026.03.26 - 2026.06.03
: **clihub.com**
> <img src="{{ site.baseurl }}{{ site.figs.project_prgm_dev_clihub_helloworld_1 }}" />
Introducing **clihub.com** to the world — a new solution that bridges CLI tools and MCP (Model Context Protocol), making command-line power accessible through a unified hub. Turn any CLI into an MCP-ready interface, seamlessly.

2026.04.03 - 2026.04.04
: **Autotrading Strategy Backtest Program**
> <img src="{{ site.baseurl }}{{ site.figs.project_prgm_dev_autotrading_backtest_1 }}" />
**우리는 세상의 특이점을 맞이하고 있습니다.**
해당 프로젝트는 기본적인 아이디어를 가지고 AI툴을 사용하여 5시간만에 만들어졌습니다. 
- Purpose of Development: Backtest for System Trading Strategy
- Schematic Design:
```
  [entry point] main_backtest.py
    └─[GUI Application] sub_backtest_viewer_app.py 
        └─[Indicater Tests] sub_backtest_strategies.py
```
- Functional Details:
```
python main_backtest.py
    └─ sub_backtest_viewer_app.main()
            │
            ├─ DataLoader (Binance Futures API)
            │       │  OHLCV Candle List
            │       │  + calc_rsi / calc_macd / calc_ema
            │       │  + build_ssi_df()
            │       │    (efi, volume_ma, etc)
            ├─ StrategyExecutor
            │   ├─ execute_ema_strategy()
            │   ├─ execute_rsi_strategy()
            │   ├─ execute_macd_strategy()
            │   └─ execute_ssi_strategy()
            │       │  List[TradeSignal]
            │
            ├─ ChartWidget
            └─ SignalTableWidget
```

2026.04.01 - Under Dev.
: **Multiagent Workflow**
> <img src="{{ site.baseurl }}{{ site.figs.project_prgm_dev_openclaw_3 }}" />
1. 목적
  - 프로젝트마다 Session 및 Workspace 격리
  - 시스템 프롬프트 경량화
2. Subagent 구성 사례
  - Awesome Claude Code Subagents [<a href="https://github.com/VoltAgent/awesome-claude-code-subagents" target="_blank">Link</a>]
3. 기본적인 설정 방법
  - [x] 새 Discord Bot 추가
  - [x] 새 Agent 추가
    ```
    openclaw agents add agentname1
    openclaw agents add agentname2
    ```
  - [x] .config에 계정/바인딩 추가 
    ```
    channels: {
      discord: {
        accounts: {
          default: { token: "XXX" },
          agentname1: { token: "XXX" },
          agentname2: { token: "XXX" }
        }
      }
    } 
    bindings: [
      { agentId: "light-speed", match: { channel: "discord", accountId: "default" } },
      { agentId: "agentname1", match: { channel: "discord", accountId: "agentname1" } },
      { agentId: "agentname2", match: { channel: "discord", accountId: "agentname2" } }
    ]
    ```
  - [x] 재시작 & 확인
  ```
  openclaw gateway restart
  openclaw agents list --bindings
  ```
  - [ ] Agent간 협엽 설정(.config)
  ```
  tools.agentToAgent.enabled: true
  ```
  


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
  - [ ] Server on Mac Mini
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


2026.03.08 - 2026.03.28.
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
