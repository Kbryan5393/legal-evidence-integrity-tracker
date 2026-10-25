# Legal Evidence Integrity Tracker

**Python | SQL | RapidAPI | Cybersecurity | Data Engineering | Legal Technology**

## Project Overview

The Legal Evidence Integrity Tracker is a Python-based legal technology and data engineering project designed to demonstrate how cryptographic hashing, data cleaning, API integration, and relational databases can support evidence integrity monitoring.

Using fictional legal evidence records, the system identifies data quality issues, generates SHA-256 digital fingerprints, detects file modifications, and stores verification results in SQLite.

## Project Dashboard

![Legal Evidence Integrity Tracker Dashboard](legal_evidence_dashboard_final.png)

## Key Results

- **20** initial evidence records processed
- **19** unique evidence records retained
- **18** files successfully verified
- **1** SHA-256 hash mismatch detected
- **2** records flagged for missing metadata
- **14** unique cryptographic algorithms retrieved through RapidAPI and stored in SQL

## Technologies Used

| Technology | Application |
|---|---|
| Python | Data processing and automation |
| Pandas | Data cleaning and transformation |
| SQLite / SQL | Evidence storage and queries |
| RapidAPI | External API integration |
| SHA-256 / hashlib | Cryptographic integrity verification |
| Matplotlib | Dashboard visualization |
| Google Colab | Python development environment |

## Data Engineering Workflow

1. Generate fictional legal evidence records.
2. Identify duplicate and incomplete records.
3. Clean and standardize metadata using Pandas.
4. Generate sample evidence files and SHA-256 hashes.
5. Verify file integrity and identify modifications.
6. Store evidence and verification results in SQLite.
7. Retrieve cryptographic algorithm information from RapidAPI.
8. Clean and load the API response into SQL.
9. Query the database and visualize the results.

## Legal Technology Applications

This project demonstrates concepts relevant to electronic discovery, litigation support, digital forensics, evidence management, and cybersecurity.

**Disclaimer:** All evidence records and case identifiers are fictional. This is an educational portfolio prototype, not a production chain-of-custody or forensic evidence-management system.
