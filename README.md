#  EEG-Based Emotion Recognition using Deep Learning (EEGNet + CBAM + SE)

This project explores **emotion recognition from EEG signals** using deep learning.  
I enhanced the original **EEGNet architecture** by integrating:

- **CBAM (Convolutional Block Attention Module)** → focuses on relevant spatial features  
- **SE (Squeeze-and-Excitation block)** → improves channel-wise feature weighting  

The goal was to improve classification performance on the **SEED-IV dataset**, a widely used benchmark in EEG-based emotion studies.

---

##  Key Features

✅ Modified EEGNet architecture with **attention mechanisms (CBAM + SE)**  
✅ Feature extraction improvements over baseline EEGNet  
✅ Emotion classification from EEG time-series data  
✅ Rigorous evaluation using:
- Validation Loss
- PR-AUC (Precision-Recall Area Under Curve)
- Region-wise accuracy comparison (frontal, parietal, temporal, etc.)

---

## 📊 Results (Summary)

| Model              | Accuracy |
|-------------------|----------|
| EEGNet (Optimized) | 88.9%   |          
| EEGNet + CBAM     | 88.43%   |
| EEGNet + SE       | 87.00%   | 



##  Dataset

Dataset Used: **SEED-IV (SJTU Emotion EEG Dataset)**  
 Contains EEG recordings of four emotion categories: *Happy, Sad, Fear, Neutral*

Dataset download link (requires access approval):  
https://bcmi.sjtu.edu.cn/~seed/seed-iv.html
