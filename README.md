This repository contains the preprocessing pipeline, dataset metadata, training notebooks, and trained YOLO11n baseline for a three-class cocoa disease detection project. The full image dataset is not stored in this repository due to size and source-dataset distribution constraints. The project combines data from the KaraAgroAI Cocoa Dataset and a public Roboflow Cocoa dataset, with annotations normalized into YOLO format.

Classes:
0 — Anthracnose
1 — CSSVD
2 — Healthy

Dataset:
5,583 images
70/20/10 split

Model:
YOLO11n

Baseline:
10 epochs
imgsz=640
batch=4
CPU

Validation:
mAP50 = 0.748
mAP50-95 = 0.491