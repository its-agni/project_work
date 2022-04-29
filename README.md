# Real-Time Hand Gesture Recognition using Mediapipe & LSTM

This is a Streamlit web application and to run the app in your local system(localhost) follow the following steps:
- Download the zip folder for the code and navigate to the target directory using terminal/command prompt (If you have vs code you can also use the integreted terminal to perform the following commands).
- Install the packages according to the configuration file requirements.txt
```sh
$ pip install -r requirements.txt
```
- After successfully installing the dependencies, Run the app.py file using the following command:
```sh
$ streamlit run app.py
```

## Features
The dataset for our model training could be find here https://drive.google.com/drive/folders/1_TV-483bzqS-YFwNZI5Xf-hoI2CIttXz?usp=sharing
The model is trained on the following 10 ASL(American Sign Language) gestures:
- Hello
- Thanks
- I Love You
- Stop
- Please
- Walk
- Argue
- Yes
- See
- Good

## Run ipynb file
 If you have jupyter notebook you can run the appRaw.ipnyb file:
 > Go to Cell --> Run All
 
 A camera window will open with a more elaborate prediction interface, Press 'Q' on your keyboard to exit the window.
 The ipynb file will not be able to run on google colab as our app uses the open cv to open the camera which is not supported by colab.
