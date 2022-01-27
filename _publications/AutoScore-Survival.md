---
title: "#5 AutoScore-Survival: Developing interpretable machine learning-based time-to-event scores with right-censored survival data"
collection: publications
permalink: /publication/AutoScore-Survival
excerpt: ''
date: 2021-11-23
venue: 'Journal of Biomedical Informatics'
paperurl: 'http://yuan-han-ai.github.io/files/AutoScore-Survival Developing interpretable machine learning-based time-to-event scores with right-censored survival data.pdf'
---
Background
Scoring systems are highly interpretable and widely used to evaluate time-to-event outcomes in healthcare research. However, existing time-to-event scores are predominantly created ad-hoc using a few manually selected variables based on clinician's knowledge, suggesting an unmet need for a robust and efficient generic score-generating method.

Methods
AutoScore was previously developed as an interpretable machine learning score generator, integrating both machine learning and point-based scores in the strong discriminability and accessibility. We have further extended it to the time-to-event outcomes and developed AutoScore-Survival, for generating time-to-event scores with right-censored survival data. Random survival forest provided an efficient solution for selecting variables, and Cox regression was used for score weighting. We implemented our proposed method as an R package. We illustrated our method in a study of 90-day survival prediction for patients in intensive care units and compared its performance with other survival models, the random survival forest, and two traditional clinical scores.

Results
The AutoScore-Survival-derived scoring system was more parsimonious than survival models built using traditional variable selection methods (e.g., penalized likelihood approach and stepwise variable selection), and its performance was comparable to survival models using the same set of variables. Although AutoScore-Survival achieved a comparable integrated area under the curve of 0.782 (95% CI: 0.767–0.794), the integer-valued time-to-event scores generated are favorable in clinical applications because they are easier to compute and interpret.

Conclusions
Our proposed AutoScore-Survival provides a robust and easy-to-use machine learning-based clinical score generator to studies of time-to-event outcomes. It gives a systematic guideline to facilitate the future development of time-to-event scores for clinical applications.

[Download paper here](http://yuan-han-ai.github.io/files/AutoScore-Survival Developing interpretable machine learning-based time-to-event scores with right-censored survival data.pdf)