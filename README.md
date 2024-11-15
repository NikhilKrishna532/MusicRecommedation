# 🎶🎬 Movie and Music Recommendation Using Emotion Detection

## 📝 Overview
This project combines **emotion detection** with **movie and music recommendations** to create a personalized entertainment experience. Using a CNN-based model, the system detects a user's emotional state in real-time via facial expressions and suggests movies or music that match the detected mood. Recommendations are delivered through a **Flask web interface** for easy and tailored content discovery.

---

## 🔥 Features
- **Emotion Detection**: Analyzes facial expressions to recognize emotions like 😊 Happy, 😢 Sad, 😡 Angry, and more.
- **Personalized Recommendations**: Suggests movies and music based on the detected emotion.
- **User Choice**: Allows users to select between movie or music recommendations.
- **Interactive Interface**: Built with Flask, providing a seamless user experience.

---

## 📊 Dataset
- **FER-2013 Dataset**: Contains grayscale facial images (48x48 pixels) categorized into seven emotions: Happy, Sad, Angry, Fear, Disgust, Surprise, and Neutral.

---

## 🏗️ Architecture

### CNN Model
1. **Input Layer**: Processes input images (48x48 pixels).
2. **Convolution Layer**: Extracts essential features.
3. **Pooling Layer**: Reduces dimensionality while retaining key features.
4. **Fully Connected Layer**: Maps extracted features to predicted emotions.
5. **Output Layer**: Identifies the user's current emotion.

### Flask Interface
- **Webpages**:
  - 🏠 Home Page
  - 🧑‍🤖 Emotion Detection
  - 🎥/🎶 Movie/Music Selection
  - 📝 Recommendation Display

---

## 🚀 Installation

### Prerequisites
- Python 3.9+
- Libraries: `NumPy`, `OpenCV`, `Keras`, `Flask`
# 📚 Usage Guide

## Access the Home Page 🏠
- The UI displays a welcoming screen to start the process.

## Emotion Detection 😄😢
- Grant webcam access to analyze emotions in real-time.
- The detected emotion is displayed on the screen.

## Select Preference 🎥 or 🎶
- Choose between "Movies" or "Music" recommendations.

## Receive Recommendations 📜
- View movies or music matching the detected emotion.

---

# 🔍 Experimental Results

- **Model Accuracy**: Achieved 73.86% accuracy with CNN.
- **Validation**: Metrics like train/validation accuracy and confusion matrices confirm model reliability.

---

# 🌐 Future Enhancements

- Expand emotion categories to include:
  - 😠 Disgust
  - 😨 Fear
- Implement a database to store user preferences for improved personalization.
- Integrate with streaming platforms like Spotify or Netflix for direct content access.

---

# 🏆 Conclusion

This project connects emotion recognition with personalized recommendations, providing users with a time-saving, personalized way to discover content. As technology advances, this solution has the potential to transform the entertainment industry by enhancing user engagement and satisfaction.
