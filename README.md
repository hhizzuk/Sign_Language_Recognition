# Sign_Language_Recognition
Goal: Train an AI model to recognize sign language gestures and phrases for potential real-world applications like healthcare interpretation.

Tech stack: Python, TensorFlow, MediaPipe, OpenCV, Google Colab.

Method:

Collect gesture videos (e.g., "hello," "goodbye", "good", "bad").

Extract body/hand/face keypoints with MediaPipe.

Train an LSTM model on gesture sequences.

Evaluate with accuracy + confusion matrix.

Test on new videos for prediction.
