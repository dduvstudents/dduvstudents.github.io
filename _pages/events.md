---
layout: single
title: Our events
permalink: /events/
author_profile: true
toc: true
---

We organize several yearly events. Some of them are meant as serious 
events that will help you progress through your PhD, while others are 
informal and focus on having fun with the other PhD students. 

# Serious events

## PhD students' day

The PhD students' day is an event created by the students for the 
students and more precisely by the de Duve students' society. The 
concept is that during one day all the PhD students gather and have 
the opportunity to present their work to their peers through a poster 
or a presentation session. It's a great opportunity to learn about the
research from the neighbouring labs and to connect with our fellow
PhD students.

{% include image-gallery.html folder="/images/phd_day" %}

## Welcome day


# Fun events 

## BBQ


## PhD weekend


# Recent posts about our events

<ul>
  {% for post in site.posts %}
    {% if post.tags contains "event" %}
      {% include archive-single.html type=entries_layout %}
    {% endif %}
  {% endfor %}
</ul>
