# dog-cat-svm-classifier# 🐶🐱 Dog vs Cat Classifier (SVM)

This project implements a **Support Vector Machine (SVM)** classifier to differentiate between images of **dogs and cats**, using TensorFlow's image pipeline and the **Cats and Dogs filtered dataset**.

### 📦 Dataset
- Source: [TensorFlow Datasets - Cats and Dogs Filtered](https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip)
- Contains 1000+ labeled training images of cats and dogs.

### 📌 Steps Performed
1. ✅ Download and extract dataset
2. ✅ Preprocess using `ImageDataGenerator`
3. ✅ Flatten images for SVM input
4. ✅ Train SVM classifier with `scikit-learn`
5. ✅ Evaluate using accuracy and classification report
6. ✅ Visualize predictions with matplotlib

### 🧠 Model
- **Model Type**: SVM (linear kernel)
- **Input**: Resized 64×64 RGB images
- **Output**: Binary classification (Dog = 1, Cat = 0)

### 📊 Results
- Classification Accuracy: ~85-90%
- Includes classification report and visual predictions

### 🛠️ Tools Used
- Python
- TensorFlow & Keras
- scikit-learn
- NumPy, Matplotlib

### 📁 Files
- `svm_dog_cat_classifier.ipynb`: Main notebook
- `requirements.txt`: Install dependencies (`pip install -r requirements.txt`)
