# About This Project
This work conducted for mine and rzasyalevi22@gmail.com final project in machine learning class supervised by setio_basuki@umm.ac.id. In this project, multiple type of machine learning for classification being used such as machine learning classic (SVM), deep learning (CNN), and pretrained model (DenseNet-169). the dataset used for training the model is "trashnet" dataset. The evaluation matriks accuracy is used in this project. this project is aim to determine which type of machine learnig for classification is suitabel for classification the trashnet dataset, wather using machine learning classic (SVM), deep learning (CNN), or pretrained model (DenseNet-169).

# Dataset
Dataset being used in this project is based on "trashnet" dataset from https://github.com/garythung/trashnet. The dataset contain multiple categories with each category have different number of data inside it, the categories and number of image inside it can be seen down here:
- Cardboard 403 images
- Glass 501 images
- Metal 410 images
- Paper 594 images
- Plastic 482 images
- Trash 137
  
The number of images in the dataset has significant inequality, some categories have large amount of data while others is the opposite. This can effect the performence of the machine learning, to dealing whit this problem some images added to all the categories, the images added to each categories are obtained through images scraping from google images, this is done so the amount of data in each categories have the same amount of data. The additon of 2 categories also conducted in order to give more variation to be classify, the categories added are bio and electronic. The final form of dataset being used can be seen down here::
- Cardboard 600 images
- Glass 600 images
- Metal 600 images
- Paper 600 images
- Plastic 600 images
- Trash 600
- Bio 600
- Electronic 600

<img src="https://github.com/mustarion/Trash_Classification/assets/132191412/f5a18dc5-ef85-4cb4-99ca-13cd615b6f16" width="400" height="300">   <img src="https://github.com/mustarion/Trash_Classification/assets/132191412/592b3845-d11c-42a2-91d1-3a3397c79a08" width="400" height="300">

# Machine Learning
Several type of machine learning are used to determine which machine learning type is most suitable to the project.
## Machine learning classic (SVM)
SVM seeks the hyperplane that separates the data classes with the largest margin, and then support vectors are used to determine the decision boundary, as stated by Cortes et al in their paper https://link.springer.com/article/10.1007/BF00994018#preview.

<img src="https://github.com/mustarion/Trash_Classification/assets/132191412/56023f28-f0b1-4730-b1d7-f14cdaf45cd4" width="500" height="300"> 

## Convolutioinal Neural Network (CNN)
Artificial neural networks consisting of convolutional, pooling, and fully connected layers enable neurons in each layer to learn independently, as described by O'Shea et al in their paper https://arxiv.org/abs/1511.08458.

<img src="https://github.com/mustarion/Trash_Classification/assets/132191412/7030c43d-6f21-4a6e-b0f9-29564aedb3f7" width="500" height="300"> 


## Pre-trained Model (DenseNet - 169)
The fundamental concept of "densely connected" allows each layer to receive input from all preceding layers, facilitating more efficient flow of information, as explained by Huang et al in their paper https://arxiv.org/abs/1608.06993v5.

<img src="https://github.com/mustarion/Trash_Classification/assets/132191412/870df1b7-661c-46c7-87a9-aabf5b27c08e" width="500" height="300"> 

# Evaluation
The evaluation matriks used to determine wich model machine learning have the best qualities is matiks accuracy, this matrix illustrates the comparison between the model's predictions and the actual values in the dataset. A confusion matrix graph visually also used to represents the performance of a classification model by showing a clear overview of the model's accuracy and errors in a tabular form.

# Resume
The project resume can be seen in the form of scientific poster down here:

<img src="https://github.com/mustarion/Trash_Classification/assets/132191412/007f3e88-5449-464f-94e4-2ee1460b9588" width="800" height="1200"> 

