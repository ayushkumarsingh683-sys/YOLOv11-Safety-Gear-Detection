Markdown
# 🪖 YOLOv11 Safety Gear & Road Object Detection System

An advanced, end-to-end Computer Vision project designed for automated safety compliance monitoring and roadside object detection. This system utilizes the state-of-the-art **YOLOv11** architecture to accurately detect workers' safety equipment (helmets, reflective jackets) and critical traffic objects (traffic cones, vehicles).

---

## 🌟 Key Features
* **Custom Dataset Training:** Trained on a curated dataset processed and augmented via Roboflow.
* **State-of-the-Art Architecture:** Powered by **YOLOv11** for an optimal balance between fast inference speed and high detection accuracy.
* **Real-World Applicability:** Ideal for automated monitoring in construction sites, industrial zones, and traffic management systems.
* **Automated Inference Pipeline:** Python-based script using OpenCV and Ultralytics to process images and generate visual bounding-box outputs seamlessly.

---

## 🛠️ Tech Stack & Tools
* **Deep Learning Framework:** YOLOv11 (Ultralytics)
* **Training Environment:** Google Colab (GPU-accelerated)
* **Dataset Management:** Roboflow (Annotation & Augmentation)
* **Programming Language:** Python
* **Libraries & Tools:** OpenCV, Visual Studio Code, Git

---

## 📂 Project Structure
```text
YOLOv11-Safety-Gear-Detection/
│
├── best.pt                   # Trained custom YOLOv11 model weights
├── main.py                   # Python script for running detection and inference
├── README.md                 # Project documentation
└── test_images/              # Directory containing test inputs and output results
    ├── test.jpeg             
    └── runs/detect/          # Generated bounding-box output directories
🚀 Getting Started & Local Setup
Prerequisites
Ensure you have Python 3.8+ installed on your system along with Visual Studio Code.

Installation
Clone this repository or download the project folder.

Open the project directory in your terminal and install the required dependencies:

Bash
pip install ultralytics opencv-python
Running Inference
To run the model on your test images and generate detection bounding boxes, execute the following command in your terminal:

Bash
python main.py
📊 Results & Performance
The model successfully detects multiple classes including helmets, reflective jackets, traffic cones, and vehicles under varying environmental conditions.

Output images with clear confidence scores and bounding boxes are automatically saved locally in the runs/detect/ directory.

🔮 Future Enhancements
Expanding the dataset size with diverse angles, lighting conditions, and weather scenarios to reduce false negatives.

Increasing training epochs for higher precision.

Integrating real-time webcam and CCTV video stream feeds for live safety monitoring.
