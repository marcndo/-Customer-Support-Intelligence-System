# Customer-Support-Intelligence-System

## Marcel Ambo Ndowah — Junior to Mid-Level Machine Learning Engineer

This repository contains an applied Customer Support Intelligence System designed to support real customer service workflows such as ticket categorization, prioritization, and insight extraction.

The purpose of this project is to demonstrate how I approach machine learning work end to end: from problem framing and data handling to modeling, evaluation, and documentation. Reviewers should assess this repository as they would an internal ML project prepared for collaboration and iteration.

## About

I am targeting a Machine Learning Engineer role, focused on applied ML systems that operate on real, imperfect data.

My work reflects the following principles:

* Start from operational problems, not algorithms

* Prefer simple, inspectable baselines before complexity

* Separate analysis, production code, and documentation clearly

* Document assumptions, risks, and limitations explicitly

The goal is not to showcase advanced theory, but to demonstrate sound engineering judgment and structured thinking.

## Portfolio Overview
This repository is organized to mirror how ML systems are developed and reviewed in production environments.

At a high level, it contains:

* Clear problem and system documentation

* Reproducible data and modeling pipelines

* Inspectable analysis and evaluation outputs

* Scripts that reflect real training and inference workflows

Each section is intentionally scoped and documented to support review, debugging, and extension.

## Core Work Artefacts
```
├── README.md
├── pyproject.toml
├── requirements.txt
├── docs/
│   ├── problem_statement.md
│   ├── system_overview.md
│   ├── assumptions_and_risks.md
│   └── evaluation_criteria.md
├── data/
│   ├── raw/
│   ├── interim/
│   ├── processed/
│   └── data_validation.md
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_label_analysis.ipynb
│   └── 03_error_analysis.ipynb
├── src/
│   └── support_intelligence/
│       ├── ingestion/
│       ├── preprocessing/
│       ├── features/
│       ├── models/
│       └── evaluation/
├── scripts/
│   ├── train.py
│   ├── evaluate.py
│   └── predict.py
├── reports/
│   ├── model_performance.md
│   └── support_insights.md
└── tests/
    ├── test_preprocessing.py
    ├── test_features.py
    └── test_models.py
```
## How to Read This Repository

Reviewers can follow this path:
1. Start with the problem context
  * docs/problem_statement.md

2. Understand the system design
  * docs/system_overview.md

3. Inspect data and modeling logic
  * src/support_intelligence/
  * scripts/

4. Review evaluation and outcomes

  * reports/model_performance.md

Core Work Artefacts
Documentation (docs/)

Contains design reasoning, assumptions, risks, and evaluation criteria. These documents capture why decisions were made and define how success is measured.

Source Code (src/)

Implements data ingestion, preprocessing, feature construction, modeling, and evaluation as a structured Python package. This layout supports testing, reuse, and maintainability.

Notebooks (notebooks/)

Used only for exploratory analysis and error inspection. No production logic lives in notebooks.

Scripts (scripts/)

Provide entry points for training, evaluation, and inference. These reflect how the system would be run in practice.

Reports (reports/)

Summarize results, failure modes, and operational insights derived from the system.

Issue Handling and Evaluation Approach

Customer support data is noisy and ambiguous. Issues such as label inconsistency, class imbalance, and unclear tickets are expected.

I handle these by:

Documenting data quality findings explicitly

Performing targeted error analysis

Evaluating impact based on support workflow consequences

Communicating limitations in plain language

This supports informed decisions about system readiness and next steps.

Tools and Skills Used
Skills Demonstrated

Translating business workflows into ML tasks

Text data preprocessing and feature design

Supervised classification

Model evaluation and error analysis

Reproducible ML system structuring

Tools Used

Python — implementation language

NumPy / pandas — data handling

scikit-learn — modeling and metrics

Jupyter Notebook — exploratory analysis

Git — version control

All tools are used in direct support of the system.

Professional Mindset

I approach machine learning as an engineering discipline focused on reliability and impact.

I prioritize clarity over complexity.

I validate assumptions early.

I treat metrics as decision aids, not goals.

I document work so others can review and extend it.

This repository reflects how I would contribute to a real ML team.

reports/support_insights.md
## Contact
GitHub: [https://github.com/your-github-username](https://github.com/marcndo)

Email: ndowahmarcel@gmail.com

Location: Cameroon (open to remote opportunities)

I am interested in junior to mid-level Machine Learning Engineer roles focused on applied ML systems, data-driven products, or AI-enabled services.
