# Vehicle Tracking & Lane Detection
I've implemented the Vehicle Detection using Mask R-CNN and Computer Vision based Lane Detectionusing on Keras and TensorFlow.
The model detects vehicles in the image frame using segmentation masks with the pretrained weights trained on COCO dataset; the lane detection is done using sobel filter.

### Mask R-CNN output on a road scene:

Final Video GIF:

![](https://github.com/Aryan05/R_CNN-SelfDrivingCar/blob/master/output/ouput.gif)

### Land Identification output:

<img src="./input/test2.jpg" width = "300" height = "150" align=center />  <img src="./output/output_lane.png" width = "300" height = "150" align=center />

Final combined output:

<img src="./input/test6.jpg" width = "300" height = "150" align=center />  <img src="./output/output.png" width = "300" height = "150" align=center />

Download the pretrained weights [here](https://drive.google.com/open?id=1dNi9Ny1h9KBMj_3mocMQNapeEwgeERlz) and place it in the current working directory. Run main.py specifying the input image path. It can be applied with video files using moviepy and calling process_video() function.

### Project Made by- Aryan Karn
