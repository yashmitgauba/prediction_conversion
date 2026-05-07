# Conversion Prediction using Machine Learning

## Research Summary

This repository includes the research paper titled **“Intelligent Conversion Prediction using Machine Learning”**. The paper studies how machine learning techniques are being used in digital advertising systems to improve conversion prediction and campaign performance.

The research explains how data-driven advertising systems can help businesses predict customer conversions more accurately and improve marketing decisions.

The research mainly focuses on:

- Conversion rate estimation
- Machine learning-driven advertising systems
- Incrementality and causal inference
- Adaptive decision-making models
- Delayed feedback handling
- Privacy-aware optimization techniques

The paper also discusses the practical challenges faced by current advertising platforms and explores possible improvements for future conversion optimization systems.

---

# Authors

- Kritika Garg — 2210004905
- Yashmit Gauba — 2210994863
- Matangini Gupta — 2210994810
- Rachit Singh — 2210994824

---

# Abstract

Conversion prediction plays an important role in modern online advertising and digital marketing systems. Most traditional advertising systems focus on attributed conversions instead of measuring the actual impact created by advertisements.

This research paper reviews different machine learning and causal inference techniques that can improve conversion optimization systems. The study investigates predictive models, uplift modeling strategies, contextual decision systems, delayed feedback learning, and privacy-preserving measurement frameworks.

The paper also explains how modern learning systems can improve advertising efficiency and budget allocation while handling challenges like delayed conversions, sparse data, and limited user tracking.

---

# Research Objectives

The main goal of this research is to analyze machine learning techniques used for conversion prediction in digital advertising platforms.

The objectives include:

1. Examining widely adopted machine learning models for conversion prediction.
2. Understanding the drawbacks of traditional attribution-based advertising systems.
3. Comparing predictive learning approaches with causal uplift techniques.
4. Exploring adaptive optimization using contextual bandit frameworks.
5. Investigating delayed conversion feedback and privacy-related challenges.
6. Identifying research gaps and future improvements in conversion optimization systems.

---

# Research Questions

### RQ1
What are the most commonly used machine learning models in conversion prediction systems?

### RQ2
How do causal and uplift modeling techniques improve incremental decision quality compared to attribution-based prediction?

### RQ3
How can budget, CPA, and pacing constraints be integrated into adaptive advertising systems?

### RQ4
What are the major deployment and research challenges under privacy-limited measurement conditions?

---

# Main Concepts Covered

## 1. Conversion Prediction

Conversion prediction refers to estimating the probability that a user will perform a valuable action such as:

- Purchase
- Subscription
- Registration
- App installation
- Sign-up

The prediction outputs are further used in:

- Ad ranking
- Budget allocation
- Bidding systems
- Campaign optimization
- Audience targeting

---

## 2. Machine Learning Approaches

The paper reviews multiple machine learning approaches used in digital advertising systems.

### Classical Models

- Logistic Regression
- Generalized Linear Models (GLMs)

### Tree-Based Models

- XGBoost
- LightGBM
- Gradient Boosted Decision Trees (GBDTs)

### Deep Learning Models

- DeepFM
- Deep & Cross Network (DCN)
- Deep Interest Network (DIN)
- ESMM (Entire Space Multi-Task Model)

### Key Learning Areas

- Feature interaction learning
- Sparse data handling
- Calibration
- Delayed feedback modeling
- Funnel-based prediction

---

# Comparative Analysis of Machine Learning Models

| Model Type | Examples | Strengths | Limitations |
|---|---|---|---|
| Classical Models | Logistic Regression | Simple and interpretable | Cannot model complex interactions |
| Tree-Based Models | XGBoost, LightGBM | Strong tabular performance | Weak sequence modeling |
| Deep Learning Models | DeepFM, DIN, DCN | Captures high-order interactions | Requires large datasets |
| Funnel-Based Models | ESMM | Reduces selection bias | More complex architecture |
| Delay-Aware Models | Delayed Feedback Models | Handles delayed conversions | Increased complexity |

---

# Attribution-Based Prediction vs Incremental Optimization

One of the major discussions in the paper is the difference between:

## Attribution-Based Systems

These systems optimize observed conversions but often fail to measure actual causal impact.

### Problems

- Over-targeting already-likely converters
- Poor budget efficiency
- Lack of causal understanding

## Incrementality-Based Systems

These systems estimate how much an advertisement actually increases conversion probability.

### Advantages

- Better budget optimization
- Improved targeting efficiency
- Accurate causal measurement
- Better ROI and iROAS

---

# Causal Uplift Modeling

The paper explores uplift modeling techniques used for estimating incremental conversion effects.

## Important Techniques

### Meta-Learners
- S-Learner
- T-Learner
- X-Learner

### Causal Forests
Used for heterogeneous treatment effect estimation.

### R-Learner
Used for robust treatment effect estimation under observational data.

---

# Contextual Bandit Systems

The paper also studies contextual bandits for adaptive ad allocation.

## Areas Covered

- Exploration vs exploitation
- Sequential optimization
- Budget-constrained learning
- Delayed reward systems
- Offline policy evaluation

## Important Methods

- Thompson Sampling
- Bandits with Knapsacks
- Doubly Robust Evaluation
- Replay-Based Evaluation

---

# Delayed Feedback in Conversion Systems

One of the biggest challenges in advertising systems is delayed feedback.

A conversion may happen:

- Minutes later
- Hours later
- Days later

This creates challenges such as:

- Incorrect negative labels
- Bias in learning systems
- Delayed optimization updates
- Unstable model performance

The paper discusses delay-aware learning systems and survival-analysis-based modeling approaches.

---

# Privacy-Conscious Advertising Frameworks

Modern advertising systems are increasingly affected by privacy regulations and tracking restrictions.

## Technologies Discussed

- App Tracking Transparency (ATT)
- Privacy Sandbox Attribution Reporting API
- Federated Learning
- Aggregated reporting systems

## Major Challenges

- Reduced user-level visibility
- Signal loss
- Sparse attribution data
- Delayed aggregated reporting

---

# Integrated Conversion Optimization Framework

```text
User / Context Input
        ↓
Feature Extraction
        ↓
Prediction Model
(Conversion / Uplift Score)
        ↓
Decision Layer
(Contextual Bandit / Policy)
        ↓
Constraint Layer
(Budget / CPA / Pacing)
        ↓
Ad Allocation
        ↓
User Interaction
        ↓
Delayed Conversion Feedback
        ↓
Model Update (Learning Loop)
```

---

# Evaluation Metrics

The research discusses multiple evaluation techniques.

## Predictive Metrics

- AUC
- PR-AUC
- Log Loss
- Calibration Error

## Uplift Evaluation Metrics

- Qini Curves
- Incremental Lift
- Treatment Effect Estimation

## Policy Evaluation Metrics

- Offline Policy Evaluation (OPE)
- Doubly Robust Estimation
- Replay-Based Evaluation

---

# Identified Research Challenges

The paper identifies several important gaps in current advertising systems:

1. Lack of integration between prediction and causal optimization.
2. Heavy reliance on attribution instead of incrementality.
3. Weak handling of delayed conversions.
4. Limited privacy-aware learning frameworks.
5. Lack of deployment-focused evaluation methods.

---

# Future Research Opportunities

The paper suggests several future research opportunities:

- Unified causal and predictive frameworks
- Delay-aware uplift systems
- Privacy-preserving advertising optimization
- Federated conversion learning
- Real-time adaptive ad allocation
- Calibration-aware decision systems
- Budget-constrained reinforcement learning

---

# Conclusion

The research concludes that future advertising systems should not rely only on traditional attribution-based prediction models and should adopt more adaptive and reliable optimization techniques.

The study emphasizes that next-generation conversion systems must combine:

- Accurate predictive analytics
- Incrementality-aware decision-making
- Contextual optimization policies
- Delayed feedback learning
- Privacy-preserving measurement techniques
- Budget-aware resource allocation

The paper shows that combining machine learning, causal inference, sequential decision-making, and privacy-aware systems can improve the overall performance of modern advertising platforms.

---

# Keywords

- Conversion Prediction
- Digital Advertising
- Machine Learning
- Uplift Modeling
- Incrementality
- Contextual Bandits
- Delayed Feedback
- Privacy-Aware Measurement
- Causal Inference
- Advertising Optimization

---

# References

The research paper includes references from:

- IEEE
- ACM
- NeurIPS
- ICML
- PMLR
- Springer
- Google Research
- Microsoft Research
- Apple Developer Documentation

Major referenced areas include:

- Conversion Rate Prediction
- Contextual Bandits
- Uplift Modeling
- Federated Learning
- Delayed Feedback Learning
- Calibration of Neural Networks
- Privacy-Preserving Advertising Systems

---

# Repository Contents

```text
├── README.md
├── Research_Paper.pdf
├── References/
└── Resources/
```

---

# Citation

If you use this research paper for academic or educational purposes, please cite the authors appropriately.

---

Source files used for generating this README: fileciteturn0file0 fileciteturn0file1

