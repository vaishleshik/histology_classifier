# histology_classifier
A machine learning model to label histologic images

Okay this is a little ambitious. We want to develop something which can have a look at a histologic section and tell which tissue it is (skin/ liver/ lung/ kidney etc).

## Training data

Training data is in the folder data_chec_resized (in Gdrive), segregated in separate folders (Liver, Lung etc). All images resized to 256 x 192 px. A jupyter notebook is also in the folder. I have began experimenting with keras. The 'pool' folder contains all the images together (as backup). The 'dat.csv' file has imae filenames with labels.

https://drive.google.com/open?id=1poViDl_vARIi2tfjhuhyMURYjr9_87KI 

## Objective

Come up with a machine learning model (whatever you prefer) which can perform with 70% accuracy on this same training data.
