# 🚗 Vehicle Detection Project

## **📌 Project Overview**
This project implements a **vehicle detection system** using **YOLOv8** and **OpenCV**. The system detects vehicles in images and videos, enhancing detection accuracy using **denoising and contrast adjustment techniques**.

## **📂 Project Structure**
```
Vehicle_Detection/
│── dataset/              # Folder for images/videos used for detection
│   ├── sample_image.jpg  # Example image
│   ├── sample_video.mp4  # Example video
│── vehicle_detection.py  # Main script for detection
│── requirements.txt      # Required dependencies
│── README.md             # Project documentation
```

## **🔧 Installation**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/erezkalifa/Vehicle_Detection.git
cd Vehicle_Detection
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```
If `pip` is not recognized, try:
```bash
python -m pip install -r requirements.txt
```

## **▶️ Running the Project**
### **Option 1: Run with PyCharm**
1. Open PyCharm and load the `Vehicle_Detection` folder.
2. Go to **Run → Edit Configurations**.
3. Click **➕ (Add Configuration)** → Select **Python**.
4. Under **Script Path**, choose `vehicle_detection.py`.
5. Click **OK** and press **Run ▶️**.

### **Option 2: Run with Terminal/CMD**
```bash
python vehicle_detection.py
```
Or if `python` is not recognized:
```bash
py vehicle_detection.py
```

## **🖼️ Using the GUI**
1. Once the program starts, a link (e.g., `http://127.0.0.1:7860`) will be displayed.
2. Open the link to access the graphical interface.
3. Choose one of the following:
   - **Upload an image/video for detection**.
   - **Select a file from the dataset**.
4. Click **Confirm Selection**.
5. The result will be displayed with bounding boxes highlighting detected vehicles.

## **⚙️ Features**
✅ Vehicle detection using **YOLOv8**
✅ Supports **images and videos**
✅ Enhances image quality for better detection
✅ User-friendly **Gradio GUI**
✅ Works with **custom uploads or dataset files**

## **🛠️ Troubleshooting**
### **1️⃣ Pip Not Recognized**
Run:
```bash
python -m ensurepip --default-pip
python -m pip install --upgrade pip
```

### **2️⃣ Dataset Folder Not Found**
If `dataset/` folder is missing, create it:
```bash
mkdir dataset
```

### **3️⃣ GitHub Authentication Issue**
Ensure you are logged in via SSH or use a Personal Access Token (PAT).

---

**📌 Now your project is ready to run! 🚀**

