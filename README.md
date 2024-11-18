# Plant-Disease-Detection
The project is to develop a software program that detects these kinds of harmful diseases in the early stage itself in order to reduce the damage that is caused to the crops. This is done using image processing
techniques. The software built in this project acts as a primary check of plant disease detection with the main aim of decreasing false negatives. The software built will take the input as the image of the leaves of the plant and classify the leaf as tend to be diseased or not, using computer aided techniques like machine learning. Dataset used in this process consists of a good ratio of health and sick leaves. Convolution neural network is used to classify the images and has an accuracy of 93.2%. Implementation is done using adam optimizer and 25 epochs for the accuracy check. The dataset is splitted on the basis of having more sick
images in the testing set so that it is easy for the classification and it is used 70% on training and 30% on testing approximately. Out of a total 3900 images, around 2700 are used for training and 1200 are used for testing. The training of the model using those 2700 images is done on the basis of all possible angles and lighting conditions of a single leaf image rather than training more individual leaf images. The dataset consists of 39 classes of the diseased leaf which are occurring regularly in the plant of different species. While doing so, it is easy for testing phase and also the classification becomes easier as the number of images used for training are more and also the accuracy can be increased and the prediction of the output will be optimal.

**Libraries and Softwares**
Platform - Google colabs. Colab allows anybody to write and execute arbitrary python code through the browser using the notebook by colabs.

Editor - Jupyter Notebook. Notebook which is used for creating the python files.

Python Libraries - Matplotlib , CV2 , OS , Skimage , Pandas ,Numpy, PIL.

Keras and Tensorflow – open source libraries used for machine learning applications.These are used for defining the neural networks.

Convolution Neural Network - This Network is used for creating the model for the application.

