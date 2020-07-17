# [YOLO-object detection](https://pjreddie.com/darknet/yolo/)

YOLO(You only look once) is state of art object detection algorithm.


IT is a new approach to object detection.Prior work on object detection repurposes classifiers to perform detection. Instead, It frame object detection as a regression problem to spatially separated bounding boxes and associated class probabilities. A single neural network predicts bounding boxes and class probabilities directly from full images in one evaluation. Since the whole detection pipeline is a single network, it can be optimized end-to-end directly on detection performance.The unified architecture is extremely fast. The base YOLO model processes images in real-time at 45 frames per second. A smaller version of the network, Fast YOLO,processes an astounding 155 frames per second while still achieving double the mAP of other real-time detectors.Compared to state-of-the-art detection systems, YOLO makes more localization errors but is less likely to predict false positives on background. Finally, YOLO learns very general representations of objects. 


# Packages Used:package: :
* **Open CV**
* **Numpy**
* **argparse**
* **imutils**

# INSTRUCTONS:
Following is an implimentation of YOLO using python.

1.Command to run the detection program > $ python yolo.py --image **directoryname**/**image name** --yolo **coco directory**

2.Save coco.names,yolov3.cfg and [weights](https://pjreddie.com/darknet/yolo/) in same directory.

3.Sava the all test images in single directory and Replace the Respective blanks in the command.



**check the following papers for a deeper understanding**:

[Rich feature hierarchies for accurate object detection and semantic segmentation](https://arxiv.org/abs/1311.2524)

[ You Only Look Once: Unified, Real-Time Object Detection](https://arxiv.org/abs/1506.02640)

[YOLOv3: An Incremental Improvement (2018)](https://arxiv.org/abs/1804.02767)

