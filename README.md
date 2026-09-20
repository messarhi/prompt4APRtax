# Toward Effective LLM-Based Automated Program Repair: A Taxonomy of Prompting Strategies and Key Trends, Insights, and Challenges

Automated Program Repair (APR) remains a core challenge in software engineering, primarily constrained by the rigid boundaries of search-based and template-driven methods. The emergence of Large Language Models (LLMs) has catalyzed a paradigm shift, enabling prompting-based approaches that exploit pre-trained reasoning capabilities to repair code without extensive fine-tuning. However, the rapid proliferation of these techniques lacks a systematic categorization framework, obscuring their unique functions and hindering practical application. In this paper, we present a taxonomy and analysis of recent prompting-based APR research. We propose a classification that organizes prompting strategies into three distinct families: Context and Structure Awareness, Cognitive Reasoning Enhancement, and Quality Assurance. Our findings highlight a highly concentrated research landscape; specifically, 66% of the reviewed studies rely on GPT-3.5 or GPT-4, and (54.7%) evaluate their approaches using the Defects4J benchmark. More critically, we identify systemic methodological limitations that limit real-world validity: 34% of studies rely on perfect fault localization, and 41.5% target single-function bugs, assumptions that significantly inflate performance metrics. This taxonomy synthesizes the state-of-the-art, exposes these “reality gaps” and outlines concrete research directions to transition prompting-based APR from academic benchmarks to industrial deployment. 

This package supports full replication of the survey reported in Section 2 (Methodology) of the paper. 

---

## ✍️ Authors

- **Omar Messarhi** — RLP Lab and Computer Science Department, University of Biskra, Algeria.
  Email: [omar.messarhi@univ-biskra.dz](mailto:omar.messarhi@univ-biskra.dz)
- **Mohamed Lamine Kerdoudi** — RLP Lab and Computer Science Department, University of Biskra, Algeria; and IRISA and Université Bretagne Sud, Vannes, France.
  Emails: [l.kerdoudi@univ-biskra.dz](mailto:l.kerdoudi@univ-biskra.dz)   and  [kerdoudi@univ-ubs.fr](mailto:kerdoudi@univ-ubs.fr)
- **Okba Tibermacine** — National School of Artificial Intelligence, Algiers, Algeria.
  Email: [okba.tibermacine@ensia.edu.dz](mailto:okba.tibermacine@ensia.edu.dz)

---

## 📖 Table of Contents

1. [Overview](#overview)
2. [Repository Structure](#repository-structure)
3. [Folder Details](#folder-details)
   - [01_search_strings](#01_search_strings)
   - [02_search_results](#02_search_results)
   - [03_included_studies](#03_included_studies)
4. [How to Reproduce the Results](#how-to-reproduce-the-results)
5. [Requirements / Dependencies](#requirements--dependencies)
6. [Acknowledgments](#acknowledgments)

---

## 🔍 Overview

This repository contains the full replication package for the survey titled:

> **"Toward Effective LLM-Based Automated Program Repair: A Taxonomy of Prompting Strategies and Key Trends, Insights, and Challenges"**

The purpose of this package is to provide full transparency and enable the replication or verification of the search, selection, and analysis processes described in the associated publication. All raw data, search queries, and result lists are provided in their original forms.

---

## 🌳 Repository Structure

The repository is organized into three main folders:

.
├── 01_search_strings/
├── 02_search_results/
├── 03_included_studies/
└── README.md


---

## 🗃️ Folder Details

### 📁 01_search_strings
**Purpose:** Contains the final search strings (queries) used to query the digital libraries.

- **Files:**
  - `search_strings.md` – The Boolean query used for each DATABASE.
- **Format:** The file contains the exact string, including field codes (e.g., TITLE-ABS-KEY) and date filters if applied.

### 📁 02_search_results
**Purpose:** Stores the raw, unprocessed results exported from each digital library.

- **Files:**
  - `scopus.ris` – Exported records from Scopus.
  - `acm.bib` – Exported records from ACM Digital Library.
  - `ieee.ris` – Exported records from IEEE.
  - `scholar.ris` – Exported records from Google Scholar.
- **Note:** These files are stored as-is to ensure data provenance.

### 📁 03_included_studies
**Purpose:** Contains the final set of studies selected for inclusion after the full screening process (title/abstract + full-text).

- **Files:**
  - `included_studies.bib` – The final bibliography of included papers.
  - `included_studies.csv` – A summary table with relevant metadata (Title, Year, DOI, Venue, Abstract, etc.).

---

## 🔁 How to Reproduce the Results

To fully reproduce the search and selection process:

**Run the Queries:** Copy the strings from `01_search_strings/` into the respective digital libraries' advanced search interfaces, using the same date ranges and filters.

---

## 📦 Requirements / Dependencies

- To view `.bib` files, any reference manager (e.g., Zotero, Mendeley, JabRef) is recommended.
- To view `.csv` and `.xlsx` files, a spreadsheet viewer (e.g., Microsoft Excel, Google Sheets, or LibreOffice Calc) is required.

---

## 🙏 Acknowledgments

- We acknowledge all the authors of the primary studies included in this survey.

---
## 📝 Citation

```bibtex
@article{MESSARHI2027113101,
title = {Toward effective LLM-based Automated Program Repair: A taxonomy of prompting strategies and key trends, insights, and challenges},
journal = {Journal of Systems and Software},
volume = {243},
pages = {113101},
year = {2027},
issn = {0164-1212},
doi = {https://doi.org/10.1016/j.jss.2026.113101},
url = {https://www.sciencedirect.com/science/article/pii/S0164121226003341},
author = {Omar Messarhi and Mohamed Lamine Kerdoudi and Okba Tibermacine},
keywords = {AutomAted Program Repair, Large Language Models, Prompting strategies, Software debugging, Program synthesis, LLM-based APR},
abstract = {Automated Program Repair (APR) remains a core challenge in software engineering, primarily constrained by the rigid boundaries of search-based and template-driven methods. The emergence of Large Language Models (LLMs) has catalyzed a paradigm shift, enabling prompting-based approaches that exploit pre-trained reasoning capabilities to repair code without extensive fine-tuning. However, the rapid proliferation of these techniques lacks a systematic categorization framework, obscuring their unique functions and hindering practical application. In this paper, we present a taxonomy and analysis of recent prompting-based APR research. We propose a classification that organizes prompting strategies into three distinct families: Context and Structure Awareness, Cognitive Reasoning Enhancement, and Quality Assurance. Our findings highlight a highly concentrated research landscape; specifically, 66% of the reviewed studies rely on GPT-3.5 or GPT-4, and (54.7%) evaluate their approaches using the Defects4J benchmark. More critically, we identify systemic methodological limitations that limit real-world validity: 34% of studies rely on perfect fault localization, and 41.5% target single-function bugs, assumptions that significantly inflate performance metrics. This taxonomy synthesizes the state-of-the-art, exposes these “reality gaps” and outlines concrete research directions to transition prompting-based APR from academic benchmarks to industrial deployment. The replication package of this survey is available at: https://github.com/messarhi/prompt4APRtax.}
}
```
---
**Last Updated:** [2026-09-20]
