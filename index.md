---
layout: default
title: Home
---

# Hyunam Archive

A technical archive focused on systems, programming, mathematics and long-term study.

## Focus

- building systems from scratch
- understanding how software works internally
- disciplined technical learning

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>— {{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
