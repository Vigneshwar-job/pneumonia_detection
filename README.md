# 🫁 Lung Cancer / Pneumonia Detection using Machine Learning

This project uses machine learning and deep learning models to detect **Lung Cancer** and **Pneumonia** from medical imaging data (such as chest X-rays or CT scans) and/or structured patient data (age, smoking habits, etc.). The objective is to enable early diagnosis and assist medical professionals in making faster, data-driven decisions.

---

## 📂 Project Structure

- `Detection.ipynb` – Jupyter Notebook with complete pipeline: data loading, preprocessing, model training, evaluation, and predictions.
- `requirements.txt` – Lists all Python packages required to run the notebook.
- `data/` – Directory for dataset files. Includes sample data or links to download full datasets.
- `models/` – Optional folder for saving trained machine learning or deep learning models (e.g., `.h5` or `.pkl` files).
- `utils/` – Contains reusable helper functions for data preprocessing, augmentation, etc.

---

## 🔍 Features

- Supports binary classification (Cancer vs. Non-Cancer / Pneumonia vs. Normal)
- Image preprocessing using OpenCV
- Model training using TensorFlow/Keras
- Performance evaluation using Accuracy, Confusion Matrix, ROC Curve
- Visualization of training history (loss/accuracy plots)

---

## 📊 Dataset

> **Note**: Data is not included in the repo due to internship and privacy. However you can find it here : 

- [Adovi_Training]([https://www.kaggle.com/datasets](https://github.com/Adaovi/Training---Nov))

Place your dataset inside the `data/` folder and adjust the paths in the notebook if necessary.

---

## ⚙️ Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Vigneshwar-job/pneumonia_detection.git
   cd lung-cancer-detection
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook**:
   Open `Detection.ipynb` in Jupyter Notebook or Google Colab and follow the steps.

---

## 📈 Model Performance

- **Framework**: TensorFlow & Keras
- **Techniques**: CNNs (Convolutional Neural Networks), Image Normalization
- **Metrics**: 
  - Accuracy
  - Precision / Recall
  - F1-Score
  - ROC-AUC

> Early tests show promising results in identifying patterns in lung disease cases.

---

## 📌 Future Enhancements

- Integrate Streamlit or Flask for a user-friendly web interface
- Add Grad-CAM for visual model interpretability
- Extend support to multi-class classification
- Include patient metadata for multimodal learning

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- Adovi Dataset
- TensorFlow & Keras Frameworks
- OpenCV, scikit-learn for preprocessing and model evaluation
