# Interpretable-AI-for-ECG-Signal-Based-Cardiac-Abnormality-Detection
This is a personal project focused on developing an interpretable and lightweight AI model for ECG signal-based cardiac abnormality detection. The goal is to design a lightweight and transparent Decision Tree classifier that can identify heart abnormalities from ECG signals while maintaining clinical interpretability.

## Overview
Adoption of AI in the healthcare industry has increased significantly in the past decade. There has been extensive research on the use of AI in medical diagnosis, with thousands of models and publications demonstrating promising diagnostic accuracy across imaging and clinical decision support.

Despite academic progress, real-world clinical adoption remains uneven. While adoption is growing in some domains, especially imaging, it is still moderate in many settings especially primary heathcare, and in some low-resource environments, it remains limited. This is not surprising, given what is at stake. Clinical diagnosis directly affects patient outcomes, and doctors are understandably cautious about relying on tools they do not fully understand, especially in high-risk situations. This is why there is a need for lightweight and interpretable AI models that are not only deployable in low-resource settings but also easily interpretable by medical professionals. 

The aim of this project is to develop an AI-based cardiac abnormality detector using Decision Trees, which are inherently lightweight and interpretable. This project will focus on two things: first, lightweightness and edge deployement, the model should be able to give satisfactory results with resource-constrained devices, primarily in portable ECG tests that are no longer than a few minutes. Second, interpretability, the model's decision-making should be easily understood by the primary users, that is, the primary physicians who are first to identify any problem with a patient and refer them to a specialist.

We will focus on the trade-off between the model’s performance (primarily Sensitivity) and its interpretability by constraining the maximum depth of the tree. We will also try to identify the minimum tree depth, number of nodes, and other structural parameters that achieve clinically acceptable Sensitivity.

## Objectives

### Primary Objective
Study the trade-off between the model’s performance and its interpretability while limiting Decision Tree depth to preserve clinical interpretability.

### Secondary Objectives
- Analyze how Sensitivity changes as tree depth increases.
- Analyze additional performance metrics (e.g., Specificity, F1-score) to quantify overall performance of the model.
- Identify the minimum tree depth, number of nodes, and other structural parameters that achieve clinically acceptable Sensitivity.

