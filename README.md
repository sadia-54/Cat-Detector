# 🐱 Cat Detector using YOLOv8

This project trains a custom object detection model using YOLOv8 to detect cats in images. The training was done on Google Colab using a dataset of over 700 labeled cat images sourced from Roboflow. The model was trained for 70 epochs and can accurately detect cats in images.

---

## 🔍 Sample Output

*![Cat Detection Result](runs/detect/predict/cat1(2).jpg)*

---

## ✨ Features

- Custom-trained YOLOv8 model for cat detection
- Dataset sourced from Roboflow (700+ images)
- Split into train/val/test sets
- Trained for 70 epochs on Colab
- Supports images

---

## ⚙️ Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/sadia-54/Cat-Detector.git
cd Cat-Detector

##  📁 Dataset

- **Source**: [Roboflow](https://app.roboflow.com/sadia-farzana-jessi-xya6i/cat-detect-4ure2-mvgfa/1/)
- **Content**: 780 labeled cat images
- **Format**: YOLOv8 compatible (images + `.txt` label files)
- **Structure**:

dataset/
├── train/
│ ├── images/
│ ├── label/
├── test/
│ ├── images/
│ ├── label/
├── val/
│ ├── images/
│ ├── label/

# Install Dependencies (for local use)

pip install ultralytics opencv-python

```markdown
# 🙏 Acknowledgements
```bash
- Ultralytics YOLOv8

- Roboflow for dataset hosting and format conversion

- Google Colab for free cloud GPU access

# 📄 License
This project is licensed under the MIT License. Feel free to use and modify it for your own purposes.


