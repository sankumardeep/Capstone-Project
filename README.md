# Capstone-Project


🚀 IoT Intrusion Detection using Hybrid Optimization and Deep Learning

📌 Overview

This project presents a multi-class intrusion detection system for IoT networks using advanced feature selection techniques and deep learning models. The system is designed to accurately classify normal and malicious traffic using the CICIoT 2023 dataset.

We combine metaheuristic optimization algorithms (SHO, PSO, ACO) with Capsule Deep Autoencoder (CapsDA) and Transformer models to improve detection performance and efficiency.

🎯 Objectives

Detect and classify IoT network attacks with high accuracy
Reduce feature dimensionality using optimization algorithms
Compare multiple models using 7 evaluation metrics
Build a robust and efficient intrusion detection system

🧠 Technologies Used

Python (NumPy, Pandas, Matplotlib, Seaborn)
Scikit-learn (Preprocessing, Metrics, PCA)
TensorFlow / Keras (Deep Learning Models)
Optimization Algorithms:
Spotted Hyena Optimization (SHO)
Particle Swarm Optimization (PSO)
Ant Colony Optimization (ACO)

📂 Dataset

CICIoT 2023 Dataset
Multi-class dataset containing:
Benign Traffic
Multiple DDoS attack types

⚙️ Project Workflow

Data Preprocessing
Merge datasets (train, test, validation)
Handle missing values and cleaning
Label encoding and balancing
Dimensionality Reduction
Apply PCA (Principal Component Analysis)
Feature Selection
SHO (Spotted Hyena Optimization)
PSO (Particle Swarm Optimization)
ACO (Ant Colony Optimization)
Model Training
CapsDA (Capsule Deep Autoencoder)
Transformer Model
Evaluation
Accuracy
Precision
Recall
F1-score
ROC-AUC
FAR (False Alarm Rate)
MCC (Matthews Correlation Coefficient)

📊 Results

Method	Accuracy	Precision	Recall	F1-score
SHO-CapsDA	96.2%	96.7%	96.2%	96.1%
PSO-CapsDA	96.0%	96.6%	96.0%	96.0%
ACO-CapsDA	96.1%	96.6%	96.1%	96.0%

👉 Achieved ~96% accuracy across all models
👉 SHO-based model performed best

📈 Visualizations

Confusion Matrix
Accuracy & Loss Graphs
Model Comparison Bar Charts
Heatmaps

🧪 Key Features

Multi-class classification (8 classes)
Hybrid approach (Optimization + Deep Learning)
Efficient feature selection
Robust performance with minimal false alarms

📦 How to Run

# Clone the repository
git clone git clone (https://github.com/sankumardeep/Capstone-Project#)

# Navigate to project
cd your-repo-name

# Install dependencies
pip install -r requirements.txt

# Run the notebooks / scripts
🧠 Key Insights
Feature selection significantly improves performance
SHO outperforms PSO and ACO
Transformer and CapsDA both achieve high accuracy
Low FAR indicates fewer false alarms
