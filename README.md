# image-classification
Data has been scraped from amazon.com using a python script 
which with selenium. All the data is in the .jpg image format.
We have over 250 images per class

We will be first scraping the data from amazon and then cleaning 
the data to be further used for training the model.
Then splitting the data into train and test set to model evaluation.
We would use VGG16, A transfer learning SOTA model for training
our data on.
We would perform multiple data augmentation techniques on the 
images for better generalization of our model.
We could check and identity an optimal batch size and number of 
epoch to Train the model using trial and error method also keeping 
the epoch loss for both training set and validation in mind.


Key Findings and Conclusions of the Study
Our model was successfully to classify the images with an accuracy 
of 85 Percent on a validation set of around 70 images
• Learning Outcomes of the Study in respect of Data 
Science
The larger the data the better the model could predict.
Multi class prediction are somewhat relatively harder to train in 
comparison to a Binary class prediction.
Data Augmentation is necessary where we have small datasets of 
images.
• Limitations of this work and Scope for Future Work
One could always provide more data for training the model in order 
to get better results.
We could use to model for apparel segmentation at Supermarkets 
and shopping stores
