# Age-Detection
A Convolutional Neural Network model trained to predict age group (Young, Middle, Old) from images.

Dataset Description :
Datasets contains 19906 images of Indian celebrities labeled in 3 classes (Young, Middle, Old) according to their ages. Most of the images are blurry and are of different angles.

Model Description :
Keeping, the computational power of my personal computer, in mind. I have used a simple Convolutional Neural Network model with just 7 hidden layers (counting convolutional and pooling layer as 1).

Problems Faced : 
I tried a alex-net like structure but my pc kept crashing while training so had to lower the number of layers in the model. VGG-16 like model kept overfitting and took around 3-4 hrs to train. Finally, chose this model was not overfitting but still accuracy is not that great, still cosidering the computational limitations of my pc model performed well enough. 
