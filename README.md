# 🎵 Emotion Based Music Recommendation System

This project is an AI-powered music recommendation system that detects a user's facial emotion in real time and recommends songs based on their mood.

The system uses a Convolutional Neural Network (CNN) to recognize facial expressions through a webcam and maps the detected emotion to suitable music from a curated dataset.

---

## 🚀 Features
- Real-time facial emotion detection using webcam  
- CNN-based emotion classification  
- Music recommendation based on detected emotion  
- Interactive web interface built with Streamlit  
- Clickable song links that redirect to music platforms  

---

## 🧠 Technologies Used
- Python  
- TensorFlow & Keras (CNN model)  
- OpenCV (Face detection)  
- Streamlit (Web interface)  
- Pandas & NumPy (Data processing)  

---

## 📂 Dataset
- Music dataset: `muse_v3.csv`  
- Contains track names, artist names, emotional and valence tags, and music links  

---

## 🧪 How It Works
1. Webcam captures the user's face  
2. OpenCV detects the face  
3. CNN model predicts the emotion (Happy, Sad, Angry, Neutral, etc.)  
4. Based on emotion, suitable songs are selected from the dataset  
5. Songs are displayed with clickable links  

---

## 📊 Emotion Classes Supported
The CNN model recognizes the following emotions:
- Angry  
- Disgusted  
- Fearful  
- Happy  
- Neutral  
- Sad  
- Surprised  

These emotions are used to select music that best matches the user's mood.

---

## 🧬 Model Architecture
The facial emotion recognition system is built using a deep CNN architecture that includes:
- Convolutional layers for feature extraction  
- MaxPooling layers for spatial reduction  
- Dropout layers to avoid overfitting  
- Fully connected Dense layers  
- Softmax output layer for multi-class emotion prediction  

The model takes a **48×48 grayscale face image** as input.

---

## 🖥️ User Interface
The UI is developed using **Streamlit**, providing:
- A clean web interface  
- One-click emotion scanning  
- Real-time AI processing  
- Clickable music recommendations

---

## 🔮 Future Enhancements
- Spotify / YouTube API integration  
- User login and history tracking  
- Playlist generation  
- Mobile application support  
- Multi-face emotion detection 

---

## 👨‍💻 Author
**Gunti Hemanth Kumar**  
Final Year Computer Science Student  
AI & Machine Learning Enthusiast  

---

⭐ If you like this project, consider giving it a star on GitHub!



