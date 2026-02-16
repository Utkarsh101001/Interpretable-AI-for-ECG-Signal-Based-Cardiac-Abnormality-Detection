# Interpretable-AI-for-ECG-Signal-Based-Cardiac-Abnormality-Detection
This is a personal project focused on developing an interpretable and lightweight AI model for ECG signal-based cardiac abnormality detection. The goal is to design a lightweight and transparent Decision Tree classifier that can identify heart abnormalities from ECG signals while maintaining clinical interpretability.

## Overview
Adoption of AI in the healthcare industry has increased significantly in the past decade. There has been extensive research on the use of AI in medical diagnosis, with thousands of models and publications demonstrating promising diagnostic accuracy across imaging and clinical decision support. However, despite substantial progress in AI methodology, real-world clinical adoption of AI in heathcare remains uneven. While adoption is growing in some domains, such as imaging, it is still limited in first-line primary healthcare settings. 

Several challenges contribute to this gap between research and practice, from data privacy risks, algorithmic bias leading to health disparities, lack of integration with existing clinical workflows to regulatory compliance, high implementation costs, and lack of transparency assosiated with "black box" nature of AI. In primary healthcare settings, where clinical decisions must be clearly explained to patients and caregivers, model interpretability is particularly critical. 

Unlike opaque AI systems with obscure internal logic, interpretable AI systems allow clinicians to understand and validate algorithmic decisions, and help prevent automation bias by challenging algorithmic conclusions when needed, thereby improving clinical acceptance and safe deployment. 

Interpretable AI methods can be broadly classified into intrinsic interpretebility, where transparency is an inherent propery of the model architecture, and post-hoc interpretebility, where different explanation techniques are applied to complex models without sacrificing predictive accuracy or altering their structure. In this project, we focus on intrinsic interpretability through the use of Decision Trees.

The objective of this project is to develop an AI-based cardiac abnormality detection system from short-duration ECG recordings using Decision Trees, which are inherently lightweight and interpretable. The project focuses on two primary objectives:

&nbsp;&nbsp;&nbsp;&nbsp;T**1. Computational Efficiency and Lightweight Design**:
&nbsp;&nbsp;&nbsp;&nbsp;TThe model should achieve satisfactory diagnostic performance while maintaining low computational requirements. Models with lightweight design uses fewer rules when making decison. They are not only more interpretable than their complex counterparts, but also require less computational resources, significantly reducing the cost of AI adoption.
&nbsp;&nbsp;&nbsp;&nbsp;T**2. Interpretability**:
&nbsp;&nbsp;&nbsp;&nbsp;TThe decision-making process of the model should be transparent and easily understandable to primary care physicians, who serve as the first point of contact in identifying potential cardiac abnormalities and referring patients to specialists.

Since any medical screening prioritizes minimizing false negatives, model performance will be evaluated primarily using Sensitivity. We will systematically study the trade-off between model performance and interpretability by constraining structural parameters such as maximum tree depth and number of nodes. The goal is to identify the minimum model complexity that achieves clinically acceptable Sensitivity while preserving interpretability and computational simplicity.

## Objectives

### Primary Objective
Study the trade-off between the model’s performance and its interpretability while limiting Decision Tree depth to preserve clinical interpretability.

### Secondary Objectives
- Analyze how Sensitivity changes as tree depth increases.
- Analyze additional performance metrics (e.g., Specificity, F1-score) to quantify overall performance of the model.
- Identify the minimum tree depth, number of nodes, and other structural parameters that achieve clinically acceptable Sensitivity.

