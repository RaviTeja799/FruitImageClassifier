# 🍎🍌 Fruit Image Classifier using CNN (TensorFlow/Keras)

This repository contains a beginner-friendly image classification project that uses a **Convolutional Neural Network (CNN)** to classify images of different fruits such as **Apple**, **Banana**, and **Orange**.

The model is built using **TensorFlow/Keras** and trained on a dataset from Kaggle. Ideal for students and beginners in deep learning and computer vision.

---

## 📂 Project Overview

- ✅ Multi-class classification of fruit images
- 🧠 Built from scratch using CNN architecture
- 📈 Includes training visualization (accuracy, loss)
- 📁 Dataset: [Fruits Dataset - Kaggle](https://www.kaggle.com/datasets/shreyapmaher/fruits-dataset-images)
- 📓 Notebook: [`FruitImageClassifier`](./FruitsImageClassifier.ipynb)

---

## 🧠 Tech Stack

- Python 3.x
- TensorFlow / Keras
- NumPy, Matplotlib
- Google Colab (recommended)
- Kaggle for dataset download

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/RaviTeja799/FruitImageClassifier.git
cd FruitImageClassifier
````

### 2. Open in Colab or Jupyter Notebook

* Open [`fruit_classifier.ipynb`](./fruit_classifier.ipynb)
* Follow the instructions to:

  * Upload your `kaggle.json` API key
  * Automatically download the dataset from Kaggle
  * Train the CNN model
  * Test with predictions

---

## 📊 Sample Results

> Visuals of training curves:
>
> * ✅ Accuracy vs Epochs
> * 📉 Loss vs Epochs
>   *(Screenshots can be added here)*

---

## 💾 Save Trained Model

```python
model.save('fruit_classifier_model.h5')
```

You can reload it later using:

```python
from tensorflow.keras.models import load_model
model = load_model('fruit_classifier_model.h5')
```

---

## 📌 To-Do

* [ ] Add MobileNetV2 version (transfer learning)
* [ ] Build Gradio or Streamlit demo
* [ ] Add more fruit categories

---

## 🙏 Credits

* **Dataset**: [Shreya Maher on Kaggle](https://www.kaggle.com/datasets/shreyapmaher/fruits-dataset-images)
* **Model & Code**: Developed for educational and beginner purposes

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
