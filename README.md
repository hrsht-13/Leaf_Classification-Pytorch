# Leaf_Classification-Pytorch
Building a model using Trasfer Learning through Pytorch with Costum training loop.
### Dataset
It contains all 185 tree species from the Northeastern United States. Dataset is highly imbalanced, as the lowest number of images a species has is around 20 images, while the highest number of images is around 150 images. All the images are in RGB.
### Preprocessing of Data
Preprocessing of data done through skimage library using transforms.
1. Resizing
2. CentreCropping
3. Normalizing the images
4. LabelEncoding the Target values
### Splitting the Dataset
Dataset has been splitted in Train and Val set in the ratio of 2:3 and 1:3 respectively.
### Model
Resnet-18 has been used with Cross entropy loss and SGD optimizer.
Further Learning rate reducer has been used to control the rate or speed at which the model learns.
### Results
The model achieved :
1. train-acc of 98.94% with a val-acc of 89.73%
2. train-loss of 0.111 with a val-loss if 0.357

