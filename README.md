# MedAxis Intelligence — Senior Data Scientist Simulation
### Project Lab | Healthcare AI Decision-Support Platform

---

> **You are joining MedAxis Intelligence as a Senior Data Scientist.**
> Meridian Health Group — a network of 6 acute hospitals — has signed a £4.2M contract.
> You have 12 weeks to deliver a production-ready AI decision-support platform.
> Missing the Week 12 board presentation triggers a £420,000 penalty clause.

---

## What You Will Build

A production-ready healthcare AI platform covering:
- Patient 30-day readmission risk prediction
- Hospital bed demand forecasting
- Length-of-stay prediction & resource optimisation
- Clinical NLP entity extraction pipeline
- RAG-powered guideline search assistant
- FastAPI model serving with Docker
- MLOps monitoring, drift detection & CI/CD
- Executive board deck with ROI model

---

## Candidate Files

| File | Description | Used In |
|------|-------------|---------|
| [`medaxis_company_brief.pdf`](medaxis_company_brief.pdf) | Business problem, current metrics, sprint timeline, regulatory context, glossary | Phase 1 |
| [`medaxis_process_notes.pdf`](medaxis_process_notes.pdf) | Incomplete handover notes — stages 4–12 intentionally missing | Phase 1 |
| [`medaxis_data_dictionary.pdf`](medaxis_data_dictionary.pdf) | FHIR-style column definitions, data types, known quality issues | Phase 2 |
| [`meridian_hospital_reference.pdf`](meridian_hospital_reference.pdf) | Site codes, ward codes, ICD-10 top diagnoses | Phase 2 |
| [`meridian_clinical_pathways.pdf`](meridian_clinical_pathways.pdf) | Escalation policies, bed management protocol, AI use policy | Phase 9 |
| [`medaxis_responsible_ai_framework.pdf`](medaxis_responsible_ai_framework.pdf) | Responsible AI framework starter — complete in Phases 5 & 11 | Phase 11 |

---

## Data Files

| File | Rows | Description |
|------|------|-------------|
| [`patients.csv`](patients.csv) | 2,012 | Patient demographics — contains near-duplicates and null values |
| [`admissions.csv`](admissions.csv) | 3,695 | Primary modelling dataset — encounters, diagnoses, LOS, readmission flag |
| [`lab_results.csv`](lab_results.csv) | 11,027 | Lab test results per encounter |
| [`observations.csv`](observations.csv) | 11,972 | Vital sign observations per encounter |
| [`medications.csv`](medications.csv) | 8,844 | Medication records per encounter |
| [`clinical_notes_sample.csv`](clinical_notes_sample.csv) | 200 | Discharge summary notes for NLP pipeline (Phase 8) |
| [`weekly_demand_forecast.csv`](weekly_demand_forecast.csv) | 104 | Weekly hospital demand — 2 years of data |

---

## ⚠️ Data Quality Warning

All data files contain intentional quality issues reflecting real healthcare data:
- Missing values, duplicate rows, inconsistent formatting, impossible dates
- One data file contains a **critical anomaly** that will produce a wrong model if not identified
- The process notes are **deliberately incomplete** — you must fill the gaps

---

## Tools You Will Use

`Python` `PostgreSQL` `DBeaver` `Jupyter` `Pandas` `Scikit-learn` `XGBoost` `SHAP`
`Great Expectations` `Prophet` `Statsmodels` `Power BI` `spaCy` `Hugging Face`
`LangChain` `ChromaDB` `Streamlit` `FastAPI` `Docker` `MLflow` `EvidentlyAI`
`GitHub Actions` `Pytest` `Postman`

---

## Simulation Details

| | |
|--|--|
| **Role** | Senior Data Scientist |
| **Difficulty** | Mid |
| **Phases** | 12 |
| **Estimated hours** | 40–60 |
| **Regulatory frameworks** | MHRA · NHS DTAC · GDPR · EU AI Act · HIPAA · FDA SaMD |
| **Platform** | [Project Lab](https://projectlab.io) |

---

*This repository is part of the Project Lab simulation platform. All company names, patient data, and clinical scenarios are fictional and generated for training purposes only.*
