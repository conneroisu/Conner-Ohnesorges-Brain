---
layout: page
permalink: /teaching/
title: teaching
description: Materials for courses taken by Conner Ohnesorge.
nav: true
nav_order: 5
created: 2022-12-31T20:54:53-06:00
updated: 2023-01-29T14:25:01-06:00
---

Organize courses by years, topics, or universities, however you like!

<!-- pages/teaching.md -->
<div class="teachings">
{%- if page.display_categories %}
  <!-- Display categorized teachings/classes -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_teachings = site.teachings | where: "category", category -%}
  {%- assign sorted_teachings = categorized_teachings | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for teaching in sorted_teachings -%}
      {% include teachings_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for teaching in sorted_teachings -%}
      {% include teachings.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_teachings = site.teachings | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_teachings -%}
      {% include teachings_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_teachings -%}
      {% include teachings.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>