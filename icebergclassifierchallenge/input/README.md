# Data Description

In this competition, you will predict whether an image contains a ship or an iceberg. The labels are provided by human experts and geographic knowledge on the target. All the images are 75x75 images with two bands.

## Data fields
**train.json, test.json**

The data (train.json, test.json) is presented in json format. The files consist of a list of images, and for each image, you can find the following fields:

-id - the id of the image
-band_1, band_2 - the flattened image data. Each band has 75x75 pixel values in the list, so the list has 5625 elements. Note that these values are not the normal non-negative integers in image files since they have physical meanings - these are float numbers with unit being dB. Band 1 and Band 2 are signals characterized by radar backscatter produced from different polarizations at a particular incidence angle. The polarizations correspond to HH (transmit/receive horizontally) and HV (transmit horizontally and receive vertically). More background on the satellite imagery can be found here.
inc_angle - the incidence angle of which the image was taken. Note that this field has missing data marked as "na", and those images with "na" incidence angles are all in the training data to prevent leakage.
-is_iceberg - the target variable, set to 1 if it is an iceberg, and 0 if it is a ship. This field only exists in train.json.
Please note that we have included machine-generated images in the test set to prevent hand labeling. They are excluded in scoring.

## sample_submission.csv

The submission file in the correct format:

-id - the id of the image
-is_iceberg - your predicted probability that this image is iceberg.