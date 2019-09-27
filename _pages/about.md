---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<p style = "font-weight: 400;">An algebraic topologist by training, my main focus is to develop and apply new topological approaches to study complex systems. In particular, I work on applying these tools to biological networks.  </p>

<p style = "font-weight: 400;">I am currently a Research Scientist at <a href = "http://iuni.iu.edu/">Indiana University Network Science Institute (IUNI)</a> in Bloomington (IN). I work on mathematical modelling for brain networks in close collaboration with Olaf Sporns and his team. I am partially founded by the IMAGENE project to develop models for the joint analysis of genomics and neuroimaging data.  </p>

<p style = "font-weight: 400;">I obtained my Ph.D in Applied Mathematics at Politecnico di Torino with a dissertation titled: "Simplicial Data Analysis: theory, practice, and algorithms". During my PhD I worked at I.S.I. Foundation in Torino, where I was a part of the research group on "Mathematics and the foundation of complex systems".  </p>

<!--Here are some of the projects I am focusing on right now:
- Developing new technique for joint analysis of genomics and neuroimaging data for transitional clinical research, joint work with Liana G. Apostolova, MD (part of the IMAGENE project);
- Analysing dMRI lifespan data, joint work with Olaf Sporns, Joshua Faskowitz @ Indiana University
- Developing a stochastic sampler for Directed Simplicial Complexes;
- Studying Mathematical models of community structures in relation to simplicial complexes;
- Topological Data Analysis on Health data (rna transcriptomes, quantitative semantic data, brain networks from fMRI, EEG, DTI).
-->


# News
{% include base_path %}

<div class="page-background"
style="background-image: url("https://alpatania.github.io/images/bg_about.png");
background-position: 90% 100%;
background-repeat: no-repeat;"
>

{% for post in site.posts reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
