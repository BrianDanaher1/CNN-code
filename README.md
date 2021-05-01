# CNN-code
MA 490 CNN code


This code is part of the NNSS project "Evaluating the Variable Stride ALgorithm". This code can sucessfully do the following:
-Take in diabetic retinopathy data from folders on Google Drive (two classes - 0 and 4)
-Classify the data into testing and training data
-Run the data through a convolutional neural network with variable stride as one of the pooling layers

Problems:
-Indexing changes had to be made to the variable stride algorithm to ensure compatibility. This may be scrambling images.
-ROC curve is close to a random classifier
  -Note that the ROC curves without using the variable stride method were better
