[← Back to overview](../README.md)

# Deep Learning (DL)
We recommend to firstly start with one or two [Machine Learning classes](ML.md), because Deep Learning is related to them and it will be easier for you.

<details>
<summary>Table of contents</summary>

* [Courses](#courses)
* [Libraries and Frameworks](#libraries-and-frameworks)
* [Curated Lists](#curated-lists)
* [Books](#books)
* [Researchers to follow](#researchers-to-follow)
* [Scientific Papers](#scientific-papers)
  + [Understanding, Generalization, Transfer](#understanding--generalization--transfer)
  + [Optimization, Training Techniques](#optimization--training-techniques)
  + [Unsupervised, Generative Models](#unsupervised--generative-models)
  + [Convolutional Neural Network Models](#convolutional-neural-network-models)
* [Cheat Sheet](#cheat-sheet)
* [Capsule Networks](#capsule-networks)
  + [Scientific Papers](#scientific-papers-1)
  + [Explanation](#explanation)

<!-- Table of contents generated with http://ecotrust-canada.github.io/markdown-toc/ -->
</details>

## Courses
* [Andrew Ng's deeplearning.ai class](https://www.deeplearning.ai/)
* [fast.ai](http://www.fast.ai/)
* [Stanford cs231n](http://cs231n.stanford.edu/)
* [Richard Socher's Deep Learning and Natural Language Processing](http://web.stanford.edu/class/cs224n/)
* [Hugo Larochelle's course](http://info.usherbrooke.ca/hlarochelle/neural_networks/content.html)
* [Nando de Freita's class on Machine/Deep Learning](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)
* [Hinton's Neural Network Machine Learning](https://www.coursera.org/learn/neural-networks)
* [Oxfords Deep NLP](https://github.com/oxford-cs-deepnlp-2017/lectures)
* [DeepSchool.io](https://github.com/sachinruk/deepschool.io)

## Libraries and Frameworks
If you don't know which DL library to start with, we suggest you to check [Ranking Popular DL Libraries](https://blog.thedataincubator.com/2017/10/ranking-popular-deep-learning-libraries-for-data-science/) from 10/2017 where the winner is [Tensorflow](https://www.tensorflow.org/), followed by [Keras](https://keras.io/) and [Caffe](http://caffe.berkeleyvision.org/).

Library | Rank | Overall | Github | Stack Overflow | Google Results
------- | ---- |-------- | ------ | -------------- | --------------
[Tensorflow](https://www.tensorflow.org/) | 1 | 10.8676777173 | 4.25282914794 | 4.371905768 | 2.24294280139
[Keras](https://keras.io/) | 2 | 1.92768682345 | 0.613405340454 | 0.830444013135 | 0.483837469861
[Caffe](http://caffe.berkeleyvision.org/) | 3 | 1.85536658344 | 1.00172325244 | 0.301598379669 | 0.552044951334

<details>
<summary>All 23 libraries and their usage (based on <a href="https://blog.thedataincubator.com/2017/10/ranking-popular-deep-learning-libraries-for-data-science/">Data Incubator ranking</a>)</summary>
<br>

Library | Rank | Overall | Github | Stack Overflow | Google Results
------- | ---- |-------- | ------ | -------------- | --------------
[Tensorflow](https://www.tensorflow.org/) | 1 | 10.8676777173 | 4.25282914794 | 4.371905768 | 2.24294280139
[Keras](https://keras.io/) | 2 | 1.92768682345 | 0.613405340454 | 0.830444013135 | 0.483837469861
[Caffe](http://caffe.berkeleyvision.org/) | 3 | 1.85536658344 | 1.00172325244 | 0.301598379669 | 0.552044951334
[Theano](http://deeplearning.net/software/theano/) | 4 | 0.757142065184 | -0.156657475854 | 0.361637072631 | 0.552162468406
[Pytorch](http://pytorch.org/) | 5 | 0.481418742361 | -0.198079135346 | -0.30225967424 | 0.981757551946
[Sonnet](https://github.com/deepmind/sonnet) | 6 | 0.427865682184 | -0.326074511957 | -0.361634296039 | 1.11557449018
[Mxnet](https://mxnet.incubator.apache.org/) | 7 | 0.0987996914674 | 0.121327235453 | -0.306328604959 | 0.283801060973
[Torch](http://torch.ch/) | 8 | 0.00559731666893 | -0.153332101969 | -0.00824393023136 | 0.167173348869
[Cntk](https://github.com/Microsoft/CNTK) | 9 | -0.0205203098963 | 0.0965088202554 | -0.282173869559 | 0.165144739407
[Dlib](http://dlib.net/ml.html) | 10 | -0.599823512154 | -0.39578194316 | -0.223382454956 | 0.0193408859617
[Caffe2](https://github.com/caffe2) | 11 | -0.671062928351 | -0.274071118159 | -0.359648165565 | -0.0373436446266
[Chainer](https://chainer.org/) | 12 | -0.70151841136 | -0.400397905813 | -0.234603397931 | -0.0665171076164
[Paddlepaddle](https://github.com/PaddlePaddle/Paddle) | 13 | -0.833003782881 | -0.267123408237 | -0.366884083295 | -0.198996291348
[Deeplearning4j](https://deeplearning4j.org/) | 14 | -0.893319117931 | -0.0575131634759 | -0.321347169592 | -0.514458784863
[Lasagne](https://lasagne.readthedocs.io/) | 15 | -1.10606125475 | -0.381150749139 | -0.287853956451 | -0.437056549158
[Bigdl](https://github.com/intel-analytics/BigDL) | 16 | -1.12821350465 | -0.458674544538 | -0.367555905286 | -0.301983054824
[Dynet](https://github.com/clab/dynet) | 17 | -1.25088837288 | -0.465671394541 | -0.367690269684 | -0.417526708658
[Apache Singa](https://singa.incubator.apache.org/) | 18 | -1.33963459336 | -0.502246959001 | -0.367824634082 | -0.469563000276
[Nvidia Digits](https://developer.nvidia.com/digits) | 19 | -1.39248467556 | -0.407011549848 | -0.346078273813 | -0.639394851898
[Matconvnet](http://www.vlfeat.org/matconvnet/) | 20 | -1.41327975079 | -0.487125591647 | -0.346308395531 | -0.579845763615
[Tflearn](http://tflearn.org/) | 21 | -1.44982650865 | -0.226089464016 | -0.282710110548 | -0.941026934086
[Nervana Neon](https://github.com/NervanaSystems/neon) | 22 | -1.65176202195 | -0.39497574163 | -0.366989720498 | -0.889796559818
[Opennn](http://www.opennn.net/) | 23 | -1.97015587693 | -0.53381703821 | -0.366068321175 | -1.07027051754

</details>

## Curated Lists
* [A guide to DL](http://yerevann.com/a-guide-to-deep-learning/) is very handy because all concepts are ranked by its difficulty
* [Awesome DL](https://github.com/ChristosChristofidis/awesome-deep-learning)

## Books
* [Deep Learning Book](http://www.deeplearningbook.org/), Ian Goodfellow, Yoshua Bengio and Aaron Courville
* [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/), Michael Nielsen

## Researchers to follow
* [Geoffrey Hinton](http://www.cs.toronto.edu/~hinton/nntut.html)
* [Yoshua Bengio](http://www.iro.umontreal.ca/~bengioy/yoshua_en/)
* [Yann Lecun](http://yann.lecun.com/)
* [Andrew Ng](http://www.andrewng.org/)
* [Andrew Karpathay](http://cs.stanford.edu/people/karpathy/)
* [Richard Socher](http://www.socher.org/)
* [Hugo Larochelle](https://research.google.com/pubs/105144.html)
* [Nando de Freitas](https://www.cs.ox.ac.uk/people/nando.defreitas/)

## Scientific Papers
Based on [Awesome DL Papers](https://github.com/terryum/awesome-deep-learning-papers#reinforcement-learning--robotics), counted since 2012 (last 5 years).

### Understanding, Generalization, Transfer
- [Visualizing and understanding convolutional networks](http://arxiv.org/pdf/1311.2901), M. Zeiler and R. Fergus, 2014
- [Decaf: A deep convolutional activation feature for generic visual recognition](http://arxiv.org/pdf/1310.1531), J. Donahue et al., 2014
- [CNN features off-the-Shelf: An astounding baseline for recognition](http://www.cv-foundation.org//openaccess/content_cvpr_workshops_2014/W15/papers/Razavian_CNN_Features_Off-the-Shelf_2014_CVPR_paper.pdf), A. Razavian et al., 2014
- [How transferable are features in deep neural networks?](http://papers.nips.cc/paper/5347-how-transferable-are-features-in-deep-neural-networks.pdf), J. Yosinski et al., 2014
- [Learning and transferring mid-Level image representations using convolutional neural networks](http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Oquab_Learning_and_Transferring_2014_CVPR_paper.pdf), M. Oquab et al., 2014
- [Distilling the knowledge in a neural network](http://arxiv.org/pdf/1503.02531), G. Hinton et al., 2015
- [Deep neural networks are easily fooled: High confidence predictions for unrecognizable images](http://arxiv.org/pdf/1412.1897), A. Nguyen et al., 2015

### Optimization, Training Techniques
- [Adam: A method for stochastic optimization](http://arxiv.org/pdf/1412.6980), D. Kingma and J. Ba, 2014
- [Dropout: A simple way to prevent neural networks from overfitting](http://jmlr.org/papers/volume15/srivastava14a/srivastava14a.pdf), N. Srivastava et al., 2014
- [Batch normalization: Accelerating deep network training by reducing internal covariate shift](http://arxiv.org/pdf/1502.03167), S. Loffe and C. Szegedy, 2015
- [Improving neural networks by preventing co-adaptation of feature detectors](http://arxiv.org/pdf/1207.0580.pdf), G. Hinton et al., 2012
- [Delving deep into rectifiers: Surpassing human-level performance on imagenet classification](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/He_Delving_Deep_into_ICCV_2015_paper.pdf), K. He et al., 2015
- [Random search for hyper-parameter optimization](http://www.jmlr.org/papers/volume13/bergstra12a/bergstra12a), J. Bergstra and Y. Bengio, 2012
- [Training very deep networks](http://papers.nips.cc/paper/5850-training-very-deep-networks.pdf), R. Srivastava et al., 2015

### Unsupervised, Generative Models
- [Generative adversarial nets](http://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf), I. Goodfellow et al., 2014
- [Building high-level features using large scale unsupervised learning](http://arxiv.org/pdf/1112.6209), Q. Le et al., 2013
- [Auto-encoding variational Bayes](http://arxiv.org/pdf/1312.6114), D. Kingma and M. Welling, 2013
- [Unsupervised representation learning with deep convolutional generative adversarial networks](https://arxiv.org/pdf/1511.06434v2), A. Radford et al., 2015
- [DRAW: A recurrent neural network for image generation](http://arxiv.org/pdf/1502.04623), K. Gregor et al.
- [Improved techniques for training GANs](http://papers.nips.cc/paper/6125-improved-techniques-for-training-gans.pdf), T. Salimans et al., 2016
- [Pixel recurrent neural networks](http://arxiv.org/pdf/1601.06759v2.pdf), A. Oord et al., 2016

</details>

## Wikipedia entries on Basic Concepts
* [Gradient ∇ (Nabla)](https://en.wikipedia.org/wiki/Del)
* [Backpropagation](https://en.wikipedia.org/wiki/Backpropagation)
* [Sigmoid σ](https://en.wikipedia.org/wiki/Sigmoid_function)
* [Rectifier (Rectified Linear Units or ReLU)](https://en.wikipedia.org/wiki/Rectifier_(neural_networks))
* [Tanh](https://en.wikipedia.org/wiki/Hyperbolic_function)
* [Gated recurrent unit (GRU)](https://en.wikipedia.org/wiki/Gated_recurrent_unit)
* [Long short-term memory](https://en.wikipedia.org/wiki/Long_short-term_memory)
* [Softmax](https://en.wikipedia.org/wiki/Softmax_function)
* [Regularization](https://en.wikipedia.org/wiki/Regularization_(mathematics))
  * [Difference between L1 and L2](http://www.chioka.in/differences-between-l1-and-l2-as-loss-function-and-regularization/)
  * [Dropout](https://wiki.tum.de/display/lfdv/Dropout)
* [Batch Normalization](https://wiki.tum.de/display/lfdv/Batch+Normalization)
* [Objective Functions](https://en.wikipedia.org/wiki/Mathematical_optimization)
* [F1 score](https://en.wikipedia.org/wiki/F1_score)
* [Cross entropy](https://en.wikipedia.org/wiki/Cross_entropy)

## Capsule Networks
### Scientific Papers
* [Dynamic Routing Between Capsules](https://arxiv.org/abs/1710.09829), Sara Sabour, Nicholas Frosst, Geoffrey E Hinton, 2017
  * [Matrix capsules with EM routing](https://openreview.net/forum?id=HJWLfGWRb&noteId=HJWLfGWRb), Blind Submission of CapsNets with Reviews, 2017

### Explanation
* [Aurélien Géron's tutorial](https://youtu.be/pPN8d0E3900), **recommended** by Geffrey Hinton himself
* [Understanding Hinton’s Capsule Networks](https://medium.com/ai%C2%B3-theory-practice-business/understanding-hintons-capsule-networks-part-i-intuition-b4b559d1159b)
