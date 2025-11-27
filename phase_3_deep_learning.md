# Phase 3: Deep Learning

## Objective
Investigate neural-network performance for binary health-outcome classification and compare against classical approaches.

## Approach

- Implemented feed-forward Keras models for binary classification
- Started with a simple baseline architecture
- Intentionally explored over-parameterized models to study overfitting
- Added early stopping to improve validation behavior
- Ran architecture search over depth, width, and activations
- Applied regularization techniques (L2 and dropout)
- Evaluated best model on held-out test data with F1 and ROC-AUC

## Key Takeaway
Generalization improved most from disciplined regularization and training control (especially early stopping/L2), not from model complexity alone.
