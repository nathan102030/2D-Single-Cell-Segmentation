# 2D-Single-Cell-Segmentation

Single Cell segmentation identifies and outlines regions of interest in an image, and one of the most difficult tasks in biomedical image analysis. The batch of images/masks needed to be read and then trained to the network. Once this was completed, the 3 datasets were created and the number of samples for each set was displayed in this image. 
Train: 4140 samples (BLUE)
Validation: 1380 samples (ORANGE)
Test: 2070 samples (GREEN)
From there A U-Net model was employed to train a neural network via a training loop, and subsequently tested against a sample from the testing set. The optimizer function utilized the ADAM algorithm, while the loss function employed binary-cross entropy. A total of 50 epochs were executed, with the best performing epoch chosen to represent the best model. Upon evaluation, the model exhibited an accuracy of approximately 98.4%. An accuracy and confusion matrix were subsequently generated to assess the model's performance by illustrating the true positives and true negatives detected by the model.
