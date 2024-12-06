# TADD model

## Introduction
This repository is a pytorch implementation of the paper "TADD Model: Texture-enhanced Attention Defect Detection Model for Thermal Protection Materials", the code is a copy from the private repository of our engineering project, the code will be made public after removing sensitive information.

## Abstract
Thermal protection materials are widely used in the aerospace field, where detecting internal defects is crucial for ensuring spacecraft structural integrity and safety in extreme temperature environments. Existing detection models struggle with these materials due to challenges like defect-background similarity, tiny size, and multi-scale characteristics. Besides, there is a lack of defect datasets in real-world scenarios. To address these issues, we first construct a thermal protection material digital radiographic (DR) image dataset (TPMDR-dataset), which contains 670 images from actual production and 6,269 defect instances annotated under expert guidance. And we propose an innovative texture-enhanced attention defect detection (TADD) model that enables accurate, efficient, and real-time defect detection. To implement the TADD model, we design a texture enhancement module that can enhance the concealed defect textures and features. Then we develop a non-local dual attention module to address the issue of severe feature loss in tiny defects. Moreover, we improve the model's ability to detect multi-scale defects through a path aggregation network. The evaluation on the TPMDR-dataset and public dataset shows that the TADD model achieves a higher mean Average Precision (mAP) compared to other methods while maintaining 25 frames per second, exceeding the baseline model by 11.05\%.

## Timeline:
Project creation date: 5/8/2023

Creation of this repository: 11/14/2023

Article Submitted: 6/12/2024

Project Status Display: 7/2/2024

## Project Status
We have built the thermal protection material defect AI recognition platform based on the TADD model, and we now publish the details of the platform as follows.

Figure 1 shows the technology stack of the platform
![](https://github.com/ChialinSung/NDA-Detector/blob/main/show_images/%E5%B9%B3%E5%8F%B0.png)

Figure 2 shows the flowchart of the platform
![](https://github.com/ChialinSung/NDA-Detector/blob/main/show_images/%E5%B9%B3%E5%8F%B0%E6%B5%81%E7%A8%8B2.png)

Figure 3 demonstrates the data flow diagram of the platform
![](https://github.com/ChialinSung/NDA-Detector/blob/main/show_images/%E6%97%B6%E5%BA%8F%E5%9B%BE.png)

Figure 4 demonstrates the data annotation process of the platform (based on CVAT)
![](https://github.com/ChialinSung/NDA-Detector/blob/main/show_images/%E6%96%B0%E7%89%88%E6%9C%AC.png)

Figure 5 shows the basic interface of the platform
![](https://github.com/ChialinSung/NDA-Detector/blob/main/show_images/%E6%9C%BA%E5%99%A8%E6%A3%80%E6%B5%8B.jpg)

Figure 6 dynamically shows the platform's machine detection process
![](https://github.com/ChialinSung/NDA-Detector/blob/main/show_images/%E6%9C%BA%E5%99%A8%E6%A3%80%E6%B5%8B.gif)

Figure 7 dynamically shows the platform's manual re-inspection process
![](https://github.com/ChialinSung/NDA-Detector/blob/main/show_images/%E4%BA%BA%E5%B7%A5%E5%A4%8D%E6%A3%80.gif)

Figure 8 dynamically shows the platform re-labeling process
![](https://github.com/ChialinSung/NDA-Detector/blob/main/show_images/%E4%BA%8C%E6%AC%A1%E6%A0%87%E8%AE%B0.gif)

More details will be revealed in the future, so stay tuned!
