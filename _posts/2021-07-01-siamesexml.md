---
layout:     post
title:      SiameseXML
date:       2021-07-01 12:32:18
summary:    Abstract and some details for SiameseXML.
categories: Publications
thumbnail: jekyll
tags:
 - Extreme Classification
 - Publications
 - ICML
---


![SiameseXMLLogo](https://i.postimg.cc/XJNk1W47/image.png)

Joint work with [Kunal Dahiya](https://kunaldahiya.github.io){:target="_blank"}, Ananye Agarwal, Gururaj K, Jian Jiao, Amit Singh, [Summet Agarwal](https://web.iitd.ac.in/~sumeet/){:target="_blank"}, [Purushottam Kar](https://www.cse.iitk.ac.in/users/purushot/){:target="_blank"}, [Manik Varma](http://manikvarma.org/){:target="_blank"}
<br>
<br>
The task of deep extreme multi-label learning (XML) requires training deep architectures capable of tagging a data point with its most relevant subset of labels from an extremely large label set. Applications of XML include tasks such as ad and product recommendation that involve labels that are rarely seen during training but which nevertheless hold the key to recommendations that delight users. Effective utilization of label metadata and high quality predictions for rare labels at the scale of millions of labels are key challenges in contemporary XML research. To address these, this paper develops the SiameseXML method by proposing a novel probabilistic model suitable for extreme scales that naturally yields a Siamese architecture that offers generalization guarantees that can be entirely independent of the number of labels, melded with high-capacity extreme classifiers. SiameseXML could effortlessly scale to tasks with 100 million labels and in live A/B tests on a popular search engine it yielded significant gains in click-through-rates, coverage, revenue and other online metrics over state-of-the-art techniques currently in production. SiameseXML also offers predictions 3–12% more accurate than leading XML methods on public benchmark datasets. The generalization bounds are based on a novel uniform Maurey-type sparsification lemma which may be of independent interest.

You can watch our conference presentation video [here](https://recorder-v3.slideslive.com/#/share?share=40009&s=282397f6-c7c4-4eec-8e9f-b84ec5554428).

<!-- Please use this Bibtext in case you need to cite the work:
```bib
@InProceedings{Saini21,
	author       = "Saini, D. and Jain, A.~K. and Dave, K. and Jiao, J. and Singh, A. and Zhang, R. and Varma, M.",
	title        = "GalaXC: Graph neural networks with labelwise attention for extreme classification",
	booktitle    = "Proceedings of The ACM International World Wide Web Conference",
	month = "April",
	year = "2021",
	}
```

Please feel free to tinker with the [code](https://github.com/Extreme-classification/GalaXC){:target="_blank"}. -->