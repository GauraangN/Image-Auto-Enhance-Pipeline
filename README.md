# 🏡 Real Estate Image Enhancement Pipeline

This project provides a complete pipeline for **enhancing real estate images**.  
It includes both **an interactive wizard** for experimenting with different enhancement methods step-by-step and a **batch processing module** for automatically enhancing all images in a folder.  
A small dataset of **interior and exterior real estate images** is included for testing.

---

## ✨ Features
- 📊 **Pipeline Stages**:
  - Gamma Correction
  - Denoising
  - CLAHE-based Contrast & Tone Correction
  - HSV Saturation Boost (adaptive + fixed)
  - Contrast Stretching
  - Image Sharpening (Filter2D & Unsharp Masking)
  - Gaussian & Median Blurring

- 🧑‍💻 **Implementation Wizard**  
  Interactively experiment with enhancement stages:
  - Option to **continue** with the stage or **skip**.
  - Preview 3 options based on parameter variants at each stage.
  
- ⚡ **Batch Processing**  
  - Input: a folder of raw images.  
  - Output: a folder of enhanced images (same filenames).  
  - Runs the full pipeline sequentially.

- 🏠 **Dataset Included**  
  - Example **interior** and **exterior** property images.  
  - Useful for testing and benchmarking.

---
## 📂 Project Structure
real-estate-enhancement/
│
├── wizard/ # Jupyter notebooks for step-by-step wizard
├── batch_processing/ # Jupyter notebooks for batch processing scripts
├── HTML comparison file of input and output
├── requirements.txt # Dependencies
└── README.md # Documentation

