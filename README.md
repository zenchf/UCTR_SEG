# UCTR_SEG #

This repository performs lung and heart segmentation from chest X-ray images using a U-Net model. The goal is to enable Cardiothoracic Ratio (CTR) calculation, which will be added in future updates.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📂 Dataset ###
The dataset can be downloaded from the following link:
https://drive.google.com/file/d/1Teg8gHN7-Pg5-V-_7HoIG7iU5DLv7xs4/view?usp=drive_link

### 📂 Pretrained Model ###
The pretrained model can be downloaded from the following link:
https://drive.google.com/file/d/1Teg8gHN7-Pg5-V-_7HoIG7iU5DLv7xs4/view?usp=sharing

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
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
Note: I regret python and tensorflow used in computer vision projects, in the future project i just use c
