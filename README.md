# MetaPred: Prediction of Cytochrome P450 Isoform Responsible for Metabolizing a Drug Molecule

## Overview

MetaPred is a computational platform developed for predicting the cytochrome P450 (CYP450) isoform responsible for metabolizing a drug molecule.

The study focused on five major CYP isoforms:

- CYP3A4
- CYP2D6
- CYP1A2
- CYP2C9
- CYP2C19

These isoforms metabolize most therapeutic drugs in humans.

---

## Research Article

**Title:** Prediction of cytochrome P450 isoform responsible for metabolizing a drug molecule

**Authors:** Nitish K Mishra, Sandhya Agarwal, and Gajendra P. S. Raghava

**Journal:** BMC Pharmacology (2010)

**DOI:** https://doi.org/10.1186/1471-2210-10-8

---

## Background

Cytochrome P450 enzymes are involved in drug metabolism and biotransformation.

Predicting the CYP isoform responsible for metabolizing a drug is important for:

- ADMET analysis
- Drug discovery
- Toxicity studies
- Drug-drug interaction analysis
- Pharmacokinetic profiling

---

## Dataset

### Main Dataset

- Total molecules: 216
- CYP3A4 substrates: 111
- CYP2D6 substrates: 47
- CYP1A2 substrates: 29
- CYP2C9 substrates: 20
- CYP2C19 substrates: 19

### Independent Dataset

- Total molecules: 146

---

## Descriptor Calculation

The study used:

- TSAR
- ADMEWORKS
- Chemistry Development Kit (CDK)

A total of 2392 molecular descriptors were initially calculated.

After feature selection, 41 descriptors were used for SVM model development.

---

## Machine Learning Methods

The following algorithms were tested:

- Support Vector Machine (SVM)
- Random Forest
- BayesNet
- Logistic Regression
- Multilayer Perceptron

SVM models achieved the best performance.

---

## Model Performance

| Isoform | Accuracy (%) | MCC |
|----------|---------------|-----|
| CYP3A4 | 81.42 | 0.63 |
| CYP2D6 | 81.24 | 0.54 |
| CYP1A2 | 83.19 | 0.49 |
| CYP2C9 | 84.51 | 0.40 |
| CYP2C19 | 70.80 | 0.15 |

### Overall Performance

- Average Accuracy: 86.02%
- Overall Accuracy: 82.81%

---

## Web Server

MetaPred Web Server:

http://crdd.osdd.net/raghava/metapred/

Supported inputs:

- MOL2
- SDF
- SMILES
- JME molecular editor

---

## Applications

MetaPred can be used for:

- Drug metabolism prediction
- Virtual screening
- ADMET analysis
- Drug discovery
- Medicinal chemistry research

---

## Technologies Used

- Linux
- WEKA
- SVM_light
- CDK descriptors
- CGI-Perl

---

## Citation

Mishra NK, Agarwal S, Raghava GPS. Prediction of cytochrome P450 isoform responsible for metabolizing a drug molecule. BMC Pharmacology. 2010;10:8.

---

## Contact

Prof. Gajendra P. S. Raghava  
Institute of Microbial Technology  
Chandigarh, India

Email: raghava@iiitd.ac.in

---

Generated from the uploaded MetaPred paper.
