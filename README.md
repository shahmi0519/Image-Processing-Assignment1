# 📌 EC7212 — Computer Vision and Image Processing  
## 📝 Take Home Assignment 1  

This repository contains Python code in a Jupyter Notebook (`Assignment.ipynb`) that performs basic image processing operations on **grayscale images**.  
It was developed as part of the *EC7212 – Computer Vision and Image Processing* coursework.  

---

## ✨ Tasks Implemented  
✅ **1️⃣ Intensity Reduction**  
- Reduce image intensity levels from 256 to 2, 4, 8, 16 levels (in powers of 2).  

✅ **2️⃣ Spatial Averaging (Blurring)**  
- Apply simple average filters using 3×3, 10×10, and 20×20 kernels.  

✅ **3️⃣ Image Rotation**  
- Rotate the image by 45° and 90° while preserving the entire image (no cropping).  

✅ **4️⃣ Block-Based Resolution Reduction**  
- For every non-overlapping block (3×3, 5×5, 7×7), replace with average block color to simulate resolution reduction.  

---

## 🛠 Technologies Used  
- Python 3  
- Jupyter Notebook  
- OpenCV  
- NumPy  

---

## 🚀 How to Run  
1️⃣ Clone this repository:  
```bash
git clone https://github.com/shahmi0519/Image-Processing-Assignment1.git
cd Image-Processing-Assignment1
```
2️⃣ Open the notebook:
```bash
jupyter notebook Assignment.ipynb
```
3️⃣ Run all cells to generate and save output images inside the images/ folder.

---

## 📌 Outputs
All output images (reduced intensity, blurred, rotated, block-averaged) are saved in the images/ directory.

File names indicate the operation performed (e.g., reduced_2_levels.jpg, avg_10x10.jpg).

---

## ⚡ Author
A.J.Ahamed Shahmi

---

## 📄 License
This repository is for academic and educational use only.
