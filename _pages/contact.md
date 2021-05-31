---
layout: single
title: Contact
permalink: /contact/
author_profile: true
---

List here how to get in touch (maybe add a comment box?)

## Project members

<ul>
{% for author_list in site.data.authors %}
  {% assign author = author_list[1] %}
  <div class="author__avatar">
    {% if author.home %}
        <a href="{{ author.home | relative_url }}">
          <img src="{{ author.avatar | relative_url }}" alt="{{ author.name }}" itemprop="image">
        </a>
      {% else %}
        <img src="{{ author.avatar | relative_url }}" alt="{{ author.name }}" itemprop="image">
      {% endif %}
    </div>
    <div class="author__content">
      <p>{{ author.name }} </p>
      <p> {{ author.bio }} </p>
      <p> <i> {{ author.motivation }} </i> </p>
    </div>
    <br>
    {% endfor %}
 </ul>