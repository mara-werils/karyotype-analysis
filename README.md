
markdown
# Karyotype Analysis for Structural Variations Detection

## Project Overview
Detection of 24 chromosome types using YOLOv8 for structural variations analysis in genome.

## Results
- **mAP50: 77.2%**
- **Precision: 71.5%** 
- **Recall: 71.1%**
- Best classes: G21 (95.5%), A1 (91.8%), A2 (91.7%)

## Quick Start
```python
!pip install ultralytics
from ultralytics import YOLO
model = YOLO('path/to/best.pt')
results = model('image.jpg')
Dataset

5000 karyotype images with annotations
24 chromosome classes (A1, A2, ..., X, Y)
Structural abnormalities annotations available
