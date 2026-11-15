---
title: "Start Here: My MSc in Enterprise IT Management"
date: 2026-11-15 08:00:00 +0100
categories: [Overview]
tags: [e-portfolio, msc, overview]
author: tobi
layout: post
comments: false
pin: true
image: /assets/img/posts/CSPROJ.jpeg
toc: true
---

This e-Portfolio documents my MSc in Enterprise IT Management at the University of Essex Online, which I studied part-time between April 2024 and 2026 alongside my role as a DevOps team lead in the securities trading division of a Swiss bank. Each module has its own post with the learning outcomes, my reflections per unit and links to the submitted work.

## 🎓 The Dissertation

My dissertation, [*Measuring Technical Debt in Mission-Critical Trading Systems*](https://github.com/TobiZeier/MScProject/blob/main/MScProject/Measuring-Technical-Debt-in-Mission-Critical-Trading-Systems.pdf), asks whether technical debt can be prioritised from operational data alone, without access to source code.

- **Approach:** Design Science. Five indicators (incident frequency, mean time to recover, change failure rate, patch recency and unsupported component months) were taken from two years of ITSM and CMDB records at a regulated Swiss financial institution.
- **Artefact:** a TOPSIS-based multi-criteria model that ranks services by debt priority, implemented in [Python](https://github.com/TobiZeier/MScProject/tree/main/code).
- **Key finding:** the ranking is stable across 20,000 weightings at the bottom and within a top cluster of three services, agrees with SAW and VIKOR at the top and bottom of the 2025 ranking, and surfaces infrastructure lifecycle debt that a simple incident count misses.
- **Contribution:** an auditable, reproducible way for regulated institutions to prioritise technical debt from data they already hold.

Read more in the [MSc Computing Project]({% link _posts/2026-01-27-CSPROJ.md %}) post, or see the [defence presentation](https://github.com/TobiZeier/MScProject/blob/main/presentation/Measuring-TD-in-Trading-Systems-Thesis-Defence.pdf).

## 📚 Modules and Results

| # | Module | Assessed work and grades |
|---|--------|--------------------------|
| 0 | [Induction Computing]({% link _posts/2024-04-22-INDM.md %}) | Not graded |
| 1 | [Launching into Enterprise IT Management]({% link _posts/2024-04-30-EIT.md %}) | Collaborative discussion 71% · Programming exercise 80% · Presentation 66% |
| 2 | [Security and Risk Management]({% link _posts/2024-08-01-SRM.md %}) | Group project 67% · Executive summary 85% · Module reflection 80% |
| 3 | [IT Service Management]({% link _posts/2024-10-22-ITSM.md %}) | CMDB design 62% · CMDB implementation 70% |
| 4 | [IT Project Management]({% link _posts/2025-01-28-EIPM.md %}) | Group report 83% · Presentation and reflection 76% |
| 5 | [Into Data Science]({% link _posts/2025-04-29-IDS.md %}) | Collaborative discussion 65% · Data report 60% · Enterprise data strategy 85% |
| 6 | [Cloud Operations and Management]({% link _posts/2025-07-28-COM.md %}) | Group assignment 68% · Cloud strategy 64% · Module reflection 80% |
| 7 | [Research Methods and Professional Practice]({% link _posts/2025-10-21-RMPP.md %}) | Literature review 80% · Proposal presentation 67% · Reflection 71% |
| 8 | [MSc Computing Project]({% link _posts/2026-01-27-CSPROJ.md %}) | Dissertation 70% · Artefact presentation 70% |

## 🧰 What I Can Show For It

- **Risk and decision modelling:** quantitative risk models in Security and Risk Management, which I later extended into the multi-criteria (TOPSIS, SAW, VIKOR) model of the dissertation.
- **IT service management:** designing and implementing a CMDB, then using real ITSM and CMDB records as the evidence base for my research.
- **Data analysis:** exploratory data analysis, statistics and visualisation in Python and Excel, from the [RMPP exercises]({% link _posts/RMPP/2025-12-07-RMPP-Exercises.md %}) to the dissertation's sensitivity analysis.
- **Strategy and governance:** enterprise data and cloud strategies, and regulatory context such as FINMA requirements for ICT risk.
- **Research practice:** literature reviews, research design, ethics approval and academic writing, summarised in my [professional skills matrix]({% link _posts/RMPP/2026-01-03-RMPP-Skills.md %}).

## 🗂 More

- [Projects]({% link _tabs/Projects.md %}): the main pieces of practical work in one place.
- [UoEO_MSc_EIM repository](https://github.com/TobiZeier/UoEO_MSc_EIM): all submissions from Modules 1–8.
- [MScProject repository](https://github.com/TobiZeier/MScProject): dissertation source, code and presentation.
