# Facial Pose Estimation Using MediaPipe

## Overview

This project aims to estimate the facial pose (pitch, yaw, roll) of individuals using the MediaPipe library. Facial landmark detection is performed using the MediaPipe FaceMesh module, followed by pose estimation based on the detected landmarks.

## Requirements

- Python 3.x
- Required libraries:
  - numpy
  - opencv-python
  - mediapipe
  - matplotlib
  - scipy

## Installation

Ensure you have the necessary libraries installed. You can install them using pip:

```bash
    pip install numpy opencv-python mediapipe matplotlib scipy
```
## Usage

1. **Downloading Data:**
   - The AFLW2000 dataset is used in this project. You can download it from [here](http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip).
   - Extract the downloaded data and place it in the appropriate directory.

2. **Preprocessing Data:**
   - Run the provided code snippets for preprocessing the data, which includes loading images, extracting facial landmarks, and preparing features and labels.

3. **Model Investigation:**
   - Various models are investigated for facial pose estimation, including Linear Regression, SVR (Support Vector Regression), Decision Tree, Random Forest, XGBoost, and AdaBoost.
   - Model training, validation, and testing are performed, and errors/scores are calculated.

4. **Testing on Images:**
   - Test the trained models on individual images from the dataset.
   - Display the estimated facial pose overlaid on the image.

5. **Testing on Videos:**
   - Test the models on videos to estimate facial pose frame by frame.
   - Output a new video with the estimated pose overlaid on each frame.

## Contributors

- Amira Adel Foda (Intake 42 - Smart Village Branch - Group 2)
- Asmaa Said (Intake 42 - Smart Village Branch - Group 2)
- Marawan Mohamed (Intake 42 - Alex. Branch - Group 2)

## License

This project is licensed under the [MIT License](LICENSE).

