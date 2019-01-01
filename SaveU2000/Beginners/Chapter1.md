# Overview

- **Chapter 1: Introduction to Deep Learning**
  - 1.1: *Linear Models and Gradient Descent*
    - Binary Classification
    - Logistic Regression
    - Gradient Descent from Scratch
    
  - 1.2: *Machine Learning Frameworks*
    - Deep Learning
    - Machine Learning
    - Probablistic Learning
    
  - 1.3: *Deep Learning (for real)*
  
----

### 1.1: Linear Models and Gradient Descent

  - *Binary Classification*
    - https://machinelearningmastery.com/binary-classification-tutorial-with-the-keras-deep-learning-library/
    - https://www.digitalocean.com/community/tutorials/how-to-build-a-machine-learning-classifier-in-python-with-scikit-learn
    - https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html#sphx-glr-beginner-blitz-cifar10-tutorial-py
    - https://www.tensorflow.org/tutorials/keras/basic_text_classification
    - https://www.youtube.com/watch?v=eqEc66RFY0I (Andrew Ng's Deep Learning AI Course materials)
    
  - *Logistic Regression*
    - [Machine Learning: Regression](https://www.coursera.org/learn/ml-regression) by University of Washington on Coursera
    - https://www.machinelearningplus.com/machine-learning/logistic-regression-tutorial-examples-r/
    - https://machinelearningmastery.com/logistic-regression-tutorial-for-machine-learning/
    - https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8
    - https://towardsdatascience.com/logistic-regression-using-python-sklearn-numpy-mnist-handwriting-recognition-matplotlib-a6b31e2b166a
    
  - *Gradient Descent from Scratch*
    - https://gluon.mxnet.io/chapter06_optimization/gd-sgd-scratch.html
    - https://machinelearningmastery.com/implement-linear-regression-stochastic-gradient-descent-scratch-python/
    - http://datacognizant.com/wp-content/uploads/2017/03/LogisticRegression_loglikelihood_derivative_gradientdescent-1.html (althogh `graphlab` is no longer maintained the exercise for gradient descent is valid)


**References:**

 - [Introduction to Machine Learning with Python](http://shop.oreilly.com/product/0636920030515.do) by Sarah Guido, Andreas Müller
 - [Hands-On Machine Learning with Scikit-Learn and TensorFlow](http://shop.oreilly.com/product/0636920052289.do) by Aurélien Géron
 - [Data Science from Scratch](http://shop.oreilly.com/product/0636920033400.do) by Joel Grus
 - [Python Data Science Handbook](http://shop.oreilly.com/product/0636920034919.do) by Jake VanderPlas
 - [Programming Collective Intelligence](http://shop.oreilly.com/product/9780596529321.do) by Toby Segaran (a little outdated by if you like to code by example, this is perfect)
 - [Machine Learning in Action](https://www.manning.com/books/machine-learning-in-action) by Peter Harrington 

**Words of advice:**

  - If you haven't coded a gradient descent from scratch before you should really try.
  - If you can, join the University of Washington's regression course reference above, it's really good. If you can't afford it, try "audit the course" button or apply for the financial aid to enroll
  - If you like phyiscal books, start with the reference books above, you don't really have to buy them if you're residing locally, the national library board (in Singapore) have most them. If not you can download the NLB app and recommend the librarians to get it. =)
    
----

###  1.2: Introduction to Machine Learning Frameworks

  - *Deep Learning*
    - [Keras] https://web.stanford.edu/class/cs20si/lectures/march9guestlecture.pdf
    - [Keras] https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/
    - [Tensorflow] https://towardsdatascience.com/a-beginner-introduction-to-tensorflow-part-1-6d139e038278
    - [Tensorflow] https://cs230-stanford.github.io/tensorflow-getting-started.html
    - [Tensorboard] https://itnext.io/how-to-use-tensorboard-5d82f8654496 
    - [Tensorboard] https://www.youtube.com/watch?v=eBbEDRsCmv4
    - [PyTorch] https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html 
    - [PyTorch] https://towardsdatascience.com/pytorch-tutorial-distilled-95ce8781a89c
    - [PyTorch] https://pytorch.org/tutorials/beginner/finetuning_torchvision_models_tutorial.html (specific to Computer Vision)
    - [FastAI] https://www.fast.ai/
    - [DyNet] https://github.com/clab/dynet_tutorial_examples (specific to NLP)
   - *Machine Learning*
     - [scikit-learn] https://scikit-learn.org/stable/tutorial/index.html
     - [Vowpal Wabbit] https://github.com/VowpalWabbit/vowpal_wabbit/wiki
     - There's a couple on this list too http://www.erogol.com/broad-view-machine-learning-libraries/ 
   - *Probabilistic Learning*
     - [PyMC3] https://docs.pymc.io/
     - [Stan] https://mc-stan.org/ 
     - [Statsmodels] http://www.statsmodels.org/stable/index.html
     - [Tensorflow Probability] https://www.tensorflow.org/probability/ , see also http://dustintran.com/talks/Tran_Edward.pdf
     
**References**

 - Tensorflow course on Udacity: https://www.udacity.com/course/deep-learning--ud730 (Knowledge is free, certification needs payment)
 - PyTorch course on Udacity https://in.udacity.com/course/deep-learning-pytorch--ud188 
 -  Fast AI https://www.fast.ai/ 
 - Bayesian analysis https://sites.google.com/site/doingbayesiandataanalysis/what-s-new-in-2nd-ed 
    
**Words of advice:**

 - Best help on the framework you get would be the dev-users communication channels that are in place for the specific frameworks
   - [PyTorch] https://discuss.pytorch.org/
   - [Tensorflow/Keras] https://www.tensorflow.org/community/ (mainly stackoverflow, just tag your question with `tensorflow` tag)
   - [Fast AI] https://forums.fast.ai/ 
 - Knowing tensorboard will get you far, do take a look at https://www.youtube.com/watch?v=eBbEDRsCmv4
 - The video/book tutorials in the references above are great start to the frameworks, investing time in them will save you time learning the way of the hard knocks later.
 
----


### 1.3: Deep Learning (for real)

Honestly, if you're only learning how to use frameworks and knowing which models/layers to use to specific tasks, it's cool and most probably you get something working. 

Knowing how to debug when training the model, how to evaluate models and how to improve the models has little to do with whether you know the syntax of the frameworks or stack the layers properly.

My suggestion is to go through the introduction courses listed in the reference list in 1.2 tediously. 
 
  - Don't just watch the videos and `shift`+`enter` through the notebooks
  - Do change some values in the notebooks and see how and understand why the function/layer/outputs reacts to the changes
  - Don't keep to yourself if you're stuck, go to the respective forums of the framework to look for help
  - Do be nice and descriptive when asking for help =)
  <!-- - Don't pass go, don't collect $200 (Just joking on this point; pardon the bad Monopoly game pun) -->
  
If you want a real deep dive to "Deep Learning (for real)", many good universities have their course materials freely available, there's no need to really pay someone to regurgitate them to you ;p

- Stanford Deep Learning Course http://cs230.stanford.edu/syllabus.html
- MIT Deep Learning Course http://introtodeeplearning.com/2018/index.html 
- CMU Deep Learning Course http://deeplearning.cs.cmu.edu/
- Berkley Deep Learning Course https://berkeley-deep-learning.github.io/ 
- Princeton Deep Learning Course https://www.cs.princeton.edu/courses/archive/spring16/cos495/

