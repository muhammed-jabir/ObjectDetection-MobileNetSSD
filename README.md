# ObjectDetection-MobileNetSSD
Beginner-friendly real-time object detection project using Python, OpenCV, and the MobileNetSSD deep learning model. Detects common objects such as person, car, dog, bottle, etc., through a live webcam feed.

# 🔍 Real-Time Object Detection using MobileNetSSD + OpenCV

This project demonstrates **real-time object detection** using the **MobileNetSSD deep learning model** and **OpenCV's DNN module**.  
It runs through a webcam feed and detects 20 common objects such as **person, car, dog, cat, bottle, chair**, and more.

---

## 🚀 Features
- Real-time webcam object detection  
- Powered by **MobileNetSSD (SSD + MobileNet architecture)**  
- Detects 20 common object categories  
- Beginner-friendly Python code  
- Uses OpenCV’s high-speed DNN module  
- Easy to run on any system (no GPU required)

---

## 📁 Project Structure
ObjectDet/
│
├── object.py # Main object detection script
├── deploy.prototxt # Model architecture
├── MobileNetSSD_deploy.caffemodel # Model weights (not included due to size)
└── README.md # Documentation


---

## 📥 Download Model Files (Required)

To run the project, download the MobileNetSSD model files:

- **MobileNetSSD_deploy.caffemodel**  
  https://github.com/chuanqi305/MobileNet-SSD/raw/master/MobileNetSSD_deploy.caffemodel

- **deploy.prototxt**  
  https://github.com/chuanqi305/MobileNet-SSD/raw/master/deploy.prototxt

Place both files in the project folder.

---

## 🛠 Requirements

Install these Python packages:

```bash
pip install opencv-python
pip install numpy
▶️ How to Run

Clone the repository:

git clone https://github.com/your-username/ObjectDetection-MobileNetSSD.git


Navigate to the folder:

cd ObjectDetection-MobileNetSSD


Run the object detection script:

python object.py


Press Q to close the webcam window.

🧠 How It Works

Input frame from webcam → converted to a blob

Blob passed through SSD model → predictions generated

Bounding boxes + labels drawn on screen in real-time

📝 License

This project is open-source and free to use for learning and development.

🤝 Contributing

Pull requests are welcome!
If you have improvements or new ideas, feel free to contribute.

⭐ Support

If you found this project helpful, consider giving it a star ⭐ on GitHub!

---

If you want, I can also generate:

✔ Project thumbnail image  
✔ Badges (Python version, OpenCV, Model type)  
✔ A cleaner repo structure  
✔ A description to paste into your LinkedIn project post  

Just tell me!

