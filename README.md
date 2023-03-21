# DS-4002-Project2

## Repository Contents
This repository contains the files and information related to the second project done by Lauren Smith, Ann Sofo and Reese Quillian in the UVA DS 4002 Project Course. In this project we explored the question: Can we differentiate between trash and recyclable materials through images?

## SRC

### Overview
The file in our src folder is a Jupyter notebook that contains all code used to clean our data, perform exploratory analysis, and build/evaluate our model. This notebook can be opened with any browser, but was originally created using Google Colaboratory. The following section outlines dependencies specific to Colab, but there may be others depending on the platform/browser you choose.

### Code Usage
In order to successfully run the code chunks in the Jupyter notebook, a few packages need to be installed to supplement those that are pre-installed in the Colab environment. The lines to install these packages (!pip install python_splitter and !pip install tensorflow==2.7.0) can be found at the beginning of the notebook - just make sure these are run first. Then run the chunk that loads the libraries. Since Colab works in the cloud, the data is loaded from this github repository: once the repository is cloned, the required data files appear in the file system on the left hand side of the Colab environment. Once these steps have been completed, the notebook can be run and follows through all of our steps related to this project: data cleaning, exploratory data analysis, and building our (convolutional neural network) model. 

## Data

The original dataset is a garbage classification dataset that was downloaded from [Kaggle](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification). The six garbage classifications found in the data and their corresponding number of images are as follows: cardboard (393), glass (491), metal (400), paper (584), plastic (472) and trash (127). Due to the comparably smaller number of trash images found in this dataset, we decided to replace our current trash classification images with the trash and biological category of [another dataset](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)  found on Kaggle to even out our classes, which left us with 1,682 images of trash. In total we have 3,102 observations of trash images, which we separated into two classes before exploring our research question: recyclables (2,390), trash (1,682). 

## Figures

## References
[1] D. Rausch, “EDA for Image Classification,” Geek Culture, Apr. 15, 2021. https://medium.com/geekculture/eda-for-image-classification-dcada9f2567a (accessed Mar. 16, 2023).
[2] Chang, “Garbage Classification.” https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification (accessed Mar. 16, 2023).
[3] Mostafa Mohamed, “Garbage Classification (12 classes).” https://www.kaggle.com/datasets/mostafaabla/garbage-classification (accessed Mar. 16, 2023).
[4] N. Lang, “Using Convolutional Neural Network for Image Classification,” Medium, Apr. 28, 2022. https://towardsdatascience.com/using-convolutional-neural-network-for-image-classification-5997bfd0ede4 (accessed Mar. 16, 2023).
[5] B. Adhikari, “Python Splitter,” GitHub, Mar. 14, 2023. https://github.com/bharatadk/python_splitter  (accessed Mar. 16, 2023).
