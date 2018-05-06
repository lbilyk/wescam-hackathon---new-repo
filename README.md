This project is intended to utilize object detection machine learning to interpret american sign language
and display the interpretation in real time on the capture screen.

The official pre-build tensorflow neural network model was used as a basis, and further adapted to work with sign language detection.

Datasets which include hundreds of images of sign language gestures are used from loicmarie's Github library.

Screen captures uses opencv to capture frames, transform them, and pass them to the neural network function.


Edge detection code was not implemented but could be used to potentially increase accuracy.




EXCLUDED FROM UPLOAD:
Dataset files (~75000 files for training)
Tensorboard Logging Data (too large to upload)

Created by: Ferencz Dominguez, Lu Bilyk, Nik Kershaw, Peter Socha
Last Edited: May 6 2018, 10:57AM