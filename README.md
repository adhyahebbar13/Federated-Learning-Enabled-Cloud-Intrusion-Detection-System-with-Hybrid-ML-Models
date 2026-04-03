# Federated Learning–Enabled Cloud Intrusion Detection System

## Overview

This project implements a comprehensive cloud intrusion detection system using a hybrid machine learning approach on synthetically generated cloud logs. It simulates realistic cloud environments and multi-stage attack scenarios, enabling robust detection of anomalous and malicious activities.

The system integrates rule-based detection, unsupervised anomaly detection, supervised learning models, and neural networks, along with federated learning to enable decentralized and privacy-preserving model training across distributed nodes.

---

## Key Features

* Synthetic cloud log generation using Faker to simulate realistic environments

* Multi-stage attack simulation (e.g., abnormal API usage, suspicious access patterns)

* Feature engineering from cloud activity:

  * API calls
  * User roles
  * Geographic regions
  * Latency and response times
  * Data transfer patterns

* Hybrid detection framework:

  * Rule-based anomaly detection
  * Unsupervised learning (Isolation Forest)
  * Supervised models (Random Forest, XGBoost)
  * Neural networks for complex pattern recognition

* Federated learning setup:

  * Decentralized model training across multiple nodes
  * Privacy-preserving learning without raw data sharing
  * Aggregation of local models into a global model

* Modular and scalable ML pipeline

---

## Tech Stack

* **Programming:** Python
* **Data Processing:** Pandas, NumPy
* **Synthetic Data Generation:** Faker
* **Machine Learning:**

  * Scikit-learn (Random Forest, Isolation Forest)
  * XGBoost
* **Deep Learning:** TensorFlow / Keras
* **Learning Paradigm:** Federated Learning

---


## Workflow

### 1. Synthetic Data Generation

* Generate realistic cloud logs using Faker
* Simulate users, services, and cloud activities
* Inject attack patterns and anomalies

### 2. Data Preprocessing

* Clean and structure log data
* Encode categorical features
* Normalize numerical features

### 3. Feature Engineering

* Extract behavioral patterns from:

  * API usage frequency
  * Access locations
  * Data transfer anomalies
  * Latency deviations

### 4. Detection Models

#### Rule-Based System

* Detect predefined suspicious behaviors
* Serve as baseline detection

#### Unsupervised Learning

* Isolation Forest for anomaly detection
* Identify unknown or zero-day patterns

#### Supervised Learning

* Random Forest and XGBoost classifiers
* Classify normal vs malicious activity

#### Neural Networks

* Capture complex, non-linear relationships
* Improve detection of subtle attack patterns

---

### 5. Federated Learning

* Simulate multiple distributed clients
* Train local models on separate datasets
* Aggregate weights into a global model
* Ensure privacy by avoiding raw data sharing

---

## Results

* Effective detection of anomalous cloud activities
* Improved robustness using hybrid ML approach
* Enhanced scalability and privacy via federated learning

*(Add accuracy, F1-score, etc. here for stronger impact)*

---

## Future Improvements

* Real-time streaming data integration
* Deployment on cloud platforms (AWS/GCP/Azure)
* Advanced federated optimization techniques
* Integration with SIEM/security monitoring tools

---


## Author

Adhya Hebbar

---

## License

MIT License
