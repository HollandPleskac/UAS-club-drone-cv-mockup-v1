﻿# UAS-Club-Drone-CV-Mockup-V1

1. Need to clone ultralytics/yolov5 in this folder.
2. Add a yolov5/custom_dataset_v2.yaml file.
```
# Train/val/test sets as 1) dir: path/to/imgs, 2) file: path/to/imgs.txt, or 3) list: [path/to/imgs1, path/to/imgs2, ..]
path: ../data_v2  # dataset root dir
train: images  # train images (relative to 'path') 128 images
val: images  # val images (relative to 'path') 128 images
# test:  # test images (optional)

# Classes (80 COCO classes)
names:
  0: zone1
```
