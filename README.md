
# Solar Panel Hotspot Detection using YOLO

## Project
A prototype for detecting candidate hotspot regions in solar
panel thermal images using YOLOv8n.

## Technologies
Python, Google Colab, YOLOv8, Ultralytics, PyTorch, OpenCV.

## Dataset
5000 images:
- Train: 4000
- Validation: 500
- Test: 500

## Files
- best.pt: saved YOLO model
- training_results.csv: training metrics
- data.yaml: YOLO dataset configuration
- sample_prediction.png: sample output
- Project_Report.txt: project report

## Important limitation
Labels were generated using automatic HSV colour thresholding.
They are provisional and require expert verification.
The model is a prototype, not a validated diagnostic system.
