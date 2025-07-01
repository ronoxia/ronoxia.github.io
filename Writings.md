---
layout: page
title: Writings
permalink: /writings-by-tags
---



This is an evolving index of everything I’m writing — notes, essays, and observations across domains.  
Browse by topic below, or [view all posts in chronological order →](/all-posts).

---

{% assign tagged_pages = site.pages 
   | where_exp: "item", "item.tags != nil" 
   | where_exp: "item", "item.date != nil" %}

{% assign tagged_posts = site.posts 
   | where_exp: "item", "item.tags != nil" 
   | where_exp: "item", "item.date != nil" %}

{% assign all_writings = tagged_pages | concat: tagged_posts %}
{% assign all_writings = all_writings  %}




<!-- Collect unique tags from posts -->
{% assign tag_list = "" | split: "" %}
{% for post in all_writings %}
  {% if post.tags %}
    {% for tag in post.tags %}
      {% unless tag_list contains tag %}
        {% assign tag_list = tag_list | push: tag %}
      {% endunless %}
    {% endfor %}
  {% endif %}
{% endfor %}

<!-- Tag filter menu -->
<div style="margin-bottom: 1.5rem;">
  <strong>Filter by tag:</strong>
  {% for tag in tag_list %}
    <a href="#tag-{{ tag | slugify }}" style="margin-right: 0.5em;">#{{ tag }}</a>
  {% endfor %}
</div>

<!-- Posts grouped by tag -->
{% for tag in tag_list %}
<h3 id="tag-{{ tag | slugify }}">#{{ tag }}</h3>
<ul>
  {% for post in all_writings %}
    {% if post.tags contains tag %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <small>— {{ post.date | date: "%b %d, %Y" }}</small>
      </li>
    {% endif %}
  {% endfor %}
</ul>
{% endfor %}
