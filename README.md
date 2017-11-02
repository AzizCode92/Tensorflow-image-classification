# Tensorflow-image-classification 
This is the repository developed for 'Image Classifier in TensorFlow in 5 Min on [Youtube](https://www.youtube.com/watch?v=QfNvhPx5Px8) using this [CodeLab](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/?utm_campaign=chrome_series_machinelearning_063016&utm_source=gdev&utm_medium=yt-desc#0) by Google as a guide.

You can use this classifier to automatically label whether an image taken is of a Tiger or a Jaguar. 

 
![es](https://github.com/AzizCode92/Tensorflow-image-classification/blob/master/test1.jpg  "Tiger")
![es](https://github.com/AzizCode92/Tensorflow-image-classification/blob/master/test4.jpg  "Jaguar")

## Requirements

* [docker](https://www.docker.com/products/docker-toolbox)

## Usage 

1. Start the docker image `docker run -it -v [path_to_project]/tf_files/images:/images/ gcr.io/tensorflow/tensorflow:latest-devel`
2. Run the label_image script to label the image. `python /tf_files/label_image.py <path_to_file>`

## Results
![el](https://github.com/AzizCode92/Tensorflow-image-classification/blob/master/test4_acc.png  "Test Accuracy(Jaguar)")

![el](https://github.com/AzizCode92/Tensorflow-image-classification/blob/master/test1_acc.png  "Test Accuracy(Tiger)")



