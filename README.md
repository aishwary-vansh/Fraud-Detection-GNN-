# Financial Network Fraud Detection using Graph Neural Networks

## Overview

Financial fraud often occurs through networks of connected accounts and transactions rather than isolated events. Traditional machine learning models struggle to capture these complex relationships.

This project aims to detect **fraudulent financial activities** by modeling transaction data as a **graph** and applying **Graph Neural Networks (GNNs)**.

The model analyzes relationships between accounts, transactions, and entities to identify suspicious patterns such as fraud rings or money laundering networks.

---

## Objectives

* Model financial transactions as a graph structure
* Detect suspicious accounts or transactions
* Apply Graph Neural Networks for fraud detection
* Analyze patterns in financial transaction networks

---

## Technologies Used

* Python
* PyTorch
* PyTorch Geometric
* NetworkX
* Pandas
* Scikit-learn

---

## Project Structure

```
Fraud-Detection-GNN
│
├── data
│   ├── raw
│   └── processed
│
├── notebooks
│   └── exploration.ipynb
│
├── src
│   ├── models
│   ├── utils
│   └── train.py
│
├── experiments
│
├── main.py
├── requirements.txt
└── README.md
```

---

## Workflow

1. Load transaction dataset
2. Preprocess financial data
3. Convert transactions into a graph
4. Train a Graph Neural Network model
5. Detect fraudulent nodes or transactions

---

## Future Improvements

* Graph Attention Networks (GAT)
* Temporal fraud detection
* Real-time fraud detection pipelines
* Large-scale financial graph analysis

---

## Author

Aishwary Vansh
B.Tech Computer Science Engineering (2024–2028)
