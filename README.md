# AI&DL Knowledge Base (AIDL_KB)

This knowledge base is a curated list that is related to [the Facebook Group about Artificial Intelligence (AI) and Deep Learning (DL)](https://www.facebook.com/groups/DeepNetGroup/), in the abbreviated form AI&DL or AIDL.

The goals of AIDL_KB are,

* to serve as an alternative FAQ of [AIDL Facebook Community](https://www.facebook.com/groups/DeepNetGroup/) 's [pinned post](https://www.facebook.com/groups/DeepNetGroup/permalink/385843868475168/).  We also hope that this FAQ is updatable over time.  You can also think of it as a more complex version of **Frequently Asked Questions** (FAQ).
* provide a Wikipedia style of knowledge base for all AIDL members and public.

Other contents published by AIDL staffs.

* [AIDL Weekly Newsletter](http://aidl.io/)
* [AIDL Office Hour](https://www.youtube.com/channel/UC3YM5TEbSqIpFGH85d6gjKg) Youtube channel

## [Group Etiquette](FB.md)

## Frequently Asked Questions

### [How To Learn & Basics](BAS.md)

### Where To Learn

#### [Prerequisites](KB/PRE.md)

#### [Machine Learning (ML)](KB/ML.md)

#### [Deep Learning (DL)](KB/DL.md)

#### [Computer Vision (CV)](KB/CV.md)

#### [Natural Language Processing (NLP)](KB/NLP.md)

#### [Speech (ASR)](KB/ASR.md)

#### [Scientific Papers](KB/SCI.md)

#### [Public Datasets](KB/DAT.md)

#### Comparing Resources
How do you compare different resources on machine learning and deep learning? As mentioned before, there's an [Arthur Chan's article](http://thegrandjanitor.com/2016/08/15/learning-deep-learning-my-top-five-resource/) that's comparing different resources and their prerequisites. YerevaNN Lab has made [A guide to Deep Learning](http://yerevann.com/a-guide-to-deep-learning/) that is very handy for learning because all concepts are ranked by its difficulty. There also exists [A16Z AI playbook](http://aiplaybook.a16z.com/docs/reference/links), a list that completes the lists before, placing more focus on AI. [Reddit's Machine Learning FAQ](https://www.reddit.com/r/MachineLearning/wiki/index) has another list of great resources.

---

### How do I

#### Build a Chatbot

First of all, despite what people tell you, a machine doesn't really know how to respond like a human yet. It is a difficult problem. We can only tell you some approaches to go forward.

The first approach is to write a bunch of ifs, and then each of them gives users some answers. This result in programmer crafting a giant state machine-like structure of the program. There are many abstraction frameworks which helps you to create this kind of program much faster, you can try AIML for example. AIDL seldom put the focus on this kind of method, because it is mostly programming/lookup. And there is not many machine learning about it.

The second approach is to gather a bunch of question/answer pairs, then try to train a machine to learn it. You can use something like a neural network machine translation (NNMT) method or any translation models you like to train such a model. But then how do you come up with a good and relevant answer is tough. So that's why it is still a research topic.

You can think the second approach could be extended to many other use cases of DL, e.g. you can stuff a reading comprehension program and later it can answer the question. But then notice that you are still not solving the question of how to give natural and relevant dialogue.

#### Use Technique X with Language Y?
It seems obvious, yet some of the questions that can easily be solved by Google are still being asked. No matter how unique problem are you solving, there's always a great possibility someone was trying to solve it before you and that somewhere out there could already be multiple source codes concerning machine learning technique in your selected programming language. It's always good to try to search Github also.

#### Explain Concept X, List 3 Properties of Concept Y
Try to Google it also. We are sorry, but we can't do your homework for you. And of course, if you've spent some time already googling the internets through, try to ask the question as thoroughly, yet simply, as you can. Add more context if needed. And of course, if you couldn't Google the term, it's fair to ask questions, we won't bite you.

#### Find an Idea for My AI Project, FYP, Thesis and Competition
Firstly, don't be lazy. Coming up with an idea is part of the training if you decide to do a project, FYP, or write a thesis, or join a competition. In fact, if you decide to join an AI competition, it will be cheating if we are the ones who come up with the idea.

But it's legit to ask *how you can come up with ideas*. Usually, there are two ways:

1. Go to check out other people's idea, then twist it.
2. Go to solve a problem that you feel about. e.g. a lot of science project winners won because their loved ones have diseases. And a deep learning-based approach helps the process to diagnose the problem.

If you are out of ideas, then consider few things:

1. Ask smarter people what inspire them to come up with an idea.
2. Read a lot.
3. Don't work on a technical problem for a while and do some artsy stuff.

All three methods can give you a lot of inspirations.
