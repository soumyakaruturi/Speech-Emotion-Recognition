
# Speech Emotion Recognition

## Overview
**Speech Emotion Recognition (SER)** aims to automatically identify human emotions from speech signals using machine learning and deep learning techniques. This repository demonstrates models and code for extracting features from speech and classifying emotions, providing a hands-on platform for research or application in affective computing and voice-driven interfaces.

## Features
- Processes raw audio data to extract vital features (MFCC, chroma, mel, etc.).
- Implements multiple algorithms (e.g., MLP, CNN, RNN-LSTM).
- Support for popular speech emotion datasets such as **RAVDESS** and **TESS**.
- Interactive prediction (command-line or notebook).

## Installation

```bash
git clone https://github.com/soumyakaruturi/Speech-Emotion-Recognition.git
cd Speech-Emotion-Recognition
pip install -r requirements.txt
```
*Requires Python 3.x and pip.*

## Usage

1. Place audio files in the relevant data directory (`data/` or as specified in code).
2. Run feature extraction and preprocess scripts as per instructions in the code/notebooks.
3. Train models or use pre-trained models:
   ```bash
   python train.py
   ```
4. Predict emotions from new audio files:
   ```bash
   python predict.py --input sample.wav
   ```
5. For help on script arguments:
   ```bash
   python predict.py --help
   ```

## Datasets

- **RAVDESS**: North American accent, 24 actors, 5 emotions.
- **TESS**: Two actresses, seven emotions.

## Emotions Supported

- Neutral

- Happy
- Sad
- Angry
- Fearful
- Disgust

## Technologies

- Python (Librosa, scikit-learn, Keras/TensorFlow or PyTorch)
- Jupyter Notebook for interactive exploration
- Soundfile, numpy, pandas for data manipulation.

## Results

Include sample outputs, accuracy, confusion matrix, and model performance metrics if available. Example:
- Classification report (precision/recall/F1)
- Model loss/accuracy plots

