# Person Detection and Tracking with YOLOv8 & ByteTrack

Implementation of a real-time person tracking pipeline using YOLOv8 (pretrained on COCO) and the ByteTrack association algorithm. This project analyzes the performance trade-offs between different model scales and visualizes tracking trajectories in high-density scenes.

## Features
- **Dual Model Comparison**: Benchmarks YOLOv8n (Nano) vs. YOLOv8s (Small).
- **Advanced Association**: Uses ByteTrack for robust tracking through occlusions.
- **Scientific Reporting**: Includes a comprehensive LaTeX report with visual and quantitative analysis.
- **Visualization**: Generates trajectory plots, detection density maps, and annotated videos.

## Repository Structure
```text
├── data/           # Input video datasets
├── docs/           # Technical documentation
├── report/         # LaTeX source and PDF report
├── results/        # Tracked videos and metrics.json
└── src/            # Jupyter notebook implementation
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
