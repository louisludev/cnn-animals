# 🦁🐆 CNN-Based Animal Classification

A Convolutional Neural Network (CNN) model for classifying **lions** and **Cheetah** based on image data.

---

## 📌 Environment

- **Python**: 3.9.0
- **CUDA**: 11.2.0
- **cuDNN**: 8.1.0
- **Framework**: TensorFlow-GPU

---

## 📂 Datasets

Images were collected and augmented from the following public datasets:

- [Lions or Cheetahs Image Classification (Kaggle)](https://www.kaggle.com/datasets/mikoajfish99/lions-or-cheetahs-image-classification?resource=download)
- [Big Cats Image Classification Dataset (Kaggle)](https://www.kaggle.com/datasets/patriciabrezeanu/big-cats-image-classification-dataset)
- [Animals Dataset (Kaggle)](https://www.kaggle.com/datasets/antobenedetti/animals)

Additionally, 100 more images (50 lions, 50 leopards) were manually collected from the following sources:

- [Lion Image Classification Dataset](https://images.cv/dataset/lion-image-classification-dataset)
- [Leopard Image Classification Dataset](https://images.cv/dataset/leopard-image-classification-dataset)

---

## 🧠 Best Model Download

The best-performing model (`best_model.h5`) is available via Google Drive:

📥 [Download Pretrained Model (.h5)](https://drive.google.com/file/d/1jUpd3Ugnw9aSuCUWtF8wxoczW5PGGZFE/view?usp=sharing)

---

## 📈 Results

Evaluation metrics, training curves, and confusion matrix are provided in the [Jupyter Notebook](./code/train_and_evaluate.ipynb).

Accuracy on the test set: **98%**

---

## 💡 Notes

- This project is part of a graduate research study on wildlife classification using deep learning.
- Images were resized, normalized, and augmented to improve model generalization.
