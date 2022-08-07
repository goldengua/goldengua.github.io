---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---



## Conference Presentations
### 2022
- Jiaxuan Li & Richard Futrell. A decomposition of surprisal predicts N400 and P600 in language processing. Poster at 28th annual conference on Architectures and Mechanisms for Language Processing (AMLaP2022), York, UK, 2022. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/amlap_2022_surprisal_decomposition.pdf)

- Weijie Xu, Jiaxuan Li, Ming Xiang & Richard Futrell. Syntactic adaptation to short-term cue-based distributional regularities. Poster at the 44th Annual Conference Cognitive Science (CogSci2022), Toronto, Canada, 2022. 

- Jiaxuan Li & Richard Futrell. Pre-trained language models can track some ERP components in language processing. Poster at the 35th Annual Conference on Human Sentence Processing (HSP2022), California [virtual], March 24-26, 2022. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/hsp_2022_LM_PNP.pdf)

- Weijie Xu, Jiaxuan Li & Ming Xiang. Syntactic adaptation to short-term cue-based distributional regularities. Poster at the 35th Annual Conference on Human Sentence Processing (HSP2022), California [virtual], March 24-26, 2022. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/hsp_2022_SynAdapt.pdf)

### 2021
- Jiaxuan Li & Ming Xiang. The benefits and costs of language prediction: Evidence from ERPs. Short talk at the 34th Annual CUNY Conference on Human Sentence Processing (CUNY2021), Philadelphia [virtual], March 4-6, 2021. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/cuny_2021_classifier.pdf)

- Jiaxuan Li & Allyson Ettinger. A noisy channel of N400 and P600 effects in sentence processing. Short talk at the 34th Annual CUNY Conference on Human Sentence Processing (CUNY2021), Philadelphia [virtual], March 4-6, 2021. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/cuny_2021_noisy_channel.pdf)

## Manuscripts and Publications
- Jiaxuan Li & Allyson Ettinger. Heuristic Interpretation as Rational Inference: A Computational Model of the N400 and P600 in Language Processing. Submitted to Cognition. [pdf](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4115173)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



