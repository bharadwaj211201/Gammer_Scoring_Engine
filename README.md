# Grammar Scoring Engine for Spoken Data

## Overview
This project implements a Grammar Scoring Engine that predicts a continuous grammar score (0–5) from spoken English audio samples using audio feature extraction and machine learning.

## Dataset Structure

dataset/
├── csvs/
│ ├── train.csv
│ └── test.csv
└── audios/
├── train/ (not included in repo)
└── test/ (not included in repo)


## Approach
- Audio preprocessing using Librosa
- MFCC, Delta, and Delta-Delta feature extraction
- Statistical feature aggregation
- Random Forest Regression
- Evaluation using RMSE

## Evaluation
- Metric: Root Mean Squared Error (RMSE)
- Training RMSE is reported in the notebook as required

## Files
- `grammar_scoring.ipynb`: Complete implementation with explanations
- `submission.csv`: Final predictions for test data

## Note
Audio files are excluded from this repository due to size constraints.

## Author
Bharadwaj Mudigonda


