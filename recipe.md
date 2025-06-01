---
layout: page
title: Recipes
permalink: /recipes/
---

<ul>
  {% for recipe in site.recipes %}
    <li>
      <a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.title }}</a>
    </li>
  {% endfor %}
</ul>
