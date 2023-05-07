---
layout: default
permalink: /challenge/
title: 
---

<br>

<h1>MUAD Uncertainty Estimation for Semantic Segmentation Challenge</h1>

<h2>Introduction</h2>

MUAD (Multiple Uncertainties for Autonomous Driving) is a synthetic dataset for autonomous driving with multiple uncertainty types and tasks. The goal of this dataset is to better evaluate the uncertainty estimation performance of the models under simulated complex outdoor scenarios. Uncertainty estimation is crucial in autonomous driving. Proven by much research, the deep neural networks are uncalibrated: the model's decisions are often overconfident. In this case, a good uncertainty estimation approach can help the decision-making more robust and trustworthy.

This challenge aims to evaluate the uncertainty estimation performance of the semantic segmentation models. The participants will download the training and validation sets (containing the RGB images and the corresponding ground truth maps) as well as the test set (only the RGB images are provided), and design and train the models. Then ones should provide the confidence maps which can provide enough information to help the decision-maker to find out the Out-Of-Distribution objects in the test set images. Some of the test set images have different levels of weather conditions (rain, fog, snow), which will be challenging to the robustness of the models.

The MUAD challenge link: <strong>[click here](https://codalab.lisn.upsaclay.fr/competitions/8007)</strong>.

More information about the MUAD dataset and its download link are available at <strong>[MUAD website](https://muad-dataset.github.io/)</strong>. 


<h2>Submission & Evaluation</h2>
The participants are expected to submit their predictions to the CodaLab server for model evaluation. In order to make a successful submission and evaluation, you need to follow the instructions, including registration, file preparation, submission & evaluation, and result view. More details can be found on the challenge page on CodaLab.


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

<h2>Acknowledgments</h2>

<p>We gratefully acknowledge the support of DATAIA Paris-Saclay institute and AID Project ACoCaTherm which supported the creation of the dataset.</p>

