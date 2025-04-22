# Diabetic Retinopathy Detection and Segmentation

This project focuses on detecting and classifying **Diabetic Retinopathy (DR)** stages from fundus images using deep learning techniques, combining both **segmentation (U-Net)** and **classification (MobileNetV2)** models.

---

## 📁 Project Structure

![image](https://github.com/user-attachments/assets/24087d30-b8da-4155-87cc-5d0edd0738e8)


---

## 🎯 Objectives

- Segment key retinal features using **U-Net** models.
- Classify the severity of Diabetic Retinopathy using **MobileNetV2**.
- Generate metrics like **IoU**, **F1 Score**, **Precision**, **Recall**, and **Accuracy** for each segmented class.
- Provide a simple **Flask-based web interface** for classification.

---

## 📊 Sample Output - Segmentation Metrics Table

| Segmentation Task | IoU (Jaccard) | F1 Score | Recall | Precision | Accuracy |
|-------------------|---------------|----------|--------|-----------|----------|
| Blood Vessel      | 0.6723        | 0.7932   | 0.7741 | 0.8371    | 0.7520   |
| Hard Exudate      | 0.6684        | 0.7853   | 0.7708 | 0.8322    | 0.7481   |
| Soft Exudate      | 0.6627        | 0.7904   | 0.7731 | 0.8433    | 0.7599   |
| Haemorrhage       | 0.6572        | 0.7992   | 0.7744 | 0.8195    | 0.7637   |
| Microaneurysm     | 0.6548        | 0.7813   | 0.7668 | 0.8227    | 0.7476   |
| Optical Disc      | 0.6640        | 0.7885   | 0.7705 | 0.8350    | 0.7735   |

> ⚠️ These values are generated for demonstration and may slightly vary each run.

---

## 🧪 Technologies Used

- **TensorFlow / Keras**
- **OpenCV**
- **MobileNetV2**
- **U-Net for segmentation**
- **Scikit-learn** for metrics
- **Flask** for web interface

---

## 🚀 Running the Project

### 1. Create Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate

2. Install Dependencies

pip install -r requirements.txt

3. Start Flask App

cd Classification
python app.py



⸻

⚠️ Note

🧩 Due to file size limitations, I could not upload the trained model files (.h5) to GitHub.
You may download them externally or train your own using the training script.

⸻

📬 Contact

For any queries or collaboration, feel free to reach out!

⸻

⭐️ If you like this project, consider giving it a star!
