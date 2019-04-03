# OCR-using-OpenCV-and-keras

Optical Character Recognition using Raspberry pi.

In this project, I have trained a deep convolutional neural network to transcribe digits. I have used the data from the learning stage to allow the Pi Camera to read and recognize digits. The AI pipeline will be implemented using Scikit and OpenCV 3.3 for image manipulation and Keras which uses TensorFlow as a back-end for the deep learning part.

To keep this easy no feature localization stage is done. We have to shove the image in front of the camera lens so that it's the only feature that it sees.

The MNIST dataset is used. 

I have done two things. First, train a network for recognizing digits. Then use the weights of the network that i trained for recognizing live camera feed digits taken from the Raspberry Pi camera.
