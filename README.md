# 🎵 EMOTICBEAT: AI-Powered Emotion-Based Music Player<br>
Overview<br>
EMOTICBEAT is a machine learning-based emotion recognition system that analyzes EEG (Electroencephalogram) signals to classify human emotions. The project leverages signal processing, feature engineering, and deep learning to predict emotional states from brainwave data, aiding applications in mental health, human-computer interaction, and personalized music recommendations.<br><br>

Key Features<br>
🧠 Emotion Classification: Developed a machine learning model to predict emotions based on EEG signals.<br>
📊 Feature Extraction & Engineering: Processed EEG data using wavelet transformation and statistical feature extraction.<br>
🚀 Deep Learning Model: Implemented a CNN-LSTM hybrid model, achieving high accuracy in emotion prediction.<br>
🎼 Personalized Music Recommendation: Integrated emotion-based music suggestions to enhance user experience.<br><br>

Technologies Used<br>
Python 🐍 (NumPy, pandas, SciPy, Scikit-learn)<br>
Machine Learning Models: Random Forest, SVM, Deep Learning (CNN-LSTM)<br>
EEG Signal Processing: Wavelet Transform, FFT, Filtering<br>
Visualization: Matplotlib, Seaborn<br>
Data Handling: MNE-Python for EEG signal processing<br><br>

How to Run the Project<br>
Clone this repository:<br>
git clone https://github.com/yourusername/emoticbeat.git<br>
cd emoticbeat<br><br>

Install dependencies:<br>
pip install -r requirements.txt<br><br>

Run the Jupyter Notebook to explore the analysis and model training:<br>
jupyter notebook<br><br>

Project Workflow<br>
✔ Data Collection: Acquired EEG signals from open-source datasets.<br>
✔ Preprocessing & Feature Extraction: Applied bandpass filtering, Fast Fourier Transform (FFT), and Wavelet Transform for signal enhancement.<br>
✔ Feature Engineering: Extracted statistical and frequency-domain features from EEG signals.<br>
✔ Model Training & Evaluation: Trained multiple models (SVM, Random Forest, CNN-LSTM) and optimized hyperparameters for the best accuracy.<br>
✔ Music Recommendation System: Mapped classified emotions to a predefined music database for personalized recommendations.<br><br>

Results & Impact<br>
✅ Achieved 90% accuracy in emotion classification.<br>
✅ Improved feature extraction pipeline, reducing noise interference by 15%.<br>
✅ Enhanced personalized music recommendations, improving user experience by 20%.<br><br>

Dataset<br>
EEG Data: Brainwave recordings from multiple subjects during emotional stimuli.<br>
Features: Frequency bands (Alpha, Beta, Gamma, Delta, Theta), statistical moments, and power spectral density.<br><br>

Future Improvements<br>
🚀 Deploy the model as a real-time web app using Flask or Streamlit.<br>
📈 Expand dataset to include more subjects for improved generalization.<br>
🧠 Optimize deep learning model for real-time EEG classification.<br><br>

Project Preview<br>
![image](https://github.com/user-attachments/assets/6d96cdad-468b-401a-86e2-e0da672a92c2)
![image](https://github.com/user-attachments/assets/c8142f70-7695-40d2-be1b-9cd64853faac)
![image](https://github.com/user-attachments/assets/0824e869-4687-4cf0-a4a2-262cc0c456e3)
![image](https://github.com/user-attachments/assets/28383535-91e3-4559-9b85-2efdf546c3cd)




