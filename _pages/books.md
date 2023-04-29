---
layout: page
title: books
permalink: /books/
description: Books I have known and loved.
nav: true
nav_order: 2
display_categories: [philosophy, science, humanities, fiction]
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  <ul class="booklist">

</ul>
<h2 id="Philosophy, Psychology</h2>
<ul class="booklist">

<li>Nietzsche, Friedrich – <dfn>The Anti-Christ</dfn> <span class="loc">(B3313.A8)</span></li>

<li>Nietzsche, Friedrich – <dfn>The Birth of Tragedy and The Case of Wagner</dfn> <span class="loc">(B3313.G42)</span></li>

<li>Nietzsche, Friedrich – <dfn>Beyond Good and Evil</dfn> <span class="loc">(B3313.J43)</span></li>

<li>Nietzsche, Friedrich – <dfn>On the Genealogy of Morals and Ecce Homo</dfn> <span class="loc">(B3316.N54)</span></li>

<li>Kahneman, Daniel – <dfn>Thinking, Fast and Slow</dfn> <span class="loc">(BF441)</span>

<li>Carnegie, Dale – <dfn>How to Win Friends &amp; Influence People</dfn> <span class="loc">(BF637.S8)</span></li>

<li>Epicurus – <dfn>Letters and Sayings of Epicurus</dfn> <span class="loc">(B570.E5)</span></li>

li>Taleb, Nassim Nicholas – <dfn>Antifragile</dfn> <span class="loc">(Q375)</span></li>

li>Taleb, Nassim Nicholas – <dfn>The Black Swan</dfn> <span class="loc">(Q375)</span></li>

/ul>

  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>

<!-- <!DOCTYPE html>
<!-- <html lang="en"><head>
<!-- 	<title>My Personal Library | Luke's Webpage</title>
<!-- 	<link rel="canonical" href="https://juiceshaman.github.io">
<!-- 	<link rel="alternate" type="application/rss+xml" title="Mario's Webpage RSS" href="/index.xml">
<!-- 	<link rel="stylesheet" type="text/css" href="/style.css">
<!-- 	<link rel="icon" href="/favicon.ico">
<!-- 	<meta name="description" content="This is a list of the books in my personal library. If you have any questions or want me to review any of them, email me (!!email!!).
<!-- I haven't read every book here, nor do I own all the books I've read or like. I also don't necessarily like all the books I own.

	<meta name="keywords" content="personal, science, tradition, lifestyle, philosophy">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<meta name="robots" content="index, follow">
	<meta charset="utf-8">
</head>
<body>
<main>
<a href="/"><header>
	<h1 id="tag_My Personal Library">My Personal Library</h1>
</header></a>
<article>

h2 id="another topic">QA: Topic</h2>
ul class="booklist">

<ul class="booklist">

</ul>
<h2 id="books-as-of-yet-unsorted">Books as of yet unsorted</h2>
<ul class="booklist">


</ul>
<div style="clear:both" class="taglist">Read related articles:<br><a id="tag_personal" href="https://juiceshaman.github.io/tags/personal">Personal</a> · <a id="tag_science" href="https://juiceshaman.github.io/tags/science">Science</a> · <a id="tag_philosophy" href="https://juiceshaman.github.io/tags/philosophy">Philosophy</a></div>
<br clear="both">
</article>
</main>
<footer>
	<a href="</a>

	<p>
<!--	<img class="lw" src="/pix/btc.svg">Bitcoin (<a href="/pix/btc-logo.png">QR</a>): wallet ID </code>
	<br>
	<img class="lw" src="/pix/xmr.svg">Monero (<a href="/pix/xmr-logo.png">QR</a>): <code class="crypto">monero wallet id> -->
	</p><p><a href="/index.xml"><img src="/rss.svg" style="max-height:1.5em" alt="RSS Feed" title="Subscribe via RSS for updates."></a>
</p></footer>


</body></html>
