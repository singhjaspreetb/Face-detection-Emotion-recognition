# Face-detection-Emotion-recognition
Emotion Detection — Classifying the emotion on the face as happy, angry, sad, neutral, surprise, disgust or fear.

1. Download Python
https://www.python.org/downloads/release/python-386/

2. Add it to path
C:\Users\upadh\AppData\Local\Programs\Python\Python38\Scripts\

3. Open Command Window by pressing Windows key, then type “cmd” 
(Right Click on
“Command Prompt” and select “Run as Administrator”)

pip install cmake

pip install dlib

Install “tensorflow” library

pip install tensorflow

Install “tensorflow-cpu” library

pip install tensorflow-cpu

Install “matplotlib” library


pip install matplotlib

Install “deepface” library

pip install deepface



4. Just open your python and type the first command

from deepface import DeepFace



from deepface import DeepFace

from PIL import Image

import cv2

import matplotlib.pyplot as plt

img_path =r'#your img path '

img = cv2.imread(img_path)

plt.imshow(img[:, :, ::-1])

image = Image.open(img_path)

image.show()

demography = DeepFace.analyze(img_path)

print("Age: ", demography["age"])

print("Gender: ", demography["gender"])

print("Emotion: ", demography["dominant_emotion"])

print("Race: ", demography["dominant_race"])

Regards-Jaspreet Singh
