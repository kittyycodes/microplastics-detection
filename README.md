# Microplastic Detection in Holographic Images

## Overview

This project focuses on detecting **microplastics** in holographic images using deep learning techniques, specifically the **Faster R-CNN** model. Microplastics are small plastic particles that pose significant environmental hazards. By accurately identifying these particles, we aim to contribute to more effective monitoring and management of plastic pollution.

## Dataset

The dataset consists of holographic images that contain various microplastic particles. These images are annotated based on the shapes of the microplastics. **Microplastics** typically exhibit more regular, uniform shapes, whereas non-microplastics, such as dust, often appear irregular. 

## Preprocessing Steps

1. **Rescaling**: All images were resized to ensure uniformity and improve model training efficiency.
   
2. **CLAHE Enhancement**: **Contrast Limited Adaptive Histogram Equalization (CLAHE)** was applied to enhance the visibility of microplastics in the images, making them easier to label.

3. **Manual Labeling**: Microplastics were labeled manually based on their shapes, utilizing the observed characteristics noted in relevant literature. This step ensures that the dataset is accurately annotated for training.

4. **Data Augmentation**: To improve the robustness of the model, data augmentation techniques such as **rotation** and **flipping** were employed. This helps increase the variability of the training dataset and enables the model to generalize better.

## Future Work

In the upcoming phases of this project, we will implement the **Faster R-CNN** model to detect microplastics within the annotated images. This model has proven effective in object detection tasks and will be fine-tuned to optimize its performance on our dataset.

