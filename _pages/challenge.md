---
layout: default
permalink: /challenge/
title: 
---

<br>

<h1>MUAD Uncertainty Estimation for Semantic Segmentation Challenge</h1>

<h2>Introduction</h2>

Predictive uncertainty estimation is essential for safe deployment of Deep Neural Networks in real-world autonomous systems. However, disentangling the different types and sources of uncertainty is nontrivial for most datasets, especially since there is no ground truth for uncertainty. In addition, while adverse weather conditions of varying intensities can disrupt neural network predictions, they are usually under-represented in both training and test sets in public datasets. We propose the <em>MUAD Uncertainty Estimation for Semantic Segmentation Challenge</em>.

The challenge is based on MUAD (Multiple Uncertainties for Autonomous Driving) dataset. More information about the dataset is available at <strong>[MUAD website](https://muad-dataset.github.io/)</strong>.


<h2>Submission & Evaluation</h2>
The MUAD challenge is now available on CodaLab here is the <strong>[Link](https://codalab.lisn.upsaclay.fr/competitions/8007)</strong> to the challenge.

The participants are expected to submit their predictions to the CodaLab server for model evaluation. In order to make a successful submission and evaluation, you need to follow the instructions including: registration, file preparation, submission & evaluation, and result view.


<h2>Important Dates</h2>


<p>All times are end of day AOE.</p>

<ul>

{% for item in site.data.other_info.deadlines_challenge  %}

  <li>{{ item.item }}: <strong>{{ item.date }}</strong></li>

{% endfor %}

</ul>


<h2>Organizers</h2>
<ul>

{% for item in site.data.organizers_challenge %}

  <li><a href="{{ item.url }}"><strong>{{ item.name }}</strong></a>, {{ item.affiliation }}</li>

{% endfor %}

</ul>
