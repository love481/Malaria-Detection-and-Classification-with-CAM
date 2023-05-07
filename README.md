# Malaria-Detection-and-Classification-with-CAM
Classify and detect Malaria using custom CNN and EfficientNet with Class Activation Map


## Requirements:
* torch >=1.8.1+cpu
* torchvision
* skimage
* glob
* efficientnet_pytorch
* numpy
* matplotlib

## Installation
Run this command on command prompt to clone the repository


`git clone https://github.com/love481/Malaria-Detection-and-Classification-with-CAM.git`

Download the Dataset from the [link](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria).

## Usage
* Navigate to the directory and copy and paste the downloaded cell_images folder in the data folder.
* Notebook with subtext "cnn" represents the custom CNN and Efficient represents the EfficientNet-B0.
* Each notebook with subtext "cam" on it represents the model where you can fine-tuned your model or train from the scratch and also visualize the heatmap.
* The saved model can also be used for CAM visualization or fine-tuning tasks
* Run the Notebook Based on Requirement and your model choices.

