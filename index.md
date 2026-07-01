---
layout: default
title: Home
---

## About Me

I am a researcher specializing in string phenomenlogy. My work focuses on building models and exploring the intersection of string theory with cosmology. 

Currently, I am working on moduli stabilization under the supervision of Dr. Pramod Kumar Shukla at Bose Institute. Prior to this, I completed my Int. MSc. at NISER.

## Research Interests
*   String Cosmology
*   Black Holes in String Theory
*   Conformal Field Theory
*   Moduli Stabilization

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
