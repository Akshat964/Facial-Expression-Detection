# Facial-Expression-Detection
Facial Expression Detection 🎭
This project is a real-time facial expression recognition system built with OpenCV and TensorFlow/Keras.
It detects a person’s face using Haar cascades and classifies emotions such as Angry, Fear, Happy, Neutral, Sad, and Surprise using a trained CNN model (Emotion_little_vgg.keras).

📌 Features
Real-time face detection via webcam
Emotion classification into 6 categories
Displays bounding boxes and emotion labels on detected faces
Simple and lightweight implementation

🛠️ Requirements
Make sure you have the following installed:
pip install tensorflow keras opencv-python numpy

📂 Project Structure
├── hello/
│   ├── haarcascade_frontalface_default.xml   # Pretrained Haar Cascade for face detection
│   ├── Emotion_little_vgg.keras              # Pretrained CNN model for emotion recognition
├── emotion_detector.py                       # Main script

▶️ Usage
Run the script to start the webcam emotion detector:
python emotion_detector.py
Press q to exit the program.

🧠 Model Information
The model used is based on a LittleVGG CNN architecture, trained on the FER-2013 dataset.
Output classes:
Angry 😠
Fear 😨
Happy 😃
Neutral 😐
Sad 😢
Surprise 😲

🖼️ Demo
When you run the program, you will see a live webcam feed with detected faces and predicted emotions:
[ Face Detected ] → Label displayed above the bounding box

⚠️ Notes
Ensure your webcam is connected and accessible.
Lighting conditions affect accuracy.
You can retrain the model on your own dataset for better results.

📜 License
This project is for educational and research purposes. You are free to use and modify it.
