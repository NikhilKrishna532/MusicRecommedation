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

![image](https://github.com/user-attachments/assets/a7c8164d-d433-44b7-9fc1-91894f83bcb1)


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
  ![image](https://github.com/user-attachments/assets/cc49390a-c27b-4cfe-9be2-4dc6a0ef7cc2)



## Emotion Detection 😄😢
- Grant webcam access to analyze emotions in real-time.
- The detected emotion is displayed on the screen.
  ![image](https://github.com/user-attachments/assets/b11e9abb-d4cc-4d64-97f1-1946cb1280a5)

  

## Select Preference 🎥 or 🎶
- Choose between "Movies" or "Music" recommendations.
  ![image](https://github.com/user-attachments/assets/f2a21607-68d2-4af7-8ce2-3323cadaaf89)


## Receive Recommendations 📜
- View movies or music matching the detected emotion.
  ![image](https://github.com/user-attachments/assets/19e75746-4319-43a1-aad1-a6cd3170442f)

  ![image](https://github.com/user-attachments/assets/db92fda1-3f91-46ff-9106-8fef356256ea)



---

# 🔍 Experimental Results

- **Model Accuracy**: Achieved 73.86% and 50.94% accuracy with CNN and MobileNetV2.
- **Validation**: Metrics like train/validation accuracy and confusion matrices confirm model reliability.

![image](https://github.com/user-attachments/assets/c97e296e-df0a-4c96-8d31-7366c0643cc2)



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
