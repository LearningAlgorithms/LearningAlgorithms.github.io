---
title: Brief introduction
date: 2020-11-05 12:42:00 +0100
categories: [Machine Learning,General]
tags: [introduction]     # TAG names should always be lowercase
image: /assets/img/img_posts/machine-learning/introduction/subsets_AI.png
comments: true
---

## What is Artificial Intelligence?

We can define **Artificial intelligence** (AI) as intelligence demonstrated by machines, contrasting with **natural intelligence** displayed by humans and animals, being intelligence described in a general form as the ability to discern information and use it to create knowledge that latter can be applied in similar situations. In this case, research in AI has been focused on learning, problem-solving, reasoning, perception, and use of language. 

Talking about more concrete tasks, since the 1940s computers have been able to perform a complex task such as playing chess or proving mathematical theorems, problems that when solved by a machine have lost the property of being problems only solvables using intelligence, and therefore a task that doesn't need AI, the [AI effect](https://en.wikipedia.org/wiki/AI_effect).

This era of research in AI began in 1935 when the mathematician [Alan Turing](https://en.wikipedia.org/wiki/Alan_Turing) proposed his general-purpose computer, the [Turing Machine](https://en.wikipedia.org/wiki/Turing_machine). In a [public lecture](https://www.vordenker.de/downloads/turing-vorlesung.pdf) in 1947 Turing said:

>What we want is a machine that can learn from experience. The possibility of letting the machine alter its own instructions provides the mechanism for this.
>
> -- <cite>[Alan Mathison Turing](https://en.wikipedia.org/wiki/Alan_Turing)</cite>

We could call this an early definition of **Machine Learning**. In a non-published paper in 1948 Turing also introduced an [idea](http://www.alanturing.net/turing_archive/pages/Reference%20Articles/connectionism/Turing's%20neural%20networks.html) to train a neural network of artificial neurons to perform a specific task, like in **Deep Learning**.

## What is Machine Learning?

The computer science discipline of **Machine Learning** (ML) is a subfield of **Artificial Intelligence**. ML objective is to construct algorithms that using a collection of examples of some phenomenon can improve their performance by itself.

Let's see some examples of how experts have defined ML as:

> Field of study that gives computers the ability to learn without being explicitly programmed.
>
> -- <cite>[Arthur L. Samuel](https://en.wikipedia.org/wiki/Arthur_Samuel)</cite>

Arthur Samuel popularized the term _Machine Learning_ in 1959, and his Checkers-playing program was one of the first successful self-learning algorithms.

> A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E.
>
> -- <cite>[Tom M. Mitchell](https://en.wikipedia.org/wiki/Tom_M._Mitchell)</cite>

Tom Mitchell is a former Chair of the Machine Learning Department at CMU. Mitchell is known for his contributions to the advancement of machine learning, artificial intelligence, and cognitive neuroscience.

In summary, Machine Learning algorithms learn by experience, in a similar way that natural organisms do.  

## What is Deep Learning?

**Deep Learning** is a subfield of ML, and its methods are based on [artificial neural networks](https://en.wikipedia.org/wiki/Artificial_neural_network), which are algorithms inspired by the structure and function of the neurons, trying to simulate a brain. The term Deep Learning was introduced to the ML community by [Rita Dechter](https://en.wikipedia.org/wiki/Rina_Dechter) in 1986.

> Deep Learning is constructing networks of parameterized functional modules & training them from examples using gradient-based optimization.
>
> -- <cite>[Yann LeCun](https://en.wikipedia.org/wiki/Yann_LeCun)</cite>

In the last decade algorithms based on Deep Learning have produced results comparable to, and in some cases surpassing, human expert performance. Fields as diverse as: 

- Computer vision:
    - [Posenet: Pose detection](https://github.com/tensorflow/tfjs-models/tree/master/posenet)
    - [YOLO: Real-Time Object Detection](https://pjreddie.com/darknet/yolo/)
    - [3D Model From 2D Images](https://ai.facebook.com/blog/powered-by-ai-turning-any-2d-photo-into-3d-using-convolutional-neural-nets/)
    - [Computer Vision in Healthcare Applications](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5857319/)
    - [Self-driving cars](https://www.tesla.com/autopilot)

- Speech recognition:
    - [Google’s Google Assistant](https://assistant.google.com/intl/es_es/)
    - [Speech recognition in healthcare](https://codeit.us/blog/speech-recognition-in-healthcare)
    - [Speech recognition with Amazon's Alexa and the internet of things](https://docs.aws.amazon.com/es_es/iot/latest/developerguide/avs-integration-aws-iot.html)

- Natural language processing:
    - [Spam detector in emails](https://www.spamtitan.com/spam-email-filter/)
    - [Search results with Google](https://blog.google/products/search/search-language-understanding-bert/)
    - [DeepL Language translator](https://www.deepl.com/home)
    - [GPT-3 Text generation](https://openai.com/blog/openai-api/)

- Games:
    - [AlphaZero in Go, Chess, and Shogi](https://en.wikipedia.org/wiki/AlphaZero)
    - [AlphaStar in StarCraft II](https://deepmind.com/blog/article/AlphaStar-Grandmaster-level-in-StarCraft-II-using-multi-agent-reinforcement-learning)

There are many examples of successful use of DL in today's world, and these models will only get better with more [data](https://www.forbes.com/sites/bernardmarr/2018/05/21/how-much-data-do-we-create-every-day-the-mind-blowing-stats-everyone-should-read/?sh=2440c20060ba).

## How is performed the "Learning"?

We can classify the type of learning used by the algorithm into four categories.

### Supervised Learning

In **supervised learning**, the dataset, the examples of the problem that we already have, are labeled and with them, our algorithms are going to infer a function, a **model** that would take inputs of the form of our examples and deduce an output. For example, a supervised learning algorithm could take as an input the square meters of a house and generate an output of how much it should cost.

### Unsupervised Learning

In **unsupervised learning**, our algorithm is going to try to find undetected patterns in the dataset, a dataset that doesn't contain any label.

### Semi-supervised Learning

**Semi-supervised** algorithms in machine-learning combine usually a small number of labeled examples and a much bigger quantity of unlabeled, the algorithm is going to use those unlabeled examples to produce a better model by being less biased. 


### Reinforcement Learning

In **reinforced learning**, our algorithm performs inside an environment in which is capable of perceiving its state and take actions, in consequence, those actions are going to report a benefit or a detriment, and this agent has to *learn* how to maximize its reward.

And now, a little joke from [XKCD](https://xkcd.com/1838/)

![XKCD Machine Learning](/assets/img/img_posts/machine-learning/introduction/xkcd-machine-learning.png)
*XKCD Machine Learning*
