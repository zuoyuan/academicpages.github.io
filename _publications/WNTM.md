---
title: "Word Network Topic Model: A Simple but General Solution for Short and Imbalanced Texts"
collection: publications
permalink: /publication/WNTM
excerpt: 'This paper is about a new topic model for short and imbalanced texts.'
date: 2016-08-01
venue: 'Knowledge and Information System (KAIS)'
paperurl: 'http://zuoyuan.github.io/files/wntm_kais.pdf'
citation: 'Yuan Zuo, Jichang Zhao and Ke Xu. Word Network Topic Model: a Simple but General Solution for Short and Imbalanced Texts. KAIS, 2016.'
---
The short text has been the prevalent format for information of Internet, especially with the development of online social media. Although sophisticated signals delivered by the short text make it a promising source for topic modeling, its extreme sparsity and imbalance bring unprecedented challenges to conventional topic models like LDA and its variants. Aiming at presenting a simple but general solution for topic modeling in short texts, we present a word co-occurrence network based model named WNTM to tackle the sparsity and imbalance simultaneously. Different from previous approaches, WNTM models the distribution over topics for each word instead of learning topics for each document, which successfully enhance the semantic density of data space without importing too much time or space complexity. Meanwhile, the rich contextual information preserved in the word-word space also guarantees its sensitivity in identifying rare topics with convincing quality. Furthermore, employing the same Gibbs sampling as LDA makes WNTM easily to be extended to various application scenarios. Extensive validations on both short and normal texts testify the outperformance of WNTM as compared to baseline methods. And we also demonstrate its potential in precisely discovering newly emerging topics or unexpected events in Weibo at pretty early stages.

[Download paper here](http://zuoyuan.github.io/files/wntm_kais.pdf)
[Download code here](http://zuoyuan.github.io/files/wntm.tar.gz)

Recommended citation: Yuan Zuo, Jichang Zhao and Ke Xu. Word Network Topic Model: a Simple but General Solution for Short and Imbalanced Texts. KAIS, 2016.