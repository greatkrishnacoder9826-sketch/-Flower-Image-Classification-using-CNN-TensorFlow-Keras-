# 🌸 Flower Image Classification using CNN (TensorFlow & Keras)

A Deep Learning project that classifies flower images into different categories using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

---

## 📌 Project Overview

This project demonstrates how to build, train, and evaluate a Convolutional Neural Network (CNN) for image classification.

The model learns visual patterns from flower images and predicts the correct flower category for unseen images.

This project covers the complete Deep Learning workflow:

- Image Loading
- Data Preprocessing
- Normalization
- Dataset Optimization
- CNN Model Building
- Model Training
- Performance Evaluation
- Prediction on New Images

---

## 🚀 Features

✅ Image Classification using CNN

✅ TensorFlow Dataset Pipeline

✅ Image Normalization

✅ Efficient Data Loading with Cache & Prefetch

✅ Model Accuracy & Loss Visualization

✅ Predict Custom Images

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## 📂 Dataset

The project uses a **Flower Dataset** containing multiple flower categories.

Example Classes:

- 🌼 Daisy
- 🌻 Dandelion
- 🌹 Rose
- 🌷 Tulip
- 🌸 Sunflower

---

## 🧠 CNN Architecture

The model consists of multiple layers including:

- Conv2D
- MaxPooling2D
- Flatten
- Dense
- Softmax Output Layer

The architecture is designed to automatically learn spatial features from images.

---

## ⚙️ Data Preprocessing

Before training:

- Images are resized
- Pixel values are normalized (0–255 → 0–1)
- Training dataset is shuffled
- Dataset is cached
- Prefetching is used for faster training

---

## 📈 Model Training

The model is trained using:

- **Optimizer:** Adam
- **Loss Function:** Sparse Categorical Crossentropy
- **Epochs:** 15
- **Validation Dataset:** Yes

---

## 📊 Performance Visualization

Training includes plots for:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss

These graphs help monitor model performance and detect overfitting.

---

## 🔍 Prediction

After training, the model can predict the class of any new flower image.

Example:

```python
prediction = model.predict(img)
```

The model outputs the most probable flower category.

---

## 📁 Project Structure

```
Flower-CNN/
│
├── CNN_Flower_Classification.ipynb
├── flowers/
│   ├── daisy/
│   ├── rose/
│   ├── tulip/
│   ├── sunflower/
│   └── dandelion/
│
├── README.md
└── requirements.txt
```

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Flower-CNN.git
```

Move into the project folder

```bash
cd Flower-CNN
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📌 Future Improvements

- Transfer Learning (EfficientNet, ResNet50)
- Data Augmentation
- Early Stopping
- Model Checkpoint
- Mobile Deployment
- Web App using Streamlit
- Grad-CAM Visualization

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

---

## 👨‍💻 Author

**Krishna Great**

- 💻 Passionate about AI, Machine Learning, Deep Learning & Data Science
- 🚀 Always learning and building real-world projects

---

## ⭐ Support

If you found this project useful, don't forget to **⭐ Star this repository!**

It motivates me to build more open-source AI projects.
