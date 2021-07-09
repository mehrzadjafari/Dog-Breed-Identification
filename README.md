# Dog-Breed-Identification

### The Final Project of Fundamentals of Data Science course

<p align="center"> 
    <img src="https://storage.googleapis.com/kaggle-competitions/kaggle/3333/media/border_collies.png" alt="dogs">
 </p>


This data comes from the Dog Breed Identification Kaggle competition and covers 120 different dog breeds. It consists of 10.2k different images for the training set and 10.4k images for the test.

<br>
<br>


## Goal of the project: 
    > 1. In the first one, we chose to follow the Linear approach. To do so, we selected the mobilenet_v2_130_224 model from TensorFlow Hub that comes from the MobileNet architecture, that accepts (224,224,3) as an eligible input size.
    > 2. In the second one, we used 4 layers, respectively InceptionV3, Xception, NASNetLarge, InceptionResNetV2, to achieve a Deep Neural Network (DNN) approach. Image size (331,331,3)


## Main Steps:
    > 1. Importing the data
    > 2. Preparing the data
    > 3. Choose and fit/train a model (TensorFlow Hub, tf.keras.applications, TensorBoard, EarlyStopping)
    > 4. Evaluating the model
    > 5. Improve the model through experimentation
    > 6. Save, sharing and reloading your model


## The repository consists of the following files:

### `Dog_Breed_Identification_Single.ipynb`: 
    > 1. The notebook consists of using only one model for determining the classes.
    > 2. The model is `mobilenet_v2_130_224` model from TensorFlow Hub that comes from the `MobileNet` architecture.
    > 3. We set the input images size at (224,224,3)

### `Dog_Breed_Identification_DNN_Approach.ipynb`: 
    > 1. The notebook consists of using four different models to extract the features from the images.
    > 2. The models are `InceptionV3`, `Xception`, `NASNetLarge`, `InceptionResNetV2`.
    > 4. We set the input image size at (331,331,3)

### `FDS Final Project Full Report.pdf`: 
    > The complete report which consists of all the approaches taken within the project, plus all key points respected in all phases of the project.
    
    

|         Group Members         |   Matricola   |
| ----------------------------- | ------------- |
|    Mehrzad Jafari Ranjbar     |    1937944    |
|          Marco Muscas         |    1883544    |
|        Giovanni Giunta        |    1177327    |
|        Francesco Lauro        |    1706784    |
| Shokoufeh Mansourihafshejani  |    1889621    |


