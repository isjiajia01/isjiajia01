# Jiajia Zhang

Operations Research · Optimization · Decision Systems  
MSc Mathematical Modelling & Computation, DTU · Copenhagen

[Website](https://zhangjiajia.me) · [Email](mailto:isjiajiazhang@gmail.com) · [GitHub](https://github.com/isjiajia01)

## About

I work at the intersection of operations research, optimization, and decision-support systems. My core focus is taking complex operational problems, structuring them into tractable models, and engineering software so teams can act on the results. Working languages: English and Chinese.

## Focus

- Constrained optimization modeling for operational planning and resource allocation
- Rolling-horizon decision workflows for logistics and dynamic environments
- Internal tools and decision-support systems with clear evidence and human review
- Product-grade software and reproducible workflows that bridge research and practice

## Selected Work

- **[DTU Thesis Workspace](https://github.com/isjiajia01/dtu-thesis-workspace)**  
  Last-mile delivery in Copenhagen is fragmented: dozens of operators, overlapping zones, no unified planning layer. I modeled the routing problem as a constrained optimization program and built a rolling-horizon controller that re-solves at each decision point as new orders arrive—keeping routes feasible under real-time demand uncertainty. The workspace spans manuscript, retained controller, and integrated solver with reproducible experiment pipelines.  
  `Python` · `Julia` · `Optimization` · `Simulation` · `Logistics`

- **[job-ops](https://github.com/isjiajia01/job-ops)**  
  The standard job search is a manual, high-noise process: scan boards, read JDs, guess fit, write cover letters from scratch. I built a self-hosted system that automates the entire pipeline—pulling listings from multiple sources, scoring each role against a structured profile with an LLM, generating tailored resume and cover letter drafts, and tracking application status end-to-end. Deployed on Oracle Cloud with a Postgres backend and RxResume PDF export.  
  `Python` · `FastAPI` · `PostgreSQL` · `Docker` · `Workflow Automation`

- **[Nu](https://github.com/isjiajia01/Nu)**  
  Transit riders in Copenhagen juggle multiple apps to plan a journey: one for departures, one for maps, one for real-time vehicles. Nu consolidates this into a single native iOS experience—nearby stations, live departure boards, journey step-by-step detail, map exploration, walking ETAs, and vehicle tracking—built entirely in SwiftUI with direct integration to public transit APIs.  
  `Swift` · `SwiftUI` · `MapKit` · `Transit APIs` · `iOS`

- **[Personal Website](https://zhangjiajia.me)** · [Repository](https://github.com/isjiajia01/personal-website)  
  Bilingual portfolio and writing platform covering decision systems, engineering, and product experiments. Built with Next.js, deployed via GitHub Actions to Oracle Cloud Infrastructure.  
  `Next.js` · `TypeScript` · `Tailwind CSS`

## Toolbox

- **Modelling & Optimization** — Python, Julia, Gurobi, OR-Tools, Pyomo, R
- **Engineering & Systems** — FastAPI, Next.js, TypeScript, PostgreSQL, Docker, Git
- **Product & Spatial** — SwiftUI, MapLibre / GIS, public transit & GTFS data

## Principles

1. Prefer simple, defensible analytical choices over decorative complexity.
2. Keep outputs reproducible, inspectable, and decision-ready.
3. Optimize for action: clarify the problem, choose the right method, and deliver usable tooling.
