

# udacity-deep-learning
Udacity MOOC Deep Learning with Google assignments

This repository contains the assignments I have done during the [Udacity MOOC on Deep Learning with Google][udacity-deep-learning]. The course is free but there is no support expect if you register to a [nanodegree program][udacity-nanodegree]. That's why I'm sharing my homeworks with as much comments as possible, you may find them useful.

**Disclaimer:** there is probably a code of conduct if you are enrolled in the nanodegree. Copying the code from the repository and pretending it to be sure would be bad. Even looking into it may be an infringement. Talk to your instructor.

The course is just great. I have posted an [extended review of it on my blog][ab.com-udacity-deep-learning]. You will use and develop neural networks for image recognition with convolution, natural language processing with embeddings and character based text generation with RNN/LTSM.

See below one of the outcome of the course, a t-SNE projection of word vectors, clustered by similarity.

![t-SNE projection of word vectors clustered by similarities][tsne-word-vectors]

Amazing, isn't it?

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
[ab.com-udacity-deep-learning]: http://arnaudbertrand.io/blog/2016/06/21/deep-learning-and-tensorflow-mooc-udacity-with-google/

[jupyter]: http://jupyter.org/
[anaconda]: https://www.continuum.io/
[tensorflow-pip-install]: https://www.tensorflow.org/versions/0.6.0/get_started/os_setup.html#pip_install
[tensorflow-repo]: https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/udacity

[notmnist]: http://yaroslavvb.blogspot.fr/2011/09/notmnist-dataset.html
[notmnist-large]: http://commondatastorage.googleapis.com/books1000/notMNIST_large.tar.gz
[notmnist-small]: http://commondatastorage.googleapis.com/books1000/notMNIST_small.tar.gz
[lenet-5]: http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf

[tsne-word-vectors]: https://raw.githubusercontent.com/Arn-O/udacity-deep-learning/master/assets/img/word-similarities-tsne.png "t-SNE projection of word vectors clustered by similarities"
