# Object Detection & Tracking – CodeAlpha AI Internship

This project focuses on **real-time vehicle detection and tracking** using **YOLOv8** for object detection and **Deep SORT** for object tracking. It processes video frames, detects vehicles (cars, buses, trucks, motorcycles), assigns unique IDs, and tracks them across frames.

Developed as part of my **AI Domain Internship at CodeAlpha**, this project demonstrates the application of **Computer Vision, Deep Learning, and Object Tracking algorithms** in solving real-world problems like **traffic monitoring and surveillance**.

---

## ✨ Features

✅ Real-time object detection using **YOLOv8**.
✅ Vehicle-specific tracking (Car, Truck, Bus, Motorcycle).
✅ Multi-object tracking with **unique IDs** using Deep SORT.
✅ Annotated bounding boxes with **labels + IDs**.
✅ Works with **video files (.mp4)** or **webcam streams**.
✅ Saves output in **MP4 format** for easy sharing and analysis.
✅ Fully compatible with **Google Colab GPU runtime**.

---

## 🛠️ Tech Stack

* **Programming Language:** Python 3
* **Libraries & Frameworks:**

  * [OpenCV](https://opencv.org/) – video input/output processing
  * [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics) – pre-trained deep learning object detection model
  * [Deep SORT](https://arxiv.org/abs/1703.07402) – tracking algorithm
  * [NumPy](https://numpy.org/) – array operations
* **Platform:** Google Colab (GPU-enabled runtime for speed)

---

## 📂 Project Structure

```
CodeAlpha_Object-Detection-and-Tracking/
│── yolov8_deepsort_tracking.ipynb   # Main Google Colab Notebook
│── output.mp4                       # Generated video with detection + tracking
│── README.md                        # Project documentation
```

---

## ⚙️ Setup & Installation

Since this project is designed for **Google Colab**, setup is simple:

### 1️⃣ Clone the Repository in Colab

```python
!git clone https://github.com/Fardeen37/CodeAlpha_Object-Detection-and-Tracking.git
%cd CodeAlpha_Object-Detection-and-Tracking
```

### 2️⃣ Install Dependencies

Run inside Colab:

```python
!pip install ultralytics opencv-python lap filterpy
```

### 3️⃣ Upload or Use Sample Video

You can upload a video (`.mp4`) directly to Colab, or provide a video link. Example:

```python
from google.colab import files
uploaded = files.upload()  # upload your own video file
```

### 4️⃣ Run the Notebook

* Open `yolov8_deepsort_tracking.ipynb` in **Colab**.
* Execute all cells step by step.
* The processed video (`output.mp4`) will be saved and ready for download.

---

## 🎯 Example Workflow

* **Input Video:** A sample road traffic video (`cars.mp4`).
* **Processing:**
  * YOLOv8 detects vehicles in each frame.
  * Deep SORT assigns unique IDs and tracks vehicles.
  * Bounding boxes + labels (`Car 1`, `Bus 3`, etc.) are drawn.
* **Output Video:** Saved as `output.mp4` with annotated vehicles and tracking IDs.

---

## 📌 Real-World Applications

🚦 **Traffic Monitoring:** Count and track vehicles in real time.
🛣️ **Smart Cities:** Improve road safety and traffic flow analysis.
🚘 **Vehicle Analytics:** Collect data for transport planning.
🛡️ **Surveillance Systems:** Enhance public security monitoring.
📊 **Research:** Use as a foundation for advanced AI-based vision systems.

---

## 🙌 Internship Project

This repository is part of my **AI Domain Internship at [CodeAlpha](https://codealpha.tech/)**, where I implemented **Object Detection & Tracking** using state-of-the-art deep learning models.

It demonstrates the ability to:

* Apply **pre-trained deep learning models** to real-world data.
* Combine **detection + tracking algorithms** for practical AI solutions.
* Deploy and test on **GPU environments like Google Colab**.

---

## 📜 License

This project is open-source under the **MIT License**. Feel free to use, modify, and build upon it.

---

## 🚀 Try It Yourself

Click the badge below to open this project in **Google Colab** and run it instantly:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1B_P0nWMpXXs-1nIKwOegRvVxW8Hi-7kv)

---
