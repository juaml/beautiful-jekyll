---
layout: post
title: Bioactivity assessment of natural compounds
subtitle: machine learning models trained on target similarity between drugs
cover-img: /assets/img/autumn-g9bfc6b9a8_640.jpg
thumbnail-img: /assets/img/autumn-g9bfc6b9a8_640.jpg
share-img: /assets/img/autumn-g9bfc6b9a8_640.jpg
tags: [paper, supervised ml]
---

Can we predict if natural compounds can function as drugs?

The paper is published in [*PLoS Computational Biology*](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010029).


**Bioactivity assessment of natural compounds using machine learning models trained on target similarity between drugs**
**Abstract** Natural compounds constitute a rich resource of potential small molecule therapeutics. While experimental access to this resource is limited due to its vast diversity and difficulties in systematic purification, computational assessment of structural similarity with known therapeutic molecules offers a scalable approach. Here, we assessed functional similarity between natural compounds and approved drugs by combining multiple chemical similarity metrics and physicochemical properties using a machine-learning approach. We computed pairwise similarities between 1410 drugs for training classification models and used the drugs shared protein targets as class labels. The best performing models were random forest which gave an average area under the ROC of 0.9, Matthews correlation coefficient of 0.35, and F1 score of 0.33, suggesting that it captured the structure-activity relation well. The models were then used to predict protein targets of circa 11k natural compounds by comparing them with the drugs. This revealed therapeutic potential of several natural compounds, including those with support from previously published sources as well as those hitherto unexplored. We experimentally validated one of the predicted pair’s activities, viz., Cox-1 inhibition by 5-methoxysalicylic acid, a molecule commonly found in tea, herbs and spices. In contrast, another natural compound, 4-isopropylbenzoic acid, with the highest similarity score when considering most weighted similarity metric but not picked by our models, did not inhibit Cox-1. Our results demonstrate the utility of a machine-learning approach combining multiple chemical features for uncovering protein binding potential of natural compounds.
