# Overview

- **Chapter 3: Recurrent Neural Nets, Self-Attention Nets and Natural Language Processing**

  - 3.1 *Introduction to Natural Language Processing*
 
  - 3.2 *Recurrent Neural Nets*
    - Blogposts that presents RNN
    - Show me the Code
    - Show me the Math
 
  - 3.3 *Self-Attention Nets* (aka Transformer)
     - Blogposts that presents Transformer
     - Show me the Code
     - Show me the Math
   
 - 3.4 *Natural Language Processing (for real)*
   
----


### 3.1: **Introduction to Natural Language Processing**

**The Get things done Way**

 - PyTorch Tutorials:
   - 
   - https://pytorch.org/tutorials/beginner/deep_learning_nlp_tutorial.html (take a look at others under the `Text` section on the left panel too)
   
 - SpaCy Tutorials
   - 
 - Gensim Tutorials
   - https://lilianweng.github.io/lil-log/2017/10/15/learning-word-embedding.html
 - NLTK Basics (the useful bits): 
   - 
   -

**The Slow and Steady Way**

 - Stanford Course: https://web.stanford.edu/class/cs224n/ 
 - Berkley Course: http://people.ischool.berkeley.edu/~dbamman/nlp18.html
 - [Lisbon Machine Learning School (LxMLS 2018)](http://lxmls.it.pt/2018/?page_id=19) (focuses a lot on NLP in 2018)
 - Saarland University [Foundations in Language Sciencea and Technology (FLST) course](http://www.coli.uni-saarland.de/courses/FLST/2018/FLST.html)  
  - National University of Singapore (NUS) [Deep Learning for NLP Course](https://www.comp.nus.edu.sg/~kanmy/courses/6101_1810/)
  
**Books / Articles**
 
  - [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/) (Jurafsky and Martin's Book) 
  - [Foundations of Statistical Natural Language Processing](https://nlp.stanford.edu/fsnlp/) (Chris Manning's book, hardcore math)
  - [Computational Linguistics and Deep Learning](https://www.mitpressjournals.org/doi/pdf/10.1162/COLI_a_00239) (Chris Manning's words in 2015)
  - [A Primer on Neural Network Models for Natural Language Processing](https://u.cs.biu.ac.il/~yogo/nnlp.pdf) (Yoav Goldberg's book/chapter)
    - physical book version on https://www.morganclaypool.com/doi/abs/10.2200/S00762ED1V01Y201703HLT037
  - [Jacob Einstein's notes on NLP and DL](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)
 
   
**Related but not directly**

  - [Artificial Intelligence: A Modern Approach](http://aima.cs.berkeley.edu/) (Russell and Norvig's book)
    - Borrow from national library, click [here](https://catalogue.nlb.gov.sg/cgi-bin/spydus.exe/FULL/WPAC/BIBENQ/13461273/269039522,1) =) 
  - [Deep Learning](https://www.deeplearningbook.org/) (Goodfellow et al. book)
  
   
**Words of advice:**

  - NLP is kind of niche but still a pretty wide subfield, knowing little goes a long way but understanding the basics goes a longer way.
  - The courses above requires quite a lot of committment 


----


### 3.2: **Recurrent Neural Nets and Attention Mechanism**

  - Blogpost that explains RNN
    - http://colah.github.io/posts/2015-08-Understanding-LSTMs/
    - http://karpathy.github.io/2015/05/21/rnn-effectiveness/
    - http://www.wildml.com/2015/09/recurrent-neural-networks-tutorial-part-1-introduction-to-rnns/
    - http://www.wildml.com/2016/08/rnns-in-tensorflow-a-practical-guide-and-undocumented-features/
    - https://medium.com/@erikhallstrm/hello-world-rnn-83cd7105b767
    - https://skymind.ai/wiki/lstm
  
  - Blogpost that explains Attention
    - https://medium.com/syncedreview/a-brief-overview-of-attention-mechanism-13c578ba9129
    - http://www.wildml.com/2016/01/attention-and-memory-in-deep-learning-and-nlp/
    - https://skymind.ai/wiki/attention-mechanism-memory-network

  - Show me the code
    - https://iamtrask.github.io/2015/11/15/anyone-can-code-lstm/
    - http://www.jessicayung.com/lstms-for-time-series-in-pytorch/
    - 


  - Show me the math
    - https://www.coursera.org/lecture/nlp-sequence-models/why-sequence-models-0h7gT
    - http://arunmallya.github.io/writeups/nn/lstm/index.html#/ (move forward the page by clicking the arrow on bottom right)
    - https://www.cs.toronto.edu/~tingwuwang/rnn_tutorial.pdf
    - https://brilliant.org/wiki/recurrent-neural-network/
    - http://www.cs.bham.ac.uk/~jxb/INC/l12.pdf
    - https://www.kth.se/polopoly_fs/1.801971!/deep%20learning.pdf
    - https://arxiv.org/pdf/1803.06396.pdf
    - Independent RNN https://arxiv.org/abs/1803.04831 (Not really for beginners but this is like the AlexNet of RNNs)
    - RNN Paper: https://www.mitpressjournals.org/doi/abs/10.1162/neco.1997.9.8.1735 
    - LSTM Paper: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.676.4320&rep=rep1&type=pdf 
    - GRU Paper: https://arxiv.org/pdf/1502.02367v4.pdf
    - Alex Grave's Thesis: http://www.cs.toronto.edu/~graves/phd.pdf

----


### 3.3: **Self-Attention Nets** (aka Transformer)

  - Blogpost that explains Self-Attention Nets
    - http://jalammar.github.io/illustrated-transformer/
    - https://ai.googleblog.com/2017/08/transformer-novel-neural-network.htm
    - https://ai.googleblog.com/2018/11/open-sourcing-bert-state-of-art-pre.html
    - https://mchromiak.github.io/articles/2017/Sep/12/Transformer-Attentionis-all-you-need/
    - https://lilianweng.github.io/lil-log/2018/06/24/attention-attention.html (Different attention)


  - Show me the code
    - http://nlp.seas.harvard.edu/2018/04/03/attention.html
    - https://medium.com/@kolloldas/building-the-mighty-transformer-for-sequence-tagging-in-pytorch-part-i-a1815655cd8 

----


### 3.4: Natural Language Processing (*for real*) 

Natural Language Processing evolves really fast and as a field that mostly adopts/applies the "hottest" trend from mainstream machine/deep learning, every ~2-3 years the underlying state-of-art architecture for NLP changes (quite drastically). <!-- This is how fast we "throw away" things in NLP, e.g. https://towardsdatascience.com/the-fall-of-rnn-lstm-2d1594c74ce0 -->

The only way to keep up is not to chase the trends. Know that the lastest/hottest algorithm or pre-trained models exists, understand how they work and find ways to incorporate them into whichever project/method you're using/researching on. 

There's really no point in chasing any method (in NLP or any other sub-fields of computing) because 

 - if you're in the industry, what usually happens is that you try every possible method until you find  that fits your needs
 - if you're in academia, chasing state-of-art is going to drain you out and make your work mediorce/common, focus on the story and why things work more than how to make model X work on task Y.
   
In 2018, here's some recent trends: https://arxiv.org/pdf/1708.02709.pdf

Best way to keep up with NLP is to look at proceedings from these conferences (there's a lot but here's a few curated ones):
 - Association of Computational Lingusitics (ACL) and related conferences: https://aclanthology.coli.uni-saarland.de/
 - Text Analysis Conference (TAC): http://tac.nist.gov/publications/index.html
   - *Due to a lapse in government funding, this and almost all NIST-affiliated websites will be unavailable until further notice.* -_-||| 
 - Interspeech proceedings on https://www.isca-speech.org/iscaweb/index.php/online-archive 
 - Text, Speech and Dialogue conferences: https://link.springer.com/conference/tsd
 - SIGIR conferences: http://sigir.org/conferences/sponsored-conferences/ 
 - AAAI conferences: http://www.aaai.org/Conferences/conferences.php 
 - WWW conferences: http://www.iw3c2.org/
 
 

