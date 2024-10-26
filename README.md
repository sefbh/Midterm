Analyzing Bias in Healthcare Predictive Models

Overview

This repository contains an in-depth analysis titled "Addressing Bias in Healthcare Algorithms: A Fairness Analysis of Predictive Models." The essay explores the topic of 
algorithmic fairness in healthcare. The work centers around a study by Obermeyer et al., which demonstrates the impact of bias in an algorithm used to prioritize healthcare resources. 
The paper includes a discussion on statistical fairness metrics and normative considerations discussed in STOR 390.

Introduction
Predictive models are essential tools in modern healthcare systems, helping allocate resources and guide treatment decisions. However, if these models are biased, they can 
worsen healthcare inequalities. 

Essay Structure

Introduction: Discusses the growing use of algorithms in healthcare and the potential for these models to introduce bias, framing the significance of fairness in healthcare technology.

Methodology: Describes the study design by Obermeyer et al., including data sources, selected variables, and the rationale for using prior healthcare expenditures as a proxy.

Statistical Fairness Measures: Explains the fairness metrics applied in the study, such as statistical parity, equalized odds, and disparate impact, and how they quantify disparities in 
resource allocation.

Ethical and Normative Implications: Reflects on the ethical consequences of biased healthcare models and the moral imperative of ensuring fair algorithmic outcomes.

Policy Recommendations: Suggests actions for policymakers, such as mandatory fairness audits and transparency requirements, to promote accountability in algorithmic healthcare models.

Methodology
The study by Obermeyer et al. analyzed a large U.S. hospital dataset, employing fairness metrics to evaluate a healthcare algorithm’s risk assessments across racial groups. By examining 
disparities in the model’s false negative rates and assessing statistical parity, the study revealed how cost-based proxies inadvertently disadvantaged Black patients with similar health 
needs to White patients.
Statistical Fairness Measures
Several fairness metrics were applied to measure algorithmic bias, including:
Statistical Parity: Ensures that each demographic group has an equal probability of a favorable outcome.
Equalized Odds: Examines whether error rates (false positives and negatives) are evenly distributed across groups.
Disparate Impact: Quantifies the probability disparity for favorable outcomes across different demographics, using risk ratios.
The findings demonstrated quantifiable disparities, indicating that fairness measures are essential for identifying biases in healthcare algorithms.

Ethical and Normative Implications
The essay discusses the ethical urgency of addressing algorithmic bias in healthcare, emphasizing that these tools should not reinforce existing inequalities. The study’s results 
highlight the importance of aligning predictive models with ethical principles to ensure equal access to care.

Policy Recommendations
To prevent bias in healthcare algorithms, the essay recommends policy interventions, such as:

Fairness Audits: Regular audits to assess and report bias in predictive models.
Transparency Requirements: Making algorithms more explainable and accessible for scrutiny.
Variable Selection Guidelines: Using clinically relevant metrics over socioeconomic proxies.
