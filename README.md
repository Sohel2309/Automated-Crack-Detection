# Automated-Crack-Detection
End-to-end deep learning system for crack detection, segmentation, and severity analysis

# 🧠 Automated Crack Detection and Severity Analysis

An end-to-end deep learning system for automatic crack detection, segmentation, geometric analysis, and severity classification using real-world surface images.

---

## 📌 Project Overview

This project implements a complete crack inspection pipeline:

- Pixel-level crack segmentation using a CNN
- Post-processing to remove noise and improve crack continuity
- Crack geometry extraction (area, length, width)
- Rule-based severity classification
- Visual output generation with crack highlighting

The goal is to move beyond simple classification and build a practical inspection system.

---

## 🏗️ System Pipeline

Input Image  
→ CNN Segmentation  
→ Post-processing  
→ Skeletonization  
→ Crack Geometry Extraction  
→ Severity Classification  
→ Final Labeled Output  

---

## 📊 Results

### Segmentation Performance
- Dice Coefficient ≈ 0.48  
- IoU Score ≈ 0.34  

### Severity Categories
- No Crack  
- Minor Crack  
- Moderate Crack  

Severity is determined using geometric thresholds on crack area, length, and width.

---

## 🖼️ Sample Outputs

Sample results can be found in:

