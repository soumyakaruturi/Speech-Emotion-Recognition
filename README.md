
# Speech Emotion Recognition

## Overview
**Speech Emotion Recognition (SER)** aims to automatically identify human emotions from speech signals using machine learning and deep learning techniques. This repository demonstrates models and code for extracting features from speech and classifying emotions, providing a hands-on platform for research or application in affective computing and voice-driven interfaces.[1][2][3]

## Features
- Processes raw audio data to extract vital features (MFCC, chroma, mel, etc.).[2][4]
- Implements multiple algorithms (e.g., MLP, CNN, RNN-LSTM).[3][1]
- Support for popular speech emotion datasets such as **RAVDESS** and **TESS**.[4][2]
- Interactive prediction (command-line or notebook).[1][3]

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

- **RAVDESS**: North American accent, 24 actors, 8 emotions.[2][4]
- **TESS**: Two actresses, seven emotions.[5][4]

## Emotions Supported

- Neutral
- Calm
- Happy
- Sad
- Angry
- Fearful
- Disgust
- Pleasurable Surprise

## Technologies

- Python (Librosa, scikit-learn, Keras/TensorFlow or PyTorch)
- Jupyter Notebook for interactive exploration
- Soundfile, numpy, pandas for data manipulation.[3][2]

## Results

Include sample outputs, accuracy, confusion matrix, and model performance metrics if available. Example:
- Classification report (precision/recall/F1)
- Model loss/accuracy plots

