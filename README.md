#  Bangladeshi Medicinal Leaf Classification

This deep learning project focuses on classifying various Bangladeshi medicinal plant leaves using Convolutional Neural Networks (CNNs) and transfer learning with state-of-the-art architectures. The primary objective is to build an efficient image classifier that can assist in the identification of medicinal plants from leaf images.

---

##  Dataset

The dataset contains images of Bangladeshi medicinal leaves and was accessed via Google Drive. It includes preprocessed, resized, and augmented images, organized into class-wise folders.

**Path used**:  
`/content/drive/MyDrive/Dataset/MP_OG_resized_augmented_merged`

---

##  Models Used

The following pre-trained CNN architectures were explored using transfer learning (`include_top=False`):

-  VGG16  
-  ResNet50  
-  InceptionV3  
-  MobileNetV2  
-  EfficientNetB0  

Custom layers such as `Conv2D`, `MaxPooling2D`, `Flatten`, `Dense`, `Dropout`, `BatchNormalization`, and `GlobalAveragePooling2D` were added on top of the base models.

---

##  Data Augmentation

Used `ImageDataGenerator` to apply common image augmentation techniques:
- Rescaling
- Zooming
- Horizontal flipping
- Shearing
- Brightness adjustment

---

##  Features

- Transfer learning for high accuracy with limited data  
- Custom CNN layers for flexibility  
- Early stopping to prevent overfitting  
- Modular codebase for model switching and tuning

---

##  Current Limitation

Due to limitations in computational resources (Colab CPU/GPU), the full training process was not completed. As a result, metrics such as accuracy, precision, recall, confusion matrix, and classification reports have **not yet been generated**.

---

##  Future Work

The following tasks are planned as part of project completion and improvement:

-  Run full training cycles for all selected models  
-  Evaluate models using accuracy, precision, recall, F1-score, confusion matrix  
-  Visualize model comparisons using training/validation plots  
-  Perform hyperparameter tuning for better performance  
-  Experiment with ensemble methods and lightweight architectures  
-  Deploy the best model via a web interface or mobile app

---

##  Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Google Colab  

---

##  Author

**Abdullah Kaisar Fardin**  

