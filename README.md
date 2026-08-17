# Intrusion Detection System Using Machine Learning

A reproducible multi-class network intrusion detection study for identifying **Normal, DoS, Probe, R2L, and U2R** traffic categories. The project combines practical cybersecurity monitoring with machine-learning evaluation and Power BI-ready reporting.

## Why this project matters

Security operations need interpretable signals, not only a high score. This repository demonstrates a complete analytical workflow: data preparation, feature scaling, Random Forest classification, evaluation, feature-importance analysis, and export of results for business-facing dashboards.

## Research workflow

1. Load and inspect the selected KDD99 or UNSW-NB15 data.
2. Prepare features, labels, and train/test partitions.
3. Train and evaluate the multi-class Random Forest model.
4. Review confusion matrices, classification metrics, and important features.
5. Export model outputs for visualization in Power BI.

## Main artifact

The notebook `Intrusion_Detection_System_(IDS)_using_ML.ipynb` contains the end-to-end experiment. For production use, separate data ingestion, preprocessing, training, and inference into tested Python modules and pin the environment before deployment.

## Responsible use

This is an educational research project. Results depend on the dataset, class balance, feature quality, and validation design. It should not be treated as a complete security control without independent testing, monitoring, and domain review.
