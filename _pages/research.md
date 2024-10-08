---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research falls into three areas: [Collective behaviour and intelligence](#collective-behaviour-and-intelligence), [Spatial models of ecology and epidemiology](#spatial-models-in-ecology-and-epidemiology), and [Philosophical aspects of mathematical modelling and complex systems](#philosophical-aspects-of-mathematical-modelling).


## Collective behaviour and intelligence

### Mathematical models of minimal cognition

Building mathematical models of brains is difficult because of the sheer complexity of the problem. One potential approach is to start by identifying models of basal cognition, which give an abstract representation of a range organisms without central nervous systems, including fungi, slime moulds and bacteria. We propose one such model, demonstrating how a combination of oscillatory and current-based reinforcement processes can be used to couple resources in an efficient manner. We identify connections between our model and basal cognition in biological systems and slime moulds, in particular, showing how oscillatory and problem-solving properties of these systems are captured by our model. 

This is joint work with [Yu Tian]( https://ytian.netlify.app/){: .btn--research}{:target="_blank"} and [David Sumpter](https://www.katalog.uu.se/profile/?id=N7-525){: .btn--research}{:target="_blank"}.

**Linnéa Gyllingberg**, Yu Tian, David J.T. Sumpter,
**A minimal model of cognition based on oscillatory and reinforcement processes**
*ArXiv preprint*,
[link](https://arxiv.org/abs/2402.02520){: .btn--research}{:target="_blank"}
![](/images/slime_network.png)


### Using neuronal models to capture burst and glide motion and leadership in fish

While mathematical models, in particular self-propelled particle (SPP) models, capture many of the observed properties of large fish schools, they do not always capture the interactions of smaller shoals. Nor do these models tend to account for the observation that, when swimming alone or in smaller groups, many species of fish use intermittent locomotion, often referred to as burst and coast or burst and glide. We propose a model of social burst and glide motion by combining a well-studied model of neuronal dynamics, the FitzHugh-Nagumo model, with a model of fish motion. 
This is joint work with [Alex Szorkovsky](https://www.uio.no/ritmo/english/people/postdoctoral-fellows/alexansz/){: .btn--research}{:target="_blank"}, and  [David Sumpter](https://www.katalog.uu.se/profile/?id=N7-525){: .btn--research}{:target="_blank"}.


**Linnéa Gyllingberg**, Alex Szorkovszky, David J.T. Sumpter,
**Using neuronal models to capture burst and glide motion and leadership in fish**,
*Journal of the Royal Society Interface*,
2023.\
[link](https://royalsocietypublishing.org/doi/10.1098/rsif.2023.0212){: .btn--research}{:target="_blank"}




[comment]: # (We begin by showing that the model can capture the motion of a single fish swimming down a channel. By then extending to a two fish model, where visual stimuli of the position of the other fish affects the internal burst or glide state of the fish, we find that our model captures a rich set of swimming dynamics found in many species of fish. These include: leader-follower behaviour; periodic changes in leadership; apparently random i.e. chaotic leadership change; and pendulum-like tit-for-tat turn taking. Unlike SPP models, which assume that fish move at a constant speed, the model produces realistic motion of individual fish. Moreover, unlike previous studies where a random component is used for leadership switching to occur, we show that leadership switching, both periodic and chaotic, can be the result of a deterministic interaction.  We give several empirically testable predictions on how fish interact and discuss our results in light of recently established correlations between fish locomotion and brain activity.)

![](/images/fishdynamics.png)


---

## Spatial models in ecology and epidemiology 
Spatial structure is critically important to understand and model many aspects of ecology as well as epidemiology. There are many ways to model spatial structure; individual-based models, coupled map lattices, network models and partial differential equations are a few of them. In the following two projects, I use different types of spatial models to capture and understand the Covid-19 spread in Uppsala County, as well as the role of space for intraspecific interactions.

[comment]: # (In the following research projects I use spatial mathematical models to gain understanding)

### Modelling transmission of the of Covid-19 in Uppsala County - a metapopulation network approach
The duration and spatial proximity of social interactions between humans may play a critical role in the propagation of airborne diseases. Digital contact-tracing using GPS-based mobile apps can only generate macro-level data bound by legal restriction. In contrast, interview-based (clinical) contact-tracing can provide extensive anonymized data from people who test positive for COVID-19 allowing us to focus on social interactions that have actually contributed to transmission. Such contact-tracing methods have successfully been used during the COVID-19 control efforts, but their full potential has yet to be reached. The spatio-temporal data collected by contact-tracing combined with COVID-19 transmission indicators could help us identify transmission hot spots and paths. In this project, our aim is to build a mathematical model in order to model the transmission of SARS-CoV-2 in Uppsala County. 
This is joint work with [Georgios Varotsis](https://www.katalog.uu.se/empinfo/?id=N20-1960){: .btn--research}, [Tove Fall](http://tovefall.se/){: .btn--research}, and [Mats Martinell](https://www.katalog.uu.se/empinfo/?id=N9-642){: .btn--research}.


### Spatial models in ecology - analytical approximations of individual based models of ecology

How does space affect population dynamics of a model with intra-specific interaction? In the paper *Finding analytical approximations for discrete, stochastic, individual-based models of ecology* we study an individual based model of intra-specific interactions, inspired by the life cycle of many insects and microorganisms. The model is simple to state, yet it gives rise to complex spatial patterns as well as population dynamics. We show that a mean-field approach is not enough to capture the complex spatial dynamics of ecological competition. Instead, we develop two approximations to capture this complexity: one based on coupling on a larger scale and one based on an approximation on a very local scale. Our findings shed light on a common discrepancy between theoretical and empirical ecology: theoretical models, as suggested by May et al. (1974) often show chaotic behaviour, but in real ecological time series chaos is infrequent. This is joint work with [David Sumpter](https://www.katalog.uu.se/profile/?id=N7-525){: .btn--research}{:target="_blank"} and [Åke Brännström](https://www.umu.se/en/staff/ake-brannstrom/){: .btn--research}{:target="_blank"}.

![](/images/approx_image.png)

**Linnéa Gyllingberg**, David J.T. Sumpter, Åke Brännström,
**Finding analytical approximations for discrete, stochastic, individual-based models of ecology**,
*Mathematical Biosciences*,
2023.\
[link](https://www.sciencedirect.com/science/article/pii/S0025556423001244){: .btn--research}{:target="_blank"}


---

## Philosophical aspects of mathematical modelling
Biological systems are complex systems. This statement is so often made, that it can obscure just how radical the consequences of complexity are for the life sciences. In the paper *The Lost Art of Matheamatical Modelling* we provide a critique of mathematical biology in light of rapid developments in modern machine learning. We argue that out of the three modelling activities --- (1) formulating models; (2) analysing models; and (3) fitting or comparing models to data --- inherent to mathematical biology, researchers currently focus too much on activity (2) at the cost of (1). This trend, we propose, can be reversed by realising that any given biological phenomena can be modelled in an infinite number of different ways, through the adoption of an open/pluralistic approach. We explain the open approach using fish locomotion as a case study and illustrate some of the pitfalls --- universalism, creating models of models, etc. --- that hinder mathematical biology. We then ask how we might rediscover a lost art: that of creative mathematical modelling.  This is joint work with  [Abeba Birhane](https://abebabirhane.com/){: .btn--research}{:target="_blank"} and [David Sumpter](https://www.katalog.uu.se/profile/?id=N7-525){: .btn--research}{:target="_blank"}.

 **Linnéa Gyllingberg**, Abeba Birhane, David J.T. Sumpter,
**The Lost Art of Mathematical Modelling**,
*Mathematical Biosciences*,
2023.\
[link](https://doi.org/10.1016/j.mbs.2023.109033){: .btn--research}{:target="_blank"}
