# tf2_ssd_mb2_dataset_prep_scripts
This repository is a collection of Python scripts for converting PASCAL VOC annotations to TFRecords. I do not own all the codes and some of them were based from tutorials on using TF2 object detection API. The scripts require installation of Object Detection API of TensorFlow2 found in https://github.com/tensorflow/models/tree/master/research/object_detection

# Instructions
1. Use xml2csv.py to create *.csv files of each dataset group (train, val, and test) from PASCAL VOC annotations.
2. Use generateTFRecords.py to generate TFRecords (*.record) from the csv files.
3. label_map.pbtext is just a sample file to create the pbtext label file.