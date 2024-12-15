The dataset for this assignment consists of 60,000 28x28 grayscale images in ten fashion categories, along with a test set of 10,000 images under labels 0 to 9 each number corresponding to a specific clothing item or foot wear. It is made freely available under the MIT License.
Further citation to the owners of this data can be obtained at [zalandoresearch/fashion-mnist: A MNIST-like fashion product database. Benchmark] with Han Xiao and Kashif Rasul and Roland Vollgraf referenced as the authors.
We use keras in python because it simplifies the process of developing and experimenting with deep learning models.
We import Tensorflow and use the Keras libraries, as well as other necessary libraries like Numpy and Matplotlib, for numerical computing and data visualization.
We load and preprocess the Fashion MNIST dataset readily available in Keras and add a channel dimension, respectively.
We normalize the data to ensure it’s on a similar scale to improve accuracy with our model. 
Since our dataset consists of grayscale images with shapes (28, 28), we added the channel dimension shape (28,28,1) to inform the model that they will run one channel and, as such, process the images correctly.
To implement a CNN with six layers to classify our dataset, we used a combination of convolutional, pooling and fully connected layers to execute this outcome on our dataset.
Thereafter, we make predictions for atleast two images from our Fashion MNIST dataset.
