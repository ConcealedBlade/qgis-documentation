# Object Detection

## Overview

> The object detection function is located in the **Object Detection** tab, which can identify the types of objects in an image and their locations, providing bounding boxes for each detected object.

![Interface](/object-detection.png)

## Operation Steps

1. **Select Image Sample**
   - Click the first "Browse..." button on the interface
   - Select the remote sensing image sample to be processed

2. **Image Processing**
   - The system will use [STD ViTs](https://github.com/yuhongtian17/Spatial-Transform-Decoupling) model for automatic processing
   - Detection results will be displayed upon completion

?> **Technical Note**:
[STD ViTs](https://github.com/yuhongtian17/Spatial-Transform-Decoupling) is an object detection model based on Vision Transformers (ViTs) that utilizes Spatial Transform Decoupling (STD) method, showing excellent performance in rotation-sensitive scenarios.