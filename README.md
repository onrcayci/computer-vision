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