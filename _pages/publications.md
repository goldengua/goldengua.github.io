---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---



# Conference Presentations
## 2022
3. Jiaxuan Li & Richard Futrell. Pre-trained language models can track some ERP components in language processing. Poster at the 35th Annual Conference on Human Sentence Processing, California [virtual], March 24-26. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/hsp_2022_LM_PNP.pdf)
3. Weijie Xu, Jiaxuan Li & Ming Xiang. Syntactic adaptation to short-term cue-based distributional regularities. Poster at the 35th Annual Conference on Human Sentence Processing, California [virtual], March 24-26. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/hsp_2022_SynAdapt.pdf)
## 2021
2. Jiaxuan Li & Ming Xiang. The benefits and costs of language prediction: Evidence from ERPs. Short talk at the 34th Annual CUNY Conference on Human Sentence Processing, Philadelphia [virtual], March 4-6. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/cuny_2021_classifier.pdf)
2. Jiaxuan Li & Allyson Ettinger. A noisy channel of N400 and P600 effects in sentence processing. Short talk at the 34th Annual CUNY Conference on Human Sentence Processing, Philadelphia [virtual], March 4-6. [pdf](https://github.com/goldengua/goldengua.github.io/blob/master/files/cuny_2021_noisy_channel.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



