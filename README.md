# Compliance Process Optimisation & Operational Risk Monitoring

> Analysed operational lifecycles and control check bottlenecks across investor onboarding workflows to eliminate regulatory SLA breach risks and optimize operational capacity.

## **View the Full Project →**

## About the Project

ABC Fund is a fictional Luxembourg-based Alternative Investment Fund Manager (AIFM) modeled and mimic on CSSF regulations, managing European investment vehicles across Investor Services, Fund Administration, Operations, and Compliance.

As investor onboarding volumes and regulatory oversight grew, management sought to evaluate end-to-end case processing lifecycles, identify operational bottlenecks, and eliminate SLA breach risks. This project investigates transactional audit trails covering **18,000 cases**, stage-by-stage workflow histories, and **23,478 control assessments**.

The analysis focuses on identifying where operational inertia originates, pinpointing stage bottlenecks, evaluating control check remediation cycle times, detecting priority misunderstanding, and mitigating regulatory SLA exposure to protect the firm's license-to-operate.

## Objective

The objective was to understand:

* How ABC Fund was performing against aggregate and regulatory SLA targets across all four business units.


* Where cases were getting stuck between intake, screening, analyst review, escalation, and closure.


* Which specific control checks (PEP & Sanctions, EDD, KYC/CDD) caused the longest remediation cycle drag.


* How operational queue handling behaviors and manual priority overrides impacted turnaround times and escalation rates.


* How targeted data engineering and analytical frameworks could inform operational and regulatory risk mitigation strategies.



## Project Approach

The investigation followed a structured, multi-pillar analytical pipeline, progressing from data staging and risk diagnostics to workflow profiling, control check analysis, and strategic roadmap design.

**Data Staging & Metric Engineering → SLA Breach & Risk Diagnosis → Workflow Bottleneck & Backlog Profiling → Control Check & Remediation Analysis → Escalation Pathways & Governance Audit → Executive Dashboard Architecture → Strategic Remediation Roadmap**

This progressive framework allowed the analysis to move beyond surface-level averages to uncover true operational root causes, quantify capacity constraints, and deliver evidence-based business recommendations.

## Technical Stack

**Data Staging & SQL Engineering**

* T-SQL / MS SQL Server


* Database Staging Views (`dbo.vw_Dim_*`, `dbo.vw_Fact_*`)


* Data transformation, deduplication, and standardization


* Advanced aggregations, CTEs, window functions, and `CASE` logic


* SLA target engineering and business day sequence modeling



**Data Modeling & Business Intelligence**

* Power BI


* Star Schema Data Modeling


* 16 Explicit DAX Measures


* Time-intelligence calculations and dynamic filter contexts


* Multi-fact modeling and directional cross-filtering



**Data Visualization & Storytelling**

* 4-Page Executive Dashboard Suite


* SLA Breach Severity & Variance Heatmaps


* Workflow Throughput & Stage Duration Share Profiling


* Control Assessment Outcomes & Remediation Lifecycle Visuals


* Custom Scatter Plots for Turnaround Latency vs. Volume Analysis



## Key Result

The analysis revealed that while aggregate breach rates appeared low (**2.19% Internal, 1.89% Regulatory**), overdue cases in **Compliance (2.62%)** and **Investor Services (2.21%)** suffered from severe tail-risk delays, staying overdue by an average of **19 to 30 days past deadline**.

Granular stage profiling identified **Analyst Review** as the primary operational bottleneck, absorbing **48.59% of total workflow hours** and trapping **74.6% of active Work-In-Progress (WIP)** cases.

Control assessment diagnostics showed a **5.13% fail rate**, with **PEP & Sanctions Screening** creating the largest drag, taking up to **3.05 days (73.25 hours)** per profile exception. Furthermore, tagging Low-Risk cases as "Urgent" artificially spiked their escalation rates from **0.0% to 29.9%**, driving average escalation dwell time to **47.46 hours**.

The project translated these insights into three strategic priorities: **automating first-line PEP screening triage, enforcing system-driven priority governance, and deploying a dedicated regulatory tail-risk remediation taskforce**.

## Data

This project uses a **real-world synthetic dataset** created specifically for portfolio purposes. It does not contain confidential data from any real company, organisation, fund manager, or individual.

## Full Project

The complete case study contains the detailed business context, analytical approach, findings, strategic recommendations, expected business impact, technical implementation, dashboard, and lessons learned.

## **View the Full Project →**
