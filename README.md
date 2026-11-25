# Bias and Mitigation in AI-Based Hiring Systems
This is an ongoing independent research project for PSTAT 199 at the University of California, Santa Barbara.

## Project Overview
This project builds on my systematic review of bias and mitigation in AI-based hiring systems. The main goal is to replicate the resume-screening audit study conducted by Wilson and Caliskan (2024), focusing on demographic bias in gender, racial, and intersectional disparities in resume retrieval by Massive Text Embedding (MTE) models.

A second study from the systematic review will be selected, and a brief discussion of methodology will be included in the final report. If it is feasible, additional analyses will be included.

## Current Progress
The current uploaded report is a working draft that covers
- The research question and design of the original study
- Dataset description of the original study and preprocessing procedures.
- The mathematical architecture of the three MTE models, including tokenization, attention, pooling, normalization, cosine similarity, and ranking.

Based on the original dataset, an example has been created using two resumes and one job description. This example is presented in the form of handwritten notes and has been organized to incorporate the mathematical derivations into the report. Instead of using actual model outputs, this example uses simplified numerical values to illustrate the calculation process.

Replication experiments and the results are not yet included in the report.

## File
[The current working draft of the research report](PSTAT_199_Bias_and_Mitigation_Replication_Lillian_Xue.pdf)

## Original Study
Wilson, K., and Caliskan, A. (2024).
"Gender, Race, and Intersectional Bias in Resume Screening via Language Model Retrieval."
Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society, 7, 1578-1590.

Original code:
https://github.com/kyrawilson/Resume-Screening-Bias
