# 👁️ Glaucoma Detection Using Deep Learning

> Early detection saves sight.  
This project leverages **Computer Vision** and **Convolutional Neural Networks (CNNs)** to detect **Glaucoma**, a serious eye disease that can lead to blindness if untreated.

---

## 🧠 Project Overview

Glaucoma affects the **optic nerve** and can lead to **irreversible vision loss**. Our system aims to **automate** the detection process using deep learning techniques, enabling:

- ✅ Early detection  
- ✅ Fast diagnosis  
- ✅ Reduced dependency on expert ophthalmologists

We use **CNNs** to analyze **fundus images** and extract key optic nerve features indicative of glaucoma.

---

## 📊 Datasets Used

This project utilizes multiple open-source datasets to improve robustness:

| Dataset     | Description                             | Images |
|-------------|-----------------------------------------|--------|
| Drishti-GS  | Annotated fundus images                 | 101    |
| RIM-ONE DL  | Retinal images with ground truth masks  | Varies |
| ACRIMA      | Healthy and glaucomatous eye images     | Varies |

> 📌 All datasets are used only for educational and research purposes.

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

## 🧪 Features

- 🖼️ **Image Preprocessing**: Resizing, normalization, and contrast enhancement  
- 🧠 **CNN Architecture**: Designed to classify images as Glaucomatous or Normal  
- 📈 **Model Evaluation**: Accuracy, confusion matrix, and ROC curves  
- 🔁 **Cross-Dataset Testing**: Ensure generalization across different sources

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Dhanalakshmisaladi/glaucoma-detection.git
cd glaucoma-detection
```

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Download the Datasets

- Download **Drishti-GS**, **RIM-ONE DL**, and **ACRIMA** datasets from their official sources.
- Place them in the `datasets/` directory in this structure:

```
datasets/
├── Drishti-GS/
├── RIM-ONE_DL/
└── ACRIMA/
```

### 5. Run Preprocessing Scripts

```bash
python preprocess.py
```

### 6. Train the Model

```bash
python train.py
```

### 7. Evaluate the Model

```bash
python evaluate.py
```

### 8. Test on New Images

```bash
python predict.py --image path_to_image.jpg
```

---

## 📁 Project Structure

```
glaucoma-detection/
├── datasets/         # Contains Drishti-GS, RIM-ONE DL, ACRIMA folders
├── models/           # Trained model checkpoints
├── notebooks/        # Jupyter notebooks for EDA, experiments
├── outputs/          # Logs, result graphs, prediction outputs
├── preprocess.py     # Preprocessing pipeline
├── train.py          # Training script
├── evaluate.py       # Evaluation script
├── predict.py        # Inference script
├── requirements.txt  # Python dependencies
└── README.md         # Project overview
```

---

## 📌 Future Work

- 🔍 Implement **attention-based CNN models** for higher accuracy  
- 🌐 Deploy as a **web application** using **Streamlit** or **Flask**  
- 📊 Add **Grad-CAM visualizations** to explain model predictions  
- 🧾 Integrate with **Electronic Health Records (EHRs)** for smart diagnostics

---

## 🙌 Acknowledgements

- [Drishti-GS Dataset](https://cvit.iiit.ac.in/projects/mip/drishti-gs/mip-dataset2/Home.php)
- [RIM-ONE DL Dataset](https://figshare.com/articles/dataset/RIM-ONE_DL_dataset/3383556)
- [ACRIMA Dataset](https://figshare.com/articles/dataset/ACRIMA_Database/5734304)
- TensorFlow and Keras
- OpenCV and its powerful image processing capabilities

---

## 📬 Contact

**Author**: Saladi Dhanalakshmi
**Email**: saladidhanalakshmi3@email.com  
**LinkedIn**: [linkedin.com/in/dhanalakshmi-saladi-a8a07523b](https://linkedin.com/in/dhanalakshmi-saladi-a8a07523b)  
**GitHub**: [github.com/Dhanalakshmisaladi](https://github.com/Dhanalakshmisaladi)

---

> ⭐ If you found this project helpful, feel free to **star it** and share it with others!
