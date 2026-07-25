# Replication Package
## Toward Effective LLM-Based Automated Program Repair: A Taxonomy of Prompting Strategies and Key Trends, Insights, and Challenges



This package supports full replication of the survey reported in
Section 2 (Methodology) of the paper. 

This paper is currently under review at the **Journal of Systems and Software (JSS)**.

---

## ✍️ Authors

- **Omar Messarhi** — RLP Lab and Computer Science Department, University of Biskra, Algeria. Email: [omar.messarhi@univ-biskra.dz](mailto:omar.messarhi@univ-biskra.dz)
- **Lamine Kerdoudi** — RLP Lab and Computer Science Department, University of Biskra, Algeria. Email: [l.kerdoudi@univ-biskra.dz](mailto:l.kerdoudi@univ-biskra.dz)
- **Okba Tibermacine** — National School of Artificial Intelligence, Algiers, Algeria. Email: [okba.tibermacine@ensia.edu.dz](mailto:okba.tibermacine@ensia.edu.dz)

---

## 📖 Table of Contents

1. [Overview](#overview)
2. [Authors](#-authors)
3. [Repository Structure](#repository-structure)
4. [Folder Details](#folder-details)
   - [01_search_strings](#01_search_strings)
   - [02_search_results](#02_search_results)
   - [03_included_studies](#03_included_studies)
5. [How to Reproduce the Results](#how-to-reproduce-the-results)
6. [Requirements / Dependencies](#requirements--dependencies)
7. [Contact](#contact)
8. [Acknowledgments](#acknowledgments)

---

## 1. Overview

This repository contains the full replication package for the survey titled:

> **"Toward Effective LLM-Based Automated Program Repair: A Taxonomy of Prompting Strategies and Key Trends, Insights, and Challenges"**

The purpose of this package is to provide full transparency and enable the replication or verification of the search, selection, and analysis processes described in the associated publication. All raw data, search queries, and result lists are provided in their original forms.

---

## 2. Repository Structure

The repository is organized into three main folders:

.
├── 01_search_strings/
├── 02_search_results/
├── 03_included_studies/
└── README.md


---

## 3. Folder Details

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

## 4. How to Reproduce the Results

To fully reproduce the search and selection process:

**Run the Queries:** Copy the strings from `01_search_strings/` into the respective digital libraries' advanced search interfaces, using the same date ranges and filters.

---

## 5. Requirements / Dependencies

- To view `.bib` files, any reference manager (e.g., Zotero, Mendeley, JabRef) is recommended.
- To view `.csv` and `.xlsx` files, a spreadsheet viewer (e.g., Microsoft Excel, Google Sheets, or LibreOffice Calc) is required.

---

## 7. Acknowledgments

- We acknowledge all the authors of the primary studies included in this survey.

---

**Last Updated:** [2026-07-25]
