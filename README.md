# Audio-Visual-Deepfake
Deepfake video detection framework leveraging ResNet18 and EfficientNet feature extractors, GRU-based temporal learning, attention mechanisms, and imbalance handling techniques such as GAN, T-SMOTE, and Random Sampling for multimodal classification on the FakeAVCeleb dataset.

Deepfake Detection using ResNet18 and EfficientNet
This project presents a multimodal deepfake detection framework that combines visual and temporal information from videos for accurate classification of real and fake content. The system utilizes pretrained ResNet18 and EfficientNet models for feature extraction, GRU networks for temporal sequence learning, and attention mechanisms to identify important frames.
To address class imbalance in the FakeAVCeleb dataset, various balancing techniques including GAN-based augmentation, T-SMOTE, and Random Sampling are employed. The extracted audio and visual features are fused to perform binary classification of deepfake videos.
Key Features
ResNet18 and EfficientNet backbones
GRU-based temporal modeling
Temporal Attention mechanism
Audio–video feature fusion
GAN-based data augmentation
T-SMOTE oversampling
Random sampling techniques
Transfer learning and fine-tuning
Early stopping and gradient clipping
Dataset
FakeAVCeleb v1.2
Technologies
Python
PyTorch
OpenCV
Torchvision
Scikit-learn
NumPy
Matplotlib
