Secure and Adversarially Robust Remote Sensing Image Analysis

Overview
This project implements a secure and adversarially robust deep learning pipeline for analyzing remote sensing survey maps. It integrates image encryption, semantic understanding, adversarial attack simulation, and defense mechanisms.

Key Features

->U-Net with ResNet34 encoder

->AES-256 encryption for secure image transmission

->Adversarial attacks: FGSM and PGD

->Defense mechanisms:

->FGSM adversarial fine-tuning

->Hybrid input preprocessing defense

->End-to-end secure inference demonstration


## Project Structure

```
secure-remote-sensing-segmentation/
│
├── notebooks/
│   ├── 01_environment_setup.ipynb
│   ├── 02_dataset_preprocessing.ipynb
│   ├── 03_model_training_unet_resnet34.ipynb
│   ├── 04_inference_and_evaluation.ipynb
│   ├── 05_aes_encryption_decryption.ipynb
│   ├── 06_adversarial_attacks.ipynb
│   ├── 07_defense_and_robustness.ipynb
│   └── 08_end_to_end_demo.ipynb
│
├── models/
│   ├── unet_resnet34.pth
│   └── unet_resnet34_adv.pth
│
├── data/
│   └── README.md
│
├── samples/
│   ├── LULC/
│   ├── River/
│   ├── Road/
│   ├── Settlement/
│   ├── Soil/
│   └── README.md
│
├── requirements.txt
└── README.md
```


Methodology:

->Train U-Net with ResNet34 on remote sensing images

->Encrypt images using AES-256 for secure transmission

->Simulate FGSM and PGD adversarial attacks

->Apply adversarial fine-tuning and hybrid defenses

->Evaluate robustness and visualize results

->Results

->FGSM adversarial fine-tuning improves robustness

->PGD attacks are mitigated using hybrid defenses

->Secure and robust inference is achieved

Technologies Used:

->Python

->PyTorch

->segmentation-models-pytorch

->Cryptography (AES)

->OpenCV

->NumPy

->Matplotlib

Notes:
Dataset is not publicly shared. See data/README.md for structure
Models are provided in the models/ directory

Sample Data:
Representative sample images for each class are available in the
`samples/` directory for visualization and understanding of the dataset.
