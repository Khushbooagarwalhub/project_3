# project_3
# Human Action Recognition (HAR)
Topic -
Machine Learning techniques in sensor based human activity recognition and understanding human actions using still images.
## Sensor-Based HAR
Data source for sensor based HAR - WISDM dataset

http://www.cis.fordham.edu/wisdm/dataset.php

The source consist of raw time series data and transformed dataset.
The raw timeseries data consist of -
Raw time series data 
Number of examples 
1,098,207
Number of attributes – 6
Class Distribution
Walking: 424,400 (38.6%)
Jogging: 342,177 (31.2%)
Upstairs: 122,869 (11.2%)
Downstairs: 100,427 (9.1%)
Sitting: 59,939 (5.5%)
Standing: 48,395 (4.4%)
Contains all x,y,z  acceleration values 

The reformatted dataset is formed by statistical measures taking 10 second window with 46 transformed attributes in it



## Image-Based HAR
Transfer learning techniques were used to build an image classification model that recognizes various classes of human activity. 
The model was trained on images from the Stanford 40 dataset. You can find out more information about the data 
<a href="http://vision.stanford.edu/Datasets/40actions.html" target="_blank">here</a>.<br>
<img src="Image Classification\Output\plots\image.png"><br>
We used a only a portion of the full dataset, training on images from
the following ten action classes.<br>
### Classes
- Applauding
- Climbing
- Cooking
- Feeding a horse
- Holding an umbrella
- Jumping
- Playing guitar
- Riding a bike
- Riding a horse
- Walking the dog
The resulting model achieved a classification accuracy of 96%. 
