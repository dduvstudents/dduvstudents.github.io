---
layout: single
title: Events
permalink: /events/
author_profile: true
---

We organize 2 yearly events: 

- PhD day
- BBQ 

# PhD day

The PhD day of the de Duve Institute is an event created by the 
students for the students and more precisely by the de Duve students' 
society. The concept is that during one day all the PhD students 
gather and have the opportunity to present their work to their peers 
through a poster or a presentation session.

Our objective is that the de Duve Institute becomes a united 
scientific community in the next years, and this starts with the PhD 
Day ! Even though the event will finally be online, we hope to provide
a nice environment for sharing research projects and connecting with 
other PhD students as well as to feed the scientific minds with 
various interesting scientific topics and stimulating discussions.

{% include image-gallery.html folder="/images/gallery" %}

# Recent posts about our events

<ul>
  {% for post in site.posts %}
    {% if post.tags contains "event" %}
      {% include archive-single.html type=entries_layout %}
    {% endif %}
  {% endfor %}
</ul>
