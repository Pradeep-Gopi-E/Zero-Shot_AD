# Zero-Shot Anomaly Detection with PaliGemma, CLIP, and RF-DETR

This repository demonstrates an approach to zero-shot anomaly detection using **PaliGemma** and **CLIP** models, as well as anomaly detection with fine-tuned **PaliGemma** and **RF-DETR**. The project leverages the capabilities of these models to detect anomalies in datasets like **MVTec AD** and **FracAtlas**.

---

## Datasets

The following datasets are utilized in this project:

1. **MVTec AD**: A benchmark dataset for industrial anomaly detection.  
   [Download MVTec AD](https://www.mvtec.com/company/research/datasets/mvtec-ad)

2. **FracAtlas**: A dataset for fracture detection in X-ray images.  
   [Explore FracAtlas](https://github.com/XLR8-07/FracAtlas)

---

## Codebase Overview

- **CLIP-Based Anomaly Localization**  
  [View Code](https://github.com/Pradeep-Gopi-E/Zero-Shot_AD/blob/main/Anomaly_Localization_CLIP.ipynb)

- **PaliGemma-Based Anomaly Localization**  
  [View Code](https://github.com/Pradeep-Gopi-E/Zero-Shot_AD/blob/main/Anomaly_Localization_PaliGemma.ipynb)

- **Fine-Tuning PaliGemma**  
  [View Code](https://github.com/Pradeep-Gopi-E/Zero-Shot_AD/blob/main/Fine_Tuning_PaliGemma.ipynb)

- **Fine-Tuning RF-DETR on FracAtlas**  
  [View Code](https://github.com/Pradeep-Gopi-E/Zero-Shot_AD/blob/main/finetune_rf_detr_Fratlas.ipynb)

---

## Results

### Intersection over Union (IoU) Comparison

The chart below compares the average IoU across all models and datasets. The Y-axis is displayed in logarithmic scale for better clarity.

![IoU Comparison Chart](https://github.com/user-attachments/assets/8b287a0a-eafa-40a0-ace7-e746972d48d1)

---

### mAP@50 Comparison Chart

The chart below showcases the performance of fine-tuned models on mAP@50 scores for the datasets.

![mAP@50 Comparison Chart](https://github.com/user-attachments/assets/f9d90a6e-9d03-468e-8477-24d8526c31cc)

---

## Models Used

### **1. PaliGemma**
PaliGemma is a lightweight vision-language model designed for multimodal reasoning tasks.

For more details about PaliGemma, see the official repository:  
[Big Vision: PaliGemma Configurations](https://github.com/google-research/big_vision/tree/main/big_vision/configs/proj/paligemma)

### **2. CLIP (Contrastive Language-Image Pretraining)**
CLIP is a VLM used for zero-shot image classification


Learn more about CLIP here:  
[OpenAI: CLIP GitHub Repository](https://github.com/openai/CLIP)

### **3. RF-DETR **
RF-DETR is a detection transformer optimized for real-time object detection.


Explore RF-DETR in the official repository:  
[RoboFlow: RF-DETR GitHub Repository](https://github.com/roboflow/rf-detr)

---
