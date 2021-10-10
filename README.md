# Facial-Expression-Recognition-With-Keras
This deep learning based project takes the camera/web-cam images/videos to classify 7 different expressions: surprise, happy, sad, neutral, angry, disgust, fear.

Sample Output:

![Alt text](https://github.com/bidhanbaray/Facial-Expression-Recognition-With-Keras/blob/master/sample_output.jpg?raw=true "Title")


### Task 1: Introduction and Overview 
In this section the project introduction and final result is shown
### Task 2 : Explore the Dataset
The original dataset in "https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data" contains ".csv" files
but the dataset presented in the Coursera project is in image form. So another script was written to convert the csv file to respective labeled images mentioned 
in the last section of this page.
### Task 3: Generate Training and Validation Batches
Look at the jupyter noteook script "Facial_Expression_Training.ipynb"
### Task 4: Create a Convolutional Neural Network (CNN) Model
Look at the jupyter noteook script "Facial_Expression_Training.ipynb"
### Task 5: Train and Evaluate Model
Look at the jupyter noteook script "Facial_Expression_Training.ipynb"
### Task 6: Represent Model as JSON String
Look at the jupyter noteook script "Facial_Expression_Training.ipynb"
### Task 7: Create a Flask App to Serve Predictions
Look at "Camera.py" and "main.py". Getting video from webcam/other video, getting faces using openCV, adding boxes around the faces,
converting images to grayscales, rescaling them, sending them to the pretrained CNN model, getting results and showing them on a web page.
### Task 8: Design an HTML Template for the Flask App
Look at "templates/index.html"
### Task 9: Use Model to Recognize Facial Expressions in Videos
Run the main.py script and open localhost 0.0.0.0/5000 in the web browser

<h4>pxToImgConverter:</h4> 
<p>The dataset from kaggle: "https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data"</br>

The python file reads the 'train.csv' and creates images and places the in the respective folders named after the emotion category.</p>

Coursera Project: https://www.coursera.org/projects/facial-expression-recognition-keras
