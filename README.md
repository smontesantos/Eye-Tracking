











## Eye Tracking

### Introduction

The repository contains three data folders:
* `data/open/train`
* `data/open/test`
* `data/close`


In those three folders, are present images of eyes, either opened or closed. We will create the following: 
Each folder contains a set of 480, 81 and 346 images respectively, all with dimensions (260, 400).
The first two folders also contain two .csv files (dataPupilCenterTrain.csv, dataPupilCenterTest.csv) containing
information on the open eye center coordinates.

### Task 1: Classfication
* Classification: make a classifier that predicts if the eye is opened or closed

### Task 2: Regression
* Regression: make a regression that predicts the center of the pupil using the target values into the file `data/open/dataPupilCenter.csv`


Both models can then become a part of a more complex YOLO eye detector.


