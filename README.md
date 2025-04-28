Contrastive Learning for 3D Point Cloud Classification
📄 Project Overview
This project focuses on building a robust and efficient 3D point cloud classification model. It leverages Depthwise Separable Convolutions and T-Net Light (Spatial Transformer Networks) for efficient feature extraction and spatial invariance. Additionally, it explores the use of self-supervised contrastive learning to enhance feature learning without heavy reliance on labeled data.

🧩 Key Features
Efficient Feature Extraction:
Lightweight Depthwise Separable Convolutions reduce computational complexity while maintaining high accuracy.

Robust Spatial Invariance:
T-Net Light modules (3×3 and 64×64 transformations) align point clouds to handle variations in rotation, scale, and translation.

Self-Supervised Contrastive Learning:
Pretraining the model with contrastive loss helps in learning robust features, reducing the need for large labeled datasets.

Comprehensive Evaluation:
Model performance evaluated on ModelNet10 using metrics like accuracy, precision, recall, and F1-score.

🔥 System Workflow
Data Preprocessing & Augmentation

Augmentations: rotation, jittering, scaling, and translation.

Feature Extraction

Using lightweight Depthwise Separable Convolutions for local feature learning.

Spatial Transformation

Alignment using T-Net Light to enhance model robustness.

Classification

Fully connected layers followed by LogSoftmax activation for final prediction.

Self-Supervised Pretraining (Optional)

Contrastive learning is used to pretrain the network.

Model Evaluation

Performance evaluated using standard metrics on ModelNet10 dataset.

📊 Dataset
ModelNet10: A benchmark dataset of 3D CAD models used for training and evaluation.

🚀 Future Scope
Integrating full self-supervised contrastive learning pipelines to further boost performance.

Extending the model to handle larger datasets like ModelNet40.

Deploying the lightweight model in real-world applications such as autonomous driving (LiDAR data), robotics, medical imaging, and AR/VR systems.
