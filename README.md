# Overview
- This repository demonstrates how to use ResNet18 for transfer learning to solve an image classification problem.
- Transfer learning allows leveraging a pre-trained model (like ResNet18) to fine-tune the model on a new dataset, making it easier and faster to build a high-performance image classification model even with limited data.

# Dataset:
- Images from google search
- Ones search for images => Extensions(Titlebar of chrome)=> Manage Extension => Download All Images (if not exist download)
  ## Reference:
  https://youtu.be/jztwpsIzEGc

# Jupyter Notebook
You can also run the entire pipeline interactively using the Jupyter notebook . This notebook covers:
- Building and loading the custom dataset.
- Fine-tuning the ResNet18 model.
- Saving the trained model.
- Evaluating the model.
- Testing the model on single or multiple images.

# Models.pth
- Pretrained model
- Fine tuned trained model

# Test Images
- Images for testing on trained model and get predictions.

# Acknowledgments
- ResNet architecture from the original paper: Deep Residual Learning for Image Recognition
- PyTorch and torchvision for providing the pretrained ResNet18 model.
