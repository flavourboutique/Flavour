---
layout: post
author: Michael Kir
title: "State of the Apple Watch"
date: 2024-06-17
---

## What is the state of the Apple Watch now and in the future?

I am very pleased with the official announcement of the watchOS 11. Because every single software update from here onwards is going to be more impactful to consumers than ever before. Apple knows exactly what they are doing when they roll out an update. From the keynote you might think that the watchOS 11 is barely an update. However in reality it is actually quite the opposite. Since the initial release of the Apple Watch, Apple has been working on core functionality of the watch and making it less reliant on the iPhone for its core functionality, not to mention setting it up and configuring it through the iPhone app. According to leaks and public documents, Apple once discussed bringing the Apple Watch app to Android. I am willing to bet they discussed bringing to other Apple devices as well. However the conclusion that they came to is that it is not worth while in the long run to maintain a distribution of this app on many platforms when eventually they aim to make the Apple Watch a fully independent product. 

No matter what new Apple Watch comes out they have to work with the current and previous supported generations of Apple Watches. This means choosing what features come and don’t come to each generation. It is really great that Apple cares so much for maintaining older generations, but does it hinder the potential of the current generation before a new one is released? Overall watchOS 11 is the strongest release of the software thus far. At the moment of writing this I read that Siri face has been discontinued, which hurts, because that is what I have been using since I got Apple Watch series 2 as a hand down during the pandemic to replace the awful Fitbit that I had. In short the experience I had with that watch got to me to wait and upgrade to the Apple Watch Series 7 Cellular. I was so blown away by the functionality I decided to try using it instead of my iPhone and it proved to be really fun. I will write more about this in another post as it would make this post too long.

The biggest factor at play is Hardware.
Especially from a software perspective a technology becomes only possible when we get innovations in the hardware. What happens when you have limitations in the hardware? You have to make decisions that look at the main objectives of the product and a decision has to answer a few questions notably:
- Will this compromise core features/functionality?
- Will this be useful to the user?
- How will this combine with other established features?

Let’s begin with Hardware. Apple Watch is limited in terms of hardware space that it can use due to its internal case space. Firstly, the biggest issue stems from the watch size, if you scale a products size, you will scale the internal size along side it. Secondly, the space taken up by the strap mechanism when you see that it is on both sides of the case. Until Apple puts double sided logic boards into production on the Apple Watch we will be constrained by the length and width of the internal space.

Currently Apple Watch lineup consists of 3 sizes which means it is hard to make one SiP (System in Package) for all of them that takes advantage of the internal space of the bigger watches.

### Why is the size of the SiP so important?
The bigger the SiP dye the more additional transistors you can fit on it. This allows you to add more cores on the CPU, GPU and the Neural engine. Additionally, you have more space for RAM and SSD, which means they can be bigger and store more things. Size of RAM is more important as it contributes to multitasking abilities and dictates what the data bottleneck is, in other terms how much data can be processed all at once.

### What do the extra cores / transistors allow SiP to do?
Currently Apple Watch has a two core CPU and a single core GPU, which means that it has a very limited number of parallel processes that can happen at once given its architecture of RISC as licensed by ARM, while being designed by Apple and produced by TSMC. The Apple Watch dye is based of a cut down iPhone SoC that they fit all the components as close together as possible to fit it into such a miniature internal space. Multitasking features come from having multiple cores to rely on. This is why Apple Watch currently has limited  multitasking features.  

### How will Apple solve this problem?
Apple when unveiling their new line up of Apple Watches in the September of 2024, will show that they have eliminated the smallest model size, while additionally reworking the strap attachment mechanism. This will allow it to cut down less on the iPhone SoC due to more available space, which will allow it to have more cores thereby being able to perform more operations all at once. This all contributes to more functionality in the software.

### Are there any alternatives?
They could make SiPs that are double sided but that would be too expensive for commercial production and will not yield the quantities result that are expected for the Apple Watch sales.