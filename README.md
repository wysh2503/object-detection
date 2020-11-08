# object-detection
Detect objects using pre-trained neural network

## Tracking object with OpenCV
Locating an object in successive frames of a video is called tracking. Usually tracking algorithms are faster than detection algorithms. When you are tracking an object that was detected in the previous frame, you know a lot about the appearance of the object.
For a good comparison of OpenCV Tracker Algorithms, read the following link:
https://ehsangazar.com/object-tracking-with-opencv-fd18ccdd7369

## Real-time Object Detection using SSD MobileNet V2
TensorFlow Model Zoo for Object Detection
The TensorFlow Model Zoo is a collection of pre-trained object detection architectures that have performed tremendously well on the COCO dataset.
The model architecture that I used in the code is SSD-mobileNet. MobileNet is an object detector released in 2017 as an efficient CNN architecture designed for mobile and embedded vision application. This architecture uses proven depth-wise separable convolutions to build lightweight deep neural networks.
