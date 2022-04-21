---
title: "#8 AutoScore-Imbalance: An interpretable machine learning tool for development of clinical scores with rare events data"
collection: publications
permalink: /publication/AutoScore-Imbalance
excerpt: ''
date: 2022-04-11
venue: 'Journal of Biomedical Informatics'
paperurl: 'http://han-yuan-med.github.io/files/AutoScore-Imbalance.pdf'
---
Background
Medical decision-making impacts both individual and public health. Clinical scores are commonly used among various decision-making models to determine the degree of disease deterioration at the bedside. AutoScore was proposed as a useful clinical score generator based on machine learning and a generalized linear model. However, its current framework still leaves room for improvement when addressing unbalanced data of rare events.

Methods
Using machine intelligence approaches, we developed AutoScore-Imbalance, which comprises three components: training dataset optimization, sample weight optimization, and adjusted AutoScore. Baseline techniques for performance comparison included the original AutoScore, full logistic regression, stepwise logistic regression, least absolute shrinkage and selection operator (LASSO), full random forest, and random forest with a reduced number of variables. These models were evaluated based on their area under the curve (AUC) in the receiver operating characteristic analysis and balanced accuracy (i.e., mean value of sensitivity and specificity). By utilizing a publicly accessible dataset from Beth Israel Deaconess Medical Center, we assessed the proposed model and baseline approaches to predict inpatient mortality.

Results
AutoScore-Imbalance outperformed baselines in terms of AUC and balanced accuracy. The nine-variable AutoScore-Imbalance sub-model achieved the highest AUC of 0.786 (0.732–0.839), while the eleven-variable original AutoScore obtained an AUC of 0.723 (0.663–0.783), and the logistic regression with 21 variables obtained an AUC of 0.743 (0.685–0.801). The AutoScore-Imbalance sub-model (using a down-sampling algorithm) yielded an AUC of 0.771 (0.718–0.823) with only five variables, demonstrating a good balance between performance and variable sparsity. Furthermore, AutoScore-Imbalance obtained the highest balanced accuracy of 0.757 (0.702–0.805), compared to 0.698 (0.643–0.753) by the original AutoScore and the maximum of 0.720 (0.664–0.769) by other baseline models.

Conclusions
We have developed an interpretable tool to handle clinical data imbalance, presented its structure, and demonstrated its superiority over baselines. The AutoScore-Imbalance tool can be applied to highly unbalanced datasets to gain further insight into rare medical events and facilitate real-world clinical decision-making.

[Download paper here](http://han-yuan-med.github.io/files/AutoScore-Imbalance.pdf)