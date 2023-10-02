# Face-Emotion-Recognition
Detection and Recognition of Human Facial Emotion using Neural Networks

In this project, we explored the world of human emotions through the lens of technology. Using the power of neural networks, we developed a system capable of detecting and understanding emotions displayed on people's faces. We performed the following:

* Capture a Photo: This step involves either using a webcam to capture a live image or selecting a local image file.
* Convert to Gray: The captured image is converted to grayscale to simplify the process of detecting a face within it.
* Detect the Face: Face detection is performed using the Open Source haarcascade_frontalface_default.xml, a popular face detection algorithm.
* Cut and Resize: After detecting the face, the image is cropped or cut to isolate the detected face, and it may be resized if needed.
* Predict Using the Pre-trained Model: The isolated face is then passed through a pre-trained model for further analysis or prediction.

We used various python libraries including OpenCV, Keras and ConvNet to train our model.
