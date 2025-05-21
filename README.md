This project aims to create a real-time sign language detection system that recognizes hand gestures and translates them into readable alphabets or words. It uses a combination of MediaPipe for real-time hand tracking, deep learning for gesture classification, and OpenCV for live video handling and visualization.


How the Model Works

Input: Sequence of 30 frames (time-series data of keypoints).

Model: A sequential deep learning model (CNN based) trained to classify gestures.
![Screenshot (239)](https://github.com/user-attachments/assets/8b639842-a9cf-4179-916d-c88518925550)
![Screenshot (233)](https://github.com/user-attachments/assets/8f18ec5c-7404-4f92-88c9-3a769dce55da)
![Screenshot (228)](https://github.com/user-attachments/assets/8ed0dd33-271b-4714-a7f4-f6075f680dec)


Output: Probability distribution over gesture labels.

