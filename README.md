# Fintech Due Diligence Automation Platform

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" alt="Snowflake"/>
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" alt="dbt"/>
  <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Apache Airflow"/>
  <img src="https://img.shields.io/badge/Great_Expectations-FF6F61?style=for-the-badge&logoColor=white" alt="Great Expectations"/>
  <img src="https://img.shields.io/badge/Metabase-509EE3?style=for-the-badge&logo=metabase&logoColor=white" alt="Metabase"/>
</p>

An end-to-end data engineering and analytics platform designed to automate corporate due diligence in India. The platform consolidates public corporate registry data, insolvency records, regional financial statistics, and historical monetary policy indicators into a unified analytical workflow for lenders, investors, and corporate buyers.

This repository contains the end-to-end data pipeline and platform engineered for a fintech due diligence client. Traditionally, corporate due diligence in India requires analysts to manually assess target companies one by one across multiple fragmented sources, specifically the Ministry of Corporate Affairs (MCA) registry, the Insolvency and Bankruptcy Board of India (IBBI) portal, and manual spreadsheets. This platform unifies and automates that entire process into a single interface as analytical workflow for lenders, investors, and corporate buyers.

By integrating automated extraction, data transformation, and orchestration layers, the platform instantly answers four critical analytical questions for lenders and buyers prior to a transaction:

1. **Is the target company legally registered and active?** (Automated via MCA Registry)
2. **Has the company ever been involved in bankruptcy or insolvency proceedings?** (Automated via IBBI)
3. **How does the company's financial footprint compare against its regional peers?** (Calculated via MCA CDM state statistics)
4. **What was the macroeconomic interest rate landscape at the time of evaluation?** (Correlated via historical RBI policy rates)

By consolidating these disparate public data streams, the platform replaces slow, manual data collection with a scalable analytical tool that accelerates credit risk assessment and corporate evaluation.