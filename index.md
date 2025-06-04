---
title: Home
---

# BATMEN Lab

Welcome to the BATMEN (BioinformAtics & Trustworthy Machine lEarNing) Lab headed by Dr. Yang Lu! 
<br>

<b>Research synopsis: </b>
Our principal research interests lie in the development of computational methods for the analysis of genomic and proteomic data. We are particularly interested in developing interpretable machine learning models to make sense of complex biological data. We are also interested in finding scientifically interesting and statistically confident hypotheses by interpreting these models.


{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
We make our research visible to both the computational biology and machine learning community.

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/publications.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
We tackle the challenges of data-intensive biology, which span data collection, data interpretation, hypothesis generation, and hypothesis testing.

{%
  include link.html
  link="tools"
  text="Browse our featured tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research.jpg"
  link="tools"
  title="Our Tools"
  flip=true
  text=text
%}

{% capture text %}
We are an interdisciplinary team of collaborative researchers with diverse skill sets.  

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/teams.jpg"
  link="team"
  title="Our Team"
  text=text
%}
