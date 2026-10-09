<div align="center">

# 😷 Face Mask Detection (CNN)

**A convolutional neural network that decides whether a person in a photo is wearing a face mask.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

</div>

---

## ✨ Overview

`t.ipynb` builds a binary image classifier:

- 📂 Reads images from `data/with_mask/` (label `1`) and `data/without_mask/` (label `0`).
- 🖼️ Resizes every image to **128 × 128 RGB** and converts it to a NumPy array.
- 🧠 Trains a Keras `Sequential` CNN (stacked `Conv2D` + `MaxPool2D` layers, 2 output classes).
- 📈 Reaches about **92 % training / validation accuracy** in the epochs recorded in the notebook.

The repository also contains `brain_tumor.ipynb`, a four-class MRI classifier (see the dedicated [brain_tumor](https://github.com/Arashomranpour/brain_tumor) repo).

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/CNN-mask.git
cd CNN-mask
pip install tensorflow keras pillow numpy pandas matplotlib scikit-learn jupyter
jupyter notebook t.ipynb
```

Download a face-mask dataset (for example the Kaggle *Face Mask Detection* dataset) and place it in a `data/` folder with the two sub-folders above.

## 📁 Project Structure

```
.
├── t.ipynb              # Face-mask CNN
└── brain_tumor.ipynb    # MRI tumor classifier
```

## 🛠️ Tech Stack

`TensorFlow` · `Keras` · `Pillow` · `NumPy` · `scikit-learn` · `Matplotlib`
