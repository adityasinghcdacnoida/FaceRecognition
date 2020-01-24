# Facenet: Real-time face recognition using deep learning Tensorflow 

This is completly based on deep learning nueral network and implented using Tensorflow framework. Here you will get how to implement fastly and you can find code at github and uses is demonstrated at YouTube.

### Installation Python Libraries:

- Tensorflow (1.4.0)
- Scipy (0.17.0)
- Scikit-learn (0.19.1)
- Opencv (2.4.9.1)

## -install them them through pip install or if you have python 3 use pip3 install

## git clone https://github.com/adityasinghcdacnoida/FaceRecognition
there is a face directory 
inside face directory you will find all trhe files


# step 1
*collect the images of different people abnd store them in  a seperated named directory respectively in trainning as well as test directory
put 20% of images in test directory and 80% of images in the training directory

# step2 
*Open data_preprocess.py give the path of train and test directory and run this file-- python data_preprocess.py or python3 data_preprocess.py 
This file will crop the face of each face and label each face image with the folder name. And generate a text file “bounding_boxes_123.txt” where you see labeling of data

# step3

*Training of Model: After preprocessing of data we have to train model with a predefined model. Put pb file inside the folder named as “model”. 
And now run the training file “train_main.py” as python command. It will train model and also pkl file will be saved inside directory “Class”. Python classifier_train.py
 OR you can train your own model .
link for pre trained model https://drive.google.com/file/d/1EXPBSXwTaqrSC0OhUdXNmKSh9qJUQ55-/view

## note 1- 
this is the pretrained model which is trained on thousands of images 
## note 2-
using your own model or wheather a pretained model after that also  you have to train your dataset of images by running so that it will create a model for you i.e classify your dataset of your choosen names of different people (you will get a file inside class directory classifier.pkl).
## classifier.pkl is the file that you have got after training

# step4
run the identify_face_video.py and set the all the paths , like classifier file path according to your directory or if you clone my repo let the path as it is

complete

## EXTRAS
1
IF YOU WANT YOUR VIDEO IN GREY SCALE
 RUN THIS FILE  identify_face_gray_video.py

2
IF YOU JUST WANT TO DETECT JUST THE IMAGE LOCATED IN YOUR LOCAL DIRECTORY RUN identify_face_image.py

3
IF YOU WANT TO GET A FEED FROM A IP CANMERA  RUN THIS FILE identify_face_ipcam_video.py

THANKS 
ADITYA SINGH

### Usage:

Well this facenet is defined and implementation of facenet paper published in Arxiv (FaceNet: A Unified Embedding for Face Recognition and Clustering). And also contain the idea of two paper named as "A Discriminative Feature Learning Approach for Deep Face Recognition" and "Deep Face Recognition". For deep understanding about its concept you can follow upper paper. One also main part is that for genearating your own model you can follow [this link](https://github.com/davidsandberg/facenet) Face Recognition using Tensorflow. David Sandberg have nicely implemnted you can also find it on Github for complete code and uses.



