# 🔍 Feature Detection & Description in Action  

![OpenCV](https://img.shields.io/badge/OpenCV-4.x-blue?logo=opencv)  
![Python](https://img.shields.io/badge/Python-3.10-yellow?logo=python)  
![License](https://img.shields.io/badge/License-MIT-green)

A hands-on exploration of **feature detection and description** techniques using OpenCV.  
This project compares **ORB and SIFT** methods on sample images to highlight their strengths and weaknesses in real-world computer vision tasks.  

---

## 📸 Example Results  

### ORB (FAST + Binary Descriptors)  
Fast and efficient, works well for real-time applications.  
![ORB Features](images/orb_features.png)

### SIFT (Scale-Invariant Feature Transform)  
Robust to scale and rotation, but slower.  
![SIFT Features](images/sift_features.png)

*(Upload your generated images into an `images/` folder in the repo and replace the links above.)*

---

## ⚡ Techniques Implemented  

- **Feature Detection**: Finding keypoints (corners, blobs, edges).  
- **Feature Description**: Computing feature vectors that describe keypoints.  
- **Matching**: Comparing features across images using Brute-Force or FLANN matcher.  

---

## 🚀 How to Run  

1. Clone this repo:
   ```bash
   git clone https://github.com/HanaNabhan/Feature-Detection-Description.git
   cd Feature-Detection-Description
