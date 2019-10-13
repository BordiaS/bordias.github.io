---
layout: page
<!---
title: About me
-->
---

<h1 align="center">Shikha Bordia</h1>

### Professional Background
I am a NLP Research Engineer at Verisk Analytics. Previously, I completed Master's in Computer Science from [New York University’s](http://www.nyu.edu/) [Courant Institute of Mathmatical Sciences](https://cs.nyu.edu/home/index.html). I was advised by Prof. Samuel R.Bowman. I was also part of [ML^2 Group](https://wp.nyu.edu/ml2/) at [CILVR Lab](https://wp.nyu.edu/cilvr/).  Broadly, my research interests are machine learning and natural language processing. 

### Publications/Projects
#### Investigating BERT’s Knowledge of Language:Five Analysis Methods with NPIs [[paper](https://arxiv.org/pdf/1909.02597.pdf)]
Though state-of-the-art sentence representation models can perform tasks requiring significant knowledge of grammar, it is an open question how best to evaluate their grammatical knowledge. We explore five experimental methods inspired by prior work evaluating pretrained sentence representation models. We use a single linguistic phenomenon, negative polarity item (NPI) licensing in English, as a case study for our experiments. NPIs like any are grammatical only if they appear in a licensing environment like negation (Sue doesn’t have any cats vs. *Sue has any cats). This phenomenon is challenging because of
the variety of NPI licensing environments that exist. We introduce an artificially generated dataset that manipulates key features of NPI licensing for the experiments. We find that BERT has significant knowledge of these features, but its success varies widely across different experimental methods. We conclude that a variety of methods is necessary to reveal all relevant aspects of a model’s grammatical knowledge in a given domain.

#### Identifying and Reducing Gender Bias in Word-Level Language Models [[paper](https://aclweb.org/anthology/papers/N/N19/N19-3002/)][[slides](https://bordias.github.io/gender_bias_slides.pdf)][[poster](https://bordias.github.io/poster.pdf)]
Many corpora exhibit problematic bias, which can  get propagated  or  amplified  in  the  models trained on such data. In this study we (i) propose a gender bias score; (ii) measure bias in a text corpus and the text generated from an embedding encoder based recurrent  neural  network language model trained on the text corpus; (iii) propose a regularization loss term for the language model that minimizes the projection of encoder trained embeddings onto an embedding subspace that encodes gender; (iv) finally, evaluate efficacy of our proposed method on reducing gender bias. This regularization method is found to be effective in reducing gender bias upto  an  optimal weight assigned to the loss term, beyond  which the model becomes unstable as the perplexity gets compromised. This study is replicated on three training corpora--Penn Treebank,  WikiText-2, and CNN/DailyMail--resulting in similar conclusions.

#### On Measuring Social Biases in Sentence Encoders[[paper](https://aclweb.org/anthology/papers/N/N19/N19-1063/)]
The Word Embedding Association Test shows that GloVe and word2vec word embeddings exhibit human-like implicit biases based on gender, race, and other social constructs. Meanwhile, research on learning reusable text representations has begun to explore sentence-level texts, with some sentence encoders seeing enthusiastic adoption. Accordingly, we extend the Word Embedding Association Test to measure bias in sentence encoders. We then test several sentence encoders, including state-of-the-art methods such as ELMo and BERT, for the social biases studied in prior work as well as two important biases that are difficult or impossible to test at the word level. Overall, we find that the encoders are sensitive to different forms of the tests, suggesting that they do not represent social bias analogously to word embeddings. We conclude by proposing directions for future work on quantifying bias in sentence encoders.

#### Contributed to [jiant](https://github.com/nyu-mll/jiant)
jiant is a work-in-progress software toolkit for natural language processing research, designed to facilitate work on multitask learning and transfer learning for sentence understanding tasks.


#### Improving pre-training and decoding in Machine Translation
There have been lot of recent advances in Machine Translation that have focused on network architectures, attention mechanisms and sequence-level training. Most of the approaches emphasize on modelling the languages better using attention. Here we explore three methods that rely on augmenting data using a pseudo-parallel corpus, improving the decoding strategy and pre-training the encoders and evaluate their effect on the machine translation task.


#### Statistical Machine Translation
Implemented a word-based statistical translation model (IBM Model) that extracts phrases using word alignment and performs parameter estimation for partially observed data using expectation maximization.

#### Text Classifier
Implemented maximum entropy classifier character model and feature extractor code for word classification. Further improved the model by implementing a one layer Perceptron.

#### Hidden Markov Model for part of speech tagger
Implemented a Hidden Markov model tagger using forward-backward algorithm and Viterbi decoder for unlabeled text data.

#### Nowcasted Gross Domestic Product
Implemented Stochastic modeling techniques for modeling structured products and the underlying economic variables were now-casted using Autoregressive Integrated Moving Average (ARIMA) model.

#### Operating System - Process Scheduler and Virtual Memory Manager
Process Scheduler: Implemented scheduling policies  (First In First Out, Last In Last Out, Shortest Job First, RoundRobin and PriorityScheduler) on processes executing on a system using Discrete Event Simulation}
Virtual Memory Manager: Implemented the core features of a virtual memory manager serving multiple processes and under memory constraints.


