# tf2_ssd_mb2_dataset_prep_scripts
Python scripts for converting PASCAL VOC annotations to TFRecords. The scripts requires intallation of Object Detection API of TensorFlow2 found in https://github.com/tensorflow/models/tree/master/research/object_detection

# Instructions
1. Use xml2csv.py to create *.csv files of each dataset group (train, val, and test) from PASCAL VOC annotations.
2. Use generateTFRecords.py to generate TFRecords (*.record) from the csv files.
3. label_map.pbtext is just a sample file to create the pbtext label file.