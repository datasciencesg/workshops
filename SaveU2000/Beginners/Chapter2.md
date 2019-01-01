# Overview

- **Chapter 2: Computer Vision and Convolutional Neural Net**
  - 2.1: *Introduction to Computer Vision*

  - 2.2: *Convolutional Neural Net*
    - Blogposts that presents CNN
    - Show me the Code
    
  - 2.3: *Convolutional Neural Net (for real)*
  
----

### 2.1: Introduction to Computer Vision

 - Georgia Tech Course: https://www.cc.gatech.edu/~hays/compvision/
 - Yet another Georgia Tech Course: https://samyak-268.github.io/F18CS4476/
 - Udacity Intro to Computer Vision: https://classroom.udacity.com/courses/ud810
 - KAIST Course: http://vclab.kaist.ac.kr/cs484/index.html 
 - MIT computer Vision class: https://www.youtube.com/watch?v=CLOAswsxudo (part of [self-driving cars course](https://selfdrivingcars.mit.edu/))
 - Stanford course http://cs231n.stanford.edu/ 
 
 
### 2.2: Convolutional Neural Nets (CNN)

 - *Blogposts that presents CNN*
   - https://medium.freecodecamp.org/an-intuitive-guide-to-convolutional-neural-networks-260c2de0a050
   - https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/
   - https://skymind.ai/wiki/convolutional-network
   - https://towardsdatascience.com/convolutional-neural-networks-from-the-ground-up-c67bb41454e1
   - https://www.analyticsvidhya.com/blog/2018/12/guide-convolutional-neural-network-cnn/ (Quite a lot of ads on the page though)
   - https://medium.com/@RaghavPrabhu/understanding-of-convolutional-neural-network-cnn-deep-learning-99760835f148
   - https://developer.nvidia.com/discover/convolutional-neural-network (at the end of the post, there's a few links that are really good for further readings about CNN)
   
 - *Show me the Code*
   - https://www.tensorflow.org/tutorials/estimators/cnn
   - http://adventuresinmachinelearning.com/keras-tutorial-cnn-11-lines/ (the pop-up advertises his book though...)
   - https://www.kaggle.com/cdeotte/how-to-choose-cnn-architecture-mnist 
   - https://github.com/keras-team/keras/blob/master/examples/mnist_cnn.py 
   - https://medium.com/tensorflow/hello-deep-learning-fashion-mnist-with-keras-50fcff8cd74a
   - https://github.com/MorvanZhou/PyTorch-Tutorial/blob/master/tutorial-contents/401_CNN.py
   

**Reference**  
  - Udacity PyTorch course: https://classroom.udacity.com/courses/ud188 
  - Udacity Tensorflow course: https://classroom.udacity.com/courses/ud730
  - Stanford Course http://cs231n.github.io/convolutional-networks/
  - Kaggle Learn https://www.kaggle.com/learn/deep-learning
    

### Convolutional Neural Net (for real)

Frankly, blogposts are nice as an idea introducer. After that one should either dive into the code or get onto the free classes (in the reference list above) to understand the details of why and how CNNs work. CNN are powerful tools that can solve many problems (even outside of computer vision). Usually, any of the courses listed above should cover:

 - What is the covolution filter?
 - What is a fully connected layer? What is pooling? What is the difference? 
 - What are the different "dimensions", "channels" in convolution neural nets?
 - How to not overfit? (the measures to prevent overfit is aka regularization)
 - How to use dropout as a regularization measure? 
 - How to apply simple convolution neural nets to image classification task?

Sometimes, there'll be more practical knowledge in the classes above too:

 - How to apply deeper CNN architectures to image classification task? 
 - How to use pre-trained models from other people to do tansfer learning

After knowing what CNN layers does and what convolutional filters are and CNN arithmetics in details, you might not go far. To really understand CNNs and make them work, most probably you need some understanding about state of art variants of CNNs and how CNNs are stacked to form bigger architectures, e.g. Resnet, VGGnet, Inception, YOLO etc. should be the end goal one should seek. And to understand these new architectures, normally Googling these terms with your deep learning framework of choice would point to good tutorial/code that you can read, e.g. "Resnet pytorch", "inception keras".

My suggestion is to go through the CNN class in the courses listed in the reference list in 2.2 tediously.
 - Do learn about *transfer learning* to save you on GPU computation cost, your precious time and sanity =)
 - FYI, *transfer learning* in CNN and computer vision is aka freeze some/most layers, unfreeze usually the last one or few layers
 - Do try to learn about new variants on top of CNN and architectures other than CNN through arixv or new reseach papers
 - Usually when most bootcamps/coding courses prepare the materials for a certain well know architecture, you can most probably learn about it by googling the architecture name with the DL framework of your choice. 
 
P/S: 
 
I do see some DL training courses touch of state-of-the-art or fresh out of the oven architectures and those usually leave me impressed. Otherwise if it's simply introducing CNN, there's more than enough information out there to learn for free =)

Also, sometimes you see coding courses/bootcamps giving a lot of new terminology in their syllabus. Most of those times, they are jargons that can be explained simply, don't be afraid to ask on the Data Science SG Facebook about what these terms are or how to find resources that can help explain those terms. For example, the course syllabus might throw you a list of jargon `["Adam", "Adagrad", "AdaDelta", "AdaMax", "NAdam", "RMSprop", "SGD", "WAdam"]`, indeed there are important differences between these names but they achieve the same purpose of updating gradients so that the model can update the parameters, i.e. optimizing the model (and that's why they're called optimizer). If the course briefly explains the difference and simply just goes through the fact that they exist in the deep learning library that you're using and show you the following images, then you're better off (i) learning to code gradient descent from scratch, then (ii) just reading [Sebastian Ruder's blogpost](http://ruder.io/optimizing-gradient-descent/index.html#visualizationofalgorithms):

![](http://ruder.io/content/images/2016/09/contours_evaluation_optimizers.gif)

![](http://ruder.io/content/images/2016/09/saddle_point_evaluation_optimizers.gif)



