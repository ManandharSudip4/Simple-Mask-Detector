# Simple-Mask-Detector
A Simple Mask Detector using YoloV3

## Environment  
Python Version : 3.10.5

## Requirements  
All the requirements are included in requirements.txt

## Instructions

### 1. Clone the repo:
> git clone https://github.com/ManandharSudip4/Simple-Mask-Detector.git

### 2. cd into cloned directory

### 3. Install python packages:
> pip install -r requirements.txt

### 4. Run the either test_on_video.py or Test_working_batch_photos.py:
> python test_on_video.py  
>python Test_working_batch_photos.py


## Note:
yolov3_training_last.weights is not added because of large file size, so you may encounter an error, to solve that error you need to train a model running following file using your own dataset.

> YoloV3_Trainning.ipynb

After training a model you will get yolov3_training_last.weights file should be copied to cloned directory. 