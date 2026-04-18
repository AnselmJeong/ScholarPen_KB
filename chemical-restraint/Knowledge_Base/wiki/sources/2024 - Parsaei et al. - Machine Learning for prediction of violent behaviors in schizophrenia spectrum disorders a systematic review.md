---
type: source
title: "Machine Learning for prediction of violent behaviors in schizophrenia spectrum disorders: a systematic review"
created: 2024-03-21
updated: 2024-03-21
tags: [machine learning, schizophrenia spectrum disorders, violent behavior prediction, gradient boosting, area under curve, risk assessment, predictive modeling, psychiatric prognosis, machine learning algorithms, psychopathology]
related: []
sources: ["Human rights, Coercive Treatment/2024 - Parsaei et al. - Machine Learning for prediction of violent behaviors in schizophrenia spectrum disorders a systematic review.pdf"]
one_line_finding: Machine learning models, particularly gradient boosting, show moderate to strong predictive performance for violent behavior in schizophrenia spectrum disorders, though heterogeneity in outcomes and lack of external validation limit clinical applicability.
---

# Machine Learning for prediction of violent behaviors in schizophrenia spectrum disorders: a systematic review

## Summary
This systematic review evaluates the application of machine learning (ML) techniques to predict violent behavior (VB) in individuals diagnosed with schizophrenia spectrum disorders (SSD). The analysis synthesized 18 studies comprising 11,733 patients, assessing various ML algorithms including support vector machines, random forests, and gradient boosting models. Outcomes were measured using area under the receiver operating characteristic curve (AUROC) and accuracy, with VB defined heterogeneously across studies—ranging from verbal aggression to homicide. Gradient boosting consistently demonstrated superior predictive performance compared to other algorithms, achieving AUROC values up to 0.95 in individual studies. Key predictors identified across models included age, antipsychotic dosage (particularly olanzapine equivalent), psychiatric symptom severity (e.g., PANSS scores), and socioenvironmental factors such as prior hospitalizations and social isolation. The review highlights the potential of ML to augment clinical risk assessment but emphasizes challenges related to outcome heterogeneity, limited external validation, and ethical concerns regarding predictive labeling in psychiatric care.

## Key Entities
- **Frontiers in Psychiatry** (journal) — the peer-reviewed journal where the study was published
- **PubMed** (database) — one of the primary literature sources searched for relevant studies
- **Web of Science** (database) — a major academic database included in the systematic search strategy
- **Embase** (database) — a biomedical and pharmacological database used in the literature search
- **PsycINFO** (database) — a psychology-specific database searched for relevant psychiatric and behavioral studies
- **PROBAST** (tool) — the risk-of-bias assessment tool used to evaluate the quality of included prediction model studies
- **CHARMS** (tool) — guidelines followed for critical appraisal and data extraction in prediction modeling studies
- **PRISMA** (tool) — the reporting standard adhered to for ensuring transparency in the systematic review process

## Key Concepts
- **Machine Learning (ML)** — a subset of artificial intelligence that enables algorithms to learn patterns from data and make predictions; applied here to forecast violent behavior in SSD populations
- **Schizophrenia Spectrum Disorders (SSD)** — a diagnostic category encompassing schizophrenia, schizoaffective disorder, and related psychotic conditions associated with elevated risk of violent behavior
- **Violent Behavior (VB)** — defined variably across studies as any act of physical or verbal aggression toward self, others, or property, including aggression, assault, and homicide
- **Area Under the Receiver Operating Characteristic Curve (AUROC)** — a standard metric for evaluating the discriminative ability of binary classifiers, with values ranging from 0.5 (chance) to 1.0 (perfect separation)
- **Gradient Boosting** — an ensemble ML technique that builds predictive models sequentially by correcting errors of prior models; identified as the top-performing algorithm in this review
- **Random Forest (RF)** — an ensemble method using multiple decision trees for classification and regression; frequently used and high-performing in the analyzed studies
- **Support Vector Machine (SVM)** — a supervised learning model effective in high-dimensional spaces; commonly applied and competitive in VB prediction tasks

## Main Arguments & Findings
- **Core claim**: Gradient boosting models demonstrated superior performance in predicting violent behavior among individuals with schizophrenia spectrum disorders compared to other machine learning algorithms.
  - **Evidence**: Across 18 studies, ML models showed AUROC values ranging from 0.56 to 0.95 and accuracy from 50.27% to 90.67%; gradient boosting consistently achieved the highest ranks in individual study comparisons and was frequently identified as the best-performing model.
  - **Strength**: Strong — supported by a rigorous systematic review following PRISMA and CHARMS guidelines, with risk of bias assessed via PROBAST; however, moderate due to high heterogeneity in VB definitions, patient populations, and feature sets, limiting direct comparison and generalizability.
- **Core claim**: Key predictors of violent behavior in SSD patients include demographic (e.g., age), clinical (e.g., antipsychotic dosage, symptom severity), and socioenvironmental factors (e.g., prior hospitalizations, social isolation).
  - **Evidence**: Multiple studies identified age and olanzapine equivalent dose at discharge as the most frequently reported significant features; others highlighted PANSS scores, history of violence, and lack of outpatient treatment.
  - **Strength**: Moderate — while consistent across several studies, the variability in how predictors were measured and modeled reduces confidence in a universal biomarker or feature set.

## Connections
- [[concepts/machine-learning]] — this study applies ML to a specific psychiatric prediction problem, illustrating its potential in clinical risk assessment
- [[concepts/risk-assessment]] — the work extends traditional risk assessment by introducing data-driven, algorithmic approaches to violence prediction in mental health
- [[concepts/schizophrenia]] — the focus on SSD populations connects to foundational knowledge about the illness, its risks, and management challenges

## Contradictions & Tensions
- Despite high AUROC values (up to 0.95) in some studies, the clinical utility of these models remains uncertain due to frequent lack of external validation, small sample sizes in individual studies, and potential overfitting to specific cohorts.
- The definition of violent behavior varied significantly across studies—from verbal aggression to criminal acts—making it difficult to compare results or develop a standardized predictive tool.
- While models show strong discriminative ability, ethical concerns arise regarding the use of predictive labels in psychiatric settings, including stigma, potential misuse in coercive interventions, and impacts on patient autonomy and therapeutic relationships.

## Open Questions
- How do machine learning predictions of violent behavior influence clinical decision-making, and do they lead to improved patient outcomes or increased use of coercive interventions?
- What are the ethical implications of deploying predictive models in psychiatric care, particularly concerning consent, privacy, and the risk of reinforcing bias against individuals with serious mental illness?
- Can machine learning models be generalized across diverse healthcare systems, cultural contexts, and patient populations, or are they limited to the specific datasets on which they were trained?
