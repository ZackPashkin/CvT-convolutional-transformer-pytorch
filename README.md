# CvT-convolutional-transformer-pytorch
CvT convolutional transformer pytorch starter https://colab.research.google.com/drive/1bZNC1rK_I4ANiS-ilEEbrPgR8E8Av_RG

# Observations
Much slower on training with less parameters size.

Compare resnet50 with 23kk learnable paramenters, batch 128, inputsize 224, epoch 2min 30sec, on tesla v100, colab env.

CvT takes about 11 min/epoch with 20kk learnable paramenters, batch 32, inputsize 224, on tesla v100, colab env

# Reference


https://github.com/rishikksh20/convolution-vision-transformers.git

https://arxiv.org/abs/2103.15808
