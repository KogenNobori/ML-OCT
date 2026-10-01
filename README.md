# Building deep learning based layer segmentation and pathology classification models in retinal OCT images
This repository shares code and data used in the project. For detailed information, please check the technical report. *The repository is still under development, and further information will be added.

## Datasets
Datasets used in this project can be found [here](https://drive.google.com/drive/folders/1XAFSmCNuPptv4a1y1t7a1SNGgEduKjCq?usp=sharing). 

Dataset creation script for classification:

## Layer segmentation 
U-Net was used for the layer segmentation. This [repository](https://github.com/KogenNobori/Pytorch-UNet) was used in training and analysis. Branches without_noise, speckle_10p_m0v0.5, speckle_10p_m0v1 were used for the three training and testing settings discussed in the report.



## Classification
ResNet and Swin Transformer were trained for classification. The Kaggle Notebooks used are included in this repository.


