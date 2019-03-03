---
layout: page
<!---
title: About me
-->
---

<h1 align="center">Shikha Bordia</h1>

### Professional Background


I’m a second-year Master student at [New York University’s](http://www.nyu.edu/) [Courant Institute of Mathmatical Sciences](https://cs.nyu.edu/home/index.html). I am a part of [ML^2 Group](https://wp.nyu.edu/ml2/) at [CILVR Lab](https://wp.nyu.edu/cilvr/). My research interests are machine learning and natural language processing. 

I graduated from [Indian Institute of Technology Kharagpur](http://www.iitkgp.ac.in) in 2011. I started my career working in the Global Analytics Group at Deutsche Bank modeling Structured Finance products.  Over the years, I have worked across multiple industries like retail, eCommerce, banking and telecom. I have provided consulting to multiple clients (Fortune 100) for business intelligence and predictive analytics projects. I am passionate about building data-driven products and scalable frameworks.

You can either connect with me on [Linkedin](https://www.linkedin.com/in/shikhabordia/) or drop me an email on bordiashikha06@gmail.com. Happier to grab a coffee in-person and exchange notes about the universe! 

### Publications/Projects
#### Identifying and Reducing Gender Bias in Word-Level Language Models
Many corpora exhibit problematic bias, which can  get propagated  or  amplified  in  the  models trained on such data. In this study we (i) propose a gender bias score; (ii) measure bias in a text corpus and the text generated from an embedding encoder based recurrent  neural  network language model trained on the text corpus; (iii) propose a regularization loss term for the language model that minimizes the projection of encoder trained embeddings onto an embedding subspace that encodes gender; (iv) finally, evaluate efficacy of our proposed method on reducing gender bias. This regularization method is found to be effective in reducing gender bias upto  an  optimal weight assigned to the loss term, beyond  which the model becomes unstable as the perplexity gets compromised. This study is replicated on three training corpora--Penn Treebank,  WikiText-2, and CNN/DailyMail--resulting in similar conclusions.

#### On Measuring Social Biases in Sentence Encoders
The Word Embedding Association Test shows that GloVe and word2vec word embeddings exhibit human-like implicit biases based on gender, race, and other social constructs. Meanwhile, research on learning reusable text representations has begun to explore sentence-level texts, with some sentence encoders seeing enthusiastic adoption. Accordingly, we extend the Word Embedding Association Test to measure bias in sentence encoders. We then test several sentence encoders, including state-of-the-art methods such as ELMo and BERT, for the social biases studied in prior work as well as two important biases that are difficult or impossible to test at the word level. Overall, we find that the encoders are sensitive to different forms of the tests, suggesting that they do not represent social bias analogously to word embeddings. We conclude by proposing directions for future work on quantifying bias in sentence encoders.

#### Improving pre-training and decoding in Machine Translation
There have been lot of recent advances in Machine Translation that have focused on network architectures, attention mechanisms and sequence-level training. Most of the approaches emphasize on modelling the languages better using attention. Here we explore three methods that rely on augmenting data using a pseudo-parallel corpus, improving the decoding strategy and pre-training the encoders and evaluate their effect on the machine translation task.


#### Statistical Machine Translation
Implemented a word-based statistical translation model (IBM Model) that extracts phrases using word alignment and performs parameter estimation for partially observed data using expectation maximization.

#### Text Clssifier
Implemented maximum entropy classifier character model and feature extractor code for word classification. Further improved the model by implementing a one layer Perceptron.

#### Hidden Markov Model for part of speech tagger
Implemented a Hidden Markov model tagger using forward-backward algorithm and Viterbi decoder for unlabeled text data.

#### Nowcasted Gross Domestic Product
Implemented Stochastic modeling techniques for modeling structured products and the underlying economic variables were now-casted using Autoregressive Integrated Moving Average (ARIMA) model.

#### Operating System - Process Scheduler and Virtual Memory Manager
Process Scheduler: Implemented scheduling policies  (First In First Out, Last In Last Out, Shortest Job First, RoundRobin and PriorityScheduler) on processes executing on a system using Discrete Event Simulation}
Virtual Memory Manager: Implemented the core features of a virtual memory manager serving multiple processes and under memory constraints
