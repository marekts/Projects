This project is image classification model which recognise artist by painting. 
In this project my goal is increase my knowledge and understanding of working with images, CNN, image recognition and computer vision.  

The dataset includes more than 8000 pictures of 50 famous artists such as Salvador Dali, Pablo Picasso, Rembrant and many others.
In fact, dataset is very imbalanced, for example: there are more thar 800 Van Gogh's arts, and less than 50 Jackson Pollock's arts and so on. I will be managing with it by reducing list of artists to artists who have at least 100 paintings, so left 30 artists and using class weights.

**Tolls: Pandas, Keras, data augmentation, transfering learning**       
 
Plan is following:

- Load data 
- Calculate classes weights
- Data augmentation 
- Build and train model 
- Check model on test data

For image recognition is good "imagenet" so I will use ResNet50 and I will freeze top layers.

Later I am going to made second part this project - style transferring. 













