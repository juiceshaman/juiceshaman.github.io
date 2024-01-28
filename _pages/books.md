---
layout: page
title: books
permalink: /books/
description: Books I have known and loved.
nav: true
nav_order: 2
display_categories: []
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  <ul class="booklist">
