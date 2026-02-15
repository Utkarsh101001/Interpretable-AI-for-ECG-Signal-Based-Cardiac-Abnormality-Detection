# Interpretable-AI-for-ECG-Signal-Based-Cardiac-Abnormality-Detection
This is a personal project focused on developing an interpretable and lightweight AI model for ECG signal-based cardiac abnormality detection. The goal is to design a lightweight and transparent Decision Tree classifier that can identify heart abnormalities from ECG signals while maintaining clinical interpretability.

## Overview
This project investigates the use of an interpretable Decision Tree classifier for detecting cardiac abnormalities from ECG signals.

The primary focus is to balance diagnostic performance with clinical transparency. By constraining the maximum depth of the Decision Tree, the model remains fully explainable, allowing each prediction to be represented as a clear and traceable set of decision rules.

This prototype aims to systematically analyze how limiting model complexity affects diagnostic performance.

Motivation

In cardiac abnormality detection, missing a diseased case (False Negative) can have serious or life-threatening consequences. Therefore, Sensitivity (True Positive Rate) is treated as the primary performance metric in this project.

Although deeper or more complex models may improve overall accuracy, they reduce interpretability and clinical trust. In healthcare applications, transparency is critical for:

Clinical validation

Trustworthy deployment

Alignment with established physiological knowledge

This project explores whether high Sensitivity can be maintained while enforcing strict interpretability constraints through shallow Decision Trees.

Objectives
🎯 Primary Objective

Maximize Sensitivity in detecting cardiac abnormalities while limiting Decision Tree depth to preserve full clinical interpretability.

📌 Secondary Objectives

Analyze how Sensitivity changes as tree depth increases.

Study the trade-off between predictive performance and interpretability.

Identify the minimum tree depth that achieves clinically acceptable Sensitivity.

Evaluate additional performance metrics (Specificity, F1-score) as secondary measures.

If you later decide to convert this into a thesis-oriented repository, we can expand this into:

Methodology

Experimental Design

Dataset Description

Results & Analysis

Future Work

For now, this version is clean, focused, and appropriate for sharing an early prototype with a prospective PhD supervisor.
