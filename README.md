# Image Classification using Machine Learning

This project was aimed to deploy a *deep learning* application to classify the images .


## Dependencies

You can install Python dependencies using ``` pip install -r requirements.txt ``` , and it should just work. if you want to install package manually, here's a list:

 - Python 
 - Scikit Learn
 - Flask
 - Scipy
 - Pillow
 - Numpy
 - Matplotlib
 - Pandas


## Dataset

The dataset consist of images of 18 different classes, 90 images for each class.

[Dataset](https://drive.google.com/drive/folders/18d2kHoA361jIWbgrCnpNGWbtfwDTE5fA)


## Approach


### Step 1. Data Preprocessing

#### a) Data labelling.
#### b) Dumped the dataset into a pickle file.


### Step 2. Feature extraction using HOG transform


![repo13](https://user-images.githubusercontent.com/64823050/130604861-7162181b-236a-47c3-aa34-8fccc89dd802.jpg) ![repo14](https://user-images.githubusercontent.com/64823050/130604828-18c0040f-4c1e-4847-bf4d-7fbe3b3453bf.jpg)

HOG, or Histogram of Oriented Gradients, is a feature descriptor that is often used to extract features from image data. It is widely used in computer vision tasks for object detection.
The HOG descriptor focuses on the structure or the shape of an object. . HOG is able to provide the edge direction as well. This is done by extracting the gradient and orientation (or you can say magnitude and direction) of the edges
Additionally, these orientations are calculated in ‘localized’ portions. This means that the complete image is broken down into smaller regions and for each region, the gradients and orientation are calculated.
Finally the HOG would generate a Histogram for each of these regions separately. The histograms are created using the gradients and orientations of the pixel values, hence the name ‘Histogram of Oriented Gradients’


### Step 3. WebApp Framework


![repo7](https://user-images.githubusercontent.com/64823050/129591794-b4fe2d45-27bf-4167-9be8-147a05c29cf7.jpg)



## Web Application
 
 
![repo15](https://user-images.githubusercontent.com/64823050/130605735-ca553035-4ff5-4450-9f69-431d8c5e3597.jpg)



## Result


![repo16](https://user-images.githubusercontent.com/64823050/130605750-10311cbf-d5df-4b1d-80fa-916bea1a8683.jpg)



## References


[HOG Tranformation](https://www.analyticsvidhya.com/blog/2019/09/feature-engineering-images-introduction-hog-feature-descriptor/)

