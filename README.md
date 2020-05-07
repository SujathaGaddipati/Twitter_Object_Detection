# Twitter_Object_Detection
## Introduction
- The task in here is to build an ML algorithm that will be trained on identifyinh the bounding box for the twitter following buttons.
- The end output would return the images with the bounding box and the cordinates for the box.
- I have used the retinanet for object detection. To use this network, I have cloned the notebook with Fizyr github account.
- Installed certain packages that I required for the running the retinanet model.
- Dataset preparation and image labelling
- Model training
- Model prediction

## Requirments
- Clone fizyr git account to load and use the retinanet model
- install Tensorflow, Keras-retinanet, Opencv, Pillow image library
- The zip file includes sample images, download the zip files dataset to run the code file.

## Usage
The code file can be downloaded and used. The installing commands are all put together in the file, with dataset preparation. The zip file contains 5 twitter images. Four of the images are used for training the dataset and one image is used for model validation. The model does not need a GPU system, it can run on the CPU system.

##### Reference code:
https://www.curiousily.com/posts/object-detection-on-custom-dataset-with-tensorflow-2-and-keras-using-python/

