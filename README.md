# Face-Detection
Real-Time Age, Gender, and Emotion Detection with Confidence Scores

Project Description:
This project is a **real-time face analysis system** that detects **age, gender, and emotion** from video streams using **OpenCV, DeepFace, and a deep learning-based CNN model**. The application provides **live predictions with confidence scores** and **stores the results** in CSV and JSON files for future analysis.  

The system supports both **USB webcams** and **IP camera streams (such as an iPhone camera)** and features a **Tkinter-based GUI** for ease of use.  

---

Key Features:

✅ **Real-Time Face Detection:**  
- Uses OpenCV's `haarcascade_frontalface_default.xml` to detect faces in a live video stream.  

✅ **Age & Gender Classification:**  
- **Deep Learning Models (Caffe-based CNNs)** predict age and gender.  
- Age is categorized into predefined ranges (e.g., 0-2, 4-6, 8-12, etc.).  

✅ **Emotion Recognition:**  
- **DeepFace framework** analyzes facial expressions to determine emotions (e.g., happy, sad, neutral, etc.).  

✅ **Confidence Scores:**  
- Each prediction (age, gender, emotion) includes a **confidence percentage** to indicate reliability.  

✅ **Live Visualization:**  
- Detected faces are displayed with **bounding boxes** and **text overlays** showing predictions.  

✅ **Data Logging:**  
- Results are **saved to CSV and JSON files** for record-keeping and analysis.  

✅ **Graphical User Interface (GUI):**  
- Built with **Tkinter** for user-friendly interaction.  
- **Buttons to manually trigger detections** and **a text display for structured results**.  

✅ **Support for External IP Camera Streams:**  
- Configured for **iPhone streaming** via **DroidCam or IP Webcam apps**.  
- Can be adapted for other IP cameras.  

---

Technologies Used:
- **Python** (Main Programming Language)  
- **OpenCV** (Face Detection, Image Processing)  
- **DeepFace** (Emotion Recognition)  
- **Caffe-based CNN Models** (Age & Gender Classification)  
- **Tkinter** (GUI for real-time visualization)  
- **Pandas & JSON** (Data storage and logging)  

