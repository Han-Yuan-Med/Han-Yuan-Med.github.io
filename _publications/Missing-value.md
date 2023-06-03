---
title: "Handling missing values in healthcare data: A systematic review of deep learning-based imputation techniques"
collection: publications
permalink: /publication/Missing-value
excerpt: ''
date: 2023-06-02
venue: 'Artificial Intelligence in Medicine'
paperurl: 'http://han-yuan-med.github.io/files/Handling missing values in healthcare data A systematic review of deep learning-based imputation techniques.pdf'
---
Objective
The proper handling of missing values is critical to delivering reliable estimates and decisions, especially in high-stakes fields such as clinical research. In response to the increasing diversity and complexity of data, many researchers have developed deep learning (DL)-based imputation techniques. We conducted a systematic review to evaluate the use of these techniques, with a particular focus on the types of data, intending to assist healthcare researchers from various disciplines in dealing with missing data.

Materials and methods
We searched five databases (MEDLINE, Web of Science, Embase, CINAHL, and Scopus) for articles published prior to February 8, 2023 that described the use of DL-based models for imputation. We examined selected articles from four perspectives: data types, model backbones (i.e., main architectures), imputation strategies, and comparisons with non-DL-based methods. Based on data types, we created an evidence map to illustrate the adoption of DL models.

Results
Out of 1822 articles, a total of 111 were included, of which tabular static data (29 %, 32/111) and temporal data (40 %, 44/111) were the most frequently investigated. Our findings revealed a discernible pattern in the choice of model backbones and data types, for example, the dominance of autoencoder and recurrent neural networks for tabular temporal data. The discrepancy in imputation strategy usage among data types was also observed. The “integrated” imputation strategy, which solves the imputation task simultaneously with downstream tasks, was most popular for tabular temporal data (52 %, 23/44) and multi-modal data (56 %, 5/9). Moreover, DL-based imputation methods yielded a higher level of imputation accuracy than non-DL methods in most studies.

Conclusion
The DL-based imputation models are a family of techniques, with diverse network structures. Their designation in healthcare is usually tailored to data types with different characteristics. Although DL-based imputation models may not be superior to conventional approaches across all datasets, it is highly possible for them to achieve satisfactory results for a particular data type or dataset. There are, however, still issues with regard to portability, interpretability, and fairness associated with current DL-based imputation models. 

Download [here](http://han-yuan-med.github.io/files/Handling missing values in healthcare data A systematic review of deep learning-based imputation techniques.pdf)