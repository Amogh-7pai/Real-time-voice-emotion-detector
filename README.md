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

## 📦 Requirements
- Python 3.9+
- numpy
- pandas
- scikit-learn
- librosa
- sounddevice
- matplotlib
- seaborn
- joblib
- pyttsx3

---

## ✅ Results

- Accuracy (Random Forest): **~65–75%** depending on parameter tuning
- Real-time predictions may vary due to microphone quality and ambient noise
- The model was trained on RAVDESS dataset, which contains acted emotions — this limits real-world generalization
- Improvements were made using audio normalization and feature tuning

---

## 🔮 Future Enhancements

- Train using your own voice samples for better real-time accuracy
- Add Streamlit app for interactive web-based prediction
- Integrate deep learning models like Wav2Vec2 for higher generalization

---


