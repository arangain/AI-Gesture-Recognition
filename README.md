Note: Followed along with educational content from Nicholas Renotte

Gesture Recognition in React with TensorFlow and Fingerpose

Overview
- This project demonstrates how to implement gesture recognition in a web application using React, TensorFlow's Handpose model, and the Fingerpose library. 

Key Features:
- Real-time Gesture Recognition: Detects hand gestures in real-time using the user's webcam.
- Dynamic Feedback: Displays emojis on the screen corresponding to recognized gestures such as 'thumbs up' and 'victory'.
- Interactive Interface: Utilizes a canvas overlaid with the webcam feed to draw the detected hand positions and gestures.

**How It Works**
1. Setup and Imports:
- The application imports necessary libraries and sets up React components.
- TensorFlow and Fingerpose libraries are used for hand detection and gesture recognition.
2. Webcam and Canvas Configuration:
- A webcam component captures video input.
- A canvas component is used to draw the output from the gesture recognition model.
3. State Management:
- React's useState is used to manage the state of detected gestures and corresponding images.
4. Model Integration and Gesture Detection:
- The Handpose model is loaded and run continuously to process frames from the webcam.
- Detected hand landmarks are analyzed by Fingerpose to recognize gestures.
- The application updates based on the gesture with the highest confidence score.
5. User Interface:
- Detected gestures are visualized by displaying emoji images corresponding to the recognized gestures.
