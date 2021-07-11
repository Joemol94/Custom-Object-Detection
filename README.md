# Custom-Object-Detection

Data Preparation.ipynb - An important step as it demonstrates the process of preparing
the dataset in ‘.csv’ file format which helps in creating TFRecords.

train.csv, test.csv - Output files of Datapreparation.ipynb

generate_tfrecord.py - provided by Tensorflow documentation, it converts pascal_voc format of the CSV file to TFRecords 

labelmap.txt - contains the encodings of the dataset classes (i.e, license_plate)

train.record, test.record - generated with the help csv files using the generate_tfrecord python script


