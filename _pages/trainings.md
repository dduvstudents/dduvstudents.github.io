---
layout: single
title: SkillUp!
permalink: /trainings/
toc: true
header:
  overlay_color: "white"
  overlay_filter: "0.4"
excerpt: ""
---

SkillUp! is a project created by the PhD student organisation
of the de Duve Institute located at the UCLouvain campus in Brussels.
It serves as a student communication hub with the following objectives:  

- Reveal and emphasize the available softskills and hardskills 
trainings organised by UCLouvain and outside organisations   
- Encourage students to attend trainings for a great science 
- Give additional tips and tricks to go further

<div style="width: 20%">
    <img src="{{site.baseurl}}/images/logos/skillup_logo.svg"/>
</div>

# Motivation

Science is of course and essentially an “all hands on deck” approach, or should we better say an “all hands on pipette/computer” approach? Running all day around the lab trying to execute you experiments or your analysis as efficiently as possible in order to test your hypothesis and get one step closer to your scientific nirvana. 

But did you know? It is also a great deal of COMMUNICATION. Even if you don’t notice it is all around us:  

- Of course, we have the classics: lab meetings, one-to-one meetings with PI, poster or oral talk 
- The less obvious: talk to yourself about organising your experiments (manage your diary, lab book), set your ideas clearly in your mind and translate them into sketches and efficient sentences to communicate them 
- The least obvious: reproducibility! Write down and explain clearly all the steps you carried out to complete a task so that the next researcher can repeat it and obtain the same results.  

So yes, communication is in the air.  

All of the above activities are we call softskills. They are the way we essentially work with ourselves and the people around us.  and these are necessary to be developed in order to achieve great science.   

*Do you need extra motivation?* students that enrolled in the doctoral program as of 2017 need at least 5 ECTS of transferable skills included in their general section of ‘Trainings’ to be completed in order to get the [60 ECTS to graduate](https://uclouvain.be/fr/secteurs/sss/repartition-des-60-credits-de-formation-doctorale.html).  

# Training organisations  

**Disclaimer**: all the organisations detailed below have multiple missions and ways to support researchers. Here, we are going to focus mostly in their trainings organisations.   

[CIO](https://uclouvain.be/fr/etudier/cio) (Centre of Information and Orientation): is part of the teaching and Training Department Administration of UCLouvain. It is not restricted to PhD students but is open to all study levels from high school students, future graduates, PhD holders etc. Among some of CIO missions are to provide career support for students at any study level, inform and bring awareness to the possibility of study and career choices. One of the ways to achieve these objectives are the organisation of trainings such as: how to write a cover letter, CV, understand the recruiter’s perspective etc.  

[SMCS](https://uclouvain.be/en/research-institutes/lidam/smcs.html) (Statistical Methodology and Computing Service): aims to support researchers in their projects from a statistical point of view. They offer training courses on different programming languages (R, Python..) …), statistical methods (data visualisation, data analysis,..). They also provide consulting services: you have a question about your analysis? You want to perform a highthroughput experiment and have questions about your design? Don’t hesitate to contact them! 

[Human resources administration](https://intranet.uclouvain.be/en/myucl/working/se-former.html): organise regularly trainings that target organisation, communication and management skills. PhD students are members of the UCLouvain staff so you are more than welcome to participate!  

[Louvain Learning Lab](https://uclouvain.be/en/study/lll): is dedicated to professors and teaching assistants who wish to develop great teaching methods to animate their course (in person or virtual courses), mentoring through their practical courses etc.   

[Libraries of UCLouvain](https://uclouvain.be/fr/bibliotheques): offer trainings regarding motor search engines, publishing in open access, reference management tools.  

# In practice: Valodoc 

You can access all trainings offered by UCLouvain from the [Valodoc website](https://search-engine-pe.sipr.ucl.ac.be/valodoc/)

This website allows you to search for trainings by different filters such as the date, organisers, types of trainings. The research engine is pretty straightforward so don’t hesitate to look for the trainings that can help you further develop your skills in an area of interest.   

This site is part of Valodoc effort to accompany students before, during and after doctoral school. It gathers information about what exactly a PhD journey is, the administrative procedures needed to enrol, as well as tool to help guide through the PhD and support for 	finding a career path after the graduation. Do not hesitate to check it out! 

# Heads up!  

For the trainings to be efficient a limited number of seats are available for each session. Additionally, as mentioned above, these trainings are not only dedicated to PhD students. If you have a training that you wish to take sign up for it as soon as it opens to make sure to have a saved seat. Another possibility is to register on a waiting list and be called if a cancellation occurs. Trainings are planned ahead the academic year so you won’t have multiple new trainings coming up often during the semester.  

Some trainings are only available in French, so don’t forget to check the language of the session! 

# Contact 

Do you have any questions? Suggestions?  

Heard of interesting trainings internal or external to UCLouvain?  

Want to give a feedback about a training you recently had?  

Do you have a training that you’d love to have but can’t find a seat available?   

Or just want to share your enthusiasm about Skill Up?  

Don’t hesitate to contact us!

# Recent posts about trainings

<ul>
  {% for post in site.posts %}
    {% if post.tags contains "training" %}
      {% include archive-single.html type=entries_layout %}
    {% endif %}
  {% endfor %}
</ul>
