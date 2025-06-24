# Improving Pre-Trained CNNs with CBAM and Skip Connections for Multi-Class Retinal Diseases Classification using OCT Images

This repository contains the implementation of the paper:

**Improving Pre-Trained CNNs with CBAM and Skip Connections for Multi-Class Retinal Diseases Classification using OCT Images**

[https://dl.acm.org/doi/full/10.1145/3723178.3723304]

## Abstract

Millions of people suffer from retinal defects over the world. Early discovery and treatment of these anomalies could halt further progression, saving many people from preventable blindness. Disease detection through manual methods is a tedious procedure that is both time-consuming and cannot produce consistent results. Building on the groundwork laid by Deep Convolutional Neural Networks (DCNNs) in computer-aided diagnosis (CAD), there have been initiatives to automate the detection of retinal diseases. This study presented a hybrid framework that utilizes pre-trained models (DenseNet121, ResNet50, VGG16, Xception, and EfficientB1) incorporating the Convolutional Block Attention Module (CBAM) and skip connections for accurate retinal disease classification. The CBAM block improved retinal disease classification by focusing on important features in OCT images. Skip connections were implemented to facilitate the direct transfer of feature information between layers. This study utilized the OCT-C8 dataset, which comprises seven disease classes and one healthy class. The DenseNet-CBAM-Skip and Xception-CBAM-Skip architectures were particularly noteworthy for their outstanding performance, with DenseNet obtaining a high accuracy of 96.28% and Xception 96.11%. They also acquired a significant F1-score of 96.31% and 96.11% respectively, making it promising for real-time application to help ophthalmologists.

## Citation

If you use this repository or code, please cite the following paper:

```bibtex
@inproceedings{novely2024improving,
  title={Improving Pre-Trained CNNs with CBAM and Skip Connections for Multi-Class Retinal Diseases Classification using OCT Images},
  author={Novely, Navia and Mahmud Shuvo, Shakil and Faruk, Md Farukuzzaman},
  booktitle={Proceedings of the 3rd International Conference on Computing Advancements},
  pages={946--953},
  year={2024}
}
``` 