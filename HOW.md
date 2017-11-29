[← Back to overview](README.md)

# How to

## Build a Chatbot

First of all, despite what people tell you, a machine doesn't really know how to respond like a human yet. It is a difficult problem. We can only tell you some approaches to go forward.

The first approach is to write a bunch of ifs, and then each of them gives users some answers. This result in programmer crafting a giant state machine-like structure of the program. There are many abstraction frameworks which helps you to create this kind of program much faster, you can try AIML for example. AIDL seldom put the focus on this kind of method, because it is mostly programming/lookup. And there is not many machine learning about it.

The second approach is to gather a bunch of question/answer pairs, then try to train a machine to learn it. You can use something like a neural network machine translation (NNMT) method or any translation models you like to train such a model. But then how do you come up with a good and relevant answer is tough. So that's why it is still a research topic.

You can think the second approach could be extended to many other use cases of DL, e.g. you can stuff a reading comprehension program and later it can answer the question. But then notice that you are still not solving the question of how to give natural and relevant dialogue.

> [How To Develop a Chatbot From Scratch](https://chatbotsmagazine.com/how-to-develop-a-chatbot-from-scratch-62bed1adab8c)
