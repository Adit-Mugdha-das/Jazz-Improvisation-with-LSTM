# Jazz Improvisation with LSTM

This repository contains the programming assignment from **Week 1** of **Course 5: Sequence Models** in the [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) by Andrew Ng on Coursera.

## Overview

In this assignment, a Long Short-Term Memory (LSTM) network is implemented to generate jazz music by predicting a sequence of musical values. The model is trained on a dataset of jazz music examples and learns to produce improvisations resembling real performances.

Key concepts covered:
- Music data preprocessing
- LSTM cell implementation
- Music sequence modeling
- Sampling new music sequences
- Generation of improvisations based on learned patterns

## Dataset Information

To comply with GitHub’s file size limitations (maximum 100MB per file), some non-essential files have been removed from the `data/` folder in this repository.  
This includes large raw audio or intermediate files that are not required to understand or run the notebook functionality.

If you wish to work with the complete original dataset, you can download it from the following link:

**[Download Full Jazz Dataset (Coursera Resources)](https://d3c33hcgiwev3.cloudfront.net/_d6a3b28b41a8e8829821fd7db6aa8df5_music_utils.py?Expires=1656547200&Signature=...)**

*Note: Please ensure you have access to Coursera's official course resources.*

## Contents

- `jazz_model.py` – Contains the implementation of the LSTM-based music generation model
- `music_utils.py` – Helper functions for processing and playing music
- `predict_and_sample()` – Predicts the next note and samples a value
- `model()` – Trains the LSTM model
- Jupyter Notebook – Walks through the assignment step-by-step

## Technologies Used

- Python 3
- TensorFlow / Keras
- NumPy

## Course Information

- Course: Sequence Models (Course 5 of 5)
- Specialization: Deep Learning Specialization
- Instructor: Andrew Ng
- Platform: Coursera
- Institution: DeepLearning.AI

## License

This repository is based on educational material provided by DeepLearning.AI through Coursera. It is intended for educational and personal use only and is not authorized for commercial use.

---
