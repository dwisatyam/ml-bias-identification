# ml-bias-identification
This repository has bias lexicons, corpus and scripts to generate augmented test-sets based on the original test data to evaluate the counter-factual fairness of NU models.

## Repo structure
```
├───bin
│   ├───notebooks
│   ├───templates
│   │   ├───beauty
│   │   ├───color
│   │   ├───disablity
│   │   ├───education
│   │   ├───gender
│   │   ├───height
│   │   ├───marital-status
│   │   ├───nationality
│   │   ├───occupation
│   │   ├───race
│   │   ├───religion
│   │   ├───sexual-identity
│   │   └───socio-economic-status
│   └───test_sets
│       ├───beauty
│       │   └───individual
│       ├───color
│       │   └───individual
│       ├───disablity
│       │   └───individual
│       ├───education
│       │   └───individual
│       ├───gender
│       │   └───individual
│       ├───height
│       │   └───individual
│       ├───marital-status
│       │   └───individual
│       ├───nationality
│       │   └───individual
│       ├───occupation
│       │   └───individual
│       ├───race
│       │   └───individual
│       ├───religion
│       │   └───individual
│       ├───sexual-identity
│       │   └───individual
│       └───socio-economic-status
│           └───individual
├───experiments
│   ├───plots
│   │   ├───classification_gap
│   │   │   ├───group_fairness
│   │   │   └───individual_fairness
│   │   └───classification_tolerance
│   │       ├───group_fairness
│   │       └───individual_fairness
│   └───results
│       └───classification_tolerance
│           ├───group_fairness
│           └───individual_fairness
└───src
    └───resources
        ├───corpus
        └───lexicons
```
## References
Below is an exhaustive list of the resources that I used to create/curate corpus and bias lexicons.

### Corpus
- Corpus	[Corpus of Contemporary American English](https://www.english-corpora.org/coca/)

### Lexicons
Self curated
