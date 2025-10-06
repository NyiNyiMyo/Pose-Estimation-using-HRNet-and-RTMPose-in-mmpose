<div align="center">
    <h1>Pose Estimation using HRNet and RTMPose <br/> in mmpose </h1>
</div>

[![python](https://img.shields.io/badge/Python-3.11-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![pytorch](https://img.shields.io/badge/PyTorch-2.0.1+cu117-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org)
![Static Badge](https://img.shields.io/badge/Pose-Estimation-cyan)
![Static Badge](https://img.shields.io/badge/mmpose-blue)

<div align="center">
    <h3>HRNet Pose Estimation </h3>
</div>

<img src="https://github.com/user-attachments/assets/9719d1b1-dc11-45ea-911f-831335becfda" width="310" height="600"> <img src="https://github.com/user-attachments/assets/09f576e3-c2b3-4076-893a-f8e02eaa30fc" width="500" height="600">

<div align="center">
    <h3>RTMPose Pose Estimation </h3>
</div>

<img src="https://github.com/user-attachments/assets/48918d84-a81e-4d42-b619-20737b488f56" width="810" height="600">

---

## 🏗️ Methodology

- 🤸‍♂️ Pose Estimation Model1: **hrnetv2_w18_coco_wholebody_hand_256x256**
- 🤸‍♂️ Type: **Top-down**
- 🤸‍♂️ Hand Detection Model: **ssdlite_mobilenetv2_scratch_600e_onehand**
- 🤸‍♂️ Framework: **PyTorch + mmpose**
- 🤸‍♂️ Pose Estimation Model2: **hrnetv2_w18_coco_wholebody_face_256x256**
- 🤸‍♂️ Type: **Top-down**
- 🤸‍♂️ Face Detection Model: **yolo-x_8xb8-300e_coco-face**
- 🤸‍♂️ Framework: **PyTorch + mmpose**
- 🤸‍♂️ Pose Estimation Model3: **rtmpose-l_simcc-body7_pt-body7-halpe26_700e-384x288**
- 🤸‍♂️ Type: **Top-down**
- 🤸‍♂️ Object Detection Model: **rtmdet_tiny_8xb32-300e_coco**
- 🤸‍♂️ Framework: **PyTorch + mmpose**

---

## ⭐ Acknowledgements

- mmpose

---
