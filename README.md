# Computer Vision

Computer Vision practice using OpenCV library for python.

## Image Processing Intro

First Practice with OpenCV and image processing. There are 5 different practices:

1. Basic Image Thresholding
2. Denoising - Intro to Filters
3. Sobel Edge Detection
4. Canny Edge Detection
5. Harris Corner Detection

Google Colab is used to write the Jupyter Notebooks, however you can run it locally as well.

The images are assumed to be in the same directory as the Jupyter Notebook. Therefore, if you want to run it locally, please remember to copy the images and the notebook into the same directory. Since I used Google Colab, it was easier for me to do this by uploading the images into the content directory of the Google Colab VM.

## Image Matching and Face Detection

Practicing more complicated image processing methods such as:

1. SIFT features
2. Image Matching using SIFT features
3. Image Stitching using SIFT features
4. PCA and Eigenfaces
5. Face Detection using Eigenfaces
6. Viola-Jones Face Detection

Google Colab is used to write the Jupyter Notebook, however it is possible to run it locally as well.

The contents of the images folder are assumed to be under the same directory as the Jupyter Notebook. Therefore, before running it locally, please remember to copy the contents of the images folder into the same directory as the Jupyter Notebook. Also, you should leave the folder `celebA_subset` as it is since there are 100 images in that folder. They are used as training images for eigenfaces and the notebook reads them from that folder.

For PCA, eigenfaces and face detection using eigenfaces, I have implemented my own algorithm instead of using the ones from OpenCV. It is possible to use the methods from OpenCV which will work better.

For Viola-Jones detection, the XML should be imported in order to use the OpenCV method.

## Image Classification

Practicing various image classification techniques to get familiar with more complex image processing libraries.

1. Image Classification using Support Vector Machines (SVM)
2. Image Classification using Random Forest (RF) Classifiers
3. Image Clasification using Convolution Neural Network (CNN)

For the first 2 classification, I am using a dataset called `flower_subset.npz`. However, it is very large file for GitHub to handle so currently the dataset is not present in the repository. Instead, you can use the **pytorch** library to download data from datasets for image classification. The Jupyter Notebook `image_clf_cnn.ipynb` includes a code snippet showing how to download a dataset using **pytorch**.

For the last image classification, I am using a subset of the dataset MNIST from **pytorch**. I am using CUDA capabilities of the pytorch library to speed up the training of the CNN. Therefore, if you want to run the notebook locally, make sure that you have an NVIDIA GPU. You can also run the notebook on Google Colab, which is easier in my opinion. You can change the runtime environment to a GPU one from the runtime pane.
