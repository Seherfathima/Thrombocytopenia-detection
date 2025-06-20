# Thrombocytopenia-detection 
This project focuses on detecting *Thrombocytopenia* (a condition marked by abnormally low platelet count) from blood smear images using *YOLOv3* for platelet detection and *K-Nearest Neighbors (KNN)* for classification.

## 📌 Project Objectives

- To assist medical professionals in detecting thrombocytopenia efficiently using automation.
- To reduce human error and time involved in manual analysis of platelet count.
- To leverage image processing and machine learning for medical diagnostics.

## 🛠️ Technologies & Tools Used

| Component        | Tool / Framework |
|------------------|------------------|
| Object Detection | YOLOv3           |
| Classification   | K-Nearest Neighbors (KNN) |
| Programming      | Python           |
| Libraries        | OpenCV, NumPy, scikit-learn, Matplotlib |
| Dataset Type     | Blood Smear Images |
| IDE              | VS Code |

## 🚀 How It Works

1. *YOLOv3* is used to detect platelets in blood smear images.
2. The detected platelet regions are extracted and preprocessed.
3. A *KNN classifier* is trained to classify whether the image indicates thrombocytopenia or normal condition.
4. The system outputs a prediction along with a confidence score.

## 📸 Sample Output

> Example:
- Input: Blood smear image
- Detected Platelets: 15
- Prediction: *Thrombocytopenia Detected*

![Sample Output](Assets/sample_output.jpg)

## 🧪 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/Seherfathima/thrombocytopenia_detection.git
cd thrombocytopenia_detection

# Install dependencies
pip install -r requirements.txt

# Run the detection
python platelet_detection.py

# Run classification
python thrombocytopenia_classifier.py
