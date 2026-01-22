# Network Intrusion Detection using Supervised Machine Learning

## Overview
This project implements a **supervised machine learning-based Network Intrusion Detection System (NIDS)** to classify network traffic as **normal or malicious**. The goal is to enhance cybersecurity through automation, accuracy, and cost efficiency.

---

## Problem Domain
Modern networks are exposed to frequent cyber threats such as DoS attacks, probing, and unauthorized access. Traditional rule-based security systems are insufficient to detect evolving attack patterns. Machine learning enables adaptive and data-driven intrusion detection.

---

## Problem Statement
The objective is to develop a **classification model** that:
- Identifies network intrusions accurately
- Achieves **≥ 90% accuracy**
- Supports business goals including **security enhancement, automation, and cost reduction**

---

## Input Data Requirements
### Data
- Labeled network traffic records
- Features include protocol type, connection duration, byte counts, and error rates

### Sources
- NSL-KDD
- UNSW-NB15
- CICIDS2017

### Considerations
- Class imbalance
- Dataset bias
- CSV structured format

---

## Output Requirements
- Binary classification:
  - `0` → Normal traffic
  - `1` → Intrusion detected
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Confusion Matrix for analysis

---

## Constraints and Assumptions
### Constraints
- Limited real-world labeled attack data
- Computational resource limits

### Assumptions
- Dataset reflects real network behavior
- Extracted features are accurate and relevant

---

## Feasibility and Impact
### Feasibility
- Availability of benchmark datasets
- Use of Scikit-learn for model development
- Proven effectiveness of supervised classifiers

### Impact
- Faster and more accurate intrusion detection
- Reduced manual monitoring
- Improved network security and operational efficiency

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## Future Work
- Real-time traffic integration
- Multi-class attack classification
- Hybrid supervised + unsupervised detection
