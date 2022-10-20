---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
author_profile: true
---

I'm a software engineer at [Legato Health Technologies](https://www.legato.com)working with Responsible AI Team on fairness, explainability and data drift for classification and regression models for tabular and text data. I'm broadly interested in developing computationally efficent and trustworthy machine learning models for variety of applications.

Previously, I was an intern at [NVIDIA](https://www.nvidia.com/) under the supervision of [Kumari Deepshikha](https://www.linkedin.com/in/deepkshikha/) where I worked on class-imbalance problem for images and speech-to-text conversion for Indic Languages. I was also an intern at [AI-ML-NLP Lab](https://www.iitp.ac.in/~ai-nlp-ml/) where I worked on author profiling of tweets under the supervision of [Prof. Sriparna Saha](https://www.iitp.ac.in/~sriparna/) and [Pushpak Bhattacharyya](https://www.cse.iitb.ac.in/~pb/).

I graduated with a B.Tech in Computer Science and Engineering from the [Indian Institute of Information Technology, Guwahati](https://www.iiitg.ac.in/) in 2022.

I have also contributed to open-source at [HuggingFace 🤗](https://huggingface.co/) I have added Microsoft's [CvT: Introducing Convolutions to Vision Transformers](https://huggingface.co/docs/transformers/model_doc/cvt) and [LeViT: Introducing Convolutions to Vision Transformers](https://huggingface.co/docs/transformers/model_doc/levit).


Feel free to get in touch if you want to chat about research! 

<h3>News</h3>
{% assign news = site.data.news | where: "hidden", nil | sort: 'date' | reverse | slice: 0, 5 %}
{% include news.html news=news %}

<h3>Publications</h3>
{% include publications.html
    publications=site.data.publications
    numbering=false
%}
