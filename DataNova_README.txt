DataNova 2026 | Predictive Healthcare Analytics and Clinical Decision-Support System
Early Risk Stratification for Type 2 Diabetes Using Explainable AI

Hackathon: DataNova 2026
Domain: Healthcare Analytics | Machine Learning | Clinical Decision Support
Project Status: Research and Solution Design Stage
Technology Stack: Python, SQL, Scikit-learn, SHAP, Power BI

Project Team:
- Pradeep Shivaji Salunke
- Surendra Reddy Alavala
- Prabhakar Edara

======================================================================
1. PROJECT OVERVIEW
======================================================================
Healthcare systems collect enormous amounts of patient information, yet identifying individuals who may develop chronic diseases remains a significant challenge.

Our project, A Predictive Healthcare Analytics and Clinical Decision-Support System, explores how machine learning and explainable artificial intelligence can help healthcare professionals recognize early patterns associated with Type 2 diabetes.

The proposed solution combines historical electronic health record (EHR) data, predictive modeling, explainability techniques, and interactive analytics to support risk-informed clinical decision-making.

Our goal is not to replace healthcare professionals but to provide meaningful insights that help them make better-informed screening and preventive-care decisions.

======================================================================
2. PROBLEM STATEMENT
======================================================================
Type 2 diabetes often develops gradually, and some patients remain undiagnosed until symptoms or complications emerge.

Traditional approaches may not fully use the information already available in longitudinal electronic health records.

Our project addresses three questions:
1. Can historical clinical information help identify patients at greater risk of developing Type 2 diabetes?
2. Can machine-learning predictions be explained in a way healthcare professionals can understand?
3. Can predictive analytics be integrated into a practical, clinician-reviewed workflow?

======================================================================
3. PROPOSED SOLUTION
======================================================================
We propose an end-to-end healthcare analytics framework consisting of five stages.

Stage 1 - Data Extraction
SQL-based extraction of eligible patient records, laboratory results, and relevant clinical history.

Stage 2 - Data Preparation
Python-based preprocessing, missing-value handling, feature engineering, and data-quality checks.

Stage 3 - Predictive Modeling
Evaluation of classification algorithms, including Logistic Regression, Random Forest, and XGBoost, to estimate diabetes-related risk.

Stage 4 - Explainable AI
Use of SHAP to help explain which clinical features contribute to model predictions.

Stage 5 - Clinical Decision Support
Power BI dashboards designed to communicate risk estimates, population trends, and patient-level explanations for clinician review.

Proposed System Architecture:
Electronic Health Records -> SQL -> Python -> Machine Learning -> SHAP -> Power BI -> Clinician Review

======================================================================
4. CLINICAL FEATURES
======================================================================
The proposed predictive framework considers:
- Age: Patient age
- BMI: Body mass index
- HbA1c: Long-term blood glucose indicator
- Blood Glucose: Recorded glucose measurements
- Blood Pressure: Blood pressure measurements
- Family History: Relevant family history
- Physical Activity: Recorded activity information
- Smoking Status: Smoking history

The final feature set will depend on dataset availability, clinical relevance, data quality, and the defined prediction target. Patient identifiers will be excluded from model predictors.

======================================================================
5. MACHINE-LEARNING METHODOLOGY
======================================================================
The planned model-development process includes:
- Defining the eligible patient population and prediction outcome.
- Excluding patients with diabetes at baseline when modeling future disease onset.
- Using only information available before the prediction date.
- Creating patient-separated training and testing datasets.
- Comparing baseline and ensemble classification models.
- Evaluating discrimination, sensitivity, precision, and calibration.
- Investigating prediction explanations using SHAP.

Where longitudinal follow-up data is unavailable, the prediction objective must be revised and clearly labeled rather than represented as future disease prediction.

======================================================================
6. PROPOSED RISK STRATIFICATION
======================================================================
The initial framework illustrates three risk categories:
- Low Risk: Below 20%
- Moderate Risk: 20%-50%
- High Risk: Above 50%

IMPORTANT: These thresholds are illustrative research-design examples. They have not been calibrated or clinically validated and must not be used for patient-care decisions.

======================================================================
7. EXPLAINABLE AI AND RESPONSIBLE HEALTHCARE ANALYTICS
======================================================================
Prediction alone is not enough in a clinical environment.

We propose incorporating explainable AI to help healthcare professionals understand the factors influencing model-generated risk estimates.

The responsible AI framework addresses:
- Transparency: Clearly communicating model predictions and limitations.
- Fairness: Evaluating differences in model performance across relevant patient groups.
- Privacy: Protecting sensitive healthcare information.
- Accountability: Preserving clinician responsibility for medical decisions.
- Reliability: Assessing model performance, calibration, and data leakage.
- Human Oversight: Ensuring predictions support, rather than replace, clinical judgment.

The system is intended for research and decision-support exploration only.

======================================================================
8. PROPOSED INNOVATION
======================================================================
The project brings together several capabilities within a single conceptual healthcare analytics workflow:

Future-Oriented Risk Modeling:
Designing models around incident diabetes rather than simply identifying existing disease.

Explainable Predictions:
Connecting risk estimates to interpretable clinical features.

Time-Aware Methodology:
Preventing future clinical information from leaking into model training.

Population-Level Analytics:
Presenting patient-risk distributions and patterns through an interactive reporting framework.

Responsible AI Integration:
Embedding fairness, privacy, uncertainty, and human oversight into the proposed architecture.

These capabilities represent proposed design elements. Their comparative novelty and clinical benefit have not yet been experimentally established.

======================================================================
9. EXPECTED IMPACT
======================================================================
If successfully implemented and validated, the proposed system could help healthcare organizations:
- Identify individuals who may benefit from earlier screening.
- Better understand population-level diabetes risk.
- Reduce manual work associated with structured risk analysis.
- Improve the interpretability of predictive insights.
- Support preventive-care planning and clinical research.

These are anticipated benefits rather than demonstrated clinical outcomes.

======================================================================
10. CURRENT PROJECT STATUS
======================================================================
This submission currently includes a conceptual system architecture, example SQL and Python workflows, proposed model-development methodology, illustrative dashboards, and a responsible AI framework.

Current limitations:
- A final authorized dataset has not yet been selected.
- No completed end-to-end model evaluation is reported.
- Model performance metrics are not yet available.
- Dashboard visuals are conceptual or based on synthetic demonstration data.
- Clinical validation and real-world deployment have not been performed.

The project is therefore presented as a research-stage solution design, not an operational clinical decision-support product.

======================================================================
11. PROJECT DOCUMENTATION
======================================================================
- Project Presentation (PPT): Hackathon solution presentation
- Project Presentation (PDF): Shareable presentation document
- Research White Paper: Technical approach and research methodology
- Responsible AI & Clinical Safety Report: Ethical, privacy, fairness, and clinical safety considerations
- README.md: Project overview, documentation, and status

======================================================================
12. FUTURE DEVELOPMENT ROADMAP
======================================================================
Phase 1 - Data Preparation:
Identify a suitable dataset, document its source and license, define the outcome, and implement preprocessing.

Phase 2 - Machine Learning:
Train baseline and ensemble models, evaluate predictions, and assess model calibration.

Phase 3 - Explainability:
Implement and evaluate SHAP-based global and patient-level explanations.

Phase 4 - Visualization:
Develop an interactive risk-analysis dashboard using Power BI or an appropriate prototype platform.

Phase 5 - Validation:
Conduct subgroup fairness analysis, temporal validation where feasible, and further clinical review before considering deployment.

======================================================================
13. ETHICAL AND CLINICAL DISCLAIMER
======================================================================
This project is intended for academic research, hackathon evaluation, and technology exploration.

It is not a clinically validated medical device and must not be used to diagnose Type 2 diabetes, determine treatment, or independently make medical decisions.

Any future healthcare implementation would require appropriate data governance, clinical validation, security review, and regulatory assessment.

======================================================================
14. CONCLUSION
======================================================================
Healthcare analytics has the potential to move beyond retrospective reporting toward more proactive and interpretable insights.

Through this project, we aim to demonstrate how SQL, Python, machine learning, explainable AI, and Power BI can be combined into a responsible framework for Type 2 diabetes risk stratification.

Our long-term vision is a system that transforms clinical information into actionable insights while keeping healthcare professionals central to every important decision.

DataNova 2026 - Predictive Healthcare Analytics and Clinical Decision-Support System
From Data to Insight. From Prediction to Prevention.
