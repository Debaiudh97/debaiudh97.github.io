---
layout: default
title: Home
---

## About Me

I am a researcher specializing in [Your Field]. My work focuses on building scalable systems and exploring the intersection of [Topic A] and [Topic B]. 

Currently, I am working on [Current Project] under the supervision of [Advisor's Name]. Prior to this, I completed my B.S. at [Previous University].

## Research Interests
*   Artificial Intelligence & Machine Learning
*   Human-Computer Interaction
*   Distributed Systems

## Recent Updates & Blog

<ul class="post-list">
  {% for post in site.posts %}
    <li class="post-item">
      <a href="{{ post.url }}">
        <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
        <h3 class="post-title">{{ post.title }}</h3>
      </a>
    </li>
  {% endfor %}
</ul>
