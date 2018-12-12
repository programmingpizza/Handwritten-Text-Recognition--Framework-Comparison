# Handwritten-Text-Recognition--Framework-Comparison

The project focuses on comparison of different frameworks for Handwritten text recognition. The Handwritten text recognition dataset being overstudied, a clear comparison of the frameworks being used should give us a better idea on how to use concepts of machine learning and what framework to use for recognition of handwritten texts.

## Getting Started

We are working with MNIST dataset.  
Install all the required librabries

### Prerequisites
* Scikit Learn
* TensorFlow
* Pytorch
* Apache MXNET with Amazon Gluon

## Built With
* Python 3.6
* Sklearn 0.20.0
* Tensorflow 1.12
* Pytorch 0.41
* Apache MXNET with Gluon

## Convolutional Neural  Networks
* Convolutional Networks work by moving small filters across the input image. This means the filters are re-used for recognizing patterns throughout the entire input image.

* This makes the Convolutional Networks much more powerful than Fully-Connected networks with the same number of variables. 
* This in turn makes the Convolutional Networks faster to train.



## Observations
* With Sklearn the best efficiency is achieved by Random Forest ( 93.86%)
* With TensorFlow following models are implemented:
  Keras- 97.87%
  TensorFlow- CNN- 91%
* With PyTorch the efficiency achieved was 97.8% (CNN)
* With Apache MXNET and Amazon Gluon the efficiency achieved was 97.01% for MLP and 98.95% for CNN

## Conclusion
 A lot of different frameworks are available in the market. Apache MXNET and Amazon Gluon performs the best in the given tested frameworks.


## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Jainam Shah** - [ProgrammingPizza](https://github.com/programmingpizza)

See also the list of [contributors](https://github.com/programmingpizza/Handwritten-Text-Recognition--Framework-Comparison/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
