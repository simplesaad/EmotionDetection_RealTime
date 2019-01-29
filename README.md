# EmotionDetection_Realtime
This is a Python 3 based project to display facial expressions (happy, sad, anger, fear, disgust, surprise, neutral) by performing fast & accurate face detection with OpenCV using a pre-trained deep learning face detector model shipped with the library.

The model is trained on the **FER-2013** dataset which was published on International Conference on Machine Learning (ICML). This dataset consists of 35887 grayscale, 48x48 sized face images with seven emotions - angry, disgusted, fearful, happy, neutral, sad and surprised.

## Dependencies

1. Python 3.x, OpenCV 3 or 4, Tensorflow, TFlearn, Keras
2. Open terminal and enter the file path to the desired directory and install the following libraries
   * ``` pip install numpy```
   * ``` pip install opencv-python```
   * ``` pip install tensorflow```
   * ``` pip install tflearn```
   * ``` pip install keras```
   
## Execution

1. Unzip the 'data.zip' file in the same location
2. Open terminal and enter the file path to the desired directory and paste the command given below
3. ``` python kerasmodel.py --mode display```
