## Project: Build a Traffic Sign Recognition Program
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)
### Overview

In this project, I use deep neural networks and convolutional neural networks to classify traffic signs. Here I trained a model so it can decode traffic signs from natural images by using the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset). After the model is trained, I tested model program on new images of traffic signs I found on the web, local as well as the test dataset. 

Please see the final project implementation in `Traffic_Sign_Classifier-MZ.ipynb`. The folder is based on Udacity Github Project 2 https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project. 

### Dependencies

This project requires **Python 3.5** and the following Python libraries installed:

- [Jupyter](http://jupyter.org/)
- [NumPy](http://www.numpy.org/)
- [SciPy](https://www.scipy.org/)
- [scikit-learn](http://scikit-learn.org/)
- [TensorFlow](http://tensorflow.org)
- [Matplotlib](http://matplotlib.org/)
- [Pandas](http://pandas.pydata.org/) (Optional)

Run this command at the terminal prompt to install [OpenCV](http://opencv.org/). Useful for image processing:

- `conda install -c https://conda.anaconda.org/menpo opencv3`

### Dataset

1. [Download the dataset](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/581faac4_traffic-signs-data/traffic-signs-data.zip). This is a pickled dataset in which we've already resized the images to 32x32.
2. Clone the project and start the notebook.

 ```
 git clone https://github.com/minmingzhao/CarND-Traffic-Sign-Classifier-Project
 cd CarND-Traffic-Sign-Classifier-Project
 jupyter notebook Traffic_Sign_Classifier-MZ.ipynb
 ```
 
3. Follow the instructions in the `Traffic_Sign_Classifier-MZ.ipynb` notebook.

