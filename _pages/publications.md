---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---
My research focus on three aspects:

# Neural mechanisms of real-time language comprehension
### Current project:
* Comprehenders could make advantage of contextual information to generate prediction and facilitate the processing of upcoming linguistic input during online sentence reading, however, it remains unclear the neural nature of context effect on sentence processing. The present study examines (1) whether context effect could affect the processing of unexpected linguistic inputs differently from expected inputs; and (2) whether there would be distinct neural process for language prediction in contexts with high- and low-levels of representation. We contrasted Chinese classifier-noun and verb-noun phrases to manipulate cloze probability (word predictability), plausibility, sentential constraints (how strongly a context would lead to a specific prediction), and levels of representation in a single ERP study. While we are still on data collection stage, the preliminary data show there was a frontal positivity effect on processing unexpected words in strongly v.s. weakly constraining contexts, suggesting a distinct neural signal to index inhibit disconfirmed language prediction.

### Past projects:
* Whether semantic prediction is graded by the strength of contextual predictability? 
* How quickly comprehenders take syntactic and semantic information to compute expectations about upcoming inputs, by manipulating various grammatical agreements between expected head nouns and preceding modifiers. 

# Computational modeling of psycholinguistic experiments 
### Current projects:
* Two important neural components N400 and P600 are closely linked to semantic and syntactic processing, respectively. However, this mapping has recently been challenged by a group of experiments with manipulation of high-level semantic information. One main distinction between psychology experiment and real-life communication is the assumption of noises. We propose that it is important to incorporate a noisy channel to model comprehension of complex semantically illusion sentences. We impleted our noisy-channel models with vector space model, LSTM and transformer. We successfully simulated nine experiments with diverging results and also compared the learnability among different NLP models. 

# Language learning 
### Current project:
* Our knowledge of native language is interfering the perception of sounds of other languages, which increases the difficulty of learning a second language. Mandarin tones, for example, are difficult to acquire with explicit instructions. Other hand, incidental learning has shown to be effective for auditory categorical learning. Incidental learning happens when learners' attention is directed away from what they are trying to learn. We aim to design a series of rhythm games to help English speakers learn Mandarin tones implicitly and efficiently. A core assumption of the game is that there is a consistent mapping between required game controls and categories of sounds the gamer is hearing. Try our game here.  

### Past project:
* I believe it is crucial to examine under-represented languages and populations when addressing theoretical issues in psycholinguistic research. Cantonese, with a distinctively rare combination of SVO main clause word order and prenominal relative clause, could shed light on the debates in competing theories of syntactic sentence processing concerned with surface structure (e.g. Dependency Locality Theory) and hierarchical sentence structure (e.g. Relativized Minimality Principle). With an eye-gaze paradigm, we examined comprehension and production of three different types of Cantonese relative clauses among 7-to-9-year-old children typically developed as well as children with Specific Language Impairment. Surprisingly, two types of relative clauses (ge3 RCs vs. CL RCs), which are different from each other with only one word, render into different syntactical analyses.  While children show a subject advantage when processing ge3 RCs, they prefer an internally headed analysis with an object advantage for CL RCs.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
