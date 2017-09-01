# Semantic Segmentation

### Introduction
In this project, we will label the pixels of a road in images using a Fully Convolutional Network (FCN).

The results of the run are present in the logsData file. The test images are in the `runs` folder.

Example output: 

[!image](/runs/1504262773.4239352/umm_000012.png)

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

 ## How to write a README
[A good guide](https://www.udacity.com/course/writing-readmes--ud777).
