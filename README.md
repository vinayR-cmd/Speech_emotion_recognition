🎶 Speech Emotion Recognition

This project is an implementation of Speech Emotion Recognition (SER) using deep learning and MFCC feature extraction.
It predicts emotions such as Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise from audio recordings.

Dataset used: 🎤 Toronto Emotional Speech Set (TESS)

🌟 Highlights

✔️ Recognizes 7 emotions from speech
✔️ Uses MFCC features for robust audio representation
✔️ Built with Deep Learning (LSTM/Conv1D)
✔️ Works on real-time input audio files
✔️ Provides confidence score for predictions
✔️ Includes training visualizations (accuracy & loss curves)

📂 Dataset Overview

Name: TESS (Toronto Emotional Speech Set)

Samples: ~5600 audio clips

Format: .wav

Speakers: 2 female actors (ages 26 and 64)

Emotions: Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise

📊 Results & Visualizations

Training Accuracy: ~95%

Testing Accuracy: ~90%

📈 Example training graph:

🚀 How It Works

Feature Extraction → Extracts MFCCs from audio signals.

Model Training → Trains a deep learning model (LSTM/Conv1D).

Prediction → Identifies the emotion from new speech samples with confidence scores.

🔮 Future Scope

Extend support for real-world noisy audio

Explore Bidirectional LSTM / Attention-based models

Integrate with RAVDESS, CREMA-D, Emo-DB datasets

Build a real-time emotion recognition app
