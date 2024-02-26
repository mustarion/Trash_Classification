## About This Project
This work conducted for my final project in machine learning class. In this project, multiple type of machine learning for classification being used such as machine learning classic (SVM), deep learning (CNN), and pretrained model (DenseNet-169). the dataset used for training the model is "trashnet" dataset. The evaluation matriks accuracy is used in this project. this project is aim to determine which type of machine learnig for classification is suitabel for classification the trashnet dataset, wather using machine learning classic (SVM), deep learning (CNN), or pretrained model (DenseNet-169).

## Dataset
Dataset being used in this project is based on "trashnet" dataset from https://github.com/garythung/trashnet. The dataset contain multiple categories with each category have different number of data inside it, the categories and number of image inside it can be seen down here:
- Cardboard 403 images
- Glass 501 images
- Metal 410 images
- Paper 594 images
- Plastic 482 images
- Trash 137
  
The number of images in the dataset has significant inequality, some categories have large amount of data while others is the opposite. This can effect the performence of the machine learning, to dealing whit this problem some images added to all the categories, the images added to each categories are obtained through images scraping from google images.  This is done so the amount of data in each categories have the same amount of data:
- Cardboard 600 images
- Glass 600 images
- Metal 600 images
- Paper 600 images
- Plastic 600 images
- Trash 600

The additon of 2 categories also conducted in order to give more variation to be classify, the categories added are bio and electronic. The final form of dataset being used can be seen down here:
- Cardboard 600 images
- Glass 600 images
- Metal 600 images
- Paper 600 images
- Plastic 600 images
- Trash 600
- Bio 600
- Electronic 600

## Machine Learning
several type of machine learning are used to determine which machine learning type is most suitable to the project.
### Machine learning classic (SVM)
