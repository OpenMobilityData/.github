# OpenMobilityData

Public records and open data on mobility in Montréal, kept with their provenance, and the code that reads them. The repositories below were created by a resident of Côte-des-Neiges–Notre-Dame-de-Grâce, most of them around one question, the protected bike lane on rue de Terrebonne and the borough's plan of October 2026 to convert one direction to parking each winter, but much of the material is city-wide and is meant to outlast that question: police-reported collisions for the whole island, the City's access-to-information releases, the City's bicycle counters, the air-quality network.

This page is the map. Each link below opens the repository's README, which says what the repository holds, where each document came from and how to reproduce every table and figure.

## The rue de Terrebonne bike lane

| Repository | What it holds |
|---|---|
| [**Terrebonne-access-requests**](https://github.com/OpenMobilityData/Terrebonne-access-requests/blob/main/README.md) | Records released under Quebec's Access to Information Act on the lane, exactly as received, one folder per request: the study of the street and the mandate behind the winter plan ([2026-581](https://github.com/OpenMobilityData/Terrebonne-access-requests/blob/main/2026-581/README.md)), the Kensington counter's daily and hourly records ([2025-697](https://github.com/OpenMobilityData/Terrebonne-access-requests/blob/main/2025-697/README.md), [2026-300](https://github.com/OpenMobilityData/Terrebonne-access-requests/blob/main/2026-300/README.md)), the 2024 petitions against the lane ([2025-081](https://github.com/OpenMobilityData/Terrebonne-access-requests/blob/main/2025-081/README.md)), the cycling-network « audit » ([2025-12847](https://github.com/OpenMobilityData/Terrebonne-access-requests/blob/main/2025-12847/README.md)). Executive summaries in English and French, parsed tables and scripts are kept apart under each request's `derived/`. Every page reference links to the page on the [GitHub Pages copy](https://openmobilitydata.github.io/Terrebonne-access-requests/). |
| [**Terrebonne-open-sources**](https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/README.md) | Public documents on the lane that were not obtained under the Act, with their provenance, one folder per document or event: the 2023 EXP mobility study, the 2020–21 working committee, the 2024 project approvals, the borough's Plan local de déplacements, Vision Zéro, checked transcripts of the borough, City and agglomeration council sittings of 2026 and of the radio interviews of 2025–26, the City's counters and its 2026 cycling-network review, the 1954–55 fire-insurance plans read for off-street parking, the press record of collisions on the street.|
| [**Terrebonne-open-sources / 2026-evidence-graph**](https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/2026-evidence-graph/README.md) | The evidence graph: every checked public statement, document, dataset and figure on the winter conversion as a node, with factual relations between them (who said what, when, from which source; which figure was computed from which data; which statements differ). Source of truth in two CSV files; [interactive page](https://openmobilitydata.github.io/Terrebonne-open-sources/2026-evidence-graph/evidence_graph.html). |
| [**Terrebonne-telraam**](https://github.com/OpenMobilityData/Terrebonne-telraam/blob/main/README.md) | Hourly counts from two citizen Telraam S2 sensors on the street (King Edward, August 2024 to May 2026; Draper, September 2024 to January 2026), with the scripts and year-over-year figures. Daylight counts only: the check and the history, not the official record. |

A selection of folders in Terrebonne-open-sources, for readers coming to the subject:
[the 2023 EXP study](https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/2023-exp-mobility-study/README.md) ·
[the 2024 approvals](https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/2024-project-approval/README.md) ·
[borough council, October 6, 2026](https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/2026-10-06-borough-council/README.md) ·
[CBC Daybreak, October 9, 2026](https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/2026-cbc-daybreak-interview/README.md) ·
[the City's bicycle counters](https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/2026-city-bike-counters/README.md) ·
[off-street parking as built, 1954–55](https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/1954-underwriters-plans-terrebonne-garages/README.md) ·
[the winter numbers on one page](https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/2026-poster-winter-numbers/README.md).

## Montréal-wide records

| Repository | What it holds |
|---|---|
| [**Montreal-collisions**](https://github.com/OpenMobilityData/Montreal-collisions/blob/main/README.md) | Police-reported road collisions: the City's SPVM open data 2012–2021 and the SAAQ accident reports 2011–2022, kept as two series; loaders, maps and charts by mode and severity for the island and for Notre-Dame-de-Grâce; the record preceding each of the 31 cyclist fatalities of 2012–2021 at the same location; a test of whether a location's earlier record predicts a later death; collisions at counted intersections set against the City's intersection counts, with the limits of that exposure stated. |
| [**Montreal-access-requests**](https://github.com/OpenMobilityData/Montreal-access-requests/blob/main/README.md) | Releases by the City and its boroughs under the Access Act on subjects other than Terrebonne, with provenance: how the central city sets three boroughs' operating budgets ([2022-1447](https://github.com/OpenMobilityData/Montreal-access-requests/blob/main/2022-1447/README.md)), borough borrowing and debt 2005–2020 ([2022-1449](https://github.com/OpenMobilityData/Montreal-access-requests/blob/main/2022-1449/README.md)), the City's legal costs in the Montgomery matter ([2021-464](https://github.com/OpenMobilityData/Montreal-access-requests/blob/main/2021-464/README.md)), and the City's proactive-disclosure bundles on budgets, cycling and inventories. |

## Web applications

| Repository | What it does |
|---|---|
| [**BikeStat**](https://github.com/OpenMobilityData/BikeStat/blob/main/README.md) | [bikestat.org](https://bikestat.org): traffic counts from a curated set of sensors in Côte-des-Neiges–Notre-Dame-de-Grâce (City counters, Telraam, the borough's Eco-Counter loop as released under the Act) overlaid on one chart, hour to month, with year-on-year comparison; English and French. Rust and WebAssembly, everything client-side. |
| [**AirQualityMTL**](https://github.com/OpenMobilityData/AirQualityMTL/blob/main/README.md) | [mtl-aq.org](https://mtl-aq.org): the City's air-quality network (RSQA) hourly measurements 1986–2024, as an interpolated map by pollutant and period and as time series by station. Same stack as BikeStat. |

## Tools and earlier work

| Repository | What it holds |
|---|---|
| [**SAAQAnalyzer**](https://github.com/OpenMobilityData/SAAQAnalyzer/blob/main/README.md) | macOS application for importing and analysing the SAAQ's open tables of vehicle registrations and driving licences. |
| [**census-extractor**](https://github.com/OpenMobilityData/census-extractor/blob/main/README.md) | Shell scripts that extract chosen characteristics from Statistics Canada census files into small CSVs for QGIS. |
| [**Telraam**](https://github.com/OpenMobilityData/Telraam/blob/main/README.md) | Scripts for Telraam S2 data (2025). For the Terrebonne sensors, the current data and figures are in Terrebonne-telraam and BikeStat. |
| [**Counting**](https://github.com/OpenMobilityData/Counting) | Code and data for bike counting (February 2025). |
| [**Budgets**](https://github.com/OpenMobilityData/Budgets/blob/main/README.md) | City of Montréal operating budgets, development plans, parking reports and the Plan vélo, as PDFs (February 2025). |

## How the record repositories are kept

The four record repositories (the two Terrebonne ones, Montreal-collisions and Montreal-access-requests) follow the same rules, stated in each README:

- One folder per document, request or dataset, with a `README.md` that gives the issuer, the date, where and when the document was obtained and what it says; `raw/` holds the documents exactly as obtained and is never edited; `derived/` holds anything made from them, with the script beside each table or figure.
- The READMEs describe and quote. They do not evaluate, recommend or impute motives.
- Every page reference in a public README links to the page (`#page=N`) where a Pages copy exists.
- Third-party data are named with a link and never redistributed unless their licence allows it; City open data (CC BY 4.0) is redistributed with credit.
- The full edit history is public by design.

## Use of AI

Much of the code and many of the drafts in these repositories were produced with an AI assistant, Anthropic's Claude, in interactive sessions directed by the author. The author chose the questions, supplied the sources, reviewed every output, and checked every quotation, page reference and figure against the documents; the author alone is responsible for the content. Commits to which the assistant contributed name it as co-author, so the division of work is visible in the history, and errors found in its work are corrected in the open like any other. Nothing in a `raw/` folder is edited by anyone, human or machine.

Everything is open to review: all source code, documents and data in these repositories are publicly visible, as is the complete change log of every file. Anyone is welcome to read any of it and check it for errors and omissions. Anyone with a concern is welcome to open an issue on GitHub in the repository concerned; every issue submitted is publicly visible, as is its answer. Each repository's README carries the same statement.

## About the author

The repositories were created, and the derived documents written, by Rick Hoge, a resident of Côte-des-Neiges–Notre-Dame-de-Grâce who cycles on Terrebonne in every season. He works as a data scientist and is a professor in the Faculty of Medicine at McGill University, where his research is in neuroscience and biomedical engineering. The work here is personal: done as a resident, on his own time, from public records, and representing no position of McGill University or of any other organization; the affiliation is given for identification only. Corrections are welcome through each repository's issue tracker.
