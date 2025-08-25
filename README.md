This repository contains the implementation of Federated Learning (FL) using a Vision Transformer (ViT-B16) model for skin lesion classification on the HAM10000 and ISIC2019 datasets. The project focuses on developing a privacy-preserving, scalable, and high-performance deep learning framework for dermatological image analysis.

Key Features
🧠 Vision Transformer (ViT-B16) model with a custom classification head optimized for skin lesion classification.
🔐 Federated Learning (FL) setup with multiple clients and FedAvg aggregation.
📊 Experiments conducted on HAM10000 and ISIC2019 datasets for multi-class classification.
⚡ Custom data splitting strategy ensuring balanced class distribution among clients.
🧩 Training logs include accuracy, loss, confusion matrices, and AUC at both client and global levels.
🔄 Easy-to-configure parameters for:
      Number of clients
      Number of rounds
      Local epochs
      Learning rate and optimizer settings
      Datasets
        HAM10000
         — 10,000 dermatoscopic images across 7 skin lesion classes.
      ISIC2019
         — 25,000+ dermatoscopic images across 8 skin lesion classes.

Both datasets are preprocessed with data augmentations and balanced splitting to improve generalization.
