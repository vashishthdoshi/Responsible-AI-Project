# AI Fairness & Responsible Policy Frameworks

## Overview
This repository contains research and policy proposals focused on two critical areas of artificial intelligence: assessing racial bias in predictive justice algorithms (similar to COMPAS) and designing actionable policy guardrails for ethical, sustainable AI adoption. 

---

## Project 1: AI Fairness in the Criminal Justice System

### Objective
To analyze synthetic data from three counties - Copiah, Claiborne, and Warren - to determine if AI-based risk assessment tools exhibit bias when aiding judges in bail decisions.

### Key Findings
* **Disparate Risk Scoring:** The AI algorithm assigned systematically higher risk scores to the Black population (average 5.86) compared to the White population (average 4.73), a difference of over a full point.
* **Unequal Bail Thresholds:** Across all analyzed counties, judges began denying bail to Black individuals at a risk score of 4, whereas White individuals were generally granted bail up to a risk score of 6. 
* **Skewed False Negative Rates (FNR):** The FNR for Black individuals was disproportionately high (over 50% higher than White individuals), meaning the model frequently categorized them as high risk even when they did not re-offend, leading to unfair jailing.
* **Skewed False Positive Rates (FPR):** The FPR for White individuals was extremely high, indicating that they were often mistakenly granted bail despite going on to re-offend.
* **Failure of Fairness Metrics:** The AI model completely failed to meet the standards for both statistical parity and equal opportunity across all three counties.

---

## Project 2: Ethical and Environmental Guardrails for AI Adoption

### Objective
To propose structured policy frameworks that balance rapid AI innovation with humanistic values, worker protection, and environmental sustainability.

### The Challenges
* **Environmental Strain:** Training advanced AI models requires immense computational power, which has been doubling roughly every 3.4 months since the early 2010s. The necessary data centers rely on carbon-intensive materials and consume massive amounts of water for cooling; for example, data center water usage in Virginia surged from 1.13 billion gallons in 2019 to 1.85 billion in 2023.
* **Socioeconomic Risk:** Unchecked AI acceleration risks massive job displacement, with the IMF warning that up to 40% of global jobs could be impacted. 

### Proposed Policy Initiatives
* **Short-Term - Certification for Research Funding:** A governance policy requiring companies to demonstrate ethical practices and operational transparency to qualify for research funds. Crucially, companies must prove they are addressing workforce displacement by investing in job retraining initiatives.
* **Short-Term - Academia-Industry Policy Initiative:** A collaborative forum uniting subject matter experts, academia, and policymakers to develop evidence-based AI guidelines addressing bias, transparency, and accountability.
* **Long-Term - Audit.AI:** A comprehensive auditing system expanding upon traditional ESG (Environmental, Social, and Governance) frameworks. This requires standardizing evaluations of a company's carbon footprint and energy usage, alongside "checks on the individual" to measure the economic impact and inclusivity benefits for employees navigating an AI-enabled workplace.

---

## Contributors
* Ashwin Kandath
* Vashishth Doshi
* Katelyn Wilson
* Satish Kumar Patchipulusu
* Junke Zhao
