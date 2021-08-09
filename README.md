# Pedestrian Counter using Tensorflow
<img width="333" alt="ped_count_ex" src="https://user-images.githubusercontent.com/70139937/128668500-fdb86a56-c655-44f9-80b1-25e93c63a217.png">
Count the number of pedestrians (people) using Tensorflow's object detection API. The model used for detection is a MobileNet SSD, obtained from tensorflow's object detection model zoo.
All training and detection was done on an IPython notebook using Google Colab.

## Description
1. 

## Usage
1. Upload the *xml_to_csv.py* and *generate_tfrecord.py* scripts to the scripts folder after its creation.
2. Train the model using the training notebook.
3. Detect on images in real-time using the *detect_images.ipynb* notebook.
