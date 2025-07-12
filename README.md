# 🎧 Real-Time Voice Emotion Detector

This project uses machine learning to detect human emotions such as **happy**, **sad**, **angry**, and **neutral** from real-time speech using your microphone. It combines classical ML techniques with live audio feature extraction to classify emotions on the fly.

---

## 📌 Features

- 🎙️ Record speech from your microphone
- 🧠 Classify emotions using Random Forest & SVM
- 📊 Hyperparameter tuning with GridSearchCV
- 📈 Accuracy comparison & feature importance visualization
- 🔁 Real-time emotion prediction with text-to-speech feedback
- 🔧 Improved prediction with normalized audio input

---

## 🚀 How to Run

# Step 1: Clone the repository
git clone https://github.com/yourusername/real-time-voice-emotion-detector.git
cd real-time-voice-emotion-detector

# Step 2: Install required packages
pip install -r requirements.txt

# Step 3: Launch the notebook
jupyter notebook notebooks/Emotion_Detection.ipynb

---

## 🧰 Tech Stack

- Python 3.9+
- scikit-learn
- librosa
- sounddevice
- matplotlib / seaborn
- pyttsx3 (for speech output)

---
📂 Folder Structure
bash
Copy code
📁 data/
 └── Audio_Speech_Actors_01-24/       # RAVDESS dataset
📁 models/
 └── emotion_model.pkl                # Trained model
 └── scaler.pkl                       # Scaler for normalization
📁 notebooks/
 └── Emotion_Detection.ipynb          # Main notebook
📄 README.md
📄 requirements.txt

