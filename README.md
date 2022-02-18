# Bollywood-face-similarity

## Project details

Used VGGFace and Resnet50 model we extract features from the photos of the celebrities.

![cnn](https://user-images.githubusercontent.com/60546202/154656174-4e7bd05a-def2-4f6f-828a-d35f9db8341c.jpg)

MTCNN detects the face of the person even if a full body picture is provided.

It predicts the similar matching bollywood celeb based on cosine similarity of the pictures.

Made the webapp using streamlit.

![photo1](https://user-images.githubusercontent.com/60546202/154656203-751d3db7-dbed-4072-9261-dc39e57ac2bb.jpg)

![photo3](https://user-images.githubusercontent.com/60546202/154656274-b3f3926e-3d7a-4930-b86a-8ab172196845.jpg)


### Dataset
Dataset can be downloaded from [here](https://www.kaggle.com/sushilyadav1998/bollywood-celeb-localized-face-dataset)


#### MTCNN 
Multi-task Cascaded Convolutional Networks (MTCNN) is a framework developed as a solution for both face detection and face alignment. The process consists of three stages of convolutional networks that are able to recognize faces and landmark location such as eyes, nose, and mouth.

#### VGGFace

The VGGFace refers to a series of models developed for face recognition and demonstrated on benchmark computer vision datasets by members of the Visual Geometry Group (VGG) at the University of Oxford. There are two main VGG models for face recognition at the time of writing; they are VGGFace and VGGFace2


## What I plan to do next

I plan to expand the dataset to sportspersons, politicians, hollywood actors and other famous personalities.

Make some changes in the UI and also shift it to flask webapp.
