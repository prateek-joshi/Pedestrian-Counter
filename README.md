# Pedestrian Counter using Tensorflow
<img width="333" alt="ped_count_ex" src="https://user-images.githubusercontent.com/70139937/128668500-fdb86a56-c655-44f9-80b1-25e93c63a217.png">
Count the number of pedestrians (people) using Tensorflow's object detection API. The model used for detection is a MobileNet SSD, obtained from tensorflow's object detection model zoo (https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md).
All training and detection was done on an IPython notebook using Google Colab.

The dataset can be found at: https://www.kaggle.com/karthika95/pedestrian-detection

## Description
1. *people_detection_training.ipynb* - notebook for training the images on the SSD model
2. *people_detection_in_images.ipynb* - notebook to detect in images
3. *generate_tfrecords.py* - script to generate TFRecords from the csv files, to increase training speed.
4. *xml_to_csv* - script to generate csv file of annotations from xml format.

## Usage
1. Upload the *xml_to_csv.py* and *generate_tfrecord.py* scripts to the scripts folder after its creation.
2. Train the model using the training notebook.
3. Detect on images in real-time using the *detect_images.ipynb* notebook.
