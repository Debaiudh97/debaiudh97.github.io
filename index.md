---
layout: default
---

# Hello, I'm [Your Name] 👋

I am a student passionate about [Your Interests/Field]. Welcome to my personal slice of the internet!

## About Me
Here is a little bit about who I am, what I study, and what I love doing.

## My Daily Blog
Here is what I've been up to recently:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
