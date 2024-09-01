<h1>AI Virtual Mouse Using OpenCV, Python, and Machine Learning</h1>   

<h2>Overview</h2>
This project demonstrates how to create an AI virtual mouse using computer vision and machine learning techniques powered by OpenCV and Python. The AI virtual mouse allows you to control the cursor on your computer screen through hand gestures captured by your webcam. It combines traditional computer vision methods with machine learning models for enhanced gesture recognition.

<h2>How It Works</h2>
<h3>1. Hand Detection:</h3> The webcam captures the video feed, and OpenCV along with MediaPipe is used to detect and track the hand in real-time.

<h3>2. Feature Extraction:</h3> Key landmarks of the hand are extracted as features to represent different gestures.

<h3>3. Machine Learning Model:</h3> A pre-trained machine learning model is used to classify these features into specific gestures.

<h3>4. Mouse Control:</h3> Based on the classified gestures, the cursor moves, clicks, or performs other actions using the PyAutoGUI library.
