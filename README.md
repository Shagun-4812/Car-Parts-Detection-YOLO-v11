# Car Parts Detection using YOLO v11

## Objective
Train a YOLO v11 object detection model to detect car parts using the Car Parts Dataset.

---

## Project Overview
This notebook covers:
1. Dataset preparation and conversion from COCO to YOLO format  
2. Model training using YOLO v11  
3. Evaluation using mAP metrics  
4. Visualization of predictions  
5. Analysis of difficult-to-detect categories  
6. Proposed solutions for improvement  

---

## ⚙️ Installation and Setup
Required packages:
- `ultralytics`: Official YOLO implementation with v11 support  
- `opencv-python`: Image processing and visualization  
- `matplotlib`: Plotting and visualization  
- `pycocotools`: COCO format parsing utilities  

### Install dependencies
```bash
pip install ultralytics opencv-python matplotlib pycocotools pillow numpy pandas
