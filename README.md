# 🕳️ Pothole Detection in Videos using YOLOv8 + Roboflow

A computer vision project that detects potholes in road videos using a custom-trained YOLOv8 model (via Roboflow) and OpenCV. The system processes video frames, applies object detection, and outputs an annotated video.

---

## 🚀 Features

✅ Pothole detection using Roboflow API  
✅ Frame-by-frame video processing using OpenCV  
✅ Automatically annotates bounding boxes with confidence   
✅ Google Drive integration (Colab only)

---

## 📹 Sample Results

 ![Sample Input](https://github.com/user-attachments/assets/e7af9cf1-be79-41f5-8d17-1013cbb518f2)
 ![Sample Output](https://github.com/user-attachments/assets/05b8c932-ee97-4ebe-ace7-1f2aa9d8e792)
 
## 🧠 Model Information

- **Model Type**: YOLOv8
- **Training Platform**: Roboflow Universe
- **Project URL**: [Pothole Detection - Roboflow](https://universe.roboflow.com/aegis/pothole-detection-i00zy)
- **Fallback**: Local YOLOv8n model if API fails

---

## 💻 How to Run (Google Colab Recommended)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

1. Upload your `.mp4` road video when prompted
2. The notebook processes and annotates potholes every 3rd frame
3. The output is saved and available in your Google Drive

---

