---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---
My research focus on three aspects:

# Neural mechanisms of real-time language comprehension
* Comprehenders could make advantage of contextual information to generate prediction and facilitate the processing of upcoming linguistic input during online sentence reading, however, it remains unclear the neural nature of context effect on sentence processing. The present study examines (1) whether context effect could affect the processing of unexpected linguistic inputs differently from expected inputs; and (2) whether there would be distinct neural process for language prediction in contexts with high- and low-levels of representation. We contrasted Chinese classifier-noun and verb-noun phrases to manipulate cloze probability (word predictability), plausibility, sentential constraints (how strongly a context would lead to a specific prediction), and levels of representation in a single ERP study. While we are still on data collection stage, the preliminary data show there was a frontal positivity effect on processing unexpected words in strongly v.s. weakly constraining contexts, suggesting a distinct neural signal to index inhibit disconfirmed language prediction.

Jiaxuan Li, Jinghua Ou & Ming Xiang (2021). The benefits and costs of language prediction: Evidence from ERPs. Short Talk presented at 34th Annual CUNY Conference on Human Sentence Processing. 


# Computational modeling of psycholinguistic experiments 

* Two important neural components N400 and P600 are closely linked to semantic and syntactic processing, respectively. However, this mapping has recently been challenged by a group of experiments with manipulation of high-level semantic information. One main distinction between psychology experiment and real-life communication is the assumption of noises. We propose that it is important to incorporate a noisy channel to model comprehension of complex semantically illusion sentences. We impleted our noisy-channel models with vector space model, LSTM and transformer. We successfully simulated nine experiments with diverging results and also compared the learnability among different NLP models. 

Jiaxuan Li, Allyson Ettinger (2021). A noisy channel model of N400 and P600 in sentence comprehension. Short Talk presented at 34th Annual CUNY Conference on Human Sentence Processing. 


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
