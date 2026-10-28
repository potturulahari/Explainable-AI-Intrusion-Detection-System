🔐 Explainable AI for Intrusion Detection Systems

LIME and SHAP Applicability on Multi-Layer Perceptron

📌 About This Project

This is an academic project focused on using Explainable Artificial Intelligence (XAI) to understand how machine learning models detect network intrusions.
Machine learning models can identify suspicious network activities, but understanding why a model classifies certain traffic as normal or malicious can be difficult.
In this project, we explored two explainability techniques, LIME and SHAP, to understand which features influence model predictions. We also studied different machine learning and deep learning algorithms to compare their performance in intrusion detection.

The project helped me understand how machine learning, data analysis, and explainability techniques can be applied to a cybersecurity problem.

🎯 Project Objectives

- Explore machine learning approaches for network intrusion detection.
- Understand how an MLP model classifies network traffic.
- Apply LIME to explain individual model predictions.
- Use SHAP to understand feature contributions to predictions.
- Compare the performance of different classification algorithms.
- Explore how explainability can improve the transparency of machine learning models.

🛠️ Technologies and Tools

- Python
- Jupyter Notebook
- Machine Learning
- Deep Learning
- LIME
- SHAP
- XGBoost
- Data Visualization

📂 Dataset

CIC-IDS Dataset

The project uses network traffic data to study the classification of normal and malicious activities.
The dataset is processed before model training so that the data can be used by the machine learning algorithms.

🤖 Models Explored

The project documentation covers the following models:

- Multi-Layer Perceptron (MLP): A neural network used for classifying network traffic.
- Long Short-Term Memory (LSTM): A neural network architecture designed to learn patterns in sequential data.
- Temporal Convolutional Network (TCN): A model used to learn patterns in data with a temporal structure.
- XGBoost: A gradient-boosting algorithm used for classification.
- Hybrid Voting Classifier: An ensemble approach that combines predictions from multiple models.

🔍 Explainable AI Techniques

1. LIME

LIME (Local Interpretable Model-Agnostic Explanations) helps explain individual predictions by showing which input features influenced a particular classification.
In this project, LIME was used to explore why network traffic was classified as normal or as an attack.

2. SHAP

SHAP (SHapley Additive exPlanations) uses Shapley values to explain how individual features contribute to model predictions.
It was used to examine feature importance and understand model behavior at both individual-prediction and overall levels.

📊 Experimental Results

The project documentation reports the following model accuracies:

| Model | Reported Accuracy |
|---|---:|
| LSTM | 99.44% |
| TCN | 99.33% |
| MLP | 99.22% |
| XGBoost | 99.77% |
| Hybrid Voting Classifier | 100% |

These figures are the results reported in the project documentation. They should not be interpreted as a guarantee of performance on unseen datasets or real-world network traffic.

💡 What I Learned

Through this academic project, I gained an understanding of:

- How machine learning can be applied to cybersecurity.
- How network traffic data can be prepared for model training.
- How different classification algorithms can be compared.
- How LIME and SHAP help explain model predictions.
- Why understanding model decisions is important alongside accuracy.
- How visualizations can help communicate analytical results.

📁 Project Files

This repository contains the available academic project documentation.
The documentation describes the methodology, model comparisons, explainability techniques, experimental results, and visualizations.
The original executable source code and trained models are not currently available as separate files in this repository.

🚀 Conclusion

This project introduced me to the role of Explainable AI in cybersecurity and helped me understand the importance of making machine learning predictions easier to interpret.
I found the combination of intrusion detection and explainability particularly interesting because it connects predictive performance with understanding why a model makes a decision.
As an aspiring Data Analyst, this project also strengthened my interest in working with data, interpreting results, and presenting technical findings in an understandable way.

Project Type: Academic Team Project
