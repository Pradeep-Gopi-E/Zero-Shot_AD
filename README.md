# Zero-Shot Anomaly Detection with PaliGemma, CLIP, and RF-DETR

This repository demonstrates an approach to zero-shot anomaly detection using PaliGemma and CLIP models, and anomaly detction with fine-tuned PaliGemma and RF-DETR. The project leverages the capabilities of these models to detect anomalies in datasets like MVTec AD and FracAtlas.

---

## Datasets

The following datasets are utilized in this project:

1. **MVTec AD**: A benchmark dataset for industrial anomaly detection. [Download MVTec AD](https://www.mvtec.com/company/research/datasets/mvtec-ad)
2. **FracAtlas**: A dataset for fracture detection in X-ray images. [Explore FracAtlas](https://github.com/XLR8-07/FracAtlas)

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


Below is a comparison chart for the average IoU across all models and datasets. The Y-axis is displayed in logarithmic scale for better clarity.
![IoU Comparison Chart](https://github.com/user-attachments/assets/8b287a0a-eafa-40a0-ace7-e746972d48d1)


---

