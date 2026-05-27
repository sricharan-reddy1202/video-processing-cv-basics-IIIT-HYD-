# Computer Vision Internship – Weeks 1 to 5

This repository contains all work completed during the Computer Vision Internship program including video preprocessing, object detection, segmentation, dataset creation, annotation, model training, testing, and final showcase.

---

# Project Overview

This internship focused on understanding and implementing an end-to-end Computer Vision pipeline using:

- Python
- YOLO (Ultralytics)
- Label Studio
- FFmpeg
- Git & GitHub

The workflow covered:

Video → Frames → Annotation → Dataset → Training → Testing → Final Output

---

# Tools Used

- Python
- YOLO (Ultralytics)
- Label Studio
- FFmpeg
- VS Code
- GitHub

---

# Week 1 – Video Processing

## Tasks Completed

- Downloaded video
- Extracted frames using FFmpeg
- Reconstructed video from frames
- Added audio to generated video

### Concepts Learned

- Video decomposition
- Frame extraction
- FPS
- Video generation

Output:

```text
Video → Frames → Video + Audio
```

---

# Week 2 – Object Detection

## Tasks Completed

- Created Python virtual environment
- Installed Ultralytics
- Executed pretrained YOLO model
- Applied detection on images
- Generated annotated outputs

### Concepts Learned

- Object Detection
- Bounding Boxes
- Pretrained Models

Output:

```text
Images → Detection → Annotated Images
```

---

# Week 3 – Semantic Segmentation

## Tasks Completed

- Performed segmentation
- Generated segmented outputs
- Converted segmented outputs into video
- Added music

### Concepts Learned

- Pixel-wise classification
- Semantic Segmentation

Output:

```text
Images → Segmentation → Video
```

---

# Week 4 – Dataset Creation and Labeling

## Tasks Completed

- Explored YAML configuration files
- Understood dataset metadata
- Installed Label Studio
- Created dataset folders
- Annotated images
- Generated YOLO labels
- Created train.txt and val.txt

### Concepts Learned

- Dataset structure
- Label formats
- Data annotation
- YOLO metadata

Dataset Structure:

```text
datasets/
│
├── images/
├── labels/
├── data.yaml
├── train.txt
└── val.txt
```

---

# Week 5 – Training and Inference

## Tasks Completed

- Resized dataset
- Trained custom YOLO model
- Generated custom weights
- Detected objects on test images
- Created prediction outputs
- Generated final showcase video

### Concepts Learned

- Training
- Validation
- Overfitting
- Inference
- Custom Weights

Generated Files:

```text
best.pt
results.png
prediction outputs
final video
```

---

# Folder Structure

```text
cv-internship
│
├── datasets
├── Week1
├── Week2
├── Week3
├── Week4
├── Week5
├── outputs
└── README.md
```

---

# Key Learnings

- End-to-end Computer Vision workflow
- Data preprocessing
- Model training
- Dataset creation
- Prediction pipelines
- Version control using GitHub

---

# Final Result

Successfully completed a complete Computer Vision pipeline including:

Video Processing  
→ Detection  
→ Segmentation  
→ Dataset Creation  
→ Annotation  
→ Training  
→ Testing  
→ Final Showcase

---

# Author

Pinreddy Sricharan Reddy

Computer Vision Internship Project
