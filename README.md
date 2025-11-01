🧠 Alzheimer MRI Classification with CNN

This project builds a Convolutional Neural Network (CNN) model to classify MRI brain scans into different stages of Alzheimer’s Disease — from Non-Demented to Moderate Demented — using deep learning.
It’s not just another CNN; it’s a step toward faster, more accurate early detection of Alzheimer’s through medical imaging.

🚀 Project Overview
The model is trained on the Augmented Alzheimer MRI Dataset
, which contains MRI scans categorized by the level of dementia.
The goal is to automate classification and support diagnostic insights for healthcare research.

📂 Dataset Structure
The dataset includes four main classes:
🧩 NonDemented — No signs of Alzheimer’s
🧠 VeryMildDemented — Early signs of dementia
🌀 MildDemented — Clear symptoms of mild dementia
🔥 ModerateDemented — Advanced Alzheimer’s stage

⚙️ Project Workflow
Data Splitting → Train / Validation split
Data Inspection → Count images & visualize samples
Image Preprocessing → Data augmentation with ImageDataGenerator
CNN Model Building → Layered architecture for feature extraction
Callbacks → EarlyStopping and ModelCheckpoint for best performance
Training & Evaluation → Accuracy and loss tracking
Predictions & Testing → Class prediction and result visualization
Performance Report → Classification report and confusion matrix

🧩 Model Architecture
A custom-built CNN with:
Multiple convolutional layers for spatial feature extraction
MaxPooling for dimensionality reduction
Dropout for regularization
Dense layers for final classification

📈 Results
Metric	    Train Accuracy	Validation Accuracy
Accuracy	  ~95%	           ~92%
Loss	      ↓ steadily	     ↓ consistently
(Results may vary slightly depending on training environment.)

🧠 Future Work

Integrate Grad-CAM for interpretability
Experiment with transfer learning (e.g., ResNet, EfficientNet)
Build a web interface for real-time MRI predictions

👨‍💻 Author
Ahmed Elhfnawi
AI/ML Engineer
