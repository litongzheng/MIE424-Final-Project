# MIE424-Final-Project
## Abstract 
This project aims to replicate the findings and experiemntal results from the paper _Understanding Deep Learning Requires Rethinking Generalization_ by Zhang et al. [1]. The project report summarizes the experiments conducted to explore the generalization capability of a variety of neural network models: AlexNet, Inception and ResNet. The CIFAR-10 dataset is used to train the models with. Initial experiments involve implementing a series of data augmentations on CIFAR-10 images and training the neural network models on the augmented data to explore the model’s ability to overfit on the data. Label randomization is performed to test the ability of the models to converge on images which have no relationship to labels that are being trained with. 
## Implementation 

The notebooks named after the three models used in this project contain detailed architecture of each model based on the descirption in Zhang et al., as well as the results of the data augmentation and convergence experiments. The data transformation notebook contain the data augmentation techniques implemnted, namely pixel shuffling, random erasing, random perspective, random horizontal flip, random rotation, color jitter, as well as label corruption. Visualization of each augmentation can be found in the data transformation notebook. It should be noted that the functions used for training the models are modified based on the code developed by the authors [2]. 

Log files of the experiments conducted are stored in the folder **runs** as well as **logfiles**. More specifically, folder **runs** contains ...., and folder **logfiles** contains text files for the logs of each data augmentation experiment mentioned above. **Logfiles** also includes the code for processing the log files as well as each model's accuracy and loss curve. 

## Citations  
[1] C. Zhang, S. Bengio, M. Hardt, B. Recht, and O. Vinyals, “Understanding deep learning requires rethinking generalization,” arXiv.org, 26-Feb-2017. [Online]. Available: https://arxiv.org/abs/1611.03530. [Accessed: 29-Apr-2021].

[2] Pluskid, “pluskid/fitting-random-labels,” GitHub. [Online]. Available: https://github.com/pluskid/fitting-random-labels. [Accessed: 29-Apr-2021].
