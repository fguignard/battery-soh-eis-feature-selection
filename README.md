# Battery State-of-Health Estimation from a Minimal Set of Electrochemical Impedance Measurements

## Overview

This repository contains the code used to produce the results presented in the accompanying article:

> Battery State-of-Health Estimation from a Minimal Set of Electrochemical Impedance at Three Frequencies

The objective of this work is to investigate whether lithium-ion battery state-of-health (SOH) can be accurately estimated from a strongly reduced set of electrochemical impedance spectroscopy (EIS) measurements using machine learning. The analysis shows that predictive performance can be maintained using impedance measurements at only three frequencies across several regression models.

This repository is intended to promote reproducible research by providing the complete analysis pipeline used to generate the results reported in the manuscript.

⸻

## Repository contents

The code implements the complete workflow described in the paper, including:

* data loading and preprocessing;
* principal component analysis (PCA);
* implementation of the machine learning models;
* nested group cross-validation for model selection and performance evaluation;
* domain-guided frequency selection and progressive reduction of the EIS feature space;
* generation of the figures presented in the manuscript.

⸻

## Python dependencies

The analyses were performed in Python using standard scientific computing libraries, including:

* NumPy
* pandas
* SciPy
* scikit-learn
* matplotlib

⸻

## Citation

If you use this code in your research, please cite the accompanying article.
