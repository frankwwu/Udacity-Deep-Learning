# Installing TensorFlow on Windows 10

Presently, TensorFlow on Windows 10 works with Python 3.5 only.

## Steps of installation:

1. Download and install Anaconda3-2.4.0-Windows-x86_64-Py3.5.zip.

2. Open command prompt, and apply following commands:

> conda install scikit-learn

> conda create -n tensorflow python=3.5

> python -m pip install --upgrade pip

> pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-1.0.1-cp35-cp35m-win_amd64.whl 

## Creating batch files (Optional)

1. Make the batch file __ipython-notebook.bat__ for stating the notebook. You can copy the .bat file to any of your working folders, and double-click it to launch the notebook.

    <code>ipython notebook</code>

2. Make the batch file __tensorboard.bat__ containing following command for starting TensorBoard. To launch TensorBoard, right-click the file, select __Run as administrator__)

    <code>tensorboard --logdir=path/to/logs</code>


# Supplementary References

[Getting Started With TensorFlow](https://www.tensorflow.org/get_started/get_started)

[CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.github.io/)

[DeepLearning 0.1 documentation](http://deeplearning.net/tutorial/contents.html)

[An Intuitive Explanation of Convolutional Neural Networks](https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/)