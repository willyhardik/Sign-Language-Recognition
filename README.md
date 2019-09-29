Problem statement:-
We have developed Android App for Sign Language Recognition. The app has an camera frame that would capture image and predict the image.

Model development:-
The model is built on Keras Library. Using the CNN Layers(Conv2d,  Maxpooling ), Then one fully connected layers after Flatten.
The Google colab notebook link https://colab.research.google.com/drive/1ORq0MmADxuXFIxINXUnLFYKkU9zVtL-j .

The model is built as .h5 file. To use it in android we need to convert it in tflite file.

Android App has tensorflowInterpreter library to use the tflite file for predictions in java. 

Here are some of the output screen shots from the application. The larger screen is the camera view. The relatively smaller one is the captured image with the predictions shown beside the image.

<img src="https://github.com/willyhardik/Sign-Language-Recognition/blob/master/Screenshot_2019-04-24-11-49-37-045_com.amitshekhar.tflite.png" height="500" width="250">


<img src="https://github.com/willyhardik/Sign-Language-Recognition/blob/master/Screenshot_2019-04-24-11-50-46-425_com.amitshekhar.tflite.png" height="500" width="250">
