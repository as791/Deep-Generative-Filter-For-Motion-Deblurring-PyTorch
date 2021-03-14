# Deep-Generative-Filter-For-Motion-Deblurring-PyTorch
This repository contains the PyTorch implementation of the ICCV'17 Paper,"Deep Generative Filter for Motion Deblurring" (https://arxiv.org/abs/1709.03481). Currently, tested with batch_size=1 with only 297 training data and 115 test data, PSNR as metric. Learning rate and momentum for optimizers are 0.0002, and 0.9 respectively as taken in original work. Trained for 40 epochs with checkpoint saving of 10 epochs. (Refer the paper for more information)

- Data was used from the original source code https://github.com/sainandan-ramakrishnan/Deep-Generative-Filter-for-motion-deblurring 
- Preprocessing functions/data utils modified from https://github.com/leftthomas/ImageDeblurring
- Used Google Colab for Testing the implementation

Achieved Average PNSR of 24.3857 dB over Test data 
