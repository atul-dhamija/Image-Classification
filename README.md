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

[Dataset]()


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


## Deployed Web Application



### Link: 

## Result




## References

