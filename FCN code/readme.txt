Theses files show how I tried to improve the model performence: 

FCN-Unet was used to detect the mining areas, 

original: means that I first tried to train the model with defult

tuning: means that I adjusted the learning rate to 0.001, retaining the same number of epochs

Excluding non-mines: means that I tried to improve the class imbalance by resampling the training data

Final: the one with tuned parameters in FCN, and compared it with FCN-DK3

Focal-loss: change the loss fucntion into 'focal-loss' to examine if the results will improve