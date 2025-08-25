---
layout: page
title: Fun
permalink: /fun/
# description: I enjoy practicing yoga, meditating and dancing. I keep exploring different things periodically, right now really into indoor gardening and composting.  Added some info and couple of resources in the fields below. Feel free to check them out if interested!

nav: true
nav_order: 5
# display_categories: [work, fun]
horizontal: false
---

<style>
/* Hide the page title */
.post-title {
  display: none !important;
}

/* Reduce top padding when title is hidden */
.post-content {
  padding-top: 0 !important;
  margin-top: -4rem !important;
}
</style>

I enjoy practicing yoga, meditating and dancing. I keep exploring different things periodically, right now really into indoor gardening and composting.  
Added couple of resources and some info about couple of things I work on below. Feel free to check it out if interested!

<!-- pages/fun.md -->
<div class="fun">
{% if site.enable_fun_categories and page.display_categories %}
  <!-- Display categorized fun -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_fun = site.fun | where: "category", category %}
  {% assign sorted_fun = categorized_fun | sort: "importance" %}
  <!-- Generate cards for each fun -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for fun in sorted_fun %}
      {% include fun_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for fun in sorted_fun %}
      {% include fun.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display fun without categories -->

{% assign sorted_fun = site.fun | sort: "importance" %}

  <!-- Generate cards for each fun -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for fun in sorted_fun %}
      {% include fun_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for fun in sorted_fun %}
      {% include fun.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>