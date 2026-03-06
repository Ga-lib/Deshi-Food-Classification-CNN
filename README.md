# Deshi-Food-Classification-CNN
A Deep Learning project to classify 60 different types of Bangladeshi (Deshi) food using ConvNeXtTiny and Data Augmentation.


🍲 Deshi Food Classification (60 Classes)
This project uses Deep Learning to classify 60 different types of Bangladeshi (Deshi) cuisine. It leverages Transfer Learning with the ConvNeXtTiny architecture and custom Data Augmentation to achieve state-of-the-art performance.

📊 Performance Summary
Final Test Accuracy: 97.95%
Final Test Loss: 0.0913
Number of Classes: 60
Architecture: ConvNeXtTiny (Fine-tuned)

📁 Dataset
The model was trained on the DeshiFood_60 dataset, which consists of images categorized into 60 distinct food types.
Source: The dataset was sourced via Kaggle/Google Drive.
Structure: 60 folders, each representing a specific food category (e.g., Biryani, Pitha, Bhorta, etc.).
Preprocessing: Images were resized to 224x224 and processed using a custom augmentation pipeline to improve model robustness.


🛠️ Tech Stack
Framework: TensorFlow / Keras
Architecture: ConvNeXtTiny
Tools: Python, NumPy, Matplotlib, Scikit-learn
Environment: Google Colab (with GPU acceleration)


🚀 Key Features
Smart Data Loading: Uses image_dataset_from_directory with an 80/10/10 split for training, validation, and testing.
Advanced Augmentation: Includes Random Rotation, Zoom, Contrast, and Brightness adjustments to prevent overfitting.
Fine-tuning: The base model layers were set to trainable to adapt specifically to the nuances of Bangladeshi food textures and colors.
Visualization: Detailed Confusion Matrix and Classification Reports are included to analyze performance across all 60 categories.


Acc and Loss:

<img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/4fd25007-37b1-4cce-b6fe-9ebb541efda0" />


Classification report and confusion matrices:

<img width="2309" height="2479" alt="image" src="https://github.com/user-attachments/assets/4634b9c6-9d4b-4664-ac59-54279e9b113a" />
<img width="2304" height="2479" alt="image" src="https://github.com/user-attachments/assets/08a91014-77eb-44c1-aa65-a7fc1f3f7472" />



