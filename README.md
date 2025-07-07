# Hand_Gestures

## Hand Gesture Recognition using OpenCV and Caffe

This project implements real-time hand keypoint detection using OpenCV's Deep Neural Network (DNN) module with a pre-trained Caffe model.

##  Features

- Detects and visualizes 22 hand keypoints.
- Draws hand skeletons in real-time from webcam input.
- Uses pre-trained Caffe model for hand pose estimation.
- Saves the annotated video output.

##  Model

This project uses the OpenPose hand model from CMU Perceptual Computing Lab:

- **Model architecture**: `pose_deploy.prototxt`
- **Pre-trained weights**: `pose_iter_102000.caffemodel`

## 📁 Folder Structure
project/
│
├── Hand_Gesture.py
├── hand/
│ ├── pose_deploy.prototxt
│ └── pose_iter_102000.caffemodel
├── output.avi

## ⚙️ Requirements

- Python 3.x
- OpenCV (>= 4.0)
- NumPy

### 🛠️ Install Dependencies

```bash
pip install opencv-python numpy

