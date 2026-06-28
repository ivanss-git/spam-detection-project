# Spam Detection System

A beginner-friendly spam detection project that combines rule-based filtering with machine learning. The goal is to understand how spam detection works from the ground up while practicing data preprocessing, model training, evaluation, and software organization.

## Project Goals

- Build a rule-based spam detector
- Train a machine learning model for spam classification
- Compare rule-based vs model-based results
- Combine both approaches into a hybrid decision system
- Practice clean project structure, testing, and documentation

## System Overview

```text
Email/Text Input
      ↓
Rule-Based Detector
      ↓
ML Spam Classifier
      ↓
Hybrid Decision Engine
      ↓
Spam / Not Spam / Uncertain

## System Overview

spam-detector/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── docs/
│   ├── project_plan.md
│   ├── research_notes.md
│   └── experiments.md
│
├── models/
│
├── src/
│   ├── rules/
│   │   ├── keyword_rules.py
│   │   ├── link_rules.py
│   │   └── scoring.py
│   │
│   ├── model/
│   │   ├── preprocess.py
│   │   ├── train.py
│   │   ├── predict.py
│   │   └── evaluate.py
│   │
│   ├── hybrid/
│   │   └── decision_engine.py
│   │
│   └── main.py
│
├── tests/
│   ├── test_rules.py
│   ├── test_preprocess.py
│   └── test_hybrid.py
│
├── README.md
├── requirements.txt
└── .gitignore