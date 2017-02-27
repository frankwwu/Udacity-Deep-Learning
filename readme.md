# Installing TensorFlow on Windows 10

Presently, TensorFlow on Windows 10 works with Python 3.5 only.

Steps of installation:
Download and install Anaconda3-2.4.0-Windows-x86_64-Py3.5.zip.
Open command prompt, and apply following commands:
conda install scikit-learn
conda create -n tensorflow python=3.5
python -m pip install --upgrade pip
pip install --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-0.12.1-cp35-cp35m-win_amd64.whl



