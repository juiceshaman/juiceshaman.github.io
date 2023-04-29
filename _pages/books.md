---
layout: page
title: books
permalink: /books/
description: Books I have known and loved.
nav: true
nav_order: 2
display_categories: [science, humanities, fiction]
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
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

<!DOCTYPE html>
<html lang="en"><head>
	<title>My Personal Library | Luke's Webpage</title>
	<link rel="canonical" href="https://juiceshaman.github.io">
	<link rel="alternate" type="application/rss+xml" title="Mario's Webpage RSS" href="/index.xml">
	<link rel="stylesheet" type="text/css" href="/style.css">
	<link rel="icon" href="/favicon.ico">
	<meta name="description" content="This is a list of the books in my personal library. If you have any questions or want me to review any of them, email me (!!email!!).
I haven't read every book here, nor do I own all the books I've read or like. I also don't necessarily like all the books I own.

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

<ul class="booklist">




<li>Nietzsche, Friedrich – <dfn>The Anti-Christ</dfn> <span class="loc">(B3313.A8)</span></li>

<li>Nietzsche, Friedrich – <dfn>The Birth of Tragedy and The Case of Wagner</dfn> <span class="loc">(B3313.G42)</span></li>

<li>Nietzsche, Friedrich – <dfn>Beyond Good and Evil</dfn> <span class="loc">(B3313.J43)</span></li>

<li>Nietzsche, Friedrich – <dfn>On the Genealogy of Morals and Ecce Homo</dfn> <span class="loc">(B3316.N54)</span></li>

<li>Wilson, Edward O. – <dfn>Consilience</dfn> <span class="loc">(B72)</span></li>

</ul>
<h2 id="bf-bl-psychology-aesthetics-ethics-general-religion-mythology-rationalism">BF-BL: Psychology, Aesthetics, Ethics, General Religion, Mythology, Rationalism</h2>
<ul class="booklist">

<li>Kahneman, Daniel – <dfn>Thinking, Fast and Slow</dfn> <span class="loc">(BF441)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Carnegie, Dale – <dfn>How to Win Friends &amp; Influence People</dfn> <span class="loc">(BF637.S8)</span></li>



<li>Epicurus – <dfn>Letters and Sayings of Epicurus</dfn> <span class="loc">(B570.E5)</span></li>

<li>Popper, Karl – <dfn>The Open Society and Its Enemies: Volume I: Plato</dfn> <span class="loc">(B63)</span> <a href="https://notrelated.xyz/#02.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Popper, Karl – <dfn>The Open Society and Its Enemies: Volume II: Hegel &amp; Marx</dfn> <span class="loc">(B63)</span></li>

<li>Wilson, Edward O. – <dfn>Consilience</dfn> <span class="loc">(B72)</span></li>

<li>Yates, Frances A. – <dfn>Giordano Bruno and the Hermetic Tradition</dfn> <span class="loc">(B783.Z7)</span></li>

<li>Searle, John – <dfn>The Mystery of Consciousness</dfn> <span class="loc">(B808.9)</span></li>

<li>Mercier, Hugo and Sperber, Dan – <dfn>The Enigma of Reason</dfn> <span class="loc">(B833)</span></li>

<li>Boorstin, Daniel J. – <dfn>The Lost World of Thomas Jefferson</dfn> <span class="loc">(B878)</span></li>

<li>Bergmann, Merrie and Moore, James and Nelson, Jack – <dfn>The Logic Book</dfn> <span class="loc">(BC135)</span></li>

<li>Patterson, Stephen and Borg, Marcus and Crossan, John Dominic – <dfn>The Search for Jesus: Modern Scholarship Looks at the Gospels</dfn> <span class="loc">(BC2555.5)</span></li>

<li>Clark, Gordon H. – <dfn>Logic</dfn> <span class="loc">(BC71)</span></li>

<li>Popper, Karl – <dfn>Conjectures and Refutations: The Growth of Scientific Knowledge</dfn> <span class="loc">(BD241)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

</ul>
<li>Bacon, Francis – <dfn>Novum Organum</dfn> <span class="loc">(AC1)</span></li>
Bacon, Francis –
<dfn>Novum Organum</dfn>
<span class="loc">(AC1)</span>
<li>Bacon, Francis – <dfn>Novum Organum</dfn> <span class="loc">(AC1)</span></li>
<li>Plotinus – <dfn>The Six Enneads</dfn> <span class="loc">(AC1)</span></li>
Plotinus –
<dfn>The Six Enneads</dfn>
<span class="loc">(AC1)</span>
<li>Plotinus – <dfn>The Six Enneads</dfn> <span class="loc">(AC1)</span></li>
<li>Clucas, Philip – <dfn>Wonders of the World</dfn> <span class="loc">(AG243)</span></li>
<li>Gould, Rupert T. – <dfn>Enigmas</dfn> <span class="loc">(AG243)</span></li>
<li>Gould, Rupert T. – <dfn>Oddities</dfn> <span class="loc">(AG243)</span></li>
<li>Hofstadter, Douglas and Dennett, Daniel – <dfn>The Mind's I</dfn> <span class="loc">(B29)</span></li>
<li>Nietzsche, Friedrich – <dfn>The Anti-Christ</dfn> <span class="loc">(B3313.A8)</span></li>
<li>Nietzsche, Friedrich – <dfn>The Birth of Tragedy and The Case of Wagner</dfn> <span class="loc">(B3313.G42)</span></li>
<li>Nietzsche, Friedrich – <dfn>Beyond Good and Evil</dfn> <span class="loc">(B3313.J43)</span></li>
<li>Nietzsche, Friedrich – <dfn>On the Genealogy of Morals and Ecce Homo</dfn> <span class="loc">(B3316.N54)</span></li>
<li>Plato – <dfn>The Dialogues of Plato</dfn> <span class="loc">(B358)</span></li>
<li>Aristotle – <dfn>The Basic Works of Aristotle</dfn> <span class="loc">(B407)</span></li>
<li>Ayer, Alfred Jules – <dfn>Language, Truth &amp; Logic</dfn> <span class="loc">(B53)</span></li>
<li>Epicurus – <dfn>Letters and Sayings of Epicurus</dfn> <span class="loc">(B570.E5)</span></li>
<li>Popper, Karl – <dfn>The Open Society and Its Enemies: Volume I: Plato</dfn> <span class="loc">(B63)</span> <a href="https://notrelated.xyz/#02.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>
<li>Popper, Karl – <dfn>The Open Society and Its Enemies: Volume II: Hegel &amp; Marx</dfn> <span class="loc">(B63)</span></li>
<li>Wilson, Edward O. – <dfn>Consilience</dfn> <span class="loc">(B72)</span></li>
<li>Yates, Frances A. – <dfn>Giordano Bruno and the Hermetic Tradition</dfn> <span class="loc">(B783.Z7)</span></li>
<li>Searle, John – <dfn>The Mystery of Consciousness</dfn> <span class="loc">(B808.9)</span></li>
<li>Mercier, Hugo and Sperber, Dan – <dfn>The Enigma of Reason</dfn> <span class="loc">(B833)</span></li>
<li>Boorstin, Daniel J. – <dfn>The Lost World of Thomas Jefferson</dfn> <span class="loc">(B878)</span></li>
<li>Bergmann, Merrie and Moore, James and Nelson, Jack – <dfn>The Logic Book</dfn> <span class="loc">(BC135)</span></li>
<li>Patterson, Stephen and Borg, Marcus and Crossan, John Dominic – <dfn>The Search for Jesus: Modern Scholarship Looks at the Gospels</dfn> <span class="loc">(BC2555.5)</span></li>
<li>Clark, Gordon H. – <dfn>Logic</dfn> <span class="loc">(BC71)</span></li>
<li>Popper, Karl – <dfn>Conjectures and Refutations: The Growth of Scientific Knowledge</dfn> <span class="loc">(BD241)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>
<ul class="booklist">
<li>Bacon, Francis – <dfn>Novum Organum</dfn> <span class="loc">(AC1)</span></li>

<li>Plotinus – <dfn>The Six Enneads</dfn> <span class="loc">(AC1)</span></li>

<li>Clucas, Philip – <dfn>Wonders of the World</dfn> <span class="loc">(AG243)</span></li>

<li>Gould, Rupert T. – <dfn>Enigmas</dfn> <span class="loc">(AG243)</span></li>

<li>Gould, Rupert T. – <dfn>Oddities</dfn> <span class="loc">(AG243)</span></li>

<li>Hofstadter, Douglas and Dennett, Daniel – <dfn>The Mind's I</dfn> <span class="loc">(B29)</span></li>

<li>Nietzsche, Friedrich – <dfn>The Anti-Christ</dfn> <span class="loc">(B3313.A8)</span></li>

<li>Nietzsche, Friedrich – <dfn>The Birth of Tragedy and The Case of Wagner</dfn> <span class="loc">(B3313.G42)</span></li>

<li>Nietzsche, Friedrich – <dfn>Beyond Good and Evil</dfn> <span class="loc">(B3313.J43)</span></li>

<li>Nietzsche, Friedrich – <dfn>On the Genealogy of Morals and Ecce Homo</dfn> <span class="loc">(B3316.N54)</span></li>

<li>Plato – <dfn>The Dialogues of Plato</dfn> <span class="loc">(B358)</span></li>

<li>Aristotle – <dfn>The Basic Works of Aristotle</dfn> <span class="loc">(B407)</span></li>

<li>Ayer, Alfred Jules – <dfn>Language, Truth &amp; Logic</dfn> <span class="loc">(B53)</span></li>

<li>Epicurus – <dfn>Letters and Sayings of Epicurus</dfn> <span class="loc">(B570.E5)</span></li>

<li>Popper, Karl – <dfn>The Open Society and Its Enemies: Volume I: Plato</dfn> <span class="loc">(B63)</span> <a href="https://notrelated.xyz/#02.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Popper, Karl – <dfn>The Open Society and Its Enemies: Volume II: Hegel &amp; Marx</dfn> <span class="loc">(B63)</span></li>

<li>Wilson, Edward O. – <dfn>Consilience</dfn> <span class="loc">(B72)</span></li>

<li>Yates, Frances A. – <dfn>Giordano Bruno and the Hermetic Tradition</dfn> <span class="loc">(B783.Z7)</span></li>

<li>Searle, John – <dfn>The Mystery of Consciousness</dfn> <span class="loc">(B808.9)</span></li>

<li>Mercier, Hugo and Sperber, Dan – <dfn>The Enigma of Reason</dfn> <span class="loc">(B833)</span></li>

<li>Boorstin, Daniel J. – <dfn>The Lost World of Thomas Jefferson</dfn> <span class="loc">(B878)</span></li>

<li>Bergmann, Merrie and Moore, James and Nelson, Jack – <dfn>The Logic Book</dfn> <span class="loc">(BC135)</span></li>

<li>Patterson, Stephen and Borg, Marcus and Crossan, John Dominic – <dfn>The Search for Jesus: Modern Scholarship Looks at the Gospels</dfn> <span class="loc">(BC2555.5)</span></li>

<li>Clark, Gordon H. – <dfn>Logic</dfn> <span class="loc">(BC71)</span></li>

<li>Popper, Karl – <dfn>Conjectures and Refutations: The Growth of Scientific Knowledge</dfn> <span class="loc">(BD241)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

</ul>
<h2 id="bf-bl-psychology-aesthetics-ethics-general-religion-mythology-rationalism">BF-BL: Psychology, Aesthetics, Ethics, General Religion, Mythology, Rationalism</h2>
<ul class="booklist">

<figure class="resright"><a href="https://www.youtube.com/watch?v=KD-B3zwyV5I"><img src="/pix/hamletsmill.jpg" title="Probably the worst book I've ever read 6 times."></a></figure>

<p></p><li>Freud, Sigmund – <dfn>Civilization and its Discontents</dfn> <span class="loc">(BF173.F682)</span></li>

<li>Sugrue, Thomas – <dfn>The Story of Edgar Cayce: There Is a River</dfn> <span class="loc">(BF1027.C3)</span></li>

<li>Kramer, Heinrich and Sprenger, James – <dfn>Malleus Maleficarum (The Hammer of the Witches)</dfn> <span class="loc">(BF1569.A2)</span></li>

<li>Fowden, Garth – <dfn>The Egyptian Hermes: A Historical Approach to the Late Pagan Mind</dfn> <span class="loc">(BF1591)</span></li>

<li>Evola, Julius – <dfn>The Hermetic Tradition: Symbols &amp; Teachings of the Royal Art</dfn> <span class="loc">(BF1611)</span></li>

<li>Three Initiates – <dfn>The Kybalion</dfn> <span class="loc">(BF1611)</span></li>

<li>Yates, Frances A. – <dfn>The Rosicrucian Enlightenment</dfn> <span class="loc">(BF1623.R7)</span></li>

<li>Slater, Lauren – <dfn>Opening Skinner's Box</dfn> <span class="loc">(BF198.7)</span></li>

<li>Jaynes, Julian – <dfn>The Origin of Consciousness in the Breakdown of the Bicamerial Mind</dfn> <span class="loc">(BF311)</span> <a href="https://notrelated.xyz/#01.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Pinker, Steven – <dfn>Blank Slate</dfn> <span class="loc">(BF341)</span></li>

<li>Kahneman, Daniel – <dfn>Thinking, Fast and Slow</dfn> <span class="loc">(BF441)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Gigerenzer, Gerd – <dfn>Rationality for Mortals: How People Cope With Uncertainty </dfn> <span class="loc">(BF442)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Carnegie, Dale – <dfn>How to Win Friends &amp; Influence People</dfn> <span class="loc">(BF637.S8)</span></li>

<li>Skinner, B. F – <dfn>Beyond Freedom and Dignity</dfn> <span class="loc">(BF698.9.C8)</span></li>

<li>Miller, Alan S. and Kanazawa, Satoshi – <dfn>Why Beautiful People Have More Daughters</dfn> <span class="loc">(BF698.95)</span></li>

<li>Murphy, Gardener – <dfn>Psychological Thought from Pythagoras to Freud</dfn> <span class="loc">(BF81)</span></li>

<li>Rand, Ayn – <dfn>The Virtue of Selfishness</dfn> <span class="loc">(BJ1474)</span></li>

<li>Mencken, H.L. – <dfn>Treatise on Right and Wrong</dfn> <span class="loc">(BJ71)</span></li>

<li>Harris, Sam – <dfn>Free Will</dfn> <span class="loc">(BK1461)</span></li>

<li>De Santillana, Giorgio &amp; von Dechend, Hertha – <dfn>Hamlet's Mill: An Essay Investigating the Origins of Human Knowledge and Its Transmission Through Myth</dfn> <span class="loc">(BL304)</span> <a href="https://notrelated.xyz/#02.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Frazer, James George – <dfn>The Golden Bough: The Roots of Religion and Folklore</dfn> <span class="loc">(BL310)</span></li>

<li>Narasimhan, Chakravarthi V. – <dfn>The Mahabharata: An English Version Based on Selected Verses</dfn> <span class="loc">(BL1138.22)</span></li>
<p></p>
</ul>
<figure class="resright"><a href="https://www.youtube.com/watch?v=KD-B3zwyV5I"><img src="/pix/hamletsmill.jpg" title="Probably the worst book I've ever read 6 times."></a></figure>
<a href="https://www.youtube.com/watch?v=KD-B3zwyV5I"><img src="/pix/hamletsmill.jpg" title="Probably the worst book I've ever read 6 times."></a>
<img src="/pix/hamletsmill.jpg" title="Probably the worst book I've ever read 6 times.">
<a href="https://www.youtube.com/watch?v=KD-B3zwyV5I"><img src="/pix/hamletsmill.jpg" title="Probably the worst book I've ever read 6 times."></a>
<figure class="resright"><a href="https://www.youtube.com/watch?v=KD-B3zwyV5I"><img src="/pix/hamletsmill.jpg" title="Probably the worst book I've ever read 6 times."></a></figure>
<p></p>
<li>Freud, Sigmund – <dfn>Civilization and its Discontents</dfn> <span class="loc">(BF173.F682)</span></li>
Freud, Sigmund –
<dfn>Civilization and its Discontents</dfn>
<span class="loc">(BF173.F682)</span>
<li>Freud, Sigmund – <dfn>Civilization and its Discontents</dfn> <span class="loc">(BF173.F682)</span></li>
<li>Sugrue, Thomas – <dfn>The Story of Edgar Cayce: There Is a River</dfn> <span class="loc">(BF1027.C3)</span></li>
Sugrue, Thomas –
<dfn>The Story of Edgar Cayce: There Is a River</dfn>
<span class="loc">(BF1027.C3)</span>
<li>Sugrue, Thomas – <dfn>The Story of Edgar Cayce: There Is a River</dfn> <span class="loc">(BF1027.C3)</span></li>
<li>Kramer, Heinrich and Sprenger, James – <dfn>Malleus Maleficarum (The Hammer of the Witches)</dfn> <span class="loc">(BF1569.A2)</span></li>
<li>Fowden, Garth – <dfn>The Egyptian Hermes: A Historical Approach to the Late Pagan Mind</dfn> <span class="loc">(BF1591)</span></li>
<li>Evola, Julius – <dfn>The Hermetic Tradition: Symbols &amp; Teachings of the Royal Art</dfn> <span class="loc">(BF1611)</span></li>
<li>Three Initiates – <dfn>The Kybalion</dfn> <span class="loc">(BF1611)</span></li>
<li>Yates, Frances A. – <dfn>The Rosicrucian Enlightenment</dfn> <span class="loc">(BF1623.R7)</span></li>
<li>Slater, Lauren – <dfn>Opening Skinner's Box</dfn> <span class="loc">(BF198.7)</span></li>
<li>Jaynes, Julian – <dfn>The Origin of Consciousness in the Breakdown of the Bicamerial Mind</dfn> <span class="loc">(BF311)</span> <a href="https://notrelated.xyz/#01.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>
<li>Pinker, Steven – <dfn>Blank Slate</dfn> <span class="loc">(BF341)</span></li>
<li>Kahneman, Daniel – <dfn>Thinking, Fast and Slow</dfn> <span class="loc">(BF441)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>
<li>Gigerenzer, Gerd – <dfn>Rationality for Mortals: How People Cope With Uncertainty </dfn> <span class="loc">(BF442)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>
<li>Carnegie, Dale – <dfn>How to Win Friends &amp; Influence People</dfn> <span class="loc">(BF637.S8)</span></li>
<li>Skinner, B. F – <dfn>Beyond Freedom and Dignity</dfn> <span class="loc">(BF698.9.C8)</span></li>
<li>Miller, Alan S. and Kanazawa, Satoshi – <dfn>Why Beautiful People Have More Daughters</dfn> <span class="loc">(BF698.95)</span></li>
<li>Murphy, Gardener – <dfn>Psychological Thought from Pythagoras to Freud</dfn> <span class="loc">(BF81)</span></li>
<li>Rand, Ayn – <dfn>The Virtue of Selfishness</dfn> <span class="loc">(BJ1474)</span></li>
<li>Mencken, H.L. – <dfn>Treatise on Right and Wrong</dfn> <span class="loc">(BJ71)</span></li>
<li>Harris, Sam – <dfn>Free Will</dfn> <span class="loc">(BK1461)</span></li>
<li>De Santillana, Giorgio &amp; von Dechend, Hertha – <dfn>Hamlet's Mill: An Essay Investigating the Origins of Human Knowledge and Its Transmission Through Myth</dfn> <span class="loc">(BL304)</span> <a href="https://notrelated.xyz/#02.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>
<li>Frazer, James George – <dfn>The Golden Bough: The Roots of Religion and Folklore</dfn> <span class="loc">(BL310)</span></li>
<li>Narasimhan, Chakravarthi V. – <dfn>The Mahabharata: An English Version Based on Selected Verses</dfn> <span class="loc">(BL1138.22)</span></li>
<p></p>
<ul class="booklist">

<figure class="resright"><a href="https://www.youtube.com/watch?v=KD-B3zwyV5I"><img src="/pix/hamletsmill.jpg" title="Probably the worst book I've ever read 6 times."></a></figure>

<p></p><li>Freud, Sigmund – <dfn>Civilization and its Discontents</dfn> <span class="loc">(BF173.F682)</span></li>

<li>Sugrue, Thomas – <dfn>The Story of Edgar Cayce: There Is a River</dfn> <span class="loc">(BF1027.C3)</span></li>

<li>Kramer, Heinrich and Sprenger, James – <dfn>Malleus Maleficarum (The Hammer of the Witches)</dfn> <span class="loc">(BF1569.A2)</span></li>

<li>Fowden, Garth – <dfn>The Egyptian Hermes: A Historical Approach to the Late Pagan Mind</dfn> <span class="loc">(BF1591)</span></li>

<li>Evola, Julius – <dfn>The Hermetic Tradition: Symbols &amp; Teachings of the Royal Art</dfn> <span class="loc">(BF1611)</span></li>

<li>Three Initiates – <dfn>The Kybalion</dfn> <span class="loc">(BF1611)</span></li>

<li>Yates, Frances A. – <dfn>The Rosicrucian Enlightenment</dfn> <span class="loc">(BF1623.R7)</span></li>

<li>Slater, Lauren – <dfn>Opening Skinner's Box</dfn> <span class="loc">(BF198.7)</span></li>

<li>Jaynes, Julian – <dfn>The Origin of Consciousness in the Breakdown of the Bicamerial Mind</dfn> <span class="loc">(BF311)</span> <a href="https://notrelated.xyz/#01.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Pinker, Steven – <dfn>Blank Slate</dfn> <span class="loc">(BF341)</span></li>

<li>Kahneman, Daniel – <dfn>Thinking, Fast and Slow</dfn> <span class="loc">(BF441)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

li>Taleb, Nassim Nicholas – <dfn>Antifragile</dfn> <span class="loc">(Q375)</span></li>

li>Taleb, Nassim Nicholas – <dfn>The Black Swan</dfn> <span class="loc">(Q375)</span></li>

/ul>
h2 id="qa-mathematics">QA: Mathematics</h2>
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
