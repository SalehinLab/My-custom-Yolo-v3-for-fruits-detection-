# My-custom-Yolo-v3-for-fruits-detection-
Computer Vision 
Spring 2023
Imrus Salehin



Object Detection
- Using Yolo-v3
- 3 Class (Apple , Banana , Graph)
- 400 data in each class 
- Using custom Model



**Custom Yolo-v3 config:

- convolutional 
filters=24

-yolo
classes=3

-learning_rate=0.001
burn_in=1000
max_batches = 6000
policy=steps
steps=3600,3800
scales=.1,.1


