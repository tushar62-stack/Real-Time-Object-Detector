# Real-Time Object Detection using YOLOv8, OpenCV & Tkinter

This project is a **real-time object detection application** built using **Ultralytics YOLOv8**, **OpenCV**, and a custom **Tkinter-based GUI**.  
It supports both **webcam detection** and **video file detection**, with high accuracy and smooth performance.

---

## 🚀 Features

-  **Real-Time Object Detection (Webcam + Video File)**
-  **YOLOv8s model optimized for high accuracy + speed**
-  **Confidence threshold filtering**
-  **HD 1280×720 detection**
-  **Custom Tkinter GUI for display**
-  **Clean bounding boxes using CVZone**
- **No lag (optimized for performance)**
- 💻 Works offline (if model file is local)

---

## 🛠 Tech Stack

- **Python**
- **Ultralytics YOLOv8**
- **OpenCV**
- **CVZone**
- **Tkinter**
- **Pillow (PIL)**

---

## 📌 How It Works

1. The application opens either:
   - the **webcam feed**, or  
   - a **selected video file**

2. The frames are passed through a YOLOv8 model for object detection.

3. Detected objects are displayed live inside a Tkinter window with:
   - bounding boxes  
   - class labels  
   - confidence scores  

4. Frames are resized and optimized to remove lag while maintaining accuracy.

---

##  Project Structure
