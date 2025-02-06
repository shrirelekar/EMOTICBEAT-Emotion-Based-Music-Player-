# EMOTICBEAT: AI-Powered Emotion-Based Music Player<br><br>
EMOTICBEAT is an emotion-based music recommendation system designed to enhance your music listening experience. By analyzing facial expressions through a webcam, EMOTICBEAT detects the user’s emotional state and selects music that matches or uplifts their mood, eliminating the need for manual playlist curation.<br><br>

Project Overview<br>
Music has the power to influence our emotions, and EMOTICBEAT takes this to the next level. By capturing real-time facial expressions, it can detect one of seven emotions—Angry, Disgust, Fear, Happy, Sad, Surprise, or Neutral—and generate a mood-matching playlist. This application can be especially valuable in environments such as hospitals, clinics, or public spaces where influencing a positive atmosphere is beneficial.<br><br>

Features<br>
Emotion Recognition: Uses a combination of the Haar Cascade and FER (Facial Emotion Recognition) algorithms to accurately classify facial expressions.<br>
Music Recommendation: Automatically curates a playlist based on detected emotions.<br>
User-Friendly Interface: A simple, clean interface built using HTML, CSS, and JavaScript.<br>
Backend with Flask: The backend is developed with Flask for a seamless web experience.<br>
Machine Learning Models: Utilizes TensorFlow and Keras for real-time emotion recognition.<br><br>

Technologies and Tools<br>
Frontend: HTML, CSS, JavaScript, and Bootstrap for a responsive and accessible design.<br>
Backend: Flask, a micro web framework, for handling web requests and managing the recommendation engine.<br>
Machine Learning Framework: TensorFlow and Keras for emotion detection.<br>
Image Processing: OpenCV library is used to process facial images captured through a webcam.<br>
Development Environment: PyCharm IDE with Python 3.<br><br>

How It Works<br>
Facial Emotion Detection: EMOTICBEAT accesses the webcam, captures the user's facial expressions, and processes the image using OpenCV and the FER model to detect emotion.<br>
Music Recommendation: Based on the identified emotion, the system selects and plays songs that are likely to resonate with the user’s mood.<br>
Real-Time Interaction: Users can seamlessly interact with the system, which continuously updates the music selection based on changing facial expressions.<br><br>

Usage<br>
Launch the application and ensure your webcam is active.<br>
Click "Start" on the main page to allow EMOTICBEAT to begin analyzing your facial expressions.<br>
Enjoy an automatically curated playlist that evolves based on your mood!<br><br>

Future Enhancements<br>
Mobile Application: Expansion to mobile platforms like Android or iOS for a broader reach.<br>
Advanced Emotion Recognition: Development of a mixed-mood recognition system to handle complex emotional states.<br>
Healthcare Applications: Further research into music therapy applications, particularly in mental health.<br><br>

Contributing<br>
Contributions are welcome! Feel free to submit a pull request or open an issue for any improvements.<br><br>

Acknowledgments<br>
Special thanks to the resources and datasets used, including FER datasets from Kaggle, TensorFlow, and OpenCV documentation.<br><br>

Preview<br>
![image](https://github.com/user-attachments/assets/6d96cdad-468b-401a-86e2-e0da672a92c2)
![image](https://github.com/user-attachments/assets/c8142f70-7695-40d2-be1b-9cd64853faac)
![image](https://github.com/user-attachments/assets/0824e869-4687-4cf0-a4a2-262cc0c456e3)
![image](https://github.com/user-attachments/assets/28383535-91e3-4559-9b85-2efdf546c3cd)




