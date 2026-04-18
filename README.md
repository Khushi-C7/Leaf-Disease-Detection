🌿 Leaf Disease Detection using Vision Transformer (ViT)
📌 Overview
This project implements a deep learning-based image classification system for detecting plant leaf diseases using a Vision Transformer (ViT) model. The pipeline includes data preprocessing, model training, evaluation, and interpretability techniques.
The goal is simple but practical:
help identify plant diseases early using AI, which can directly impact agriculture productivity.

🚀 Key Features


Vision Transformer (ViT) for image classification


Custom dataset handling using ImageFolder


Data splitting (Train / Validation / Test)


Training with:


Early stopping


Validation monitoring




Model evaluation using:


Accuracy


Confusion Matrix


ROC Curve




Visualization tools:


Dataset samples


Class distribution


t-SNE feature visualization




Model interpretability using Grad-CAM


Misclassification analysis



🧠 Model Architecture


Backbone: Vision Transformer (ViT) (via timm)


Pretrained weights used for better convergence


Custom classification head for disease classes



📂 Dataset


Dataset is downloaded using kagglehub


Images are organized into class folders


Automatically split into:


70% Training


15% Validation


15% Testing





⚙️ Tech Stack


Python


PyTorch


timm (PyTorch Image Models)


Torchvision


Scikit-learn


Matplotlib & Seaborn


Albumentations


Grad-CAM



🏋️ Training Details


Loss Function: CrossEntropyLoss


Optimizer: Adam / AdamW (depending on config)


Epochs: 10


Early stopping patience: 3



📊 Evaluation Metrics


Accuracy


Confusion Matrix


Class-wise accuracy


ROC-AUC curves



🔍 Visualizations Included


📷 Sample images from dataset


📊 Class distribution plot


📉 Confusion matrix


📈 ROC curves


🧬 t-SNE feature space visualization


❌ Misclassified samples analysis



🔥 Model Interpretability
Grad-CAM is used to visualize:


Which parts of the leaf image the model focuses on


Whether the model is actually learning disease patterns or just noise



📌 Results (What Actually Matters)


Model achieves strong classification performance on test data


Visualizations confirm meaningful feature learning


Grad-CAM shows attention on infected regions (not random areas)



⚠️ Limitations (Don’t Ignore This)


Small dataset → risk of overfitting


ViT is data-hungry → performance depends heavily on dataset size


Real-world deployment needs:


More diverse data


Mobile optimization


Robust preprocessing


🎯 Why This Project Matters
Agriculture is still heavily dependent on manual inspection.
This system shows how AI can:


Reduce human effort


Improve accuracy


Enable early disease detection



If you want, I can:


Make this resume-ready (ATS optimized)


Turn it into a GitHub project that actually stands out


Or brutally review your project like a recruiter would (and fix weak points)

