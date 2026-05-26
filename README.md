# CBCL-PDA

A GCN-Transformer dual-branch encoder for protein-drug association prediction

Requirements

Python >= 3.8
PyTorch >= 1.10
scikit-learn >= 1.0
XGBoost >= 1.5
numpy >= 1.21
pandas >= 1.3

File Structure
.
├── model.py          # Model definitions: GCN, Transformer, contrastive learning, attention fusion
├── train.py          # Training logic: model training, negative sampling, graph construction, data preparation
├── data_utils.py     # Utilities: data loading, cross-validation, evaluation metrics
├── main.py           # Entry point: 5-fold cross-validation pipeline
└── README.md         # Project documentation


Quick Start
    python main.py
