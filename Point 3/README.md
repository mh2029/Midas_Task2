# Subtask 3

**Note** If you are having github rendering issue view the colab file for Sub_task3 [here](https://drive.google.com/file/d/1zEDlAU6FIMKle5_5DaIAOBvK3tPb3ZTe/view?usp=sharing)

1. In this task we have to train a neural netowrk handwritten digits dataset, where each label correspond to what the image is not. This is opposite to what most supervised learning probelems.
2. The netowrk is trained, with the learning objective to maximize the output for all the complement classes, hence the actual prediction is the output probability with 
minimum value.
3. Two models are compared, one with randomly initialized weights and second that is trained on MNIST dataset
4. The model is teseted on MNIST test dataset with an accuracy of 95% on test set and using the same CustomCNN discussed earlier
