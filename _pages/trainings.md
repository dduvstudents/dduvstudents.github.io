---
layout: single
title: SkillUp!
permalink: /trainings/
toc: true

header:
  overlay_color: "white"
  overlay_filter: "0.4"
  overlay_image: "images/logos/skillup_logo.png"
  
excerpt: ""
---

SkillUp! is a project created by the PhD student organisation
of the de Duve Institute located at the UCLouvain campus in Brussels.
It serves as a student communication hub with the following objectives:  

- Reveal and emphasize the available softskills and hardskills 
trainings organised by UCLouvain and outside organisations   
- Encourage students to attend trainings for a great science 
- Give additional tips and tricks to go further

# Motivation

Science is of course and essentially an “all hands on deck” approach, or should we better say an “all hands on pipette/computer” approach? Running all day around the lab trying to execute you experiments or your analysis as efficiently as possible in order to test your hypothesis and get one step closer to your scientific nirvana. 

But did you know? It is also a great deal of COMMUNICATION. Even if you don’t notice it is all around us:  

- Of course, we have the classics: lab meetings, one-to-one meetings with PI, poster or oral talk 
- The less obvious: talk to yourself about organising your experiments (manage your diary, lab book), set your ideas clearly in your mind and translate them into sketches and efficient sentences to communicate them 
- The least obvious: reproducibility! Write down and explain clearly all the steps you carried out to complete a task so that the next researcher can repeat it and obtain the same results.  

So yes, communication is in the air.  

All of the above activities are we call softskills. They are the way we essentially work with ourselves and the people around us.  and these are necessary to be developed in order to achieve great science.   

*Do you need extra motivation?* students that enrolled in the doctoral program as of 2017 need at least 5 ECTS of transferable skills included in their general section of ‘Trainings’ to be completed in order to get the 60 ECTS to graduate: 

(https://uclouvain.be/fr/secteurs/sss/repartition-des-60-credits-de-formation-doctorale.html).  

# Reach out! 

Do you have any questions? Suggestions? Or do you just want to share your enthusiasm about Skill Up? Don’t hesitate to contact us!   

# Training organisations  

- CIO (center of information and orientation) 
- SMCS 
- Human resources administration 
- Louvain learning lab 
- Libraries of UCLouvain  

# Recent posts about trainings

<ul>
  {% for post in site.posts %}
    {% if post.tags contains "training" %}
      {% include archive-single.html type=entries_layout %}
    {% endif %}
  {% endfor %}
</ul>
