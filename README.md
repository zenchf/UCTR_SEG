# UCTR_SEG #

This repository performs lung and heart segmentation from chest X-ray images using a U-Net model. The goal is to enable Cardiothoracic Ratio (CTR) calculation, which will be added in future updates.

### 📂 Dataset ###
The dataset can be downloaded from the following link:

### 🛠 Repository Structure ###
model.py → Contains the U-Net architecture for segmentation.

data.py → Data preprocessing utilities.

main.py → Training script.

mode/config.py → Configuration and command-line arguments.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This project was built and tested with legacy versions of TensorFlow and Keras:

Python 3.7.17

TensorFlow 1.14.0

Keras 2.2.4

cuda 1.12/cudnn 8.9/ nvidia RTX 3080 

NumPy, OpenCV, Matplotlib, etc.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
