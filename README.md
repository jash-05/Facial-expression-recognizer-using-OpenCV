# Facial-expression-recognizer-using-OpenCV

## Description:

This project implements the Haar Feature-Based Cascaded Classifier as a part of the OpenCV framwework in order to use real time image processing to detect the facial expression on the subject's face and classify it into one of seven softmax outputs. The detected facial expression will be one of Happy, Angry, Surpised, Fearful, Sad, Disgusted or Neutral. 

## Dependencies:

* Python (>3.6)
* OpenCV
* Tflearn

pip install opencv-python
pip install tflearn

## Steps to implement

1. Download and extract the pre trained models from [this link](https://drive.google.com/open?id=1TkV3FWR215ArsY_YOHlnEOMci921SSRF), and extract and paste the Data folder into the main working directory.
2. Run python em_model.py singleface, in order to detect expressions in a single face
3. Run python em_model.py multiface, in order to detect expressions in multiple faces at the same time. 

## Output samples

Happy:
<br>
<img src="https://github.com/jash-05/Facial-expression-recognizer-using-OpenCV/blob/master/output%20samples/happy.png?raw=true" alt="Happy face" width="255"/>

Angry:
<br>
<img src="https://github.com/jash-05/Facial-expression-recognizer-using-OpenCV/blob/master/output%20samples/angry.png?raw=true" alt="Angry face" width="255"/>

Disgusted:
<br>
<img src="https://github.com/jash-05/Facial-expression-recognizer-using-OpenCV/blob/master/output%20samples/disgusted.png?raw=true" alt="Disgusted face" width="255"/>
