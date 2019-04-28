# Carla-Object-Detection-Dataset
Labeled Dataset for Object Detection in Carla Simulator

This dataset contains 1028 images each 640x380 pixel. The dataset is split into 208 test and 820 training examples.
Every image comes with an associated label .xml file in the pascal VOC format. The dataset was collected in Carla Simulator, driving around in autopilot mode in various environments (Town01, Town02, Town03, Town04, Town05) and saving every x frame. The labels where then automatically generated using the semantic segmentation information. 

Available classes are: 

* Vehicle (Car, Truck)
* Bike
* Motobike
* Traffic light
* Traffic sign

Example image:

![example image](https://github.com/DanielHfnr/Carla-Object-Detection-Dataset/blob/master/test/Town01_011940.png "Example Image from Dataset")

