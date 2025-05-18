# Hazardous Material Detection using YOLOv8 and Flask
This project detects hazardous materials (gas cylinders, fire extinguishers, shock absorbers, etc,.) in metal scrap using a YOLOv8 segmentation model and serves it through a web-based Flask application. Users can upload both images and videos, view annotated predictions, and see object counts in a clean, responsive interface.

# Project Overview

- Built a YOLOv8 segmentation model to identify high-risk objects in metal scrap environments.
- Addressed challenges such as class imbalance, limited data, and noisy backgrounds.
- Deployed the model through a modern Flask web app with support for both images and videos.

---

# Features

-  Polygon mask-based segmentation using YOLOv8
-  Custom drag-and-drop file uploader (HTML/CSS/JS)
-  Image and video upload support
-  Visual prediction results + object counts
-  Responsive, Bootstrap-powered UI

---

# Model Details

- Model: YOLOv8s-seg
- Training data: Custom annotated dataset (via Roboflow)
- Input size: 640×640  
- Augmentation: rotation, flip, HSV shift, mixup, mosaic  

---

# Example Classes

- Fire Extinguisher  
- Gas Cylinder  
- Shock Absorber

---

# How to Run the App

### 1. Clone the Repository
```bash
git clone https://github.com/jeev2727/hazardous-material-detector.git
cd hazardous-material-detector
