# Quantitative-Identification-Cracks-of-Heritage-Rock-Based-on-Digital-Image-Technology
# Crack Detection in Heritage Rock using Digital Image Processing

This project is a Python-based implementation of the research paper _"Quantitative Identification Cracks of Heritage Rock Based on Digital Image Technology"_. The goal is to apply a series of digital image processing techniques to extract and highlight crack regions from rock images for heritage preservation analysis.

## 📚 Overview

Using grayscale conversion, filtering, enhancement, segmentation, and morphological processing, this pipeline simulates the method presented in the original research paper and validates its effectiveness through visual comparisons.

---

## 🧰 Technologies Used

- Python 3.x
- OpenCV (cv2)
- NumPy
- Matplotlib (for visualizations)

---


---

## 🧪 Methodology

The project follows the exact sequence of preprocessing steps and enhancement operations as described in the research paper:

### 1. Grayscale Conversion
- **Component Method**
- **Maximum Method**
- **Average Method**
- **Weighted Average Method**

### 2. Filtering Techniques
- **Mean Filtering**
- **Gaussian Filtering** (chosen for final preprocessing)
- **Median Filtering**

### 3. Spatial Domain Enhancement
- Neighborhood-based contrast improvement using linear transforms.

### 4. Binarization
- Threshold-based binary segmentation (black & white conversion).

### 5. Crack Segmentation
- **Region Growing** using grayscale-based seed expansion.

### 6. Morphological Processing
- **Erosion** to refine and isolate cracks by removing noise.

---

### 🔍 Visual Comparison

- Final crack maps are compared to the figures from the research paper to validate performance and precision.
- Slight differences may occur due to:
  - Image quality/resolution
  - Lighting conditions
  - Different kernel sizes or thresholding parameters

---

## 📝 Conclusion

This implementation demonstrates that classical image processing techniques—when carefully chained—can be effective in detecting and quantifying natural fractures in heritage rock images. The pipeline closely replicates the paper’s methodology and achieves comparable results.

---


---

## 📖 Reference

Xiufang Wang, Jingyuan Li, Ming Bai, and Yan Pei.  
“Quantitative Identification Cracks of Heritage Rock Based on Digital Image Technology.”  
_Journal of Physics: Conference Series_, 2148(1):012048, 2021.  

---



