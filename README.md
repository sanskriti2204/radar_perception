# Radar Perception

**Radar Perception** is a modular Python-based toolkit designed for radar-centric perception tasks such as detection, segmentation, tracking, and sensor fusion. It supports multiple radar data formats and integrates processing, modeling, and visualization into one streamlined pipeline. 🚗📡

---

## Radar Perception

### Short Description:
Radar Perception is a Python toolbox for building radar-based perception systems. It includes support for signal processing, object detection, segmentation, multi-object tracking, and sensor fusion with lidar or camera. It also provides dataset loaders, evaluation metrics, and visualizations for radar-based tasks.

### Features:
- **Signal Processing:** FFT, CFAR detection, clutter removal, etc.
- **Radar Representations:** Works with RD/RA maps, angle tensors, and radar point clouds.
- **Object Detection & Segmentation:** Supports radar-only object detection and weakly supervised segmentation.
- **Multi-Object Tracking:** Includes support for tracking across frames using motion models.
- **Sensor Fusion:** Combines radar data with camera or lidar inputs.
- **Dataset Loaders:** Built-in loaders for popular radar datasets like CARRADA, CRUW, RadarScenes, and more.
- **Visualization Tools:** Visualizes radar tensors, heatmaps, and point clouds.
- **Modular Codebase:** Highly configurable pipeline using YAML files.

### Technologies Used:
- **Python 3**
- **PyTorch**
- **NumPy, OpenCV**
- **Matplotlib & Plotly for Visualization**
- **Radar Datasets (CARRADA, CRUW, RadarScenes)**

### How to Use:
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/sanskriti2204/radar_perception.git
   cd radar_perception
