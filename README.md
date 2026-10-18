# AI Governance Portfolio

This repository contains applied AI governance artifacts demonstrating end-to-end implementation of global AI frameworks (NIST, EU AI Act). 

These artifacts are designed for enterprise AI review boards, regulatory compliance, and operational risk management.

---

## 📂 Artifact 1: NIST AI RMF Risk Assessment (FraudShield AI)
**Framework:** NIST AI Risk Management Framework (AI RMF 1.0)  
**Domain:** Fintech / Fraud Detection with LLM explanations

A complete risk register and executive analysis mapping 15 AI risks across the four core RMF functions (Govern, Map, Measure, Manage). 
*   **Deliverables:** Risk scoring model (Impact × Likelihood), heat map, category/level visualizations, and a decision-ready executive summary.
*   **Key Finding:** 60% of risks classified as Critical, indicating systemic governance gaps requiring deployment pause and remediation.
*   **Files:** 
    *   `NIST_AI_RMF_Risk_Assessment_FraudShield.html` (Interactive Notebook)
    *   `NIST_AI_RMF_Memo_FraudShield.pdf` (Executive Memo)

---

## 📂 Artifact 2: AI Transparency Documentation & EU AI Act Crosswalk (FeedbackIQ)
**Framework:** EU AI Act (Article 11 / Annex IV) & MITRE ATLAS  
**Domain:** B2B SaaS / Multilingual Sentiment Analysis

A comprehensive transparency stack for a high-risk AI system launch into the EU market. This artifact demonstrates the ability to translate regulatory requirements into concrete documentation.
*   **Model Card:** Detailed metrics (subgroup accuracy by language/segment), MITRE ATLAS threat modeling (evasion, prompt injection), and known limitations (sarcasm, OOD languages).
*   **Article 11 Crosswalk:** Maps Model Card sections directly to Annex IV statutory requirements, explicitly naming sister artifacts (Datasheet, System Card, Impact Assessment) for partial coverages.
*   **Gap Log:** A formal remediation plan assigning ownership and target dates for outstanding compliance requirements.
*   **File:** 
    *   `FeedbackIQ_EU_AI_Act_Model_Card_and_Crosswalk.xlsx`

---

## 📂 Artifact 3: EU AI Act Risk Classifier & Compliance Plan (TalentScope AI)
**Framework:** EU AI Act (Regulation (EU) 2024/1689)  
**Domain:** HR Tech / GenAI Recruitment Screening (High-Risk)

An end-to-end compliance engine that translates the EU AI Act into executable Python logic and a project management remediation plan.

*   **Python Risk Classifier:** A rule-based engine that evaluates AI system characteristics (sector, biometrics, foundation model status) to automatically assign risk tiers (Unacceptable, High-Risk, GPAI, Limited, Minimal) and output applicable Articles and required actions.
*   **Enterprise Compliance Plan:** A 13-point remediation matrix for a High-Risk AI system, mapping legal requirements (Articles 9-15, 43, 49, 72, 73) to technical controls, identifying gaps (e.g., an 8% gender disparity), and assigning owners and deadlines to achieve conformity.
*   **Files:** 
    *   `EU_AI_Act_Risk_Classifier.html` (Interactive Notebook)
    *   `TalentScope_EU_AI_Act_Compliance_Plan.xlsx` (Compliance Matrix)
---
*Author: Muhammad Safyan, PhD | Associate Professor of AI | AI Governance & Risk Management*
