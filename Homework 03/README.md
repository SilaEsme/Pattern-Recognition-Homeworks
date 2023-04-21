# Homework 2

### Step1 Feature Extraction

Read images in RGB format. Then convert image to HSV format. An image must be in the 224x224x3 format. Instead of using the whole image data (224x224x3 size), we have to extract some meaningful features in image. In this study, we will use following feature extraction method.\
- `skimage.feature.multiscale_basic_features`
- `from skimage.color import rgb2hsv`
- <https://scikitimage.org/docs/dev/api/skimage.feature.html#skimage.feature.multiscale_basic_features>

You can see that an image will be represented only with ndarray features. The dimension of feature vector per sample is 1xn. It means that training data (1457 samples) will be represented as (1457xn). Let’s call the X matrix as training matrix and y is label vector, which keeps the class name of samples. The size of X matrix is (1457xn) and the size of y vector is (1457x1). You are expected to fill the X matrix with features and y vector with class label per each sample.

### Step2

You are expected to train with SVM classifier. For this purpose, you can use the following SVM class.\

- <https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html>

### Step3

You are expected to test with SVM classifier. Create confusion matrix and show the accuracy for test samples.
