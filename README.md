# GL-Interface-Reconciliation-Automation

## Project Overview

This case study focused on designing an automated General Ledger (GL) interface between SICS and SunSystems.
The existing process involved manual quarterly exports and imports with limited reconciliation transparency. The objective was to design a scalable, automated, and auditable integration framework.

---

## Business Problem

Client A manually exported GL data from SICS and imported it into SunSystems.

This created:

- High manual effort  
- Mapping and transformation errors  
- Limited reconciliation visibility  
- Slower period-end closing  

The task was to design a structured automation solution with built-in reconciliation controls.

---

## Solution Design

### As-Is vs To-Be Process

**As-Is**

- Manual export from SICS  
- Manual transformation  
- Quarterly import into Sun  
- Limited reconciliation transparency  

**To-Be**

- Automated scheduled extraction (daily)  
- Transformation & mapping layer  
- API-based upload to SunSystems  
- Automated reconciliation & validation logic  
- Audit logging & error notifications  

---

## Functional Requirements

- Scheduled GL data extraction  
- Data mapping & transformation engine  
- API integration with SunSystems  
- Automated reconciliation logic  
- Exception logging & alerts  

---

## Non-Functional Requirements

- System reliability  
- Secure data transmission  
- Maintainable mapping configuration  
- Audit trail capability  
- Overnight batch execution  

---

## Reconciliation Analysis (EPI Dataset)

I analyzed reconciliation results across 181 records covering:

- Estimated Premium Income (EPI)  
- Minimum Premium (MinPrem)  

### Key Findings

- Total MinPrem variance: $1.596B  
- Top 10 policies accounted for ~30% of total variance  
- Data mislabeling (EPI ↔ MinPrem) distorted reporting  
- Missing identifiers reduced traceability  

---

## Root Causes Identified

- Data mapping inconsistencies  
- Field misclassification  
- Reporting period misalignment  
- Lack of standardized unique identifiers  

---

## Recommendations

- Prioritize high-impact variances (> $100K)  
- Correct mapping logic before reruns  
- Standardize transaction identifiers  
- Implement automated variance alerts  

---

## Tools & Approach

- Process flow modeling (As-Is / To-Be)  
- Variance analysis  
- Risk assessment framework  
- Structured requirement definition  

---

## Why This Project Matters

This project demonstrates:

- Systems thinking  
- Financial data reconciliation  
- Process automation design  
- Risk identification  
- Business-technical translation  

It bridges analytics and business process design.
