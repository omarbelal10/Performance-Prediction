# Performance-Prediction
Predicting the best of the N object detectors

# Training pipiline using Vi-T
![Proposed_ViT](https://github.com/user-attachments/assets/dfa9e25e-963c-4d67-9be7-49cdc931d475)

# Training Pipline using ResNet
![Proposed_ResNET](https://github.com/user-attachments/assets/a6047314-f11d-4a30-a191-53f3c8940e30)

# Testing
![Testing_pipline](https://github.com/user-attachments/assets/5dd6f760-4e87-4caf-a258-bf1fd7613e38)

# Abstract

We observe that the performance of state-of-the-art (SOTA) object detectors exhibits significant variations when assessed across diverse image attributes in the maritime datasets.This is because a single object detection paradigm is only suitable for a particular set of scenarios while it observes reduced performance in other scenarios.To address this issue, we present a novel paradigm for improving maritime object detection by developing a model capable of predicting the performance of different SOTA object detectors for a given scene.Based on this prediction, the best-performing SOTA object detector is then selected for that scene.
The proposed model, dubbed as Maritime Object Detection Prediction Network (MODPN) leverages a powerful backbone based on Vision Transformer (ViT) and pre-trained to predict the performance of a set of eight SOTA object detectors over a wide range of datasets. Thus, the MODPN introduces a new object detection paradigm by utilizing the capabilities of the existing SOTA object detectors.Extensive experimental evaluation on several maritime object detection benchmark datasets reveals that MODPN outperforms the individual SOTA object detectors, showcasing its effectiveness across varying scenarios.MODPN achieved a mean IoU of 65.10%, 67.30%, and 61.30% on SeaShips, Singapore Maritime, and ABOships datasets compared to 61.0%, 56.0%, 30.0% current best performances, respectively.The scope of the proposed MODPN paradigm is not limited to maritime object detection rather, it is generic and applicable to any object detection scenario.

# Results 

![Spider_diagram](https://github.com/user-attachments/assets/1418c866-a99b-4251-8a49-7fd27e0b0801)


# Training 
The following datasets have been used for training 
   1. SeaShips
   2. Singapore maritime 
   3. ABOships 
   
We provide the pretrained model under in the following link https://1drv.ms/f/c/5aa3f723702b9959/EvDdRXwwtwFKunyGDhA5kb4BcyeZM-A8rbj3UFmu9UfNhw?e=qsow2b, However If you want to do it yourself Please do the following

- Open the following Notebook to perfrom data augmentation and training using The Vi-T model (This notebook shows an example using one dataset and you can do the same using the other datasets) 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/omarbelal10/Performance-Prediction/blob/main/Vi-T_Train.ipynb)


- Open the following Notebook to perfrom data augmentation and training using The ResNet models (This notebook shows an example using one dataset and you can do the same using the other datasets)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/omarbelal10/Performance-Prediction/blob/main/ResNet_Train.ipynb)

# Testing

- Open the following Notebook to perfrom testing using the pretrained Vi-T model (This notebook shows an example using one dataset and you can do the same using the other datasets) 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/omarbelal10/Performance-Prediction/blob/main/Vi-T_Test.ipynb)

- Open the following Notebook to perfrom testing using The ResNet models (This notebook shows an example using one dataset and you can do the same using the other datasets) 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/omarbelal10/Performance-Prediction/blob/main/ResNet_Test.ipynb)


