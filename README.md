# Person Detection and Tracking with YOLOv8 & ByteTrack

[![Computer Vision](https://img.shields.io/badge/Computer-Vision-blue.svg)](https://opencv.org/)
[![YOLOv8](https://img.shields.io/badge/Model-YOLOv8-green.svg)](https://github.com/ultralytics/ultralytics)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A professional implementation of a real-time person tracking pipeline using YOLOv8 (pretrained on COCO) and the ByteTrack association algorithm. This project analyzes the performance trade-offs between different model scales and visualizes tracking trajectories in high-density scenes.

## 🚀 Features
- **Dual Model Comparison**: Benchmarks YOLOv8n (Nano) vs. YOLOv8s (Small).
- **Advanced Association**: Uses ByteTrack for robust tracking through occlusions.
- **Scientific Reporting**: Includes a comprehensive LaTeX report with visual and quantitative analysis.
- **Visualization**: Generates trajectory plots, detection density maps, and annotated videos.

## 📁 Repository Structure
```text
├── data/           # Input video datasets
├── docs/           # Technical documentation
├── report/         # LaTeX source and PDF report
├── results/        # Tracked videos and metrics.json
└── src/            # Jupyter notebook implementation
```

## 📊 Sample Results
The system achieves high FPS on GPU-accelerated environments, with the Nano model reaching real-time performance (>30 FPS) while maintaining stable person IDs.

## 🛠️ Installation
```bash
pip install ultralytics lapx
```

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author
**Amr Yasser**
- Zewail City of Science and Technology
- Computer Vision Assignment 4
