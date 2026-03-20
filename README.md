
# 🇮🇳 Indian Sign Language Recognition System

##  Overview
This project focuses on building an **image classification system** to recognize **Indian Sign Language (ISL)** gestures using machine learning and deep learning techniques.

The workflow includes:
- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Training multiple ML & DL models
- Performance comparison and evaluation

The goal is to explore how effectively different algorithms can classify hand gestures and contribute toward **assistive AI technologies**.

---

##  Key Features

-  Comprehensive **EDA (Exploratory Data Analysis)**
-  Implementation of **6 different models**
-  Feature engineering for traditional ML models
-  Image preprocessing and normalization
-  Data augmentation for improved generalization
-  Model comparison using accuracy and visualizations
-  Confusion matrix and classification report

---

##  Models Implemented

### 🔹 Classical Machine Learning Models
- Decision Tree
- K-Nearest Neighbors (KNN)
- Random Forest
- Support Vector Machine (SVM)

###  Deep Learning Models
- Basic CNN
- Deep CNN

---

##  Project Structure

```

├── dataset/ <br>
├── Indi_Sign_Lang_Prediction.ipynb <br>
├── README.md <br>

```

---

##  Tech Stack

- Python 
- NumPy, Pandas
- Matplotlib, Seaborn
- OpenCV
- Scikit-learn
- TensorFlow / Keras

---

##  Exploratory Data Analysis (EDA)

The project includes multiple visual analyses:

- Class distribution
- Sample images
- Image dimension analysis
- Pixel intensity distribution
- Color channel distribution
- PCA visualization (feature space)

These help in:
- Detecting class imbalance
- Understanding dataset structure
- Improving preprocessing decisions

---

##  Data Preprocessing

- Image resizing (uniform dimensions)
- Normalization (0–1 scaling)
- Label encoding
- Train-test split

---

##  Data Augmentation

Applied to improve generalization:
- Rotation
- Flipping
- Zooming
- Shifting

---

##  Model Training

### Classical ML:
- Images flattened into 1D vectors

### Deep Learning:
- CNN architectures with:
  - Convolution layers
  - MaxPooling
  - Dense layers

---

##  Model Performance

| Model         | Accuracy |
|--------------|---------|
| Decision Tree | 90.35% |
| KNN           | 98.89% |
| Random Forest | 99.20% |
| **SVM**       | **99.70%** |
| CNN           | 85.63% |
| Deep CNN      | 90.25% |

---

## Key Insights

-  **SVM achieved the highest accuracy (99.7%)**
-  Classical ML models outperformed CNN models in this case
-  Dataset size and feature representation significantly affect deep learning performance
-  Random Forest and KNN also showed strong results (>98%)

---

##  Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

##  Visualizations

- Model comparison bar chart
- Confusion matrix heatmap
- PCA plots

---

##  Conclusion

This project demonstrates that:

> Classical machine learning models can outperform deep learning models on moderate-sized image datasets when proper feature engineering is applied.

The system highlights the potential of AI in:
- Assistive communication tools
- Real-time gesture recognition systems
- Accessibility technology

---

##  Future Improvements

-  Use larger and more diverse datasets
-  Apply transfer learning (ResNet, MobileNet)
-  Real-time gesture detection using webcam
-  Deploy as a web/mobile application
-  Convert gestures into speech/text output

---

##  How to Run

1. Clone the repository:
```

git clone <your-repo-link>

```

2. Install dependencies:
```

pip install -r requirements.txt

```

3. Run the notebook:
```

jupyter notebook

```

---

##  Contribution

Contributions are welcome! Feel free to:
- Open issues
- Suggest improvements
- Submit pull requests

---

##  License

This project is open-source and available under the MIT License.

---

##  Acknowledgment

This project is inspired by the need to build **inclusive AI systems** that improve accessibility for the deaf and hard-of-hearing community.

```

