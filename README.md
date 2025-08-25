This repository contains the implementation of Federated Learning (FL) using a Vision Transformer (ViT-B16) model for skin lesion classification on the HAM10000 and ISIC2019 datasets. The project focuses on developing a privacy-preserving, scalable, and high-performance deep learning framework for dermatological image analysis.
Key Features
1. Vision Transformer (ViT-B16) model with a custom classification head optimized for skin lesion classification.
2. Federated Learning (FL) setup with multiple clients and FedAvg aggregation.
3. Experiments conducted on HAM10000 and ISIC2019 datasets for multi-class classification.
4. Custom data splitting strategy ensuring balanced class distribution among clients.
5. Training logs include accuracy, loss, confusion matrices, and AUC at both client and global levels.
6. Easy-to-configure parameters for:
      1. Number of clients
      2. Number of rounds
      3. Local epochs
      4. Learning rate and optimizer settings
      5. Datasets
        a. HAM10000
               — 10,000 dermatoscopic images across 7 skin lesion classes.
         b. ISIC2019
               — 25,000+ dermatoscopic images across 8 skin lesion classes.

Both datasets are preprocessed with data augmentations and balanced splitting to improve generalization.
