# Overview

- **Chapter 5: Nuts and Bolts in Machine Learning** 
  - 5.1: *Bias and Variance*
  - 5.2: *Regularlization*
    - Why is my Neural Network not working?
    - Weights Regularization and Dropout
  - 5.3: *Knowledge Distilation*
  
**Note:** This chapter doesn't have the "for real" section because every point in here seems to be the for real part when we train models with realistic datasets. 

----


### 5.1: Bias and Variance

 - Andrew Ng's ML Course https://www.coursera.org/lecture/deep-neural-network/bias-variance-ZhclI 
   - see also the NIPS 2016 tutorial https://www.youtube.com/watch?v=wjqaz6m42wU (slides: https://media.nips.cc/Conferences/2016/Slides/6203-Slides.pdf) 
   - see also https://www.youtube.com/watch?v=F1ka6a13S9I
   - and if you're a fan, here's Andrew Ng on the same topic a longer time ago https://www.courses.com/stanford-university/machine-learning/9 
 - Emily Fox's ML Course https://www.coursera.org/lecture/ml-regression/variance-and-the-bias-variance-tradeoff-ZvP40
 - Yaser Abu-Mostafa's Caltech Course https://www.youtube.com/watch?v=zrEyxfl2-a8 (a little dense but if you come from the math/stats path, you might like it)
 - Sebastian Thrun explaining causually when in a self-driving car https://www.youtube.com/watch?v=W5uUYnSHDhM 
 - https://www.ics.uci.edu/~smyth/courses/cs274/readings/xing_singh_CMU_bias_variance.pdf (hardcore math but good)
 - [A Modern Take on the Bias-Variance Tradeoff in NN](https://arxiv.org/pdf/1810.08591.pdf)
 - https://www.learnopencv.com/bias-variance-tradeoff-in-machine-learning/
 - http://www.r2d3.us/visual-intro-to-machine-learning-part-2/
 - https://towardsdatascience.com/understanding-the-bias-variance-tradeoff-165e6942b229
 - In terse math: http://www.inf.ed.ac.uk/teaching/courses/mlsc/Notes/Lecture4/BiasVariance.pdf 
 - https://kevinzakka.github.io/2016/09/26/applying-deep-learning/
 
### 5.2: Regularization

 - Why is my Neural Network not working?
  - https://blog.slavv.com/37-reasons-why-your-neural-network-is-not-working-4020854bd607
  - https://machinelearningmastery.com/introduction-to-regularization-to-reduce-overfitting-and-improve-generalization-error/
  - https://keras.rstudio.com/articles/tutorial_overfit_underfit.html
  - Be Nice to your Neurons https://www.cl.cam.ac.uk/~pv273/slides/UCLS2.pdf
  
 - Weights Regularization, Activity Regularization and Dropout
   - https://stackoverflow.com/questions/50649831/understanding-regularization-in-keras
   - https://machinelearningmastery.com/weight-regularization-to-reduce-overfitting-of-deep-learning-models/
   - https://www.fast.ai/2018/07/02/adam-weight-decay/
   - Practical Keras code snippets for regularization https://www.ics.uci.edu/~mohamadt/keras_DL.pdf 
   - Weights vs Acvity Regularization: https://github.com/keras-team/keras/issues/1618
   - https://robotwealth.com/deep-learning-trading-fighting-overfitting-dropout-regularization/
   - https://machinelearningmastery.com/dropout-regularization-deep-learning-models-keras/
   - Dropout in 3 lines of Python https://iamtrask.github.io/2015/07/28/dropout/ 
   - The original Dropout paper: https://www.cs.toronto.edu/~hinton/absps/JMLRdropout.pdf
   - Keras author on weights regularization vs dropout https://twitter.com/fchollet/status/763085560206340096
   
 - Knowledge Distillation (maybe not so beginner but good to know to make your models smaller)
  - The paper: https://arxiv.org/abs/1503.02531 
  - https://github.com/Ujjwal-9/Knowledge-Distillation
  - https://jacobgil.github.io/deeplearning/pruning-deep-learning
  - https://www.oreilly.com/ideas/compressing-and-regularizing-deep-neural-networks
  - https://github.com/kmsravindra/ML-AI-experiments/blob/master/AI/knowledge_distillation/Knowledge%20distillation.ipynb
  - https://medium.com/neural-machines/knowledge-distillation-dc241d7c2322
  - https://github.com/dkozlov/awesome-knowledge-distillation
  - https://github.com/NervanaSystems/distiller/

