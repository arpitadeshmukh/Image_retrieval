# 🔍 Image Retrieval System

This project implements an **Image Retrieval System** that identifies and returns visually similar images from a dataset given a query image. The system explores various classical and deep learning-based techniques for feature extraction and image similarity.

## 📌 Highlights

- 📸 Feature extraction using:
  - **SIFT** (Scale-Invariant Feature Transform)
  - **HOG** (Histogram of Oriented Gradients)
  - **Edge Detection**
  - **ResNet** (Deep features)
- 🔍 Retrieval using:
  - **K-Nearest Neighbors (KNN)**
  - **K-Means Clustering**
  - **Support Vector Machines (SVM)**
- 📊 Evaluation metrics:
  - **Precision**
  - **Recall**
- 🏆 **Best performance** achieved using:
  - **Bag of Visual Words (BoVW)** + **ResNet features**

---

## 🧠 Techniques Explored

### Feature Extraction
- SIFT: Local keypoint descriptors
- HOG: Gradient-based global features
- Edge Detection: Simple edge map encoding
- ResNet: Deep feature vectors from pretrained CNN

### Models for Retrieval
- SVM: Trained binary/multiclass classifier for retrieval task
- KMeans: Clustering of visual descriptors into vocabulary (BoVW)
- MLP: trained a MLP with various layers to predict the class of the image

---

## 📈 Evaluation

We evaluated each method using:
- **Precision**
- **Recall**

These metrics allowed us to compare how accurately and completely the system retrieves relevant images for a given query.

---

## 🧪 Results

| Method                  | Precision | Recall |
|-------------------------|-----------|--------|
| SIFT + KNN              | Moderate  | Moderate |
| HOG + SVM               | Moderate  | Low     |
| ResNet + KNN            | High      | High    |
| **BoVW + ResNet (Best)**| ✅ High   | ✅ High |

---

## 🚀 Try It Live

- 🌐 **[Live Demo](https://prml-project-625596018923.us-central1.run.app/)**  
- 📄 **[Project Page](https://storage.googleapis.com/prml-project/index.html)**
- 📄 **[Report](https://storage.googleapis.com/prml-project/image_retrieval_endterm.pdf)**