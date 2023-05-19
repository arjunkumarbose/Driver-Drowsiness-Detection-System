# Driver-Drowsiness-Detection-System-using-Image-Processing-Machine-Learning-and-Arduino-UNO
## Project Objectives
• Our main goal is to detect driver drowsiness using facial features with the help of computer vision, image processing and machine learning.

• Features such as eye closure, blinking frequency, yawning,and head-nodding can be used to detect drowsiness. We are working with only eye state feature.

• Our modified transfer learning model will predict the eye state and the based on the result of eye state the Arduino based alert system will show the output and alert the driver.

## Dataset
In order to train our machine learning CNN model, we need to choose a dataset with enough numbers of data. In this project, MRL eye dataset is used [15]. This dataset has extensive collection of images of human eyes. This dataset includes low- and high-resolution infrared photos that were all taken under varied lightning situations and with various equipment. Testing various features or trainable classifiers is appropriate for this dataset. The photographs are separated into numerous categories to make it easier to compare methods, and this also makes them excellent for developing and testing classifiers.
This dataset is consisting images of 37 candidates, among them 33 men and 4 women. All the images are open eyes or closed eyes image. There are total number of 84,898 images of close and open eyes. We split the data 80% for training and validation other 20% for testing and evaluating the model. From the 80% of training and validation 20% data were used for validating and rest used for training the model.
