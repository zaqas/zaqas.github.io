---

title: "Invalidity of AI"
layout: post
date: 2023-07-28
image: /assets/image/markdown.jpg
headerImage: false
tag:

- AI
- Intelligence
- Reproducibility
  
category: blog
author: Reza
---

Over the years, I have developed an aversion to AI. Nowadays, whenever I see a company's webpage, and they mention using neural networks as an advantage of their service, I simply close the page and move on.

I did not always used to be like this. I remember, at some point, having an interest in machine learning and AI, and I thought it was an interesting topic to delve into. Not only that, but I started reading the classical book on AI by Norvig in my undergraduate years. In my graduate program, I had the opportunity to study machine learning and AI. Initially, it was very interesting. We would discuss not only technical details but also touch upon philosophical concepts about what learning is and how the definition of intelligence has morphed over the years. In ancient times, memory was considered an invaluable skill, and one's capacity for storing information was correlated with his level of intelligence [0]. There were various methods of storing large quantities of data that would allow information to be passed down from generation to generation. Some methods have been lost due to time, but others have remained. The most well-known technique is the memory palace. Moreover, we have evidence of mnemonic devices found in tribes used to transmit knowledge to chiefs [1].

### Lack of definition

In cybersecurity, there are different metrics for measuring security. After all, how could you say something is secure without having taken any measures in the first place? In the field of artificial intelligence, the ultimate goal is to reach AGI. This term stands for artificial general intelligence, meaning that the machine would be able to perform when put in different contexts and to transfer its knowledge to different domains. Current models cannot be used in a different context. If a model is trained to play a game and learns the game well, If we change the game by making few modifications, the model would simply collapse. AI experts cannot even agree on what intelligence is, yet they want to create an intelligent machine. How do you create something you wish for without knowing what exactly that thing is? Alan Turing proposed a test where, if a human is tricked by a machine into thinking that interaction is with another human and not a machine, this would be considered an intelligent machine [2].

Fairly simply, chatbots could fake such a scenario, but are they really intelligent? Some may argue that faking intelligence requires intelligence. Maybe, but the machines are not even faking them intentionally.


### Simply a selling point

In today's climate, AI is being used mostly as a selling point. It is not adopted because it is the most efficient solution (in fact, it is very inefficient), but because it is considered a trend. People simply jump to neural networks without considering their actual needs. They do not even try to see whether a problem could be solved using different means.

As I already mentioned, neural networks are inefficient, and this is due to multiple reasons, in my opinion. When faced with choosing the hyperparameters, most practitioners tune the parameters either by following their instinct [3] or using computationally expensive approaches like grid search. Grid search is simply a brute-force approach to trying all possible parameters to observe what gives the best performance. The computational cost is immense, and the carbon footprint of deep learning is unacceptable [4]. I remember having a discussion and bringing up this point, and he was using the no-free lunch theorem as an argument. This has nothing to do with the NFL; it is simply an inelegant approach.

AI in the research community
---
It is interesting to me that AI is being used in the research community besides the industry because the staple of science is reproducibility, and numerous papers cannot be reproduced [5, 6, 7]. When faced with the question of why the model performs in this manner, they say it is due to a lack of explainability, which is an inherent feature. Models cannot be explained, which makes AI a strange approach to be used in the research community, as they are not able to explain why the models work or not. Moreover, tuning the parameters is more aligned with alchemy since different architectures are tried until the performance is considered acceptable. Nowadays, we consider alchemy a pseudo-science, but somehow, when it comes to AI, we turn a blind eye.

### Privacy and ethics


Besides the computational cost, there is a cost in terms of privacy. In Europe, due to GDPR, at least "on the surface," it seems that citizens are protected and have rights to protect their data. But in developing countries, many would simply trade intimate and personal information micro jobs websites. Moreover, for annotation, companies rely on those individuals to help them. The fee received by each individual for their work or data is unacceptable. Besides technical solutions, we need regulations to limit what types of data can be processed.


### Final remark

We used to think about the problems we faced and find innovative and creative solutions. For instance, type inference based on the Hindley-Milner type system identifies types without using any form of AI. I cannot imagine an individual today reaching the same endpoint without relying on AI at some point in the production process. We have become too dependent on machines, and we still have not defined safety regulations. Imagine the following scenario: We give the objective of reducing harmful agents to the environment in terms of climate change to a machine based on a few factors we define. The machines might take actions without considering the consequences of their actions. They might decide to cut the electricity in a region, putting lives at risk. The risks are immense, and we have not thought this through.


Overall, I think AI is just a temporary fascination, and after the initial excitement is over, we see it for what it actually is [8]. Reflect on all the "world-changing technologies" that were supposed to revolutionize our lives but faded after a while (e.g., VR, AI glasses, etc.). In the research community, more courses are needed to teach about the history of computing and the rich history of the field. For the time being, we have to focus on finding alternative solutions that are less computationally expensive and more elegant and talk openly about the issues of AI, as it is a multi-faceted problem and we need different groups of individuals when it comes to solving it.

---
[0] https://www.cambridge.org/core/books/abs/book-of-memory/introduction/B185E76088F1B134F33C4133B4D17E95
[1] https://aeon.co/ideas/this-ancient-mnemonic-technique-builds-a-palace-of-memory
[2] https://en.wikipedia.org/wiki/Turing_test
[3] https://www.science.org/content/article/ai-researchers-allege-machine-learning-alchemy
[4] https://www.technologyreview.com/2019/06/06/239031/training-a-single-ai-model-can-emit-as-much-carbon-as-five-cars-in-their-lifetimes/
[5] https://petewarden.com/2018/03/19/the-machine-learning-reproducibility-crisis/
[6] https://www.wired.com/story/machine-learning-reproducibility-crisis/
[7] https://www.wired.com/story/artificial-intelligence-confronts-reproducibility-crisis/
[8] https://news.ycombinator.com/item?id=34848353
