# MIE424-Final-Project
## Abstract 
This project aims to replicate the findings and experiemntal results from the paper _Understanding Deep Learning Requires Rethinking Generalization_ by Zhang et al. [1]. The project report summarizes the experiments conducted to explore the generalization capability of a variety of neural network models: AlexNet, Inception and ResNet. The CIFAR-10 dataset is used to train the models with. Initial experiments involve implementing a series of data augmentations on CIFAR-10 images and training the neural network models on the augmented data to explore the model’s ability to overfit on the data. Label randomization is performed to test the ability of the models to converge on images which have no relationship to labels that are being trained with. 
## Implementation 

The notebooks named after the three models used in this project contain detailed architecture of each model based on the descirption in Zhang et al., and the data transformation notebook contain the data augmentation techniques implemnted, namely pixel shuffling, random erasing, and so on. 

Log files of the experiments conducted are stored in the folder **runs** as well as **logfiles**. More specifically, folder **runs** contains logs for each data augmentation experiment mentioned above, and folder **logfiles** contains ...

## Citation 
[1] C. Zhang, S. Bengio, M. Hardt, B. Recht, and O. Vinyals, “Understanding deep learning requires rethinking generalization,” arXiv.org, 26-Feb-2017. [Online]. Available: https://arxiv.org/abs/1611.03530. [Accessed: 29-Apr-2021].
