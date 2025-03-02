# Uplift Modelling

[![CodeFactor](https://www.codefactor.io/repository/github/lunayht/uplift-modelling/badge)](https://www.codefactor.io/repository/github/lunayht/uplift-modelling) [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

This repository contains the code for various uplift modelling algorithms, including:

- S-learner
- T-learner
- Simplified X-learner
- X-learner

## What is uplift modelling?

Uplift modelling is a causal inference technique that predicts the incremental impact of a treatment on an individual's behaviour, which allows businesses to target only those customers who are likely to respond positively to a treatment. This can be used to improve the effectiveness of marketing campaigns, reduce costs, and increase revenue.

## Difference between revenue uplift and churn uplift

By definition, there will be four possible outcomes based on a response to a treatment:

1. Persuadable
2. Sure Thing
3. Lost Cause
4. Do Not Disturb

In practice, the actual definition of these outcomes may vary depending on the hypothesis. When predicting uplift score and selecting a segment by the highest score, we are trying to find the only one type of customer: persuadable in revenue uplift or do not disturb in churn uplift.

## Acknowledgements

1. [Causal Infernce for the Brave and True](https://matheusfacure.github.io/python-causality-handbook/landing-page.html)
2. [Sklift](https://www.uplift-modeling.com/en/latest/user_guide/introduction/index.html)
3. [CausalML](https://causalml.readthedocs.io/en/latest/about.html)
4. [Simplified X-Learner](https://medium.com/@rndonnelly/a-simpler-alternative-to-x-learner-for-uplift-modeling-f3a11ebf6bf1#:~:text=%5B%3A%2C%201%5D-,Simplified%20X%2Dlearner%20(Xs%2Dlearner),using%20only%20the%20untreated%20observations.)
