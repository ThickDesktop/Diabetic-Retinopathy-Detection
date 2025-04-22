# Diabetic Retinopathy Detection and Segmentation

This project focuses on detecting and classifying **Diabetic Retinopathy (DR)** stages from fundus images using deep learning techniques, combining both **segmentation (U-Net)** and **classification (MobileNetV2)** models.

---

## 📁 Project Structure

![image](https://github.com/user-attachments/assets/3200e2d7-ebcb-4cdf-ac29-587e88292505)

---

## 🎯 Objectives

- Segment key retinal features using **U-Net** models.
- Classify the severity of Diabetic Retinopathy using **MobileNetV2**.
- Generate metrics like **IoU**, **F1 Score**, **Precision**, **Recall**, and **Accuracy**.
- Provide a simple **Flask** web interface.

---

## 📊 Sample Output - Segmentation Metrics

| Segmentation Task | IoU (Jaccard) | F1 Score | Recall | Precision | Accuracy |
|-------------------|---------------|----------|--------|-----------|----------|
| Blood Vessel      | 0.6723        | 0.7932   | 0.7741 | 0.8371    | 0.7520   |
| Hard Exudate      | 0.6684        | 0.7853   | 0.7708 | 0.8322    | 0.7481   |
| Soft Exudate      | 0.6627        | 0.7904   | 0.7731 | 0.8433    | 0.7599   |
| Haemorrhage       | 0.6572        | 0.7992   | 0.7744 | 0.8195    | 0.7637   |
| Microaneurysm     | 0.6548        | 0.7813   | 0.7668 | 0.8227    | 0.7476   |
| Optical Disc      | 0.6640        | 0.7885   | 0.7705 | 0.8350    | 0.7735   |

---

## 🧪 Technologies Used

- TensorFlow / Keras
- MobileNetV2
- U-Net
- OpenCV
- Scikit-learn
- Flask

---

## 🚀 How to Run

1. Create a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate

	2.	Install dependencies:

pip install -r requirements.txt


	3.	Launch the Flask app:

cd Classification
python app.py



⸻

⚠️ Note

📂 Due to GitHub file size limitations, the trained models could not be uploaded here.

🔗 You can download the complete project and trained models from:
Google Drive Project Folder

⸻

📬 Contact

For questions or suggestions, feel free to reach out!

⸻

⭐ If you find this helpful, consider starring the project on GitHub!
