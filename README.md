# emotion-detection
The notebook begins with installing dependencies and importing libraries such as Whisper, Librosa, and Scikit-learn. It then proceeds to load the Whisper model, likely for transcribing speech from audio files. There’s also mention of `moviepy`, suggesting audio extraction from video files.


---

# Multilingual Emotion Detection in Voice

This repository contains a Jupyter notebook that demonstrates how to detect emotions from multilingual voice data using OpenAI's Whisper model for transcription, Librosa for audio feature extraction, and Support Vector Machine (SVM) for classification.

## 📌 Overview

The notebook walks through the following major steps:

1. **Speech Recognition**
   Using Whisper to transcribe audio files to text.

2. **Feature Extraction**
   Extracting MFCC (Mel-frequency cepstral coefficients) features from audio using Librosa.

3. **Emotion Classification**
   Using a Support Vector Machine (SVM) to classify emotional tone based on extracted features.

4. **Audio Processing**
   Includes support for extracting audio from video files using `moviepy`.

## 🧰 Requirements

```bash
pip install openai-whisper librosa scikit-learn moviepy
```

## 🛠️ Technologies Used

* **Whisper** – Multilingual automatic speech recognition.
* **Librosa** – Audio analysis and MFCC feature extraction.
* **Scikit-learn** – Training SVM classifiers.
* **MoviePy** – Extracting audio from video files.

## 📁 Files

* `multilingual_emotion_detection_in_voice.ipynb`: The core notebook containing code, instructions, and demonstrations.

## 🚀 Getting Started

1. Clone the repository.
2. Open the notebook in Jupyter.
3. Run each cell in order to:

   * Transcribe audio
   * Extract features
   * Train/test the classifier

## 🧪 Example Use Cases

* Analyze customer support calls for sentiment
* Monitor emotional state in multilingual therapeutic contexts
* Add emotional awareness to voice assistants

## 📝 License

This project is licensed under the MIT License.

---

