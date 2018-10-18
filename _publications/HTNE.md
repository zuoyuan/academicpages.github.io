---
title: "Embedding Temporal Network via Neighborhood Formation"
collection: publications
permalink: /publication/HTNE
excerpt: 'This paper is about embedding temporal network.'
date: 2018-08-01
venue: 'SIGKDD'
paperurl: 'http://zuoyuan.github.io/files/htne_kdd18.pdf'
citation: 'Yuan Zuo, Guannan Liu, Hao Lin, Jia Guo, Xiaoqian Hu, Junjie Wu. 2018. Embedding Temporal Network via Neighborhood Formation. In Proceedings of KDD’2018.'
---
Given the rich real-life applications of network mining as well as the surge of representation learning in recent years, network embedding has become the focal point of increasing research in- terests in both academic and industrial domains. Nevertheless, the complete temporal formation process of networks characterized by sequential interactive events between nodes has yet seldom been modeled in the existing studies, which calls for further research on the so-called temporal network embedding problem. In light of this, in this paper, we introduce the concept of neighborhood formation sequence to describe the evolution of a node, where temporal exci- tation effects exist between neighbors in the sequence, and thus we propose a Hawkes process based Temporal Network Embedding (HTNE) method. HTNE well integrates the Hawkes process into network embedding so as to capture the influence of historical neighbors on the current neighbors. In particular, the interactions of low-dimensional vectors are fed into the Hawkes process as base rate and temporal influence, respectively. In addition, attention mechanism is also integrated into HTNE to better determine the influence of historical neighbors on current neighbors of a node. Ex- periments on three large-scale real-life networks demonstrate that the embeddings learned from the proposed HTNE model achieve better performance than state-of-the-art methods in various tasks including node classification, link prediction, and embedding visu- alization. In particular, temporal recommendation based on arrival rate inferred from node embeddings shows excellent predictive power of the proposed model.

[Download paper here](http://zuoyuan.github.io/files/htne_kdd18.pdf)

[Download code here](http://zuoyuan.github.io/files/htne.zip)

Recommended citation: Yuan Zuo, Guannan Liu, Hao Lin, Jia Guo, Xiaoqian Hu, Junjie Wu. 2018. Embedding Temporal Network via Neighborhood Formation. In Proceedings of KDD’2018.