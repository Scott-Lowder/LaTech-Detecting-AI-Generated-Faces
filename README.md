# LaTech-Detecting-AI-Generated-Faces  
### Project Proposal  

**Team Members:**  
David Castilla, Scott Lowder, Bennett Volanth, and Franco Zabaleta  
**Date:** October 9th, 2025  

---

## 1. Project Overview  

The problem we will investigate is the growing difficulty of distinguishing real human faces from AI-generated or deepfake images.  
AI media creators, such as *Tilly Norwood*, an AI actress stirring up Hollywood, and *Sora 2*, a video-generation tool, have shown it is easier than ever to produce convincing real content.  
This raises concerns about misinformation, digital identity manipulation, and media authenticity.  

This issue is both current and socially relevant, as AI-generated content increasingly appears in news, social media, and entertainment, making automated detection tools critical.

---

## 2. Background and Literature Review  

Our group will examine literature on deepfake generation techniques, GAN-based image synthesis, and existing detection methods — including convolutional neural network (CNN) architectures and interpretability approaches such as Grad-CAM.  

We will also review research on dataset biases and generalization challenges in deepfake detection to guide our model design and evaluation strategy.

---

## 3. Dataset  

We will use the **140K Real and Fake Faces** dataset available on Kaggle, which contains approximately **70,000 real** and **70,000 AI-generated** images.  
These images cover a wide range of demographics and styles, providing a balanced and diverse dataset for training and evaluation.

---

## 4. Methodology  

We propose designing and training custom **CNN architectures** for binary classification of real vs. fake faces.  
We will experiment with architectural variations such as convolutional depth, kernel size, and normalization layers to improve performance and interpretability.  

To benchmark our approach, we will compare our models against standard architectures like **ResNet** and **EfficientNet**.  
Our goal is to develop models that generalize well to unseen deepfake styles and to interpret which facial regions most influence classification decisions.

---

## 5. Evaluation  

### **Qualitative Evaluation:**  
- Confusion matrices  
- Grad-CAM heatmaps  
- Feature importance plots  

### **Quantitative Evaluation:**  
- Accuracy  
- Precision  
- ROC-AUC  

---

## 6. Timeline and Milestones  

| Date | Milestone |
|------|------------|
| **Oct 25** | Literature review and dataset preprocessing |
| **Nov 14** | Model training, baseline evaluation, and hyperparameter tuning |
| **Dec 2**  | Robustness testing, interpretability analysis, and final report preparation |

---

## 7. Team Roles  

| Member | Responsibility |
|---------|----------------|
| **Member 1** | Data collection and preprocessing |
| **Member 2** | Model implementation and training |
| **Member 3** | Evaluation and analysis |
| **Member 4** | Visualization and report compilation |



