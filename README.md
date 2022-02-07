# 2022Spring-Project-STAT
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)

# Implementation of Accurate Binary Convolutional Neural Network

<span style="color:red">Wei Pan,Xiaofan Lin,Cong Zhao [Towards Accurate Binary Convolutional Neural Network][ref1][NIPS 2017]</span>

The project is based on the NIPS 17 paper [1]
that brings Binary Neural Networks to CNNs and studies the
top 1% and 5% accuracy. The goal of Binary networks is to
reduce memory storage requirements, improve power efficiency
and reduce floating point operations (especially multiplication
in convolution). Binary CNNs also increase the parallelization
ability of the computation and can work better with specialized
hardware The approximated model accuracy is quite near the
actual model for small datasets but drops for larger datasets. A
tabular representation or a metric to study the computational
gain will be modeled as part of the project. More recent
approaches and future scope are discussed and are likely to be
explored as the project progresses.

## Code Run Instructions
Install the necessary requirements by running the following command.

~~~python
pip install -r requirements.txt
~~~

next run the main_notebook which contains the keras model defination.
The model can be loaded directly using the 
~~~python
import tensorflow
model = tensorflow.keras.models.load_model('path/to/location')()
~~~
Each model can be run and verified.

# Organization of this directory
The project directory is organised as follows
```
./
├── README.md
├── requirements.txt
├── e4040-2021Fall-Project-ABCN-sg3904-mk4427-ads2251.pdf
├── dataset_loader
│   ├── __pycache__
│   │   └── data_loader.cpython-36.pyc
│   └── data_loader.py
├── main_notebook.ipynb
└── utils
    ├── CustomActivations
    │   ├── __pycache__
    │   │   └── activations.cpython-36.pyc
    │   └── activations.py
    ├── CustomCallbacks
    │   ├── __pycache__
    │   │   └── callbacks.cpython-36.pyc
    │   └── callbacks.py
    ├── CustomLayers
    │   ├── __pycache__
    │   │   ├── binary_layers.cpython-36.pyc
    │   │   └── ternary_layers.cpython-36.pyc
    │   ├── binary_layers.py
    │   └── ternary_layers.py
    └── CustomOperations
        ├── __pycache__
        │   ├── binary_ops.cpython-36.pyc
        │   └── ternary_ops.cpython-36.pyc
        ├── binary_ops.py
        └── ternary_ops.py

11 directories, 18 files
```

# Code Content

>dataset_loader
~~~python
Loads the MNIST Dataset
~~~

>CustomActivations
~~~python
Contain activation functions implemented
~~~

>CustomCallbacks
~~~python
Contain callback functions implemented
~~~

>CustomLayers
~~~python
Contain binary and ternary layers implemented
~~~

>CustomOperations
~~~python
Contain binary and ternary operations implemented
~~~



# References

[ref1]: http://papers.nips.cc/paper/6638-towards-accurate-binary-convolutional-neural-network
Wei Pan,Xiaofan Lin,Cong Zhao Towards Accurate Binary Convolutional Neural Network[NIPS 2017]

# Models Drive Link

https://drive.google.com/file/d/1n8RlbHh1abPmFBUd2IhhZgG5EcmeQ5Ui/view?usp=sharing

# Paper Link
https://drive.google.com/file/d/13Zi08oF2SK7KGa-21_S9ejlzhZjkgXoe/view?usp=sharing
