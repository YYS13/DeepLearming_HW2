# Introduction
## In repositories I design two image ckassification models and compare with traditional ResNet34 on ImageNet-mini
### 1. replace traditional Convolution module by Dynamic Convolution module in Resnet34 (dynamic_convolution_ipynb)
### 2. Design a four-Layer model can achieve 90% performance of ResNet34 (4_layer_model.ipynb)

# How to run the code and reporduce the experiment
## You need to clone the repository and download the Dataset from Moodle and create ./models directory for saving the model's parameters

## 1. Dynamic Convolution
### install all pakages in first cell
### set your own hyperparameters in cell specific for hyperparameters
### change loss function & optimizer in function call train_from_scratch  
### Run all
### You will get Resnet34 & Dynamic ResNet34 models for 3channels and 1channels information respectivily 
### Models' parameters will be saved in ./models as best_dynamic_resnet34_1channels.pth & best_dynamic_resnet34_3channels.pth & best_resnet34_1channels.pth & best_resnet34_3channels.pth

## 2. Four-Layer Models 
### install all pakages in first cell 
### set your own hyperparameters in cell specific for hyperparameters
### change loss function & optimizer in function call train_from_scratch  
### Run all
### You will get four-layer model information for 3channels input
### Model's parameters will be saved in ./models as  3_channels_four_layer_model.pth 

# ./Resault directory save all result screenshots of models 
