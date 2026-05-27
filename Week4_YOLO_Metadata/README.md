# Week 4 – YOLO Dataset Metadata and Configuration File Analysis

## Objective

The objective of this task was to explore and understand the metadata and configuration files used in YOLO datasets and analyze how datasets are structured for training and validation.

---

## Dataset Configuration Files Explored

The following YOLO dataset configuration files were analyzed:

- `coco128.yaml`
- `coco8-seg.yaml`

Location:

```text
venv/
└── Lib/
    └── site-packages/
        └── ultralytics/
            └── cfg/
                └── datasets/
```

---

## Understanding YAML Configuration Files

YOLO uses YAML files to define dataset information.

Example:

```yaml
path: coco128

train: images/train2017

val: images/train2017

names:
  0: person
  1: bicycle
  2: car
```

---

## Explanation of Important Fields

| Field | Description |
|-------|-------------|
| path | Root directory of dataset |
| train | Path containing training images |
| val | Path containing validation images |
| test | Optional testing images |
| names | Mapping of class IDs to object names |

---

## Class Definitions

YOLO stores object categories using numeric IDs.

Examples:

| Class ID | Object |
|---------|--------|
| 0 | person |
| 1 | bicycle |
| 2 | car |
| 3 | motorcycle |
| 4 | airplane |

These class IDs are later used during training and prediction.

---

## Detection vs Segmentation

### Object Detection
Object detection identifies objects and places bounding boxes around them.

Example:

```text
[ Person ]
```

---

### Semantic Segmentation

Semantic segmentation performs pixel-wise classification and identifies precise object boundaries.

Example:

```text
Colored mask over exact object shape
```

Segmentation provides more detailed localization than detection.

---

## YOLO Label Structure

YOLO label files typically follow this format:

```text
class x_center y_center width height
```

Example:

```text
0 0.53 0.40 0.32 0.50
```

Meaning:

| Value | Description |
|-------|-------------|
| 0 | Object Class |
| 0.53 | X center |
| 0.40 | Y center |
| 0.32 | Width |
| 0.50 | Height |

Coordinates are normalized between 0 and 1.

---

## Observations

- YAML files organize datasets and training information.
- Classes are represented using numerical IDs.
- Separate directories are maintained for training and validation.
- Semantic segmentation provides more precise understanding compared to object detection.

---

## Conclusion

This task helped understand how YOLO datasets are configured and how metadata files control training workflows. YAML files define dataset structure, classes, and image locations while labels store object information used by YOLO models.

---

## References

Ultralytics Documentation:

https://docs.ultralytics.com/datasets/

https://docs.ultralytics.com/tasks/segment/
