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

## PhD day

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
