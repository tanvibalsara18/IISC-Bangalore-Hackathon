# YOLOv8 Object Detection Notebook

This repository contains a notebook that demonstrates how to use the YOLOv8 model for object detection tasks. The notebook leverages the `ultralytics` library and integrates with Google Colab for data storage and model execution.

## Project Structure

- **Notebook**: `yolov8_small_data.ipynb`
  - This notebook performs object detection using the YOLOv8 model.
  - Key operations include dataset loading, model setup, and inference.
  - 
## Open-Source Model References
The notebook uses the YOLOv8n model checkpoint provided by Ultralytics:

Model Checkpoint URL: yolov8n.pt

## System Requirements
The notebook was tested in a Google Colab environment with the following specifications:

- GPU: NVIDIA Tesla T4 (15 GB VRAM)
- CPU: 2 vCPUs
- RAM: 12.7 GB

## Recommended System Specifications for Local Execution
- GPU: NVIDIA GPU with CUDA support (e.g., Tesla T4, RTX 2080, etc.)
- CPU: 4+ cores
- RAM: 16 GB or higher
- Disk Space: Minimum of 50 GB free space

## Requirements

The following Python libraries are required to run the notebook:

- `ultralytics==8.2.81`
- `torch==2.3.1+cu121`

These dependencies can be installed using:

```bash
pip install -r Requirements.txt

