# DensePrediction

# Vision Transformer for Depth Estimation

## Description
This project uses a Vision Transformer (ViT) model for monocular depth estimation. The model is trained on a custom dataset and evaluated on test images.


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rkeesee11/DensePrediction/blob/main/simplified_midas_reproduction.ipynb)



Or paste this link:
[https://colab.research.google.com/drive/1CZyRhTxWD-ngnGNtxPyQ0cuWMj0eIdqq?usp=sharing](https://colab.research.google.com/drive/1CZyRhTxWD-ngnGNtxPyQ0cuWMj0eIdqq?usp=sharing)


## Requirements
- Google Colab (recommended) or local environment
- Python 3.x
- PyTorch
- torchvision
- numpy
- matplotlib

### Download the model
You can download the model from Google Drive
https://drive.google.com/file/d/1UWx3R0KMbNq0B_tsjCzaaROgAOUpmpUq/view?usp=sharing

## Usage
1. Upload a test image, name it text_image.jpg (or test mine)
2. Download and import the model weight above called vit_depth_model.pth
3. Run the depth estimation model.
4. Visualize the predicted depth map.

## Results
The model produces a depth map of any image you upload in the correct format of jpg or png!
This is not an improvement from our article, but it does replicate it in a way.
