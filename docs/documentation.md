# Project Documentation: Person Detection and Tracking

## Overview
This project implements a multi-object tracking (MOT) system for pedestrians using YOLOv8 for detection and ByteTrack for association.

## Directory Structure
- `src/`: Contains the Jupyter notebook used for experimentation and model comparison.
- `data/`: Contains the input video source.
- `results/`: Contains the output tracked videos and quantitative metrics.
- `report/`: Contains the LaTeX source code and the compiled scientific report.
- `docs/`: Project documentation.

## Models Used
- **YOLOv8n**: Nano model, fastest for real-time inference.
- **YOLOv8s**: Small model, higher accuracy but slower.

## How to Run
1. Install dependencies:
   ```bash
   pip install ultralytics lapx imageio[ffmpeg]
   ```
2. Run the notebook in `src/person_tracking_yolov8_bytetrack.ipynb`.
3. The results will be saved in the `results/` directory.

## Metrics
The following metrics are tracked:
- Total detections
- Detections per frame
- Unique Track IDs
- Inference Speed (FPS)
- Trajectory stability
