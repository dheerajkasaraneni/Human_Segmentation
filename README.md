# Human Segmentation
Human Segmentation is the process of classifing each and every pixel of input image into a pixel containing Human or not.
## Overview
The algorithm used in the code is Down-Sample and Up-Sample the the given image to clasify each and every pixel of the image into binary formate. Where 1 
representing Human and 0 representing non-Human.

The Down-Sample is done by using Convolutional Neural Network (CNN) and the Up-Sample is done by using Transposed Convolution Neural Network.
## Dependencies
The entire code is written in google Colab as it provides free GPU and the entire code is compiled in cloud with out any pressure on the computer.
## Usage
Download the repository using the download option or
```bash
git clone https://github.com/likhit-paruchuri/Human_Segmentation
```
Now upload the entire folder to the google drive.

Open the Human_Segmentation.ipynb file with Colab (install Colab extension for your drive if you are using it for the first time).

Set EPOCHS and BATCH_SIZE to the desired values based on the size of dataset.

Set Continue_training_step_numbe to the highest value file in training_checkpoints to load the pre-trained models or set to 0 if there no pre-trained model.

After Training the model you can upload the test images in Human_Segmentation/Dataset/test folder.
## Output
The training process for the images is shown below:
<p align="center">
  <img width="400" height="400" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/Dataset/Training_Images/10.jpg">
  <img width="400" height="400" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/output.gif">
</p>
The final output of few images at 1k EPOCH is shown below:
<p align="center">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_in_1.jpg">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_out_1.jpg">
</p>
<p align="center">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_in_2.jpg">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_out_2.jpg">
</p>
<p align="center">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_in_3.jpg">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_out_3.jpg">
</p>
<p align="center">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_in_4.jpg">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_out_4.jpg">
</p>
<p align="center">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_in_5.jpg">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_out_5.jpg">
</p>
<p align="center">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_in_6.jpg">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_out_6.jpg">
</p>
<p align="center">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_in_7.jpg">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_out_7.jpg">
</p>
<p align="center">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_in_8.jpg">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_out_8.jpg">
</p>
<p align="center">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_in_9.jpg">
  <img width="200" height="200" src="https://github.com/likhit-paruchuri/Human_Segmentation/blob/master/test_out/img_out_9.jpg">
</p>
This project is still under progress and need more training.
