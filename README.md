# Sign Language Detector

The **Sign Language Detector** is a real-time machine learning and computer vision project developed to bridge the communication gap between hearing and speech-impaired individuals and people who do not understand sign language. Communication is an essential part of everyday life, yet many individuals who rely on sign language face challenges in education, workplaces, healthcare, and social interactions due to the lack of accessible translation tools. This project provides a practical, affordable, and user-friendly solution by translating hand gestures into text and speech using a standard webcam, eliminating the need for expensive sensors or specialized hardware.

The system uses **MediaPipe** to detect and track hand movements in real time by extracting 21 hand landmark points. These landmarks are converted into numerical feature vectors, preprocessed, and passed to a trained **Machine Learning model** for gesture classification. Once a gesture is recognized, the corresponding text is displayed on a **Flask-based web application**, while the **Web Speech API** converts the recognized text into speech, enabling smooth and interactive communication.

The project is designed with a focus on real-time performance, accuracy, and ease of use. It supports continuous gesture recognition with minimal processing delay, making it suitable for practical day-to-day communication. The system performs effectively under normal lighting conditions and demonstrates improved recognition accuracy as the training dataset grows. Its lightweight architecture allows it to run on standard computers equipped with a webcam, making it accessible to a wider audience.

 **Key Features**

* Real-time hand gesture detection using a webcam
* Hand landmark extraction using MediaPipe
* Machine Learning-based gesture recognition
* Instant conversion of gestures into text
* Text-to-speech functionality using the Web Speech API
* Interactive Flask web interface
* Low-cost solution requiring no specialized hardware
* User-friendly design with continuous gesture recognition

### Technologies Used

* Python
* Flask
* MediaPipe
* OpenCV
* Scikit-learn
* HTML, CSS, JavaScript
* Web Speech API

This project demonstrates how Artificial Intelligence, Machine Learning, and Computer Vision can be combined to create an inclusive communication tool that enhances accessibility for the deaf and mute community. Future enhancements include supporting larger sign language vocabularies, multiple regional and international sign languages, deep learning models for improved accuracy, facial expression recognition, mobile application deployment, multilingual translation, offline speech generation, and better performance under challenging lighting conditions.
