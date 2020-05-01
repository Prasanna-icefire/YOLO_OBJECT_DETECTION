# YOLO_OBJECT_DETECTION
I have got this up by using tutorials from https://machinelearningspace.com/the-beginners-guide-to-implementing-yolo-v3-in-tensorflow-2-0-part-1/
All u need to do is git clone this repository,
Into the weights folder, download yolov3.weights from https://pjreddie.com/media/files/yolov3.weights
Having done this, execute the convert_weights.py
Having successfully done this,change the path of the weightfile in the video.py to yolov3.weights.....instructions mentioned in 
the instructions.txt
After this run the video.py to detect objects from the webcam
To change the sorce of deection,replace the o of the videocapture() with a link to the video enclosed in quotes.

Make sure you have tensorflow and opencv installed. I have used tensorflow 2.0
To run it with GPU support,easiest way to set things up would be to      conda install tensorflow-gpu

![](https://raw.githubusercontent.com/Prasanna-icefire/YOLO_OBJECT_DETECTION/master/Screenshot/Screenshot%20from%202020-05-01%2016-19-33.png)
