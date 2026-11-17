---
# the default layout is 'page'
icon: fas fa-terminal
order: 5
---

The main pieces of practical work from my MSc, with links to the code and documents.

## Technical Debt Prioritisation Framework

*MSc dissertation, 2026*

![Technical debt prioritisation framework](/assets/img/posts/CSPROJ.jpeg){: w="1200" h="654" }

**At a glance:** 6 services · 5 indicators · 2 years of ITSM and CMDB records · 20,000 weightings tested · dissertation 70%

A quantitative framework that ranks IT services by technical debt priority using only operational data: incident frequency, mean time to recover, change failure rate, patch recency and unsupported component months, taken from two years of ITSM and CMDB records at a Swiss financial institution. The services are ranked with TOPSIS, cross-checked against SAW and VIKOR, and stress-tested across 20,000 weightings.

**Tech:** Python, TOPSIS / multi-criteria decision-making, Quarto, LaTeX

- 📄 [Dissertation](https://github.com/TobiZeier/MScProject/blob/main/MScProject/Measuring-Technical-Debt-in-Mission-Critical-Trading-Systems.pdf)
- 📊 [Defence presentation](https://github.com/TobiZeier/MScProject/blob/main/presentation/Measuring-TD-in-Trading-Systems-Thesis-Defence.pdf)
- 💻 [Code](https://github.com/TobiZeier/MScProject/tree/main/code)
- 📝 [Module write-up]({% link _posts/2026-01-27-CSPROJ.md %})

## Configuration Management Database (CMDB)

*IT Service Management, 2024*

![Configuration management database](/assets/img/posts/ITSM.jpeg){: w="1200" h="654" }

**At a glance:** Design document, ServiceNow build and recorded demo · design 62% · implementation 70%

Design and implementation of a CMDB for IT service and security management, from the data model with its configuration items and relationships to a working implementation and a recorded demonstration. It was also my first hands-on work with the kind of CMDB data I later used in the dissertation.

**Tech:** ServiceNow (Personal Developer Instance), CMDB data modelling

- 📄 [Design document](https://github.com/TobiZeier/UoEO_MSc_EIM/blob/main/Module3_Information_Technology_Service_Management/TobiasZeierCMDB_Design-111124.pdf)
- 📁 [Implementation and demonstration](https://github.com/TobiZeier/UoEO_MSc_EIM/tree/main/Module3_Information_Technology_Service_Management/Assignment2)
- 📝 [Module write-up]({% link _posts/2024-10-22-ITSM.md %})

## Sorting Performance: Python vs C

*Launching into Enterprise IT Management, 2024*

![Sorting performance in Python and C](/assets/img/posts/EIT.jpeg){: w="1200" h="654" }

**At a glance:** Python vs C on a large generated dataset · programming exercise 80%

Sorting a large generated dataset in Python and comparing the run time against a C-based solution, to see how language choice and algorithm affect efficiency at scale.

**Tech:** Python, C

- 📁 [Code and report](https://github.com/TobiZeier/UoEO_MSc_EIM/tree/main/Module1_Launching_into_Enterprise_IT_Management/Assignment2)
- 📝 [Module write-up]({% link _posts/2024-04-30-EIT.md %})
