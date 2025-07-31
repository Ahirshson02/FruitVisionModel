# Fruit Quality Classifier 🍎🍌🍇

A machine learning project built with TensorFlow and Python to classify fruit as **ripe**, **rotten**, or **preserved** using the FruitVision dataset. This project explores custom CNN architectures alongside transfer learning to achieve high classification accuracy.

---

## 🚀 Project Overview

This project investigates how Convolutional Neural Networks (CNNs) can classify the quality of fruit. It was motivated by public health concerns, particularly the use of **formalin** as a preservative on fruit, though the current model focuses solely on image-based classification.

### Key Features:
- Built and evaluated **multiple CNN architectures**, including:
  - Custom CNN models
  - Fine-tuned pre-trained models (transfer learning)
- **Achieved up to 91% validation accuracy** with transfer learning, improving from 50–60% in early custom models
- Explored and mitigated **overfitting** through architectural adjustments and preprocessing
- Conducted a **literature review** of CNN models used in similar food-quality and object classification tasks

---

## 🧠 Technologies Used

- **Python**
- **TensorFlow / Keras**
- **NumPy / Pandas / Matplotlib**
- **FruitVision Dataset**
- **Jupyter Notebook / VS Code**

---

## 📊 Dataset

The [FruitVision dataset]([https://www.kaggle.com/datasets](https://data.mendeley.com/datasets/xkbjx8959c/2)) includes labeled images of fruits categorized by ripeness and preservation state. Dataset preprocessing included resizing, normalization, and augmentation.

---

## 🧪 Results

| Model Type         | Validation Accuracy |
|--------------------|---------------------|
| Initial Custom CNN | ~50–60% (high overfitting) |
| Optimized Custom CNN | ~80%               |
| Transfer Learning (e.g., MobileNet, ResNet) | **~91%**               |

---

## ⚠️ Limitations

- The model does **not directly detect formalin**; rather, it classifies based on visual signs that may correlate with preservation.
- Not integrated into an end-to-end application (e.g., no UI or deployment layer).
- The project remains a **research prototype**.

---

## 📝 Future Work

- Explore additional datasets or real-world samples with known preservative use.
- Improve real-time classification through model compression and optimization.
- Build a lightweight mobile app or web tool for demonstration.

---

## 📂 Project Structure





# Necessary Libraries/Dependencies
Python - version 3.9-3.12 (subversions acceptable)
Tensorflow (I used version 2.19)
Matplotlib (I used version 3.10.1)
Scikit-learn (I used version 1.6.1)

Install Commands:
"pip install tensorflow" OR "pip install tensorflow==2.19"
"pip install matplotlib" OR "pip install matplotlib==3.10.1"
"pip install scikit-learn" OR "pip install scikit-learn==1.6.1"

# Models
All the models included in the written report and presentation are saved as .keras files, and their repsective code can be found in the ml-fruitvision.ipynb file

# Evaluation
For quick and easy evaluation without training, you can run the saved models by running code cells 2 and then cell 1. Cell 2 must run first to initialize the test_dataset
