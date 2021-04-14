1. ``point1_88_Resnetv2_.hdf5`` this is the pretrained weight for resnetv2 trained for point1(subtask1) so load this weight into a resnetv2 archotecutre and **preprocess** the image before testing.

2. ``point1_customcnn.hdf5``  if you want to test custom CNN on test dataset

3. ``point2_customdataset_network_zero2nine.hdf5:`` : These are the weights that are obtained by training CustomCNN only on 0-9 digits of custom dataset. This pretrained netowrk is required for point 2 subtask.

4. ``point2_mnist_randomweights.h5``: These are the weights obtained on training CustomCNN, with randomly initialized weights on mnist dataset.

5. ``point2_mnisttrainedon_pretrain.h5``: These are the weights obtained on training customCNN on MNIST with pretrained wegihts.
 
6. ``point3_pretrained.h5``: thse are the weights obtained by training a CustomCNN with weights loaded from 'Midas_Task2/Weights/Misc_weights/task3_customdata_029_size28x28_customCnn.hdf5'
ans then trained on this new dataset provided in point 3.
7. ``point3_randominint.h5``: these are the weights obtained by training a randomly initialized CNN on this new dataset.
