# Drowsiness Detection 
 In this project I have customized the famous YOLO v5 model to accurately detect wheather the person is awake or drowsy using web cam
 
 In this project I have customized the famous YOLO v5 model that uses an object detection algorithm that divides images into a grid system and each grid is responsible for detecting objects within itself.  I have taken the dataset from my own webcam 20 images for each new classes that I have created namely, drowsy and awake. Then I have used labelImg framework to select out the important features from my face such as yawning, eyes etc. Then I have trained this model on Google Colab for nearly 100 epochs and then loaded it into YOLO v5 custom model. And finally I have used my web cam for real time drowsiness detection.
