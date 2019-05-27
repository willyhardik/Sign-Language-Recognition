Problem statement:-
We have developed Android App for Sign Language Recognition. The app has an camera frame that would capture image and predict the image.

Model development:-
The model is built on Keras Library. Using the CNN Layers(Conv2d,  Maxpooling ), Then one fully connected layers after Flatten.
The Google colab notebook link https://colab.research.google.com/drive/1ORq0MmADxuXFIxINXUnLFYKkU9zVtL-j

The model is built as .h5 file. To use it in android we need to convert it in tflite file

Android App has tensorflowInterpreter library to use the tflite file for predictions in java 
