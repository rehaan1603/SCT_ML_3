# 🐱🐶 Cat vs Dog Image Dataset - Task 3

This repository (`SCL_ML_3`) contains a dataset of cat and dog images under the `Task 3/` directory. It is intended for image classification tasks using machine learning models such as SVM, CNNs, etc.

---

## 📁 Folder Structure

```
Task 3/
├── Cats/
│   ├── cat1.jpg
│   ├── cat2.jpg
│   └── ...
└── Dogs/
    ├── dog1.jpg
    ├── dog2.jpg
    └── ...
```

- `Cats/`: Contains images of cats labeled as class `0`.
- `Dogs/`: Contains images of dogs labeled as class `1`.

---

## 🧠 How to Use

This dataset can be used to:
- Train a binary image classifier
- Explore SVM and feature flattening
- Test image preprocessing pipelines
- Build a computer vision project using Scikit-learn or TensorFlow

Example Python snippet:
```python
from PIL import Image
import numpy as np
import os

# Load, resize, and flatten images for SVM
```

> 🔗 Full training code is available in `main.py` or `classifier.ipynb`.

---

## 📦 Dataset Details

| Class | Label | Description          |
|-------|-------|----------------------|
| Cats  | 0     | Images of cats       |
| Dogs  | 1     | Images of dogs       |

- All images are resized to 128x128 pixels.
- Format: RGB images

---

## 🛠 Tools & Libraries Used

- Python 🐍
- NumPy
- Pillow (PIL)
- scikit-learn
- matplotlib

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/rehaan1603/SCL_ML_3.git
   ```

2. Navigate into the repo:
   ```bash
   cd SCL_ML_3
   ```

3. Run the training script:
   ```bash
   python main.py
   ```

---

## 🙋‍♂️ Author

- **Rehaan**  
  🔗 [GitHub](https://github.com/rehaan1603)

---

## 📄 License

This project is open-source and available for educational use.
