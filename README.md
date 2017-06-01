# The Challenges of Image Classification

Before Convolutional Neural Networks came around, inferring what your images was a manual process of extracting features and piping them into a classifier. This project explores those classic techniques and compares three feature representations of images. 
- Compared histogram oriented gradients (HOG)  and bag of visual words (BoW) using SIFT descriptors to raw pixel data using a LinearSVM.
- Built BoW using OpenCV's implementation of SIFT and scikit-learn's  KMeans.

## Takeaways

The accuracy improved the more I abstracted the image, where SIFT created the largest accuracy, but I found that there was a problem with some classes not being guessed at all.


## Tools

- sklearn
- OpenCV
- skimage
- LinearSVM
- Mini-Batch KMeans
