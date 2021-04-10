# Computer Vision Assignment MIDAS

__(Attempted Task@2 by MIDAS Lab@IITD for Summer Internship 2021)__

## __Overview Of the Task__

As per the task was based on Image Classification, the problem was devided into three parts:</br>
-   __Part 1__: Creating a random model and training on dataset containing 62 classes.

-   __Part 2__: Selecting (0-9) number labeled images from the above dataset and training it from the scratch, then using the same pretrained model for MNIST dataset.

-   __Part 3__: Training on noisy labelled dataset from the scrath using the pretrained model from part. __PLEASE DO ACKNOWLEDGE__: I had a little bit of doubt regarding this  question as we were being told to use pretrained model from scratch and provide test accuracy.  So two methods were coming to my mind:
  - 1. Taking this whole noisy dataset as our training dataset and using MNIST test dataset as our validation dataset.
  - 2. Splitting this dataset into train and validation dataset and then using the trained model on MNIST dataset and than providing the test accuracy.

I didn't want to left out on any part, so I went away with both these methods.
I have organised separated both of these problems in CV_TASK_1.3. You can either check both of these prolem or just check the right one for that matter. 

### Directory:

    |- CV_TASK_1.1                                        #task 1    
    |     |---MIDAS_CV_PART_1.ipynb                       #Notebook
    |     |---T1_model1.h5                                #saved model
    |-CV_TASK_1.2
    |     |--- MIDAS_CV_PART_2.1                          #This folder contains the notebook and model on which 0-9 images were trained.
    |        |---|--- MIDAS_CV_PART_2.1.ipynb             #Notebook containg the code and logs
    |        |---|--- T2_model_1.h5                       #Saved model
    |     |--- MIDAS_CV_PART_2.2
    |        |---|--- MNIST_CV_PART_2.2.ipynb             #Notebook containg the code and logs
    |        |---|--- BASE MODEL                          #Baseline Model
    |- CV_TASK_1.3
    |    |--- MIDAS_CV_PART_3.1                           #This folder contains the approach 1 for Task 3
    |        |---|--- MIDAS_CV_PART_3.1.ipynb             #Notebook containg the code and logs
    |        |---|--- T3_model_1.h5
    |     |--- MIDAS_CV_PART_3.2
    |        |---|--- MNIST_CV_PART_3.2.ipynb             #This folder conatins the approach 2 for Task 3
    |        |---|--- T3_model_2.h5                       #Notebook containg the code and logs
    
    
 ## __References__
 __Advanced Deep Learning with Keras By Rowel Atienza__ </br>
 ['CNN with Tensorflow|Keras for Fashion MNIST'](https://www.kaggle.com/gpreda/cnn-with-tensorflow-keras-for-fashion-mnist) 
