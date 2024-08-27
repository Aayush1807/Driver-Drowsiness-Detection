# Driver-Drowsiness-Detection
 Built a drowsiness detection system that will detect if a person’s eyes are closed for a few seconds and will alert them when drowsiness is detected. In orderto prevent accidents that are caused by drivers who fell asleep while driving.
 
# Project Prerequisites
The requirement for this Python project is a webcam through which we will capture images. You need to have Python(Updated version recommended) installed on your system, then using pip, you can install the necessary packages.
1.OpenCV – pip install opencv-python (face and eye detection).
2.TensorFlow – pip install tensorflow (keras uses TensorFlow as backend).
3.Keras – pip install keras (to build our classification model).
4.Pygame – pip install pygame (to play alarm sound).

# Steps for Performing Driver Drowsiness Detection
Step 1 – Take Image as Input from a Camera
Step 2 – Detect Face in the Image and Create a Region of Interest (ROI)
Step 3 – Detect the eyes from ROI and feed it to the classifier
Step 4 – Classifier will Categorize whether Eyes are Open or Closed
Step 5 – Calculate Score to Check whether Person is Drowsy
