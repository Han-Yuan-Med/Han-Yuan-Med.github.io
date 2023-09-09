---
title: "FedScore: A Privacy-Preserving Framework for Federated Scoring System Development"
collection: publications
permalink: /publication/FedScore
excerpt: ''
date: 2023-09-01
venue: 'Journal of Biomedical Informatics'
paperurl: 'http://han-yuan-med.github.io/files/FedScore A Privacy-Preserving Framework for Federated Scoring System Development.pdf'
---
Objective
We propose FedScore, a privacy-preserving federated learning framework for scoring system generation across multiple sites to facilitate cross-institutional collaborations.

Materials and Methods
The FedScore framework includes five modules: federated variable ranking, federated variable transformation, federated score derivation, federated model selection and federated model evaluation. To illustrate usage and assess FedScore’s performance, we built a hypothetical global scoring system for mortality prediction within 30 days after a visit to an emergency department using 10 simulated sites divided from a tertiary hospital in Singapore. We employed a pre-existing score generator to construct 10 local scoring systems independently at each site and we also developed a scoring system using centralized data for comparison.

Results
We compared the acquired FedScore model’s performance with that of other scoring models using the receiver operating characteristic (ROC) analysis. The FedScore model achieved an average area under the curve (AUC) value of 0.763 across all sites, with a standard deviation (SD) of 0.020. We also calculated the average AUC values and SDs for each local model, and the FedScore model showed promising accuracy and stability with a high average AUC value which was closest to the one of the pooled model and SD which was lower than that of most local models.

Conclusion
This study demonstrates that FedScore is a privacy-preserving scoring system generator with potentially good generalizability.

Download [here](http://han-yuan-med.github.io/files/FedScore A Privacy-Preserving Framework for Federated Scoring System Development.pdf)