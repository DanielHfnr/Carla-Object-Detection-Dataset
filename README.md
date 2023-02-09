# Carla-Object-Detection-Dataset

**Labeled Dataset for Object Detection in Carla Simulator**

This dataset contains 1028 images each 640x380 pixel. The dataset is split into 249 test and 779 training examples.
Every image comes with an associated label .xml file in the pascal VOC format (`labels` folder), in the yolo format (`labels_yolo_format`) as well as annotations in the MS COCO format (`annotations` folder) as a json file. The dataset was collected in Carla Simulator, driving around in autopilot mode in various environments (Town01, Town02, Town03, Town04, Town05) and saving every x-th frame. The labels where then automatically generated using the semantic segmentation information.

**Available classes are:**

* Vehicle (Car, Truck)
* Bike
* Motobike
* Traffic light
* Traffic sign

**Example image:**

![example image](/images/train/Town01_011940.png "Example Image from Dataset")

## Changelog

### 2023-01-06

#### Changed

* Restructured dataset
  * Changed train/val/test split
  * Changed folder structure
* Added annotations in MS COCO format
