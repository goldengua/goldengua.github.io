---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<h2> Publications </h2>
<p> Jiaxuan Li & Allyson Ettinger. Heuristic Interpretation as Rational Inference: A Computational Model of the N400 and P600 in Language Processing. <i> To appear in Cognition. </i> <a href= "https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4115173">[PDF]</a> </p>

<h2> Peer-reviewed Conferences </h2>
<p> <b> 2022 </b> </p>
<p> Jiaxuan Li & Richard Futrell. A unified information-theoretic model of EEG signatures of human language processing. <i> NeurIPS 2022 Workshop on Information-Theoretic Principles in Cognitive Systems (InfoCog) </i>, New Orleans, US, 2022. <a href = "https://openreview.net/pdf?id=fYzwjX_XC0C"> [PDF] </a> </p>

<p> Jiaxuan Li, Yu Lang & Allyson Ettinger. A unified information-theoretic model of EEG signatures of human language processing. <i> NeurIPS 2022 Workshop on Neuro Causal and Symbolic AI (nCSI) </i>, New Orleans, US, 2022. [pdf](https://arxiv.org/abs/2212.03278) </p>

<p> Jiaxuan Li & Richard Futrell. A decomposition of surprisal predicts N400 and P600 in language processing. <i> The 28th annual conference on Architectures and Mechanisms for Language Processing (AMLaP2022) </i>, York, UK, 2022. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/amlap_2022_surprisal_decomposition.pdf) </p>

<p> Weijie Xu, Jiaxuan Li, Ming Xiang & Richard Futrell. Syntactic adaptation to short-term cue-based distributional regularities. <i> Poster at the 44th Annual Conference Cognitive Science (CogSci2022) </i>, Toronto, Canada, 2022. </p>

<p> Jiaxuan Li & Richard Futrell. Pre-trained language models can track some ERP components in language processing. <i> The 35th Annual Conference on Human Sentence Processing (HSP2022) </i>, California, March 24-26, 2022. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/hsp_2022_LM_PNP.pdf) </p>

<p> Weijie Xu, Jiaxuan Li & Ming Xiang. Syntactic adaptation to short-term cue-based distributional regularities. <i> The 35th Annual Conference on Human Sentence Processing (HSP2022) </i>, California, March 24-26, 2022. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/hsp_2022_SynAdapt.pdf) </p>

<p> <b> 2021 </b> </p>
<p> Jiaxuan Li & Ming Xiang. The benefits and costs of language prediction: Evidence from ERPs. <i> The 34th Annual CUNY Conference on Human Sentence Processing (CUNY2021) </i>, Philadelphia, March 4-6, 2021. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/cuny_2021_classifier.pdf) </p>

<p> Jiaxuan Li & Allyson Ettinger. A noisy channel of N400 and P600 effects in sentence processing. <i> The 34th Annual CUNY Conference on Human Sentence Processing (CUNY2021) </i>, Philadelphia, March 4-6, 2021. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/cuny_2021_noisy_channel.pdf) </p>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



