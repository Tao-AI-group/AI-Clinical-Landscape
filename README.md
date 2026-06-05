# Evaluating AI in Clinical Practice: A Systematic Landscape Analysis

This repository contains the data, scripts, and figures for the systematic landscape analysis of AI-related clinical trials registered on ClinicalTrials.gov. 

## Project Overview

Artificial intelligence is rapidly reshaping clinical evidence generation, but public registries often lack the structured metadata required to distinguish AI evaluated as a direct medical intervention (AI comparative clinical trials) from AI used merely to facilitate backend research operations. 

This study characterizes the functional roles, data modalities, and clinical applications of AI within registered clinical trials. Using an automated large language model pipeline (GPT-4o) and semantic standardization (SapBERT and PheCode mapping), the analysis categorizes trials to map the current state of clinical AI validation.

## Repository Structure

* **Data/**: Datasets containing the clinical trial records and associated extracted metadata.
* **Script/**: Code and scripts used for the automated LLM annotation pipeline, semantic standardization of medical conditions, and statistical analysis.
* **Figure/**: Visualizations and plots generated from the analysis (e.g., Sankey diagrams of modality-application pipelines, bar charts of trial characteristics).

## Key Findings

- **Growth**: AI comparative clinical trials maintained sustained double-digit growth even while overall clinical trials stagnated post-2020.
- **Data Modalities**: Visual data (image and video) strongly dominates the landscape, predominantly fueling Clinical Decision Support Systems (CDSS).
- **Disease Focus**: Current applications often target single-modality diagnostic silos (like colon polyps and diabetic retinopathy). Complex systemic diseases and multimodal behavioral applications remain underrepresented.
- **Sponsorship**: The landscape is heavily skewed toward academic/non-profit sponsors (86.5% of comparative trials) and is geographically concentrated in the USA and China.
