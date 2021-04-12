# Substask 1

**Note** If you are having github rendering issue view the colab file [here](https://drive.google.com/file/d/1lfqG4TetlBooIkVJUc1jHFY36OUvFcRp/view?usp=sharing)

This jupyter notebook performs classification on custom 62 classes dataset, containing 0-9 digits, a-z letters and A-Z letters.
Top 2 models have been presented, 
1. CustomCNN which is a modiifed LeNet with added BatchNorm layers and dropouts to increase performance and reduce overfitting. A validation accuracy of 85% is observed.
2. 2. A ResNet50v2 is also tesed which outperforms the above network and gave a validation accuracy of 87%
3. Corresponding pre-trained weight are in Midas_Task2/Weights/Important_weights/ directory.
4. point1_88_Resnetv2_.hdf5 are resnet weights and point1_customcnn.hdf5 are CustomCNN weights
5. They have already been loaded in the Sub_task1 notebook

