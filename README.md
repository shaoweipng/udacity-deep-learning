
# udacity-deep-learning
Assignments of the Udacity MOOC Deep Learning

This repository stores the assignments I have done during the [Udacity MOOC on Deep Learning][udacity-deep-learning]. The course is free but there is no support expect if you register to a [nanodegree program][udacity-nanodegree]. That's why I have I tried to comment as much as possible my results, you may find them useful.

## Installation and setup

Note that 4 GB of RAM are short to run the notebooks, 8 GB will be more comfortable.

I already had [Jupyter Notebook][jupyter] running on my Mac. For reference, it has been shipped with [Anaconda][anaconda] which is my Python bundle of choice. It works on Linux as well.

The only module to install from there is TensorFlow. The installation from ``pip`` is fine to me, the only trick is that the version 0.6.0 has been required (not the latest one). You can refer to the [official documentation][tensorflow-pip-install]. So the installation is done with a single command line:

```
pip install --upgrade https://storage.googleapis.com/tensorflow/mac/tensorflow-0.5.0-py2-none-any.whl
```

You can now grab the assignments from here to run my code or the stubs from the [TensorFlow repository][tensorflow-repo].

## Quick start

From the repository root, start Notebook with ``jupyter notebook``.

## Contributions

This repository is mainly for my own purpose but I would be happy to share some thoughts with you. There are probably many ways to improve and tune the various neural networks.

To do so, just fork this repository. 

## Credits

+ all the assignments come from [Udacity][udacity-deep-learning] and the [TensorFlow repository][tensorflow-repo]
+ the weird fonts data set used for this training is the [notMNIST dataset][notmnist] from Yaroslav Bulatov (there are also a download mirrors for the [large][notmnist-large] and [small][notmnist-small] dataset)
+ the final neural network of the assignment #4 is loosely inspired by the notorious LeNet-5, as described in the research paper ["Gradient-Based Learning Applied to Document Recognition"][lenet-5] by Y. LeCun, L. Bottou, Y. Bengio and P. Haffner
 
[udacity-deep-learning]: https://www.udacity.com/course/deep-learning--ud730
[udacity-nanodegree]: https://www.udacity.com/nanodegree

[jupyter]: http://jupyter.org/
[anaconda]: https://www.continuum.io/
[tensorflow-pip-install]: https://www.tensorflow.org/versions/0.6.0/get_started/os_setup.html#pip_install
[tensorflow-repo]: https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/udacity

[notmnist]: http://yaroslavvb.blogspot.fr/2011/09/notmnist-dataset.html
[notmnist-large]: http://commondatastorage.googleapis.com/books1000/notMNIST_large.tar.gz
[notmnist-small]: http://commondatastorage.googleapis.com/books1000/notMNIST_small.tar.gz
[lenet-5]: http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf
