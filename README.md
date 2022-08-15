# X-CT-Porosity-CNN

In this repository a CNN model is developed to classify the X-CT images taken from samples produced using additive manufacturing. The target is to train the model on learning the attribute of each image based on the amount of porosity that has been measured for each individual image.
Images are preprocessed using ImageJ to add filters, convert to a 2D image, and measure the porosity. Then the images are labeled manually and moved to different folders based on the class. 
Eventually the raw images are utilized and fed to the CNN model for training and validation.
