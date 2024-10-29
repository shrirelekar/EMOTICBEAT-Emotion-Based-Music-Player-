EMOTICBEAT

EMOTICBEAT is an emotion-based music recommendation system designed to enhance your music listening experience. By analyzing facial expressions through a webcam, EMOTICBEAT detects the user’s emotional state and selects music that matches or uplifts their mood, eliminating the need for manual playlist curation.

Project Overview
Music has the power to influence our emotions, and EMOTICBEAT takes this to the next level. By capturing real-time facial expressions, it can detect one of seven emotions—Angry, Disgust, Fear, Happy, Sad, Surprise, or Neutral—and generate a mood-matching playlist. This application can be especially valuable in environments such as hospitals, clinics, or public spaces where influencing a positive atmosphere is beneficial.

Features<br>
Emotion Recognition: Uses a combination of the Haar Cascade and FER (Facial Emotion Recognition) algorithms to accurately classify facial expressions.
Music Recommendation: Automatically curates a playlist based on detected emotions.
User-Friendly Interface: A simple, clean interface built using HTML, CSS, and JavaScript.
Backend with Flask: The backend is developed with Flask for a seamless web experience.
Machine Learning Models: Utilizes TensorFlow and Keras for real-time emotion recognition.

Technologies and Tools
Frontend: HTML, CSS, JavaScript, and Bootstrap for a responsive and accessible design.
Backend: Flask, a micro web framework, for handling web requests and managing the recommendation engine.
Machine Learning Framework: TensorFlow and Keras for emotion detection.
Image Processing: OpenCV library is used to process facial images captured through a webcam.
Development Environment: PyCharm IDE with Python 3.

How It Works
Facial Emotion Detection: EMOTICBEAT accesses the webcam, captures the user's facial expressions, and processes the image using OpenCV and the FER model to detect emotion.
Music Recommendation: Based on the identified emotion, the system selects and plays songs that are likely to resonate with the user’s mood.
Real-Time Interaction: Users can seamlessly interact with the system, which continuously updates the music selection based on changing facial expressions.

Usage
Launch the application and ensure your webcam is active.
Click "Start" on the main page to allow EMOTICBEAT to begin analyzing your facial expressions.
Enjoy an automatically curated playlist that evolves based on your mood!

Future Enhancements
Mobile Application: Expansion to mobile platforms like Android or iOS for a broader reach.
Advanced Emotion Recognition: Development of a mixed-mood recognition system to handle complex emotional states.
Healthcare Applications: Further research into music therapy applications, particularly in mental health.
Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for any improvements.

License
This project is licensed under the MIT License.

Acknowledgments
Special thanks to the resources and datasets used, including FER datasets from Kaggle, TensorFlow, and OpenCV documentation.
