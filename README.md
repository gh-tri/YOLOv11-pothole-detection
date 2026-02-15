# YOLOv11-pothole-detection
This repository contains a single, self-contained Jupyter notebook that documents and reproduces my pothole detection study using Ultralytics YOLOv11.  
The notebook covers: dataset setup, training (YOLOv11s/m; fixed vs. multi-scale), validation/test evaluation (mAP, P, R), operating-point analysis (conf=0.25), and qualitative TP/FN/FP overlays.

---

## Contents
- `Yolo11_FineTune_pothole.ipynb` — the complete pipeline (run cells top-to-bottom)
- `report_samples/` — qualitative test examples, 4 examples per case --organized into:
  - `typical/`   — expected/normal cases
  - `hard_fn/`   — failure cases dominated by false negatives (missed potholes)
  - `hard_fp/`   — failure cases dominated by false positives (false alarms)
  - `random/`    — randomly sampled cases (fixed seed) to avoid selection bias

---
