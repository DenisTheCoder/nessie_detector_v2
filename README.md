# nessie_detector_v2
ssd mobilenet v2 coco model additionally trained to recognize only Loch Ness monster plushies

this is a faster version intended for edge devices (can sustain ~2fps running on Raspberry Pi 4 and similar). Original version 1 (faster rcnn) -> https://github.com/DenisTheCoder/nessie_detector_v1

Trained with Tesnorflow 1.13 object detection api, can be found here -> https://github.com/tensorflow/models/tree/r1.13.0
This model in initially a **SSD Mobilenet V2 coco model** can be found here -> https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf1_detection_zoo.md.
The model was additionally trained with dataset of 80 photos with Loch Ness Monster plush.

Model is originally intended to use with Tensorflow 1.X

Labelmap can be found in the model files.

Sample photos:
![image](https://user-images.githubusercontent.com/65178931/160280171-28feb327-72f9-4149-8227-522a754f736e.png)
![image](https://user-images.githubusercontent.com/65178931/160280183-8c617606-b268-4c10-807a-48c1662db540.png)
![image](https://user-images.githubusercontent.com/65178931/160280188-7e40da26-b9d6-4d6a-9730-bc6600b5c9dd.png)
![IMG_2522_JPG rf 914690efa58866950bd8e55481df9a17](https://user-images.githubusercontent.com/65178931/160280205-4a9fd0ab-793d-4a1a-8e2d-daa781000c71.jpg)



Special thanks...
to Edje for explaining the basics of training models with Obect Detection API - https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10#2-set-up-tensorflow-directory-and-anaconda-virtual-environment

to Edje repo community and fellow enthusiasts for troubleshooting common issues - https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10/issues/184 
