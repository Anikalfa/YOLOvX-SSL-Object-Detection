# YOLOv10, YOLOv11, and YOLOv12 Object Detection with SSL and Semi-Supervised Learning

## Overview
This repository contains code for performing object detection using YOLOv10, YOLOv11, and YOLOv12 backbones, utilizing Semi-Supervised Learning (SSL) and Self-Supervised Learning (SSL) methods. The project includes multiple notebooks for different configurations and experimental setups.

## Notebooks
The notebooks are organized as follows:

### YOLOv10
- **BYOL:** [YOLOv10 BYOL](https://www.kaggle.com/code/rahinarefin/byolv10)  
- **DINO:** [YOLOv10 DINO](https://www.kaggle.com/code/rahinarefinahmed/dinov10-lat)  
- **STAC:** [YOLOv10 STAC](https://www.kaggle.com/code/nick2alfa1/stac-yolov10n)

### YOLOv11
- **BYOL:** [YOLOv11 BYOL](https://www.kaggle.com/code/rahin56/byol-yolov11)  
- **DINO:** [YOLOv11 DINO](https://www.kaggle.com/code/nick2alfa1/final-dinoyolov11)  
- **STAC:** [YOLOv11 STAC](https://www.kaggle.com/code/nickalfa/stac-yolov11)

### YOLOv12
- **BYOL:** [YOLOv12 BYOL](https://www.kaggle.com/code/rahinarefin/yolov12-byol-project-bestof-all)  
- **DINO:** [YOLOv12 DINO](https://www.kaggle.com/code/rahin56/dino-yolov12-latest)  
- **STAC:** [YOLOv12 STAC](https://www.kaggle.com/code/nickalfa/stac-yolov12)

## Project Structure
- **/yolov10** - Contains YOLOv10-based notebooks for training with BYOL, DINO, and STAC.
- **/yolov11** - Contains YOLOv11-based notebooks for training with BYOL, DINO, and STAC.
- **/yolov12** - Contains YOLOv12-based notebooks for training with BYOL, DINO, and STAC.
- **/datasets** - Includes datasets used for training and validation.
- **/models** - Contains pre-trained models and configuration files.
  
## Requirements
The project requires the following dependencies:
- Python 3.x
- PyTorch
- TensorFlow (for some models)
- OpenCV
- Matplotlib
- scikit-learn
- pandas
- other dependencies are listed in `requirements.txt`

Install the dependencies using:
```bash
pip install -r requirements.txt
