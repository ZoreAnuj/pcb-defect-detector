# PCB Defect Detector with YOLOv10

This project implements a computer vision system for detecting manufacturing defects on printed circuit boards (PCBs). It fine-tunes the YOLOv10 object detection model on a custom PCB defect dataset to automate visual quality inspection, aiming to improve accuracy and efficiency over manual checks.

## Key Features
*   Fine-tuned YOLOv10 model for six common PCB defect classes.
*   Includes scripts for dataset preparation, model training, and inference.
*   Provides evaluation metrics and visualizations of detection results.
*   Optimized for deployment in automated inspection pipelines.

## Tech Stack
*   **Framework:** Ultralytics YOLOv10
*   **Language:** Python
*   **Libraries:** PyTorch, OpenCV, Pandas, Matplotlib

## Getting Started
1.  Clone the repository: `git clone https://github.com/zoreanuj/pcb-defect-detector.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Place your dataset in the `datasets/` directory and update the data configuration.
4.  Run training: `python train.py`