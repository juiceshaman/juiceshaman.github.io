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
	<link rel="canonical" href="https://lukesmith.xyz">
	<link rel="alternate" type="application/rss+xml" title="Luke's Webpage RSS" href="/index.xml">
	<link rel="stylesheet" type="text/css" href="/style.css">
	<link rel="icon" href="/favicon.ico">
	<meta name="description" content="This is a list of the books in my personal library. If you have any questions or want me to review any of them, email me (luke@lukesmith.xyz).
I haven't read every book here, nor do I own all the books I've read or like. I also don't necessarily like all the books I own.
Check out my podcast, Not Related! for some book reviews and other things. Books I've talked about in one way or another in the podcast will have a link to that episode.">
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
<p>This is a list of the books in my personal library. If you have any
questions or want me to review any of them, email me
(<a href="mailto:luke@lukesmith.xyz">luke@lukesmith.xyz</a>).</p>
<p>I haven't read every book here, nor do I own all the books I've read
or like. I also don't necessarily like all the books I own.</p>
<p>Check out <a href="https://notrelated.xyz">my podcast, <em>Not Related!</em></a>
for some book reviews and other things. Books I've talked about in one
way or another in the podcast will have a link to that episode.</p>
<h2 id="-lindypressnet-books">🆕 LindyPress.net Books</h2>
<p>Note that now I am reprinting out-of-print works at
<a href="https://lindypress.net">LindyPress.net</a>. You can buy any of these books
yourself if you'd like. (Most of them are pretty exclusive in that I'm
the only one reprinting them.)</p>
<ul>
<li>Pseudo-Aristotle – <a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a></li>
<li><a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a></li>
<li>Isidore of Seville – <a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a></li>
<li>Roger Bacon ‐ <a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a></li>
<li>Marcus Aurelius – <a href="https://lindypress.net/book?pk=2">Meditations</a></li>
<li><a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a></li>
</ul>
<p>(These are at the top since I don't know if anyone has given them Library of
Congress numbers, and I suppose as an ad.)</p>
<h2 id="a-bd-general-works-philosophy-logic-speculative-philosophy">A-BD: General Works, Philosophy, Logic, Speculative Philosophy</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hCVdCS0t46I"><img src="/pix/searle.jpg" title="Searle (actually literally) did nothing wrong."></a></figure>

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
<h2 id="bm-bx-specific-religions-and-theology">BM-BX: Specific Religions and Theology</h2>

<figure class="resright"><img src="/pix/biglot.jpg" title="A Greek and Latin biglottic Bible"></figure>

<ul class="booklist">
<li><dfn>'תְּהִלַּת ה</dfn> <span class="loc">(BM675/D3)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Key to Theosophy</dfn> <span class="loc">(BP561)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Voice of Silence</dfn> <span class="loc">(BP561)</span></li>

<li>Wright, Stuart – <dfn>Armageddon in Waco</dfn> <span class="loc">(BP605.B62)</span></li>

<li>Lewis, C. S. – <dfn>Mere Christianity</dfn> <span class="loc">(BR123)</span></li>

<li>Lewis, C. S. – <dfn>The Screwtape Letters</dfn> <span class="loc">(BR125)</span></li>

<li>Reardon, Patrick Henry – <dfn>Christ in the Psalms</dfn> <span class="loc">(BS1430.4)</span></li>

<li>Leithart, Peter J. – <dfn>Solomon Among the Postmoderns</dfn> <span class="loc">(BS1475.52)</span></li>

<li>Porter, J. R. – <dfn>The Lost Bible</dfn> <span class="loc">(BS1700)</span></li>

<li>Heiser, Michael – <dfn>Reversing Hermon: Enoch, the Watchers and the Forgotten Mission of Jesus Christ</dfn> <span class="loc">(BS1830.E7)</span></li>

<li><dfn>The New Oxford Annotated Bible</dfn> <span class="loc">(BS191.5.A1)</span></li>

<li><dfn>The New English Bible</dfn> <span class="loc">(BS192.A1)</span></li>

<li>Montano, Arias and Leudsen, Johann – <dfn>Greek-Latin Parallel New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>Pocket Interlinear New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>The New International Dictionary of New Testament Theology (3 Volumes)</dfn> <span class="loc">(BS2312)</span></li>

<li><dfn>Ἡ Καινὴ Διαθήκη</dfn> <span class="loc">(BS2312)</span></li>

<li>Kümmel, Werner Georg – <dfn>Introduction to the New Testament</dfn> <span class="loc">(BS2330)</span></li>

<li>Aland, Kurt – <dfn>Synopsis Quattuor Evangeliorum</dfn> <span class="loc">(BS2560.A2)</span></li>

<li>Mack. Burton L. – <dfn>A Myth of Innocence</dfn> <span class="loc">(BS2585.2)</span></li>

<li>Ehrman, Bart D. – <dfn>Lost Christianities: The Battles for Scriptures and the Faiths We Never Knew</dfn> <span class="loc">(BS2840.E4)</span></li>

<li>Luther, Martin – <dfn>Luther's Small Catechism with Additions Including the Augsburg Confession</dfn> <span class="loc">(BR331.K64)</span></li>

<li>Strong, James – <dfn>Strong's Exhaustive Concordance of the Bible with Hebrew and Greek Dictionaries</dfn> <span class="loc">(BS425)</span></li>

<li><dfn>Illustrated Dictionary and Concordance of the Bible</dfn> <span class="loc">(BS440)</span></li>

<li>McDowell, Josh – <dfn>The New Evidence that Demands a Verdict</dfn> <span class="loc">(BS480)</span></li>

<li>Laymon, Charles M. – <dfn>The Interpreter's One-Volume Commentary on the Bible</dfn> <span class="loc">(BS491.2)</span></li>

<li>Cross, John R. – <dfn>The Stranger on the Road to Emmaus</dfn> <span class="loc">(BS511.2)</span></li>

<li><dfn>Reader's Digest Mysteries of the Bible; the Enduring Questions of the Scriptures</dfn> <span class="loc">(BS538)</span></li>

<li>Smith, Brendan Powell – <dfn>The Brick Bible</dfn> <span class="loc">(BS550.3)</span></li>

<li>Kent, Paul and McLaughlan, David – <dfn>Know Your Bible: All 66 Books Explained and Applied</dfn> <span class="loc">(BS593)</span></li>

<li><dfn>Septuagint with Apocrypha</dfn> <span class="loc">(BS742)</span></li>

<li><dfn>Biblia Sacra Vulgata</dfn> <span class="loc">(BS75)</span></li>

<li>Newman, John Henry – <dfn>An Essay on the Development of Christian Doctrine</dfn> <span class="loc">(BT21)</span></li>

<li>Robinson, James M. – <dfn>The Nag Hammadi Library</dfn> <span class="loc">(BT1391)</span></li>

<li>Lewis, C. S. – <dfn>Surprised by Joy: The Shape of My Early Life</dfn> <span class="loc">(BV4935.L43)</span></li>

<li>Carman, Stephen L. and Owen, Bob – <dfn>Quest: The Story of an Aerospace Engineer who Challenged God to Prove Himself</dfn> <span class="loc">(BV4930)</span></li>

<li>Ware, Timothy – <dfn>The Orthodox Church</dfn> <span class="loc">(BX106)</span></li>

<li>Aveling, J. C. H. – <dfn>The Jesuits</dfn> <span class="loc">(BX3706.2)</span></li>

<li><dfn>The Book of Common Prayer</dfn> <span class="loc">(BX5145)</span></li>

<li><dfn>Five Great Encyclicals: Labor, Education, Marriage, Reconstructing the Social Order, Atheistic Communism</dfn> <span class="loc">(BX860)</span></li>

</ul>
<h2 id="c-auxiliary-sciences-of-history">C: Auxiliary Sciences of History</h2>
<ul class="booklist">
<li>Graeber, David and Wengrow, David – <dfn>The Dawn of Everything: A New History of Humanity</dfn> <span class="loc">(CB19)</span></li>

<li>McNeill, William H. – <dfn>The Rise of the West: A History of the Human Community</dfn> <span class="loc">(CB59)</span></li>

<li>Sitchin, Zecharia – <dfn>The 12th Planet</dfn> <span class="loc">(CB156)</span></li>

<li>Rohl, David – <dfn>The Lords of Avaris: Uncovering the Legendary Origins of Western Civilization</dfn> <span class="loc">(CB245)</span> <a href="https://notrelated.xyz/#02.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Casson, Lionel and Clairborne, Robert and Fagan, Brian and Karp, Walter – <dfn>Mysteries of the Past</dfn> <span class="loc">(CB311)</span></li>

<li>Fisher, Marshall John and Fisher, David E. – <dfn>Mysteries of Lost Empires</dfn> <span class="loc">(CB311)</span></li>

<li>Hawkes, Jacquetta – <dfn>The Atlas of Early Man</dfn> <span class="loc">(CB311)</span></li>

<li>Platt, Richard and Riddell, Chris – <dfn>Castle Diary</dfn> <span class="loc">(CB351)</span></li>

<li>Cahill, Thomas – <dfn>Mysteries of the Middle Ages</dfn> <span class="loc">(CB351)</span></li>

</ul>
<h2 id="d-world-history">D: World History</h2>

<figure class="resright"><img src="/pix/racehutton.jpg" title="Hutton's book on the Third Reich"></figure>

<ul class="booklist">
<li>Malesky, Kee – <dfn>All Facts Considered, the Essential Library of Inessential Knowledge</dfn> <span class="loc">(D10)</span></li>

<li>Evola, Julius – <dfn>Revolt Against the Modern World</dfn> <span class="loc">(D16.8)</span></li>

<li>Epstein, Steven A. – <dfn>An Economic and Social History of Later Medieval Europe, 1000-1500</dfn> <span class="loc">(D117)</span></li>

<li>Pirenne, Henri – <dfn>A History of Europe</dfn> <span class="loc">(D117)</span></li>

<li>Cantor, Nroman F. – <dfn>Medieval History: The Life and Death of a Civilization</dfn> <span class="loc">(D118)</span></li>

<li>Roberts, J. M. – <dfn>New History of the World</dfn> <span class="loc">(D20)</span></li>

<li>Mann, Charles C. – <dfn>1493, Uncovering the New World Columbus Created</dfn> <span class="loc">(D228)</span></li>

<li>Rogan, Eugene L. – <dfn>The FAll of the Ottomans: The Great War in the Middle East</dfn> <span class="loc">(D566)</span></li>

<li>Sanborn, Frederick R. – <dfn>Design for War: A Study of Secret Power Politics</dfn> <span class="loc">(D742.U5)</span></li>

<li>Cheyney, Edward P. – <dfn>A Short History of England</dfn> <span class="loc">(DA32)</span></li>

<li>Thomas, Charles – <dfn>Celtic Britain</dfn> <span class="loc">(DA140)</span></li>

<li>Sellar, W.C. &amp; Yeatman R.J. – <dfn>1066 and All That</dfn> <span class="loc">(DA33)</span></li>

<li>Freeman, John and Sharpe, Sue – <dfn>This Beautiful Land: Britain</dfn> <span class="loc">(DA632)</span></li>

<li>Hutton, Christopher – <dfn>Race and the Third Reich</dfn> <span class="loc">(DD253)</span></li>

<li>Tacitus, C. Cornellius – <dfn>Annales et Historiae</dfn> <span class="loc">(DG207.T3)</span></li>

<li>Shirer, William L. – <dfn>The Rise and Fall of the Third Reich</dfn> <span class="loc">(DD256.5)</span></li>

<li>MacDonald, Kevin – <dfn>The Culture of Critique: An Evolutionary Analysis of Jewish Involvement in Twentieth-Century Intellectual and Political Movements</dfn> <span class="loc">(DS143)</span></li>

<li>Ford, Henry Sr. – <dfn>The International Jew: The World's Foremost Problem</dfn> <span class="loc">(DS145)</span></li>

<li>Ali, Tariq – <dfn>The Duel: Pakistan on the Flight Path of American Power</dfn> <span class="loc">(DS384)</span></li>

<li>De Bary, William Theodore – <dfn>The Sources of Indian Tradition</dfn> <span class="loc">(DS423)</span></li>

<li>Keay, John – <dfn>India, A History</dfn> <span class="loc">(DS451)</span></li>

<li>Ebrey, Patricia Buckley – <dfn>Cambridge Illustrated History of China</dfn> <span class="loc">(DS706)</span></li>

<li>National Geographic Society – <dfn>Journey into China</dfn> <span class="loc">(DS712)</span></li>

</ul>
<h2 id="e-f-history-of-the-americas">E-F: History of the Americas</h2>

<figure class="resright"><img src="/pix/foxfire.jpg"></figure>

<ul class="booklist">
<li>Hancock, Graham – <dfn>America Before: The Key to Earth's Lost Civilization</dfn> <span class="loc">(E61)</span></li>

<li>Little, Gregory – <dfn>Path of Souls: The Native American Death Journey: Cygnus, Orion, the Milky Way, Giant Skeletons in Mounds, &amp; the Smithsonian</dfn> <span class="loc">(E98.M8)</span></li>

<li>Mooney, James – <dfn>Myths of the Cherokee</dfn> <span class="loc">(E99.C5)</span></li>

<li>Greenblatt, Stephen – <dfn>New World Encounters</dfn> <span class="loc">(E141)</span></li>

<li>Fischer, David Hackett – <dfn>Albion's Seed: Four British Folkways in America</dfn> <span class="loc">(E169.1)</span> <a href="https://notrelated.xyz/#01.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Sowell, Thomas – <dfn>Ethnic America</dfn> <span class="loc">(E184.A1)</span></li>

<li>Hurmence, Belinda – <dfn>Before Freedom: 48 Oral Histories of Former North and South Carolina Slaves</dfn> <span class="loc">(E444)</span></li>

<li>Adams, Nehemiah – <dfn>A South-side View of Slavery: or Three Months at the South in 1854</dfn> <span class="loc">(E449)</span></li>

<li>Parsons, Charles Grandison – <dfn>An Inside View of Slavery; or A Tour Among the Planters</dfn> <span class="loc">(E449)</span></li>

<li>Long, A. L. – <dfn>Memoirs of Robert E. Lee</dfn> <span class="loc">(E467.1.L4)</span></li>

<li>Henry, Robert Selph – <dfn>The Story of the Confederacy</dfn> <span class="loc">(E487)</span></li>

<li>Mann, Charles C. – <dfn>1491, New Revelations of the Americas Before Columbus</dfn> <span class="loc">(E61)</span></li>

<li>Wharton, H. M. – <dfn>War Songs and Poems of the Southern Confederacy, 1861-1865: a Collection of the Most Popular and Impressive Songs and Poems of War Times, Dear to Every Southern Heart</dfn> <span class="loc">(E647)</span></li>

<li><dfn>The Blue Book of the John Birch Society</dfn> <span class="loc">(E743.5)</span></li>

<li>Stormer, John A. – <dfn>The Death of a Nation</dfn> <span class="loc">(E743.5)</span></li>

<li>Ramo, Joshua Cooper – <dfn>The Age of the Unthinkable</dfn> <span class="loc">(E902)</span></li>

<li>de las Casas, Bartolomé – <dfn>Brevisima relación de la destrución de las Indias</dfn> <span class="loc">(F1411)</span></li>

<li><dfn>The Foxfire Book</dfn> <span class="loc">(F291.2)</span></li>

<li><dfn>The Foxfire Book 2</dfn> <span class="loc">(F291.2)</span></li>

</ul>
<h2 id="g-geography-anthropology-recreation">G: Geography, Anthropology, Recreation</h2>
<ul class="booklist">
<li>Winer, Richard – <dfn>Ghost Ships: True Stories of Nautical Nightmares, Hauntings, and Disasters</dfn> <span class="loc">(G525)</span></li>

<li><dfn>National Geographic Collegiate Atlas of the World</dfn> <span class="loc">(G1021)</span></li>

<li>Wells, Spencer – <dfn>Pandora's Seed: The Unforeseen Cost of Civilization</dfn> <span class="loc">(GF75)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cochran, Gregory and Harpending, Henry – <dfn>the 10,000 Explosion: How Civilization Accelerated Human Evolution</dfn> <span class="loc">(GN281.4)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cremo, Michael A. &amp; Thompson, Ricahrd L. – <dfn>Forbidden Archaeology: The Hidden History of the Human Race</dfn> <span class="loc">(GN741)</span></li>

<li>Hancock, Graham – <dfn>Magicians of the Gods: The Forgotten Wisdom of Earth's Lost Civilization</dfn> <span class="loc">(GN751)</span></li>

<li>Cayce, Hugh Lynn – <dfn>Edgar Cayce on Atlantis</dfn> <span class="loc">(GN751.C35)</span></li>

<li>Marshack, Alexander – <dfn>The Roots of Civilization: The Cognitive Beginnings of Man's First Art, Symbol and Notation</dfn> <span class="loc">(GN772)</span></li>

<li>Bord, Janet and Bord, Colin – <dfn>Prehistoric Britain from the Air</dfn> <span class="loc">(GN805)</span></li>

<li>Bruce, Annette J. – <dfn>More Tellable Cracker Tales</dfn> <span class="loc">(GR110.F5)</span></li>

</ul>
<h2 id="h-social-sciences">H: Social Sciences</h2>
<p>
</p><figure class="resright"><img src="/pix/democracy.jpg"></figure>


<figure class="resright"><img src="/pix/pike.jpg"></figure>
<p></p>
<ul class="booklist">
<li>Greenspan, Alan – <dfn>The Age of Turbulence</dfn> <span class="loc">(HB119.G74)</span></li>

<li>Hazlitt, Hentry – <dfn>Economics in One Lesson (two copies)</dfn> <span class="loc">(HB171)</span></li>

<li>Keynes, John Maynard – <dfn>The General Theory of Employment, Interest and Money</dfn> <span class="loc">(HB171)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Rothbard, Murray – <dfn>Man, Economy and State with Power and Market</dfn> <span class="loc">(HB171)</span></li>

<li>von Mises, Ludwig – <dfn>Economic Policy</dfn> <span class="loc">(HB171)</span></li>

<li>Boulding, Kenneth E. – <dfn>Economic Analysis</dfn> <span class="loc">(HB171.5)</span></li>

<li>Goodman, Kennard E. and Moore, William L. – <dfn>Economics in Everyday Life</dfn> <span class="loc">(HB171.5)</span></li>

<li>Pindyck, Robert S. and Rubinfeld, Daniel L. – <dfn>Microeconomics</dfn> <span class="loc">(HB172)</span></li>

<li>Fisher, David Hackett – <dfn>The Great Wave: Price Revolutions and the Rhythm of History</dfn> <span class="loc">(HB231)</span></li>

<li>Soros, George – <dfn>The Crash of 2008 and What It Means</dfn> <span class="loc">(HB3722)</span> <a href="https://notrelated.xyz/#02.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Keen, Steve – <dfn>Debunking Economics: The Naked Emperor Dethroned?</dfn> <span class="loc">(HB71)</span></li>

<li>Krugman, Paul – <dfn>The Accidental Theorist</dfn> <span class="loc">(HB74.5)</span></li>

<li>Hoppe, Hans Hermann – <dfn>Democracy: The God That Failed: The Economics and Politics of Monarchy, Democracy and Natural Law</dfn> <span class="loc">(HB74.P65)</span></li>

<li>Ekelund, Robert B. Jr. and Hébert, Robert F – <dfn>A History of Economic Theory and Method</dfn> <span class="loc">(HB75)</span></li>

<li>Buchholz, Todd G. – <dfn>New Ideas from Dead Economists, an Introduction to Modern Economic Thought</dfn> <span class="loc">(HB76)</span></li>

<li>Heilbroner, Robert L. – <dfn>The Worldly Philosophers</dfn> <span class="loc">(HB76)</span></li>

<li>Paul Erlich – <dfn>The Population Bomb</dfn> <span class="loc">(HB875.E35)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Palmer, Tom G. – <dfn>After the Welfare State</dfn> <span class="loc">(HB99.3)</span></li>

<li>Krugman, Paul – <dfn>Peddling Prosperity</dfn> <span class="loc">(HB99.7)</span></li>

<li>Walton, Gary M. and Rockoff, Hugh – <dfn>History of the American Economy</dfn> <span class="loc">(HC103)</span></li>

<li>Krugman, Paul – <dfn>The Great Unravelling</dfn> <span class="loc">(HC106)</span></li>

<li>Krugman, Paul – <dfn>The Conscience of a Liberal</dfn> <span class="loc">(HC110.I5)</span></li>

<li>Clark, Gregory – <dfn>A Farewell to Alms</dfn> <span class="loc">(HC21)</span></li>

<li>Easterly, William – <dfn>The Elusive Quest for Growth</dfn> <span class="loc">(HC59.72.P6)</span></li>

<li>Simon, Julian L. and Kahn, Herman – <dfn>The Resourceful Earth</dfn> <span class="loc">(HC59.R445)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Dixit, Avinash K. and Nalebuff, Barry J. – <dfn>Thinking Strategically, The Competitive Edge in Business, Politics, and Everyday Life</dfn> <span class="loc">(HD30.28)</span></li>

<li>Adams, Scott – <dfn>The Dilbert Principle</dfn> <span class="loc">(HD31)</span></li>

<li>Ehrenreich, Barbara – <dfn>Nickel and Dimed</dfn> <span class="loc">(HD4918)</span></li>

<li>Thiel, Peter – <dfn>Zero to One: Notes on Start-Ups, or How to Build the Future</dfn> <span class="loc">(HD62.5)</span></li>

<li>Montgomery, David – <dfn>Beyond Equality: Labor and the Radical Republicans 1862-1872</dfn> <span class="loc">(HD8076)</span></li>

<li>Caplan, Bryan – <dfn>The Myth of the Rational Voter: Why Democracies Choose Bad Policies</dfn> <span class="loc">(HD87)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bhagwati, Jagdish – <dfn>In Defense of Globalization</dfn> <span class="loc">(HF1359)</span></li>

<li>Krugman, Paul and Obstfield, Maurice – <dfn>International Economics</dfn> <span class="loc">(HF1359)</span></li>

<li>Lechner, Frank J. and Boli, John – <dfn>The Globalization Reader</dfn> <span class="loc">(HF1359)</span></li>

<li>Myrdal, Gunnar – <dfn>Beyond the Welfare State</dfn> <span class="loc">(HF1411)</span></li>

<li>Graeber, David – <dfn>Bullshit Jobs: A Theory</dfn> <span class="loc">(HF5549.5.J63)</span> <a href="https://notrelated.xyz/#02.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Soros, George – <dfn>In Defense of Open Society</dfn> <span class="loc">(HG172.S63)</span></li>

<li>Boortz, Neal and Linder, John – <dfn>The Fairtax Book: Saying Goodbye to the Income Tax and the IRS</dfn> <span class="loc">(HJ4652)</span></li>

<li>Stove, David – <dfn>Darwinian Fairytales</dfn> <span class="loc">(HM106)</span></li>

<li>O'Brien, Jodi – <dfn>The Production of Reality</dfn> <span class="loc">(HM1033)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Skin in the Game</dfn> <span class="loc">(HM1101)</span></li>

<li>Berne, Eric – <dfn>Games People Play</dfn> <span class="loc">(HM1106)</span></li>

<li>Pinker, Steven – <dfn>The Better Angels of Our Nature</dfn> <span class="loc">(HM1116)</span></li>

<li>Kropotkin, Peter – <dfn>Mutual Aid: A Factor of Evolution</dfn> <span class="loc">(HM131)</span></li>

<li>Diamond, Jared – <dfn>Guns, Germs and Steel</dfn> <span class="loc">(HM206)</span></li>

<li>Bork, Robert H. – <dfn>Slouching Towards Gomorrah: Modern Liberalism and American Decline</dfn> <span class="loc">(HN59.2)</span></li>

<li>Arnold, Matthew – <dfn>Culture and Anarchy</dfn> <span class="loc">(HN389)</span></li>

<li>Jones, E. Michael – <dfn>Libido Dominandi: Sexual Liberation and Political Control</dfn> <span class="loc">(HQ472.U6)</span></li>

<li>Eisler, Riane – <dfn>The Chalice and the Blade, Our History, Our Future</dfn> <span class="loc">(HQ1075)</span></li>

<li>Harris, Judith Rich – <dfn>The Nurture Assumption</dfn> <span class="loc">(HQ772)</span></li>

<li>Beuerlein, Mark – <dfn>The Dumbest Generation</dfn> <span class="loc">(HQ799.7)</span></li>

<li>Street, Oliver Day – <dfn>Symbolism of the Three Degrees</dfn> <span class="loc">(HS425)</span></li>

<li><dfn>Morals and Dogma of the Ancient and Accepted Scottish Rite of Freemasonry</dfn> <span class="loc">(HS767)</span></li>

<li><dfn>The 9/11 Commission Report: Final Report of the National Commission on Terrorist Attacks upon the United States</dfn> <span class="loc">(HV6432.7)</span></li>

<li>Engels, Frederick – <dfn>Socialism: Utopian and Scientific</dfn> <span class="loc">(HX276)</span></li>

<li>Hayek, F. A. – <dfn>The Intellectuals and Socialism</dfn> <span class="loc">(HX528)</span></li>

<li>More, Thomas – <dfn>Utopia</dfn> <span class="loc">(HX810.5)</span></li>

<li>Stringham, Edward P. – <dfn>Anarchy and the Law</dfn> <span class="loc">(HX833)</span></li>

<li>Schumpeter, Joseph Alois – <dfn>Capitalism, Socialism and Democracy</dfn> <span class="loc">(HX86)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bastiat, Frederic – <dfn>The Law</dfn> <span class="loc">(HX87)</span></li>

</ul>
<h2 id="j-k-political-science-and-law">J-K: Political Science and Law</h2>

<figure class="resright"><img src="/pix/archeofuturism.jpg"></figure>

<ul class="booklist">
<li>Faye, Guillaume – <dfn>Archeofuturism: European Visions of the Post-Catastrophic Age</dfn> <span class="loc">(JA84.F8)</span></li>

<li>Plato – <dfn>The Republic</dfn> <span class="loc">(JC71)</span></li>

<li>Machiavelli, Niccolò – <dfn>The Prince and Other Writings</dfn> <span class="loc">(JC143)</span></li>

<li>Hobbes, Thomas – <dfn>Leviathan</dfn> <span class="loc">(JC153)</span></li>

<li>Filmer, Robert – <dfn>Patriarcha, or, The Natural Power of Kings</dfn> <span class="loc">(JC153.F48)</span></li>

<li>Samons, Loren J. – <dfn>What's Wrong with Democracy?</dfn> <span class="loc">(JC421)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Mill, John Stewart – <dfn>On Liberty</dfn> <span class="loc">(JC585)</span></li>

<li>Reed, Lawrence W. – <dfn>Are We Good Enough for Liberty?</dfn> <span class="loc">(JC585)</span></li>

<li>Jeffery, – <dfn>People's War: New Light on the Struggle for South Africa</dfn> <span class="loc">(JQ1998.A4)</span></li>

<li>Beard, Charles – <dfn>An Economic Interpretation of the Constitution of the United States</dfn> <span class="loc">(JK146)</span></li>

<li>Smith, Bradley A. – <dfn>Unfree Speech: The Folly of Campaign Finance Reform</dfn> <span class="loc">(JK1991)</span></li>

<li>de Tocqueville, Alexis – <dfn>Democracy in America</dfn> <span class="loc">(JK216)</span></li>

<li>Brimelow, Peter – <dfn>Alien Nation: Common Sense about America's Immigration Disaster</dfn> <span class="loc">(JV6493)</span></li>

<li>Fukuyama, Francis – <dfn>America at the Crossroads: Democracy, Power and Neoconservative Legacy</dfn> <span class="loc">(JZ1480)</span></li>

<li>Silverglate, Harvey A. and French, David A. and Lukianoff, Greg – <dfn>FIRE's Guide to Free Speech on Campus</dfn> <span class="loc">(KF4123.5)</span></li>

<li>Bernstein, David E. – <dfn>You Can't Say That!</dfn> <span class="loc">(KF4749)</span></li>

</ul>
<h2 id="l-n-education-music-fine-arts">L-N: Education, Music, Fine Arts</h2>
<ul class="booklist">
<li>Bloom, Allan – <dfn>The Closing of the American Mind: How Higher Education Has Failed Democracy and Impoverished the Souls of Today's Students</dfn> <span class="loc">(LA227.3)</span></li>

<li>Russell, Bertrand – <dfn>Education and the Good Life</dfn> <span class="loc">(LB775)</span></li>

<li><dfn>Baptist Hymnal</dfn> <span class="loc">(M2122)</span></li>

<li>Towner, D. B., Lorenz, E. S. and Wilson, Ira B. – <dfn>Songs of Praise: A Collection of Gospel Songs for Men's Voices</dfn> <span class="loc">(M2198)</span></li>

<li>International Graphic Society – <dfn>The Arts of Mankind: Painting, Architecture, Music</dfn> <span class="loc">(N5302)</span></li>

<li>Barral i Altet, Xavier – <dfn>The Early Middle Ages: From Late Antiquity to A.D. 1000</dfn> <span class="loc">(NA350)</span></li>

<li>Churchill, Winston S. – <dfn>Painting as a Pastime: An instructive and inspiring invitation to the joy of painting</dfn> <span class="loc">(ND1142)</span></li>

<li>Cornelius, Maurits – <dfn>The Graphic Work of M.C. Escher</dfn> <span class="loc">(NE670.E75)</span></li>

</ul>
<h2 id="p-philology-linguistics">P: Philology, Linguistics</h2>

<figure class="resright"><img src="/pix/westernclassical.jpg" title="Good for learning some #Lindy linguistics"></figure>

<ul class="booklist">
<li>Smith, Luke – <dfn>External Possession and the Undisentanglability of Syntax and Semantics</dfn></li>

<li>Chomsky, Noam – <dfn>Language and Mind</dfn> <span class="loc">(P106)</span></li>

<li>Harris, Roy – <dfn>Language, Saussure and Wittgenstein, How to Play Games with Words</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>Words and Rules, the Ingredients of Language</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>The Stuff of Thought</dfn> <span class="loc">(P107)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: I Linguistic Theory: Foundations</dfn> <span class="loc">(P121)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: II Linguistics Theory: Extensions and Implications</dfn> <span class="loc">(P121)</span></li>

<li>Ohio State University – <dfn>Language Files 11</dfn> <span class="loc">(P121)</span></li>

<li>Chomsky, Noam – <dfn>The Logical Structure of Linguistic Theory</dfn> <span class="loc">(P158)</span></li>

<li>Falk, Yehuda N. – <dfn>Lexical-Functional Grammar, An Introduction to Parallel Constraint-Based Syntax</dfn> <span class="loc">(P158.25)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Chomsky's Minimalism</dfn> <span class="loc">(P158.28)</span></li>

<li>Gutiérrez, Bravo and Arellanes Arellanes, Francisco and Peón Herrero, Mario Ernesto Chávez – <dfn>Nuevos estudios de Teoría de la Optimalidad</dfn> <span class="loc">(P158.42)</span></li>

<li>Richards, Norvin – <dfn>Contiguity Theory</dfn> <span class="loc">(P224.R43)</span></li>

<li>Bresnan, Joan and Asudeh, Ash and Tolivonen, Ida and Wechsler, Stephen – <dfn>Lexical-Functional Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Chomsky, Noam – <dfn>Aspects of the Theory of Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Freidin, Robert – <dfn>Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Saeed, John I. – <dfn>Semantics</dfn> <span class="loc">(P325)</span></li>

<li>Dalby, Andrew – <dfn>Dictionary of Languages, the Definitive Reference to More than 400 Languages</dfn> <span class="loc">(P371)</span></li>

<li>Allan, Keith – <dfn>The Western Classical Tradition in Linguistics</dfn> <span class="loc">(P61)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Western Linguistics: An Historical Introduction</dfn> <span class="loc">(P61)</span></li>

<li>Klein, Jared – <dfn>An Indo-European Chrestomathy</dfn></li>

<li>Watkins, Calvert – <dfn>The American Heritage Dictionary of Indo-European Roots</dfn> <span class="loc">(P615)</span></li>

<li>Sampson, Geoff – <dfn>Schools of Linguistics</dfn> <span class="loc">(P77)</span></li>

<li>Harris, Randy Allen – <dfn>The Linguistics Wars</dfn> <span class="loc">(P85.C47)</span></li>

<li>Cutting, Joan – <dfn>Pragmatics and Discourse</dfn> <span class="loc">(P99.4.P72)</span></li>

</ul>
<h2 id="pa-greek-and-latin-language-and-literature">PA: Greek and Latin language and Literature</h2>

<figure class="resright"><img src="/pix/hughes.jpg" title="These are actually pretty good and readable English translations."></figure>

<ul class="booklist">
<li>Morrison, Clinton and Barnes, David H. – <dfn>New Testament Word Lists</dfn> <span class="loc">(PA881)</span></li>

<li>Magoffin, Ralph van Deman and Henry, Margaret Young – <dfn>Latin First Year</dfn> <span class="loc">(PA2087)</span></li>

<li>Wheelock, Frederic M. – <dfn>Latin, an Introductory Course Based on Ancient Authors</dfn> <span class="loc">(PA2087.5)</span></li>

<li>Orberg, Hans H – <dfn>Roma Aeterna</dfn> <span class="loc">(PA2094.5)</span></li>

<li>Orberg, Hans H – <dfn>Colloquium Personarum</dfn> <span class="loc">(PA2095)</span></li>

<li>Orberg, Hans H – <dfn>Lingua Latina</dfn> <span class="loc">(PA2095)</span></li>

<li>Simpson, D. P. – <dfn>Cassell's Latin Dictionary</dfn> <span class="loc">(PA2365.E5)</span></li>

<li>Landis, Paul – <dfn>Four Famous Greek Plays</dfn> <span class="loc">(PA3626.A2)</span></li>

<li>Aeschylus – <dfn>The Oresteia</dfn> <span class="loc">(PA3827.A7)</span></li>

<li>Apollonius of Rhodes – <dfn>Jason and the Argonauts (Argonautica)</dfn> <span class="loc">(PA3872)</span></li>

<li>Euripides – <dfn>Three Plays of Euripides: Alcestis, Medea, the Bacchae</dfn> <span class="loc">(PA3975)</span></li>

<li>Euripides – <dfn>Alcestis and Other Plays</dfn> <span class="loc">(PA3975.A5)</span></li>

<li>Corpus Hermeticum – <dfn>Hermes Trismegistus</dfn> <span class="loc">(PA3998)</span></li>

<li>Homer – <dfn>The Iliad</dfn> <span class="loc">(PA4025.A2)</span></li>

<li>Homer – <dfn>The Odyssey</dfn> <span class="loc">(PA4025.A5)</span></li>

<li>Sophocles – <dfn>The Theban Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>The Complete Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>Electra and Other Plays</dfn> <span class="loc">(PA4414.A2)</span></li>

<li>Feyerabend, Karl – <dfn>Greek-English Dictionary</dfn> <span class="loc">(PA445.E5)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Liddell, H. G. and Scott – <dfn>Greek-English Lexicon</dfn> <span class="loc">(PA445.E5)</span></li>

<li>Juvenal – <dfn>The Sixteen Satires</dfn> <span class="loc">(PA6447.E5)</span></li>

<li>Lucretius – <dfn>On the Nature of Things</dfn> <span class="loc">(PA6483.E5)</span></li>

<li>Hughes, Ted – <dfn>Tales from Ovid: Twenty-Four Passages from the 'Metamorphoses' by Ovid</dfn> <span class="loc">(PA6522)</span></li>

<li>Petronius – <dfn>the Satyricon and the Fragments</dfn> <span class="loc">(PA6558.E5)</span></li>

<li>Pliny the Younger – <dfn>Pliny: A Self-Portrait in Letters</dfn> <span class="loc">(PA6639.E5)</span></li>

<li>Virgil – <dfn>Aeneid</dfn> <span class="loc">(PA6807.A5)</span></li>

<li>Virgil – <dfn>The Pastoral Poems</dfn> <span class="loc">(PA6807.B7)</span></li>

</ul>
<h2 id="pc-romance-languages">PC: Romance Languages</h2>

<figure class="resright"><img src="/pix/lathrop.jpg" title="Lathrop's Course on Historical Spanish"></figure>

<ul class="booklist">
<li>Decker, Henry W. and Bernhard, Francoise – <dfn>Modern French</dfn> <span class="loc">(PC211)</span></li>

<li>Azevedo, Milton M. – <dfn>Introducción a la Lingüística Española</dfn> <span class="loc">(PC4073)</span></li>

<li>Lathrop, T. A. and Gutiérrex Cuadrado, Juan – <dfn>Curso de gramática histórica española</dfn> <span class="loc">(PC4101)</span></li>

<li>Moreno, Oscar – <dfn>Gramática avanzada del español</dfn> <span class="loc">(PC4129.E5)</span></li>

<li>Cash, Annette G. and Murray, James C. – <dfn>Teoría y técnicas de traduccón: primeras etapas</dfn> <span class="loc">(PC4498)</span></li>

<li>Gili Gaya, Samuel – <dfn>Vox: Diccionario abreviado de la lengua española</dfn> <span class="loc">(PC4625)</span></li>

</ul>
<h2 id="pd-pf-germanic-languages-and-literatures">PD-PF: Germanic Languages and Literatures</h2>
<ul class="booklist">
<li>Lambdin, Thomas O. – <dfn>An Introduction to the Gothic Language</dfn> <span class="loc">(PD1123)</span></li>

<li>Hugo – <dfn>Swedish Phrase Book</dfn> <span class="loc">(PD5121)</span></li>

<li>Warriner, John E. and Whitten, Mary E. and Friggith, Francis J. – <dfn>Warriner's English Grammar and Composition</dfn> <span class="loc">(PE1112)</span></li>

<li>Elson, William H. and Keck, Christine – <dfn>Elson Grammar School Literature Book Two</dfn> <span class="loc">(PE1121)</span></li>

<li>Mitchell, Brucew and Robinson, Fred C. – <dfn>A Guide to Old English</dfn> <span class="loc">(PE131)</span></li>

<li>Evans, Jonathan – <dfn>An Introduction to Old English</dfn> <span class="loc">(PE135)</span></li>

<li>Bright, James W. – <dfn>Bright's Anglo-Saxon Reader</dfn> <span class="loc">(PE137)</span></li>

<li>Gottschalk, Katherine and Keith Hjortshoj – <dfn>The Elements of Teaching Writing</dfn> <span class="loc">(PE1404)</span></li>

<li>Forsyth, Mark – <dfn>The Elements of Eloquence</dfn> <span class="loc">(PE1421)</span></li>

<li>McCloskey, Deirdre N. – <dfn>Economical Writing</dfn> <span class="loc">(PE1479.E35)</span></li>

<li>Sharp, Stanley Louis and Strothmann, Friedrich Wilhelm – <dfn>German Reading Grammar</dfn> <span class="loc">(PF3111)</span></li>

<li>Morgan, Baynard Quincy and Strothmann, Friedrich Wilhelm – <dfn>Reading German</dfn> <span class="loc">(PF3117)</span></li>

<li>Berlitz – <dfn>Berlitz Self-Teaching German</dfn> <span class="loc">(PF3121)</span></li>

</ul>
<h2 id="pj-pl-oriental-indo-iranian-east-asian-and-oceanian-languages">PJ-PL: Oriental, Indo-Iranian, East-Asian and Oceanian Languages</h2>

<figure class="resright"><img src="/pix/sastry.jpg" title="Sanskrit in the Development of World Thought"></figure>

<ul class="booklist">
<li>Anonymous – <dfn>The Epic of Gilgamesh</dfn> <span class="loc">(PJ3771.G5)</span></li>

<li>Wightwick, Jane and Gaafar, Mahmoud – <dfn>Mastering Arabic</dfn> <span class="loc">(PJ6307)</span></li>

<li>Luxenberg, Christoph – <dfn>The Syro-Aramaic Reading of the Koran: A Contribution to Decoding the Language of the Koran</dfn> <span class="loc">(PJ6696)</span></li>

<li>Burnell, Arthur Coke – <dfn>On the Aindra school of Sanskrit grammarians, their place in the Sanskrit and subordinate literatures</dfn> <span class="loc">(PK407)</span></li>

<li>Sastry, Vempaty Kutumba – <dfn>Sanskrit and Development of World Thought</dfn> <span class="loc">(PK423)</span></li>

<li>Elwell-Sutton, L. P. – <dfn>Elementary Persian Grammar</dfn> <span class="loc">(PK6235)</span></li>

<li>Whitney, William Dwight – <dfn>A Sanskrit Grammar: Including Both the Classical Language, and the Older Dialects, of the Veda and Brahmana</dfn> <span class="loc">(PK663)</span></li>

<li>Sutherland, Goldman – <dfn>Devavanipravesika</dfn> <span class="loc">(PK666)</span></li>

<li>Whitney, William Dwight – <dfn>The Roots, Verb-Forms, And Primary Derivatives of the Sankstrit Language: A Supplement to his Sanskrit Grammar</dfn> <span class="loc">(PK745)</span></li>

<li>DeFrancis, John – <dfn>Intermediate Chinese</dfn> <span class="loc">(PL11117)</span></li>

<li>DeFrancis, John – <dfn>Advanced Chinese</dfn> <span class="loc">(PL1121.C5)</span></li>

<li>Defense Language Institute – <dfn>Chinese: Basic Course</dfn> <span class="loc">(PL1125)</span></li>

<li>Seligman, Scott D. – <dfn>Mandarin Chinese at a Glance</dfn> <span class="loc">(PL1125.E6)</span></li>

<li>DeFrancis, John – <dfn>The Chinese Language, Fact and Fantasy</dfn> <span class="loc">(PL1171)</span></li>

<li><dfn>Oxford Chinese Dictionary</dfn> <span class="loc">(PL1455)</span></li>

<li>Waley, Arthur – <dfn>Translations from the Chinese</dfn> <span class="loc">(PL3277.E3)</span></li>

<li>Burlington, Scott – <dfn>Instant Hawaiian</dfn> <span class="loc">(PL6445)</span></li>

<li>Pukui, Mary Kawena and Elbert, Samuel H. and Mookini, Esther T. – <dfn>The Pocket Hawaiian Dictionary</dfn> <span class="loc">(PL6446)</span></li>

</ul>
<h2 id="pn-general-literature">PN: General Literature</h2>
<ul class="booklist">
<li>Butterworth, Hezekiah – <dfn>The Story of America</dfn> <span class="loc">(PN1009.A1)</span></li>

<li>Kaplar, Richard T. and Patrick D. Maines – <dfn>The Government Factor: Undermining Journalistic Ethics in the Information Age</dfn> <span class="loc">(PN4888.E8)</span></li>

<li>Schwarz, Leo W. – <dfn>Feast of Leviathan: Tales of Adventure, Faith and Love from Jewish Literature</dfn> <span class="loc">(PN6071.J5)</span></li>

<li><dfn>Treasury of Familiar Quotations</dfn> <span class="loc">(PN6081)</span></li>

<li><dfn>Reader's Digest Treasury of American Humor</dfn> <span class="loc">(PN6162)</span></li>

<li>The Onion – <dfn>Dispatches from the Tenth Circle</dfn> <span class="loc">(PN6165)</span></li>

<li>The Onion – <dfn>Our Dumb World</dfn> <span class="loc">(PN6231.A74)</span></li>

<li>Raymond, Eric S. – <dfn>The New Hacker's Dictionary</dfn> <span class="loc">(PN6231.E4)</span></li>

<li>The Onion – <dfn>Our Dumb Century</dfn> <span class="loc">(PN6231.N6)</span></li>

<li>Gómez Dávila, Nicolás – <dfn>Escolios a un texto implícito</dfn> <span class="loc">(PN6275)</span></li>

<li>Brown, Jeffrey – <dfn>Darth Vader and Son</dfn> <span class="loc">(PN6727.B7575)</span></li>

<li>Watterson, Bill – <dfn>Calvin and Hobbes: Scientific Progress Goes 'Boink'</dfn> <span class="loc">(PN6728.C34)</span></li>

<li>Lewis, C. S. – <dfn>The Discarded Image: An Introduction to Medieval and Renaissance Literature</dfn> <span class="loc">(PN671)</span></li>

</ul>
<h2 id="pq-romance-literature">PQ: Romance Literature</h2>

<figure class="resright"><img src="/pix/inferno.jpg"></figure>

<ul class="booklist">
<li>de Montaigne, Michel – <dfn>Montaigne Selected Essays</dfn> <span class="loc">(PQ1642.E6)</span></li>

<li>Morlière, Jean-Baptiste – <dfn>Tartuffe and Other Plays</dfn> <span class="loc">(PQ1842)</span></li>

<li>De Saint-Exupéry – <dfn>Sazadeo Qickek</dfn> <span class="loc">(PQ2637.A274)</span></li>

<li>Alighieri, Dante – <dfn>The Divine Comedy</dfn> <span class="loc">(PQ4315)</span></li>

<li>Alighieri, Dante – <dfn>The Inferno</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Alighieri, Dante – <dfn>I: Hell (Sayers translation)</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Eco, Umberto – <dfn>Foucault's Pendulum</dfn> <span class="loc">(PQ4864.C6)</span></li>

<li>De la Vega, Garcilaso – <dfn>Poesías</dfn> <span class="loc">(PQ6391)</span></li>

<li>Garcia Lorca, Federico – <dfn>Rosita la soltera</dfn> <span class="loc">(PQ6613.A763)</span></li>

<li>Pérez-Reverte, Arturo – <dfn>La tabla de Flandés</dfn> <span class="loc">(PQ6666.E765)</span></li>

<li>Rulfo, Juan &amp;ndash; Pedro – <dfn>y El Llano en llamas</dfn> <span class="loc">(PQ7297.R89)</span></li>

</ul>
<h2 id="pr-english-literature">PR: English Literature</h2>
<ul class="booklist">
<li>Clark, Thomas Curtis and Gillespie, Esther A. – <dfn>1000 Quotable Poems</dfn> <span class="loc">(PR1175)</span></li>

<li><dfn>Beowulf</dfn> <span class="loc">(PR1583)</span></li>

<li>Chaucer, Geoffrey – <dfn>Chaucer's Major Poetry</dfn> <span class="loc">(PR1851)</span></li>

<li>Chaucer, Geoffrey – <dfn>The Canterbury Tales</dfn> <span class="loc">(PR1870.A1)</span></li>

<li>Collis, Louise – <dfn>Memoirs of a Medieval Woman</dfn> <span class="loc">(PR2007)</span></li>

<li>Malory, Thomas – <dfn>Le Morte d'Arthur</dfn> <span class="loc">(PR2041)</span></li>

<li>Craig, W. J. – <dfn>The Complete Works of William Shakespeare</dfn> <span class="loc">(PR2753.C8)</span></li>

<li>Shakespeare, William – <dfn>Hamlet (2 copies)</dfn> <span class="loc">(PR2801.A2)</span></li>

<li>Shakespeare, William – <dfn>Macbeth</dfn> <span class="loc">(PR2823.A2)</span></li>

<li>Shakespeare, William – <dfn>A Midsummer Night's Dream</dfn> <span class="loc">(PR2827.A2)</span></li>

<li>Shakespeare, William – <dfn>The Merchant of Venice</dfn> <span class="loc">(PR2825.A2)</span></li>

<li>Shakespeare, William – <dfn>The Sonnets</dfn> <span class="loc">(PR2848.A2)</span></li>

<li>Crystal, David – <dfn>The Oxford Dictionary of Original Shakespearean Pronunciation</dfn> <span class="loc">(PR2892)</span></li>

<li>Bunyan, John – <dfn>Pilgrim's Progress</dfn> <span class="loc">(PR3330)</span></li>

<li>Milton, John – <dfn>Paradise Lost and Other Poems</dfn> <span class="loc">(PR3560)</span></li>

<li>Coleridge, Samuel Taylor – <dfn>The Rime of the Ancient Mariner</dfn> <span class="loc">(PR4479)</span></li>

<li>Dickens, Charles – <dfn>Great Expectations</dfn> <span class="loc">(PR4560)</span></li>

<li>Shaw, George Bernard – <dfn>Pygmalion</dfn> <span class="loc">(PR5363)</span></li>

<li>Stevenson, Robert Louis – <dfn>The Black Arrow</dfn> <span class="loc">(PR5484)</span></li>

<li>Stevenson, Robert Louis – <dfn>New Arabian Nights</dfn> <span class="loc">(PR5484)</span></li>

<li>Wells, H. G. – <dfn>The Island of Dr. Moreau</dfn> <span class="loc">(PR5774)</span></li>

<li>Wilde, Oscar – <dfn>The Importance of Being Earnest</dfn> <span class="loc">(PR5818)</span></li>

<li>Christie, Agatha – <dfn>Death on the Nile</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Christie, Agatha – <dfn>The Nursery Rhyme Murders</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Golding, William – <dfn>Lord of the Flies</dfn> <span class="loc">(PR6013.O35)</span></li>

<li>Lewis, C. S. – <dfn>The Lion, the Witch and the Wardrobe</dfn> <span class="loc">(PR6023.E926)</span></li>

<li>Huxley, Aldous – <dfn>Brave New World</dfn> <span class="loc">(PR6015.U9)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Lord of the Rings, One-Volume Edition</dfn> <span class="loc">(PR6039.O32)</span></li>

<li>White, T. H. – <dfn>The Once and Future King</dfn> <span class="loc">(PR6045.H2)</span></li>

<li>Adams, Douglas – <dfn>Life, the Universe and Everything</dfn> <span class="loc">(PR6051.D3352)</span></li>

<li>Erickson, Paul – <dfn>Doctor Who: The Ark</dfn> <span class="loc">(PR6052.R449)</span></li>

<li>Burgess, Anthony – <dfn>A Clockwork Orange</dfn> <span class="loc">(PR6052.U638)</span></li>

<li>Grimwade, Peter – <dfn>Doctor Who: Planet of Fire</dfn> <span class="loc">(PR6057.R545)</span></li>

<li>Halleck, Reuben Post – <dfn>History of English Literature</dfn> <span class="loc">(PR85)</span></li>

<li>Achebe, Chinua – <dfn>Things Fall Apart</dfn> <span class="loc">(PR9387.9.A3)</span></li>

</ul>
<h2 id="ps-american-literature">PS: American Literature</h2>

<figure class="resright"><img src="/pix/lovecraft.jpg"></figure>

<ul class="booklist">
<li>Twain, Mark – <dfn>A Connecticut Yankee in King Arthur's Court</dfn> <span class="loc">(PS1308)</span></li>

<li>Hawthorne, Nathaniel – <dfn>The Scarlet Letter</dfn> <span class="loc">(PS1868)</span></li>

<li>Poe, Edgar Allan – <dfn>Edgar Allan Poe Reader</dfn> <span class="loc">(PS2603)</span></li>

<li>Poe, Edgar Allen – <dfn>Tales of Terror and Detection</dfn> <span class="loc">(PS2612)</span></li>

<li>Thoreau, Henry David – <dfn>Walden</dfn> <span class="loc">(PS3048)</span></li>

<li>Wallace, Lew – <dfn>Ben Hur</dfn> <span class="loc">(PS3134)</span></li>

<li>Faulkner, William – <dfn>Light in August</dfn> <span class="loc">(PS3511.A86)</span></li>

<li>Fitzgerald, F. Scott – <dfn>The Great Gatsby</dfn> <span class="loc">(PS3511.I9)</span></li>

<li>Heinlein, Robert A. – <dfn>For Us, the Living</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Heinlein, Robert A. – <dfn>The Moon is a Harsh Mistress</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Lovecraft, H. P. – <dfn>Great Tales of Horror</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Case of Charles Dexter Ward</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Doom That Came to Sarnath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Dream Quest of Unknown Kadath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Tomb</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Rodgers, Marion Elizabeth – <dfn>Mencken &amp; Sara</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Mencken, H. L. – <dfn>The Vintage Mencken</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Rand, Ayn – <dfn>Atlas Shugged</dfn> <span class="loc">(PS3535.A547)</span></li>

<li>Skinner, B. F. – <dfn>Walden Two</dfn> <span class="loc">(PS3537.K527)</span></li>

<li>Smith, Clark Ashton – <dfn>Hyperborea</dfn> <span class="loc">(PS3537.M335)</span></li>

<li>Bear, Greg – <dfn>Darwin's Radio</dfn> <span class="loc">(PS3552.E157)</span></li>

<li>Card, Orson Scott – <dfn>Ender's Game</dfn> <span class="loc">(PS3553.A655)</span></li>

<li>Crichton, Michael – <dfn>Congo</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Jurassic Park</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Timeline</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Dick, Philip K. – <dfn>Dr. Bloodmoney</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Dick, Philip K. – <dfn>Flow My Tears, The Policeman Said</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Herbert, Frank – <dfn>Dune</dfn> <span class="loc">(PS3558.E63)</span></li>

<li>Jordan, Robert – <dfn>The Eye of the World</dfn> <span class="loc">(PS3560.O7617)</span></li>

<li>King, Stephen – <dfn>The Bazaar of Bad Dreams</dfn> <span class="loc">(PS3561.I483)</span></li>

<li>Myers, Bill – <dfn>Blood of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Fire of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Threshold</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Quinn, Daniel – <dfn>Ishmael: An Adventure of the Mind and Spirit</dfn> <span class="loc">(PS3567.U338)</span></li>

<li>Pearl, Matthew – <dfn>The Dante Club</dfn> <span class="loc">(PS3616.E25)</span></li>

<li>Asimov, Isaac – <dfn>Before the Golden Age: A Science Fiction Anthology of the 1930's</dfn> <span class="loc">(PS648.S3)</span></li>

<li>Saramago, José – <dfn>Todos los nombres</dfn> <span class="loc">(PS9281.A66)</span></li>

</ul>
<h2 id="pq-pz-other-literature">PQ-PZ: Other Literature</h2>

<figure class="resright"><img src="/pix/edda.jpg"></figure>

<ul class="booklist">
<li>Voltaire – <dfn>Candide, Zadig and selected stories</dfn> <span class="loc">(PQ2081.E5)</span></li>

<li>Hesse, Hermann – <dfn>Siddhartha</dfn> <span class="loc">(PT2617.E85)</span></li>

<li>Hesse, Hermann – <dfn>The Glass Bead Game</dfn> <span class="loc">(PT2617.E85 G513)</span></li>

<li>Sturluson, Snorri – <dfn>Poetic Edda</dfn> <span class="loc">(PT7235)</span></li>

<li>Sturluson, Snorri – <dfn>Prose Edda</dfn> <span class="loc">(PT7313.E5)</span></li>

<li>Borges, Jorge Luis – <dfn>Ficciones</dfn> <span class="loc">(PW7797.B635)</span></li>

<li>Connor, Ralph – <dfn>Black Rock: a Tale of the Selkirks</dfn> <span class="loc">(PZ3.G654)</span></li>

<li>Roberts, James Hall – <dfn>The Q Document</dfn> <span class="loc">(PZ4.D913)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Hobbit</dfn> <span class="loc">(PZ7.T5744)</span></li>

<li>Wilder, Laura Ingalls – <dfn>Little House (entire series)</dfn> <span class="loc">(PZ7.W6461)</span></li>

<li>Jacobs, Joseph – <dfn>Favorite Celtic Fairy Tales</dfn> <span class="loc">(PZ8)</span></li>

<li>Baum, L. Frank – <dfn>The Wizard of Oz</dfn> <span class="loc">(PZ8.B327)</span></li>

<li><dfn>The Brothers Grimm Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

<li><dfn>The Complete Grimm's Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

</ul>
<h2 id="qa-general-science">QA: General Science</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hVxvLd6cF0k"><img src="/pix/againstmethod.jpg"></a></figure>

<ul class="booklist">
<li>de Santillanna, Giorgio – <dfn>The Origins of Scientific Thought: from Anazimander to Proclus, 600 B.C. to 300 A.D.</dfn> <span class="loc">(Q125)</span></li>

<li>Gardner, Martin – <dfn>Great Essays in Science</dfn> <span class="loc">(Q171)</span></li>

<li>Kuhn, Thomas – <dfn>The Structure of Scientific Revolutions</dfn> <span class="loc">(Q175)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Wiener, Norbert – <dfn>The Human Use of Human Beings</dfn> <span class="loc">(Q175)</span></li>

<li>Feyerabend, Paul – <dfn>Against Method </dfn> <span class="loc">(Q175)</span></li>

<li>Motterlini, Matteo – <dfn>For and Against Method: Including Lakatos's Lectures on Scientific Method and the Lakatos-Feyerabend Correspondence </dfn> <span class="loc">(Q175.3)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Antifragile</dfn> <span class="loc">(Q375)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>The Black Swan</dfn> <span class="loc">(Q375)</span></li>

</ul>
<h2 id="qa-mathematics">QA: Mathematics</h2>
<ul class="booklist">
<li>Sawyer, W. W. – <dfn>Mathematician's Delight</dfn> <span class="loc">(QA37)</span></li>

<li>Birns, Peter and Brown, Patrick and Muster, John C. C. – <dfn>Unix for People</dfn> <span class="loc">(QA76.6)</span></li>

<li>Raymond, Eric S. – <dfn>The Cathedral and the Bazaar</dfn> <span class="loc">(QA76.76.O63)</span></li>

<li>Bellos, Alex – <dfn>Here's Looking at Euclid</dfn> <span class="loc">(QA141.15)</span></li>

<li>Nyberg, Joseph A. – <dfn>Second Course in Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Wentworth, G. A. – <dfn>New School Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Hart, William – <dfn>College Algebra</dfn> <span class="loc">(QA154)</span></li>

<li>Lial, Margaret L. and Miller, Charles D. – <dfn>Algebra and Trigonometry</dfn> <span class="loc">(QA154.2)</span></li>

<li>Sokal, Alan and Bricmont, Jean – <dfn>Fashionable Nonsense: Postmodern Intellectuals' Abuse of Science</dfn> <span class="loc">(QA175)</span></li>

<li>Neugebauer, Otto – <dfn>The Exact Sciences in Antiquity</dfn> <span class="loc">(QA22)</span></li>

<li>Bharati Krsna Thirthaji Maharaja – <dfn>Vedic Mathematics</dfn> <span class="loc">(QA27.I4)</span></li>

<li>Christian, Robert R. – <dfn>Introduction to Logic and Sets</dfn> <span class="loc">(QA248)</span></li>

<li>Davis, Morton D. – <dfn>Game Theory: A Nontechnical Introduction</dfn> <span class="loc">(QA269)</span></li>

<li>Friedman, Avner – <dfn>Differential Games</dfn> <span class="loc">(QA272)</span></li>

<li>Takahashi, Shin – <dfn>The Manga Guide to Statistics</dfn> <span class="loc">(QA276)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 1-10</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 10-15 and Appendices</dfn> <span class="loc">(QA303)</span></li>

<li>Smith, Edward S. and Salkover, Meyer and Justive, Howard K. – <dfn>Unified Calculus</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny – <dfn>Calculus with Analytic Geometry</dfn> <span class="loc">(QA33)</span></li>

<li>Sperling, Abraham and Stuart, Monroe – <dfn>Mathematics (Made Simple Self-Teaching Library)</dfn> <span class="loc">(QA39.2)</span></li>

<li>Horblit, Marcus and Nielson, Kaj L. – <dfn>Problems in Plane Geometry with Solutions</dfn> <span class="loc">(QA459)</span></li>

<li>Shively, Levi S. – <dfn>Modern Geometry</dfn> <span class="loc">(QA473)</span></li>

<li>Nelson, Alfred L. and Folley, Karl W. – <dfn>Plane and Spherical Trigonometry</dfn> <span class="loc">(QA531.N45)</span></li>

<li>Love, Clyde E. – <dfn>Analytic Geometry</dfn> <span class="loc">(QA551)</span></li>

<li>Hutton, Graham – <dfn>Programming in Haskell</dfn> <span class="loc">(QA76.62)</span></li>

<li>Kernighan, Brian W. and Ritchie, Dennis M. – <dfn>The C Programming Language</dfn> <span class="loc">(QA76.73.C15)</span></li>

<li>Barski, Conrad – <dfn>Land of Lisp</dfn> <span class="loc">(QA76.76.C672)</span></li>

<li>Hofstadter, Douglas – <dfn>Gödel, Escher, Bach</dfn> <span class="loc">(QA9.8)</span></li>

<li>Emmet, E. R. – <dfn>Brain Puzzler's Delight</dfn> <span class="loc">(QA95)</span></li>

<li>Emmet, E. R. – <dfn>Puzzles for Pleasure</dfn> <span class="loc">(QA95)</span></li>

<li>Gardner, Martin – <dfn>aha! Gotcha, Paradoxes to puzzle and delight</dfn> <span class="loc">(QA95)</span></li>

<li>Heafford, Philip – <dfn>The Math Entertainer</dfn> <span class="loc">(QA95)</span></li>

</ul>
<h2 id="qb-qr-other-sciences">QB-QR: Other Sciences</h2>
<ul class="booklist">
<li>Hawking, Stephen W. – <dfn>A Brief History of Time</dfn> <span class="loc">(QB981)</span></li>

<li>Lerner, Eric – <dfn>The Big Bang Never Happened</dfn> <span class="loc">(QB991.B54)</span></li>

<li>McEvoy, J. P. and Zarate, Oscar – <dfn>Quantum Theory, A Graphic Guide</dfn> <span class="loc">(QC173.98)</span></li>

<li>Booker, Christopher – <dfn>The Real Global Warming Disaster</dfn> <span class="loc">(QC981.8.G56)</span></li>

<li>Greenburg, Arthur – <dfn>From Alchemy to Chemistry in Picture and Story</dfn> <span class="loc">(QD11)</span></li>

<li>Valentine, Basil – <dfn>Of Natural and Supernatural Things: Also, of the First Tincture, Root, and Spirit of Metals and Minerals: How the Same are Conceived, Generated, Brought Forth, Changed and Augmented</dfn> <span class="loc">(QD25)</span></li>

<li>Watson, James – <dfn>The Double Helix</dfn> <span class="loc">(QH31.D434)</span></li>

<li>Fodor, Jerry and Piattelli Palmarini, Massimo – <dfn>What Darwin Got Wrong</dfn> <span class="loc">(QH375)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Kadans, Joseph M. – <dfn>Modern Encyclopedia of Herbs</dfn> <span class="loc">(QK99.A1)</span></li>

<li>McFarland, J. Horace – <dfn>Getting Acquainted with Trees</dfn> <span class="loc">(QK482)</span></li>

<li>Kurzweil, Ray – <dfn>The Singularity is Near</dfn> <span class="loc">(QP376)</span></li>

<li>Kandel, Eric R. and Schwartz, James H. and Jessell, Thomas M. – <dfn>Essentials of Neural Science and Behavior</dfn> <span class="loc">(QP355.2)</span></li>

</ul>
<h2 id="r-medicine">R: Medicine</h2>
<ul class="booklist">
<li>FC&amp;A – <dfn>The Folk Remedy Encyclopedia: Olive Oil, Vinegar, Honey and 1,001 Other Home Remedies</dfn> <span class="loc">(R733)</span></li>

<li><dfn>Better Homes and Gardens Family Medical Guide</dfn> <span class="loc">(RC81.A2)</span></li>

<li><dfn>The Encyclopedia of Common Diseases</dfn> <span class="loc">(RC81.A2)</span></li>

</ul>
<h2 id="s-t-agriculture-and-technology">S-T: Agriculture and Technology</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=YRNKjQg6y-c"><img src="/pix/salatin.jpg"></a></figure>

<ul class="booklist">
<li>Mollison, Bill – <dfn>Introduction to Permaculture</dfn> <span class="loc">(S494.5.P47)</span></li>

<li>Salatin, Joel – <dfn>Everything I Want to Do Is Illegal</dfn> <span class="loc">(S605.5)</span></li>

<li>David the Good – <dfn>Totally Crazy Easy Florida Gardening</dfn></li>

<li>Seymour, John – <dfn>The Complete Book of Self-Sufficiency</dfn> <span class="loc">(S605.5)</span></li>

<li>Cobleigh, Rolfe – <dfn>Handy Farm Devices and How to Make Them (2 copies)</dfn> <span class="loc">(S676)</span></li>

<li>Seymour, John – <dfn>Gardener's Delight</dfn> <span class="loc">(SB322)</span></li>

<li>Seymour, John – <dfn>The Self-Sufficient Gardener</dfn> <span class="loc">(SB324.3)</span></li>

<li>Haring, Elda – <dfn>The Seedling Handbook</dfn> <span class="loc">(SB405)</span></li>

<li>Abraham, George – <dfn>The Green Thumb Garden Handbook</dfn> <span class="loc">(SB453)</span></li>

<li><dfn>Reader's Digest Illustrated Guide to Gardening</dfn> <span class="loc">(SB453)</span></li>

<li>Kaczynski, Theodore John – <dfn>Technological Slavery</dfn> <span class="loc">(T14.5)</span></li>

<li>Kaczynski, Theodore John – <dfn>Anti-Tech Revolution: Why and How</dfn> <span class="loc">(T14.5)</span></li>

<li>Macaulay, David and Ardleym Neil – <dfn>The Way Things Work</dfn> <span class="loc">(T47)</span></li>

<li>Slater, Robert and Li, Ling and Li, Wen – <dfn>Portraits in Silicon</dfn> <span class="loc">(TK7885.2)</span></li>

<li>Bishop, Michael and Zimmerman, Holmes – <dfn>Detailing Cars and Trucks</dfn> <span class="loc">(TL152)</span></li>

<li>Allaby, Michael and Lovelock, James – <dfn>The Greening of Mars</dfn> <span class="loc">(TL795.7)</span></li>

<li>Abbey, Barbara – <dfn>The Complete Book of Knitting</dfn> <span class="loc">(TT820)</span></li>

<li>Bishop, Jack – <dfn>Vegetables Every Day</dfn> <span class="loc">(TX801)</span></li>

<li>Lo, Kenneth – <dfn>Chinese Regional Cooking</dfn> <span class="loc">(TX724.5.C5)</span></li>

</ul>
<h2 id="books-as-of-yet-unsorted">Books as of yet unsorted</h2>
<ul class="booklist">
<li>Seb Falk – <dfn>The Light Ages: The Surprising Story of Medieval Science</dfn></li>

<li><dfn>The Penny Catechism: A Catechism of Christian Doctrine</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese Reader, Part 1</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese</dfn></li>

<li>Flame Tree Publishing – <dfn>Gothic Fantasy: Lost Worlds Short Stories</dfn></li>

<li>Lee, Christopher – <dfn>This Sceptered Isle 55 BC to 1901</dfn></li>

<li>Malice, Michael – <dfn>Dear Reader</dfn></li>

<li>McCloskey, Deirdre N. – <dfn>Economic Writing</dfn></li>

<li>Meyer, Jerome S. – <dfn>The Provocative Puzzler</dfn></li>

<li>Parikh, Prashant – <dfn>Language and Equilibrium</dfn></li>

<li>Reed, Lawrence W. – <dfn>Great Myths of the Great Depression</dfn></li>

<li><dfn>Using HTML4, Java 1.1, and Javascript 1.2</dfn></li>

<li>Valizadeh, Roosh – <dfn>Game</dfn></li>

<li>Vikernes, Varg – <dfn>MYFAROG 2.6</dfn></li>

</ul>
<div style="clear:both" class="taglist">Read related articles:<br><a id="tag_personal" href="https://lukesmith.xyz/tags/personal">Personal</a> · <a id="tag_science" href="https://lukesmith.xyz/tags/science">Science</a> · <a id="tag_tradition" href="https://lukesmith.xyz/tags/tradition">Tradition</a> · <a id="tag_lifestyle" href="https://lukesmith.xyz/tags/lifestyle">Lifestyle</a> · <a id="tag_philosophy" href="https://lukesmith.xyz/tags/philosophy">Philosophy</a></div>
<br clear="both">
</article>
</main>
<footer>
	<a href="https://lukesmith.xyz">https://lukesmith.xyz</a>

	<p>
	<img class="lw" src="/pix/btc.svg">Bitcoin (<a href="/pix/btc-logo.png">QR</a>): <code>bc1qkyvknjap3cjtgfqd5qwc0q2ygry7nep7d4t57y</code>
	<br>
	<img class="lw" src="/pix/xmr.svg">Monero (<a href="/pix/xmr-logo.png">QR</a>): <code class="crypto">48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh</code>
	</p><p><a href="/index.xml"><img src="/rss.svg" style="max-height:1.5em" alt="RSS Feed" title="Subscribe via RSS for updates."></a>
</p></footer>


</body></html>
<head>
	<title>My Personal Library | Luke's Webpage</title>
	<link rel="canonical" href="https://lukesmith.xyz">
	<link rel="alternate" type="application/rss+xml" title="Luke's Webpage RSS" href="/index.xml">
	<link rel="stylesheet" type="text/css" href="/style.css">
	<link rel="icon" href="/favicon.ico">
	<meta name="description" content="This is a list of the books in my personal library. If you have any questions or want me to review any of them, email me (luke@lukesmith.xyz).
I haven't read every book here, nor do I own all the books I've read or like. I also don't necessarily like all the books I own.
Check out my podcast, Not Related! for some book reviews and other things. Books I've talked about in one way or another in the podcast will have a link to that episode.">
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
<p>This is a list of the books in my personal library. If you have any
questions or want me to review any of them, email me
(<a href="mailto:luke@lukesmith.xyz">luke@lukesmith.xyz</a>).</p>
<p>I haven't read every book here, nor do I own all the books I've read
or like. I also don't necessarily like all the books I own.</p>
<p>Check out <a href="https://notrelated.xyz">my podcast, <em>Not Related!</em></a>
for some book reviews and other things. Books I've talked about in one
way or another in the podcast will have a link to that episode.</p>
<h2 id="-lindypressnet-books">🆕 LindyPress.net Books</h2>
<p>Note that now I am reprinting out-of-print works at
<a href="https://lindypress.net">LindyPress.net</a>. You can buy any of these books
yourself if you'd like. (Most of them are pretty exclusive in that I'm
the only one reprinting them.)</p>
<ul>
<li>Pseudo-Aristotle – <a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a></li>
<li><a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a></li>
<li>Isidore of Seville – <a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a></li>
<li>Roger Bacon ‐ <a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a></li>
<li>Marcus Aurelius – <a href="https://lindypress.net/book?pk=2">Meditations</a></li>
<li><a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a></li>
</ul>
<p>(These are at the top since I don't know if anyone has given them Library of
Congress numbers, and I suppose as an ad.)</p>
<h2 id="a-bd-general-works-philosophy-logic-speculative-philosophy">A-BD: General Works, Philosophy, Logic, Speculative Philosophy</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hCVdCS0t46I"><img src="/pix/searle.jpg" title="Searle (actually literally) did nothing wrong."></a></figure>

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
<h2 id="bm-bx-specific-religions-and-theology">BM-BX: Specific Religions and Theology</h2>

<figure class="resright"><img src="/pix/biglot.jpg" title="A Greek and Latin biglottic Bible"></figure>

<ul class="booklist">
<li><dfn>'תְּהִלַּת ה</dfn> <span class="loc">(BM675/D3)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Key to Theosophy</dfn> <span class="loc">(BP561)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Voice of Silence</dfn> <span class="loc">(BP561)</span></li>

<li>Wright, Stuart – <dfn>Armageddon in Waco</dfn> <span class="loc">(BP605.B62)</span></li>

<li>Lewis, C. S. – <dfn>Mere Christianity</dfn> <span class="loc">(BR123)</span></li>

<li>Lewis, C. S. – <dfn>The Screwtape Letters</dfn> <span class="loc">(BR125)</span></li>

<li>Reardon, Patrick Henry – <dfn>Christ in the Psalms</dfn> <span class="loc">(BS1430.4)</span></li>

<li>Leithart, Peter J. – <dfn>Solomon Among the Postmoderns</dfn> <span class="loc">(BS1475.52)</span></li>

<li>Porter, J. R. – <dfn>The Lost Bible</dfn> <span class="loc">(BS1700)</span></li>

<li>Heiser, Michael – <dfn>Reversing Hermon: Enoch, the Watchers and the Forgotten Mission of Jesus Christ</dfn> <span class="loc">(BS1830.E7)</span></li>

<li><dfn>The New Oxford Annotated Bible</dfn> <span class="loc">(BS191.5.A1)</span></li>

<li><dfn>The New English Bible</dfn> <span class="loc">(BS192.A1)</span></li>

<li>Montano, Arias and Leudsen, Johann – <dfn>Greek-Latin Parallel New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>Pocket Interlinear New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>The New International Dictionary of New Testament Theology (3 Volumes)</dfn> <span class="loc">(BS2312)</span></li>

<li><dfn>Ἡ Καινὴ Διαθήκη</dfn> <span class="loc">(BS2312)</span></li>

<li>Kümmel, Werner Georg – <dfn>Introduction to the New Testament</dfn> <span class="loc">(BS2330)</span></li>

<li>Aland, Kurt – <dfn>Synopsis Quattuor Evangeliorum</dfn> <span class="loc">(BS2560.A2)</span></li>

<li>Mack. Burton L. – <dfn>A Myth of Innocence</dfn> <span class="loc">(BS2585.2)</span></li>

<li>Ehrman, Bart D. – <dfn>Lost Christianities: The Battles for Scriptures and the Faiths We Never Knew</dfn> <span class="loc">(BS2840.E4)</span></li>

<li>Luther, Martin – <dfn>Luther's Small Catechism with Additions Including the Augsburg Confession</dfn> <span class="loc">(BR331.K64)</span></li>

<li>Strong, James – <dfn>Strong's Exhaustive Concordance of the Bible with Hebrew and Greek Dictionaries</dfn> <span class="loc">(BS425)</span></li>

<li><dfn>Illustrated Dictionary and Concordance of the Bible</dfn> <span class="loc">(BS440)</span></li>

<li>McDowell, Josh – <dfn>The New Evidence that Demands a Verdict</dfn> <span class="loc">(BS480)</span></li>

<li>Laymon, Charles M. – <dfn>The Interpreter's One-Volume Commentary on the Bible</dfn> <span class="loc">(BS491.2)</span></li>

<li>Cross, John R. – <dfn>The Stranger on the Road to Emmaus</dfn> <span class="loc">(BS511.2)</span></li>

<li><dfn>Reader's Digest Mysteries of the Bible; the Enduring Questions of the Scriptures</dfn> <span class="loc">(BS538)</span></li>

<li>Smith, Brendan Powell – <dfn>The Brick Bible</dfn> <span class="loc">(BS550.3)</span></li>

<li>Kent, Paul and McLaughlan, David – <dfn>Know Your Bible: All 66 Books Explained and Applied</dfn> <span class="loc">(BS593)</span></li>

<li><dfn>Septuagint with Apocrypha</dfn> <span class="loc">(BS742)</span></li>

<li><dfn>Biblia Sacra Vulgata</dfn> <span class="loc">(BS75)</span></li>

<li>Newman, John Henry – <dfn>An Essay on the Development of Christian Doctrine</dfn> <span class="loc">(BT21)</span></li>

<li>Robinson, James M. – <dfn>The Nag Hammadi Library</dfn> <span class="loc">(BT1391)</span></li>

<li>Lewis, C. S. – <dfn>Surprised by Joy: The Shape of My Early Life</dfn> <span class="loc">(BV4935.L43)</span></li>

<li>Carman, Stephen L. and Owen, Bob – <dfn>Quest: The Story of an Aerospace Engineer who Challenged God to Prove Himself</dfn> <span class="loc">(BV4930)</span></li>

<li>Ware, Timothy – <dfn>The Orthodox Church</dfn> <span class="loc">(BX106)</span></li>

<li>Aveling, J. C. H. – <dfn>The Jesuits</dfn> <span class="loc">(BX3706.2)</span></li>

<li><dfn>The Book of Common Prayer</dfn> <span class="loc">(BX5145)</span></li>

<li><dfn>Five Great Encyclicals: Labor, Education, Marriage, Reconstructing the Social Order, Atheistic Communism</dfn> <span class="loc">(BX860)</span></li>

</ul>
<h2 id="c-auxiliary-sciences-of-history">C: Auxiliary Sciences of History</h2>
<ul class="booklist">
<li>Graeber, David and Wengrow, David – <dfn>The Dawn of Everything: A New History of Humanity</dfn> <span class="loc">(CB19)</span></li>

<li>McNeill, William H. – <dfn>The Rise of the West: A History of the Human Community</dfn> <span class="loc">(CB59)</span></li>

<li>Sitchin, Zecharia – <dfn>The 12th Planet</dfn> <span class="loc">(CB156)</span></li>

<li>Rohl, David – <dfn>The Lords of Avaris: Uncovering the Legendary Origins of Western Civilization</dfn> <span class="loc">(CB245)</span> <a href="https://notrelated.xyz/#02.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Casson, Lionel and Clairborne, Robert and Fagan, Brian and Karp, Walter – <dfn>Mysteries of the Past</dfn> <span class="loc">(CB311)</span></li>

<li>Fisher, Marshall John and Fisher, David E. – <dfn>Mysteries of Lost Empires</dfn> <span class="loc">(CB311)</span></li>

<li>Hawkes, Jacquetta – <dfn>The Atlas of Early Man</dfn> <span class="loc">(CB311)</span></li>

<li>Platt, Richard and Riddell, Chris – <dfn>Castle Diary</dfn> <span class="loc">(CB351)</span></li>

<li>Cahill, Thomas – <dfn>Mysteries of the Middle Ages</dfn> <span class="loc">(CB351)</span></li>

</ul>
<h2 id="d-world-history">D: World History</h2>

<figure class="resright"><img src="/pix/racehutton.jpg" title="Hutton's book on the Third Reich"></figure>

<ul class="booklist">
<li>Malesky, Kee – <dfn>All Facts Considered, the Essential Library of Inessential Knowledge</dfn> <span class="loc">(D10)</span></li>

<li>Evola, Julius – <dfn>Revolt Against the Modern World</dfn> <span class="loc">(D16.8)</span></li>

<li>Epstein, Steven A. – <dfn>An Economic and Social History of Later Medieval Europe, 1000-1500</dfn> <span class="loc">(D117)</span></li>

<li>Pirenne, Henri – <dfn>A History of Europe</dfn> <span class="loc">(D117)</span></li>

<li>Cantor, Nroman F. – <dfn>Medieval History: The Life and Death of a Civilization</dfn> <span class="loc">(D118)</span></li>

<li>Roberts, J. M. – <dfn>New History of the World</dfn> <span class="loc">(D20)</span></li>

<li>Mann, Charles C. – <dfn>1493, Uncovering the New World Columbus Created</dfn> <span class="loc">(D228)</span></li>

<li>Rogan, Eugene L. – <dfn>The FAll of the Ottomans: The Great War in the Middle East</dfn> <span class="loc">(D566)</span></li>

<li>Sanborn, Frederick R. – <dfn>Design for War: A Study of Secret Power Politics</dfn> <span class="loc">(D742.U5)</span></li>

<li>Cheyney, Edward P. – <dfn>A Short History of England</dfn> <span class="loc">(DA32)</span></li>

<li>Thomas, Charles – <dfn>Celtic Britain</dfn> <span class="loc">(DA140)</span></li>

<li>Sellar, W.C. &amp; Yeatman R.J. – <dfn>1066 and All That</dfn> <span class="loc">(DA33)</span></li>

<li>Freeman, John and Sharpe, Sue – <dfn>This Beautiful Land: Britain</dfn> <span class="loc">(DA632)</span></li>

<li>Hutton, Christopher – <dfn>Race and the Third Reich</dfn> <span class="loc">(DD253)</span></li>

<li>Tacitus, C. Cornellius – <dfn>Annales et Historiae</dfn> <span class="loc">(DG207.T3)</span></li>

<li>Shirer, William L. – <dfn>The Rise and Fall of the Third Reich</dfn> <span class="loc">(DD256.5)</span></li>

<li>MacDonald, Kevin – <dfn>The Culture of Critique: An Evolutionary Analysis of Jewish Involvement in Twentieth-Century Intellectual and Political Movements</dfn> <span class="loc">(DS143)</span></li>

<li>Ford, Henry Sr. – <dfn>The International Jew: The World's Foremost Problem</dfn> <span class="loc">(DS145)</span></li>

<li>Ali, Tariq – <dfn>The Duel: Pakistan on the Flight Path of American Power</dfn> <span class="loc">(DS384)</span></li>

<li>De Bary, William Theodore – <dfn>The Sources of Indian Tradition</dfn> <span class="loc">(DS423)</span></li>

<li>Keay, John – <dfn>India, A History</dfn> <span class="loc">(DS451)</span></li>

<li>Ebrey, Patricia Buckley – <dfn>Cambridge Illustrated History of China</dfn> <span class="loc">(DS706)</span></li>

<li>National Geographic Society – <dfn>Journey into China</dfn> <span class="loc">(DS712)</span></li>

</ul>
<h2 id="e-f-history-of-the-americas">E-F: History of the Americas</h2>

<figure class="resright"><img src="/pix/foxfire.jpg"></figure>

<ul class="booklist">
<li>Hancock, Graham – <dfn>America Before: The Key to Earth's Lost Civilization</dfn> <span class="loc">(E61)</span></li>

<li>Little, Gregory – <dfn>Path of Souls: The Native American Death Journey: Cygnus, Orion, the Milky Way, Giant Skeletons in Mounds, &amp; the Smithsonian</dfn> <span class="loc">(E98.M8)</span></li>

<li>Mooney, James – <dfn>Myths of the Cherokee</dfn> <span class="loc">(E99.C5)</span></li>

<li>Greenblatt, Stephen – <dfn>New World Encounters</dfn> <span class="loc">(E141)</span></li>

<li>Fischer, David Hackett – <dfn>Albion's Seed: Four British Folkways in America</dfn> <span class="loc">(E169.1)</span> <a href="https://notrelated.xyz/#01.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Sowell, Thomas – <dfn>Ethnic America</dfn> <span class="loc">(E184.A1)</span></li>

<li>Hurmence, Belinda – <dfn>Before Freedom: 48 Oral Histories of Former North and South Carolina Slaves</dfn> <span class="loc">(E444)</span></li>

<li>Adams, Nehemiah – <dfn>A South-side View of Slavery: or Three Months at the South in 1854</dfn> <span class="loc">(E449)</span></li>

<li>Parsons, Charles Grandison – <dfn>An Inside View of Slavery; or A Tour Among the Planters</dfn> <span class="loc">(E449)</span></li>

<li>Long, A. L. – <dfn>Memoirs of Robert E. Lee</dfn> <span class="loc">(E467.1.L4)</span></li>

<li>Henry, Robert Selph – <dfn>The Story of the Confederacy</dfn> <span class="loc">(E487)</span></li>

<li>Mann, Charles C. – <dfn>1491, New Revelations of the Americas Before Columbus</dfn> <span class="loc">(E61)</span></li>

<li>Wharton, H. M. – <dfn>War Songs and Poems of the Southern Confederacy, 1861-1865: a Collection of the Most Popular and Impressive Songs and Poems of War Times, Dear to Every Southern Heart</dfn> <span class="loc">(E647)</span></li>

<li><dfn>The Blue Book of the John Birch Society</dfn> <span class="loc">(E743.5)</span></li>

<li>Stormer, John A. – <dfn>The Death of a Nation</dfn> <span class="loc">(E743.5)</span></li>

<li>Ramo, Joshua Cooper – <dfn>The Age of the Unthinkable</dfn> <span class="loc">(E902)</span></li>

<li>de las Casas, Bartolomé – <dfn>Brevisima relación de la destrución de las Indias</dfn> <span class="loc">(F1411)</span></li>

<li><dfn>The Foxfire Book</dfn> <span class="loc">(F291.2)</span></li>

<li><dfn>The Foxfire Book 2</dfn> <span class="loc">(F291.2)</span></li>

</ul>
<h2 id="g-geography-anthropology-recreation">G: Geography, Anthropology, Recreation</h2>
<ul class="booklist">
<li>Winer, Richard – <dfn>Ghost Ships: True Stories of Nautical Nightmares, Hauntings, and Disasters</dfn> <span class="loc">(G525)</span></li>

<li><dfn>National Geographic Collegiate Atlas of the World</dfn> <span class="loc">(G1021)</span></li>

<li>Wells, Spencer – <dfn>Pandora's Seed: The Unforeseen Cost of Civilization</dfn> <span class="loc">(GF75)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cochran, Gregory and Harpending, Henry – <dfn>the 10,000 Explosion: How Civilization Accelerated Human Evolution</dfn> <span class="loc">(GN281.4)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cremo, Michael A. &amp; Thompson, Ricahrd L. – <dfn>Forbidden Archaeology: The Hidden History of the Human Race</dfn> <span class="loc">(GN741)</span></li>

<li>Hancock, Graham – <dfn>Magicians of the Gods: The Forgotten Wisdom of Earth's Lost Civilization</dfn> <span class="loc">(GN751)</span></li>

<li>Cayce, Hugh Lynn – <dfn>Edgar Cayce on Atlantis</dfn> <span class="loc">(GN751.C35)</span></li>

<li>Marshack, Alexander – <dfn>The Roots of Civilization: The Cognitive Beginnings of Man's First Art, Symbol and Notation</dfn> <span class="loc">(GN772)</span></li>

<li>Bord, Janet and Bord, Colin – <dfn>Prehistoric Britain from the Air</dfn> <span class="loc">(GN805)</span></li>

<li>Bruce, Annette J. – <dfn>More Tellable Cracker Tales</dfn> <span class="loc">(GR110.F5)</span></li>

</ul>
<h2 id="h-social-sciences">H: Social Sciences</h2>
<p>
</p><figure class="resright"><img src="/pix/democracy.jpg"></figure>


<figure class="resright"><img src="/pix/pike.jpg"></figure>
<p></p>
<ul class="booklist">
<li>Greenspan, Alan – <dfn>The Age of Turbulence</dfn> <span class="loc">(HB119.G74)</span></li>

<li>Hazlitt, Hentry – <dfn>Economics in One Lesson (two copies)</dfn> <span class="loc">(HB171)</span></li>

<li>Keynes, John Maynard – <dfn>The General Theory of Employment, Interest and Money</dfn> <span class="loc">(HB171)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Rothbard, Murray – <dfn>Man, Economy and State with Power and Market</dfn> <span class="loc">(HB171)</span></li>

<li>von Mises, Ludwig – <dfn>Economic Policy</dfn> <span class="loc">(HB171)</span></li>

<li>Boulding, Kenneth E. – <dfn>Economic Analysis</dfn> <span class="loc">(HB171.5)</span></li>

<li>Goodman, Kennard E. and Moore, William L. – <dfn>Economics in Everyday Life</dfn> <span class="loc">(HB171.5)</span></li>

<li>Pindyck, Robert S. and Rubinfeld, Daniel L. – <dfn>Microeconomics</dfn> <span class="loc">(HB172)</span></li>

<li>Fisher, David Hackett – <dfn>The Great Wave: Price Revolutions and the Rhythm of History</dfn> <span class="loc">(HB231)</span></li>

<li>Soros, George – <dfn>The Crash of 2008 and What It Means</dfn> <span class="loc">(HB3722)</span> <a href="https://notrelated.xyz/#02.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Keen, Steve – <dfn>Debunking Economics: The Naked Emperor Dethroned?</dfn> <span class="loc">(HB71)</span></li>

<li>Krugman, Paul – <dfn>The Accidental Theorist</dfn> <span class="loc">(HB74.5)</span></li>

<li>Hoppe, Hans Hermann – <dfn>Democracy: The God That Failed: The Economics and Politics of Monarchy, Democracy and Natural Law</dfn> <span class="loc">(HB74.P65)</span></li>

<li>Ekelund, Robert B. Jr. and Hébert, Robert F – <dfn>A History of Economic Theory and Method</dfn> <span class="loc">(HB75)</span></li>

<li>Buchholz, Todd G. – <dfn>New Ideas from Dead Economists, an Introduction to Modern Economic Thought</dfn> <span class="loc">(HB76)</span></li>

<li>Heilbroner, Robert L. – <dfn>The Worldly Philosophers</dfn> <span class="loc">(HB76)</span></li>

<li>Paul Erlich – <dfn>The Population Bomb</dfn> <span class="loc">(HB875.E35)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Palmer, Tom G. – <dfn>After the Welfare State</dfn> <span class="loc">(HB99.3)</span></li>

<li>Krugman, Paul – <dfn>Peddling Prosperity</dfn> <span class="loc">(HB99.7)</span></li>

<li>Walton, Gary M. and Rockoff, Hugh – <dfn>History of the American Economy</dfn> <span class="loc">(HC103)</span></li>

<li>Krugman, Paul – <dfn>The Great Unravelling</dfn> <span class="loc">(HC106)</span></li>

<li>Krugman, Paul – <dfn>The Conscience of a Liberal</dfn> <span class="loc">(HC110.I5)</span></li>

<li>Clark, Gregory – <dfn>A Farewell to Alms</dfn> <span class="loc">(HC21)</span></li>

<li>Easterly, William – <dfn>The Elusive Quest for Growth</dfn> <span class="loc">(HC59.72.P6)</span></li>

<li>Simon, Julian L. and Kahn, Herman – <dfn>The Resourceful Earth</dfn> <span class="loc">(HC59.R445)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Dixit, Avinash K. and Nalebuff, Barry J. – <dfn>Thinking Strategically, The Competitive Edge in Business, Politics, and Everyday Life</dfn> <span class="loc">(HD30.28)</span></li>

<li>Adams, Scott – <dfn>The Dilbert Principle</dfn> <span class="loc">(HD31)</span></li>

<li>Ehrenreich, Barbara – <dfn>Nickel and Dimed</dfn> <span class="loc">(HD4918)</span></li>

<li>Thiel, Peter – <dfn>Zero to One: Notes on Start-Ups, or How to Build the Future</dfn> <span class="loc">(HD62.5)</span></li>

<li>Montgomery, David – <dfn>Beyond Equality: Labor and the Radical Republicans 1862-1872</dfn> <span class="loc">(HD8076)</span></li>

<li>Caplan, Bryan – <dfn>The Myth of the Rational Voter: Why Democracies Choose Bad Policies</dfn> <span class="loc">(HD87)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bhagwati, Jagdish – <dfn>In Defense of Globalization</dfn> <span class="loc">(HF1359)</span></li>

<li>Krugman, Paul and Obstfield, Maurice – <dfn>International Economics</dfn> <span class="loc">(HF1359)</span></li>

<li>Lechner, Frank J. and Boli, John – <dfn>The Globalization Reader</dfn> <span class="loc">(HF1359)</span></li>

<li>Myrdal, Gunnar – <dfn>Beyond the Welfare State</dfn> <span class="loc">(HF1411)</span></li>

<li>Graeber, David – <dfn>Bullshit Jobs: A Theory</dfn> <span class="loc">(HF5549.5.J63)</span> <a href="https://notrelated.xyz/#02.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Soros, George – <dfn>In Defense of Open Society</dfn> <span class="loc">(HG172.S63)</span></li>

<li>Boortz, Neal and Linder, John – <dfn>The Fairtax Book: Saying Goodbye to the Income Tax and the IRS</dfn> <span class="loc">(HJ4652)</span></li>

<li>Stove, David – <dfn>Darwinian Fairytales</dfn> <span class="loc">(HM106)</span></li>

<li>O'Brien, Jodi – <dfn>The Production of Reality</dfn> <span class="loc">(HM1033)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Skin in the Game</dfn> <span class="loc">(HM1101)</span></li>

<li>Berne, Eric – <dfn>Games People Play</dfn> <span class="loc">(HM1106)</span></li>

<li>Pinker, Steven – <dfn>The Better Angels of Our Nature</dfn> <span class="loc">(HM1116)</span></li>

<li>Kropotkin, Peter – <dfn>Mutual Aid: A Factor of Evolution</dfn> <span class="loc">(HM131)</span></li>

<li>Diamond, Jared – <dfn>Guns, Germs and Steel</dfn> <span class="loc">(HM206)</span></li>

<li>Bork, Robert H. – <dfn>Slouching Towards Gomorrah: Modern Liberalism and American Decline</dfn> <span class="loc">(HN59.2)</span></li>

<li>Arnold, Matthew – <dfn>Culture and Anarchy</dfn> <span class="loc">(HN389)</span></li>

<li>Jones, E. Michael – <dfn>Libido Dominandi: Sexual Liberation and Political Control</dfn> <span class="loc">(HQ472.U6)</span></li>

<li>Eisler, Riane – <dfn>The Chalice and the Blade, Our History, Our Future</dfn> <span class="loc">(HQ1075)</span></li>

<li>Harris, Judith Rich – <dfn>The Nurture Assumption</dfn> <span class="loc">(HQ772)</span></li>

<li>Beuerlein, Mark – <dfn>The Dumbest Generation</dfn> <span class="loc">(HQ799.7)</span></li>

<li>Street, Oliver Day – <dfn>Symbolism of the Three Degrees</dfn> <span class="loc">(HS425)</span></li>

<li><dfn>Morals and Dogma of the Ancient and Accepted Scottish Rite of Freemasonry</dfn> <span class="loc">(HS767)</span></li>

<li><dfn>The 9/11 Commission Report: Final Report of the National Commission on Terrorist Attacks upon the United States</dfn> <span class="loc">(HV6432.7)</span></li>

<li>Engels, Frederick – <dfn>Socialism: Utopian and Scientific</dfn> <span class="loc">(HX276)</span></li>

<li>Hayek, F. A. – <dfn>The Intellectuals and Socialism</dfn> <span class="loc">(HX528)</span></li>

<li>More, Thomas – <dfn>Utopia</dfn> <span class="loc">(HX810.5)</span></li>

<li>Stringham, Edward P. – <dfn>Anarchy and the Law</dfn> <span class="loc">(HX833)</span></li>

<li>Schumpeter, Joseph Alois – <dfn>Capitalism, Socialism and Democracy</dfn> <span class="loc">(HX86)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bastiat, Frederic – <dfn>The Law</dfn> <span class="loc">(HX87)</span></li>

</ul>
<h2 id="j-k-political-science-and-law">J-K: Political Science and Law</h2>

<figure class="resright"><img src="/pix/archeofuturism.jpg"></figure>

<ul class="booklist">
<li>Faye, Guillaume – <dfn>Archeofuturism: European Visions of the Post-Catastrophic Age</dfn> <span class="loc">(JA84.F8)</span></li>

<li>Plato – <dfn>The Republic</dfn> <span class="loc">(JC71)</span></li>

<li>Machiavelli, Niccolò – <dfn>The Prince and Other Writings</dfn> <span class="loc">(JC143)</span></li>

<li>Hobbes, Thomas – <dfn>Leviathan</dfn> <span class="loc">(JC153)</span></li>

<li>Filmer, Robert – <dfn>Patriarcha, or, The Natural Power of Kings</dfn> <span class="loc">(JC153.F48)</span></li>

<li>Samons, Loren J. – <dfn>What's Wrong with Democracy?</dfn> <span class="loc">(JC421)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Mill, John Stewart – <dfn>On Liberty</dfn> <span class="loc">(JC585)</span></li>

<li>Reed, Lawrence W. – <dfn>Are We Good Enough for Liberty?</dfn> <span class="loc">(JC585)</span></li>

<li>Jeffery, – <dfn>People's War: New Light on the Struggle for South Africa</dfn> <span class="loc">(JQ1998.A4)</span></li>

<li>Beard, Charles – <dfn>An Economic Interpretation of the Constitution of the United States</dfn> <span class="loc">(JK146)</span></li>

<li>Smith, Bradley A. – <dfn>Unfree Speech: The Folly of Campaign Finance Reform</dfn> <span class="loc">(JK1991)</span></li>

<li>de Tocqueville, Alexis – <dfn>Democracy in America</dfn> <span class="loc">(JK216)</span></li>

<li>Brimelow, Peter – <dfn>Alien Nation: Common Sense about America's Immigration Disaster</dfn> <span class="loc">(JV6493)</span></li>

<li>Fukuyama, Francis – <dfn>America at the Crossroads: Democracy, Power and Neoconservative Legacy</dfn> <span class="loc">(JZ1480)</span></li>

<li>Silverglate, Harvey A. and French, David A. and Lukianoff, Greg – <dfn>FIRE's Guide to Free Speech on Campus</dfn> <span class="loc">(KF4123.5)</span></li>

<li>Bernstein, David E. – <dfn>You Can't Say That!</dfn> <span class="loc">(KF4749)</span></li>

</ul>
<h2 id="l-n-education-music-fine-arts">L-N: Education, Music, Fine Arts</h2>
<ul class="booklist">
<li>Bloom, Allan – <dfn>The Closing of the American Mind: How Higher Education Has Failed Democracy and Impoverished the Souls of Today's Students</dfn> <span class="loc">(LA227.3)</span></li>

<li>Russell, Bertrand – <dfn>Education and the Good Life</dfn> <span class="loc">(LB775)</span></li>

<li><dfn>Baptist Hymnal</dfn> <span class="loc">(M2122)</span></li>

<li>Towner, D. B., Lorenz, E. S. and Wilson, Ira B. – <dfn>Songs of Praise: A Collection of Gospel Songs for Men's Voices</dfn> <span class="loc">(M2198)</span></li>

<li>International Graphic Society – <dfn>The Arts of Mankind: Painting, Architecture, Music</dfn> <span class="loc">(N5302)</span></li>

<li>Barral i Altet, Xavier – <dfn>The Early Middle Ages: From Late Antiquity to A.D. 1000</dfn> <span class="loc">(NA350)</span></li>

<li>Churchill, Winston S. – <dfn>Painting as a Pastime: An instructive and inspiring invitation to the joy of painting</dfn> <span class="loc">(ND1142)</span></li>

<li>Cornelius, Maurits – <dfn>The Graphic Work of M.C. Escher</dfn> <span class="loc">(NE670.E75)</span></li>

</ul>
<h2 id="p-philology-linguistics">P: Philology, Linguistics</h2>

<figure class="resright"><img src="/pix/westernclassical.jpg" title="Good for learning some #Lindy linguistics"></figure>

<ul class="booklist">
<li>Smith, Luke – <dfn>External Possession and the Undisentanglability of Syntax and Semantics</dfn></li>

<li>Chomsky, Noam – <dfn>Language and Mind</dfn> <span class="loc">(P106)</span></li>

<li>Harris, Roy – <dfn>Language, Saussure and Wittgenstein, How to Play Games with Words</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>Words and Rules, the Ingredients of Language</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>The Stuff of Thought</dfn> <span class="loc">(P107)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: I Linguistic Theory: Foundations</dfn> <span class="loc">(P121)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: II Linguistics Theory: Extensions and Implications</dfn> <span class="loc">(P121)</span></li>

<li>Ohio State University – <dfn>Language Files 11</dfn> <span class="loc">(P121)</span></li>

<li>Chomsky, Noam – <dfn>The Logical Structure of Linguistic Theory</dfn> <span class="loc">(P158)</span></li>

<li>Falk, Yehuda N. – <dfn>Lexical-Functional Grammar, An Introduction to Parallel Constraint-Based Syntax</dfn> <span class="loc">(P158.25)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Chomsky's Minimalism</dfn> <span class="loc">(P158.28)</span></li>

<li>Gutiérrez, Bravo and Arellanes Arellanes, Francisco and Peón Herrero, Mario Ernesto Chávez – <dfn>Nuevos estudios de Teoría de la Optimalidad</dfn> <span class="loc">(P158.42)</span></li>

<li>Richards, Norvin – <dfn>Contiguity Theory</dfn> <span class="loc">(P224.R43)</span></li>

<li>Bresnan, Joan and Asudeh, Ash and Tolivonen, Ida and Wechsler, Stephen – <dfn>Lexical-Functional Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Chomsky, Noam – <dfn>Aspects of the Theory of Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Freidin, Robert – <dfn>Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Saeed, John I. – <dfn>Semantics</dfn> <span class="loc">(P325)</span></li>

<li>Dalby, Andrew – <dfn>Dictionary of Languages, the Definitive Reference to More than 400 Languages</dfn> <span class="loc">(P371)</span></li>

<li>Allan, Keith – <dfn>The Western Classical Tradition in Linguistics</dfn> <span class="loc">(P61)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Western Linguistics: An Historical Introduction</dfn> <span class="loc">(P61)</span></li>

<li>Klein, Jared – <dfn>An Indo-European Chrestomathy</dfn></li>

<li>Watkins, Calvert – <dfn>The American Heritage Dictionary of Indo-European Roots</dfn> <span class="loc">(P615)</span></li>

<li>Sampson, Geoff – <dfn>Schools of Linguistics</dfn> <span class="loc">(P77)</span></li>

<li>Harris, Randy Allen – <dfn>The Linguistics Wars</dfn> <span class="loc">(P85.C47)</span></li>

<li>Cutting, Joan – <dfn>Pragmatics and Discourse</dfn> <span class="loc">(P99.4.P72)</span></li>

</ul>
<h2 id="pa-greek-and-latin-language-and-literature">PA: Greek and Latin language and Literature</h2>

<figure class="resright"><img src="/pix/hughes.jpg" title="These are actually pretty good and readable English translations."></figure>

<ul class="booklist">
<li>Morrison, Clinton and Barnes, David H. – <dfn>New Testament Word Lists</dfn> <span class="loc">(PA881)</span></li>

<li>Magoffin, Ralph van Deman and Henry, Margaret Young – <dfn>Latin First Year</dfn> <span class="loc">(PA2087)</span></li>

<li>Wheelock, Frederic M. – <dfn>Latin, an Introductory Course Based on Ancient Authors</dfn> <span class="loc">(PA2087.5)</span></li>

<li>Orberg, Hans H – <dfn>Roma Aeterna</dfn> <span class="loc">(PA2094.5)</span></li>

<li>Orberg, Hans H – <dfn>Colloquium Personarum</dfn> <span class="loc">(PA2095)</span></li>

<li>Orberg, Hans H – <dfn>Lingua Latina</dfn> <span class="loc">(PA2095)</span></li>

<li>Simpson, D. P. – <dfn>Cassell's Latin Dictionary</dfn> <span class="loc">(PA2365.E5)</span></li>

<li>Landis, Paul – <dfn>Four Famous Greek Plays</dfn> <span class="loc">(PA3626.A2)</span></li>

<li>Aeschylus – <dfn>The Oresteia</dfn> <span class="loc">(PA3827.A7)</span></li>

<li>Apollonius of Rhodes – <dfn>Jason and the Argonauts (Argonautica)</dfn> <span class="loc">(PA3872)</span></li>

<li>Euripides – <dfn>Three Plays of Euripides: Alcestis, Medea, the Bacchae</dfn> <span class="loc">(PA3975)</span></li>

<li>Euripides – <dfn>Alcestis and Other Plays</dfn> <span class="loc">(PA3975.A5)</span></li>

<li>Corpus Hermeticum – <dfn>Hermes Trismegistus</dfn> <span class="loc">(PA3998)</span></li>

<li>Homer – <dfn>The Iliad</dfn> <span class="loc">(PA4025.A2)</span></li>

<li>Homer – <dfn>The Odyssey</dfn> <span class="loc">(PA4025.A5)</span></li>

<li>Sophocles – <dfn>The Theban Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>The Complete Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>Electra and Other Plays</dfn> <span class="loc">(PA4414.A2)</span></li>

<li>Feyerabend, Karl – <dfn>Greek-English Dictionary</dfn> <span class="loc">(PA445.E5)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Liddell, H. G. and Scott – <dfn>Greek-English Lexicon</dfn> <span class="loc">(PA445.E5)</span></li>

<li>Juvenal – <dfn>The Sixteen Satires</dfn> <span class="loc">(PA6447.E5)</span></li>

<li>Lucretius – <dfn>On the Nature of Things</dfn> <span class="loc">(PA6483.E5)</span></li>

<li>Hughes, Ted – <dfn>Tales from Ovid: Twenty-Four Passages from the 'Metamorphoses' by Ovid</dfn> <span class="loc">(PA6522)</span></li>

<li>Petronius – <dfn>the Satyricon and the Fragments</dfn> <span class="loc">(PA6558.E5)</span></li>

<li>Pliny the Younger – <dfn>Pliny: A Self-Portrait in Letters</dfn> <span class="loc">(PA6639.E5)</span></li>

<li>Virgil – <dfn>Aeneid</dfn> <span class="loc">(PA6807.A5)</span></li>

<li>Virgil – <dfn>The Pastoral Poems</dfn> <span class="loc">(PA6807.B7)</span></li>

</ul>
<h2 id="pc-romance-languages">PC: Romance Languages</h2>

<figure class="resright"><img src="/pix/lathrop.jpg" title="Lathrop's Course on Historical Spanish"></figure>

<ul class="booklist">
<li>Decker, Henry W. and Bernhard, Francoise – <dfn>Modern French</dfn> <span class="loc">(PC211)</span></li>

<li>Azevedo, Milton M. – <dfn>Introducción a la Lingüística Española</dfn> <span class="loc">(PC4073)</span></li>

<li>Lathrop, T. A. and Gutiérrex Cuadrado, Juan – <dfn>Curso de gramática histórica española</dfn> <span class="loc">(PC4101)</span></li>

<li>Moreno, Oscar – <dfn>Gramática avanzada del español</dfn> <span class="loc">(PC4129.E5)</span></li>

<li>Cash, Annette G. and Murray, James C. – <dfn>Teoría y técnicas de traduccón: primeras etapas</dfn> <span class="loc">(PC4498)</span></li>

<li>Gili Gaya, Samuel – <dfn>Vox: Diccionario abreviado de la lengua española</dfn> <span class="loc">(PC4625)</span></li>

</ul>
<h2 id="pd-pf-germanic-languages-and-literatures">PD-PF: Germanic Languages and Literatures</h2>
<ul class="booklist">
<li>Lambdin, Thomas O. – <dfn>An Introduction to the Gothic Language</dfn> <span class="loc">(PD1123)</span></li>

<li>Hugo – <dfn>Swedish Phrase Book</dfn> <span class="loc">(PD5121)</span></li>

<li>Warriner, John E. and Whitten, Mary E. and Friggith, Francis J. – <dfn>Warriner's English Grammar and Composition</dfn> <span class="loc">(PE1112)</span></li>

<li>Elson, William H. and Keck, Christine – <dfn>Elson Grammar School Literature Book Two</dfn> <span class="loc">(PE1121)</span></li>

<li>Mitchell, Brucew and Robinson, Fred C. – <dfn>A Guide to Old English</dfn> <span class="loc">(PE131)</span></li>

<li>Evans, Jonathan – <dfn>An Introduction to Old English</dfn> <span class="loc">(PE135)</span></li>

<li>Bright, James W. – <dfn>Bright's Anglo-Saxon Reader</dfn> <span class="loc">(PE137)</span></li>

<li>Gottschalk, Katherine and Keith Hjortshoj – <dfn>The Elements of Teaching Writing</dfn> <span class="loc">(PE1404)</span></li>

<li>Forsyth, Mark – <dfn>The Elements of Eloquence</dfn> <span class="loc">(PE1421)</span></li>

<li>McCloskey, Deirdre N. – <dfn>Economical Writing</dfn> <span class="loc">(PE1479.E35)</span></li>

<li>Sharp, Stanley Louis and Strothmann, Friedrich Wilhelm – <dfn>German Reading Grammar</dfn> <span class="loc">(PF3111)</span></li>

<li>Morgan, Baynard Quincy and Strothmann, Friedrich Wilhelm – <dfn>Reading German</dfn> <span class="loc">(PF3117)</span></li>

<li>Berlitz – <dfn>Berlitz Self-Teaching German</dfn> <span class="loc">(PF3121)</span></li>

</ul>
<h2 id="pj-pl-oriental-indo-iranian-east-asian-and-oceanian-languages">PJ-PL: Oriental, Indo-Iranian, East-Asian and Oceanian Languages</h2>

<figure class="resright"><img src="/pix/sastry.jpg" title="Sanskrit in the Development of World Thought"></figure>

<ul class="booklist">
<li>Anonymous – <dfn>The Epic of Gilgamesh</dfn> <span class="loc">(PJ3771.G5)</span></li>

<li>Wightwick, Jane and Gaafar, Mahmoud – <dfn>Mastering Arabic</dfn> <span class="loc">(PJ6307)</span></li>

<li>Luxenberg, Christoph – <dfn>The Syro-Aramaic Reading of the Koran: A Contribution to Decoding the Language of the Koran</dfn> <span class="loc">(PJ6696)</span></li>

<li>Burnell, Arthur Coke – <dfn>On the Aindra school of Sanskrit grammarians, their place in the Sanskrit and subordinate literatures</dfn> <span class="loc">(PK407)</span></li>

<li>Sastry, Vempaty Kutumba – <dfn>Sanskrit and Development of World Thought</dfn> <span class="loc">(PK423)</span></li>

<li>Elwell-Sutton, L. P. – <dfn>Elementary Persian Grammar</dfn> <span class="loc">(PK6235)</span></li>

<li>Whitney, William Dwight – <dfn>A Sanskrit Grammar: Including Both the Classical Language, and the Older Dialects, of the Veda and Brahmana</dfn> <span class="loc">(PK663)</span></li>

<li>Sutherland, Goldman – <dfn>Devavanipravesika</dfn> <span class="loc">(PK666)</span></li>

<li>Whitney, William Dwight – <dfn>The Roots, Verb-Forms, And Primary Derivatives of the Sankstrit Language: A Supplement to his Sanskrit Grammar</dfn> <span class="loc">(PK745)</span></li>

<li>DeFrancis, John – <dfn>Intermediate Chinese</dfn> <span class="loc">(PL11117)</span></li>

<li>DeFrancis, John – <dfn>Advanced Chinese</dfn> <span class="loc">(PL1121.C5)</span></li>

<li>Defense Language Institute – <dfn>Chinese: Basic Course</dfn> <span class="loc">(PL1125)</span></li>

<li>Seligman, Scott D. – <dfn>Mandarin Chinese at a Glance</dfn> <span class="loc">(PL1125.E6)</span></li>

<li>DeFrancis, John – <dfn>The Chinese Language, Fact and Fantasy</dfn> <span class="loc">(PL1171)</span></li>

<li><dfn>Oxford Chinese Dictionary</dfn> <span class="loc">(PL1455)</span></li>

<li>Waley, Arthur – <dfn>Translations from the Chinese</dfn> <span class="loc">(PL3277.E3)</span></li>

<li>Burlington, Scott – <dfn>Instant Hawaiian</dfn> <span class="loc">(PL6445)</span></li>

<li>Pukui, Mary Kawena and Elbert, Samuel H. and Mookini, Esther T. – <dfn>The Pocket Hawaiian Dictionary</dfn> <span class="loc">(PL6446)</span></li>

</ul>
<h2 id="pn-general-literature">PN: General Literature</h2>
<ul class="booklist">
<li>Butterworth, Hezekiah – <dfn>The Story of America</dfn> <span class="loc">(PN1009.A1)</span></li>

<li>Kaplar, Richard T. and Patrick D. Maines – <dfn>The Government Factor: Undermining Journalistic Ethics in the Information Age</dfn> <span class="loc">(PN4888.E8)</span></li>

<li>Schwarz, Leo W. – <dfn>Feast of Leviathan: Tales of Adventure, Faith and Love from Jewish Literature</dfn> <span class="loc">(PN6071.J5)</span></li>

<li><dfn>Treasury of Familiar Quotations</dfn> <span class="loc">(PN6081)</span></li>

<li><dfn>Reader's Digest Treasury of American Humor</dfn> <span class="loc">(PN6162)</span></li>

<li>The Onion – <dfn>Dispatches from the Tenth Circle</dfn> <span class="loc">(PN6165)</span></li>

<li>The Onion – <dfn>Our Dumb World</dfn> <span class="loc">(PN6231.A74)</span></li>

<li>Raymond, Eric S. – <dfn>The New Hacker's Dictionary</dfn> <span class="loc">(PN6231.E4)</span></li>

<li>The Onion – <dfn>Our Dumb Century</dfn> <span class="loc">(PN6231.N6)</span></li>

<li>Gómez Dávila, Nicolás – <dfn>Escolios a un texto implícito</dfn> <span class="loc">(PN6275)</span></li>

<li>Brown, Jeffrey – <dfn>Darth Vader and Son</dfn> <span class="loc">(PN6727.B7575)</span></li>

<li>Watterson, Bill – <dfn>Calvin and Hobbes: Scientific Progress Goes 'Boink'</dfn> <span class="loc">(PN6728.C34)</span></li>

<li>Lewis, C. S. – <dfn>The Discarded Image: An Introduction to Medieval and Renaissance Literature</dfn> <span class="loc">(PN671)</span></li>

</ul>
<h2 id="pq-romance-literature">PQ: Romance Literature</h2>

<figure class="resright"><img src="/pix/inferno.jpg"></figure>

<ul class="booklist">
<li>de Montaigne, Michel – <dfn>Montaigne Selected Essays</dfn> <span class="loc">(PQ1642.E6)</span></li>

<li>Morlière, Jean-Baptiste – <dfn>Tartuffe and Other Plays</dfn> <span class="loc">(PQ1842)</span></li>

<li>De Saint-Exupéry – <dfn>Sazadeo Qickek</dfn> <span class="loc">(PQ2637.A274)</span></li>

<li>Alighieri, Dante – <dfn>The Divine Comedy</dfn> <span class="loc">(PQ4315)</span></li>

<li>Alighieri, Dante – <dfn>The Inferno</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Alighieri, Dante – <dfn>I: Hell (Sayers translation)</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Eco, Umberto – <dfn>Foucault's Pendulum</dfn> <span class="loc">(PQ4864.C6)</span></li>

<li>De la Vega, Garcilaso – <dfn>Poesías</dfn> <span class="loc">(PQ6391)</span></li>

<li>Garcia Lorca, Federico – <dfn>Rosita la soltera</dfn> <span class="loc">(PQ6613.A763)</span></li>

<li>Pérez-Reverte, Arturo – <dfn>La tabla de Flandés</dfn> <span class="loc">(PQ6666.E765)</span></li>

<li>Rulfo, Juan &amp;ndash; Pedro – <dfn>y El Llano en llamas</dfn> <span class="loc">(PQ7297.R89)</span></li>

</ul>
<h2 id="pr-english-literature">PR: English Literature</h2>
<ul class="booklist">
<li>Clark, Thomas Curtis and Gillespie, Esther A. – <dfn>1000 Quotable Poems</dfn> <span class="loc">(PR1175)</span></li>

<li><dfn>Beowulf</dfn> <span class="loc">(PR1583)</span></li>

<li>Chaucer, Geoffrey – <dfn>Chaucer's Major Poetry</dfn> <span class="loc">(PR1851)</span></li>

<li>Chaucer, Geoffrey – <dfn>The Canterbury Tales</dfn> <span class="loc">(PR1870.A1)</span></li>

<li>Collis, Louise – <dfn>Memoirs of a Medieval Woman</dfn> <span class="loc">(PR2007)</span></li>

<li>Malory, Thomas – <dfn>Le Morte d'Arthur</dfn> <span class="loc">(PR2041)</span></li>

<li>Craig, W. J. – <dfn>The Complete Works of William Shakespeare</dfn> <span class="loc">(PR2753.C8)</span></li>

<li>Shakespeare, William – <dfn>Hamlet (2 copies)</dfn> <span class="loc">(PR2801.A2)</span></li>

<li>Shakespeare, William – <dfn>Macbeth</dfn> <span class="loc">(PR2823.A2)</span></li>

<li>Shakespeare, William – <dfn>A Midsummer Night's Dream</dfn> <span class="loc">(PR2827.A2)</span></li>

<li>Shakespeare, William – <dfn>The Merchant of Venice</dfn> <span class="loc">(PR2825.A2)</span></li>

<li>Shakespeare, William – <dfn>The Sonnets</dfn> <span class="loc">(PR2848.A2)</span></li>

<li>Crystal, David – <dfn>The Oxford Dictionary of Original Shakespearean Pronunciation</dfn> <span class="loc">(PR2892)</span></li>

<li>Bunyan, John – <dfn>Pilgrim's Progress</dfn> <span class="loc">(PR3330)</span></li>

<li>Milton, John – <dfn>Paradise Lost and Other Poems</dfn> <span class="loc">(PR3560)</span></li>

<li>Coleridge, Samuel Taylor – <dfn>The Rime of the Ancient Mariner</dfn> <span class="loc">(PR4479)</span></li>

<li>Dickens, Charles – <dfn>Great Expectations</dfn> <span class="loc">(PR4560)</span></li>

<li>Shaw, George Bernard – <dfn>Pygmalion</dfn> <span class="loc">(PR5363)</span></li>

<li>Stevenson, Robert Louis – <dfn>The Black Arrow</dfn> <span class="loc">(PR5484)</span></li>

<li>Stevenson, Robert Louis – <dfn>New Arabian Nights</dfn> <span class="loc">(PR5484)</span></li>

<li>Wells, H. G. – <dfn>The Island of Dr. Moreau</dfn> <span class="loc">(PR5774)</span></li>

<li>Wilde, Oscar – <dfn>The Importance of Being Earnest</dfn> <span class="loc">(PR5818)</span></li>

<li>Christie, Agatha – <dfn>Death on the Nile</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Christie, Agatha – <dfn>The Nursery Rhyme Murders</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Golding, William – <dfn>Lord of the Flies</dfn> <span class="loc">(PR6013.O35)</span></li>

<li>Lewis, C. S. – <dfn>The Lion, the Witch and the Wardrobe</dfn> <span class="loc">(PR6023.E926)</span></li>

<li>Huxley, Aldous – <dfn>Brave New World</dfn> <span class="loc">(PR6015.U9)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Lord of the Rings, One-Volume Edition</dfn> <span class="loc">(PR6039.O32)</span></li>

<li>White, T. H. – <dfn>The Once and Future King</dfn> <span class="loc">(PR6045.H2)</span></li>

<li>Adams, Douglas – <dfn>Life, the Universe and Everything</dfn> <span class="loc">(PR6051.D3352)</span></li>

<li>Erickson, Paul – <dfn>Doctor Who: The Ark</dfn> <span class="loc">(PR6052.R449)</span></li>

<li>Burgess, Anthony – <dfn>A Clockwork Orange</dfn> <span class="loc">(PR6052.U638)</span></li>

<li>Grimwade, Peter – <dfn>Doctor Who: Planet of Fire</dfn> <span class="loc">(PR6057.R545)</span></li>

<li>Halleck, Reuben Post – <dfn>History of English Literature</dfn> <span class="loc">(PR85)</span></li>

<li>Achebe, Chinua – <dfn>Things Fall Apart</dfn> <span class="loc">(PR9387.9.A3)</span></li>

</ul>
<h2 id="ps-american-literature">PS: American Literature</h2>

<figure class="resright"><img src="/pix/lovecraft.jpg"></figure>

<ul class="booklist">
<li>Twain, Mark – <dfn>A Connecticut Yankee in King Arthur's Court</dfn> <span class="loc">(PS1308)</span></li>

<li>Hawthorne, Nathaniel – <dfn>The Scarlet Letter</dfn> <span class="loc">(PS1868)</span></li>

<li>Poe, Edgar Allan – <dfn>Edgar Allan Poe Reader</dfn> <span class="loc">(PS2603)</span></li>

<li>Poe, Edgar Allen – <dfn>Tales of Terror and Detection</dfn> <span class="loc">(PS2612)</span></li>

<li>Thoreau, Henry David – <dfn>Walden</dfn> <span class="loc">(PS3048)</span></li>

<li>Wallace, Lew – <dfn>Ben Hur</dfn> <span class="loc">(PS3134)</span></li>

<li>Faulkner, William – <dfn>Light in August</dfn> <span class="loc">(PS3511.A86)</span></li>

<li>Fitzgerald, F. Scott – <dfn>The Great Gatsby</dfn> <span class="loc">(PS3511.I9)</span></li>

<li>Heinlein, Robert A. – <dfn>For Us, the Living</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Heinlein, Robert A. – <dfn>The Moon is a Harsh Mistress</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Lovecraft, H. P. – <dfn>Great Tales of Horror</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Case of Charles Dexter Ward</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Doom That Came to Sarnath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Dream Quest of Unknown Kadath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Tomb</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Rodgers, Marion Elizabeth – <dfn>Mencken &amp; Sara</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Mencken, H. L. – <dfn>The Vintage Mencken</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Rand, Ayn – <dfn>Atlas Shugged</dfn> <span class="loc">(PS3535.A547)</span></li>

<li>Skinner, B. F. – <dfn>Walden Two</dfn> <span class="loc">(PS3537.K527)</span></li>

<li>Smith, Clark Ashton – <dfn>Hyperborea</dfn> <span class="loc">(PS3537.M335)</span></li>

<li>Bear, Greg – <dfn>Darwin's Radio</dfn> <span class="loc">(PS3552.E157)</span></li>

<li>Card, Orson Scott – <dfn>Ender's Game</dfn> <span class="loc">(PS3553.A655)</span></li>

<li>Crichton, Michael – <dfn>Congo</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Jurassic Park</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Timeline</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Dick, Philip K. – <dfn>Dr. Bloodmoney</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Dick, Philip K. – <dfn>Flow My Tears, The Policeman Said</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Herbert, Frank – <dfn>Dune</dfn> <span class="loc">(PS3558.E63)</span></li>

<li>Jordan, Robert – <dfn>The Eye of the World</dfn> <span class="loc">(PS3560.O7617)</span></li>

<li>King, Stephen – <dfn>The Bazaar of Bad Dreams</dfn> <span class="loc">(PS3561.I483)</span></li>

<li>Myers, Bill – <dfn>Blood of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Fire of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Threshold</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Quinn, Daniel – <dfn>Ishmael: An Adventure of the Mind and Spirit</dfn> <span class="loc">(PS3567.U338)</span></li>

<li>Pearl, Matthew – <dfn>The Dante Club</dfn> <span class="loc">(PS3616.E25)</span></li>

<li>Asimov, Isaac – <dfn>Before the Golden Age: A Science Fiction Anthology of the 1930's</dfn> <span class="loc">(PS648.S3)</span></li>

<li>Saramago, José – <dfn>Todos los nombres</dfn> <span class="loc">(PS9281.A66)</span></li>

</ul>
<h2 id="pq-pz-other-literature">PQ-PZ: Other Literature</h2>

<figure class="resright"><img src="/pix/edda.jpg"></figure>

<ul class="booklist">
<li>Voltaire – <dfn>Candide, Zadig and selected stories</dfn> <span class="loc">(PQ2081.E5)</span></li>

<li>Hesse, Hermann – <dfn>Siddhartha</dfn> <span class="loc">(PT2617.E85)</span></li>

<li>Hesse, Hermann – <dfn>The Glass Bead Game</dfn> <span class="loc">(PT2617.E85 G513)</span></li>

<li>Sturluson, Snorri – <dfn>Poetic Edda</dfn> <span class="loc">(PT7235)</span></li>

<li>Sturluson, Snorri – <dfn>Prose Edda</dfn> <span class="loc">(PT7313.E5)</span></li>

<li>Borges, Jorge Luis – <dfn>Ficciones</dfn> <span class="loc">(PW7797.B635)</span></li>

<li>Connor, Ralph – <dfn>Black Rock: a Tale of the Selkirks</dfn> <span class="loc">(PZ3.G654)</span></li>

<li>Roberts, James Hall – <dfn>The Q Document</dfn> <span class="loc">(PZ4.D913)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Hobbit</dfn> <span class="loc">(PZ7.T5744)</span></li>

<li>Wilder, Laura Ingalls – <dfn>Little House (entire series)</dfn> <span class="loc">(PZ7.W6461)</span></li>

<li>Jacobs, Joseph – <dfn>Favorite Celtic Fairy Tales</dfn> <span class="loc">(PZ8)</span></li>

<li>Baum, L. Frank – <dfn>The Wizard of Oz</dfn> <span class="loc">(PZ8.B327)</span></li>

<li><dfn>The Brothers Grimm Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

<li><dfn>The Complete Grimm's Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

</ul>
<h2 id="qa-general-science">QA: General Science</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hVxvLd6cF0k"><img src="/pix/againstmethod.jpg"></a></figure>

<ul class="booklist">
<li>de Santillanna, Giorgio – <dfn>The Origins of Scientific Thought: from Anazimander to Proclus, 600 B.C. to 300 A.D.</dfn> <span class="loc">(Q125)</span></li>

<li>Gardner, Martin – <dfn>Great Essays in Science</dfn> <span class="loc">(Q171)</span></li>

<li>Kuhn, Thomas – <dfn>The Structure of Scientific Revolutions</dfn> <span class="loc">(Q175)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Wiener, Norbert – <dfn>The Human Use of Human Beings</dfn> <span class="loc">(Q175)</span></li>

<li>Feyerabend, Paul – <dfn>Against Method </dfn> <span class="loc">(Q175)</span></li>

<li>Motterlini, Matteo – <dfn>For and Against Method: Including Lakatos's Lectures on Scientific Method and the Lakatos-Feyerabend Correspondence </dfn> <span class="loc">(Q175.3)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Antifragile</dfn> <span class="loc">(Q375)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>The Black Swan</dfn> <span class="loc">(Q375)</span></li>

</ul>
<h2 id="qa-mathematics">QA: Mathematics</h2>
<ul class="booklist">
<li>Sawyer, W. W. – <dfn>Mathematician's Delight</dfn> <span class="loc">(QA37)</span></li>

<li>Birns, Peter and Brown, Patrick and Muster, John C. C. – <dfn>Unix for People</dfn> <span class="loc">(QA76.6)</span></li>

<li>Raymond, Eric S. – <dfn>The Cathedral and the Bazaar</dfn> <span class="loc">(QA76.76.O63)</span></li>

<li>Bellos, Alex – <dfn>Here's Looking at Euclid</dfn> <span class="loc">(QA141.15)</span></li>

<li>Nyberg, Joseph A. – <dfn>Second Course in Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Wentworth, G. A. – <dfn>New School Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Hart, William – <dfn>College Algebra</dfn> <span class="loc">(QA154)</span></li>

<li>Lial, Margaret L. and Miller, Charles D. – <dfn>Algebra and Trigonometry</dfn> <span class="loc">(QA154.2)</span></li>

<li>Sokal, Alan and Bricmont, Jean – <dfn>Fashionable Nonsense: Postmodern Intellectuals' Abuse of Science</dfn> <span class="loc">(QA175)</span></li>

<li>Neugebauer, Otto – <dfn>The Exact Sciences in Antiquity</dfn> <span class="loc">(QA22)</span></li>

<li>Bharati Krsna Thirthaji Maharaja – <dfn>Vedic Mathematics</dfn> <span class="loc">(QA27.I4)</span></li>

<li>Christian, Robert R. – <dfn>Introduction to Logic and Sets</dfn> <span class="loc">(QA248)</span></li>

<li>Davis, Morton D. – <dfn>Game Theory: A Nontechnical Introduction</dfn> <span class="loc">(QA269)</span></li>

<li>Friedman, Avner – <dfn>Differential Games</dfn> <span class="loc">(QA272)</span></li>

<li>Takahashi, Shin – <dfn>The Manga Guide to Statistics</dfn> <span class="loc">(QA276)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 1-10</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 10-15 and Appendices</dfn> <span class="loc">(QA303)</span></li>

<li>Smith, Edward S. and Salkover, Meyer and Justive, Howard K. – <dfn>Unified Calculus</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny – <dfn>Calculus with Analytic Geometry</dfn> <span class="loc">(QA33)</span></li>

<li>Sperling, Abraham and Stuart, Monroe – <dfn>Mathematics (Made Simple Self-Teaching Library)</dfn> <span class="loc">(QA39.2)</span></li>

<li>Horblit, Marcus and Nielson, Kaj L. – <dfn>Problems in Plane Geometry with Solutions</dfn> <span class="loc">(QA459)</span></li>

<li>Shively, Levi S. – <dfn>Modern Geometry</dfn> <span class="loc">(QA473)</span></li>

<li>Nelson, Alfred L. and Folley, Karl W. – <dfn>Plane and Spherical Trigonometry</dfn> <span class="loc">(QA531.N45)</span></li>

<li>Love, Clyde E. – <dfn>Analytic Geometry</dfn> <span class="loc">(QA551)</span></li>

<li>Hutton, Graham – <dfn>Programming in Haskell</dfn> <span class="loc">(QA76.62)</span></li>

<li>Kernighan, Brian W. and Ritchie, Dennis M. – <dfn>The C Programming Language</dfn> <span class="loc">(QA76.73.C15)</span></li>

<li>Barski, Conrad – <dfn>Land of Lisp</dfn> <span class="loc">(QA76.76.C672)</span></li>

<li>Hofstadter, Douglas – <dfn>Gödel, Escher, Bach</dfn> <span class="loc">(QA9.8)</span></li>

<li>Emmet, E. R. – <dfn>Brain Puzzler's Delight</dfn> <span class="loc">(QA95)</span></li>

<li>Emmet, E. R. – <dfn>Puzzles for Pleasure</dfn> <span class="loc">(QA95)</span></li>

<li>Gardner, Martin – <dfn>aha! Gotcha, Paradoxes to puzzle and delight</dfn> <span class="loc">(QA95)</span></li>

<li>Heafford, Philip – <dfn>The Math Entertainer</dfn> <span class="loc">(QA95)</span></li>

</ul>
<h2 id="qb-qr-other-sciences">QB-QR: Other Sciences</h2>
<ul class="booklist">
<li>Hawking, Stephen W. – <dfn>A Brief History of Time</dfn> <span class="loc">(QB981)</span></li>

<li>Lerner, Eric – <dfn>The Big Bang Never Happened</dfn> <span class="loc">(QB991.B54)</span></li>

<li>McEvoy, J. P. and Zarate, Oscar – <dfn>Quantum Theory, A Graphic Guide</dfn> <span class="loc">(QC173.98)</span></li>

<li>Booker, Christopher – <dfn>The Real Global Warming Disaster</dfn> <span class="loc">(QC981.8.G56)</span></li>

<li>Greenburg, Arthur – <dfn>From Alchemy to Chemistry in Picture and Story</dfn> <span class="loc">(QD11)</span></li>

<li>Valentine, Basil – <dfn>Of Natural and Supernatural Things: Also, of the First Tincture, Root, and Spirit of Metals and Minerals: How the Same are Conceived, Generated, Brought Forth, Changed and Augmented</dfn> <span class="loc">(QD25)</span></li>

<li>Watson, James – <dfn>The Double Helix</dfn> <span class="loc">(QH31.D434)</span></li>

<li>Fodor, Jerry and Piattelli Palmarini, Massimo – <dfn>What Darwin Got Wrong</dfn> <span class="loc">(QH375)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Kadans, Joseph M. – <dfn>Modern Encyclopedia of Herbs</dfn> <span class="loc">(QK99.A1)</span></li>

<li>McFarland, J. Horace – <dfn>Getting Acquainted with Trees</dfn> <span class="loc">(QK482)</span></li>

<li>Kurzweil, Ray – <dfn>The Singularity is Near</dfn> <span class="loc">(QP376)</span></li>

<li>Kandel, Eric R. and Schwartz, James H. and Jessell, Thomas M. – <dfn>Essentials of Neural Science and Behavior</dfn> <span class="loc">(QP355.2)</span></li>

</ul>
<h2 id="r-medicine">R: Medicine</h2>
<ul class="booklist">
<li>FC&amp;A – <dfn>The Folk Remedy Encyclopedia: Olive Oil, Vinegar, Honey and 1,001 Other Home Remedies</dfn> <span class="loc">(R733)</span></li>

<li><dfn>Better Homes and Gardens Family Medical Guide</dfn> <span class="loc">(RC81.A2)</span></li>

<li><dfn>The Encyclopedia of Common Diseases</dfn> <span class="loc">(RC81.A2)</span></li>

</ul>
<h2 id="s-t-agriculture-and-technology">S-T: Agriculture and Technology</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=YRNKjQg6y-c"><img src="/pix/salatin.jpg"></a></figure>

<ul class="booklist">
<li>Mollison, Bill – <dfn>Introduction to Permaculture</dfn> <span class="loc">(S494.5.P47)</span></li>

<li>Salatin, Joel – <dfn>Everything I Want to Do Is Illegal</dfn> <span class="loc">(S605.5)</span></li>

<li>David the Good – <dfn>Totally Crazy Easy Florida Gardening</dfn></li>

<li>Seymour, John – <dfn>The Complete Book of Self-Sufficiency</dfn> <span class="loc">(S605.5)</span></li>

<li>Cobleigh, Rolfe – <dfn>Handy Farm Devices and How to Make Them (2 copies)</dfn> <span class="loc">(S676)</span></li>

<li>Seymour, John – <dfn>Gardener's Delight</dfn> <span class="loc">(SB322)</span></li>

<li>Seymour, John – <dfn>The Self-Sufficient Gardener</dfn> <span class="loc">(SB324.3)</span></li>

<li>Haring, Elda – <dfn>The Seedling Handbook</dfn> <span class="loc">(SB405)</span></li>

<li>Abraham, George – <dfn>The Green Thumb Garden Handbook</dfn> <span class="loc">(SB453)</span></li>

<li><dfn>Reader's Digest Illustrated Guide to Gardening</dfn> <span class="loc">(SB453)</span></li>

<li>Kaczynski, Theodore John – <dfn>Technological Slavery</dfn> <span class="loc">(T14.5)</span></li>

<li>Kaczynski, Theodore John – <dfn>Anti-Tech Revolution: Why and How</dfn> <span class="loc">(T14.5)</span></li>

<li>Macaulay, David and Ardleym Neil – <dfn>The Way Things Work</dfn> <span class="loc">(T47)</span></li>

<li>Slater, Robert and Li, Ling and Li, Wen – <dfn>Portraits in Silicon</dfn> <span class="loc">(TK7885.2)</span></li>

<li>Bishop, Michael and Zimmerman, Holmes – <dfn>Detailing Cars and Trucks</dfn> <span class="loc">(TL152)</span></li>

<li>Allaby, Michael and Lovelock, James – <dfn>The Greening of Mars</dfn> <span class="loc">(TL795.7)</span></li>

<li>Abbey, Barbara – <dfn>The Complete Book of Knitting</dfn> <span class="loc">(TT820)</span></li>

<li>Bishop, Jack – <dfn>Vegetables Every Day</dfn> <span class="loc">(TX801)</span></li>

<li>Lo, Kenneth – <dfn>Chinese Regional Cooking</dfn> <span class="loc">(TX724.5.C5)</span></li>

</ul>
<h2 id="books-as-of-yet-unsorted">Books as of yet unsorted</h2>
<ul class="booklist">
<li>Seb Falk – <dfn>The Light Ages: The Surprising Story of Medieval Science</dfn></li>

<li><dfn>The Penny Catechism: A Catechism of Christian Doctrine</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese Reader, Part 1</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese</dfn></li>

<li>Flame Tree Publishing – <dfn>Gothic Fantasy: Lost Worlds Short Stories</dfn></li>

<li>Lee, Christopher – <dfn>This Sceptered Isle 55 BC to 1901</dfn></li>

<li>Malice, Michael – <dfn>Dear Reader</dfn></li>

<li>McCloskey, Deirdre N. – <dfn>Economic Writing</dfn></li>

<li>Meyer, Jerome S. – <dfn>The Provocative Puzzler</dfn></li>

<li>Parikh, Prashant – <dfn>Language and Equilibrium</dfn></li>

<li>Reed, Lawrence W. – <dfn>Great Myths of the Great Depression</dfn></li>

<li><dfn>Using HTML4, Java 1.1, and Javascript 1.2</dfn></li>

<li>Valizadeh, Roosh – <dfn>Game</dfn></li>

<li>Vikernes, Varg – <dfn>MYFAROG 2.6</dfn></li>

</ul>
<div style="clear:both" class="taglist">Read related articles:<br><a id="tag_personal" href="https://lukesmith.xyz/tags/personal">Personal</a> · <a id="tag_science" href="https://lukesmith.xyz/tags/science">Science</a> · <a id="tag_tradition" href="https://lukesmith.xyz/tags/tradition">Tradition</a> · <a id="tag_lifestyle" href="https://lukesmith.xyz/tags/lifestyle">Lifestyle</a> · <a id="tag_philosophy" href="https://lukesmith.xyz/tags/philosophy">Philosophy</a></div>
<br clear="both">
</article>
</main>
<footer>
	<a href="https://lukesmith.xyz">https://lukesmith.xyz</a>

	<p>
	<img class="lw" src="/pix/btc.svg">Bitcoin (<a href="/pix/btc-logo.png">QR</a>): <code>bc1qkyvknjap3cjtgfqd5qwc0q2ygry7nep7d4t57y</code>
	<br>
	<img class="lw" src="/pix/xmr.svg">Monero (<a href="/pix/xmr-logo.png">QR</a>): <code class="crypto">48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh</code>
	</p><p><a href="/index.xml"><img src="/rss.svg" style="max-height:1.5em" alt="RSS Feed" title="Subscribe via RSS for updates."></a>
</p></footer>


</body>
<main>
<a href="/"><header>
	<h1 id="tag_My Personal Library">My Personal Library</h1>
</header></a>
<article>
<p>This is a list of the books in my personal library. If you have any
questions or want me to review any of them, email me
(<a href="mailto:luke@lukesmith.xyz">luke@lukesmith.xyz</a>).</p>
<p>I haven't read every book here, nor do I own all the books I've read
or like. I also don't necessarily like all the books I own.</p>
<p>Check out <a href="https://notrelated.xyz">my podcast, <em>Not Related!</em></a>
for some book reviews and other things. Books I've talked about in one
way or another in the podcast will have a link to that episode.</p>
<h2 id="-lindypressnet-books">🆕 LindyPress.net Books</h2>
<p>Note that now I am reprinting out-of-print works at
<a href="https://lindypress.net">LindyPress.net</a>. You can buy any of these books
yourself if you'd like. (Most of them are pretty exclusive in that I'm
the only one reprinting them.)</p>
<ul>
<li>Pseudo-Aristotle – <a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a></li>
<li><a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a></li>
<li>Isidore of Seville – <a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a></li>
<li>Roger Bacon ‐ <a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a></li>
<li>Marcus Aurelius – <a href="https://lindypress.net/book?pk=2">Meditations</a></li>
<li><a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a></li>
</ul>
<p>(These are at the top since I don't know if anyone has given them Library of
Congress numbers, and I suppose as an ad.)</p>
<h2 id="a-bd-general-works-philosophy-logic-speculative-philosophy">A-BD: General Works, Philosophy, Logic, Speculative Philosophy</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hCVdCS0t46I"><img src="/pix/searle.jpg" title="Searle (actually literally) did nothing wrong."></a></figure>

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
<h2 id="bm-bx-specific-religions-and-theology">BM-BX: Specific Religions and Theology</h2>

<figure class="resright"><img src="/pix/biglot.jpg" title="A Greek and Latin biglottic Bible"></figure>

<ul class="booklist">
<li><dfn>'תְּהִלַּת ה</dfn> <span class="loc">(BM675/D3)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Key to Theosophy</dfn> <span class="loc">(BP561)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Voice of Silence</dfn> <span class="loc">(BP561)</span></li>

<li>Wright, Stuart – <dfn>Armageddon in Waco</dfn> <span class="loc">(BP605.B62)</span></li>

<li>Lewis, C. S. – <dfn>Mere Christianity</dfn> <span class="loc">(BR123)</span></li>

<li>Lewis, C. S. – <dfn>The Screwtape Letters</dfn> <span class="loc">(BR125)</span></li>

<li>Reardon, Patrick Henry – <dfn>Christ in the Psalms</dfn> <span class="loc">(BS1430.4)</span></li>

<li>Leithart, Peter J. – <dfn>Solomon Among the Postmoderns</dfn> <span class="loc">(BS1475.52)</span></li>

<li>Porter, J. R. – <dfn>The Lost Bible</dfn> <span class="loc">(BS1700)</span></li>

<li>Heiser, Michael – <dfn>Reversing Hermon: Enoch, the Watchers and the Forgotten Mission of Jesus Christ</dfn> <span class="loc">(BS1830.E7)</span></li>

<li><dfn>The New Oxford Annotated Bible</dfn> <span class="loc">(BS191.5.A1)</span></li>

<li><dfn>The New English Bible</dfn> <span class="loc">(BS192.A1)</span></li>

<li>Montano, Arias and Leudsen, Johann – <dfn>Greek-Latin Parallel New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>Pocket Interlinear New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>The New International Dictionary of New Testament Theology (3 Volumes)</dfn> <span class="loc">(BS2312)</span></li>

<li><dfn>Ἡ Καινὴ Διαθήκη</dfn> <span class="loc">(BS2312)</span></li>

<li>Kümmel, Werner Georg – <dfn>Introduction to the New Testament</dfn> <span class="loc">(BS2330)</span></li>

<li>Aland, Kurt – <dfn>Synopsis Quattuor Evangeliorum</dfn> <span class="loc">(BS2560.A2)</span></li>

<li>Mack. Burton L. – <dfn>A Myth of Innocence</dfn> <span class="loc">(BS2585.2)</span></li>

<li>Ehrman, Bart D. – <dfn>Lost Christianities: The Battles for Scriptures and the Faiths We Never Knew</dfn> <span class="loc">(BS2840.E4)</span></li>

<li>Luther, Martin – <dfn>Luther's Small Catechism with Additions Including the Augsburg Confession</dfn> <span class="loc">(BR331.K64)</span></li>

<li>Strong, James – <dfn>Strong's Exhaustive Concordance of the Bible with Hebrew and Greek Dictionaries</dfn> <span class="loc">(BS425)</span></li>

<li><dfn>Illustrated Dictionary and Concordance of the Bible</dfn> <span class="loc">(BS440)</span></li>

<li>McDowell, Josh – <dfn>The New Evidence that Demands a Verdict</dfn> <span class="loc">(BS480)</span></li>

<li>Laymon, Charles M. – <dfn>The Interpreter's One-Volume Commentary on the Bible</dfn> <span class="loc">(BS491.2)</span></li>

<li>Cross, John R. – <dfn>The Stranger on the Road to Emmaus</dfn> <span class="loc">(BS511.2)</span></li>

<li><dfn>Reader's Digest Mysteries of the Bible; the Enduring Questions of the Scriptures</dfn> <span class="loc">(BS538)</span></li>

<li>Smith, Brendan Powell – <dfn>The Brick Bible</dfn> <span class="loc">(BS550.3)</span></li>

<li>Kent, Paul and McLaughlan, David – <dfn>Know Your Bible: All 66 Books Explained and Applied</dfn> <span class="loc">(BS593)</span></li>

<li><dfn>Septuagint with Apocrypha</dfn> <span class="loc">(BS742)</span></li>

<li><dfn>Biblia Sacra Vulgata</dfn> <span class="loc">(BS75)</span></li>

<li>Newman, John Henry – <dfn>An Essay on the Development of Christian Doctrine</dfn> <span class="loc">(BT21)</span></li>

<li>Robinson, James M. – <dfn>The Nag Hammadi Library</dfn> <span class="loc">(BT1391)</span></li>

<li>Lewis, C. S. – <dfn>Surprised by Joy: The Shape of My Early Life</dfn> <span class="loc">(BV4935.L43)</span></li>

<li>Carman, Stephen L. and Owen, Bob – <dfn>Quest: The Story of an Aerospace Engineer who Challenged God to Prove Himself</dfn> <span class="loc">(BV4930)</span></li>

<li>Ware, Timothy – <dfn>The Orthodox Church</dfn> <span class="loc">(BX106)</span></li>

<li>Aveling, J. C. H. – <dfn>The Jesuits</dfn> <span class="loc">(BX3706.2)</span></li>

<li><dfn>The Book of Common Prayer</dfn> <span class="loc">(BX5145)</span></li>

<li><dfn>Five Great Encyclicals: Labor, Education, Marriage, Reconstructing the Social Order, Atheistic Communism</dfn> <span class="loc">(BX860)</span></li>

</ul>
<h2 id="c-auxiliary-sciences-of-history">C: Auxiliary Sciences of History</h2>
<ul class="booklist">
<li>Graeber, David and Wengrow, David – <dfn>The Dawn of Everything: A New History of Humanity</dfn> <span class="loc">(CB19)</span></li>

<li>McNeill, William H. – <dfn>The Rise of the West: A History of the Human Community</dfn> <span class="loc">(CB59)</span></li>

<li>Sitchin, Zecharia – <dfn>The 12th Planet</dfn> <span class="loc">(CB156)</span></li>

<li>Rohl, David – <dfn>The Lords of Avaris: Uncovering the Legendary Origins of Western Civilization</dfn> <span class="loc">(CB245)</span> <a href="https://notrelated.xyz/#02.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Casson, Lionel and Clairborne, Robert and Fagan, Brian and Karp, Walter – <dfn>Mysteries of the Past</dfn> <span class="loc">(CB311)</span></li>

<li>Fisher, Marshall John and Fisher, David E. – <dfn>Mysteries of Lost Empires</dfn> <span class="loc">(CB311)</span></li>

<li>Hawkes, Jacquetta – <dfn>The Atlas of Early Man</dfn> <span class="loc">(CB311)</span></li>

<li>Platt, Richard and Riddell, Chris – <dfn>Castle Diary</dfn> <span class="loc">(CB351)</span></li>

<li>Cahill, Thomas – <dfn>Mysteries of the Middle Ages</dfn> <span class="loc">(CB351)</span></li>

</ul>
<h2 id="d-world-history">D: World History</h2>

<figure class="resright"><img src="/pix/racehutton.jpg" title="Hutton's book on the Third Reich"></figure>

<ul class="booklist">
<li>Malesky, Kee – <dfn>All Facts Considered, the Essential Library of Inessential Knowledge</dfn> <span class="loc">(D10)</span></li>

<li>Evola, Julius – <dfn>Revolt Against the Modern World</dfn> <span class="loc">(D16.8)</span></li>

<li>Epstein, Steven A. – <dfn>An Economic and Social History of Later Medieval Europe, 1000-1500</dfn> <span class="loc">(D117)</span></li>

<li>Pirenne, Henri – <dfn>A History of Europe</dfn> <span class="loc">(D117)</span></li>

<li>Cantor, Nroman F. – <dfn>Medieval History: The Life and Death of a Civilization</dfn> <span class="loc">(D118)</span></li>

<li>Roberts, J. M. – <dfn>New History of the World</dfn> <span class="loc">(D20)</span></li>

<li>Mann, Charles C. – <dfn>1493, Uncovering the New World Columbus Created</dfn> <span class="loc">(D228)</span></li>

<li>Rogan, Eugene L. – <dfn>The FAll of the Ottomans: The Great War in the Middle East</dfn> <span class="loc">(D566)</span></li>

<li>Sanborn, Frederick R. – <dfn>Design for War: A Study of Secret Power Politics</dfn> <span class="loc">(D742.U5)</span></li>

<li>Cheyney, Edward P. – <dfn>A Short History of England</dfn> <span class="loc">(DA32)</span></li>

<li>Thomas, Charles – <dfn>Celtic Britain</dfn> <span class="loc">(DA140)</span></li>

<li>Sellar, W.C. &amp; Yeatman R.J. – <dfn>1066 and All That</dfn> <span class="loc">(DA33)</span></li>

<li>Freeman, John and Sharpe, Sue – <dfn>This Beautiful Land: Britain</dfn> <span class="loc">(DA632)</span></li>

<li>Hutton, Christopher – <dfn>Race and the Third Reich</dfn> <span class="loc">(DD253)</span></li>

<li>Tacitus, C. Cornellius – <dfn>Annales et Historiae</dfn> <span class="loc">(DG207.T3)</span></li>

<li>Shirer, William L. – <dfn>The Rise and Fall of the Third Reich</dfn> <span class="loc">(DD256.5)</span></li>

<li>MacDonald, Kevin – <dfn>The Culture of Critique: An Evolutionary Analysis of Jewish Involvement in Twentieth-Century Intellectual and Political Movements</dfn> <span class="loc">(DS143)</span></li>

<li>Ford, Henry Sr. – <dfn>The International Jew: The World's Foremost Problem</dfn> <span class="loc">(DS145)</span></li>

<li>Ali, Tariq – <dfn>The Duel: Pakistan on the Flight Path of American Power</dfn> <span class="loc">(DS384)</span></li>

<li>De Bary, William Theodore – <dfn>The Sources of Indian Tradition</dfn> <span class="loc">(DS423)</span></li>

<li>Keay, John – <dfn>India, A History</dfn> <span class="loc">(DS451)</span></li>

<li>Ebrey, Patricia Buckley – <dfn>Cambridge Illustrated History of China</dfn> <span class="loc">(DS706)</span></li>

<li>National Geographic Society – <dfn>Journey into China</dfn> <span class="loc">(DS712)</span></li>

</ul>
<h2 id="e-f-history-of-the-americas">E-F: History of the Americas</h2>

<figure class="resright"><img src="/pix/foxfire.jpg"></figure>

<ul class="booklist">
<li>Hancock, Graham – <dfn>America Before: The Key to Earth's Lost Civilization</dfn> <span class="loc">(E61)</span></li>

<li>Little, Gregory – <dfn>Path of Souls: The Native American Death Journey: Cygnus, Orion, the Milky Way, Giant Skeletons in Mounds, &amp; the Smithsonian</dfn> <span class="loc">(E98.M8)</span></li>

<li>Mooney, James – <dfn>Myths of the Cherokee</dfn> <span class="loc">(E99.C5)</span></li>

<li>Greenblatt, Stephen – <dfn>New World Encounters</dfn> <span class="loc">(E141)</span></li>

<li>Fischer, David Hackett – <dfn>Albion's Seed: Four British Folkways in America</dfn> <span class="loc">(E169.1)</span> <a href="https://notrelated.xyz/#01.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Sowell, Thomas – <dfn>Ethnic America</dfn> <span class="loc">(E184.A1)</span></li>

<li>Hurmence, Belinda – <dfn>Before Freedom: 48 Oral Histories of Former North and South Carolina Slaves</dfn> <span class="loc">(E444)</span></li>

<li>Adams, Nehemiah – <dfn>A South-side View of Slavery: or Three Months at the South in 1854</dfn> <span class="loc">(E449)</span></li>

<li>Parsons, Charles Grandison – <dfn>An Inside View of Slavery; or A Tour Among the Planters</dfn> <span class="loc">(E449)</span></li>

<li>Long, A. L. – <dfn>Memoirs of Robert E. Lee</dfn> <span class="loc">(E467.1.L4)</span></li>

<li>Henry, Robert Selph – <dfn>The Story of the Confederacy</dfn> <span class="loc">(E487)</span></li>

<li>Mann, Charles C. – <dfn>1491, New Revelations of the Americas Before Columbus</dfn> <span class="loc">(E61)</span></li>

<li>Wharton, H. M. – <dfn>War Songs and Poems of the Southern Confederacy, 1861-1865: a Collection of the Most Popular and Impressive Songs and Poems of War Times, Dear to Every Southern Heart</dfn> <span class="loc">(E647)</span></li>

<li><dfn>The Blue Book of the John Birch Society</dfn> <span class="loc">(E743.5)</span></li>

<li>Stormer, John A. – <dfn>The Death of a Nation</dfn> <span class="loc">(E743.5)</span></li>

<li>Ramo, Joshua Cooper – <dfn>The Age of the Unthinkable</dfn> <span class="loc">(E902)</span></li>

<li>de las Casas, Bartolomé – <dfn>Brevisima relación de la destrución de las Indias</dfn> <span class="loc">(F1411)</span></li>

<li><dfn>The Foxfire Book</dfn> <span class="loc">(F291.2)</span></li>

<li><dfn>The Foxfire Book 2</dfn> <span class="loc">(F291.2)</span></li>

</ul>
<h2 id="g-geography-anthropology-recreation">G: Geography, Anthropology, Recreation</h2>
<ul class="booklist">
<li>Winer, Richard – <dfn>Ghost Ships: True Stories of Nautical Nightmares, Hauntings, and Disasters</dfn> <span class="loc">(G525)</span></li>

<li><dfn>National Geographic Collegiate Atlas of the World</dfn> <span class="loc">(G1021)</span></li>

<li>Wells, Spencer – <dfn>Pandora's Seed: The Unforeseen Cost of Civilization</dfn> <span class="loc">(GF75)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cochran, Gregory and Harpending, Henry – <dfn>the 10,000 Explosion: How Civilization Accelerated Human Evolution</dfn> <span class="loc">(GN281.4)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cremo, Michael A. &amp; Thompson, Ricahrd L. – <dfn>Forbidden Archaeology: The Hidden History of the Human Race</dfn> <span class="loc">(GN741)</span></li>

<li>Hancock, Graham – <dfn>Magicians of the Gods: The Forgotten Wisdom of Earth's Lost Civilization</dfn> <span class="loc">(GN751)</span></li>

<li>Cayce, Hugh Lynn – <dfn>Edgar Cayce on Atlantis</dfn> <span class="loc">(GN751.C35)</span></li>

<li>Marshack, Alexander – <dfn>The Roots of Civilization: The Cognitive Beginnings of Man's First Art, Symbol and Notation</dfn> <span class="loc">(GN772)</span></li>

<li>Bord, Janet and Bord, Colin – <dfn>Prehistoric Britain from the Air</dfn> <span class="loc">(GN805)</span></li>

<li>Bruce, Annette J. – <dfn>More Tellable Cracker Tales</dfn> <span class="loc">(GR110.F5)</span></li>

</ul>
<h2 id="h-social-sciences">H: Social Sciences</h2>
<p>
</p><figure class="resright"><img src="/pix/democracy.jpg"></figure>


<figure class="resright"><img src="/pix/pike.jpg"></figure>
<p></p>
<ul class="booklist">
<li>Greenspan, Alan – <dfn>The Age of Turbulence</dfn> <span class="loc">(HB119.G74)</span></li>

<li>Hazlitt, Hentry – <dfn>Economics in One Lesson (two copies)</dfn> <span class="loc">(HB171)</span></li>

<li>Keynes, John Maynard – <dfn>The General Theory of Employment, Interest and Money</dfn> <span class="loc">(HB171)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Rothbard, Murray – <dfn>Man, Economy and State with Power and Market</dfn> <span class="loc">(HB171)</span></li>

<li>von Mises, Ludwig – <dfn>Economic Policy</dfn> <span class="loc">(HB171)</span></li>

<li>Boulding, Kenneth E. – <dfn>Economic Analysis</dfn> <span class="loc">(HB171.5)</span></li>

<li>Goodman, Kennard E. and Moore, William L. – <dfn>Economics in Everyday Life</dfn> <span class="loc">(HB171.5)</span></li>

<li>Pindyck, Robert S. and Rubinfeld, Daniel L. – <dfn>Microeconomics</dfn> <span class="loc">(HB172)</span></li>

<li>Fisher, David Hackett – <dfn>The Great Wave: Price Revolutions and the Rhythm of History</dfn> <span class="loc">(HB231)</span></li>

<li>Soros, George – <dfn>The Crash of 2008 and What It Means</dfn> <span class="loc">(HB3722)</span> <a href="https://notrelated.xyz/#02.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Keen, Steve – <dfn>Debunking Economics: The Naked Emperor Dethroned?</dfn> <span class="loc">(HB71)</span></li>

<li>Krugman, Paul – <dfn>The Accidental Theorist</dfn> <span class="loc">(HB74.5)</span></li>

<li>Hoppe, Hans Hermann – <dfn>Democracy: The God That Failed: The Economics and Politics of Monarchy, Democracy and Natural Law</dfn> <span class="loc">(HB74.P65)</span></li>

<li>Ekelund, Robert B. Jr. and Hébert, Robert F – <dfn>A History of Economic Theory and Method</dfn> <span class="loc">(HB75)</span></li>

<li>Buchholz, Todd G. – <dfn>New Ideas from Dead Economists, an Introduction to Modern Economic Thought</dfn> <span class="loc">(HB76)</span></li>

<li>Heilbroner, Robert L. – <dfn>The Worldly Philosophers</dfn> <span class="loc">(HB76)</span></li>

<li>Paul Erlich – <dfn>The Population Bomb</dfn> <span class="loc">(HB875.E35)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Palmer, Tom G. – <dfn>After the Welfare State</dfn> <span class="loc">(HB99.3)</span></li>

<li>Krugman, Paul – <dfn>Peddling Prosperity</dfn> <span class="loc">(HB99.7)</span></li>

<li>Walton, Gary M. and Rockoff, Hugh – <dfn>History of the American Economy</dfn> <span class="loc">(HC103)</span></li>

<li>Krugman, Paul – <dfn>The Great Unravelling</dfn> <span class="loc">(HC106)</span></li>

<li>Krugman, Paul – <dfn>The Conscience of a Liberal</dfn> <span class="loc">(HC110.I5)</span></li>

<li>Clark, Gregory – <dfn>A Farewell to Alms</dfn> <span class="loc">(HC21)</span></li>

<li>Easterly, William – <dfn>The Elusive Quest for Growth</dfn> <span class="loc">(HC59.72.P6)</span></li>

<li>Simon, Julian L. and Kahn, Herman – <dfn>The Resourceful Earth</dfn> <span class="loc">(HC59.R445)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Dixit, Avinash K. and Nalebuff, Barry J. – <dfn>Thinking Strategically, The Competitive Edge in Business, Politics, and Everyday Life</dfn> <span class="loc">(HD30.28)</span></li>

<li>Adams, Scott – <dfn>The Dilbert Principle</dfn> <span class="loc">(HD31)</span></li>

<li>Ehrenreich, Barbara – <dfn>Nickel and Dimed</dfn> <span class="loc">(HD4918)</span></li>

<li>Thiel, Peter – <dfn>Zero to One: Notes on Start-Ups, or How to Build the Future</dfn> <span class="loc">(HD62.5)</span></li>

<li>Montgomery, David – <dfn>Beyond Equality: Labor and the Radical Republicans 1862-1872</dfn> <span class="loc">(HD8076)</span></li>

<li>Caplan, Bryan – <dfn>The Myth of the Rational Voter: Why Democracies Choose Bad Policies</dfn> <span class="loc">(HD87)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bhagwati, Jagdish – <dfn>In Defense of Globalization</dfn> <span class="loc">(HF1359)</span></li>

<li>Krugman, Paul and Obstfield, Maurice – <dfn>International Economics</dfn> <span class="loc">(HF1359)</span></li>

<li>Lechner, Frank J. and Boli, John – <dfn>The Globalization Reader</dfn> <span class="loc">(HF1359)</span></li>

<li>Myrdal, Gunnar – <dfn>Beyond the Welfare State</dfn> <span class="loc">(HF1411)</span></li>

<li>Graeber, David – <dfn>Bullshit Jobs: A Theory</dfn> <span class="loc">(HF5549.5.J63)</span> <a href="https://notrelated.xyz/#02.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Soros, George – <dfn>In Defense of Open Society</dfn> <span class="loc">(HG172.S63)</span></li>

<li>Boortz, Neal and Linder, John – <dfn>The Fairtax Book: Saying Goodbye to the Income Tax and the IRS</dfn> <span class="loc">(HJ4652)</span></li>

<li>Stove, David – <dfn>Darwinian Fairytales</dfn> <span class="loc">(HM106)</span></li>

<li>O'Brien, Jodi – <dfn>The Production of Reality</dfn> <span class="loc">(HM1033)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Skin in the Game</dfn> <span class="loc">(HM1101)</span></li>

<li>Berne, Eric – <dfn>Games People Play</dfn> <span class="loc">(HM1106)</span></li>

<li>Pinker, Steven – <dfn>The Better Angels of Our Nature</dfn> <span class="loc">(HM1116)</span></li>

<li>Kropotkin, Peter – <dfn>Mutual Aid: A Factor of Evolution</dfn> <span class="loc">(HM131)</span></li>

<li>Diamond, Jared – <dfn>Guns, Germs and Steel</dfn> <span class="loc">(HM206)</span></li>

<li>Bork, Robert H. – <dfn>Slouching Towards Gomorrah: Modern Liberalism and American Decline</dfn> <span class="loc">(HN59.2)</span></li>

<li>Arnold, Matthew – <dfn>Culture and Anarchy</dfn> <span class="loc">(HN389)</span></li>

<li>Jones, E. Michael – <dfn>Libido Dominandi: Sexual Liberation and Political Control</dfn> <span class="loc">(HQ472.U6)</span></li>

<li>Eisler, Riane – <dfn>The Chalice and the Blade, Our History, Our Future</dfn> <span class="loc">(HQ1075)</span></li>

<li>Harris, Judith Rich – <dfn>The Nurture Assumption</dfn> <span class="loc">(HQ772)</span></li>

<li>Beuerlein, Mark – <dfn>The Dumbest Generation</dfn> <span class="loc">(HQ799.7)</span></li>

<li>Street, Oliver Day – <dfn>Symbolism of the Three Degrees</dfn> <span class="loc">(HS425)</span></li>

<li><dfn>Morals and Dogma of the Ancient and Accepted Scottish Rite of Freemasonry</dfn> <span class="loc">(HS767)</span></li>

<li><dfn>The 9/11 Commission Report: Final Report of the National Commission on Terrorist Attacks upon the United States</dfn> <span class="loc">(HV6432.7)</span></li>

<li>Engels, Frederick – <dfn>Socialism: Utopian and Scientific</dfn> <span class="loc">(HX276)</span></li>

<li>Hayek, F. A. – <dfn>The Intellectuals and Socialism</dfn> <span class="loc">(HX528)</span></li>

<li>More, Thomas – <dfn>Utopia</dfn> <span class="loc">(HX810.5)</span></li>

<li>Stringham, Edward P. – <dfn>Anarchy and the Law</dfn> <span class="loc">(HX833)</span></li>

<li>Schumpeter, Joseph Alois – <dfn>Capitalism, Socialism and Democracy</dfn> <span class="loc">(HX86)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bastiat, Frederic – <dfn>The Law</dfn> <span class="loc">(HX87)</span></li>

</ul>
<h2 id="j-k-political-science-and-law">J-K: Political Science and Law</h2>

<figure class="resright"><img src="/pix/archeofuturism.jpg"></figure>

<ul class="booklist">
<li>Faye, Guillaume – <dfn>Archeofuturism: European Visions of the Post-Catastrophic Age</dfn> <span class="loc">(JA84.F8)</span></li>

<li>Plato – <dfn>The Republic</dfn> <span class="loc">(JC71)</span></li>

<li>Machiavelli, Niccolò – <dfn>The Prince and Other Writings</dfn> <span class="loc">(JC143)</span></li>

<li>Hobbes, Thomas – <dfn>Leviathan</dfn> <span class="loc">(JC153)</span></li>

<li>Filmer, Robert – <dfn>Patriarcha, or, The Natural Power of Kings</dfn> <span class="loc">(JC153.F48)</span></li>

<li>Samons, Loren J. – <dfn>What's Wrong with Democracy?</dfn> <span class="loc">(JC421)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Mill, John Stewart – <dfn>On Liberty</dfn> <span class="loc">(JC585)</span></li>

<li>Reed, Lawrence W. – <dfn>Are We Good Enough for Liberty?</dfn> <span class="loc">(JC585)</span></li>

<li>Jeffery, – <dfn>People's War: New Light on the Struggle for South Africa</dfn> <span class="loc">(JQ1998.A4)</span></li>

<li>Beard, Charles – <dfn>An Economic Interpretation of the Constitution of the United States</dfn> <span class="loc">(JK146)</span></li>

<li>Smith, Bradley A. – <dfn>Unfree Speech: The Folly of Campaign Finance Reform</dfn> <span class="loc">(JK1991)</span></li>

<li>de Tocqueville, Alexis – <dfn>Democracy in America</dfn> <span class="loc">(JK216)</span></li>

<li>Brimelow, Peter – <dfn>Alien Nation: Common Sense about America's Immigration Disaster</dfn> <span class="loc">(JV6493)</span></li>

<li>Fukuyama, Francis – <dfn>America at the Crossroads: Democracy, Power and Neoconservative Legacy</dfn> <span class="loc">(JZ1480)</span></li>

<li>Silverglate, Harvey A. and French, David A. and Lukianoff, Greg – <dfn>FIRE's Guide to Free Speech on Campus</dfn> <span class="loc">(KF4123.5)</span></li>

<li>Bernstein, David E. – <dfn>You Can't Say That!</dfn> <span class="loc">(KF4749)</span></li>

</ul>
<h2 id="l-n-education-music-fine-arts">L-N: Education, Music, Fine Arts</h2>
<ul class="booklist">
<li>Bloom, Allan – <dfn>The Closing of the American Mind: How Higher Education Has Failed Democracy and Impoverished the Souls of Today's Students</dfn> <span class="loc">(LA227.3)</span></li>

<li>Russell, Bertrand – <dfn>Education and the Good Life</dfn> <span class="loc">(LB775)</span></li>

<li><dfn>Baptist Hymnal</dfn> <span class="loc">(M2122)</span></li>

<li>Towner, D. B., Lorenz, E. S. and Wilson, Ira B. – <dfn>Songs of Praise: A Collection of Gospel Songs for Men's Voices</dfn> <span class="loc">(M2198)</span></li>

<li>International Graphic Society – <dfn>The Arts of Mankind: Painting, Architecture, Music</dfn> <span class="loc">(N5302)</span></li>

<li>Barral i Altet, Xavier – <dfn>The Early Middle Ages: From Late Antiquity to A.D. 1000</dfn> <span class="loc">(NA350)</span></li>

<li>Churchill, Winston S. – <dfn>Painting as a Pastime: An instructive and inspiring invitation to the joy of painting</dfn> <span class="loc">(ND1142)</span></li>

<li>Cornelius, Maurits – <dfn>The Graphic Work of M.C. Escher</dfn> <span class="loc">(NE670.E75)</span></li>

</ul>
<h2 id="p-philology-linguistics">P: Philology, Linguistics</h2>

<figure class="resright"><img src="/pix/westernclassical.jpg" title="Good for learning some #Lindy linguistics"></figure>

<ul class="booklist">
<li>Smith, Luke – <dfn>External Possession and the Undisentanglability of Syntax and Semantics</dfn></li>

<li>Chomsky, Noam – <dfn>Language and Mind</dfn> <span class="loc">(P106)</span></li>

<li>Harris, Roy – <dfn>Language, Saussure and Wittgenstein, How to Play Games with Words</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>Words and Rules, the Ingredients of Language</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>The Stuff of Thought</dfn> <span class="loc">(P107)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: I Linguistic Theory: Foundations</dfn> <span class="loc">(P121)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: II Linguistics Theory: Extensions and Implications</dfn> <span class="loc">(P121)</span></li>

<li>Ohio State University – <dfn>Language Files 11</dfn> <span class="loc">(P121)</span></li>

<li>Chomsky, Noam – <dfn>The Logical Structure of Linguistic Theory</dfn> <span class="loc">(P158)</span></li>

<li>Falk, Yehuda N. – <dfn>Lexical-Functional Grammar, An Introduction to Parallel Constraint-Based Syntax</dfn> <span class="loc">(P158.25)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Chomsky's Minimalism</dfn> <span class="loc">(P158.28)</span></li>

<li>Gutiérrez, Bravo and Arellanes Arellanes, Francisco and Peón Herrero, Mario Ernesto Chávez – <dfn>Nuevos estudios de Teoría de la Optimalidad</dfn> <span class="loc">(P158.42)</span></li>

<li>Richards, Norvin – <dfn>Contiguity Theory</dfn> <span class="loc">(P224.R43)</span></li>

<li>Bresnan, Joan and Asudeh, Ash and Tolivonen, Ida and Wechsler, Stephen – <dfn>Lexical-Functional Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Chomsky, Noam – <dfn>Aspects of the Theory of Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Freidin, Robert – <dfn>Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Saeed, John I. – <dfn>Semantics</dfn> <span class="loc">(P325)</span></li>

<li>Dalby, Andrew – <dfn>Dictionary of Languages, the Definitive Reference to More than 400 Languages</dfn> <span class="loc">(P371)</span></li>

<li>Allan, Keith – <dfn>The Western Classical Tradition in Linguistics</dfn> <span class="loc">(P61)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Western Linguistics: An Historical Introduction</dfn> <span class="loc">(P61)</span></li>

<li>Klein, Jared – <dfn>An Indo-European Chrestomathy</dfn></li>

<li>Watkins, Calvert – <dfn>The American Heritage Dictionary of Indo-European Roots</dfn> <span class="loc">(P615)</span></li>

<li>Sampson, Geoff – <dfn>Schools of Linguistics</dfn> <span class="loc">(P77)</span></li>

<li>Harris, Randy Allen – <dfn>The Linguistics Wars</dfn> <span class="loc">(P85.C47)</span></li>

<li>Cutting, Joan – <dfn>Pragmatics and Discourse</dfn> <span class="loc">(P99.4.P72)</span></li>

</ul>
<h2 id="pa-greek-and-latin-language-and-literature">PA: Greek and Latin language and Literature</h2>

<figure class="resright"><img src="/pix/hughes.jpg" title="These are actually pretty good and readable English translations."></figure>

<ul class="booklist">
<li>Morrison, Clinton and Barnes, David H. – <dfn>New Testament Word Lists</dfn> <span class="loc">(PA881)</span></li>

<li>Magoffin, Ralph van Deman and Henry, Margaret Young – <dfn>Latin First Year</dfn> <span class="loc">(PA2087)</span></li>

<li>Wheelock, Frederic M. – <dfn>Latin, an Introductory Course Based on Ancient Authors</dfn> <span class="loc">(PA2087.5)</span></li>

<li>Orberg, Hans H – <dfn>Roma Aeterna</dfn> <span class="loc">(PA2094.5)</span></li>

<li>Orberg, Hans H – <dfn>Colloquium Personarum</dfn> <span class="loc">(PA2095)</span></li>

<li>Orberg, Hans H – <dfn>Lingua Latina</dfn> <span class="loc">(PA2095)</span></li>

<li>Simpson, D. P. – <dfn>Cassell's Latin Dictionary</dfn> <span class="loc">(PA2365.E5)</span></li>

<li>Landis, Paul – <dfn>Four Famous Greek Plays</dfn> <span class="loc">(PA3626.A2)</span></li>

<li>Aeschylus – <dfn>The Oresteia</dfn> <span class="loc">(PA3827.A7)</span></li>

<li>Apollonius of Rhodes – <dfn>Jason and the Argonauts (Argonautica)</dfn> <span class="loc">(PA3872)</span></li>

<li>Euripides – <dfn>Three Plays of Euripides: Alcestis, Medea, the Bacchae</dfn> <span class="loc">(PA3975)</span></li>

<li>Euripides – <dfn>Alcestis and Other Plays</dfn> <span class="loc">(PA3975.A5)</span></li>

<li>Corpus Hermeticum – <dfn>Hermes Trismegistus</dfn> <span class="loc">(PA3998)</span></li>

<li>Homer – <dfn>The Iliad</dfn> <span class="loc">(PA4025.A2)</span></li>

<li>Homer – <dfn>The Odyssey</dfn> <span class="loc">(PA4025.A5)</span></li>

<li>Sophocles – <dfn>The Theban Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>The Complete Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>Electra and Other Plays</dfn> <span class="loc">(PA4414.A2)</span></li>

<li>Feyerabend, Karl – <dfn>Greek-English Dictionary</dfn> <span class="loc">(PA445.E5)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Liddell, H. G. and Scott – <dfn>Greek-English Lexicon</dfn> <span class="loc">(PA445.E5)</span></li>

<li>Juvenal – <dfn>The Sixteen Satires</dfn> <span class="loc">(PA6447.E5)</span></li>

<li>Lucretius – <dfn>On the Nature of Things</dfn> <span class="loc">(PA6483.E5)</span></li>

<li>Hughes, Ted – <dfn>Tales from Ovid: Twenty-Four Passages from the 'Metamorphoses' by Ovid</dfn> <span class="loc">(PA6522)</span></li>

<li>Petronius – <dfn>the Satyricon and the Fragments</dfn> <span class="loc">(PA6558.E5)</span></li>

<li>Pliny the Younger – <dfn>Pliny: A Self-Portrait in Letters</dfn> <span class="loc">(PA6639.E5)</span></li>

<li>Virgil – <dfn>Aeneid</dfn> <span class="loc">(PA6807.A5)</span></li>

<li>Virgil – <dfn>The Pastoral Poems</dfn> <span class="loc">(PA6807.B7)</span></li>

</ul>
<h2 id="pc-romance-languages">PC: Romance Languages</h2>

<figure class="resright"><img src="/pix/lathrop.jpg" title="Lathrop's Course on Historical Spanish"></figure>

<ul class="booklist">
<li>Decker, Henry W. and Bernhard, Francoise – <dfn>Modern French</dfn> <span class="loc">(PC211)</span></li>

<li>Azevedo, Milton M. – <dfn>Introducción a la Lingüística Española</dfn> <span class="loc">(PC4073)</span></li>

<li>Lathrop, T. A. and Gutiérrex Cuadrado, Juan – <dfn>Curso de gramática histórica española</dfn> <span class="loc">(PC4101)</span></li>

<li>Moreno, Oscar – <dfn>Gramática avanzada del español</dfn> <span class="loc">(PC4129.E5)</span></li>

<li>Cash, Annette G. and Murray, James C. – <dfn>Teoría y técnicas de traduccón: primeras etapas</dfn> <span class="loc">(PC4498)</span></li>

<li>Gili Gaya, Samuel – <dfn>Vox: Diccionario abreviado de la lengua española</dfn> <span class="loc">(PC4625)</span></li>

</ul>
<h2 id="pd-pf-germanic-languages-and-literatures">PD-PF: Germanic Languages and Literatures</h2>
<ul class="booklist">
<li>Lambdin, Thomas O. – <dfn>An Introduction to the Gothic Language</dfn> <span class="loc">(PD1123)</span></li>

<li>Hugo – <dfn>Swedish Phrase Book</dfn> <span class="loc">(PD5121)</span></li>

<li>Warriner, John E. and Whitten, Mary E. and Friggith, Francis J. – <dfn>Warriner's English Grammar and Composition</dfn> <span class="loc">(PE1112)</span></li>

<li>Elson, William H. and Keck, Christine – <dfn>Elson Grammar School Literature Book Two</dfn> <span class="loc">(PE1121)</span></li>

<li>Mitchell, Brucew and Robinson, Fred C. – <dfn>A Guide to Old English</dfn> <span class="loc">(PE131)</span></li>

<li>Evans, Jonathan – <dfn>An Introduction to Old English</dfn> <span class="loc">(PE135)</span></li>

<li>Bright, James W. – <dfn>Bright's Anglo-Saxon Reader</dfn> <span class="loc">(PE137)</span></li>

<li>Gottschalk, Katherine and Keith Hjortshoj – <dfn>The Elements of Teaching Writing</dfn> <span class="loc">(PE1404)</span></li>

<li>Forsyth, Mark – <dfn>The Elements of Eloquence</dfn> <span class="loc">(PE1421)</span></li>

<li>McCloskey, Deirdre N. – <dfn>Economical Writing</dfn> <span class="loc">(PE1479.E35)</span></li>

<li>Sharp, Stanley Louis and Strothmann, Friedrich Wilhelm – <dfn>German Reading Grammar</dfn> <span class="loc">(PF3111)</span></li>

<li>Morgan, Baynard Quincy and Strothmann, Friedrich Wilhelm – <dfn>Reading German</dfn> <span class="loc">(PF3117)</span></li>

<li>Berlitz – <dfn>Berlitz Self-Teaching German</dfn> <span class="loc">(PF3121)</span></li>

</ul>
<h2 id="pj-pl-oriental-indo-iranian-east-asian-and-oceanian-languages">PJ-PL: Oriental, Indo-Iranian, East-Asian and Oceanian Languages</h2>

<figure class="resright"><img src="/pix/sastry.jpg" title="Sanskrit in the Development of World Thought"></figure>

<ul class="booklist">
<li>Anonymous – <dfn>The Epic of Gilgamesh</dfn> <span class="loc">(PJ3771.G5)</span></li>

<li>Wightwick, Jane and Gaafar, Mahmoud – <dfn>Mastering Arabic</dfn> <span class="loc">(PJ6307)</span></li>

<li>Luxenberg, Christoph – <dfn>The Syro-Aramaic Reading of the Koran: A Contribution to Decoding the Language of the Koran</dfn> <span class="loc">(PJ6696)</span></li>

<li>Burnell, Arthur Coke – <dfn>On the Aindra school of Sanskrit grammarians, their place in the Sanskrit and subordinate literatures</dfn> <span class="loc">(PK407)</span></li>

<li>Sastry, Vempaty Kutumba – <dfn>Sanskrit and Development of World Thought</dfn> <span class="loc">(PK423)</span></li>

<li>Elwell-Sutton, L. P. – <dfn>Elementary Persian Grammar</dfn> <span class="loc">(PK6235)</span></li>

<li>Whitney, William Dwight – <dfn>A Sanskrit Grammar: Including Both the Classical Language, and the Older Dialects, of the Veda and Brahmana</dfn> <span class="loc">(PK663)</span></li>

<li>Sutherland, Goldman – <dfn>Devavanipravesika</dfn> <span class="loc">(PK666)</span></li>

<li>Whitney, William Dwight – <dfn>The Roots, Verb-Forms, And Primary Derivatives of the Sankstrit Language: A Supplement to his Sanskrit Grammar</dfn> <span class="loc">(PK745)</span></li>

<li>DeFrancis, John – <dfn>Intermediate Chinese</dfn> <span class="loc">(PL11117)</span></li>

<li>DeFrancis, John – <dfn>Advanced Chinese</dfn> <span class="loc">(PL1121.C5)</span></li>

<li>Defense Language Institute – <dfn>Chinese: Basic Course</dfn> <span class="loc">(PL1125)</span></li>

<li>Seligman, Scott D. – <dfn>Mandarin Chinese at a Glance</dfn> <span class="loc">(PL1125.E6)</span></li>

<li>DeFrancis, John – <dfn>The Chinese Language, Fact and Fantasy</dfn> <span class="loc">(PL1171)</span></li>

<li><dfn>Oxford Chinese Dictionary</dfn> <span class="loc">(PL1455)</span></li>

<li>Waley, Arthur – <dfn>Translations from the Chinese</dfn> <span class="loc">(PL3277.E3)</span></li>

<li>Burlington, Scott – <dfn>Instant Hawaiian</dfn> <span class="loc">(PL6445)</span></li>

<li>Pukui, Mary Kawena and Elbert, Samuel H. and Mookini, Esther T. – <dfn>The Pocket Hawaiian Dictionary</dfn> <span class="loc">(PL6446)</span></li>

</ul>
<h2 id="pn-general-literature">PN: General Literature</h2>
<ul class="booklist">
<li>Butterworth, Hezekiah – <dfn>The Story of America</dfn> <span class="loc">(PN1009.A1)</span></li>

<li>Kaplar, Richard T. and Patrick D. Maines – <dfn>The Government Factor: Undermining Journalistic Ethics in the Information Age</dfn> <span class="loc">(PN4888.E8)</span></li>

<li>Schwarz, Leo W. – <dfn>Feast of Leviathan: Tales of Adventure, Faith and Love from Jewish Literature</dfn> <span class="loc">(PN6071.J5)</span></li>

<li><dfn>Treasury of Familiar Quotations</dfn> <span class="loc">(PN6081)</span></li>

<li><dfn>Reader's Digest Treasury of American Humor</dfn> <span class="loc">(PN6162)</span></li>

<li>The Onion – <dfn>Dispatches from the Tenth Circle</dfn> <span class="loc">(PN6165)</span></li>

<li>The Onion – <dfn>Our Dumb World</dfn> <span class="loc">(PN6231.A74)</span></li>

<li>Raymond, Eric S. – <dfn>The New Hacker's Dictionary</dfn> <span class="loc">(PN6231.E4)</span></li>

<li>The Onion – <dfn>Our Dumb Century</dfn> <span class="loc">(PN6231.N6)</span></li>

<li>Gómez Dávila, Nicolás – <dfn>Escolios a un texto implícito</dfn> <span class="loc">(PN6275)</span></li>

<li>Brown, Jeffrey – <dfn>Darth Vader and Son</dfn> <span class="loc">(PN6727.B7575)</span></li>

<li>Watterson, Bill – <dfn>Calvin and Hobbes: Scientific Progress Goes 'Boink'</dfn> <span class="loc">(PN6728.C34)</span></li>

<li>Lewis, C. S. – <dfn>The Discarded Image: An Introduction to Medieval and Renaissance Literature</dfn> <span class="loc">(PN671)</span></li>

</ul>
<h2 id="pq-romance-literature">PQ: Romance Literature</h2>

<figure class="resright"><img src="/pix/inferno.jpg"></figure>

<ul class="booklist">
<li>de Montaigne, Michel – <dfn>Montaigne Selected Essays</dfn> <span class="loc">(PQ1642.E6)</span></li>

<li>Morlière, Jean-Baptiste – <dfn>Tartuffe and Other Plays</dfn> <span class="loc">(PQ1842)</span></li>

<li>De Saint-Exupéry – <dfn>Sazadeo Qickek</dfn> <span class="loc">(PQ2637.A274)</span></li>

<li>Alighieri, Dante – <dfn>The Divine Comedy</dfn> <span class="loc">(PQ4315)</span></li>

<li>Alighieri, Dante – <dfn>The Inferno</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Alighieri, Dante – <dfn>I: Hell (Sayers translation)</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Eco, Umberto – <dfn>Foucault's Pendulum</dfn> <span class="loc">(PQ4864.C6)</span></li>

<li>De la Vega, Garcilaso – <dfn>Poesías</dfn> <span class="loc">(PQ6391)</span></li>

<li>Garcia Lorca, Federico – <dfn>Rosita la soltera</dfn> <span class="loc">(PQ6613.A763)</span></li>

<li>Pérez-Reverte, Arturo – <dfn>La tabla de Flandés</dfn> <span class="loc">(PQ6666.E765)</span></li>

<li>Rulfo, Juan &amp;ndash; Pedro – <dfn>y El Llano en llamas</dfn> <span class="loc">(PQ7297.R89)</span></li>

</ul>
<h2 id="pr-english-literature">PR: English Literature</h2>
<ul class="booklist">
<li>Clark, Thomas Curtis and Gillespie, Esther A. – <dfn>1000 Quotable Poems</dfn> <span class="loc">(PR1175)</span></li>

<li><dfn>Beowulf</dfn> <span class="loc">(PR1583)</span></li>

<li>Chaucer, Geoffrey – <dfn>Chaucer's Major Poetry</dfn> <span class="loc">(PR1851)</span></li>

<li>Chaucer, Geoffrey – <dfn>The Canterbury Tales</dfn> <span class="loc">(PR1870.A1)</span></li>

<li>Collis, Louise – <dfn>Memoirs of a Medieval Woman</dfn> <span class="loc">(PR2007)</span></li>

<li>Malory, Thomas – <dfn>Le Morte d'Arthur</dfn> <span class="loc">(PR2041)</span></li>

<li>Craig, W. J. – <dfn>The Complete Works of William Shakespeare</dfn> <span class="loc">(PR2753.C8)</span></li>

<li>Shakespeare, William – <dfn>Hamlet (2 copies)</dfn> <span class="loc">(PR2801.A2)</span></li>

<li>Shakespeare, William – <dfn>Macbeth</dfn> <span class="loc">(PR2823.A2)</span></li>

<li>Shakespeare, William – <dfn>A Midsummer Night's Dream</dfn> <span class="loc">(PR2827.A2)</span></li>

<li>Shakespeare, William – <dfn>The Merchant of Venice</dfn> <span class="loc">(PR2825.A2)</span></li>

<li>Shakespeare, William – <dfn>The Sonnets</dfn> <span class="loc">(PR2848.A2)</span></li>

<li>Crystal, David – <dfn>The Oxford Dictionary of Original Shakespearean Pronunciation</dfn> <span class="loc">(PR2892)</span></li>

<li>Bunyan, John – <dfn>Pilgrim's Progress</dfn> <span class="loc">(PR3330)</span></li>

<li>Milton, John – <dfn>Paradise Lost and Other Poems</dfn> <span class="loc">(PR3560)</span></li>

<li>Coleridge, Samuel Taylor – <dfn>The Rime of the Ancient Mariner</dfn> <span class="loc">(PR4479)</span></li>

<li>Dickens, Charles – <dfn>Great Expectations</dfn> <span class="loc">(PR4560)</span></li>

<li>Shaw, George Bernard – <dfn>Pygmalion</dfn> <span class="loc">(PR5363)</span></li>

<li>Stevenson, Robert Louis – <dfn>The Black Arrow</dfn> <span class="loc">(PR5484)</span></li>

<li>Stevenson, Robert Louis – <dfn>New Arabian Nights</dfn> <span class="loc">(PR5484)</span></li>

<li>Wells, H. G. – <dfn>The Island of Dr. Moreau</dfn> <span class="loc">(PR5774)</span></li>

<li>Wilde, Oscar – <dfn>The Importance of Being Earnest</dfn> <span class="loc">(PR5818)</span></li>

<li>Christie, Agatha – <dfn>Death on the Nile</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Christie, Agatha – <dfn>The Nursery Rhyme Murders</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Golding, William – <dfn>Lord of the Flies</dfn> <span class="loc">(PR6013.O35)</span></li>

<li>Lewis, C. S. – <dfn>The Lion, the Witch and the Wardrobe</dfn> <span class="loc">(PR6023.E926)</span></li>

<li>Huxley, Aldous – <dfn>Brave New World</dfn> <span class="loc">(PR6015.U9)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Lord of the Rings, One-Volume Edition</dfn> <span class="loc">(PR6039.O32)</span></li>

<li>White, T. H. – <dfn>The Once and Future King</dfn> <span class="loc">(PR6045.H2)</span></li>

<li>Adams, Douglas – <dfn>Life, the Universe and Everything</dfn> <span class="loc">(PR6051.D3352)</span></li>

<li>Erickson, Paul – <dfn>Doctor Who: The Ark</dfn> <span class="loc">(PR6052.R449)</span></li>

<li>Burgess, Anthony – <dfn>A Clockwork Orange</dfn> <span class="loc">(PR6052.U638)</span></li>

<li>Grimwade, Peter – <dfn>Doctor Who: Planet of Fire</dfn> <span class="loc">(PR6057.R545)</span></li>

<li>Halleck, Reuben Post – <dfn>History of English Literature</dfn> <span class="loc">(PR85)</span></li>

<li>Achebe, Chinua – <dfn>Things Fall Apart</dfn> <span class="loc">(PR9387.9.A3)</span></li>

</ul>
<h2 id="ps-american-literature">PS: American Literature</h2>

<figure class="resright"><img src="/pix/lovecraft.jpg"></figure>

<ul class="booklist">
<li>Twain, Mark – <dfn>A Connecticut Yankee in King Arthur's Court</dfn> <span class="loc">(PS1308)</span></li>

<li>Hawthorne, Nathaniel – <dfn>The Scarlet Letter</dfn> <span class="loc">(PS1868)</span></li>

<li>Poe, Edgar Allan – <dfn>Edgar Allan Poe Reader</dfn> <span class="loc">(PS2603)</span></li>

<li>Poe, Edgar Allen – <dfn>Tales of Terror and Detection</dfn> <span class="loc">(PS2612)</span></li>

<li>Thoreau, Henry David – <dfn>Walden</dfn> <span class="loc">(PS3048)</span></li>

<li>Wallace, Lew – <dfn>Ben Hur</dfn> <span class="loc">(PS3134)</span></li>

<li>Faulkner, William – <dfn>Light in August</dfn> <span class="loc">(PS3511.A86)</span></li>

<li>Fitzgerald, F. Scott – <dfn>The Great Gatsby</dfn> <span class="loc">(PS3511.I9)</span></li>

<li>Heinlein, Robert A. – <dfn>For Us, the Living</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Heinlein, Robert A. – <dfn>The Moon is a Harsh Mistress</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Lovecraft, H. P. – <dfn>Great Tales of Horror</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Case of Charles Dexter Ward</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Doom That Came to Sarnath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Dream Quest of Unknown Kadath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Tomb</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Rodgers, Marion Elizabeth – <dfn>Mencken &amp; Sara</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Mencken, H. L. – <dfn>The Vintage Mencken</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Rand, Ayn – <dfn>Atlas Shugged</dfn> <span class="loc">(PS3535.A547)</span></li>

<li>Skinner, B. F. – <dfn>Walden Two</dfn> <span class="loc">(PS3537.K527)</span></li>

<li>Smith, Clark Ashton – <dfn>Hyperborea</dfn> <span class="loc">(PS3537.M335)</span></li>

<li>Bear, Greg – <dfn>Darwin's Radio</dfn> <span class="loc">(PS3552.E157)</span></li>

<li>Card, Orson Scott – <dfn>Ender's Game</dfn> <span class="loc">(PS3553.A655)</span></li>

<li>Crichton, Michael – <dfn>Congo</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Jurassic Park</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Timeline</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Dick, Philip K. – <dfn>Dr. Bloodmoney</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Dick, Philip K. – <dfn>Flow My Tears, The Policeman Said</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Herbert, Frank – <dfn>Dune</dfn> <span class="loc">(PS3558.E63)</span></li>

<li>Jordan, Robert – <dfn>The Eye of the World</dfn> <span class="loc">(PS3560.O7617)</span></li>

<li>King, Stephen – <dfn>The Bazaar of Bad Dreams</dfn> <span class="loc">(PS3561.I483)</span></li>

<li>Myers, Bill – <dfn>Blood of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Fire of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Threshold</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Quinn, Daniel – <dfn>Ishmael: An Adventure of the Mind and Spirit</dfn> <span class="loc">(PS3567.U338)</span></li>

<li>Pearl, Matthew – <dfn>The Dante Club</dfn> <span class="loc">(PS3616.E25)</span></li>

<li>Asimov, Isaac – <dfn>Before the Golden Age: A Science Fiction Anthology of the 1930's</dfn> <span class="loc">(PS648.S3)</span></li>

<li>Saramago, José – <dfn>Todos los nombres</dfn> <span class="loc">(PS9281.A66)</span></li>

</ul>
<h2 id="pq-pz-other-literature">PQ-PZ: Other Literature</h2>

<figure class="resright"><img src="/pix/edda.jpg"></figure>

<ul class="booklist">
<li>Voltaire – <dfn>Candide, Zadig and selected stories</dfn> <span class="loc">(PQ2081.E5)</span></li>

<li>Hesse, Hermann – <dfn>Siddhartha</dfn> <span class="loc">(PT2617.E85)</span></li>

<li>Hesse, Hermann – <dfn>The Glass Bead Game</dfn> <span class="loc">(PT2617.E85 G513)</span></li>

<li>Sturluson, Snorri – <dfn>Poetic Edda</dfn> <span class="loc">(PT7235)</span></li>

<li>Sturluson, Snorri – <dfn>Prose Edda</dfn> <span class="loc">(PT7313.E5)</span></li>

<li>Borges, Jorge Luis – <dfn>Ficciones</dfn> <span class="loc">(PW7797.B635)</span></li>

<li>Connor, Ralph – <dfn>Black Rock: a Tale of the Selkirks</dfn> <span class="loc">(PZ3.G654)</span></li>

<li>Roberts, James Hall – <dfn>The Q Document</dfn> <span class="loc">(PZ4.D913)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Hobbit</dfn> <span class="loc">(PZ7.T5744)</span></li>

<li>Wilder, Laura Ingalls – <dfn>Little House (entire series)</dfn> <span class="loc">(PZ7.W6461)</span></li>

<li>Jacobs, Joseph – <dfn>Favorite Celtic Fairy Tales</dfn> <span class="loc">(PZ8)</span></li>

<li>Baum, L. Frank – <dfn>The Wizard of Oz</dfn> <span class="loc">(PZ8.B327)</span></li>

<li><dfn>The Brothers Grimm Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

<li><dfn>The Complete Grimm's Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

</ul>
<h2 id="qa-general-science">QA: General Science</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hVxvLd6cF0k"><img src="/pix/againstmethod.jpg"></a></figure>

<ul class="booklist">
<li>de Santillanna, Giorgio – <dfn>The Origins of Scientific Thought: from Anazimander to Proclus, 600 B.C. to 300 A.D.</dfn> <span class="loc">(Q125)</span></li>

<li>Gardner, Martin – <dfn>Great Essays in Science</dfn> <span class="loc">(Q171)</span></li>

<li>Kuhn, Thomas – <dfn>The Structure of Scientific Revolutions</dfn> <span class="loc">(Q175)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Wiener, Norbert – <dfn>The Human Use of Human Beings</dfn> <span class="loc">(Q175)</span></li>

<li>Feyerabend, Paul – <dfn>Against Method </dfn> <span class="loc">(Q175)</span></li>

<li>Motterlini, Matteo – <dfn>For and Against Method: Including Lakatos's Lectures on Scientific Method and the Lakatos-Feyerabend Correspondence </dfn> <span class="loc">(Q175.3)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Antifragile</dfn> <span class="loc">(Q375)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>The Black Swan</dfn> <span class="loc">(Q375)</span></li>

</ul>
<h2 id="qa-mathematics">QA: Mathematics</h2>
<ul class="booklist">
<li>Sawyer, W. W. – <dfn>Mathematician's Delight</dfn> <span class="loc">(QA37)</span></li>

<li>Birns, Peter and Brown, Patrick and Muster, John C. C. – <dfn>Unix for People</dfn> <span class="loc">(QA76.6)</span></li>

<li>Raymond, Eric S. – <dfn>The Cathedral and the Bazaar</dfn> <span class="loc">(QA76.76.O63)</span></li>

<li>Bellos, Alex – <dfn>Here's Looking at Euclid</dfn> <span class="loc">(QA141.15)</span></li>

<li>Nyberg, Joseph A. – <dfn>Second Course in Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Wentworth, G. A. – <dfn>New School Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Hart, William – <dfn>College Algebra</dfn> <span class="loc">(QA154)</span></li>

<li>Lial, Margaret L. and Miller, Charles D. – <dfn>Algebra and Trigonometry</dfn> <span class="loc">(QA154.2)</span></li>

<li>Sokal, Alan and Bricmont, Jean – <dfn>Fashionable Nonsense: Postmodern Intellectuals' Abuse of Science</dfn> <span class="loc">(QA175)</span></li>

<li>Neugebauer, Otto – <dfn>The Exact Sciences in Antiquity</dfn> <span class="loc">(QA22)</span></li>

<li>Bharati Krsna Thirthaji Maharaja – <dfn>Vedic Mathematics</dfn> <span class="loc">(QA27.I4)</span></li>

<li>Christian, Robert R. – <dfn>Introduction to Logic and Sets</dfn> <span class="loc">(QA248)</span></li>

<li>Davis, Morton D. – <dfn>Game Theory: A Nontechnical Introduction</dfn> <span class="loc">(QA269)</span></li>

<li>Friedman, Avner – <dfn>Differential Games</dfn> <span class="loc">(QA272)</span></li>

<li>Takahashi, Shin – <dfn>The Manga Guide to Statistics</dfn> <span class="loc">(QA276)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 1-10</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 10-15 and Appendices</dfn> <span class="loc">(QA303)</span></li>

<li>Smith, Edward S. and Salkover, Meyer and Justive, Howard K. – <dfn>Unified Calculus</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny – <dfn>Calculus with Analytic Geometry</dfn> <span class="loc">(QA33)</span></li>

<li>Sperling, Abraham and Stuart, Monroe – <dfn>Mathematics (Made Simple Self-Teaching Library)</dfn> <span class="loc">(QA39.2)</span></li>

<li>Horblit, Marcus and Nielson, Kaj L. – <dfn>Problems in Plane Geometry with Solutions</dfn> <span class="loc">(QA459)</span></li>

<li>Shively, Levi S. – <dfn>Modern Geometry</dfn> <span class="loc">(QA473)</span></li>

<li>Nelson, Alfred L. and Folley, Karl W. – <dfn>Plane and Spherical Trigonometry</dfn> <span class="loc">(QA531.N45)</span></li>

<li>Love, Clyde E. – <dfn>Analytic Geometry</dfn> <span class="loc">(QA551)</span></li>

<li>Hutton, Graham – <dfn>Programming in Haskell</dfn> <span class="loc">(QA76.62)</span></li>

<li>Kernighan, Brian W. and Ritchie, Dennis M. – <dfn>The C Programming Language</dfn> <span class="loc">(QA76.73.C15)</span></li>

<li>Barski, Conrad – <dfn>Land of Lisp</dfn> <span class="loc">(QA76.76.C672)</span></li>

<li>Hofstadter, Douglas – <dfn>Gödel, Escher, Bach</dfn> <span class="loc">(QA9.8)</span></li>

<li>Emmet, E. R. – <dfn>Brain Puzzler's Delight</dfn> <span class="loc">(QA95)</span></li>

<li>Emmet, E. R. – <dfn>Puzzles for Pleasure</dfn> <span class="loc">(QA95)</span></li>

<li>Gardner, Martin – <dfn>aha! Gotcha, Paradoxes to puzzle and delight</dfn> <span class="loc">(QA95)</span></li>

<li>Heafford, Philip – <dfn>The Math Entertainer</dfn> <span class="loc">(QA95)</span></li>

</ul>
<h2 id="qb-qr-other-sciences">QB-QR: Other Sciences</h2>
<ul class="booklist">
<li>Hawking, Stephen W. – <dfn>A Brief History of Time</dfn> <span class="loc">(QB981)</span></li>

<li>Lerner, Eric – <dfn>The Big Bang Never Happened</dfn> <span class="loc">(QB991.B54)</span></li>

<li>McEvoy, J. P. and Zarate, Oscar – <dfn>Quantum Theory, A Graphic Guide</dfn> <span class="loc">(QC173.98)</span></li>

<li>Booker, Christopher – <dfn>The Real Global Warming Disaster</dfn> <span class="loc">(QC981.8.G56)</span></li>

<li>Greenburg, Arthur – <dfn>From Alchemy to Chemistry in Picture and Story</dfn> <span class="loc">(QD11)</span></li>

<li>Valentine, Basil – <dfn>Of Natural and Supernatural Things: Also, of the First Tincture, Root, and Spirit of Metals and Minerals: How the Same are Conceived, Generated, Brought Forth, Changed and Augmented</dfn> <span class="loc">(QD25)</span></li>

<li>Watson, James – <dfn>The Double Helix</dfn> <span class="loc">(QH31.D434)</span></li>

<li>Fodor, Jerry and Piattelli Palmarini, Massimo – <dfn>What Darwin Got Wrong</dfn> <span class="loc">(QH375)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Kadans, Joseph M. – <dfn>Modern Encyclopedia of Herbs</dfn> <span class="loc">(QK99.A1)</span></li>

<li>McFarland, J. Horace – <dfn>Getting Acquainted with Trees</dfn> <span class="loc">(QK482)</span></li>

<li>Kurzweil, Ray – <dfn>The Singularity is Near</dfn> <span class="loc">(QP376)</span></li>

<li>Kandel, Eric R. and Schwartz, James H. and Jessell, Thomas M. – <dfn>Essentials of Neural Science and Behavior</dfn> <span class="loc">(QP355.2)</span></li>

</ul>
<h2 id="r-medicine">R: Medicine</h2>
<ul class="booklist">
<li>FC&amp;A – <dfn>The Folk Remedy Encyclopedia: Olive Oil, Vinegar, Honey and 1,001 Other Home Remedies</dfn> <span class="loc">(R733)</span></li>

<li><dfn>Better Homes and Gardens Family Medical Guide</dfn> <span class="loc">(RC81.A2)</span></li>

<li><dfn>The Encyclopedia of Common Diseases</dfn> <span class="loc">(RC81.A2)</span></li>

</ul>
<h2 id="s-t-agriculture-and-technology">S-T: Agriculture and Technology</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=YRNKjQg6y-c"><img src="/pix/salatin.jpg"></a></figure>

<ul class="booklist">
<li>Mollison, Bill – <dfn>Introduction to Permaculture</dfn> <span class="loc">(S494.5.P47)</span></li>

<li>Salatin, Joel – <dfn>Everything I Want to Do Is Illegal</dfn> <span class="loc">(S605.5)</span></li>

<li>David the Good – <dfn>Totally Crazy Easy Florida Gardening</dfn></li>

<li>Seymour, John – <dfn>The Complete Book of Self-Sufficiency</dfn> <span class="loc">(S605.5)</span></li>

<li>Cobleigh, Rolfe – <dfn>Handy Farm Devices and How to Make Them (2 copies)</dfn> <span class="loc">(S676)</span></li>

<li>Seymour, John – <dfn>Gardener's Delight</dfn> <span class="loc">(SB322)</span></li>

<li>Seymour, John – <dfn>The Self-Sufficient Gardener</dfn> <span class="loc">(SB324.3)</span></li>

<li>Haring, Elda – <dfn>The Seedling Handbook</dfn> <span class="loc">(SB405)</span></li>

<li>Abraham, George – <dfn>The Green Thumb Garden Handbook</dfn> <span class="loc">(SB453)</span></li>

<li><dfn>Reader's Digest Illustrated Guide to Gardening</dfn> <span class="loc">(SB453)</span></li>

<li>Kaczynski, Theodore John – <dfn>Technological Slavery</dfn> <span class="loc">(T14.5)</span></li>

<li>Kaczynski, Theodore John – <dfn>Anti-Tech Revolution: Why and How</dfn> <span class="loc">(T14.5)</span></li>

<li>Macaulay, David and Ardleym Neil – <dfn>The Way Things Work</dfn> <span class="loc">(T47)</span></li>

<li>Slater, Robert and Li, Ling and Li, Wen – <dfn>Portraits in Silicon</dfn> <span class="loc">(TK7885.2)</span></li>

<li>Bishop, Michael and Zimmerman, Holmes – <dfn>Detailing Cars and Trucks</dfn> <span class="loc">(TL152)</span></li>

<li>Allaby, Michael and Lovelock, James – <dfn>The Greening of Mars</dfn> <span class="loc">(TL795.7)</span></li>

<li>Abbey, Barbara – <dfn>The Complete Book of Knitting</dfn> <span class="loc">(TT820)</span></li>

<li>Bishop, Jack – <dfn>Vegetables Every Day</dfn> <span class="loc">(TX801)</span></li>

<li>Lo, Kenneth – <dfn>Chinese Regional Cooking</dfn> <span class="loc">(TX724.5.C5)</span></li>

</ul>
<h2 id="books-as-of-yet-unsorted">Books as of yet unsorted</h2>
<ul class="booklist">
<li>Seb Falk – <dfn>The Light Ages: The Surprising Story of Medieval Science</dfn></li>

<li><dfn>The Penny Catechism: A Catechism of Christian Doctrine</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese Reader, Part 1</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese</dfn></li>

<li>Flame Tree Publishing – <dfn>Gothic Fantasy: Lost Worlds Short Stories</dfn></li>

<li>Lee, Christopher – <dfn>This Sceptered Isle 55 BC to 1901</dfn></li>

<li>Malice, Michael – <dfn>Dear Reader</dfn></li>

<li>McCloskey, Deirdre N. – <dfn>Economic Writing</dfn></li>

<li>Meyer, Jerome S. – <dfn>The Provocative Puzzler</dfn></li>

<li>Parikh, Prashant – <dfn>Language and Equilibrium</dfn></li>

<li>Reed, Lawrence W. – <dfn>Great Myths of the Great Depression</dfn></li>

<li><dfn>Using HTML4, Java 1.1, and Javascript 1.2</dfn></li>

<li>Valizadeh, Roosh – <dfn>Game</dfn></li>

<li>Vikernes, Varg – <dfn>MYFAROG 2.6</dfn></li>

</ul>
<div style="clear:both" class="taglist">Read related articles:<br><a id="tag_personal" href="https://lukesmith.xyz/tags/personal">Personal</a> · <a id="tag_science" href="https://lukesmith.xyz/tags/science">Science</a> · <a id="tag_tradition" href="https://lukesmith.xyz/tags/tradition">Tradition</a> · <a id="tag_lifestyle" href="https://lukesmith.xyz/tags/lifestyle">Lifestyle</a> · <a id="tag_philosophy" href="https://lukesmith.xyz/tags/philosophy">Philosophy</a></div>
<br clear="both">
</article>
</main>
<a href="/"><header>
	<h1 id="tag_My Personal Library">My Personal Library</h1>
</header></a>
<header>
	<h1 id="tag_My Personal Library">My Personal Library</h1>
</header>
<h1 id="tag_My Personal Library">My Personal Library</h1>
<header>
	<h1 id="tag_My Personal Library">My Personal Library</h1>
</header>
<a href="/"><header>
	<h1 id="tag_My Personal Library">My Personal Library</h1>
</header></a>
<article>
<p>This is a list of the books in my personal library. If you have any
questions or want me to review any of them, email me
(<a href="mailto:luke@lukesmith.xyz">luke@lukesmith.xyz</a>).</p>
<p>I haven't read every book here, nor do I own all the books I've read
or like. I also don't necessarily like all the books I own.</p>
<p>Check out <a href="https://notrelated.xyz">my podcast, <em>Not Related!</em></a>
for some book reviews and other things. Books I've talked about in one
way or another in the podcast will have a link to that episode.</p>
<h2 id="-lindypressnet-books">🆕 LindyPress.net Books</h2>
<p>Note that now I am reprinting out-of-print works at
<a href="https://lindypress.net">LindyPress.net</a>. You can buy any of these books
yourself if you'd like. (Most of them are pretty exclusive in that I'm
the only one reprinting them.)</p>
<ul>
<li>Pseudo-Aristotle – <a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a></li>
<li><a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a></li>
<li>Isidore of Seville – <a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a></li>
<li>Roger Bacon ‐ <a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a></li>
<li>Marcus Aurelius – <a href="https://lindypress.net/book?pk=2">Meditations</a></li>
<li><a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a></li>
</ul>
<p>(These are at the top since I don't know if anyone has given them Library of
Congress numbers, and I suppose as an ad.)</p>
<h2 id="a-bd-general-works-philosophy-logic-speculative-philosophy">A-BD: General Works, Philosophy, Logic, Speculative Philosophy</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hCVdCS0t46I"><img src="/pix/searle.jpg" title="Searle (actually literally) did nothing wrong."></a></figure>

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
<h2 id="bm-bx-specific-religions-and-theology">BM-BX: Specific Religions and Theology</h2>

<figure class="resright"><img src="/pix/biglot.jpg" title="A Greek and Latin biglottic Bible"></figure>

<ul class="booklist">
<li><dfn>'תְּהִלַּת ה</dfn> <span class="loc">(BM675/D3)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Key to Theosophy</dfn> <span class="loc">(BP561)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Voice of Silence</dfn> <span class="loc">(BP561)</span></li>

<li>Wright, Stuart – <dfn>Armageddon in Waco</dfn> <span class="loc">(BP605.B62)</span></li>

<li>Lewis, C. S. – <dfn>Mere Christianity</dfn> <span class="loc">(BR123)</span></li>

<li>Lewis, C. S. – <dfn>The Screwtape Letters</dfn> <span class="loc">(BR125)</span></li>

<li>Reardon, Patrick Henry – <dfn>Christ in the Psalms</dfn> <span class="loc">(BS1430.4)</span></li>

<li>Leithart, Peter J. – <dfn>Solomon Among the Postmoderns</dfn> <span class="loc">(BS1475.52)</span></li>

<li>Porter, J. R. – <dfn>The Lost Bible</dfn> <span class="loc">(BS1700)</span></li>

<li>Heiser, Michael – <dfn>Reversing Hermon: Enoch, the Watchers and the Forgotten Mission of Jesus Christ</dfn> <span class="loc">(BS1830.E7)</span></li>

<li><dfn>The New Oxford Annotated Bible</dfn> <span class="loc">(BS191.5.A1)</span></li>

<li><dfn>The New English Bible</dfn> <span class="loc">(BS192.A1)</span></li>

<li>Montano, Arias and Leudsen, Johann – <dfn>Greek-Latin Parallel New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>Pocket Interlinear New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>The New International Dictionary of New Testament Theology (3 Volumes)</dfn> <span class="loc">(BS2312)</span></li>

<li><dfn>Ἡ Καινὴ Διαθήκη</dfn> <span class="loc">(BS2312)</span></li>

<li>Kümmel, Werner Georg – <dfn>Introduction to the New Testament</dfn> <span class="loc">(BS2330)</span></li>

<li>Aland, Kurt – <dfn>Synopsis Quattuor Evangeliorum</dfn> <span class="loc">(BS2560.A2)</span></li>

<li>Mack. Burton L. – <dfn>A Myth of Innocence</dfn> <span class="loc">(BS2585.2)</span></li>

<li>Ehrman, Bart D. – <dfn>Lost Christianities: The Battles for Scriptures and the Faiths We Never Knew</dfn> <span class="loc">(BS2840.E4)</span></li>

<li>Luther, Martin – <dfn>Luther's Small Catechism with Additions Including the Augsburg Confession</dfn> <span class="loc">(BR331.K64)</span></li>

<li>Strong, James – <dfn>Strong's Exhaustive Concordance of the Bible with Hebrew and Greek Dictionaries</dfn> <span class="loc">(BS425)</span></li>

<li><dfn>Illustrated Dictionary and Concordance of the Bible</dfn> <span class="loc">(BS440)</span></li>

<li>McDowell, Josh – <dfn>The New Evidence that Demands a Verdict</dfn> <span class="loc">(BS480)</span></li>

<li>Laymon, Charles M. – <dfn>The Interpreter's One-Volume Commentary on the Bible</dfn> <span class="loc">(BS491.2)</span></li>

<li>Cross, John R. – <dfn>The Stranger on the Road to Emmaus</dfn> <span class="loc">(BS511.2)</span></li>

<li><dfn>Reader's Digest Mysteries of the Bible; the Enduring Questions of the Scriptures</dfn> <span class="loc">(BS538)</span></li>

<li>Smith, Brendan Powell – <dfn>The Brick Bible</dfn> <span class="loc">(BS550.3)</span></li>

<li>Kent, Paul and McLaughlan, David – <dfn>Know Your Bible: All 66 Books Explained and Applied</dfn> <span class="loc">(BS593)</span></li>

<li><dfn>Septuagint with Apocrypha</dfn> <span class="loc">(BS742)</span></li>

<li><dfn>Biblia Sacra Vulgata</dfn> <span class="loc">(BS75)</span></li>

<li>Newman, John Henry – <dfn>An Essay on the Development of Christian Doctrine</dfn> <span class="loc">(BT21)</span></li>

<li>Robinson, James M. – <dfn>The Nag Hammadi Library</dfn> <span class="loc">(BT1391)</span></li>

<li>Lewis, C. S. – <dfn>Surprised by Joy: The Shape of My Early Life</dfn> <span class="loc">(BV4935.L43)</span></li>

<li>Carman, Stephen L. and Owen, Bob – <dfn>Quest: The Story of an Aerospace Engineer who Challenged God to Prove Himself</dfn> <span class="loc">(BV4930)</span></li>

<li>Ware, Timothy – <dfn>The Orthodox Church</dfn> <span class="loc">(BX106)</span></li>

<li>Aveling, J. C. H. – <dfn>The Jesuits</dfn> <span class="loc">(BX3706.2)</span></li>

<li><dfn>The Book of Common Prayer</dfn> <span class="loc">(BX5145)</span></li>

<li><dfn>Five Great Encyclicals: Labor, Education, Marriage, Reconstructing the Social Order, Atheistic Communism</dfn> <span class="loc">(BX860)</span></li>

</ul>
<h2 id="c-auxiliary-sciences-of-history">C: Auxiliary Sciences of History</h2>
<ul class="booklist">
<li>Graeber, David and Wengrow, David – <dfn>The Dawn of Everything: A New History of Humanity</dfn> <span class="loc">(CB19)</span></li>

<li>McNeill, William H. – <dfn>The Rise of the West: A History of the Human Community</dfn> <span class="loc">(CB59)</span></li>

<li>Sitchin, Zecharia – <dfn>The 12th Planet</dfn> <span class="loc">(CB156)</span></li>

<li>Rohl, David – <dfn>The Lords of Avaris: Uncovering the Legendary Origins of Western Civilization</dfn> <span class="loc">(CB245)</span> <a href="https://notrelated.xyz/#02.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Casson, Lionel and Clairborne, Robert and Fagan, Brian and Karp, Walter – <dfn>Mysteries of the Past</dfn> <span class="loc">(CB311)</span></li>

<li>Fisher, Marshall John and Fisher, David E. – <dfn>Mysteries of Lost Empires</dfn> <span class="loc">(CB311)</span></li>

<li>Hawkes, Jacquetta – <dfn>The Atlas of Early Man</dfn> <span class="loc">(CB311)</span></li>

<li>Platt, Richard and Riddell, Chris – <dfn>Castle Diary</dfn> <span class="loc">(CB351)</span></li>

<li>Cahill, Thomas – <dfn>Mysteries of the Middle Ages</dfn> <span class="loc">(CB351)</span></li>

</ul>
<h2 id="d-world-history">D: World History</h2>

<figure class="resright"><img src="/pix/racehutton.jpg" title="Hutton's book on the Third Reich"></figure>

<ul class="booklist">
<li>Malesky, Kee – <dfn>All Facts Considered, the Essential Library of Inessential Knowledge</dfn> <span class="loc">(D10)</span></li>

<li>Evola, Julius – <dfn>Revolt Against the Modern World</dfn> <span class="loc">(D16.8)</span></li>

<li>Epstein, Steven A. – <dfn>An Economic and Social History of Later Medieval Europe, 1000-1500</dfn> <span class="loc">(D117)</span></li>

<li>Pirenne, Henri – <dfn>A History of Europe</dfn> <span class="loc">(D117)</span></li>

<li>Cantor, Nroman F. – <dfn>Medieval History: The Life and Death of a Civilization</dfn> <span class="loc">(D118)</span></li>

<li>Roberts, J. M. – <dfn>New History of the World</dfn> <span class="loc">(D20)</span></li>

<li>Mann, Charles C. – <dfn>1493, Uncovering the New World Columbus Created</dfn> <span class="loc">(D228)</span></li>

<li>Rogan, Eugene L. – <dfn>The FAll of the Ottomans: The Great War in the Middle East</dfn> <span class="loc">(D566)</span></li>

<li>Sanborn, Frederick R. – <dfn>Design for War: A Study of Secret Power Politics</dfn> <span class="loc">(D742.U5)</span></li>

<li>Cheyney, Edward P. – <dfn>A Short History of England</dfn> <span class="loc">(DA32)</span></li>

<li>Thomas, Charles – <dfn>Celtic Britain</dfn> <span class="loc">(DA140)</span></li>

<li>Sellar, W.C. &amp; Yeatman R.J. – <dfn>1066 and All That</dfn> <span class="loc">(DA33)</span></li>

<li>Freeman, John and Sharpe, Sue – <dfn>This Beautiful Land: Britain</dfn> <span class="loc">(DA632)</span></li>

<li>Hutton, Christopher – <dfn>Race and the Third Reich</dfn> <span class="loc">(DD253)</span></li>

<li>Tacitus, C. Cornellius – <dfn>Annales et Historiae</dfn> <span class="loc">(DG207.T3)</span></li>

<li>Shirer, William L. – <dfn>The Rise and Fall of the Third Reich</dfn> <span class="loc">(DD256.5)</span></li>

<li>MacDonald, Kevin – <dfn>The Culture of Critique: An Evolutionary Analysis of Jewish Involvement in Twentieth-Century Intellectual and Political Movements</dfn> <span class="loc">(DS143)</span></li>

<li>Ford, Henry Sr. – <dfn>The International Jew: The World's Foremost Problem</dfn> <span class="loc">(DS145)</span></li>

<li>Ali, Tariq – <dfn>The Duel: Pakistan on the Flight Path of American Power</dfn> <span class="loc">(DS384)</span></li>

<li>De Bary, William Theodore – <dfn>The Sources of Indian Tradition</dfn> <span class="loc">(DS423)</span></li>

<li>Keay, John – <dfn>India, A History</dfn> <span class="loc">(DS451)</span></li>

<li>Ebrey, Patricia Buckley – <dfn>Cambridge Illustrated History of China</dfn> <span class="loc">(DS706)</span></li>

<li>National Geographic Society – <dfn>Journey into China</dfn> <span class="loc">(DS712)</span></li>

</ul>
<h2 id="e-f-history-of-the-americas">E-F: History of the Americas</h2>

<figure class="resright"><img src="/pix/foxfire.jpg"></figure>

<ul class="booklist">
<li>Hancock, Graham – <dfn>America Before: The Key to Earth's Lost Civilization</dfn> <span class="loc">(E61)</span></li>

<li>Little, Gregory – <dfn>Path of Souls: The Native American Death Journey: Cygnus, Orion, the Milky Way, Giant Skeletons in Mounds, &amp; the Smithsonian</dfn> <span class="loc">(E98.M8)</span></li>

<li>Mooney, James – <dfn>Myths of the Cherokee</dfn> <span class="loc">(E99.C5)</span></li>

<li>Greenblatt, Stephen – <dfn>New World Encounters</dfn> <span class="loc">(E141)</span></li>

<li>Fischer, David Hackett – <dfn>Albion's Seed: Four British Folkways in America</dfn> <span class="loc">(E169.1)</span> <a href="https://notrelated.xyz/#01.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Sowell, Thomas – <dfn>Ethnic America</dfn> <span class="loc">(E184.A1)</span></li>

<li>Hurmence, Belinda – <dfn>Before Freedom: 48 Oral Histories of Former North and South Carolina Slaves</dfn> <span class="loc">(E444)</span></li>

<li>Adams, Nehemiah – <dfn>A South-side View of Slavery: or Three Months at the South in 1854</dfn> <span class="loc">(E449)</span></li>

<li>Parsons, Charles Grandison – <dfn>An Inside View of Slavery; or A Tour Among the Planters</dfn> <span class="loc">(E449)</span></li>

<li>Long, A. L. – <dfn>Memoirs of Robert E. Lee</dfn> <span class="loc">(E467.1.L4)</span></li>

<li>Henry, Robert Selph – <dfn>The Story of the Confederacy</dfn> <span class="loc">(E487)</span></li>

<li>Mann, Charles C. – <dfn>1491, New Revelations of the Americas Before Columbus</dfn> <span class="loc">(E61)</span></li>

<li>Wharton, H. M. – <dfn>War Songs and Poems of the Southern Confederacy, 1861-1865: a Collection of the Most Popular and Impressive Songs and Poems of War Times, Dear to Every Southern Heart</dfn> <span class="loc">(E647)</span></li>

<li><dfn>The Blue Book of the John Birch Society</dfn> <span class="loc">(E743.5)</span></li>

<li>Stormer, John A. – <dfn>The Death of a Nation</dfn> <span class="loc">(E743.5)</span></li>

<li>Ramo, Joshua Cooper – <dfn>The Age of the Unthinkable</dfn> <span class="loc">(E902)</span></li>

<li>de las Casas, Bartolomé – <dfn>Brevisima relación de la destrución de las Indias</dfn> <span class="loc">(F1411)</span></li>

<li><dfn>The Foxfire Book</dfn> <span class="loc">(F291.2)</span></li>

<li><dfn>The Foxfire Book 2</dfn> <span class="loc">(F291.2)</span></li>

</ul>
<h2 id="g-geography-anthropology-recreation">G: Geography, Anthropology, Recreation</h2>
<ul class="booklist">
<li>Winer, Richard – <dfn>Ghost Ships: True Stories of Nautical Nightmares, Hauntings, and Disasters</dfn> <span class="loc">(G525)</span></li>

<li><dfn>National Geographic Collegiate Atlas of the World</dfn> <span class="loc">(G1021)</span></li>

<li>Wells, Spencer – <dfn>Pandora's Seed: The Unforeseen Cost of Civilization</dfn> <span class="loc">(GF75)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cochran, Gregory and Harpending, Henry – <dfn>the 10,000 Explosion: How Civilization Accelerated Human Evolution</dfn> <span class="loc">(GN281.4)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cremo, Michael A. &amp; Thompson, Ricahrd L. – <dfn>Forbidden Archaeology: The Hidden History of the Human Race</dfn> <span class="loc">(GN741)</span></li>

<li>Hancock, Graham – <dfn>Magicians of the Gods: The Forgotten Wisdom of Earth's Lost Civilization</dfn> <span class="loc">(GN751)</span></li>

<li>Cayce, Hugh Lynn – <dfn>Edgar Cayce on Atlantis</dfn> <span class="loc">(GN751.C35)</span></li>

<li>Marshack, Alexander – <dfn>The Roots of Civilization: The Cognitive Beginnings of Man's First Art, Symbol and Notation</dfn> <span class="loc">(GN772)</span></li>

<li>Bord, Janet and Bord, Colin – <dfn>Prehistoric Britain from the Air</dfn> <span class="loc">(GN805)</span></li>

<li>Bruce, Annette J. – <dfn>More Tellable Cracker Tales</dfn> <span class="loc">(GR110.F5)</span></li>

</ul>
<h2 id="h-social-sciences">H: Social Sciences</h2>
<p>
</p><figure class="resright"><img src="/pix/democracy.jpg"></figure>


<figure class="resright"><img src="/pix/pike.jpg"></figure>
<p></p>
<ul class="booklist">
<li>Greenspan, Alan – <dfn>The Age of Turbulence</dfn> <span class="loc">(HB119.G74)</span></li>

<li>Hazlitt, Hentry – <dfn>Economics in One Lesson (two copies)</dfn> <span class="loc">(HB171)</span></li>

<li>Keynes, John Maynard – <dfn>The General Theory of Employment, Interest and Money</dfn> <span class="loc">(HB171)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Rothbard, Murray – <dfn>Man, Economy and State with Power and Market</dfn> <span class="loc">(HB171)</span></li>

<li>von Mises, Ludwig – <dfn>Economic Policy</dfn> <span class="loc">(HB171)</span></li>

<li>Boulding, Kenneth E. – <dfn>Economic Analysis</dfn> <span class="loc">(HB171.5)</span></li>

<li>Goodman, Kennard E. and Moore, William L. – <dfn>Economics in Everyday Life</dfn> <span class="loc">(HB171.5)</span></li>

<li>Pindyck, Robert S. and Rubinfeld, Daniel L. – <dfn>Microeconomics</dfn> <span class="loc">(HB172)</span></li>

<li>Fisher, David Hackett – <dfn>The Great Wave: Price Revolutions and the Rhythm of History</dfn> <span class="loc">(HB231)</span></li>

<li>Soros, George – <dfn>The Crash of 2008 and What It Means</dfn> <span class="loc">(HB3722)</span> <a href="https://notrelated.xyz/#02.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Keen, Steve – <dfn>Debunking Economics: The Naked Emperor Dethroned?</dfn> <span class="loc">(HB71)</span></li>

<li>Krugman, Paul – <dfn>The Accidental Theorist</dfn> <span class="loc">(HB74.5)</span></li>

<li>Hoppe, Hans Hermann – <dfn>Democracy: The God That Failed: The Economics and Politics of Monarchy, Democracy and Natural Law</dfn> <span class="loc">(HB74.P65)</span></li>

<li>Ekelund, Robert B. Jr. and Hébert, Robert F – <dfn>A History of Economic Theory and Method</dfn> <span class="loc">(HB75)</span></li>

<li>Buchholz, Todd G. – <dfn>New Ideas from Dead Economists, an Introduction to Modern Economic Thought</dfn> <span class="loc">(HB76)</span></li>

<li>Heilbroner, Robert L. – <dfn>The Worldly Philosophers</dfn> <span class="loc">(HB76)</span></li>

<li>Paul Erlich – <dfn>The Population Bomb</dfn> <span class="loc">(HB875.E35)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Palmer, Tom G. – <dfn>After the Welfare State</dfn> <span class="loc">(HB99.3)</span></li>

<li>Krugman, Paul – <dfn>Peddling Prosperity</dfn> <span class="loc">(HB99.7)</span></li>

<li>Walton, Gary M. and Rockoff, Hugh – <dfn>History of the American Economy</dfn> <span class="loc">(HC103)</span></li>

<li>Krugman, Paul – <dfn>The Great Unravelling</dfn> <span class="loc">(HC106)</span></li>

<li>Krugman, Paul – <dfn>The Conscience of a Liberal</dfn> <span class="loc">(HC110.I5)</span></li>

<li>Clark, Gregory – <dfn>A Farewell to Alms</dfn> <span class="loc">(HC21)</span></li>

<li>Easterly, William – <dfn>The Elusive Quest for Growth</dfn> <span class="loc">(HC59.72.P6)</span></li>

<li>Simon, Julian L. and Kahn, Herman – <dfn>The Resourceful Earth</dfn> <span class="loc">(HC59.R445)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Dixit, Avinash K. and Nalebuff, Barry J. – <dfn>Thinking Strategically, The Competitive Edge in Business, Politics, and Everyday Life</dfn> <span class="loc">(HD30.28)</span></li>

<li>Adams, Scott – <dfn>The Dilbert Principle</dfn> <span class="loc">(HD31)</span></li>

<li>Ehrenreich, Barbara – <dfn>Nickel and Dimed</dfn> <span class="loc">(HD4918)</span></li>

<li>Thiel, Peter – <dfn>Zero to One: Notes on Start-Ups, or How to Build the Future</dfn> <span class="loc">(HD62.5)</span></li>

<li>Montgomery, David – <dfn>Beyond Equality: Labor and the Radical Republicans 1862-1872</dfn> <span class="loc">(HD8076)</span></li>

<li>Caplan, Bryan – <dfn>The Myth of the Rational Voter: Why Democracies Choose Bad Policies</dfn> <span class="loc">(HD87)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bhagwati, Jagdish – <dfn>In Defense of Globalization</dfn> <span class="loc">(HF1359)</span></li>

<li>Krugman, Paul and Obstfield, Maurice – <dfn>International Economics</dfn> <span class="loc">(HF1359)</span></li>

<li>Lechner, Frank J. and Boli, John – <dfn>The Globalization Reader</dfn> <span class="loc">(HF1359)</span></li>

<li>Myrdal, Gunnar – <dfn>Beyond the Welfare State</dfn> <span class="loc">(HF1411)</span></li>

<li>Graeber, David – <dfn>Bullshit Jobs: A Theory</dfn> <span class="loc">(HF5549.5.J63)</span> <a href="https://notrelated.xyz/#02.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Soros, George – <dfn>In Defense of Open Society</dfn> <span class="loc">(HG172.S63)</span></li>

<li>Boortz, Neal and Linder, John – <dfn>The Fairtax Book: Saying Goodbye to the Income Tax and the IRS</dfn> <span class="loc">(HJ4652)</span></li>

<li>Stove, David – <dfn>Darwinian Fairytales</dfn> <span class="loc">(HM106)</span></li>

<li>O'Brien, Jodi – <dfn>The Production of Reality</dfn> <span class="loc">(HM1033)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Skin in the Game</dfn> <span class="loc">(HM1101)</span></li>

<li>Berne, Eric – <dfn>Games People Play</dfn> <span class="loc">(HM1106)</span></li>

<li>Pinker, Steven – <dfn>The Better Angels of Our Nature</dfn> <span class="loc">(HM1116)</span></li>

<li>Kropotkin, Peter – <dfn>Mutual Aid: A Factor of Evolution</dfn> <span class="loc">(HM131)</span></li>

<li>Diamond, Jared – <dfn>Guns, Germs and Steel</dfn> <span class="loc">(HM206)</span></li>

<li>Bork, Robert H. – <dfn>Slouching Towards Gomorrah: Modern Liberalism and American Decline</dfn> <span class="loc">(HN59.2)</span></li>

<li>Arnold, Matthew – <dfn>Culture and Anarchy</dfn> <span class="loc">(HN389)</span></li>

<li>Jones, E. Michael – <dfn>Libido Dominandi: Sexual Liberation and Political Control</dfn> <span class="loc">(HQ472.U6)</span></li>

<li>Eisler, Riane – <dfn>The Chalice and the Blade, Our History, Our Future</dfn> <span class="loc">(HQ1075)</span></li>

<li>Harris, Judith Rich – <dfn>The Nurture Assumption</dfn> <span class="loc">(HQ772)</span></li>

<li>Beuerlein, Mark – <dfn>The Dumbest Generation</dfn> <span class="loc">(HQ799.7)</span></li>

<li>Street, Oliver Day – <dfn>Symbolism of the Three Degrees</dfn> <span class="loc">(HS425)</span></li>

<li><dfn>Morals and Dogma of the Ancient and Accepted Scottish Rite of Freemasonry</dfn> <span class="loc">(HS767)</span></li>

<li><dfn>The 9/11 Commission Report: Final Report of the National Commission on Terrorist Attacks upon the United States</dfn> <span class="loc">(HV6432.7)</span></li>

<li>Engels, Frederick – <dfn>Socialism: Utopian and Scientific</dfn> <span class="loc">(HX276)</span></li>

<li>Hayek, F. A. – <dfn>The Intellectuals and Socialism</dfn> <span class="loc">(HX528)</span></li>

<li>More, Thomas – <dfn>Utopia</dfn> <span class="loc">(HX810.5)</span></li>

<li>Stringham, Edward P. – <dfn>Anarchy and the Law</dfn> <span class="loc">(HX833)</span></li>

<li>Schumpeter, Joseph Alois – <dfn>Capitalism, Socialism and Democracy</dfn> <span class="loc">(HX86)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bastiat, Frederic – <dfn>The Law</dfn> <span class="loc">(HX87)</span></li>

</ul>
<h2 id="j-k-political-science-and-law">J-K: Political Science and Law</h2>

<figure class="resright"><img src="/pix/archeofuturism.jpg"></figure>

<ul class="booklist">
<li>Faye, Guillaume – <dfn>Archeofuturism: European Visions of the Post-Catastrophic Age</dfn> <span class="loc">(JA84.F8)</span></li>

<li>Plato – <dfn>The Republic</dfn> <span class="loc">(JC71)</span></li>

<li>Machiavelli, Niccolò – <dfn>The Prince and Other Writings</dfn> <span class="loc">(JC143)</span></li>

<li>Hobbes, Thomas – <dfn>Leviathan</dfn> <span class="loc">(JC153)</span></li>

<li>Filmer, Robert – <dfn>Patriarcha, or, The Natural Power of Kings</dfn> <span class="loc">(JC153.F48)</span></li>

<li>Samons, Loren J. – <dfn>What's Wrong with Democracy?</dfn> <span class="loc">(JC421)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Mill, John Stewart – <dfn>On Liberty</dfn> <span class="loc">(JC585)</span></li>

<li>Reed, Lawrence W. – <dfn>Are We Good Enough for Liberty?</dfn> <span class="loc">(JC585)</span></li>

<li>Jeffery, – <dfn>People's War: New Light on the Struggle for South Africa</dfn> <span class="loc">(JQ1998.A4)</span></li>

<li>Beard, Charles – <dfn>An Economic Interpretation of the Constitution of the United States</dfn> <span class="loc">(JK146)</span></li>

<li>Smith, Bradley A. – <dfn>Unfree Speech: The Folly of Campaign Finance Reform</dfn> <span class="loc">(JK1991)</span></li>

<li>de Tocqueville, Alexis – <dfn>Democracy in America</dfn> <span class="loc">(JK216)</span></li>

<li>Brimelow, Peter – <dfn>Alien Nation: Common Sense about America's Immigration Disaster</dfn> <span class="loc">(JV6493)</span></li>

<li>Fukuyama, Francis – <dfn>America at the Crossroads: Democracy, Power and Neoconservative Legacy</dfn> <span class="loc">(JZ1480)</span></li>

<li>Silverglate, Harvey A. and French, David A. and Lukianoff, Greg – <dfn>FIRE's Guide to Free Speech on Campus</dfn> <span class="loc">(KF4123.5)</span></li>

<li>Bernstein, David E. – <dfn>You Can't Say That!</dfn> <span class="loc">(KF4749)</span></li>

</ul>
<h2 id="l-n-education-music-fine-arts">L-N: Education, Music, Fine Arts</h2>
<ul class="booklist">
<li>Bloom, Allan – <dfn>The Closing of the American Mind: How Higher Education Has Failed Democracy and Impoverished the Souls of Today's Students</dfn> <span class="loc">(LA227.3)</span></li>

<li>Russell, Bertrand – <dfn>Education and the Good Life</dfn> <span class="loc">(LB775)</span></li>

<li><dfn>Baptist Hymnal</dfn> <span class="loc">(M2122)</span></li>

<li>Towner, D. B., Lorenz, E. S. and Wilson, Ira B. – <dfn>Songs of Praise: A Collection of Gospel Songs for Men's Voices</dfn> <span class="loc">(M2198)</span></li>

<li>International Graphic Society – <dfn>The Arts of Mankind: Painting, Architecture, Music</dfn> <span class="loc">(N5302)</span></li>

<li>Barral i Altet, Xavier – <dfn>The Early Middle Ages: From Late Antiquity to A.D. 1000</dfn> <span class="loc">(NA350)</span></li>

<li>Churchill, Winston S. – <dfn>Painting as a Pastime: An instructive and inspiring invitation to the joy of painting</dfn> <span class="loc">(ND1142)</span></li>

<li>Cornelius, Maurits – <dfn>The Graphic Work of M.C. Escher</dfn> <span class="loc">(NE670.E75)</span></li>

</ul>
<h2 id="p-philology-linguistics">P: Philology, Linguistics</h2>

<figure class="resright"><img src="/pix/westernclassical.jpg" title="Good for learning some #Lindy linguistics"></figure>

<ul class="booklist">
<li>Smith, Luke – <dfn>External Possession and the Undisentanglability of Syntax and Semantics</dfn></li>

<li>Chomsky, Noam – <dfn>Language and Mind</dfn> <span class="loc">(P106)</span></li>

<li>Harris, Roy – <dfn>Language, Saussure and Wittgenstein, How to Play Games with Words</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>Words and Rules, the Ingredients of Language</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>The Stuff of Thought</dfn> <span class="loc">(P107)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: I Linguistic Theory: Foundations</dfn> <span class="loc">(P121)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: II Linguistics Theory: Extensions and Implications</dfn> <span class="loc">(P121)</span></li>

<li>Ohio State University – <dfn>Language Files 11</dfn> <span class="loc">(P121)</span></li>

<li>Chomsky, Noam – <dfn>The Logical Structure of Linguistic Theory</dfn> <span class="loc">(P158)</span></li>

<li>Falk, Yehuda N. – <dfn>Lexical-Functional Grammar, An Introduction to Parallel Constraint-Based Syntax</dfn> <span class="loc">(P158.25)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Chomsky's Minimalism</dfn> <span class="loc">(P158.28)</span></li>

<li>Gutiérrez, Bravo and Arellanes Arellanes, Francisco and Peón Herrero, Mario Ernesto Chávez – <dfn>Nuevos estudios de Teoría de la Optimalidad</dfn> <span class="loc">(P158.42)</span></li>

<li>Richards, Norvin – <dfn>Contiguity Theory</dfn> <span class="loc">(P224.R43)</span></li>

<li>Bresnan, Joan and Asudeh, Ash and Tolivonen, Ida and Wechsler, Stephen – <dfn>Lexical-Functional Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Chomsky, Noam – <dfn>Aspects of the Theory of Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Freidin, Robert – <dfn>Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Saeed, John I. – <dfn>Semantics</dfn> <span class="loc">(P325)</span></li>

<li>Dalby, Andrew – <dfn>Dictionary of Languages, the Definitive Reference to More than 400 Languages</dfn> <span class="loc">(P371)</span></li>

<li>Allan, Keith – <dfn>The Western Classical Tradition in Linguistics</dfn> <span class="loc">(P61)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Western Linguistics: An Historical Introduction</dfn> <span class="loc">(P61)</span></li>

<li>Klein, Jared – <dfn>An Indo-European Chrestomathy</dfn></li>

<li>Watkins, Calvert – <dfn>The American Heritage Dictionary of Indo-European Roots</dfn> <span class="loc">(P615)</span></li>

<li>Sampson, Geoff – <dfn>Schools of Linguistics</dfn> <span class="loc">(P77)</span></li>

<li>Harris, Randy Allen – <dfn>The Linguistics Wars</dfn> <span class="loc">(P85.C47)</span></li>

<li>Cutting, Joan – <dfn>Pragmatics and Discourse</dfn> <span class="loc">(P99.4.P72)</span></li>

</ul>
<h2 id="pa-greek-and-latin-language-and-literature">PA: Greek and Latin language and Literature</h2>

<figure class="resright"><img src="/pix/hughes.jpg" title="These are actually pretty good and readable English translations."></figure>

<ul class="booklist">
<li>Morrison, Clinton and Barnes, David H. – <dfn>New Testament Word Lists</dfn> <span class="loc">(PA881)</span></li>

<li>Magoffin, Ralph van Deman and Henry, Margaret Young – <dfn>Latin First Year</dfn> <span class="loc">(PA2087)</span></li>

<li>Wheelock, Frederic M. – <dfn>Latin, an Introductory Course Based on Ancient Authors</dfn> <span class="loc">(PA2087.5)</span></li>

<li>Orberg, Hans H – <dfn>Roma Aeterna</dfn> <span class="loc">(PA2094.5)</span></li>

<li>Orberg, Hans H – <dfn>Colloquium Personarum</dfn> <span class="loc">(PA2095)</span></li>

<li>Orberg, Hans H – <dfn>Lingua Latina</dfn> <span class="loc">(PA2095)</span></li>

<li>Simpson, D. P. – <dfn>Cassell's Latin Dictionary</dfn> <span class="loc">(PA2365.E5)</span></li>

<li>Landis, Paul – <dfn>Four Famous Greek Plays</dfn> <span class="loc">(PA3626.A2)</span></li>

<li>Aeschylus – <dfn>The Oresteia</dfn> <span class="loc">(PA3827.A7)</span></li>

<li>Apollonius of Rhodes – <dfn>Jason and the Argonauts (Argonautica)</dfn> <span class="loc">(PA3872)</span></li>

<li>Euripides – <dfn>Three Plays of Euripides: Alcestis, Medea, the Bacchae</dfn> <span class="loc">(PA3975)</span></li>

<li>Euripides – <dfn>Alcestis and Other Plays</dfn> <span class="loc">(PA3975.A5)</span></li>

<li>Corpus Hermeticum – <dfn>Hermes Trismegistus</dfn> <span class="loc">(PA3998)</span></li>

<li>Homer – <dfn>The Iliad</dfn> <span class="loc">(PA4025.A2)</span></li>

<li>Homer – <dfn>The Odyssey</dfn> <span class="loc">(PA4025.A5)</span></li>

<li>Sophocles – <dfn>The Theban Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>The Complete Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>Electra and Other Plays</dfn> <span class="loc">(PA4414.A2)</span></li>

<li>Feyerabend, Karl – <dfn>Greek-English Dictionary</dfn> <span class="loc">(PA445.E5)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Liddell, H. G. and Scott – <dfn>Greek-English Lexicon</dfn> <span class="loc">(PA445.E5)</span></li>

<li>Juvenal – <dfn>The Sixteen Satires</dfn> <span class="loc">(PA6447.E5)</span></li>

<li>Lucretius – <dfn>On the Nature of Things</dfn> <span class="loc">(PA6483.E5)</span></li>

<li>Hughes, Ted – <dfn>Tales from Ovid: Twenty-Four Passages from the 'Metamorphoses' by Ovid</dfn> <span class="loc">(PA6522)</span></li>

<li>Petronius – <dfn>the Satyricon and the Fragments</dfn> <span class="loc">(PA6558.E5)</span></li>

<li>Pliny the Younger – <dfn>Pliny: A Self-Portrait in Letters</dfn> <span class="loc">(PA6639.E5)</span></li>

<li>Virgil – <dfn>Aeneid</dfn> <span class="loc">(PA6807.A5)</span></li>

<li>Virgil – <dfn>The Pastoral Poems</dfn> <span class="loc">(PA6807.B7)</span></li>

</ul>
<h2 id="pc-romance-languages">PC: Romance Languages</h2>

<figure class="resright"><img src="/pix/lathrop.jpg" title="Lathrop's Course on Historical Spanish"></figure>

<ul class="booklist">
<li>Decker, Henry W. and Bernhard, Francoise – <dfn>Modern French</dfn> <span class="loc">(PC211)</span></li>

<li>Azevedo, Milton M. – <dfn>Introducción a la Lingüística Española</dfn> <span class="loc">(PC4073)</span></li>

<li>Lathrop, T. A. and Gutiérrex Cuadrado, Juan – <dfn>Curso de gramática histórica española</dfn> <span class="loc">(PC4101)</span></li>

<li>Moreno, Oscar – <dfn>Gramática avanzada del español</dfn> <span class="loc">(PC4129.E5)</span></li>

<li>Cash, Annette G. and Murray, James C. – <dfn>Teoría y técnicas de traduccón: primeras etapas</dfn> <span class="loc">(PC4498)</span></li>

<li>Gili Gaya, Samuel – <dfn>Vox: Diccionario abreviado de la lengua española</dfn> <span class="loc">(PC4625)</span></li>

</ul>
<h2 id="pd-pf-germanic-languages-and-literatures">PD-PF: Germanic Languages and Literatures</h2>
<ul class="booklist">
<li>Lambdin, Thomas O. – <dfn>An Introduction to the Gothic Language</dfn> <span class="loc">(PD1123)</span></li>

<li>Hugo – <dfn>Swedish Phrase Book</dfn> <span class="loc">(PD5121)</span></li>

<li>Warriner, John E. and Whitten, Mary E. and Friggith, Francis J. – <dfn>Warriner's English Grammar and Composition</dfn> <span class="loc">(PE1112)</span></li>

<li>Elson, William H. and Keck, Christine – <dfn>Elson Grammar School Literature Book Two</dfn> <span class="loc">(PE1121)</span></li>

<li>Mitchell, Brucew and Robinson, Fred C. – <dfn>A Guide to Old English</dfn> <span class="loc">(PE131)</span></li>

<li>Evans, Jonathan – <dfn>An Introduction to Old English</dfn> <span class="loc">(PE135)</span></li>

<li>Bright, James W. – <dfn>Bright's Anglo-Saxon Reader</dfn> <span class="loc">(PE137)</span></li>

<li>Gottschalk, Katherine and Keith Hjortshoj – <dfn>The Elements of Teaching Writing</dfn> <span class="loc">(PE1404)</span></li>

<li>Forsyth, Mark – <dfn>The Elements of Eloquence</dfn> <span class="loc">(PE1421)</span></li>

<li>McCloskey, Deirdre N. – <dfn>Economical Writing</dfn> <span class="loc">(PE1479.E35)</span></li>

<li>Sharp, Stanley Louis and Strothmann, Friedrich Wilhelm – <dfn>German Reading Grammar</dfn> <span class="loc">(PF3111)</span></li>

<li>Morgan, Baynard Quincy and Strothmann, Friedrich Wilhelm – <dfn>Reading German</dfn> <span class="loc">(PF3117)</span></li>

<li>Berlitz – <dfn>Berlitz Self-Teaching German</dfn> <span class="loc">(PF3121)</span></li>

</ul>
<h2 id="pj-pl-oriental-indo-iranian-east-asian-and-oceanian-languages">PJ-PL: Oriental, Indo-Iranian, East-Asian and Oceanian Languages</h2>

<figure class="resright"><img src="/pix/sastry.jpg" title="Sanskrit in the Development of World Thought"></figure>

<ul class="booklist">
<li>Anonymous – <dfn>The Epic of Gilgamesh</dfn> <span class="loc">(PJ3771.G5)</span></li>

<li>Wightwick, Jane and Gaafar, Mahmoud – <dfn>Mastering Arabic</dfn> <span class="loc">(PJ6307)</span></li>

<li>Luxenberg, Christoph – <dfn>The Syro-Aramaic Reading of the Koran: A Contribution to Decoding the Language of the Koran</dfn> <span class="loc">(PJ6696)</span></li>

<li>Burnell, Arthur Coke – <dfn>On the Aindra school of Sanskrit grammarians, their place in the Sanskrit and subordinate literatures</dfn> <span class="loc">(PK407)</span></li>

<li>Sastry, Vempaty Kutumba – <dfn>Sanskrit and Development of World Thought</dfn> <span class="loc">(PK423)</span></li>

<li>Elwell-Sutton, L. P. – <dfn>Elementary Persian Grammar</dfn> <span class="loc">(PK6235)</span></li>

<li>Whitney, William Dwight – <dfn>A Sanskrit Grammar: Including Both the Classical Language, and the Older Dialects, of the Veda and Brahmana</dfn> <span class="loc">(PK663)</span></li>

<li>Sutherland, Goldman – <dfn>Devavanipravesika</dfn> <span class="loc">(PK666)</span></li>

<li>Whitney, William Dwight – <dfn>The Roots, Verb-Forms, And Primary Derivatives of the Sankstrit Language: A Supplement to his Sanskrit Grammar</dfn> <span class="loc">(PK745)</span></li>

<li>DeFrancis, John – <dfn>Intermediate Chinese</dfn> <span class="loc">(PL11117)</span></li>

<li>DeFrancis, John – <dfn>Advanced Chinese</dfn> <span class="loc">(PL1121.C5)</span></li>

<li>Defense Language Institute – <dfn>Chinese: Basic Course</dfn> <span class="loc">(PL1125)</span></li>

<li>Seligman, Scott D. – <dfn>Mandarin Chinese at a Glance</dfn> <span class="loc">(PL1125.E6)</span></li>

<li>DeFrancis, John – <dfn>The Chinese Language, Fact and Fantasy</dfn> <span class="loc">(PL1171)</span></li>

<li><dfn>Oxford Chinese Dictionary</dfn> <span class="loc">(PL1455)</span></li>

<li>Waley, Arthur – <dfn>Translations from the Chinese</dfn> <span class="loc">(PL3277.E3)</span></li>

<li>Burlington, Scott – <dfn>Instant Hawaiian</dfn> <span class="loc">(PL6445)</span></li>

<li>Pukui, Mary Kawena and Elbert, Samuel H. and Mookini, Esther T. – <dfn>The Pocket Hawaiian Dictionary</dfn> <span class="loc">(PL6446)</span></li>

</ul>
<h2 id="pn-general-literature">PN: General Literature</h2>
<ul class="booklist">
<li>Butterworth, Hezekiah – <dfn>The Story of America</dfn> <span class="loc">(PN1009.A1)</span></li>

<li>Kaplar, Richard T. and Patrick D. Maines – <dfn>The Government Factor: Undermining Journalistic Ethics in the Information Age</dfn> <span class="loc">(PN4888.E8)</span></li>

<li>Schwarz, Leo W. – <dfn>Feast of Leviathan: Tales of Adventure, Faith and Love from Jewish Literature</dfn> <span class="loc">(PN6071.J5)</span></li>

<li><dfn>Treasury of Familiar Quotations</dfn> <span class="loc">(PN6081)</span></li>

<li><dfn>Reader's Digest Treasury of American Humor</dfn> <span class="loc">(PN6162)</span></li>

<li>The Onion – <dfn>Dispatches from the Tenth Circle</dfn> <span class="loc">(PN6165)</span></li>

<li>The Onion – <dfn>Our Dumb World</dfn> <span class="loc">(PN6231.A74)</span></li>

<li>Raymond, Eric S. – <dfn>The New Hacker's Dictionary</dfn> <span class="loc">(PN6231.E4)</span></li>

<li>The Onion – <dfn>Our Dumb Century</dfn> <span class="loc">(PN6231.N6)</span></li>

<li>Gómez Dávila, Nicolás – <dfn>Escolios a un texto implícito</dfn> <span class="loc">(PN6275)</span></li>

<li>Brown, Jeffrey – <dfn>Darth Vader and Son</dfn> <span class="loc">(PN6727.B7575)</span></li>

<li>Watterson, Bill – <dfn>Calvin and Hobbes: Scientific Progress Goes 'Boink'</dfn> <span class="loc">(PN6728.C34)</span></li>

<li>Lewis, C. S. – <dfn>The Discarded Image: An Introduction to Medieval and Renaissance Literature</dfn> <span class="loc">(PN671)</span></li>

</ul>
<h2 id="pq-romance-literature">PQ: Romance Literature</h2>

<figure class="resright"><img src="/pix/inferno.jpg"></figure>

<ul class="booklist">
<li>de Montaigne, Michel – <dfn>Montaigne Selected Essays</dfn> <span class="loc">(PQ1642.E6)</span></li>

<li>Morlière, Jean-Baptiste – <dfn>Tartuffe and Other Plays</dfn> <span class="loc">(PQ1842)</span></li>

<li>De Saint-Exupéry – <dfn>Sazadeo Qickek</dfn> <span class="loc">(PQ2637.A274)</span></li>

<li>Alighieri, Dante – <dfn>The Divine Comedy</dfn> <span class="loc">(PQ4315)</span></li>

<li>Alighieri, Dante – <dfn>The Inferno</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Alighieri, Dante – <dfn>I: Hell (Sayers translation)</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Eco, Umberto – <dfn>Foucault's Pendulum</dfn> <span class="loc">(PQ4864.C6)</span></li>

<li>De la Vega, Garcilaso – <dfn>Poesías</dfn> <span class="loc">(PQ6391)</span></li>

<li>Garcia Lorca, Federico – <dfn>Rosita la soltera</dfn> <span class="loc">(PQ6613.A763)</span></li>

<li>Pérez-Reverte, Arturo – <dfn>La tabla de Flandés</dfn> <span class="loc">(PQ6666.E765)</span></li>

<li>Rulfo, Juan &amp;ndash; Pedro – <dfn>y El Llano en llamas</dfn> <span class="loc">(PQ7297.R89)</span></li>

</ul>
<h2 id="pr-english-literature">PR: English Literature</h2>
<ul class="booklist">
<li>Clark, Thomas Curtis and Gillespie, Esther A. – <dfn>1000 Quotable Poems</dfn> <span class="loc">(PR1175)</span></li>

<li><dfn>Beowulf</dfn> <span class="loc">(PR1583)</span></li>

<li>Chaucer, Geoffrey – <dfn>Chaucer's Major Poetry</dfn> <span class="loc">(PR1851)</span></li>

<li>Chaucer, Geoffrey – <dfn>The Canterbury Tales</dfn> <span class="loc">(PR1870.A1)</span></li>

<li>Collis, Louise – <dfn>Memoirs of a Medieval Woman</dfn> <span class="loc">(PR2007)</span></li>

<li>Malory, Thomas – <dfn>Le Morte d'Arthur</dfn> <span class="loc">(PR2041)</span></li>

<li>Craig, W. J. – <dfn>The Complete Works of William Shakespeare</dfn> <span class="loc">(PR2753.C8)</span></li>

<li>Shakespeare, William – <dfn>Hamlet (2 copies)</dfn> <span class="loc">(PR2801.A2)</span></li>

<li>Shakespeare, William – <dfn>Macbeth</dfn> <span class="loc">(PR2823.A2)</span></li>

<li>Shakespeare, William – <dfn>A Midsummer Night's Dream</dfn> <span class="loc">(PR2827.A2)</span></li>

<li>Shakespeare, William – <dfn>The Merchant of Venice</dfn> <span class="loc">(PR2825.A2)</span></li>

<li>Shakespeare, William – <dfn>The Sonnets</dfn> <span class="loc">(PR2848.A2)</span></li>

<li>Crystal, David – <dfn>The Oxford Dictionary of Original Shakespearean Pronunciation</dfn> <span class="loc">(PR2892)</span></li>

<li>Bunyan, John – <dfn>Pilgrim's Progress</dfn> <span class="loc">(PR3330)</span></li>

<li>Milton, John – <dfn>Paradise Lost and Other Poems</dfn> <span class="loc">(PR3560)</span></li>

<li>Coleridge, Samuel Taylor – <dfn>The Rime of the Ancient Mariner</dfn> <span class="loc">(PR4479)</span></li>

<li>Dickens, Charles – <dfn>Great Expectations</dfn> <span class="loc">(PR4560)</span></li>

<li>Shaw, George Bernard – <dfn>Pygmalion</dfn> <span class="loc">(PR5363)</span></li>

<li>Stevenson, Robert Louis – <dfn>The Black Arrow</dfn> <span class="loc">(PR5484)</span></li>

<li>Stevenson, Robert Louis – <dfn>New Arabian Nights</dfn> <span class="loc">(PR5484)</span></li>

<li>Wells, H. G. – <dfn>The Island of Dr. Moreau</dfn> <span class="loc">(PR5774)</span></li>

<li>Wilde, Oscar – <dfn>The Importance of Being Earnest</dfn> <span class="loc">(PR5818)</span></li>

<li>Christie, Agatha – <dfn>Death on the Nile</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Christie, Agatha – <dfn>The Nursery Rhyme Murders</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Golding, William – <dfn>Lord of the Flies</dfn> <span class="loc">(PR6013.O35)</span></li>

<li>Lewis, C. S. – <dfn>The Lion, the Witch and the Wardrobe</dfn> <span class="loc">(PR6023.E926)</span></li>

<li>Huxley, Aldous – <dfn>Brave New World</dfn> <span class="loc">(PR6015.U9)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Lord of the Rings, One-Volume Edition</dfn> <span class="loc">(PR6039.O32)</span></li>

<li>White, T. H. – <dfn>The Once and Future King</dfn> <span class="loc">(PR6045.H2)</span></li>

<li>Adams, Douglas – <dfn>Life, the Universe and Everything</dfn> <span class="loc">(PR6051.D3352)</span></li>

<li>Erickson, Paul – <dfn>Doctor Who: The Ark</dfn> <span class="loc">(PR6052.R449)</span></li>

<li>Burgess, Anthony – <dfn>A Clockwork Orange</dfn> <span class="loc">(PR6052.U638)</span></li>

<li>Grimwade, Peter – <dfn>Doctor Who: Planet of Fire</dfn> <span class="loc">(PR6057.R545)</span></li>

<li>Halleck, Reuben Post – <dfn>History of English Literature</dfn> <span class="loc">(PR85)</span></li>

<li>Achebe, Chinua – <dfn>Things Fall Apart</dfn> <span class="loc">(PR9387.9.A3)</span></li>

</ul>
<h2 id="ps-american-literature">PS: American Literature</h2>

<figure class="resright"><img src="/pix/lovecraft.jpg"></figure>

<ul class="booklist">
<li>Twain, Mark – <dfn>A Connecticut Yankee in King Arthur's Court</dfn> <span class="loc">(PS1308)</span></li>

<li>Hawthorne, Nathaniel – <dfn>The Scarlet Letter</dfn> <span class="loc">(PS1868)</span></li>

<li>Poe, Edgar Allan – <dfn>Edgar Allan Poe Reader</dfn> <span class="loc">(PS2603)</span></li>

<li>Poe, Edgar Allen – <dfn>Tales of Terror and Detection</dfn> <span class="loc">(PS2612)</span></li>

<li>Thoreau, Henry David – <dfn>Walden</dfn> <span class="loc">(PS3048)</span></li>

<li>Wallace, Lew – <dfn>Ben Hur</dfn> <span class="loc">(PS3134)</span></li>

<li>Faulkner, William – <dfn>Light in August</dfn> <span class="loc">(PS3511.A86)</span></li>

<li>Fitzgerald, F. Scott – <dfn>The Great Gatsby</dfn> <span class="loc">(PS3511.I9)</span></li>

<li>Heinlein, Robert A. – <dfn>For Us, the Living</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Heinlein, Robert A. – <dfn>The Moon is a Harsh Mistress</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Lovecraft, H. P. – <dfn>Great Tales of Horror</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Case of Charles Dexter Ward</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Doom That Came to Sarnath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Dream Quest of Unknown Kadath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Tomb</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Rodgers, Marion Elizabeth – <dfn>Mencken &amp; Sara</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Mencken, H. L. – <dfn>The Vintage Mencken</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Rand, Ayn – <dfn>Atlas Shugged</dfn> <span class="loc">(PS3535.A547)</span></li>

<li>Skinner, B. F. – <dfn>Walden Two</dfn> <span class="loc">(PS3537.K527)</span></li>

<li>Smith, Clark Ashton – <dfn>Hyperborea</dfn> <span class="loc">(PS3537.M335)</span></li>

<li>Bear, Greg – <dfn>Darwin's Radio</dfn> <span class="loc">(PS3552.E157)</span></li>

<li>Card, Orson Scott – <dfn>Ender's Game</dfn> <span class="loc">(PS3553.A655)</span></li>

<li>Crichton, Michael – <dfn>Congo</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Jurassic Park</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Timeline</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Dick, Philip K. – <dfn>Dr. Bloodmoney</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Dick, Philip K. – <dfn>Flow My Tears, The Policeman Said</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Herbert, Frank – <dfn>Dune</dfn> <span class="loc">(PS3558.E63)</span></li>

<li>Jordan, Robert – <dfn>The Eye of the World</dfn> <span class="loc">(PS3560.O7617)</span></li>

<li>King, Stephen – <dfn>The Bazaar of Bad Dreams</dfn> <span class="loc">(PS3561.I483)</span></li>

<li>Myers, Bill – <dfn>Blood of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Fire of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Threshold</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Quinn, Daniel – <dfn>Ishmael: An Adventure of the Mind and Spirit</dfn> <span class="loc">(PS3567.U338)</span></li>

<li>Pearl, Matthew – <dfn>The Dante Club</dfn> <span class="loc">(PS3616.E25)</span></li>

<li>Asimov, Isaac – <dfn>Before the Golden Age: A Science Fiction Anthology of the 1930's</dfn> <span class="loc">(PS648.S3)</span></li>

<li>Saramago, José – <dfn>Todos los nombres</dfn> <span class="loc">(PS9281.A66)</span></li>

</ul>
<h2 id="pq-pz-other-literature">PQ-PZ: Other Literature</h2>

<figure class="resright"><img src="/pix/edda.jpg"></figure>

<ul class="booklist">
<li>Voltaire – <dfn>Candide, Zadig and selected stories</dfn> <span class="loc">(PQ2081.E5)</span></li>

<li>Hesse, Hermann – <dfn>Siddhartha</dfn> <span class="loc">(PT2617.E85)</span></li>

<li>Hesse, Hermann – <dfn>The Glass Bead Game</dfn> <span class="loc">(PT2617.E85 G513)</span></li>

<li>Sturluson, Snorri – <dfn>Poetic Edda</dfn> <span class="loc">(PT7235)</span></li>

<li>Sturluson, Snorri – <dfn>Prose Edda</dfn> <span class="loc">(PT7313.E5)</span></li>

<li>Borges, Jorge Luis – <dfn>Ficciones</dfn> <span class="loc">(PW7797.B635)</span></li>

<li>Connor, Ralph – <dfn>Black Rock: a Tale of the Selkirks</dfn> <span class="loc">(PZ3.G654)</span></li>

<li>Roberts, James Hall – <dfn>The Q Document</dfn> <span class="loc">(PZ4.D913)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Hobbit</dfn> <span class="loc">(PZ7.T5744)</span></li>

<li>Wilder, Laura Ingalls – <dfn>Little House (entire series)</dfn> <span class="loc">(PZ7.W6461)</span></li>

<li>Jacobs, Joseph – <dfn>Favorite Celtic Fairy Tales</dfn> <span class="loc">(PZ8)</span></li>

<li>Baum, L. Frank – <dfn>The Wizard of Oz</dfn> <span class="loc">(PZ8.B327)</span></li>

<li><dfn>The Brothers Grimm Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

<li><dfn>The Complete Grimm's Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

</ul>
<h2 id="qa-general-science">QA: General Science</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hVxvLd6cF0k"><img src="/pix/againstmethod.jpg"></a></figure>

<ul class="booklist">
<li>de Santillanna, Giorgio – <dfn>The Origins of Scientific Thought: from Anazimander to Proclus, 600 B.C. to 300 A.D.</dfn> <span class="loc">(Q125)</span></li>

<li>Gardner, Martin – <dfn>Great Essays in Science</dfn> <span class="loc">(Q171)</span></li>

<li>Kuhn, Thomas – <dfn>The Structure of Scientific Revolutions</dfn> <span class="loc">(Q175)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Wiener, Norbert – <dfn>The Human Use of Human Beings</dfn> <span class="loc">(Q175)</span></li>

<li>Feyerabend, Paul – <dfn>Against Method </dfn> <span class="loc">(Q175)</span></li>

<li>Motterlini, Matteo – <dfn>For and Against Method: Including Lakatos's Lectures on Scientific Method and the Lakatos-Feyerabend Correspondence </dfn> <span class="loc">(Q175.3)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Antifragile</dfn> <span class="loc">(Q375)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>The Black Swan</dfn> <span class="loc">(Q375)</span></li>

</ul>
<h2 id="qa-mathematics">QA: Mathematics</h2>
<ul class="booklist">
<li>Sawyer, W. W. – <dfn>Mathematician's Delight</dfn> <span class="loc">(QA37)</span></li>

<li>Birns, Peter and Brown, Patrick and Muster, John C. C. – <dfn>Unix for People</dfn> <span class="loc">(QA76.6)</span></li>

<li>Raymond, Eric S. – <dfn>The Cathedral and the Bazaar</dfn> <span class="loc">(QA76.76.O63)</span></li>

<li>Bellos, Alex – <dfn>Here's Looking at Euclid</dfn> <span class="loc">(QA141.15)</span></li>

<li>Nyberg, Joseph A. – <dfn>Second Course in Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Wentworth, G. A. – <dfn>New School Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Hart, William – <dfn>College Algebra</dfn> <span class="loc">(QA154)</span></li>

<li>Lial, Margaret L. and Miller, Charles D. – <dfn>Algebra and Trigonometry</dfn> <span class="loc">(QA154.2)</span></li>

<li>Sokal, Alan and Bricmont, Jean – <dfn>Fashionable Nonsense: Postmodern Intellectuals' Abuse of Science</dfn> <span class="loc">(QA175)</span></li>

<li>Neugebauer, Otto – <dfn>The Exact Sciences in Antiquity</dfn> <span class="loc">(QA22)</span></li>

<li>Bharati Krsna Thirthaji Maharaja – <dfn>Vedic Mathematics</dfn> <span class="loc">(QA27.I4)</span></li>

<li>Christian, Robert R. – <dfn>Introduction to Logic and Sets</dfn> <span class="loc">(QA248)</span></li>

<li>Davis, Morton D. – <dfn>Game Theory: A Nontechnical Introduction</dfn> <span class="loc">(QA269)</span></li>

<li>Friedman, Avner – <dfn>Differential Games</dfn> <span class="loc">(QA272)</span></li>

<li>Takahashi, Shin – <dfn>The Manga Guide to Statistics</dfn> <span class="loc">(QA276)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 1-10</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 10-15 and Appendices</dfn> <span class="loc">(QA303)</span></li>

<li>Smith, Edward S. and Salkover, Meyer and Justive, Howard K. – <dfn>Unified Calculus</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny – <dfn>Calculus with Analytic Geometry</dfn> <span class="loc">(QA33)</span></li>

<li>Sperling, Abraham and Stuart, Monroe – <dfn>Mathematics (Made Simple Self-Teaching Library)</dfn> <span class="loc">(QA39.2)</span></li>

<li>Horblit, Marcus and Nielson, Kaj L. – <dfn>Problems in Plane Geometry with Solutions</dfn> <span class="loc">(QA459)</span></li>

<li>Shively, Levi S. – <dfn>Modern Geometry</dfn> <span class="loc">(QA473)</span></li>

<li>Nelson, Alfred L. and Folley, Karl W. – <dfn>Plane and Spherical Trigonometry</dfn> <span class="loc">(QA531.N45)</span></li>

<li>Love, Clyde E. – <dfn>Analytic Geometry</dfn> <span class="loc">(QA551)</span></li>

<li>Hutton, Graham – <dfn>Programming in Haskell</dfn> <span class="loc">(QA76.62)</span></li>

<li>Kernighan, Brian W. and Ritchie, Dennis M. – <dfn>The C Programming Language</dfn> <span class="loc">(QA76.73.C15)</span></li>

<li>Barski, Conrad – <dfn>Land of Lisp</dfn> <span class="loc">(QA76.76.C672)</span></li>

<li>Hofstadter, Douglas – <dfn>Gödel, Escher, Bach</dfn> <span class="loc">(QA9.8)</span></li>

<li>Emmet, E. R. – <dfn>Brain Puzzler's Delight</dfn> <span class="loc">(QA95)</span></li>

<li>Emmet, E. R. – <dfn>Puzzles for Pleasure</dfn> <span class="loc">(QA95)</span></li>

<li>Gardner, Martin – <dfn>aha! Gotcha, Paradoxes to puzzle and delight</dfn> <span class="loc">(QA95)</span></li>

<li>Heafford, Philip – <dfn>The Math Entertainer</dfn> <span class="loc">(QA95)</span></li>

</ul>
<h2 id="qb-qr-other-sciences">QB-QR: Other Sciences</h2>
<ul class="booklist">
<li>Hawking, Stephen W. – <dfn>A Brief History of Time</dfn> <span class="loc">(QB981)</span></li>

<li>Lerner, Eric – <dfn>The Big Bang Never Happened</dfn> <span class="loc">(QB991.B54)</span></li>

<li>McEvoy, J. P. and Zarate, Oscar – <dfn>Quantum Theory, A Graphic Guide</dfn> <span class="loc">(QC173.98)</span></li>

<li>Booker, Christopher – <dfn>The Real Global Warming Disaster</dfn> <span class="loc">(QC981.8.G56)</span></li>

<li>Greenburg, Arthur – <dfn>From Alchemy to Chemistry in Picture and Story</dfn> <span class="loc">(QD11)</span></li>

<li>Valentine, Basil – <dfn>Of Natural and Supernatural Things: Also, of the First Tincture, Root, and Spirit of Metals and Minerals: How the Same are Conceived, Generated, Brought Forth, Changed and Augmented</dfn> <span class="loc">(QD25)</span></li>

<li>Watson, James – <dfn>The Double Helix</dfn> <span class="loc">(QH31.D434)</span></li>

<li>Fodor, Jerry and Piattelli Palmarini, Massimo – <dfn>What Darwin Got Wrong</dfn> <span class="loc">(QH375)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Kadans, Joseph M. – <dfn>Modern Encyclopedia of Herbs</dfn> <span class="loc">(QK99.A1)</span></li>

<li>McFarland, J. Horace – <dfn>Getting Acquainted with Trees</dfn> <span class="loc">(QK482)</span></li>

<li>Kurzweil, Ray – <dfn>The Singularity is Near</dfn> <span class="loc">(QP376)</span></li>

<li>Kandel, Eric R. and Schwartz, James H. and Jessell, Thomas M. – <dfn>Essentials of Neural Science and Behavior</dfn> <span class="loc">(QP355.2)</span></li>

</ul>
<h2 id="r-medicine">R: Medicine</h2>
<ul class="booklist">
<li>FC&amp;A – <dfn>The Folk Remedy Encyclopedia: Olive Oil, Vinegar, Honey and 1,001 Other Home Remedies</dfn> <span class="loc">(R733)</span></li>

<li><dfn>Better Homes and Gardens Family Medical Guide</dfn> <span class="loc">(RC81.A2)</span></li>

<li><dfn>The Encyclopedia of Common Diseases</dfn> <span class="loc">(RC81.A2)</span></li>

</ul>
<h2 id="s-t-agriculture-and-technology">S-T: Agriculture and Technology</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=YRNKjQg6y-c"><img src="/pix/salatin.jpg"></a></figure>

<ul class="booklist">
<li>Mollison, Bill – <dfn>Introduction to Permaculture</dfn> <span class="loc">(S494.5.P47)</span></li>

<li>Salatin, Joel – <dfn>Everything I Want to Do Is Illegal</dfn> <span class="loc">(S605.5)</span></li>

<li>David the Good – <dfn>Totally Crazy Easy Florida Gardening</dfn></li>

<li>Seymour, John – <dfn>The Complete Book of Self-Sufficiency</dfn> <span class="loc">(S605.5)</span></li>

<li>Cobleigh, Rolfe – <dfn>Handy Farm Devices and How to Make Them (2 copies)</dfn> <span class="loc">(S676)</span></li>

<li>Seymour, John – <dfn>Gardener's Delight</dfn> <span class="loc">(SB322)</span></li>

<li>Seymour, John – <dfn>The Self-Sufficient Gardener</dfn> <span class="loc">(SB324.3)</span></li>

<li>Haring, Elda – <dfn>The Seedling Handbook</dfn> <span class="loc">(SB405)</span></li>

<li>Abraham, George – <dfn>The Green Thumb Garden Handbook</dfn> <span class="loc">(SB453)</span></li>

<li><dfn>Reader's Digest Illustrated Guide to Gardening</dfn> <span class="loc">(SB453)</span></li>

<li>Kaczynski, Theodore John – <dfn>Technological Slavery</dfn> <span class="loc">(T14.5)</span></li>

<li>Kaczynski, Theodore John – <dfn>Anti-Tech Revolution: Why and How</dfn> <span class="loc">(T14.5)</span></li>

<li>Macaulay, David and Ardleym Neil – <dfn>The Way Things Work</dfn> <span class="loc">(T47)</span></li>

<li>Slater, Robert and Li, Ling and Li, Wen – <dfn>Portraits in Silicon</dfn> <span class="loc">(TK7885.2)</span></li>

<li>Bishop, Michael and Zimmerman, Holmes – <dfn>Detailing Cars and Trucks</dfn> <span class="loc">(TL152)</span></li>

<li>Allaby, Michael and Lovelock, James – <dfn>The Greening of Mars</dfn> <span class="loc">(TL795.7)</span></li>

<li>Abbey, Barbara – <dfn>The Complete Book of Knitting</dfn> <span class="loc">(TT820)</span></li>

<li>Bishop, Jack – <dfn>Vegetables Every Day</dfn> <span class="loc">(TX801)</span></li>

<li>Lo, Kenneth – <dfn>Chinese Regional Cooking</dfn> <span class="loc">(TX724.5.C5)</span></li>

</ul>
<h2 id="books-as-of-yet-unsorted">Books as of yet unsorted</h2>
<ul class="booklist">
<li>Seb Falk – <dfn>The Light Ages: The Surprising Story of Medieval Science</dfn></li>

<li><dfn>The Penny Catechism: A Catechism of Christian Doctrine</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese Reader, Part 1</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese</dfn></li>

<li>Flame Tree Publishing – <dfn>Gothic Fantasy: Lost Worlds Short Stories</dfn></li>

<li>Lee, Christopher – <dfn>This Sceptered Isle 55 BC to 1901</dfn></li>

<li>Malice, Michael – <dfn>Dear Reader</dfn></li>

<li>McCloskey, Deirdre N. – <dfn>Economic Writing</dfn></li>

<li>Meyer, Jerome S. – <dfn>The Provocative Puzzler</dfn></li>

<li>Parikh, Prashant – <dfn>Language and Equilibrium</dfn></li>

<li>Reed, Lawrence W. – <dfn>Great Myths of the Great Depression</dfn></li>

<li><dfn>Using HTML4, Java 1.1, and Javascript 1.2</dfn></li>

<li>Valizadeh, Roosh – <dfn>Game</dfn></li>

<li>Vikernes, Varg – <dfn>MYFAROG 2.6</dfn></li>

</ul>
<div style="clear:both" class="taglist">Read related articles:<br><a id="tag_personal" href="https://lukesmith.xyz/tags/personal">Personal</a> · <a id="tag_science" href="https://lukesmith.xyz/tags/science">Science</a> · <a id="tag_tradition" href="https://lukesmith.xyz/tags/tradition">Tradition</a> · <a id="tag_lifestyle" href="https://lukesmith.xyz/tags/lifestyle">Lifestyle</a> · <a id="tag_philosophy" href="https://lukesmith.xyz/tags/philosophy">Philosophy</a></div>
<br clear="both">
</article>
<p>This is a list of the books in my personal library. If you have any
questions or want me to review any of them, email me
(<a href="mailto:luke@lukesmith.xyz">luke@lukesmith.xyz</a>).</p>
This is a list of the books in my personal library. If you have any
questions or want me to review any of them, email me
(
<a href="mailto:luke@lukesmith.xyz">luke@lukesmith.xyz</a>
).
<p>This is a list of the books in my personal library. If you have any
questions or want me to review any of them, email me
(<a href="mailto:luke@lukesmith.xyz">luke@lukesmith.xyz</a>).</p>
<p>I haven't read every book here, nor do I own all the books I've read
or like. I also don't necessarily like all the books I own.</p>
I haven't read every book here, nor do I own all the books I've read
or like. I also don't necessarily like all the books I own.
<p>I haven't read every book here, nor do I own all the books I've read
or like. I also don't necessarily like all the books I own.</p>
<p>Check out <a href="https://notrelated.xyz">my podcast, <em>Not Related!</em></a>
for some book reviews and other things. Books I've talked about in one
way or another in the podcast will have a link to that episode.</p>
Check out
<a href="https://notrelated.xyz">my podcast, <em>Not Related!</em></a>

for some book reviews and other things. Books I've talked about in one
way or another in the podcast will have a link to that episode.
<p>Check out <a href="https://notrelated.xyz">my podcast, <em>Not Related!</em></a>
for some book reviews and other things. Books I've talked about in one
way or another in the podcast will have a link to that episode.</p>
<h2 id="-lindypressnet-books">🆕 LindyPress.net Books</h2>
<p>Note that now I am reprinting out-of-print works at
<a href="https://lindypress.net">LindyPress.net</a>. You can buy any of these books
yourself if you'd like. (Most of them are pretty exclusive in that I'm
the only one reprinting them.)</p>
Note that now I am reprinting out-of-print works at

<a href="https://lindypress.net">LindyPress.net</a>
. You can buy any of these books
yourself if you'd like. (Most of them are pretty exclusive in that I'm
the only one reprinting them.)
<p>Note that now I am reprinting out-of-print works at
<a href="https://lindypress.net">LindyPress.net</a>. You can buy any of these books
yourself if you'd like. (Most of them are pretty exclusive in that I'm
the only one reprinting them.)</p>
<ul>
<li>Pseudo-Aristotle – <a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a></li>
<li><a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a></li>
<li>Isidore of Seville – <a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a></li>
<li>Roger Bacon ‐ <a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a></li>
<li>Marcus Aurelius – <a href="https://lindypress.net/book?pk=2">Meditations</a></li>
<li><a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a></li>
</ul>
<li>Pseudo-Aristotle – <a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a></li>
Pseudo-Aristotle –
<a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a>
<li>Pseudo-Aristotle – <a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a></li>
<li><a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a></li>
<a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a>
<li><a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a></li>
<li>Isidore of Seville – <a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a></li>
Isidore of Seville –
<a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a>
<li>Isidore of Seville – <a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a></li>
<li>Roger Bacon ‐ <a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a></li>
Roger Bacon ‐
<a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a>
<li>Roger Bacon ‐ <a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a></li>
<li>Marcus Aurelius – <a href="https://lindypress.net/book?pk=2">Meditations</a></li>
Marcus Aurelius –
<a href="https://lindypress.net/book?pk=2">Meditations</a>
<li>Marcus Aurelius – <a href="https://lindypress.net/book?pk=2">Meditations</a></li>
<li><a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a></li>
<a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a>
<li><a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a></li>
<ul>
<li>Pseudo-Aristotle – <a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a></li>
<li><a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a></li>
<li>Isidore of Seville – <a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a></li>
<li>Roger Bacon ‐ <a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a></li>
<li>Marcus Aurelius – <a href="https://lindypress.net/book?pk=2">Meditations</a></li>
<li><a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a></li>
</ul>
<p>(These are at the top since I don't know if anyone has given them Library of
Congress numbers, and I suppose as an ad.)</p>
(These are at the top since I don't know if anyone has given them Library of
Congress numbers, and I suppose as an ad.)
<p>(These are at the top since I don't know if anyone has given them Library of
Congress numbers, and I suppose as an ad.)</p>
<h2 id="a-bd-general-works-philosophy-logic-speculative-philosophy">A-BD: General Works, Philosophy, Logic, Speculative Philosophy</h2>
<figure class="resright"><a href="https://www.youtube.com/watch?v=hCVdCS0t46I"><img src="/pix/searle.jpg" title="Searle (actually literally) did nothing wrong."></a></figure>
<a href="https://www.youtube.com/watch?v=hCVdCS0t46I"><img src="/pix/searle.jpg" title="Searle (actually literally) did nothing wrong."></a>
<figure class="resright"><a href="https://www.youtube.com/watch?v=hCVdCS0t46I"><img src="/pix/searle.jpg" title="Searle (actually literally) did nothing wrong."></a></figure>
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
<h2 id="bm-bx-specific-religions-and-theology">BM-BX: Specific Religions and Theology</h2>
<figure class="resright"><img src="/pix/biglot.jpg" title="A Greek and Latin biglottic Bible"></figure>
<img src="/pix/biglot.jpg" title="A Greek and Latin biglottic Bible">
<figure class="resright"><img src="/pix/biglot.jpg" title="A Greek and Latin biglottic Bible"></figure>
<ul class="booklist">
<li><dfn>'תְּהִלַּת ה</dfn> <span class="loc">(BM675/D3)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Key to Theosophy</dfn> <span class="loc">(BP561)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Voice of Silence</dfn> <span class="loc">(BP561)</span></li>

<li>Wright, Stuart – <dfn>Armageddon in Waco</dfn> <span class="loc">(BP605.B62)</span></li>

<li>Lewis, C. S. – <dfn>Mere Christianity</dfn> <span class="loc">(BR123)</span></li>

<li>Lewis, C. S. – <dfn>The Screwtape Letters</dfn> <span class="loc">(BR125)</span></li>

<li>Reardon, Patrick Henry – <dfn>Christ in the Psalms</dfn> <span class="loc">(BS1430.4)</span></li>

<li>Leithart, Peter J. – <dfn>Solomon Among the Postmoderns</dfn> <span class="loc">(BS1475.52)</span></li>

<li>Porter, J. R. – <dfn>The Lost Bible</dfn> <span class="loc">(BS1700)</span></li>

<li>Heiser, Michael – <dfn>Reversing Hermon: Enoch, the Watchers and the Forgotten Mission of Jesus Christ</dfn> <span class="loc">(BS1830.E7)</span></li>

<li><dfn>The New Oxford Annotated Bible</dfn> <span class="loc">(BS191.5.A1)</span></li>

<li><dfn>The New English Bible</dfn> <span class="loc">(BS192.A1)</span></li>

<li>Montano, Arias and Leudsen, Johann – <dfn>Greek-Latin Parallel New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>Pocket Interlinear New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>The New International Dictionary of New Testament Theology (3 Volumes)</dfn> <span class="loc">(BS2312)</span></li>

<li><dfn>Ἡ Καινὴ Διαθήκη</dfn> <span class="loc">(BS2312)</span></li>

<li>Kümmel, Werner Georg – <dfn>Introduction to the New Testament</dfn> <span class="loc">(BS2330)</span></li>

<li>Aland, Kurt – <dfn>Synopsis Quattuor Evangeliorum</dfn> <span class="loc">(BS2560.A2)</span></li>

<li>Mack. Burton L. – <dfn>A Myth of Innocence</dfn> <span class="loc">(BS2585.2)</span></li>

<li>Ehrman, Bart D. – <dfn>Lost Christianities: The Battles for Scriptures and the Faiths We Never Knew</dfn> <span class="loc">(BS2840.E4)</span></li>

<li>Luther, Martin – <dfn>Luther's Small Catechism with Additions Including the Augsburg Confession</dfn> <span class="loc">(BR331.K64)</span></li>

<li>Strong, James – <dfn>Strong's Exhaustive Concordance of the Bible with Hebrew and Greek Dictionaries</dfn> <span class="loc">(BS425)</span></li>

<li><dfn>Illustrated Dictionary and Concordance of the Bible</dfn> <span class="loc">(BS440)</span></li>

<li>McDowell, Josh – <dfn>The New Evidence that Demands a Verdict</dfn> <span class="loc">(BS480)</span></li>

<li>Laymon, Charles M. – <dfn>The Interpreter's One-Volume Commentary on the Bible</dfn> <span class="loc">(BS491.2)</span></li>

<li>Cross, John R. – <dfn>The Stranger on the Road to Emmaus</dfn> <span class="loc">(BS511.2)</span></li>

<li><dfn>Reader's Digest Mysteries of the Bible; the Enduring Questions of the Scriptures</dfn> <span class="loc">(BS538)</span></li>

<li>Smith, Brendan Powell – <dfn>The Brick Bible</dfn> <span class="loc">(BS550.3)</span></li>

<li>Kent, Paul and McLaughlan, David – <dfn>Know Your Bible: All 66 Books Explained and Applied</dfn> <span class="loc">(BS593)</span></li>

<li><dfn>Septuagint with Apocrypha</dfn> <span class="loc">(BS742)</span></li>

<li><dfn>Biblia Sacra Vulgata</dfn> <span class="loc">(BS75)</span></li>

<li>Newman, John Henry – <dfn>An Essay on the Development of Christian Doctrine</dfn> <span class="loc">(BT21)</span></li>

<li>Robinson, James M. – <dfn>The Nag Hammadi Library</dfn> <span class="loc">(BT1391)</span></li>

<li>Lewis, C. S. – <dfn>Surprised by Joy: The Shape of My Early Life</dfn> <span class="loc">(BV4935.L43)</span></li>

<li>Carman, Stephen L. and Owen, Bob – <dfn>Quest: The Story of an Aerospace Engineer who Challenged God to Prove Himself</dfn> <span class="loc">(BV4930)</span></li>

<li>Ware, Timothy – <dfn>The Orthodox Church</dfn> <span class="loc">(BX106)</span></li>

<li>Aveling, J. C. H. – <dfn>The Jesuits</dfn> <span class="loc">(BX3706.2)</span></li>

<li><dfn>The Book of Common Prayer</dfn> <span class="loc">(BX5145)</span></li>

<li><dfn>Five Great Encyclicals: Labor, Education, Marriage, Reconstructing the Social Order, Atheistic Communism</dfn> <span class="loc">(BX860)</span></li>

</ul>
<li><dfn>'תְּהִלַּת ה</dfn> <span class="loc">(BM675/D3)</span></li>
<li>Blavatsky, Helena Petrovna – <dfn>The Key to Theosophy</dfn> <span class="loc">(BP561)</span></li>
<li>Blavatsky, Helena Petrovna – <dfn>The Voice of Silence</dfn> <span class="loc">(BP561)</span></li>
<li>Wright, Stuart – <dfn>Armageddon in Waco</dfn> <span class="loc">(BP605.B62)</span></li>
<li>Lewis, C. S. – <dfn>Mere Christianity</dfn> <span class="loc">(BR123)</span></li>
<li>Lewis, C. S. – <dfn>The Screwtape Letters</dfn> <span class="loc">(BR125)</span></li>
<li>Reardon, Patrick Henry – <dfn>Christ in the Psalms</dfn> <span class="loc">(BS1430.4)</span></li>
<li>Leithart, Peter J. – <dfn>Solomon Among the Postmoderns</dfn> <span class="loc">(BS1475.52)</span></li>
<li>Porter, J. R. – <dfn>The Lost Bible</dfn> <span class="loc">(BS1700)</span></li>
<li>Heiser, Michael – <dfn>Reversing Hermon: Enoch, the Watchers and the Forgotten Mission of Jesus Christ</dfn> <span class="loc">(BS1830.E7)</span></li>
<li><dfn>The New Oxford Annotated Bible</dfn> <span class="loc">(BS191.5.A1)</span></li>
<li><dfn>The New English Bible</dfn> <span class="loc">(BS192.A1)</span></li>
<li>Montano, Arias and Leudsen, Johann – <dfn>Greek-Latin Parallel New Testament</dfn> <span class="loc">(BS1965)</span></li>
<li><dfn>Pocket Interlinear New Testament</dfn> <span class="loc">(BS1965)</span></li>
<li><dfn>The New International Dictionary of New Testament Theology (3 Volumes)</dfn> <span class="loc">(BS2312)</span></li>
<li><dfn>Ἡ Καινὴ Διαθήκη</dfn> <span class="loc">(BS2312)</span></li>
<li>Kümmel, Werner Georg – <dfn>Introduction to the New Testament</dfn> <span class="loc">(BS2330)</span></li>
<li>Aland, Kurt – <dfn>Synopsis Quattuor Evangeliorum</dfn> <span class="loc">(BS2560.A2)</span></li>
<li>Mack. Burton L. – <dfn>A Myth of Innocence</dfn> <span class="loc">(BS2585.2)</span></li>
<li>Ehrman, Bart D. – <dfn>Lost Christianities: The Battles for Scriptures and the Faiths We Never Knew</dfn> <span class="loc">(BS2840.E4)</span></li>
<li>Luther, Martin – <dfn>Luther's Small Catechism with Additions Including the Augsburg Confession</dfn> <span class="loc">(BR331.K64)</span></li>
<li>Strong, James – <dfn>Strong's Exhaustive Concordance of the Bible with Hebrew and Greek Dictionaries</dfn> <span class="loc">(BS425)</span></li>
<li><dfn>Illustrated Dictionary and Concordance of the Bible</dfn> <span class="loc">(BS440)</span></li>
<li>McDowell, Josh – <dfn>The New Evidence that Demands a Verdict</dfn> <span class="loc">(BS480)</span></li>
<li>Laymon, Charles M. – <dfn>The Interpreter's One-Volume Commentary on the Bible</dfn> <span class="loc">(BS491.2)</span></li>
<li>Cross, John R. – <dfn>The Stranger on the Road to Emmaus</dfn> <span class="loc">(BS511.2)</span></li>
<li><dfn>Reader's Digest Mysteries of the Bible; the Enduring Questions of the Scriptures</dfn> <span class="loc">(BS538)</span></li>
<li>Smith, Brendan Powell – <dfn>The Brick Bible</dfn> <span class="loc">(BS550.3)</span></li>
<li>Kent, Paul and McLaughlan, David – <dfn>Know Your Bible: All 66 Books Explained and Applied</dfn> <span class="loc">(BS593)</span></li>
<li><dfn>Septuagint with Apocrypha</dfn> <span class="loc">(BS742)</span></li>
<li><dfn>Biblia Sacra Vulgata</dfn> <span class="loc">(BS75)</span></li>
<li>Newman, John Henry – <dfn>An Essay on the Development of Christian Doctrine</dfn> <span class="loc">(BT21)</span></li>
<li>Robinson, James M. – <dfn>The Nag Hammadi Library</dfn> <span class="loc">(BT1391)</span></li>
<li>Lewis, C. S. – <dfn>Surprised by Joy: The Shape of My Early Life</dfn> <span class="loc">(BV4935.L43)</span></li>
<li>Carman, Stephen L. and Owen, Bob – <dfn>Quest: The Story of an Aerospace Engineer who Challenged God to Prove Himself</dfn> <span class="loc">(BV4930)</span></li>
<li>Ware, Timothy – <dfn>The Orthodox Church</dfn> <span class="loc">(BX106)</span></li>
<li>Aveling, J. C. H. – <dfn>The Jesuits</dfn> <span class="loc">(BX3706.2)</span></li>
<li><dfn>The Book of Common Prayer</dfn> <span class="loc">(BX5145)</span></li>
<li><dfn>Five Great Encyclicals: Labor, Education, Marriage, Reconstructing the Social Order, Atheistic Communism</dfn> <span class="loc">(BX860)</span></li>
<ul class="booklist">
<li><dfn>'תְּהִלַּת ה</dfn> <span class="loc">(BM675/D3)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Key to Theosophy</dfn> <span class="loc">(BP561)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Voice of Silence</dfn> <span class="loc">(BP561)</span></li>

<li>Wright, Stuart – <dfn>Armageddon in Waco</dfn> <span class="loc">(BP605.B62)</span></li>

<li>Lewis, C. S. – <dfn>Mere Christianity</dfn> <span class="loc">(BR123)</span></li>

<li>Lewis, C. S. – <dfn>The Screwtape Letters</dfn> <span class="loc">(BR125)</span></li>

<li>Reardon, Patrick Henry – <dfn>Christ in the Psalms</dfn> <span class="loc">(BS1430.4)</span></li>

<li>Leithart, Peter J. – <dfn>Solomon Among the Postmoderns</dfn> <span class="loc">(BS1475.52)</span></li>

<li>Porter, J. R. – <dfn>The Lost Bible</dfn> <span class="loc">(BS1700)</span></li>

<li>Heiser, Michael – <dfn>Reversing Hermon: Enoch, the Watchers and the Forgotten Mission of Jesus Christ</dfn> <span class="loc">(BS1830.E7)</span></li>

<li><dfn>The New Oxford Annotated Bible</dfn> <span class="loc">(BS191.5.A1)</span></li>

<li><dfn>The New English Bible</dfn> <span class="loc">(BS192.A1)</span></li>

<li>Montano, Arias and Leudsen, Johann – <dfn>Greek-Latin Parallel New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>Pocket Interlinear New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>The New International Dictionary of New Testament Theology (3 Volumes)</dfn> <span class="loc">(BS2312)</span></li>

<li><dfn>Ἡ Καινὴ Διαθήκη</dfn> <span class="loc">(BS2312)</span></li>

<li>Kümmel, Werner Georg – <dfn>Introduction to the New Testament</dfn> <span class="loc">(BS2330)</span></li>

<li>Aland, Kurt – <dfn>Synopsis Quattuor Evangeliorum</dfn> <span class="loc">(BS2560.A2)</span></li>

<li>Mack. Burton L. – <dfn>A Myth of Innocence</dfn> <span class="loc">(BS2585.2)</span></li>

<li>Ehrman, Bart D. – <dfn>Lost Christianities: The Battles for Scriptures and the Faiths We Never Knew</dfn> <span class="loc">(BS2840.E4)</span></li>

<li>Luther, Martin – <dfn>Luther's Small Catechism with Additions Including the Augsburg Confession</dfn> <span class="loc">(BR331.K64)</span></li>

<li>Strong, James – <dfn>Strong's Exhaustive Concordance of the Bible with Hebrew and Greek Dictionaries</dfn> <span class="loc">(BS425)</span></li>

<li><dfn>Illustrated Dictionary and Concordance of the Bible</dfn> <span class="loc">(BS440)</span></li>

<li>McDowell, Josh – <dfn>The New Evidence that Demands a Verdict</dfn> <span class="loc">(BS480)</span></li>

<li>Laymon, Charles M. – <dfn>The Interpreter's One-Volume Commentary on the Bible</dfn> <span class="loc">(BS491.2)</span></li>

<li>Cross, John R. – <dfn>The Stranger on the Road to Emmaus</dfn> <span class="loc">(BS511.2)</span></li>

<li><dfn>Reader's Digest Mysteries of the Bible; the Enduring Questions of the Scriptures</dfn> <span class="loc">(BS538)</span></li>

<li>Smith, Brendan Powell – <dfn>The Brick Bible</dfn> <span class="loc">(BS550.3)</span></li>

<li>Kent, Paul and McLaughlan, David – <dfn>Know Your Bible: All 66 Books Explained and Applied</dfn> <span class="loc">(BS593)</span></li>

<li><dfn>Septuagint with Apocrypha</dfn> <span class="loc">(BS742)</span></li>

<li><dfn>Biblia Sacra Vulgata</dfn> <span class="loc">(BS75)</span></li>

<li>Newman, John Henry – <dfn>An Essay on the Development of Christian Doctrine</dfn> <span class="loc">(BT21)</span></li>

<li>Robinson, James M. – <dfn>The Nag Hammadi Library</dfn> <span class="loc">(BT1391)</span></li>

<li>Lewis, C. S. – <dfn>Surprised by Joy: The Shape of My Early Life</dfn> <span class="loc">(BV4935.L43)</span></li>

<li>Carman, Stephen L. and Owen, Bob – <dfn>Quest: The Story of an Aerospace Engineer who Challenged God to Prove Himself</dfn> <span class="loc">(BV4930)</span></li>

<li>Ware, Timothy – <dfn>The Orthodox Church</dfn> <span class="loc">(BX106)</span></li>

<li>Aveling, J. C. H. – <dfn>The Jesuits</dfn> <span class="loc">(BX3706.2)</span></li>

<li><dfn>The Book of Common Prayer</dfn> <span class="loc">(BX5145)</span></li>

<li><dfn>Five Great Encyclicals: Labor, Education, Marriage, Reconstructing the Social Order, Atheistic Communism</dfn> <span class="loc">(BX860)</span></li>

</ul>
<h2 id="c-auxiliary-sciences-of-history">C: Auxiliary Sciences of History</h2>
<ul class="booklist">
<li>Graeber, David and Wengrow, David – <dfn>The Dawn of Everything: A New History of Humanity</dfn> <span class="loc">(CB19)</span></li>

<li>McNeill, William H. – <dfn>The Rise of the West: A History of the Human Community</dfn> <span class="loc">(CB59)</span></li>

<li>Sitchin, Zecharia – <dfn>The 12th Planet</dfn> <span class="loc">(CB156)</span></li>

<li>Rohl, David – <dfn>The Lords of Avaris: Uncovering the Legendary Origins of Western Civilization</dfn> <span class="loc">(CB245)</span> <a href="https://notrelated.xyz/#02.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Casson, Lionel and Clairborne, Robert and Fagan, Brian and Karp, Walter – <dfn>Mysteries of the Past</dfn> <span class="loc">(CB311)</span></li>

<li>Fisher, Marshall John and Fisher, David E. – <dfn>Mysteries of Lost Empires</dfn> <span class="loc">(CB311)</span></li>

<li>Hawkes, Jacquetta – <dfn>The Atlas of Early Man</dfn> <span class="loc">(CB311)</span></li>

<li>Platt, Richard and Riddell, Chris – <dfn>Castle Diary</dfn> <span class="loc">(CB351)</span></li>

<li>Cahill, Thomas – <dfn>Mysteries of the Middle Ages</dfn> <span class="loc">(CB351)</span></li>

</ul>
<li>Graeber, David and Wengrow, David – <dfn>The Dawn of Everything: A New History of Humanity</dfn> <span class="loc">(CB19)</span></li>
<li>McNeill, William H. – <dfn>The Rise of the West: A History of the Human Community</dfn> <span class="loc">(CB59)</span></li>
<li>Sitchin, Zecharia – <dfn>The 12th Planet</dfn> <span class="loc">(CB156)</span></li>
<li>Rohl, David – <dfn>The Lords of Avaris: Uncovering the Legendary Origins of Western Civilization</dfn> <span class="loc">(CB245)</span> <a href="https://notrelated.xyz/#02.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>
<li>Casson, Lionel and Clairborne, Robert and Fagan, Brian and Karp, Walter – <dfn>Mysteries of the Past</dfn> <span class="loc">(CB311)</span></li>
<li>Fisher, Marshall John and Fisher, David E. – <dfn>Mysteries of Lost Empires</dfn> <span class="loc">(CB311)</span></li>
<li>Hawkes, Jacquetta – <dfn>The Atlas of Early Man</dfn> <span class="loc">(CB311)</span></li>
<li>Platt, Richard and Riddell, Chris – <dfn>Castle Diary</dfn> <span class="loc">(CB351)</span></li>
<li>Cahill, Thomas – <dfn>Mysteries of the Middle Ages</dfn> <span class="loc">(CB351)</span></li>
<ul class="booklist">
<li>Graeber, David and Wengrow, David – <dfn>The Dawn of Everything: A New History of Humanity</dfn> <span class="loc">(CB19)</span></li>

<li>McNeill, William H. – <dfn>The Rise of the West: A History of the Human Community</dfn> <span class="loc">(CB59)</span></li>

<li>Sitchin, Zecharia – <dfn>The 12th Planet</dfn> <span class="loc">(CB156)</span></li>

<li>Rohl, David – <dfn>The Lords of Avaris: Uncovering the Legendary Origins of Western Civilization</dfn> <span class="loc">(CB245)</span> <a href="https://notrelated.xyz/#02.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Casson, Lionel and Clairborne, Robert and Fagan, Brian and Karp, Walter – <dfn>Mysteries of the Past</dfn> <span class="loc">(CB311)</span></li>

<li>Fisher, Marshall John and Fisher, David E. – <dfn>Mysteries of Lost Empires</dfn> <span class="loc">(CB311)</span></li>

<li>Hawkes, Jacquetta – <dfn>The Atlas of Early Man</dfn> <span class="loc">(CB311)</span></li>

<li>Platt, Richard and Riddell, Chris – <dfn>Castle Diary</dfn> <span class="loc">(CB351)</span></li>

<li>Cahill, Thomas – <dfn>Mysteries of the Middle Ages</dfn> <span class="loc">(CB351)</span></li>

</ul>
<h2 id="d-world-history">D: World History</h2>
<figure class="resright"><img src="/pix/racehutton.jpg" title="Hutton's book on the Third Reich"></figure>
<img src="/pix/racehutton.jpg" title="Hutton's book on the Third Reich">
<figure class="resright"><img src="/pix/racehutton.jpg" title="Hutton's book on the Third Reich"></figure>
<ul class="booklist">
<li>Malesky, Kee – <dfn>All Facts Considered, the Essential Library of Inessential Knowledge</dfn> <span class="loc">(D10)</span></li>

<li>Evola, Julius – <dfn>Revolt Against the Modern World</dfn> <span class="loc">(D16.8)</span></li>

<li>Epstein, Steven A. – <dfn>An Economic and Social History of Later Medieval Europe, 1000-1500</dfn> <span class="loc">(D117)</span></li>

<li>Pirenne, Henri – <dfn>A History of Europe</dfn> <span class="loc">(D117)</span></li>

<li>Cantor, Nroman F. – <dfn>Medieval History: The Life and Death of a Civilization</dfn> <span class="loc">(D118)</span></li>

<li>Roberts, J. M. – <dfn>New History of the World</dfn> <span class="loc">(D20)</span></li>

<li>Mann, Charles C. – <dfn>1493, Uncovering the New World Columbus Created</dfn> <span class="loc">(D228)</span></li>

<li>Rogan, Eugene L. – <dfn>The FAll of the Ottomans: The Great War in the Middle East</dfn> <span class="loc">(D566)</span></li>

<li>Sanborn, Frederick R. – <dfn>Design for War: A Study of Secret Power Politics</dfn> <span class="loc">(D742.U5)</span></li>

<li>Cheyney, Edward P. – <dfn>A Short History of England</dfn> <span class="loc">(DA32)</span></li>

<li>Thomas, Charles – <dfn>Celtic Britain</dfn> <span class="loc">(DA140)</span></li>

<li>Sellar, W.C. &amp; Yeatman R.J. – <dfn>1066 and All That</dfn> <span class="loc">(DA33)</span></li>

<li>Freeman, John and Sharpe, Sue – <dfn>This Beautiful Land: Britain</dfn> <span class="loc">(DA632)</span></li>

<li>Hutton, Christopher – <dfn>Race and the Third Reich</dfn> <span class="loc">(DD253)</span></li>

<li>Tacitus, C. Cornellius – <dfn>Annales et Historiae</dfn> <span class="loc">(DG207.T3)</span></li>

<li>Shirer, William L. – <dfn>The Rise and Fall of the Third Reich</dfn> <span class="loc">(DD256.5)</span></li>

<li>MacDonald, Kevin – <dfn>The Culture of Critique: An Evolutionary Analysis of Jewish Involvement in Twentieth-Century Intellectual and Political Movements</dfn> <span class="loc">(DS143)</span></li>

<li>Ford, Henry Sr. – <dfn>The International Jew: The World's Foremost Problem</dfn> <span class="loc">(DS145)</span></li>

<li>Ali, Tariq – <dfn>The Duel: Pakistan on the Flight Path of American Power</dfn> <span class="loc">(DS384)</span></li>

<li>De Bary, William Theodore – <dfn>The Sources of Indian Tradition</dfn> <span class="loc">(DS423)</span></li>

<li>Keay, John – <dfn>India, A History</dfn> <span class="loc">(DS451)</span></li>

<li>Ebrey, Patricia Buckley – <dfn>Cambridge Illustrated History of China</dfn> <span class="loc">(DS706)</span></li>

<li>National Geographic Society – <dfn>Journey into China</dfn> <span class="loc">(DS712)</span></li>

</ul>
<li>Malesky, Kee – <dfn>All Facts Considered, the Essential Library of Inessential Knowledge</dfn> <span class="loc">(D10)</span></li>
<li>Evola, Julius – <dfn>Revolt Against the Modern World</dfn> <span class="loc">(D16.8)</span></li>
<li>Epstein, Steven A. – <dfn>An Economic and Social History of Later Medieval Europe, 1000-1500</dfn> <span class="loc">(D117)</span></li>
<li>Pirenne, Henri – <dfn>A History of Europe</dfn> <span class="loc">(D117)</span></li>
<li>Cantor, Nroman F. – <dfn>Medieval History: The Life and Death of a Civilization</dfn> <span class="loc">(D118)</span></li>
<li>Roberts, J. M. – <dfn>New History of the World</dfn> <span class="loc">(D20)</span></li>
<li>Mann, Charles C. – <dfn>1493, Uncovering the New World Columbus Created</dfn> <span class="loc">(D228)</span></li>
<li>Rogan, Eugene L. – <dfn>The FAll of the Ottomans: The Great War in the Middle East</dfn> <span class="loc">(D566)</span></li>
<li>Sanborn, Frederick R. – <dfn>Design for War: A Study of Secret Power Politics</dfn> <span class="loc">(D742.U5)</span></li>
<li>Cheyney, Edward P. – <dfn>A Short History of England</dfn> <span class="loc">(DA32)</span></li>
<li>Thomas, Charles – <dfn>Celtic Britain</dfn> <span class="loc">(DA140)</span></li>
<li>Sellar, W.C. &amp; Yeatman R.J. – <dfn>1066 and All That</dfn> <span class="loc">(DA33)</span></li>
<li>Freeman, John and Sharpe, Sue – <dfn>This Beautiful Land: Britain</dfn> <span class="loc">(DA632)</span></li>
<li>Hutton, Christopher – <dfn>Race and the Third Reich</dfn> <span class="loc">(DD253)</span></li>
<li>Tacitus, C. Cornellius – <dfn>Annales et Historiae</dfn> <span class="loc">(DG207.T3)</span></li>
<li>Shirer, William L. – <dfn>The Rise and Fall of the Third Reich</dfn> <span class="loc">(DD256.5)</span></li>
<li>MacDonald, Kevin – <dfn>The Culture of Critique: An Evolutionary Analysis of Jewish Involvement in Twentieth-Century Intellectual and Political Movements</dfn> <span class="loc">(DS143)</span></li>
<li>Ford, Henry Sr. – <dfn>The International Jew: The World's Foremost Problem</dfn> <span class="loc">(DS145)</span></li>
<li>Ali, Tariq – <dfn>The Duel: Pakistan on the Flight Path of American Power</dfn> <span class="loc">(DS384)</span></li>
<li>De Bary, William Theodore – <dfn>The Sources of Indian Tradition</dfn> <span class="loc">(DS423)</span></li>
<li>Keay, John – <dfn>India, A History</dfn> <span class="loc">(DS451)</span></li>
<li>Ebrey, Patricia Buckley – <dfn>Cambridge Illustrated History of China</dfn> <span class="loc">(DS706)</span></li>
<li>National Geographic Society – <dfn>Journey into China</dfn> <span class="loc">(DS712)</span></li>
<ul class="booklist">
<li>Malesky, Kee – <dfn>All Facts Considered, the Essential Library of Inessential Knowledge</dfn> <span class="loc">(D10)</span></li>

<li>Evola, Julius – <dfn>Revolt Against the Modern World</dfn> <span class="loc">(D16.8)</span></li>

<li>Epstein, Steven A. – <dfn>An Economic and Social History of Later Medieval Europe, 1000-1500</dfn> <span class="loc">(D117)</span></li>

<li>Pirenne, Henri – <dfn>A History of Europe</dfn> <span class="loc">(D117)</span></li>

<li>Cantor, Nroman F. – <dfn>Medieval History: The Life and Death of a Civilization</dfn> <span class="loc">(D118)</span></li>

<li>Roberts, J. M. – <dfn>New History of the World</dfn> <span class="loc">(D20)</span></li>

<li>Mann, Charles C. – <dfn>1493, Uncovering the New World Columbus Created</dfn> <span class="loc">(D228)</span></li>

<li>Rogan, Eugene L. – <dfn>The FAll of the Ottomans: The Great War in the Middle East</dfn> <span class="loc">(D566)</span></li>

<li>Sanborn, Frederick R. – <dfn>Design for War: A Study of Secret Power Politics</dfn> <span class="loc">(D742.U5)</span></li>

<li>Cheyney, Edward P. – <dfn>A Short History of England</dfn> <span class="loc">(DA32)</span></li>

<li>Thomas, Charles – <dfn>Celtic Britain</dfn> <span class="loc">(DA140)</span></li>

<li>Sellar, W.C. &amp; Yeatman R.J. – <dfn>1066 and All That</dfn> <span class="loc">(DA33)</span></li>

<li>Freeman, John and Sharpe, Sue – <dfn>This Beautiful Land: Britain</dfn> <span class="loc">(DA632)</span></li>

<li>Hutton, Christopher – <dfn>Race and the Third Reich</dfn> <span class="loc">(DD253)</span></li>

<li>Tacitus, C. Cornellius – <dfn>Annales et Historiae</dfn> <span class="loc">(DG207.T3)</span></li>

<li>Shirer, William L. – <dfn>The Rise and Fall of the Third Reich</dfn> <span class="loc">(DD256.5)</span></li>

<li>MacDonald, Kevin – <dfn>The Culture of Critique: An Evolutionary Analysis of Jewish Involvement in Twentieth-Century Intellectual and Political Movements</dfn> <span class="loc">(DS143)</span></li>

<li>Ford, Henry Sr. – <dfn>The International Jew: The World's Foremost Problem</dfn> <span class="loc">(DS145)</span></li>

<li>Ali, Tariq – <dfn>The Duel: Pakistan on the Flight Path of American Power</dfn> <span class="loc">(DS384)</span></li>

<li>De Bary, William Theodore – <dfn>The Sources of Indian Tradition</dfn> <span class="loc">(DS423)</span></li>

<li>Keay, John – <dfn>India, A History</dfn> <span class="loc">(DS451)</span></li>

<li>Ebrey, Patricia Buckley – <dfn>Cambridge Illustrated History of China</dfn> <span class="loc">(DS706)</span></li>

<li>National Geographic Society – <dfn>Journey into China</dfn> <span class="loc">(DS712)</span></li>

</ul>
<h2 id="e-f-history-of-the-americas">E-F: History of the Americas</h2>
<figure class="resright"><img src="/pix/foxfire.jpg"></figure>
<ul class="booklist">
<li>Hancock, Graham – <dfn>America Before: The Key to Earth's Lost Civilization</dfn> <span class="loc">(E61)</span></li>

<li>Little, Gregory – <dfn>Path of Souls: The Native American Death Journey: Cygnus, Orion, the Milky Way, Giant Skeletons in Mounds, &amp; the Smithsonian</dfn> <span class="loc">(E98.M8)</span></li>

<li>Mooney, James – <dfn>Myths of the Cherokee</dfn> <span class="loc">(E99.C5)</span></li>

<li>Greenblatt, Stephen – <dfn>New World Encounters</dfn> <span class="loc">(E141)</span></li>

<li>Fischer, David Hackett – <dfn>Albion's Seed: Four British Folkways in America</dfn> <span class="loc">(E169.1)</span> <a href="https://notrelated.xyz/#01.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Sowell, Thomas – <dfn>Ethnic America</dfn> <span class="loc">(E184.A1)</span></li>

<li>Hurmence, Belinda – <dfn>Before Freedom: 48 Oral Histories of Former North and South Carolina Slaves</dfn> <span class="loc">(E444)</span></li>

<li>Adams, Nehemiah – <dfn>A South-side View of Slavery: or Three Months at the South in 1854</dfn> <span class="loc">(E449)</span></li>

<li>Parsons, Charles Grandison – <dfn>An Inside View of Slavery; or A Tour Among the Planters</dfn> <span class="loc">(E449)</span></li>

<li>Long, A. L. – <dfn>Memoirs of Robert E. Lee</dfn> <span class="loc">(E467.1.L4)</span></li>

<li>Henry, Robert Selph – <dfn>The Story of the Confederacy</dfn> <span class="loc">(E487)</span></li>

<li>Mann, Charles C. – <dfn>1491, New Revelations of the Americas Before Columbus</dfn> <span class="loc">(E61)</span></li>

<li>Wharton, H. M. – <dfn>War Songs and Poems of the Southern Confederacy, 1861-1865: a Collection of the Most Popular and Impressive Songs and Poems of War Times, Dear to Every Southern Heart</dfn> <span class="loc">(E647)</span></li>

<li><dfn>The Blue Book of the John Birch Society</dfn> <span class="loc">(E743.5)</span></li>

<li>Stormer, John A. – <dfn>The Death of a Nation</dfn> <span class="loc">(E743.5)</span></li>

<li>Ramo, Joshua Cooper – <dfn>The Age of the Unthinkable</dfn> <span class="loc">(E902)</span></li>

<li>de las Casas, Bartolomé – <dfn>Brevisima relación de la destrución de las Indias</dfn> <span class="loc">(F1411)</span></li>

<li><dfn>The Foxfire Book</dfn> <span class="loc">(F291.2)</span></li>

<li><dfn>The Foxfire Book 2</dfn> <span class="loc">(F291.2)</span></li>

</ul>
<h2 id="g-geography-anthropology-recreation">G: Geography, Anthropology, Recreation</h2>
<ul class="booklist">
<li>Winer, Richard – <dfn>Ghost Ships: True Stories of Nautical Nightmares, Hauntings, and Disasters</dfn> <span class="loc">(G525)</span></li>

<li><dfn>National Geographic Collegiate Atlas of the World</dfn> <span class="loc">(G1021)</span></li>

<li>Wells, Spencer – <dfn>Pandora's Seed: The Unforeseen Cost of Civilization</dfn> <span class="loc">(GF75)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cochran, Gregory and Harpending, Henry – <dfn>the 10,000 Explosion: How Civilization Accelerated Human Evolution</dfn> <span class="loc">(GN281.4)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cremo, Michael A. &amp; Thompson, Ricahrd L. – <dfn>Forbidden Archaeology: The Hidden History of the Human Race</dfn> <span class="loc">(GN741)</span></li>

<li>Hancock, Graham – <dfn>Magicians of the Gods: The Forgotten Wisdom of Earth's Lost Civilization</dfn> <span class="loc">(GN751)</span></li>

<li>Cayce, Hugh Lynn – <dfn>Edgar Cayce on Atlantis</dfn> <span class="loc">(GN751.C35)</span></li>

<li>Marshack, Alexander – <dfn>The Roots of Civilization: The Cognitive Beginnings of Man's First Art, Symbol and Notation</dfn> <span class="loc">(GN772)</span></li>

<li>Bord, Janet and Bord, Colin – <dfn>Prehistoric Britain from the Air</dfn> <span class="loc">(GN805)</span></li>

<li>Bruce, Annette J. – <dfn>More Tellable Cracker Tales</dfn> <span class="loc">(GR110.F5)</span></li>

</ul>
<h2 id="h-social-sciences">H: Social Sciences</h2>
<p>
</p>
<figure class="resright"><img src="/pix/democracy.jpg"></figure>
<figure class="resright"><img src="/pix/pike.jpg"></figure>
<p></p>
<ul class="booklist">
<li>Greenspan, Alan – <dfn>The Age of Turbulence</dfn> <span class="loc">(HB119.G74)</span></li>

<li>Hazlitt, Hentry – <dfn>Economics in One Lesson (two copies)</dfn> <span class="loc">(HB171)</span></li>

<li>Keynes, John Maynard – <dfn>The General Theory of Employment, Interest and Money</dfn> <span class="loc">(HB171)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Rothbard, Murray – <dfn>Man, Economy and State with Power and Market</dfn> <span class="loc">(HB171)</span></li>

<li>von Mises, Ludwig – <dfn>Economic Policy</dfn> <span class="loc">(HB171)</span></li>

<li>Boulding, Kenneth E. – <dfn>Economic Analysis</dfn> <span class="loc">(HB171.5)</span></li>

<li>Goodman, Kennard E. and Moore, William L. – <dfn>Economics in Everyday Life</dfn> <span class="loc">(HB171.5)</span></li>

<li>Pindyck, Robert S. and Rubinfeld, Daniel L. – <dfn>Microeconomics</dfn> <span class="loc">(HB172)</span></li>

<li>Fisher, David Hackett – <dfn>The Great Wave: Price Revolutions and the Rhythm of History</dfn> <span class="loc">(HB231)</span></li>

<li>Soros, George – <dfn>The Crash of 2008 and What It Means</dfn> <span class="loc">(HB3722)</span> <a href="https://notrelated.xyz/#02.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Keen, Steve – <dfn>Debunking Economics: The Naked Emperor Dethroned?</dfn> <span class="loc">(HB71)</span></li>

<li>Krugman, Paul – <dfn>The Accidental Theorist</dfn> <span class="loc">(HB74.5)</span></li>

<li>Hoppe, Hans Hermann – <dfn>Democracy: The God That Failed: The Economics and Politics of Monarchy, Democracy and Natural Law</dfn> <span class="loc">(HB74.P65)</span></li>

<li>Ekelund, Robert B. Jr. and Hébert, Robert F – <dfn>A History of Economic Theory and Method</dfn> <span class="loc">(HB75)</span></li>

<li>Buchholz, Todd G. – <dfn>New Ideas from Dead Economists, an Introduction to Modern Economic Thought</dfn> <span class="loc">(HB76)</span></li>

<li>Heilbroner, Robert L. – <dfn>The Worldly Philosophers</dfn> <span class="loc">(HB76)</span></li>

<li>Paul Erlich – <dfn>The Population Bomb</dfn> <span class="loc">(HB875.E35)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Palmer, Tom G. – <dfn>After the Welfare State</dfn> <span class="loc">(HB99.3)</span></li>

<li>Krugman, Paul – <dfn>Peddling Prosperity</dfn> <span class="loc">(HB99.7)</span></li>

<li>Walton, Gary M. and Rockoff, Hugh – <dfn>History of the American Economy</dfn> <span class="loc">(HC103)</span></li>

<li>Krugman, Paul – <dfn>The Great Unravelling</dfn> <span class="loc">(HC106)</span></li>

<li>Krugman, Paul – <dfn>The Conscience of a Liberal</dfn> <span class="loc">(HC110.I5)</span></li>

<li>Clark, Gregory – <dfn>A Farewell to Alms</dfn> <span class="loc">(HC21)</span></li>

<li>Easterly, William – <dfn>The Elusive Quest for Growth</dfn> <span class="loc">(HC59.72.P6)</span></li>

<li>Simon, Julian L. and Kahn, Herman – <dfn>The Resourceful Earth</dfn> <span class="loc">(HC59.R445)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Dixit, Avinash K. and Nalebuff, Barry J. – <dfn>Thinking Strategically, The Competitive Edge in Business, Politics, and Everyday Life</dfn> <span class="loc">(HD30.28)</span></li>

<li>Adams, Scott – <dfn>The Dilbert Principle</dfn> <span class="loc">(HD31)</span></li>

<li>Ehrenreich, Barbara – <dfn>Nickel and Dimed</dfn> <span class="loc">(HD4918)</span></li>

<li>Thiel, Peter – <dfn>Zero to One: Notes on Start-Ups, or How to Build the Future</dfn> <span class="loc">(HD62.5)</span></li>

<li>Montgomery, David – <dfn>Beyond Equality: Labor and the Radical Republicans 1862-1872</dfn> <span class="loc">(HD8076)</span></li>

<li>Caplan, Bryan – <dfn>The Myth of the Rational Voter: Why Democracies Choose Bad Policies</dfn> <span class="loc">(HD87)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bhagwati, Jagdish – <dfn>In Defense of Globalization</dfn> <span class="loc">(HF1359)</span></li>

<li>Krugman, Paul and Obstfield, Maurice – <dfn>International Economics</dfn> <span class="loc">(HF1359)</span></li>

<li>Lechner, Frank J. and Boli, John – <dfn>The Globalization Reader</dfn> <span class="loc">(HF1359)</span></li>

<li>Myrdal, Gunnar – <dfn>Beyond the Welfare State</dfn> <span class="loc">(HF1411)</span></li>

<li>Graeber, David – <dfn>Bullshit Jobs: A Theory</dfn> <span class="loc">(HF5549.5.J63)</span> <a href="https://notrelated.xyz/#02.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Soros, George – <dfn>In Defense of Open Society</dfn> <span class="loc">(HG172.S63)</span></li>

<li>Boortz, Neal and Linder, John – <dfn>The Fairtax Book: Saying Goodbye to the Income Tax and the IRS</dfn> <span class="loc">(HJ4652)</span></li>

<li>Stove, David – <dfn>Darwinian Fairytales</dfn> <span class="loc">(HM106)</span></li>

<li>O'Brien, Jodi – <dfn>The Production of Reality</dfn> <span class="loc">(HM1033)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Skin in the Game</dfn> <span class="loc">(HM1101)</span></li>

<li>Berne, Eric – <dfn>Games People Play</dfn> <span class="loc">(HM1106)</span></li>

<li>Pinker, Steven – <dfn>The Better Angels of Our Nature</dfn> <span class="loc">(HM1116)</span></li>

<li>Kropotkin, Peter – <dfn>Mutual Aid: A Factor of Evolution</dfn> <span class="loc">(HM131)</span></li>

<li>Diamond, Jared – <dfn>Guns, Germs and Steel</dfn> <span class="loc">(HM206)</span></li>

<li>Bork, Robert H. – <dfn>Slouching Towards Gomorrah: Modern Liberalism and American Decline</dfn> <span class="loc">(HN59.2)</span></li>

<li>Arnold, Matthew – <dfn>Culture and Anarchy</dfn> <span class="loc">(HN389)</span></li>

<li>Jones, E. Michael – <dfn>Libido Dominandi: Sexual Liberation and Political Control</dfn> <span class="loc">(HQ472.U6)</span></li>

<li>Eisler, Riane – <dfn>The Chalice and the Blade, Our History, Our Future</dfn> <span class="loc">(HQ1075)</span></li>

<li>Harris, Judith Rich – <dfn>The Nurture Assumption</dfn> <span class="loc">(HQ772)</span></li>

<li>Beuerlein, Mark – <dfn>The Dumbest Generation</dfn> <span class="loc">(HQ799.7)</span></li>

<li>Street, Oliver Day – <dfn>Symbolism of the Three Degrees</dfn> <span class="loc">(HS425)</span></li>

<li><dfn>Morals and Dogma of the Ancient and Accepted Scottish Rite of Freemasonry</dfn> <span class="loc">(HS767)</span></li>

<li><dfn>The 9/11 Commission Report: Final Report of the National Commission on Terrorist Attacks upon the United States</dfn> <span class="loc">(HV6432.7)</span></li>

<li>Engels, Frederick – <dfn>Socialism: Utopian and Scientific</dfn> <span class="loc">(HX276)</span></li>

<li>Hayek, F. A. – <dfn>The Intellectuals and Socialism</dfn> <span class="loc">(HX528)</span></li>

<li>More, Thomas – <dfn>Utopia</dfn> <span class="loc">(HX810.5)</span></li>

<li>Stringham, Edward P. – <dfn>Anarchy and the Law</dfn> <span class="loc">(HX833)</span></li>

<li>Schumpeter, Joseph Alois – <dfn>Capitalism, Socialism and Democracy</dfn> <span class="loc">(HX86)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bastiat, Frederic – <dfn>The Law</dfn> <span class="loc">(HX87)</span></li>

</ul>
<h2 id="j-k-political-science-and-law">J-K: Political Science and Law</h2>
<figure class="resright"><img src="/pix/archeofuturism.jpg"></figure>
<ul class="booklist">
<li>Faye, Guillaume – <dfn>Archeofuturism: European Visions of the Post-Catastrophic Age</dfn> <span class="loc">(JA84.F8)</span></li>

<li>Plato – <dfn>The Republic</dfn> <span class="loc">(JC71)</span></li>

<li>Machiavelli, Niccolò – <dfn>The Prince and Other Writings</dfn> <span class="loc">(JC143)</span></li>

<li>Hobbes, Thomas – <dfn>Leviathan</dfn> <span class="loc">(JC153)</span></li>

<li>Filmer, Robert – <dfn>Patriarcha, or, The Natural Power of Kings</dfn> <span class="loc">(JC153.F48)</span></li>

<li>Samons, Loren J. – <dfn>What's Wrong with Democracy?</dfn> <span class="loc">(JC421)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Mill, John Stewart – <dfn>On Liberty</dfn> <span class="loc">(JC585)</span></li>

<li>Reed, Lawrence W. – <dfn>Are We Good Enough for Liberty?</dfn> <span class="loc">(JC585)</span></li>

<li>Jeffery, – <dfn>People's War: New Light on the Struggle for South Africa</dfn> <span class="loc">(JQ1998.A4)</span></li>

<li>Beard, Charles – <dfn>An Economic Interpretation of the Constitution of the United States</dfn> <span class="loc">(JK146)</span></li>

<li>Smith, Bradley A. – <dfn>Unfree Speech: The Folly of Campaign Finance Reform</dfn> <span class="loc">(JK1991)</span></li>

<li>de Tocqueville, Alexis – <dfn>Democracy in America</dfn> <span class="loc">(JK216)</span></li>

<li>Brimelow, Peter – <dfn>Alien Nation: Common Sense about America's Immigration Disaster</dfn> <span class="loc">(JV6493)</span></li>

<li>Fukuyama, Francis – <dfn>America at the Crossroads: Democracy, Power and Neoconservative Legacy</dfn> <span class="loc">(JZ1480)</span></li>

<li>Silverglate, Harvey A. and French, David A. and Lukianoff, Greg – <dfn>FIRE's Guide to Free Speech on Campus</dfn> <span class="loc">(KF4123.5)</span></li>

<li>Bernstein, David E. – <dfn>You Can't Say That!</dfn> <span class="loc">(KF4749)</span></li>

</ul>
<h2 id="l-n-education-music-fine-arts">L-N: Education, Music, Fine Arts</h2>
<ul class="booklist">
<li>Bloom, Allan – <dfn>The Closing of the American Mind: How Higher Education Has Failed Democracy and Impoverished the Souls of Today's Students</dfn> <span class="loc">(LA227.3)</span></li>

<li>Russell, Bertrand – <dfn>Education and the Good Life</dfn> <span class="loc">(LB775)</span></li>

<li><dfn>Baptist Hymnal</dfn> <span class="loc">(M2122)</span></li>

<li>Towner, D. B., Lorenz, E. S. and Wilson, Ira B. – <dfn>Songs of Praise: A Collection of Gospel Songs for Men's Voices</dfn> <span class="loc">(M2198)</span></li>

<li>International Graphic Society – <dfn>The Arts of Mankind: Painting, Architecture, Music</dfn> <span class="loc">(N5302)</span></li>

<li>Barral i Altet, Xavier – <dfn>The Early Middle Ages: From Late Antiquity to A.D. 1000</dfn> <span class="loc">(NA350)</span></li>

<li>Churchill, Winston S. – <dfn>Painting as a Pastime: An instructive and inspiring invitation to the joy of painting</dfn> <span class="loc">(ND1142)</span></li>

<li>Cornelius, Maurits – <dfn>The Graphic Work of M.C. Escher</dfn> <span class="loc">(NE670.E75)</span></li>

</ul>
<h2 id="p-philology-linguistics">P: Philology, Linguistics</h2>
<figure class="resright"><img src="/pix/westernclassical.jpg" title="Good for learning some #Lindy linguistics"></figure>
<ul class="booklist">
<li>Smith, Luke – <dfn>External Possession and the Undisentanglability of Syntax and Semantics</dfn></li>

<li>Chomsky, Noam – <dfn>Language and Mind</dfn> <span class="loc">(P106)</span></li>

<li>Harris, Roy – <dfn>Language, Saussure and Wittgenstein, How to Play Games with Words</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>Words and Rules, the Ingredients of Language</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>The Stuff of Thought</dfn> <span class="loc">(P107)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: I Linguistic Theory: Foundations</dfn> <span class="loc">(P121)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: II Linguistics Theory: Extensions and Implications</dfn> <span class="loc">(P121)</span></li>

<li>Ohio State University – <dfn>Language Files 11</dfn> <span class="loc">(P121)</span></li>

<li>Chomsky, Noam – <dfn>The Logical Structure of Linguistic Theory</dfn> <span class="loc">(P158)</span></li>

<li>Falk, Yehuda N. – <dfn>Lexical-Functional Grammar, An Introduction to Parallel Constraint-Based Syntax</dfn> <span class="loc">(P158.25)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Chomsky's Minimalism</dfn> <span class="loc">(P158.28)</span></li>

<li>Gutiérrez, Bravo and Arellanes Arellanes, Francisco and Peón Herrero, Mario Ernesto Chávez – <dfn>Nuevos estudios de Teoría de la Optimalidad</dfn> <span class="loc">(P158.42)</span></li>

<li>Richards, Norvin – <dfn>Contiguity Theory</dfn> <span class="loc">(P224.R43)</span></li>

<li>Bresnan, Joan and Asudeh, Ash and Tolivonen, Ida and Wechsler, Stephen – <dfn>Lexical-Functional Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Chomsky, Noam – <dfn>Aspects of the Theory of Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Freidin, Robert – <dfn>Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Saeed, John I. – <dfn>Semantics</dfn> <span class="loc">(P325)</span></li>

<li>Dalby, Andrew – <dfn>Dictionary of Languages, the Definitive Reference to More than 400 Languages</dfn> <span class="loc">(P371)</span></li>

<li>Allan, Keith – <dfn>The Western Classical Tradition in Linguistics</dfn> <span class="loc">(P61)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Western Linguistics: An Historical Introduction</dfn> <span class="loc">(P61)</span></li>

<li>Klein, Jared – <dfn>An Indo-European Chrestomathy</dfn></li>

<li>Watkins, Calvert – <dfn>The American Heritage Dictionary of Indo-European Roots</dfn> <span class="loc">(P615)</span></li>

<li>Sampson, Geoff – <dfn>Schools of Linguistics</dfn> <span class="loc">(P77)</span></li>

<li>Harris, Randy Allen – <dfn>The Linguistics Wars</dfn> <span class="loc">(P85.C47)</span></li>

<li>Cutting, Joan – <dfn>Pragmatics and Discourse</dfn> <span class="loc">(P99.4.P72)</span></li>

</ul>
<h2 id="pa-greek-and-latin-language-and-literature">PA: Greek and Latin language and Literature</h2>
<figure class="resright"><img src="/pix/hughes.jpg" title="These are actually pretty good and readable English translations."></figure>
<ul class="booklist">
<li>Morrison, Clinton and Barnes, David H. – <dfn>New Testament Word Lists</dfn> <span class="loc">(PA881)</span></li>

<li>Magoffin, Ralph van Deman and Henry, Margaret Young – <dfn>Latin First Year</dfn> <span class="loc">(PA2087)</span></li>

<li>Wheelock, Frederic M. – <dfn>Latin, an Introductory Course Based on Ancient Authors</dfn> <span class="loc">(PA2087.5)</span></li>

<li>Orberg, Hans H – <dfn>Roma Aeterna</dfn> <span class="loc">(PA2094.5)</span></li>

<li>Orberg, Hans H – <dfn>Colloquium Personarum</dfn> <span class="loc">(PA2095)</span></li>

<li>Orberg, Hans H – <dfn>Lingua Latina</dfn> <span class="loc">(PA2095)</span></li>

<li>Simpson, D. P. – <dfn>Cassell's Latin Dictionary</dfn> <span class="loc">(PA2365.E5)</span></li>

<li>Landis, Paul – <dfn>Four Famous Greek Plays</dfn> <span class="loc">(PA3626.A2)</span></li>

<li>Aeschylus – <dfn>The Oresteia</dfn> <span class="loc">(PA3827.A7)</span></li>

<li>Apollonius of Rhodes – <dfn>Jason and the Argonauts (Argonautica)</dfn> <span class="loc">(PA3872)</span></li>

<li>Euripides – <dfn>Three Plays of Euripides: Alcestis, Medea, the Bacchae</dfn> <span class="loc">(PA3975)</span></li>

<li>Euripides – <dfn>Alcestis and Other Plays</dfn> <span class="loc">(PA3975.A5)</span></li>

<li>Corpus Hermeticum – <dfn>Hermes Trismegistus</dfn> <span class="loc">(PA3998)</span></li>

<li>Homer – <dfn>The Iliad</dfn> <span class="loc">(PA4025.A2)</span></li>

<li>Homer – <dfn>The Odyssey</dfn> <span class="loc">(PA4025.A5)</span></li>

<li>Sophocles – <dfn>The Theban Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>The Complete Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>Electra and Other Plays</dfn> <span class="loc">(PA4414.A2)</span></li>

<li>Feyerabend, Karl – <dfn>Greek-English Dictionary</dfn> <span class="loc">(PA445.E5)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Liddell, H. G. and Scott – <dfn>Greek-English Lexicon</dfn> <span class="loc">(PA445.E5)</span></li>

<li>Juvenal – <dfn>The Sixteen Satires</dfn> <span class="loc">(PA6447.E5)</span></li>

<li>Lucretius – <dfn>On the Nature of Things</dfn> <span class="loc">(PA6483.E5)</span></li>

<li>Hughes, Ted – <dfn>Tales from Ovid: Twenty-Four Passages from the 'Metamorphoses' by Ovid</dfn> <span class="loc">(PA6522)</span></li>

<li>Petronius – <dfn>the Satyricon and the Fragments</dfn> <span class="loc">(PA6558.E5)</span></li>

<li>Pliny the Younger – <dfn>Pliny: A Self-Portrait in Letters</dfn> <span class="loc">(PA6639.E5)</span></li>

<li>Virgil – <dfn>Aeneid</dfn> <span class="loc">(PA6807.A5)</span></li>

<li>Virgil – <dfn>The Pastoral Poems</dfn> <span class="loc">(PA6807.B7)</span></li>

</ul>
<h2 id="pc-romance-languages">PC: Romance Languages</h2>
<figure class="resright"><img src="/pix/lathrop.jpg" title="Lathrop's Course on Historical Spanish"></figure>
<ul class="booklist">
<li>Decker, Henry W. and Bernhard, Francoise – <dfn>Modern French</dfn> <span class="loc">(PC211)</span></li>

<li>Azevedo, Milton M. – <dfn>Introducción a la Lingüística Española</dfn> <span class="loc">(PC4073)</span></li>

<li>Lathrop, T. A. and Gutiérrex Cuadrado, Juan – <dfn>Curso de gramática histórica española</dfn> <span class="loc">(PC4101)</span></li>

<li>Moreno, Oscar – <dfn>Gramática avanzada del español</dfn> <span class="loc">(PC4129.E5)</span></li>

<li>Cash, Annette G. and Murray, James C. – <dfn>Teoría y técnicas de traduccón: primeras etapas</dfn> <span class="loc">(PC4498)</span></li>

<li>Gili Gaya, Samuel – <dfn>Vox: Diccionario abreviado de la lengua española</dfn> <span class="loc">(PC4625)</span></li>

</ul>
<h2 id="pd-pf-germanic-languages-and-literatures">PD-PF: Germanic Languages and Literatures</h2>
<ul class="booklist">
<li>Lambdin, Thomas O. – <dfn>An Introduction to the Gothic Language</dfn> <span class="loc">(PD1123)</span></li>

<li>Hugo – <dfn>Swedish Phrase Book</dfn> <span class="loc">(PD5121)</span></li>

<li>Warriner, John E. and Whitten, Mary E. and Friggith, Francis J. – <dfn>Warriner's English Grammar and Composition</dfn> <span class="loc">(PE1112)</span></li>

<li>Elson, William H. and Keck, Christine – <dfn>Elson Grammar School Literature Book Two</dfn> <span class="loc">(PE1121)</span></li>

<li>Mitchell, Brucew and Robinson, Fred C. – <dfn>A Guide to Old English</dfn> <span class="loc">(PE131)</span></li>

<li>Evans, Jonathan – <dfn>An Introduction to Old English</dfn> <span class="loc">(PE135)</span></li>

<li>Bright, James W. – <dfn>Bright's Anglo-Saxon Reader</dfn> <span class="loc">(PE137)</span></li>

<li>Gottschalk, Katherine and Keith Hjortshoj – <dfn>The Elements of Teaching Writing</dfn> <span class="loc">(PE1404)</span></li>

<li>Forsyth, Mark – <dfn>The Elements of Eloquence</dfn> <span class="loc">(PE1421)</span></li>

<li>McCloskey, Deirdre N. – <dfn>Economical Writing</dfn> <span class="loc">(PE1479.E35)</span></li>

<li>Sharp, Stanley Louis and Strothmann, Friedrich Wilhelm – <dfn>German Reading Grammar</dfn> <span class="loc">(PF3111)</span></li>

<li>Morgan, Baynard Quincy and Strothmann, Friedrich Wilhelm – <dfn>Reading German</dfn> <span class="loc">(PF3117)</span></li>

<li>Berlitz – <dfn>Berlitz Self-Teaching German</dfn> <span class="loc">(PF3121)</span></li>

</ul>
<h2 id="pj-pl-oriental-indo-iranian-east-asian-and-oceanian-languages">PJ-PL: Oriental, Indo-Iranian, East-Asian and Oceanian Languages</h2>
<figure class="resright"><img src="/pix/sastry.jpg" title="Sanskrit in the Development of World Thought"></figure>
<ul class="booklist">
<li>Anonymous – <dfn>The Epic of Gilgamesh</dfn> <span class="loc">(PJ3771.G5)</span></li>

<li>Wightwick, Jane and Gaafar, Mahmoud – <dfn>Mastering Arabic</dfn> <span class="loc">(PJ6307)</span></li>

<li>Luxenberg, Christoph – <dfn>The Syro-Aramaic Reading of the Koran: A Contribution to Decoding the Language of the Koran</dfn> <span class="loc">(PJ6696)</span></li>

<li>Burnell, Arthur Coke – <dfn>On the Aindra school of Sanskrit grammarians, their place in the Sanskrit and subordinate literatures</dfn> <span class="loc">(PK407)</span></li>

<li>Sastry, Vempaty Kutumba – <dfn>Sanskrit and Development of World Thought</dfn> <span class="loc">(PK423)</span></li>

<li>Elwell-Sutton, L. P. – <dfn>Elementary Persian Grammar</dfn> <span class="loc">(PK6235)</span></li>

<li>Whitney, William Dwight – <dfn>A Sanskrit Grammar: Including Both the Classical Language, and the Older Dialects, of the Veda and Brahmana</dfn> <span class="loc">(PK663)</span></li>

<li>Sutherland, Goldman – <dfn>Devavanipravesika</dfn> <span class="loc">(PK666)</span></li>

<li>Whitney, William Dwight – <dfn>The Roots, Verb-Forms, And Primary Derivatives of the Sankstrit Language: A Supplement to his Sanskrit Grammar</dfn> <span class="loc">(PK745)</span></li>

<li>DeFrancis, John – <dfn>Intermediate Chinese</dfn> <span class="loc">(PL11117)</span></li>

<li>DeFrancis, John – <dfn>Advanced Chinese</dfn> <span class="loc">(PL1121.C5)</span></li>

<li>Defense Language Institute – <dfn>Chinese: Basic Course</dfn> <span class="loc">(PL1125)</span></li>

<li>Seligman, Scott D. – <dfn>Mandarin Chinese at a Glance</dfn> <span class="loc">(PL1125.E6)</span></li>

<li>DeFrancis, John – <dfn>The Chinese Language, Fact and Fantasy</dfn> <span class="loc">(PL1171)</span></li>

<li><dfn>Oxford Chinese Dictionary</dfn> <span class="loc">(PL1455)</span></li>

<li>Waley, Arthur – <dfn>Translations from the Chinese</dfn> <span class="loc">(PL3277.E3)</span></li>

<li>Burlington, Scott – <dfn>Instant Hawaiian</dfn> <span class="loc">(PL6445)</span></li>

<li>Pukui, Mary Kawena and Elbert, Samuel H. and Mookini, Esther T. – <dfn>The Pocket Hawaiian Dictionary</dfn> <span class="loc">(PL6446)</span></li>

</ul>
<h2 id="pn-general-literature">PN: General Literature</h2>
<ul class="booklist">
<li>Butterworth, Hezekiah – <dfn>The Story of America</dfn> <span class="loc">(PN1009.A1)</span></li>

<li>Kaplar, Richard T. and Patrick D. Maines – <dfn>The Government Factor: Undermining Journalistic Ethics in the Information Age</dfn> <span class="loc">(PN4888.E8)</span></li>

<li>Schwarz, Leo W. – <dfn>Feast of Leviathan: Tales of Adventure, Faith and Love from Jewish Literature</dfn> <span class="loc">(PN6071.J5)</span></li>

<li><dfn>Treasury of Familiar Quotations</dfn> <span class="loc">(PN6081)</span></li>

<li><dfn>Reader's Digest Treasury of American Humor</dfn> <span class="loc">(PN6162)</span></li>

<li>The Onion – <dfn>Dispatches from the Tenth Circle</dfn> <span class="loc">(PN6165)</span></li>

<li>The Onion – <dfn>Our Dumb World</dfn> <span class="loc">(PN6231.A74)</span></li>

<li>Raymond, Eric S. – <dfn>The New Hacker's Dictionary</dfn> <span class="loc">(PN6231.E4)</span></li>

<li>The Onion – <dfn>Our Dumb Century</dfn> <span class="loc">(PN6231.N6)</span></li>

<li>Gómez Dávila, Nicolás – <dfn>Escolios a un texto implícito</dfn> <span class="loc">(PN6275)</span></li>

<li>Brown, Jeffrey – <dfn>Darth Vader and Son</dfn> <span class="loc">(PN6727.B7575)</span></li>

<li>Watterson, Bill – <dfn>Calvin and Hobbes: Scientific Progress Goes 'Boink'</dfn> <span class="loc">(PN6728.C34)</span></li>

<li>Lewis, C. S. – <dfn>The Discarded Image: An Introduction to Medieval and Renaissance Literature</dfn> <span class="loc">(PN671)</span></li>

</ul>
<h2 id="pq-romance-literature">PQ: Romance Literature</h2>
<figure class="resright"><img src="/pix/inferno.jpg"></figure>
<ul class="booklist">
<li>de Montaigne, Michel – <dfn>Montaigne Selected Essays</dfn> <span class="loc">(PQ1642.E6)</span></li>

<li>Morlière, Jean-Baptiste – <dfn>Tartuffe and Other Plays</dfn> <span class="loc">(PQ1842)</span></li>

<li>De Saint-Exupéry – <dfn>Sazadeo Qickek</dfn> <span class="loc">(PQ2637.A274)</span></li>

<li>Alighieri, Dante – <dfn>The Divine Comedy</dfn> <span class="loc">(PQ4315)</span></li>

<li>Alighieri, Dante – <dfn>The Inferno</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Alighieri, Dante – <dfn>I: Hell (Sayers translation)</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Eco, Umberto – <dfn>Foucault's Pendulum</dfn> <span class="loc">(PQ4864.C6)</span></li>

<li>De la Vega, Garcilaso – <dfn>Poesías</dfn> <span class="loc">(PQ6391)</span></li>

<li>Garcia Lorca, Federico – <dfn>Rosita la soltera</dfn> <span class="loc">(PQ6613.A763)</span></li>

<li>Pérez-Reverte, Arturo – <dfn>La tabla de Flandés</dfn> <span class="loc">(PQ6666.E765)</span></li>

<li>Rulfo, Juan &amp;ndash; Pedro – <dfn>y El Llano en llamas</dfn> <span class="loc">(PQ7297.R89)</span></li>

</ul>
<h2 id="pr-english-literature">PR: English Literature</h2>
<ul class="booklist">
<li>Clark, Thomas Curtis and Gillespie, Esther A. – <dfn>1000 Quotable Poems</dfn> <span class="loc">(PR1175)</span></li>

<li><dfn>Beowulf</dfn> <span class="loc">(PR1583)</span></li>

<li>Chaucer, Geoffrey – <dfn>Chaucer's Major Poetry</dfn> <span class="loc">(PR1851)</span></li>

<li>Chaucer, Geoffrey – <dfn>The Canterbury Tales</dfn> <span class="loc">(PR1870.A1)</span></li>

<li>Collis, Louise – <dfn>Memoirs of a Medieval Woman</dfn> <span class="loc">(PR2007)</span></li>

<li>Malory, Thomas – <dfn>Le Morte d'Arthur</dfn> <span class="loc">(PR2041)</span></li>

<li>Craig, W. J. – <dfn>The Complete Works of William Shakespeare</dfn> <span class="loc">(PR2753.C8)</span></li>

<li>Shakespeare, William – <dfn>Hamlet (2 copies)</dfn> <span class="loc">(PR2801.A2)</span></li>

<li>Shakespeare, William – <dfn>Macbeth</dfn> <span class="loc">(PR2823.A2)</span></li>

<li>Shakespeare, William – <dfn>A Midsummer Night's Dream</dfn> <span class="loc">(PR2827.A2)</span></li>

<li>Shakespeare, William – <dfn>The Merchant of Venice</dfn> <span class="loc">(PR2825.A2)</span></li>

<li>Shakespeare, William – <dfn>The Sonnets</dfn> <span class="loc">(PR2848.A2)</span></li>

<li>Crystal, David – <dfn>The Oxford Dictionary of Original Shakespearean Pronunciation</dfn> <span class="loc">(PR2892)</span></li>

<li>Bunyan, John – <dfn>Pilgrim's Progress</dfn> <span class="loc">(PR3330)</span></li>

<li>Milton, John – <dfn>Paradise Lost and Other Poems</dfn> <span class="loc">(PR3560)</span></li>

<li>Coleridge, Samuel Taylor – <dfn>The Rime of the Ancient Mariner</dfn> <span class="loc">(PR4479)</span></li>

<li>Dickens, Charles – <dfn>Great Expectations</dfn> <span class="loc">(PR4560)</span></li>

<li>Shaw, George Bernard – <dfn>Pygmalion</dfn> <span class="loc">(PR5363)</span></li>

<li>Stevenson, Robert Louis – <dfn>The Black Arrow</dfn> <span class="loc">(PR5484)</span></li>

<li>Stevenson, Robert Louis – <dfn>New Arabian Nights</dfn> <span class="loc">(PR5484)</span></li>

<li>Wells, H. G. – <dfn>The Island of Dr. Moreau</dfn> <span class="loc">(PR5774)</span></li>

<li>Wilde, Oscar – <dfn>The Importance of Being Earnest</dfn> <span class="loc">(PR5818)</span></li>

<li>Christie, Agatha – <dfn>Death on the Nile</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Christie, Agatha – <dfn>The Nursery Rhyme Murders</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Golding, William – <dfn>Lord of the Flies</dfn> <span class="loc">(PR6013.O35)</span></li>

<li>Lewis, C. S. – <dfn>The Lion, the Witch and the Wardrobe</dfn> <span class="loc">(PR6023.E926)</span></li>

<li>Huxley, Aldous – <dfn>Brave New World</dfn> <span class="loc">(PR6015.U9)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Lord of the Rings, One-Volume Edition</dfn> <span class="loc">(PR6039.O32)</span></li>

<li>White, T. H. – <dfn>The Once and Future King</dfn> <span class="loc">(PR6045.H2)</span></li>

<li>Adams, Douglas – <dfn>Life, the Universe and Everything</dfn> <span class="loc">(PR6051.D3352)</span></li>

<li>Erickson, Paul – <dfn>Doctor Who: The Ark</dfn> <span class="loc">(PR6052.R449)</span></li>

<li>Burgess, Anthony – <dfn>A Clockwork Orange</dfn> <span class="loc">(PR6052.U638)</span></li>

<li>Grimwade, Peter – <dfn>Doctor Who: Planet of Fire</dfn> <span class="loc">(PR6057.R545)</span></li>

<li>Halleck, Reuben Post – <dfn>History of English Literature</dfn> <span class="loc">(PR85)</span></li>

<li>Achebe, Chinua – <dfn>Things Fall Apart</dfn> <span class="loc">(PR9387.9.A3)</span></li>

</ul>
<h2 id="ps-american-literature">PS: American Literature</h2>
<figure class="resright"><img src="/pix/lovecraft.jpg"></figure>
<ul class="booklist">
<li>Twain, Mark – <dfn>A Connecticut Yankee in King Arthur's Court</dfn> <span class="loc">(PS1308)</span></li>

<li>Hawthorne, Nathaniel – <dfn>The Scarlet Letter</dfn> <span class="loc">(PS1868)</span></li>

<li>Poe, Edgar Allan – <dfn>Edgar Allan Poe Reader</dfn> <span class="loc">(PS2603)</span></li>

<li>Poe, Edgar Allen – <dfn>Tales of Terror and Detection</dfn> <span class="loc">(PS2612)</span></li>

<li>Thoreau, Henry David – <dfn>Walden</dfn> <span class="loc">(PS3048)</span></li>

<li>Wallace, Lew – <dfn>Ben Hur</dfn> <span class="loc">(PS3134)</span></li>

<li>Faulkner, William – <dfn>Light in August</dfn> <span class="loc">(PS3511.A86)</span></li>

<li>Fitzgerald, F. Scott – <dfn>The Great Gatsby</dfn> <span class="loc">(PS3511.I9)</span></li>

<li>Heinlein, Robert A. – <dfn>For Us, the Living</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Heinlein, Robert A. – <dfn>The Moon is a Harsh Mistress</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Lovecraft, H. P. – <dfn>Great Tales of Horror</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Case of Charles Dexter Ward</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Doom That Came to Sarnath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Dream Quest of Unknown Kadath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Tomb</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Rodgers, Marion Elizabeth – <dfn>Mencken &amp; Sara</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Mencken, H. L. – <dfn>The Vintage Mencken</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Rand, Ayn – <dfn>Atlas Shugged</dfn> <span class="loc">(PS3535.A547)</span></li>

<li>Skinner, B. F. – <dfn>Walden Two</dfn> <span class="loc">(PS3537.K527)</span></li>

<li>Smith, Clark Ashton – <dfn>Hyperborea</dfn> <span class="loc">(PS3537.M335)</span></li>

<li>Bear, Greg – <dfn>Darwin's Radio</dfn> <span class="loc">(PS3552.E157)</span></li>

<li>Card, Orson Scott – <dfn>Ender's Game</dfn> <span class="loc">(PS3553.A655)</span></li>

<li>Crichton, Michael – <dfn>Congo</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Jurassic Park</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Timeline</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Dick, Philip K. – <dfn>Dr. Bloodmoney</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Dick, Philip K. – <dfn>Flow My Tears, The Policeman Said</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Herbert, Frank – <dfn>Dune</dfn> <span class="loc">(PS3558.E63)</span></li>

<li>Jordan, Robert – <dfn>The Eye of the World</dfn> <span class="loc">(PS3560.O7617)</span></li>

<li>King, Stephen – <dfn>The Bazaar of Bad Dreams</dfn> <span class="loc">(PS3561.I483)</span></li>

<li>Myers, Bill – <dfn>Blood of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Fire of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Threshold</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Quinn, Daniel – <dfn>Ishmael: An Adventure of the Mind and Spirit</dfn> <span class="loc">(PS3567.U338)</span></li>

<li>Pearl, Matthew – <dfn>The Dante Club</dfn> <span class="loc">(PS3616.E25)</span></li>

<li>Asimov, Isaac – <dfn>Before the Golden Age: A Science Fiction Anthology of the 1930's</dfn> <span class="loc">(PS648.S3)</span></li>

<li>Saramago, José – <dfn>Todos los nombres</dfn> <span class="loc">(PS9281.A66)</span></li>

</ul>
<h2 id="pq-pz-other-literature">PQ-PZ: Other Literature</h2>
<figure class="resright"><img src="/pix/edda.jpg"></figure>
<ul class="booklist">
<li>Voltaire – <dfn>Candide, Zadig and selected stories</dfn> <span class="loc">(PQ2081.E5)</span></li>

<li>Hesse, Hermann – <dfn>Siddhartha</dfn> <span class="loc">(PT2617.E85)</span></li>

<li>Hesse, Hermann – <dfn>The Glass Bead Game</dfn> <span class="loc">(PT2617.E85 G513)</span></li>

<li>Sturluson, Snorri – <dfn>Poetic Edda</dfn> <span class="loc">(PT7235)</span></li>

<li>Sturluson, Snorri – <dfn>Prose Edda</dfn> <span class="loc">(PT7313.E5)</span></li>

<li>Borges, Jorge Luis – <dfn>Ficciones</dfn> <span class="loc">(PW7797.B635)</span></li>

<li>Connor, Ralph – <dfn>Black Rock: a Tale of the Selkirks</dfn> <span class="loc">(PZ3.G654)</span></li>

<li>Roberts, James Hall – <dfn>The Q Document</dfn> <span class="loc">(PZ4.D913)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Hobbit</dfn> <span class="loc">(PZ7.T5744)</span></li>

<li>Wilder, Laura Ingalls – <dfn>Little House (entire series)</dfn> <span class="loc">(PZ7.W6461)</span></li>

<li>Jacobs, Joseph – <dfn>Favorite Celtic Fairy Tales</dfn> <span class="loc">(PZ8)</span></li>

<li>Baum, L. Frank – <dfn>The Wizard of Oz</dfn> <span class="loc">(PZ8.B327)</span></li>

<li><dfn>The Brothers Grimm Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

<li><dfn>The Complete Grimm's Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

</ul>
<h2 id="qa-general-science">QA: General Science</h2>
<figure class="resright"><a href="https://www.youtube.com/watch?v=hVxvLd6cF0k"><img src="/pix/againstmethod.jpg"></a></figure>
<ul class="booklist">
<li>de Santillanna, Giorgio – <dfn>The Origins of Scientific Thought: from Anazimander to Proclus, 600 B.C. to 300 A.D.</dfn> <span class="loc">(Q125)</span></li>

<li>Gardner, Martin – <dfn>Great Essays in Science</dfn> <span class="loc">(Q171)</span></li>

<li>Kuhn, Thomas – <dfn>The Structure of Scientific Revolutions</dfn> <span class="loc">(Q175)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Wiener, Norbert – <dfn>The Human Use of Human Beings</dfn> <span class="loc">(Q175)</span></li>

<li>Feyerabend, Paul – <dfn>Against Method </dfn> <span class="loc">(Q175)</span></li>

<li>Motterlini, Matteo – <dfn>For and Against Method: Including Lakatos's Lectures on Scientific Method and the Lakatos-Feyerabend Correspondence </dfn> <span class="loc">(Q175.3)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Antifragile</dfn> <span class="loc">(Q375)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>The Black Swan</dfn> <span class="loc">(Q375)</span></li>

</ul>
<h2 id="qa-mathematics">QA: Mathematics</h2>
<ul class="booklist">
<li>Sawyer, W. W. – <dfn>Mathematician's Delight</dfn> <span class="loc">(QA37)</span></li>

<li>Birns, Peter and Brown, Patrick and Muster, John C. C. – <dfn>Unix for People</dfn> <span class="loc">(QA76.6)</span></li>

<li>Raymond, Eric S. – <dfn>The Cathedral and the Bazaar</dfn> <span class="loc">(QA76.76.O63)</span></li>

<li>Bellos, Alex – <dfn>Here's Looking at Euclid</dfn> <span class="loc">(QA141.15)</span></li>

<li>Nyberg, Joseph A. – <dfn>Second Course in Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Wentworth, G. A. – <dfn>New School Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Hart, William – <dfn>College Algebra</dfn> <span class="loc">(QA154)</span></li>

<li>Lial, Margaret L. and Miller, Charles D. – <dfn>Algebra and Trigonometry</dfn> <span class="loc">(QA154.2)</span></li>

<li>Sokal, Alan and Bricmont, Jean – <dfn>Fashionable Nonsense: Postmodern Intellectuals' Abuse of Science</dfn> <span class="loc">(QA175)</span></li>

<li>Neugebauer, Otto – <dfn>The Exact Sciences in Antiquity</dfn> <span class="loc">(QA22)</span></li>

<li>Bharati Krsna Thirthaji Maharaja – <dfn>Vedic Mathematics</dfn> <span class="loc">(QA27.I4)</span></li>

<li>Christian, Robert R. – <dfn>Introduction to Logic and Sets</dfn> <span class="loc">(QA248)</span></li>

<li>Davis, Morton D. – <dfn>Game Theory: A Nontechnical Introduction</dfn> <span class="loc">(QA269)</span></li>

<li>Friedman, Avner – <dfn>Differential Games</dfn> <span class="loc">(QA272)</span></li>

<li>Takahashi, Shin – <dfn>The Manga Guide to Statistics</dfn> <span class="loc">(QA276)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 1-10</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 10-15 and Appendices</dfn> <span class="loc">(QA303)</span></li>

<li>Smith, Edward S. and Salkover, Meyer and Justive, Howard K. – <dfn>Unified Calculus</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny – <dfn>Calculus with Analytic Geometry</dfn> <span class="loc">(QA33)</span></li>

<li>Sperling, Abraham and Stuart, Monroe – <dfn>Mathematics (Made Simple Self-Teaching Library)</dfn> <span class="loc">(QA39.2)</span></li>

<li>Horblit, Marcus and Nielson, Kaj L. – <dfn>Problems in Plane Geometry with Solutions</dfn> <span class="loc">(QA459)</span></li>

<li>Shively, Levi S. – <dfn>Modern Geometry</dfn> <span class="loc">(QA473)</span></li>

<li>Nelson, Alfred L. and Folley, Karl W. – <dfn>Plane and Spherical Trigonometry</dfn> <span class="loc">(QA531.N45)</span></li>

<li>Love, Clyde E. – <dfn>Analytic Geometry</dfn> <span class="loc">(QA551)</span></li>

<li>Hutton, Graham – <dfn>Programming in Haskell</dfn> <span class="loc">(QA76.62)</span></li>

<li>Kernighan, Brian W. and Ritchie, Dennis M. – <dfn>The C Programming Language</dfn> <span class="loc">(QA76.73.C15)</span></li>

<li>Barski, Conrad – <dfn>Land of Lisp</dfn> <span class="loc">(QA76.76.C672)</span></li>

<li>Hofstadter, Douglas – <dfn>Gödel, Escher, Bach</dfn> <span class="loc">(QA9.8)</span></li>

<li>Emmet, E. R. – <dfn>Brain Puzzler's Delight</dfn> <span class="loc">(QA95)</span></li>

<li>Emmet, E. R. – <dfn>Puzzles for Pleasure</dfn> <span class="loc">(QA95)</span></li>

<li>Gardner, Martin – <dfn>aha! Gotcha, Paradoxes to puzzle and delight</dfn> <span class="loc">(QA95)</span></li>

<li>Heafford, Philip – <dfn>The Math Entertainer</dfn> <span class="loc">(QA95)</span></li>

</ul>
<h2 id="qb-qr-other-sciences">QB-QR: Other Sciences</h2>
<ul class="booklist">
<li>Hawking, Stephen W. – <dfn>A Brief History of Time</dfn> <span class="loc">(QB981)</span></li>

<li>Lerner, Eric – <dfn>The Big Bang Never Happened</dfn> <span class="loc">(QB991.B54)</span></li>

<li>McEvoy, J. P. and Zarate, Oscar – <dfn>Quantum Theory, A Graphic Guide</dfn> <span class="loc">(QC173.98)</span></li>

<li>Booker, Christopher – <dfn>The Real Global Warming Disaster</dfn> <span class="loc">(QC981.8.G56)</span></li>

<li>Greenburg, Arthur – <dfn>From Alchemy to Chemistry in Picture and Story</dfn> <span class="loc">(QD11)</span></li>

<li>Valentine, Basil – <dfn>Of Natural and Supernatural Things: Also, of the First Tincture, Root, and Spirit of Metals and Minerals: How the Same are Conceived, Generated, Brought Forth, Changed and Augmented</dfn> <span class="loc">(QD25)</span></li>

<li>Watson, James – <dfn>The Double Helix</dfn> <span class="loc">(QH31.D434)</span></li>

<li>Fodor, Jerry and Piattelli Palmarini, Massimo – <dfn>What Darwin Got Wrong</dfn> <span class="loc">(QH375)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Kadans, Joseph M. – <dfn>Modern Encyclopedia of Herbs</dfn> <span class="loc">(QK99.A1)</span></li>

<li>McFarland, J. Horace – <dfn>Getting Acquainted with Trees</dfn> <span class="loc">(QK482)</span></li>

<li>Kurzweil, Ray – <dfn>The Singularity is Near</dfn> <span class="loc">(QP376)</span></li>

<li>Kandel, Eric R. and Schwartz, James H. and Jessell, Thomas M. – <dfn>Essentials of Neural Science and Behavior</dfn> <span class="loc">(QP355.2)</span></li>

</ul>
<h2 id="r-medicine">R: Medicine</h2>
<ul class="booklist">
<li>FC&amp;A – <dfn>The Folk Remedy Encyclopedia: Olive Oil, Vinegar, Honey and 1,001 Other Home Remedies</dfn> <span class="loc">(R733)</span></li>

<li><dfn>Better Homes and Gardens Family Medical Guide</dfn> <span class="loc">(RC81.A2)</span></li>

<li><dfn>The Encyclopedia of Common Diseases</dfn> <span class="loc">(RC81.A2)</span></li>

</ul>
<h2 id="s-t-agriculture-and-technology">S-T: Agriculture and Technology</h2>
<figure class="resright"><a href="https://www.youtube.com/watch?v=YRNKjQg6y-c"><img src="/pix/salatin.jpg"></a></figure>
<ul class="booklist">
<li>Mollison, Bill – <dfn>Introduction to Permaculture</dfn> <span class="loc">(S494.5.P47)</span></li>

<li>Salatin, Joel – <dfn>Everything I Want to Do Is Illegal</dfn> <span class="loc">(S605.5)</span></li>

<li>David the Good – <dfn>Totally Crazy Easy Florida Gardening</dfn></li>

<li>Seymour, John – <dfn>The Complete Book of Self-Sufficiency</dfn> <span class="loc">(S605.5)</span></li>

<li>Cobleigh, Rolfe – <dfn>Handy Farm Devices and How to Make Them (2 copies)</dfn> <span class="loc">(S676)</span></li>

<li>Seymour, John – <dfn>Gardener's Delight</dfn> <span class="loc">(SB322)</span></li>

<li>Seymour, John – <dfn>The Self-Sufficient Gardener</dfn> <span class="loc">(SB324.3)</span></li>

<li>Haring, Elda – <dfn>The Seedling Handbook</dfn> <span class="loc">(SB405)</span></li>

<li>Abraham, George – <dfn>The Green Thumb Garden Handbook</dfn> <span class="loc">(SB453)</span></li>

<li><dfn>Reader's Digest Illustrated Guide to Gardening</dfn> <span class="loc">(SB453)</span></li>

<li>Kaczynski, Theodore John – <dfn>Technological Slavery</dfn> <span class="loc">(T14.5)</span></li>

<li>Kaczynski, Theodore John – <dfn>Anti-Tech Revolution: Why and How</dfn> <span class="loc">(T14.5)</span></li>

<li>Macaulay, David and Ardleym Neil – <dfn>The Way Things Work</dfn> <span class="loc">(T47)</span></li>

<li>Slater, Robert and Li, Ling and Li, Wen – <dfn>Portraits in Silicon</dfn> <span class="loc">(TK7885.2)</span></li>

<li>Bishop, Michael and Zimmerman, Holmes – <dfn>Detailing Cars and Trucks</dfn> <span class="loc">(TL152)</span></li>

<li>Allaby, Michael and Lovelock, James – <dfn>The Greening of Mars</dfn> <span class="loc">(TL795.7)</span></li>

<li>Abbey, Barbara – <dfn>The Complete Book of Knitting</dfn> <span class="loc">(TT820)</span></li>

<li>Bishop, Jack – <dfn>Vegetables Every Day</dfn> <span class="loc">(TX801)</span></li>

<li>Lo, Kenneth – <dfn>Chinese Regional Cooking</dfn> <span class="loc">(TX724.5.C5)</span></li>

</ul>
<li>Mollison, Bill – <dfn>Introduction to Permaculture</dfn> <span class="loc">(S494.5.P47)</span></li>
<li>Salatin, Joel – <dfn>Everything I Want to Do Is Illegal</dfn> <span class="loc">(S605.5)</span></li>
<li>David the Good – <dfn>Totally Crazy Easy Florida Gardening</dfn></li>
<li>Seymour, John – <dfn>The Complete Book of Self-Sufficiency</dfn> <span class="loc">(S605.5)</span></li>
<li>Cobleigh, Rolfe – <dfn>Handy Farm Devices and How to Make Them (2 copies)</dfn> <span class="loc">(S676)</span></li>
<li>Seymour, John – <dfn>Gardener's Delight</dfn> <span class="loc">(SB322)</span></li>
<li>Seymour, John – <dfn>The Self-Sufficient Gardener</dfn> <span class="loc">(SB324.3)</span></li>
<li>Haring, Elda – <dfn>The Seedling Handbook</dfn> <span class="loc">(SB405)</span></li>
<li>Abraham, George – <dfn>The Green Thumb Garden Handbook</dfn> <span class="loc">(SB453)</span></li>
<li><dfn>Reader's Digest Illustrated Guide to Gardening</dfn> <span class="loc">(SB453)</span></li>
<li>Kaczynski, Theodore John – <dfn>Technological Slavery</dfn> <span class="loc">(T14.5)</span></li>
<li>Kaczynski, Theodore John – <dfn>Anti-Tech Revolution: Why and How</dfn> <span class="loc">(T14.5)</span></li>
<li>Macaulay, David and Ardleym Neil – <dfn>The Way Things Work</dfn> <span class="loc">(T47)</span></li>
<li>Slater, Robert and Li, Ling and Li, Wen – <dfn>Portraits in Silicon</dfn> <span class="loc">(TK7885.2)</span></li>
<li>Bishop, Michael and Zimmerman, Holmes – <dfn>Detailing Cars and Trucks</dfn> <span class="loc">(TL152)</span></li>
<li>Allaby, Michael and Lovelock, James – <dfn>The Greening of Mars</dfn> <span class="loc">(TL795.7)</span></li>
<li>Abbey, Barbara – <dfn>The Complete Book of Knitting</dfn> <span class="loc">(TT820)</span></li>
<li>Bishop, Jack – <dfn>Vegetables Every Day</dfn> <span class="loc">(TX801)</span></li>
<li>Lo, Kenneth – <dfn>Chinese Regional Cooking</dfn> <span class="loc">(TX724.5.C5)</span></li>
<ul class="booklist">
<li>Mollison, Bill – <dfn>Introduction to Permaculture</dfn> <span class="loc">(S494.5.P47)</span></li>

<li>Salatin, Joel – <dfn>Everything I Want to Do Is Illegal</dfn> <span class="loc">(S605.5)</span></li>

<li>David the Good – <dfn>Totally Crazy Easy Florida Gardening</dfn></li>

<li>Seymour, John – <dfn>The Complete Book of Self-Sufficiency</dfn> <span class="loc">(S605.5)</span></li>

<li>Cobleigh, Rolfe – <dfn>Handy Farm Devices and How to Make Them (2 copies)</dfn> <span class="loc">(S676)</span></li>

<li>Seymour, John – <dfn>Gardener's Delight</dfn> <span class="loc">(SB322)</span></li>

<li>Seymour, John – <dfn>The Self-Sufficient Gardener</dfn> <span class="loc">(SB324.3)</span></li>

<li>Haring, Elda – <dfn>The Seedling Handbook</dfn> <span class="loc">(SB405)</span></li>

<li>Abraham, George – <dfn>The Green Thumb Garden Handbook</dfn> <span class="loc">(SB453)</span></li>

<li><dfn>Reader's Digest Illustrated Guide to Gardening</dfn> <span class="loc">(SB453)</span></li>

<li>Kaczynski, Theodore John – <dfn>Technological Slavery</dfn> <span class="loc">(T14.5)</span></li>

<li>Kaczynski, Theodore John – <dfn>Anti-Tech Revolution: Why and How</dfn> <span class="loc">(T14.5)</span></li>

<li>Macaulay, David and Ardleym Neil – <dfn>The Way Things Work</dfn> <span class="loc">(T47)</span></li>

<li>Slater, Robert and Li, Ling and Li, Wen – <dfn>Portraits in Silicon</dfn> <span class="loc">(TK7885.2)</span></li>

<li>Bishop, Michael and Zimmerman, Holmes – <dfn>Detailing Cars and Trucks</dfn> <span class="loc">(TL152)</span></li>

<li>Allaby, Michael and Lovelock, James – <dfn>The Greening of Mars</dfn> <span class="loc">(TL795.7)</span></li>

<li>Abbey, Barbara – <dfn>The Complete Book of Knitting</dfn> <span class="loc">(TT820)</span></li>

<li>Bishop, Jack – <dfn>Vegetables Every Day</dfn> <span class="loc">(TX801)</span></li>

<li>Lo, Kenneth – <dfn>Chinese Regional Cooking</dfn> <span class="loc">(TX724.5.C5)</span></li>

</ul>
<h2 id="books-as-of-yet-unsorted">Books as of yet unsorted</h2>
<ul class="booklist">
<li>Seb Falk – <dfn>The Light Ages: The Surprising Story of Medieval Science</dfn></li>

<li><dfn>The Penny Catechism: A Catechism of Christian Doctrine</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese Reader, Part 1</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese</dfn></li>

<li>Flame Tree Publishing – <dfn>Gothic Fantasy: Lost Worlds Short Stories</dfn></li>

<li>Lee, Christopher – <dfn>This Sceptered Isle 55 BC to 1901</dfn></li>

<li>Malice, Michael – <dfn>Dear Reader</dfn></li>

<li>McCloskey, Deirdre N. – <dfn>Economic Writing</dfn></li>

<li>Meyer, Jerome S. – <dfn>The Provocative Puzzler</dfn></li>

<li>Parikh, Prashant – <dfn>Language and Equilibrium</dfn></li>

<li>Reed, Lawrence W. – <dfn>Great Myths of the Great Depression</dfn></li>

<li><dfn>Using HTML4, Java 1.1, and Javascript 1.2</dfn></li>

<li>Valizadeh, Roosh – <dfn>Game</dfn></li>

<li>Vikernes, Varg – <dfn>MYFAROG 2.6</dfn></li>

</ul>
<li>Seb Falk – <dfn>The Light Ages: The Surprising Story of Medieval Science</dfn></li>
<li><dfn>The Penny Catechism: A Catechism of Christian Doctrine</dfn></li>
<li>DeFrancis, John – <dfn>Beginning Chinese Reader, Part 1</dfn></li>
<li>DeFrancis, John – <dfn>Beginning Chinese</dfn></li>
<li>Flame Tree Publishing – <dfn>Gothic Fantasy: Lost Worlds Short Stories</dfn></li>
<li>Lee, Christopher – <dfn>This Sceptered Isle 55 BC to 1901</dfn></li>
<li>Malice, Michael – <dfn>Dear Reader</dfn></li>
<li>McCloskey, Deirdre N. – <dfn>Economic Writing</dfn></li>
<li>Meyer, Jerome S. – <dfn>The Provocative Puzzler</dfn></li>
<li>Parikh, Prashant – <dfn>Language and Equilibrium</dfn></li>
<li>Reed, Lawrence W. – <dfn>Great Myths of the Great Depression</dfn></li>
<li><dfn>Using HTML4, Java 1.1, and Javascript 1.2</dfn></li>
<li>Valizadeh, Roosh – <dfn>Game</dfn></li>
<li>Vikernes, Varg – <dfn>MYFAROG 2.6</dfn></li>
<ul class="booklist">
<li>Seb Falk – <dfn>The Light Ages: The Surprising Story of Medieval Science</dfn></li>

<li><dfn>The Penny Catechism: A Catechism of Christian Doctrine</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese Reader, Part 1</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese</dfn></li>

<li>Flame Tree Publishing – <dfn>Gothic Fantasy: Lost Worlds Short Stories</dfn></li>

<li>Lee, Christopher – <dfn>This Sceptered Isle 55 BC to 1901</dfn></li>

<li>Malice, Michael – <dfn>Dear Reader</dfn></li>

<li>McCloskey, Deirdre N. – <dfn>Economic Writing</dfn></li>

<li>Meyer, Jerome S. – <dfn>The Provocative Puzzler</dfn></li>

<li>Parikh, Prashant – <dfn>Language and Equilibrium</dfn></li>

<li>Reed, Lawrence W. – <dfn>Great Myths of the Great Depression</dfn></li>

<li><dfn>Using HTML4, Java 1.1, and Javascript 1.2</dfn></li>

<li>Valizadeh, Roosh – <dfn>Game</dfn></li>

<li>Vikernes, Varg – <dfn>MYFAROG 2.6</dfn></li>

</ul>
<div style="clear:both" class="taglist">Read related articles:<br><a id="tag_personal" href="https://lukesmith.xyz/tags/personal">Personal</a> · <a id="tag_science" href="https://lukesmith.xyz/tags/science">Science</a> · <a id="tag_tradition" href="https://lukesmith.xyz/tags/tradition">Tradition</a> · <a id="tag_lifestyle" href="https://lukesmith.xyz/tags/lifestyle">Lifestyle</a> · <a id="tag_philosophy" href="https://lukesmith.xyz/tags/philosophy">Philosophy</a></div>
Read related articles:
<br>
<a id="tag_personal" href="https://lukesmith.xyz/tags/personal">Personal</a>
<<pseudo>></<pseudo>>
Personal
<a id="tag_personal" href="https://lukesmith.xyz/tags/personal">Personal</a>
 ·
<a id="tag_science" href="https://lukesmith.xyz/tags/science">Science</a>
<<pseudo>></<pseudo>>
Science
<a id="tag_science" href="https://lukesmith.xyz/tags/science">Science</a>
 ·
<a id="tag_tradition" href="https://lukesmith.xyz/tags/tradition">Tradition</a>
 ·
<a id="tag_lifestyle" href="https://lukesmith.xyz/tags/lifestyle">Lifestyle</a>
 ·
<a id="tag_philosophy" href="https://lukesmith.xyz/tags/philosophy">Philosophy</a>
<div style="clear:both" class="taglist">Read related articles:<br><a id="tag_personal" href="https://lukesmith.xyz/tags/personal">Personal</a> · <a id="tag_science" href="https://lukesmith.xyz/tags/science">Science</a> · <a id="tag_tradition" href="https://lukesmith.xyz/tags/tradition">Tradition</a> · <a id="tag_lifestyle" href="https://lukesmith.xyz/tags/lifestyle">Lifestyle</a> · <a id="tag_philosophy" href="https://lukesmith.xyz/tags/philosophy">Philosophy</a></div>
<br clear="both">
<article>
<p>This is a list of the books in my personal library. If you have any
questions or want me to review any of them, email me
(<a href="mailto:luke@lukesmith.xyz">luke@lukesmith.xyz</a>).</p>
<p>I haven't read every book here, nor do I own all the books I've read
or like. I also don't necessarily like all the books I own.</p>
<p>Check out <a href="https://notrelated.xyz">my podcast, <em>Not Related!</em></a>
for some book reviews and other things. Books I've talked about in one
way or another in the podcast will have a link to that episode.</p>
<h2 id="-lindypressnet-books">🆕 LindyPress.net Books</h2>
<p>Note that now I am reprinting out-of-print works at
<a href="https://lindypress.net">LindyPress.net</a>. You can buy any of these books
yourself if you'd like. (Most of them are pretty exclusive in that I'm
the only one reprinting them.)</p>
<ul>
<li>Pseudo-Aristotle – <a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a></li>
<li><a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a></li>
<li>Isidore of Seville – <a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a></li>
<li>Roger Bacon ‐ <a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a></li>
<li>Marcus Aurelius – <a href="https://lindypress.net/book?pk=2">Meditations</a></li>
<li><a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a></li>
</ul>
<p>(These are at the top since I don't know if anyone has given them Library of
Congress numbers, and I suppose as an ad.)</p>
<h2 id="a-bd-general-works-philosophy-logic-speculative-philosophy">A-BD: General Works, Philosophy, Logic, Speculative Philosophy</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hCVdCS0t46I"><img src="/pix/searle.jpg" title="Searle (actually literally) did nothing wrong."></a></figure>

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
<h2 id="bm-bx-specific-religions-and-theology">BM-BX: Specific Religions and Theology</h2>

<figure class="resright"><img src="/pix/biglot.jpg" title="A Greek and Latin biglottic Bible"></figure>

<ul class="booklist">
<li><dfn>'תְּהִלַּת ה</dfn> <span class="loc">(BM675/D3)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Key to Theosophy</dfn> <span class="loc">(BP561)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Voice of Silence</dfn> <span class="loc">(BP561)</span></li>

<li>Wright, Stuart – <dfn>Armageddon in Waco</dfn> <span class="loc">(BP605.B62)</span></li>

<li>Lewis, C. S. – <dfn>Mere Christianity</dfn> <span class="loc">(BR123)</span></li>

<li>Lewis, C. S. – <dfn>The Screwtape Letters</dfn> <span class="loc">(BR125)</span></li>

<li>Reardon, Patrick Henry – <dfn>Christ in the Psalms</dfn> <span class="loc">(BS1430.4)</span></li>

<li>Leithart, Peter J. – <dfn>Solomon Among the Postmoderns</dfn> <span class="loc">(BS1475.52)</span></li>

<li>Porter, J. R. – <dfn>The Lost Bible</dfn> <span class="loc">(BS1700)</span></li>

<li>Heiser, Michael – <dfn>Reversing Hermon: Enoch, the Watchers and the Forgotten Mission of Jesus Christ</dfn> <span class="loc">(BS1830.E7)</span></li>

<li><dfn>The New Oxford Annotated Bible</dfn> <span class="loc">(BS191.5.A1)</span></li>

<li><dfn>The New English Bible</dfn> <span class="loc">(BS192.A1)</span></li>

<li>Montano, Arias and Leudsen, Johann – <dfn>Greek-Latin Parallel New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>Pocket Interlinear New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>The New International Dictionary of New Testament Theology (3 Volumes)</dfn> <span class="loc">(BS2312)</span></li>

<li><dfn>Ἡ Καινὴ Διαθήκη</dfn> <span class="loc">(BS2312)</span></li>

<li>Kümmel, Werner Georg – <dfn>Introduction to the New Testament</dfn> <span class="loc">(BS2330)</span></li>

<li>Aland, Kurt – <dfn>Synopsis Quattuor Evangeliorum</dfn> <span class="loc">(BS2560.A2)</span></li>

<li>Mack. Burton L. – <dfn>A Myth of Innocence</dfn> <span class="loc">(BS2585.2)</span></li>

<li>Ehrman, Bart D. – <dfn>Lost Christianities: The Battles for Scriptures and the Faiths We Never Knew</dfn> <span class="loc">(BS2840.E4)</span></li>

<li>Luther, Martin – <dfn>Luther's Small Catechism with Additions Including the Augsburg Confession</dfn> <span class="loc">(BR331.K64)</span></li>

<li>Strong, James – <dfn>Strong's Exhaustive Concordance of the Bible with Hebrew and Greek Dictionaries</dfn> <span class="loc">(BS425)</span></li>

<li><dfn>Illustrated Dictionary and Concordance of the Bible</dfn> <span class="loc">(BS440)</span></li>

<li>McDowell, Josh – <dfn>The New Evidence that Demands a Verdict</dfn> <span class="loc">(BS480)</span></li>

<li>Laymon, Charles M. – <dfn>The Interpreter's One-Volume Commentary on the Bible</dfn> <span class="loc">(BS491.2)</span></li>

<li>Cross, John R. – <dfn>The Stranger on the Road to Emmaus</dfn> <span class="loc">(BS511.2)</span></li>

<li><dfn>Reader's Digest Mysteries of the Bible; the Enduring Questions of the Scriptures</dfn> <span class="loc">(BS538)</span></li>

<li>Smith, Brendan Powell – <dfn>The Brick Bible</dfn> <span class="loc">(BS550.3)</span></li>

<li>Kent, Paul and McLaughlan, David – <dfn>Know Your Bible: All 66 Books Explained and Applied</dfn> <span class="loc">(BS593)</span></li>

<li><dfn>Septuagint with Apocrypha</dfn> <span class="loc">(BS742)</span></li>

<li><dfn>Biblia Sacra Vulgata</dfn> <span class="loc">(BS75)</span></li>

<li>Newman, John Henry – <dfn>An Essay on the Development of Christian Doctrine</dfn> <span class="loc">(BT21)</span></li>

<li>Robinson, James M. – <dfn>The Nag Hammadi Library</dfn> <span class="loc">(BT1391)</span></li>

<li>Lewis, C. S. – <dfn>Surprised by Joy: The Shape of My Early Life</dfn> <span class="loc">(BV4935.L43)</span></li>

<li>Carman, Stephen L. and Owen, Bob – <dfn>Quest: The Story of an Aerospace Engineer who Challenged God to Prove Himself</dfn> <span class="loc">(BV4930)</span></li>

<li>Ware, Timothy – <dfn>The Orthodox Church</dfn> <span class="loc">(BX106)</span></li>

<li>Aveling, J. C. H. – <dfn>The Jesuits</dfn> <span class="loc">(BX3706.2)</span></li>

<li><dfn>The Book of Common Prayer</dfn> <span class="loc">(BX5145)</span></li>

<li><dfn>Five Great Encyclicals: Labor, Education, Marriage, Reconstructing the Social Order, Atheistic Communism</dfn> <span class="loc">(BX860)</span></li>

</ul>
<h2 id="c-auxiliary-sciences-of-history">C: Auxiliary Sciences of History</h2>
<ul class="booklist">
<li>Graeber, David and Wengrow, David – <dfn>The Dawn of Everything: A New History of Humanity</dfn> <span class="loc">(CB19)</span></li>

<li>McNeill, William H. – <dfn>The Rise of the West: A History of the Human Community</dfn> <span class="loc">(CB59)</span></li>

<li>Sitchin, Zecharia – <dfn>The 12th Planet</dfn> <span class="loc">(CB156)</span></li>

<li>Rohl, David – <dfn>The Lords of Avaris: Uncovering the Legendary Origins of Western Civilization</dfn> <span class="loc">(CB245)</span> <a href="https://notrelated.xyz/#02.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Casson, Lionel and Clairborne, Robert and Fagan, Brian and Karp, Walter – <dfn>Mysteries of the Past</dfn> <span class="loc">(CB311)</span></li>

<li>Fisher, Marshall John and Fisher, David E. – <dfn>Mysteries of Lost Empires</dfn> <span class="loc">(CB311)</span></li>

<li>Hawkes, Jacquetta – <dfn>The Atlas of Early Man</dfn> <span class="loc">(CB311)</span></li>

<li>Platt, Richard and Riddell, Chris – <dfn>Castle Diary</dfn> <span class="loc">(CB351)</span></li>

<li>Cahill, Thomas – <dfn>Mysteries of the Middle Ages</dfn> <span class="loc">(CB351)</span></li>

</ul>
<h2 id="d-world-history">D: World History</h2>

<figure class="resright"><img src="/pix/racehutton.jpg" title="Hutton's book on the Third Reich"></figure>

<ul class="booklist">
<li>Malesky, Kee – <dfn>All Facts Considered, the Essential Library of Inessential Knowledge</dfn> <span class="loc">(D10)</span></li>

<li>Evola, Julius – <dfn>Revolt Against the Modern World</dfn> <span class="loc">(D16.8)</span></li>

<li>Epstein, Steven A. – <dfn>An Economic and Social History of Later Medieval Europe, 1000-1500</dfn> <span class="loc">(D117)</span></li>

<li>Pirenne, Henri – <dfn>A History of Europe</dfn> <span class="loc">(D117)</span></li>

<li>Cantor, Nroman F. – <dfn>Medieval History: The Life and Death of a Civilization</dfn> <span class="loc">(D118)</span></li>

<li>Roberts, J. M. – <dfn>New History of the World</dfn> <span class="loc">(D20)</span></li>

<li>Mann, Charles C. – <dfn>1493, Uncovering the New World Columbus Created</dfn> <span class="loc">(D228)</span></li>

<li>Rogan, Eugene L. – <dfn>The FAll of the Ottomans: The Great War in the Middle East</dfn> <span class="loc">(D566)</span></li>

<li>Sanborn, Frederick R. – <dfn>Design for War: A Study of Secret Power Politics</dfn> <span class="loc">(D742.U5)</span></li>

<li>Cheyney, Edward P. – <dfn>A Short History of England</dfn> <span class="loc">(DA32)</span></li>

<li>Thomas, Charles – <dfn>Celtic Britain</dfn> <span class="loc">(DA140)</span></li>

<li>Sellar, W.C. &amp; Yeatman R.J. – <dfn>1066 and All That</dfn> <span class="loc">(DA33)</span></li>

<li>Freeman, John and Sharpe, Sue – <dfn>This Beautiful Land: Britain</dfn> <span class="loc">(DA632)</span></li>

<li>Hutton, Christopher – <dfn>Race and the Third Reich</dfn> <span class="loc">(DD253)</span></li>

<li>Tacitus, C. Cornellius – <dfn>Annales et Historiae</dfn> <span class="loc">(DG207.T3)</span></li>

<li>Shirer, William L. – <dfn>The Rise and Fall of the Third Reich</dfn> <span class="loc">(DD256.5)</span></li>

<li>MacDonald, Kevin – <dfn>The Culture of Critique: An Evolutionary Analysis of Jewish Involvement in Twentieth-Century Intellectual and Political Movements</dfn> <span class="loc">(DS143)</span></li>

<li>Ford, Henry Sr. – <dfn>The International Jew: The World's Foremost Problem</dfn> <span class="loc">(DS145)</span></li>

<li>Ali, Tariq – <dfn>The Duel: Pakistan on the Flight Path of American Power</dfn> <span class="loc">(DS384)</span></li>

<li>De Bary, William Theodore – <dfn>The Sources of Indian Tradition</dfn> <span class="loc">(DS423)</span></li>

<li>Keay, John – <dfn>India, A History</dfn> <span class="loc">(DS451)</span></li>

<li>Ebrey, Patricia Buckley – <dfn>Cambridge Illustrated History of China</dfn> <span class="loc">(DS706)</span></li>

<li>National Geographic Society – <dfn>Journey into China</dfn> <span class="loc">(DS712)</span></li>

</ul>
<h2 id="e-f-history-of-the-americas">E-F: History of the Americas</h2>

<figure class="resright"><img src="/pix/foxfire.jpg"></figure>

<ul class="booklist">
<li>Hancock, Graham – <dfn>America Before: The Key to Earth's Lost Civilization</dfn> <span class="loc">(E61)</span></li>

<li>Little, Gregory – <dfn>Path of Souls: The Native American Death Journey: Cygnus, Orion, the Milky Way, Giant Skeletons in Mounds, &amp; the Smithsonian</dfn> <span class="loc">(E98.M8)</span></li>

<li>Mooney, James – <dfn>Myths of the Cherokee</dfn> <span class="loc">(E99.C5)</span></li>

<li>Greenblatt, Stephen – <dfn>New World Encounters</dfn> <span class="loc">(E141)</span></li>

<li>Fischer, David Hackett – <dfn>Albion's Seed: Four British Folkways in America</dfn> <span class="loc">(E169.1)</span> <a href="https://notrelated.xyz/#01.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Sowell, Thomas – <dfn>Ethnic America</dfn> <span class="loc">(E184.A1)</span></li>

<li>Hurmence, Belinda – <dfn>Before Freedom: 48 Oral Histories of Former North and South Carolina Slaves</dfn> <span class="loc">(E444)</span></li>

<li>Adams, Nehemiah – <dfn>A South-side View of Slavery: or Three Months at the South in 1854</dfn> <span class="loc">(E449)</span></li>

<li>Parsons, Charles Grandison – <dfn>An Inside View of Slavery; or A Tour Among the Planters</dfn> <span class="loc">(E449)</span></li>

<li>Long, A. L. – <dfn>Memoirs of Robert E. Lee</dfn> <span class="loc">(E467.1.L4)</span></li>

<li>Henry, Robert Selph – <dfn>The Story of the Confederacy</dfn> <span class="loc">(E487)</span></li>

<li>Mann, Charles C. – <dfn>1491, New Revelations of the Americas Before Columbus</dfn> <span class="loc">(E61)</span></li>

<li>Wharton, H. M. – <dfn>War Songs and Poems of the Southern Confederacy, 1861-1865: a Collection of the Most Popular and Impressive Songs and Poems of War Times, Dear to Every Southern Heart</dfn> <span class="loc">(E647)</span></li>

<li><dfn>The Blue Book of the John Birch Society</dfn> <span class="loc">(E743.5)</span></li>

<li>Stormer, John A. – <dfn>The Death of a Nation</dfn> <span class="loc">(E743.5)</span></li>

<li>Ramo, Joshua Cooper – <dfn>The Age of the Unthinkable</dfn> <span class="loc">(E902)</span></li>

<li>de las Casas, Bartolomé – <dfn>Brevisima relación de la destrución de las Indias</dfn> <span class="loc">(F1411)</span></li>

<li><dfn>The Foxfire Book</dfn> <span class="loc">(F291.2)</span></li>

<li><dfn>The Foxfire Book 2</dfn> <span class="loc">(F291.2)</span></li>

</ul>
<h2 id="g-geography-anthropology-recreation">G: Geography, Anthropology, Recreation</h2>
<ul class="booklist">
<li>Winer, Richard – <dfn>Ghost Ships: True Stories of Nautical Nightmares, Hauntings, and Disasters</dfn> <span class="loc">(G525)</span></li>

<li><dfn>National Geographic Collegiate Atlas of the World</dfn> <span class="loc">(G1021)</span></li>

<li>Wells, Spencer – <dfn>Pandora's Seed: The Unforeseen Cost of Civilization</dfn> <span class="loc">(GF75)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cochran, Gregory and Harpending, Henry – <dfn>the 10,000 Explosion: How Civilization Accelerated Human Evolution</dfn> <span class="loc">(GN281.4)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cremo, Michael A. &amp; Thompson, Ricahrd L. – <dfn>Forbidden Archaeology: The Hidden History of the Human Race</dfn> <span class="loc">(GN741)</span></li>

<li>Hancock, Graham – <dfn>Magicians of the Gods: The Forgotten Wisdom of Earth's Lost Civilization</dfn> <span class="loc">(GN751)</span></li>

<li>Cayce, Hugh Lynn – <dfn>Edgar Cayce on Atlantis</dfn> <span class="loc">(GN751.C35)</span></li>

<li>Marshack, Alexander – <dfn>The Roots of Civilization: The Cognitive Beginnings of Man's First Art, Symbol and Notation</dfn> <span class="loc">(GN772)</span></li>

<li>Bord, Janet and Bord, Colin – <dfn>Prehistoric Britain from the Air</dfn> <span class="loc">(GN805)</span></li>

<li>Bruce, Annette J. – <dfn>More Tellable Cracker Tales</dfn> <span class="loc">(GR110.F5)</span></li>

</ul>
<h2 id="h-social-sciences">H: Social Sciences</h2>
<p>
</p><figure class="resright"><img src="/pix/democracy.jpg"></figure>


<figure class="resright"><img src="/pix/pike.jpg"></figure>
<p></p>
<ul class="booklist">
<li>Greenspan, Alan – <dfn>The Age of Turbulence</dfn> <span class="loc">(HB119.G74)</span></li>

<li>Hazlitt, Hentry – <dfn>Economics in One Lesson (two copies)</dfn> <span class="loc">(HB171)</span></li>

<li>Keynes, John Maynard – <dfn>The General Theory of Employment, Interest and Money</dfn> <span class="loc">(HB171)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Rothbard, Murray – <dfn>Man, Economy and State with Power and Market</dfn> <span class="loc">(HB171)</span></li>

<li>von Mises, Ludwig – <dfn>Economic Policy</dfn> <span class="loc">(HB171)</span></li>

<li>Boulding, Kenneth E. – <dfn>Economic Analysis</dfn> <span class="loc">(HB171.5)</span></li>

<li>Goodman, Kennard E. and Moore, William L. – <dfn>Economics in Everyday Life</dfn> <span class="loc">(HB171.5)</span></li>

<li>Pindyck, Robert S. and Rubinfeld, Daniel L. – <dfn>Microeconomics</dfn> <span class="loc">(HB172)</span></li>

<li>Fisher, David Hackett – <dfn>The Great Wave: Price Revolutions and the Rhythm of History</dfn> <span class="loc">(HB231)</span></li>

<li>Soros, George – <dfn>The Crash of 2008 and What It Means</dfn> <span class="loc">(HB3722)</span> <a href="https://notrelated.xyz/#02.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Keen, Steve – <dfn>Debunking Economics: The Naked Emperor Dethroned?</dfn> <span class="loc">(HB71)</span></li>

<li>Krugman, Paul – <dfn>The Accidental Theorist</dfn> <span class="loc">(HB74.5)</span></li>

<li>Hoppe, Hans Hermann – <dfn>Democracy: The God That Failed: The Economics and Politics of Monarchy, Democracy and Natural Law</dfn> <span class="loc">(HB74.P65)</span></li>

<li>Ekelund, Robert B. Jr. and Hébert, Robert F – <dfn>A History of Economic Theory and Method</dfn> <span class="loc">(HB75)</span></li>

<li>Buchholz, Todd G. – <dfn>New Ideas from Dead Economists, an Introduction to Modern Economic Thought</dfn> <span class="loc">(HB76)</span></li>

<li>Heilbroner, Robert L. – <dfn>The Worldly Philosophers</dfn> <span class="loc">(HB76)</span></li>

<li>Paul Erlich – <dfn>The Population Bomb</dfn> <span class="loc">(HB875.E35)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Palmer, Tom G. – <dfn>After the Welfare State</dfn> <span class="loc">(HB99.3)</span></li>

<li>Krugman, Paul – <dfn>Peddling Prosperity</dfn> <span class="loc">(HB99.7)</span></li>

<li>Walton, Gary M. and Rockoff, Hugh – <dfn>History of the American Economy</dfn> <span class="loc">(HC103)</span></li>

<li>Krugman, Paul – <dfn>The Great Unravelling</dfn> <span class="loc">(HC106)</span></li>

<li>Krugman, Paul – <dfn>The Conscience of a Liberal</dfn> <span class="loc">(HC110.I5)</span></li>

<li>Clark, Gregory – <dfn>A Farewell to Alms</dfn> <span class="loc">(HC21)</span></li>

<li>Easterly, William – <dfn>The Elusive Quest for Growth</dfn> <span class="loc">(HC59.72.P6)</span></li>

<li>Simon, Julian L. and Kahn, Herman – <dfn>The Resourceful Earth</dfn> <span class="loc">(HC59.R445)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Dixit, Avinash K. and Nalebuff, Barry J. – <dfn>Thinking Strategically, The Competitive Edge in Business, Politics, and Everyday Life</dfn> <span class="loc">(HD30.28)</span></li>

<li>Adams, Scott – <dfn>The Dilbert Principle</dfn> <span class="loc">(HD31)</span></li>

<li>Ehrenreich, Barbara – <dfn>Nickel and Dimed</dfn> <span class="loc">(HD4918)</span></li>

<li>Thiel, Peter – <dfn>Zero to One: Notes on Start-Ups, or How to Build the Future</dfn> <span class="loc">(HD62.5)</span></li>

<li>Montgomery, David – <dfn>Beyond Equality: Labor and the Radical Republicans 1862-1872</dfn> <span class="loc">(HD8076)</span></li>

<li>Caplan, Bryan – <dfn>The Myth of the Rational Voter: Why Democracies Choose Bad Policies</dfn> <span class="loc">(HD87)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bhagwati, Jagdish – <dfn>In Defense of Globalization</dfn> <span class="loc">(HF1359)</span></li>

<li>Krugman, Paul and Obstfield, Maurice – <dfn>International Economics</dfn> <span class="loc">(HF1359)</span></li>

<li>Lechner, Frank J. and Boli, John – <dfn>The Globalization Reader</dfn> <span class="loc">(HF1359)</span></li>

<li>Myrdal, Gunnar – <dfn>Beyond the Welfare State</dfn> <span class="loc">(HF1411)</span></li>

<li>Graeber, David – <dfn>Bullshit Jobs: A Theory</dfn> <span class="loc">(HF5549.5.J63)</span> <a href="https://notrelated.xyz/#02.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Soros, George – <dfn>In Defense of Open Society</dfn> <span class="loc">(HG172.S63)</span></li>

<li>Boortz, Neal and Linder, John – <dfn>The Fairtax Book: Saying Goodbye to the Income Tax and the IRS</dfn> <span class="loc">(HJ4652)</span></li>

<li>Stove, David – <dfn>Darwinian Fairytales</dfn> <span class="loc">(HM106)</span></li>

<li>O'Brien, Jodi – <dfn>The Production of Reality</dfn> <span class="loc">(HM1033)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Skin in the Game</dfn> <span class="loc">(HM1101)</span></li>

<li>Berne, Eric – <dfn>Games People Play</dfn> <span class="loc">(HM1106)</span></li>

<li>Pinker, Steven – <dfn>The Better Angels of Our Nature</dfn> <span class="loc">(HM1116)</span></li>

<li>Kropotkin, Peter – <dfn>Mutual Aid: A Factor of Evolution</dfn> <span class="loc">(HM131)</span></li>

<li>Diamond, Jared – <dfn>Guns, Germs and Steel</dfn> <span class="loc">(HM206)</span></li>

<li>Bork, Robert H. – <dfn>Slouching Towards Gomorrah: Modern Liberalism and American Decline</dfn> <span class="loc">(HN59.2)</span></li>

<li>Arnold, Matthew – <dfn>Culture and Anarchy</dfn> <span class="loc">(HN389)</span></li>

<li>Jones, E. Michael – <dfn>Libido Dominandi: Sexual Liberation and Political Control</dfn> <span class="loc">(HQ472.U6)</span></li>

<li>Eisler, Riane – <dfn>The Chalice and the Blade, Our History, Our Future</dfn> <span class="loc">(HQ1075)</span></li>

<li>Harris, Judith Rich – <dfn>The Nurture Assumption</dfn> <span class="loc">(HQ772)</span></li>

<li>Beuerlein, Mark – <dfn>The Dumbest Generation</dfn> <span class="loc">(HQ799.7)</span></li>

<li>Street, Oliver Day – <dfn>Symbolism of the Three Degrees</dfn> <span class="loc">(HS425)</span></li>

<li><dfn>Morals and Dogma of the Ancient and Accepted Scottish Rite of Freemasonry</dfn> <span class="loc">(HS767)</span></li>

<li><dfn>The 9/11 Commission Report: Final Report of the National Commission on Terrorist Attacks upon the United States</dfn> <span class="loc">(HV6432.7)</span></li>

<li>Engels, Frederick – <dfn>Socialism: Utopian and Scientific</dfn> <span class="loc">(HX276)</span></li>

<li>Hayek, F. A. – <dfn>The Intellectuals and Socialism</dfn> <span class="loc">(HX528)</span></li>

<li>More, Thomas – <dfn>Utopia</dfn> <span class="loc">(HX810.5)</span></li>

<li>Stringham, Edward P. – <dfn>Anarchy and the Law</dfn> <span class="loc">(HX833)</span></li>

<li>Schumpeter, Joseph Alois – <dfn>Capitalism, Socialism and Democracy</dfn> <span class="loc">(HX86)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bastiat, Frederic – <dfn>The Law</dfn> <span class="loc">(HX87)</span></li>

</ul>
<h2 id="j-k-political-science-and-law">J-K: Political Science and Law</h2>

<figure class="resright"><img src="/pix/archeofuturism.jpg"></figure>

<ul class="booklist">
<li>Faye, Guillaume – <dfn>Archeofuturism: European Visions of the Post-Catastrophic Age</dfn> <span class="loc">(JA84.F8)</span></li>

<li>Plato – <dfn>The Republic</dfn> <span class="loc">(JC71)</span></li>

<li>Machiavelli, Niccolò – <dfn>The Prince and Other Writings</dfn> <span class="loc">(JC143)</span></li>

<li>Hobbes, Thomas – <dfn>Leviathan</dfn> <span class="loc">(JC153)</span></li>

<li>Filmer, Robert – <dfn>Patriarcha, or, The Natural Power of Kings</dfn> <span class="loc">(JC153.F48)</span></li>

<li>Samons, Loren J. – <dfn>What's Wrong with Democracy?</dfn> <span class="loc">(JC421)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Mill, John Stewart – <dfn>On Liberty</dfn> <span class="loc">(JC585)</span></li>

<li>Reed, Lawrence W. – <dfn>Are We Good Enough for Liberty?</dfn> <span class="loc">(JC585)</span></li>

<li>Jeffery, – <dfn>People's War: New Light on the Struggle for South Africa</dfn> <span class="loc">(JQ1998.A4)</span></li>

<li>Beard, Charles – <dfn>An Economic Interpretation of the Constitution of the United States</dfn> <span class="loc">(JK146)</span></li>

<li>Smith, Bradley A. – <dfn>Unfree Speech: The Folly of Campaign Finance Reform</dfn> <span class="loc">(JK1991)</span></li>

<li>de Tocqueville, Alexis – <dfn>Democracy in America</dfn> <span class="loc">(JK216)</span></li>

<li>Brimelow, Peter – <dfn>Alien Nation: Common Sense about America's Immigration Disaster</dfn> <span class="loc">(JV6493)</span></li>

<li>Fukuyama, Francis – <dfn>America at the Crossroads: Democracy, Power and Neoconservative Legacy</dfn> <span class="loc">(JZ1480)</span></li>

<li>Silverglate, Harvey A. and French, David A. and Lukianoff, Greg – <dfn>FIRE's Guide to Free Speech on Campus</dfn> <span class="loc">(KF4123.5)</span></li>

<li>Bernstein, David E. – <dfn>You Can't Say That!</dfn> <span class="loc">(KF4749)</span></li>

</ul>
<h2 id="l-n-education-music-fine-arts">L-N: Education, Music, Fine Arts</h2>
<ul class="booklist">
<li>Bloom, Allan – <dfn>The Closing of the American Mind: How Higher Education Has Failed Democracy and Impoverished the Souls of Today's Students</dfn> <span class="loc">(LA227.3)</span></li>

<li>Russell, Bertrand – <dfn>Education and the Good Life</dfn> <span class="loc">(LB775)</span></li>

<li><dfn>Baptist Hymnal</dfn> <span class="loc">(M2122)</span></li>

<li>Towner, D. B., Lorenz, E. S. and Wilson, Ira B. – <dfn>Songs of Praise: A Collection of Gospel Songs for Men's Voices</dfn> <span class="loc">(M2198)</span></li>

<li>International Graphic Society – <dfn>The Arts of Mankind: Painting, Architecture, Music</dfn> <span class="loc">(N5302)</span></li>

<li>Barral i Altet, Xavier – <dfn>The Early Middle Ages: From Late Antiquity to A.D. 1000</dfn> <span class="loc">(NA350)</span></li>

<li>Churchill, Winston S. – <dfn>Painting as a Pastime: An instructive and inspiring invitation to the joy of painting</dfn> <span class="loc">(ND1142)</span></li>

<li>Cornelius, Maurits – <dfn>The Graphic Work of M.C. Escher</dfn> <span class="loc">(NE670.E75)</span></li>

</ul>
<h2 id="p-philology-linguistics">P: Philology, Linguistics</h2>

<figure class="resright"><img src="/pix/westernclassical.jpg" title="Good for learning some #Lindy linguistics"></figure>

<ul class="booklist">
<li>Smith, Luke – <dfn>External Possession and the Undisentanglability of Syntax and Semantics</dfn></li>

<li>Chomsky, Noam – <dfn>Language and Mind</dfn> <span class="loc">(P106)</span></li>

<li>Harris, Roy – <dfn>Language, Saussure and Wittgenstein, How to Play Games with Words</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>Words and Rules, the Ingredients of Language</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>The Stuff of Thought</dfn> <span class="loc">(P107)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: I Linguistic Theory: Foundations</dfn> <span class="loc">(P121)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: II Linguistics Theory: Extensions and Implications</dfn> <span class="loc">(P121)</span></li>

<li>Ohio State University – <dfn>Language Files 11</dfn> <span class="loc">(P121)</span></li>

<li>Chomsky, Noam – <dfn>The Logical Structure of Linguistic Theory</dfn> <span class="loc">(P158)</span></li>

<li>Falk, Yehuda N. – <dfn>Lexical-Functional Grammar, An Introduction to Parallel Constraint-Based Syntax</dfn> <span class="loc">(P158.25)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Chomsky's Minimalism</dfn> <span class="loc">(P158.28)</span></li>

<li>Gutiérrez, Bravo and Arellanes Arellanes, Francisco and Peón Herrero, Mario Ernesto Chávez – <dfn>Nuevos estudios de Teoría de la Optimalidad</dfn> <span class="loc">(P158.42)</span></li>

<li>Richards, Norvin – <dfn>Contiguity Theory</dfn> <span class="loc">(P224.R43)</span></li>

<li>Bresnan, Joan and Asudeh, Ash and Tolivonen, Ida and Wechsler, Stephen – <dfn>Lexical-Functional Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Chomsky, Noam – <dfn>Aspects of the Theory of Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Freidin, Robert – <dfn>Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Saeed, John I. – <dfn>Semantics</dfn> <span class="loc">(P325)</span></li>

<li>Dalby, Andrew – <dfn>Dictionary of Languages, the Definitive Reference to More than 400 Languages</dfn> <span class="loc">(P371)</span></li>

<li>Allan, Keith – <dfn>The Western Classical Tradition in Linguistics</dfn> <span class="loc">(P61)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Western Linguistics: An Historical Introduction</dfn> <span class="loc">(P61)</span></li>

<li>Klein, Jared – <dfn>An Indo-European Chrestomathy</dfn></li>

<li>Watkins, Calvert – <dfn>The American Heritage Dictionary of Indo-European Roots</dfn> <span class="loc">(P615)</span></li>

<li>Sampson, Geoff – <dfn>Schools of Linguistics</dfn> <span class="loc">(P77)</span></li>

<li>Harris, Randy Allen – <dfn>The Linguistics Wars</dfn> <span class="loc">(P85.C47)</span></li>

<li>Cutting, Joan – <dfn>Pragmatics and Discourse</dfn> <span class="loc">(P99.4.P72)</span></li>

</ul>
<h2 id="pa-greek-and-latin-language-and-literature">PA: Greek and Latin language and Literature</h2>

<figure class="resright"><img src="/pix/hughes.jpg" title="These are actually pretty good and readable English translations."></figure>

<ul class="booklist">
<li>Morrison, Clinton and Barnes, David H. – <dfn>New Testament Word Lists</dfn> <span class="loc">(PA881)</span></li>

<li>Magoffin, Ralph van Deman and Henry, Margaret Young – <dfn>Latin First Year</dfn> <span class="loc">(PA2087)</span></li>

<li>Wheelock, Frederic M. – <dfn>Latin, an Introductory Course Based on Ancient Authors</dfn> <span class="loc">(PA2087.5)</span></li>

<li>Orberg, Hans H – <dfn>Roma Aeterna</dfn> <span class="loc">(PA2094.5)</span></li>

<li>Orberg, Hans H – <dfn>Colloquium Personarum</dfn> <span class="loc">(PA2095)</span></li>

<li>Orberg, Hans H – <dfn>Lingua Latina</dfn> <span class="loc">(PA2095)</span></li>

<li>Simpson, D. P. – <dfn>Cassell's Latin Dictionary</dfn> <span class="loc">(PA2365.E5)</span></li>

<li>Landis, Paul – <dfn>Four Famous Greek Plays</dfn> <span class="loc">(PA3626.A2)</span></li>

<li>Aeschylus – <dfn>The Oresteia</dfn> <span class="loc">(PA3827.A7)</span></li>

<li>Apollonius of Rhodes – <dfn>Jason and the Argonauts (Argonautica)</dfn> <span class="loc">(PA3872)</span></li>

<li>Euripides – <dfn>Three Plays of Euripides: Alcestis, Medea, the Bacchae</dfn> <span class="loc">(PA3975)</span></li>

<li>Euripides – <dfn>Alcestis and Other Plays</dfn> <span class="loc">(PA3975.A5)</span></li>

<li>Corpus Hermeticum – <dfn>Hermes Trismegistus</dfn> <span class="loc">(PA3998)</span></li>

<li>Homer – <dfn>The Iliad</dfn> <span class="loc">(PA4025.A2)</span></li>

<li>Homer – <dfn>The Odyssey</dfn> <span class="loc">(PA4025.A5)</span></li>

<li>Sophocles – <dfn>The Theban Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>The Complete Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>Electra and Other Plays</dfn> <span class="loc">(PA4414.A2)</span></li>

<li>Feyerabend, Karl – <dfn>Greek-English Dictionary</dfn> <span class="loc">(PA445.E5)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Liddell, H. G. and Scott – <dfn>Greek-English Lexicon</dfn> <span class="loc">(PA445.E5)</span></li>

<li>Juvenal – <dfn>The Sixteen Satires</dfn> <span class="loc">(PA6447.E5)</span></li>

<li>Lucretius – <dfn>On the Nature of Things</dfn> <span class="loc">(PA6483.E5)</span></li>

<li>Hughes, Ted – <dfn>Tales from Ovid: Twenty-Four Passages from the 'Metamorphoses' by Ovid</dfn> <span class="loc">(PA6522)</span></li>

<li>Petronius – <dfn>the Satyricon and the Fragments</dfn> <span class="loc">(PA6558.E5)</span></li>

<li>Pliny the Younger – <dfn>Pliny: A Self-Portrait in Letters</dfn> <span class="loc">(PA6639.E5)</span></li>

<li>Virgil – <dfn>Aeneid</dfn> <span class="loc">(PA6807.A5)</span></li>

<li>Virgil – <dfn>The Pastoral Poems</dfn> <span class="loc">(PA6807.B7)</span></li>

</ul>
<h2 id="pc-romance-languages">PC: Romance Languages</h2>

<figure class="resright"><img src="/pix/lathrop.jpg" title="Lathrop's Course on Historical Spanish"></figure>

<ul class="booklist">
<li>Decker, Henry W. and Bernhard, Francoise – <dfn>Modern French</dfn> <span class="loc">(PC211)</span></li>

<li>Azevedo, Milton M. – <dfn>Introducción a la Lingüística Española</dfn> <span class="loc">(PC4073)</span></li>

<li>Lathrop, T. A. and Gutiérrex Cuadrado, Juan – <dfn>Curso de gramática histórica española</dfn> <span class="loc">(PC4101)</span></li>

<li>Moreno, Oscar – <dfn>Gramática avanzada del español</dfn> <span class="loc">(PC4129.E5)</span></li>

<li>Cash, Annette G. and Murray, James C. – <dfn>Teoría y técnicas de traduccón: primeras etapas</dfn> <span class="loc">(PC4498)</span></li>

<li>Gili Gaya, Samuel – <dfn>Vox: Diccionario abreviado de la lengua española</dfn> <span class="loc">(PC4625)</span></li>

</ul>
<h2 id="pd-pf-germanic-languages-and-literatures">PD-PF: Germanic Languages and Literatures</h2>
<ul class="booklist">
<li>Lambdin, Thomas O. – <dfn>An Introduction to the Gothic Language</dfn> <span class="loc">(PD1123)</span></li>

<li>Hugo – <dfn>Swedish Phrase Book</dfn> <span class="loc">(PD5121)</span></li>

<li>Warriner, John E. and Whitten, Mary E. and Friggith, Francis J. – <dfn>Warriner's English Grammar and Composition</dfn> <span class="loc">(PE1112)</span></li>

<li>Elson, William H. and Keck, Christine – <dfn>Elson Grammar School Literature Book Two</dfn> <span class="loc">(PE1121)</span></li>

<li>Mitchell, Brucew and Robinson, Fred C. – <dfn>A Guide to Old English</dfn> <span class="loc">(PE131)</span></li>

<li>Evans, Jonathan – <dfn>An Introduction to Old English</dfn> <span class="loc">(PE135)</span></li>

<li>Bright, James W. – <dfn>Bright's Anglo-Saxon Reader</dfn> <span class="loc">(PE137)</span></li>

<li>Gottschalk, Katherine and Keith Hjortshoj – <dfn>The Elements of Teaching Writing</dfn> <span class="loc">(PE1404)</span></li>

<li>Forsyth, Mark – <dfn>The Elements of Eloquence</dfn> <span class="loc">(PE1421)</span></li>

<li>McCloskey, Deirdre N. – <dfn>Economical Writing</dfn> <span class="loc">(PE1479.E35)</span></li>

<li>Sharp, Stanley Louis and Strothmann, Friedrich Wilhelm – <dfn>German Reading Grammar</dfn> <span class="loc">(PF3111)</span></li>

<li>Morgan, Baynard Quincy and Strothmann, Friedrich Wilhelm – <dfn>Reading German</dfn> <span class="loc">(PF3117)</span></li>

<li>Berlitz – <dfn>Berlitz Self-Teaching German</dfn> <span class="loc">(PF3121)</span></li>

</ul>
<h2 id="pj-pl-oriental-indo-iranian-east-asian-and-oceanian-languages">PJ-PL: Oriental, Indo-Iranian, East-Asian and Oceanian Languages</h2>

<figure class="resright"><img src="/pix/sastry.jpg" title="Sanskrit in the Development of World Thought"></figure>

<ul class="booklist">
<li>Anonymous – <dfn>The Epic of Gilgamesh</dfn> <span class="loc">(PJ3771.G5)</span></li>

<li>Wightwick, Jane and Gaafar, Mahmoud – <dfn>Mastering Arabic</dfn> <span class="loc">(PJ6307)</span></li>

<li>Luxenberg, Christoph – <dfn>The Syro-Aramaic Reading of the Koran: A Contribution to Decoding the Language of the Koran</dfn> <span class="loc">(PJ6696)</span></li>

<li>Burnell, Arthur Coke – <dfn>On the Aindra school of Sanskrit grammarians, their place in the Sanskrit and subordinate literatures</dfn> <span class="loc">(PK407)</span></li>

<li>Sastry, Vempaty Kutumba – <dfn>Sanskrit and Development of World Thought</dfn> <span class="loc">(PK423)</span></li>

<li>Elwell-Sutton, L. P. – <dfn>Elementary Persian Grammar</dfn> <span class="loc">(PK6235)</span></li>

<li>Whitney, William Dwight – <dfn>A Sanskrit Grammar: Including Both the Classical Language, and the Older Dialects, of the Veda and Brahmana</dfn> <span class="loc">(PK663)</span></li>

<li>Sutherland, Goldman – <dfn>Devavanipravesika</dfn> <span class="loc">(PK666)</span></li>

<li>Whitney, William Dwight – <dfn>The Roots, Verb-Forms, And Primary Derivatives of the Sankstrit Language: A Supplement to his Sanskrit Grammar</dfn> <span class="loc">(PK745)</span></li>

<li>DeFrancis, John – <dfn>Intermediate Chinese</dfn> <span class="loc">(PL11117)</span></li>

<li>DeFrancis, John – <dfn>Advanced Chinese</dfn> <span class="loc">(PL1121.C5)</span></li>

<li>Defense Language Institute – <dfn>Chinese: Basic Course</dfn> <span class="loc">(PL1125)</span></li>

<li>Seligman, Scott D. – <dfn>Mandarin Chinese at a Glance</dfn> <span class="loc">(PL1125.E6)</span></li>

<li>DeFrancis, John – <dfn>The Chinese Language, Fact and Fantasy</dfn> <span class="loc">(PL1171)</span></li>

<li><dfn>Oxford Chinese Dictionary</dfn> <span class="loc">(PL1455)</span></li>

<li>Waley, Arthur – <dfn>Translations from the Chinese</dfn> <span class="loc">(PL3277.E3)</span></li>

<li>Burlington, Scott – <dfn>Instant Hawaiian</dfn> <span class="loc">(PL6445)</span></li>

<li>Pukui, Mary Kawena and Elbert, Samuel H. and Mookini, Esther T. – <dfn>The Pocket Hawaiian Dictionary</dfn> <span class="loc">(PL6446)</span></li>

</ul>
<h2 id="pn-general-literature">PN: General Literature</h2>
<ul class="booklist">
<li>Butterworth, Hezekiah – <dfn>The Story of America</dfn> <span class="loc">(PN1009.A1)</span></li>

<li>Kaplar, Richard T. and Patrick D. Maines – <dfn>The Government Factor: Undermining Journalistic Ethics in the Information Age</dfn> <span class="loc">(PN4888.E8)</span></li>

<li>Schwarz, Leo W. – <dfn>Feast of Leviathan: Tales of Adventure, Faith and Love from Jewish Literature</dfn> <span class="loc">(PN6071.J5)</span></li>

<li><dfn>Treasury of Familiar Quotations</dfn> <span class="loc">(PN6081)</span></li>

<li><dfn>Reader's Digest Treasury of American Humor</dfn> <span class="loc">(PN6162)</span></li>

<li>The Onion – <dfn>Dispatches from the Tenth Circle</dfn> <span class="loc">(PN6165)</span></li>

<li>The Onion – <dfn>Our Dumb World</dfn> <span class="loc">(PN6231.A74)</span></li>

<li>Raymond, Eric S. – <dfn>The New Hacker's Dictionary</dfn> <span class="loc">(PN6231.E4)</span></li>

<li>The Onion – <dfn>Our Dumb Century</dfn> <span class="loc">(PN6231.N6)</span></li>

<li>Gómez Dávila, Nicolás – <dfn>Escolios a un texto implícito</dfn> <span class="loc">(PN6275)</span></li>

<li>Brown, Jeffrey – <dfn>Darth Vader and Son</dfn> <span class="loc">(PN6727.B7575)</span></li>

<li>Watterson, Bill – <dfn>Calvin and Hobbes: Scientific Progress Goes 'Boink'</dfn> <span class="loc">(PN6728.C34)</span></li>

<li>Lewis, C. S. – <dfn>The Discarded Image: An Introduction to Medieval and Renaissance Literature</dfn> <span class="loc">(PN671)</span></li>

</ul>
<h2 id="pq-romance-literature">PQ: Romance Literature</h2>

<figure class="resright"><img src="/pix/inferno.jpg"></figure>

<ul class="booklist">
<li>de Montaigne, Michel – <dfn>Montaigne Selected Essays</dfn> <span class="loc">(PQ1642.E6)</span></li>

<li>Morlière, Jean-Baptiste – <dfn>Tartuffe and Other Plays</dfn> <span class="loc">(PQ1842)</span></li>

<li>De Saint-Exupéry – <dfn>Sazadeo Qickek</dfn> <span class="loc">(PQ2637.A274)</span></li>

<li>Alighieri, Dante – <dfn>The Divine Comedy</dfn> <span class="loc">(PQ4315)</span></li>

<li>Alighieri, Dante – <dfn>The Inferno</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Alighieri, Dante – <dfn>I: Hell (Sayers translation)</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Eco, Umberto – <dfn>Foucault's Pendulum</dfn> <span class="loc">(PQ4864.C6)</span></li>

<li>De la Vega, Garcilaso – <dfn>Poesías</dfn> <span class="loc">(PQ6391)</span></li>

<li>Garcia Lorca, Federico – <dfn>Rosita la soltera</dfn> <span class="loc">(PQ6613.A763)</span></li>

<li>Pérez-Reverte, Arturo – <dfn>La tabla de Flandés</dfn> <span class="loc">(PQ6666.E765)</span></li>

<li>Rulfo, Juan &amp;ndash; Pedro – <dfn>y El Llano en llamas</dfn> <span class="loc">(PQ7297.R89)</span></li>

</ul>
<h2 id="pr-english-literature">PR: English Literature</h2>
<ul class="booklist">
<li>Clark, Thomas Curtis and Gillespie, Esther A. – <dfn>1000 Quotable Poems</dfn> <span class="loc">(PR1175)</span></li>

<li><dfn>Beowulf</dfn> <span class="loc">(PR1583)</span></li>

<li>Chaucer, Geoffrey – <dfn>Chaucer's Major Poetry</dfn> <span class="loc">(PR1851)</span></li>

<li>Chaucer, Geoffrey – <dfn>The Canterbury Tales</dfn> <span class="loc">(PR1870.A1)</span></li>

<li>Collis, Louise – <dfn>Memoirs of a Medieval Woman</dfn> <span class="loc">(PR2007)</span></li>

<li>Malory, Thomas – <dfn>Le Morte d'Arthur</dfn> <span class="loc">(PR2041)</span></li>

<li>Craig, W. J. – <dfn>The Complete Works of William Shakespeare</dfn> <span class="loc">(PR2753.C8)</span></li>

<li>Shakespeare, William – <dfn>Hamlet (2 copies)</dfn> <span class="loc">(PR2801.A2)</span></li>

<li>Shakespeare, William – <dfn>Macbeth</dfn> <span class="loc">(PR2823.A2)</span></li>

<li>Shakespeare, William – <dfn>A Midsummer Night's Dream</dfn> <span class="loc">(PR2827.A2)</span></li>

<li>Shakespeare, William – <dfn>The Merchant of Venice</dfn> <span class="loc">(PR2825.A2)</span></li>

<li>Shakespeare, William – <dfn>The Sonnets</dfn> <span class="loc">(PR2848.A2)</span></li>

<li>Crystal, David – <dfn>The Oxford Dictionary of Original Shakespearean Pronunciation</dfn> <span class="loc">(PR2892)</span></li>

<li>Bunyan, John – <dfn>Pilgrim's Progress</dfn> <span class="loc">(PR3330)</span></li>

<li>Milton, John – <dfn>Paradise Lost and Other Poems</dfn> <span class="loc">(PR3560)</span></li>

<li>Coleridge, Samuel Taylor – <dfn>The Rime of the Ancient Mariner</dfn> <span class="loc">(PR4479)</span></li>

<li>Dickens, Charles – <dfn>Great Expectations</dfn> <span class="loc">(PR4560)</span></li>

<li>Shaw, George Bernard – <dfn>Pygmalion</dfn> <span class="loc">(PR5363)</span></li>

<li>Stevenson, Robert Louis – <dfn>The Black Arrow</dfn> <span class="loc">(PR5484)</span></li>

<li>Stevenson, Robert Louis – <dfn>New Arabian Nights</dfn> <span class="loc">(PR5484)</span></li>

<li>Wells, H. G. – <dfn>The Island of Dr. Moreau</dfn> <span class="loc">(PR5774)</span></li>

<li>Wilde, Oscar – <dfn>The Importance of Being Earnest</dfn> <span class="loc">(PR5818)</span></li>

<li>Christie, Agatha – <dfn>Death on the Nile</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Christie, Agatha – <dfn>The Nursery Rhyme Murders</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Golding, William – <dfn>Lord of the Flies</dfn> <span class="loc">(PR6013.O35)</span></li>

<li>Lewis, C. S. – <dfn>The Lion, the Witch and the Wardrobe</dfn> <span class="loc">(PR6023.E926)</span></li>

<li>Huxley, Aldous – <dfn>Brave New World</dfn> <span class="loc">(PR6015.U9)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Lord of the Rings, One-Volume Edition</dfn> <span class="loc">(PR6039.O32)</span></li>

<li>White, T. H. – <dfn>The Once and Future King</dfn> <span class="loc">(PR6045.H2)</span></li>

<li>Adams, Douglas – <dfn>Life, the Universe and Everything</dfn> <span class="loc">(PR6051.D3352)</span></li>

<li>Erickson, Paul – <dfn>Doctor Who: The Ark</dfn> <span class="loc">(PR6052.R449)</span></li>

<li>Burgess, Anthony – <dfn>A Clockwork Orange</dfn> <span class="loc">(PR6052.U638)</span></li>

<li>Grimwade, Peter – <dfn>Doctor Who: Planet of Fire</dfn> <span class="loc">(PR6057.R545)</span></li>

<li>Halleck, Reuben Post – <dfn>History of English Literature</dfn> <span class="loc">(PR85)</span></li>

<li>Achebe, Chinua – <dfn>Things Fall Apart</dfn> <span class="loc">(PR9387.9.A3)</span></li>

</ul>
<h2 id="ps-american-literature">PS: American Literature</h2>

<figure class="resright"><img src="/pix/lovecraft.jpg"></figure>

<ul class="booklist">
<li>Twain, Mark – <dfn>A Connecticut Yankee in King Arthur's Court</dfn> <span class="loc">(PS1308)</span></li>

<li>Hawthorne, Nathaniel – <dfn>The Scarlet Letter</dfn> <span class="loc">(PS1868)</span></li>

<li>Poe, Edgar Allan – <dfn>Edgar Allan Poe Reader</dfn> <span class="loc">(PS2603)</span></li>

<li>Poe, Edgar Allen – <dfn>Tales of Terror and Detection</dfn> <span class="loc">(PS2612)</span></li>

<li>Thoreau, Henry David – <dfn>Walden</dfn> <span class="loc">(PS3048)</span></li>

<li>Wallace, Lew – <dfn>Ben Hur</dfn> <span class="loc">(PS3134)</span></li>

<li>Faulkner, William – <dfn>Light in August</dfn> <span class="loc">(PS3511.A86)</span></li>

<li>Fitzgerald, F. Scott – <dfn>The Great Gatsby</dfn> <span class="loc">(PS3511.I9)</span></li>

<li>Heinlein, Robert A. – <dfn>For Us, the Living</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Heinlein, Robert A. – <dfn>The Moon is a Harsh Mistress</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Lovecraft, H. P. – <dfn>Great Tales of Horror</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Case of Charles Dexter Ward</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Doom That Came to Sarnath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Dream Quest of Unknown Kadath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Tomb</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Rodgers, Marion Elizabeth – <dfn>Mencken &amp; Sara</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Mencken, H. L. – <dfn>The Vintage Mencken</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Rand, Ayn – <dfn>Atlas Shugged</dfn> <span class="loc">(PS3535.A547)</span></li>

<li>Skinner, B. F. – <dfn>Walden Two</dfn> <span class="loc">(PS3537.K527)</span></li>

<li>Smith, Clark Ashton – <dfn>Hyperborea</dfn> <span class="loc">(PS3537.M335)</span></li>

<li>Bear, Greg – <dfn>Darwin's Radio</dfn> <span class="loc">(PS3552.E157)</span></li>

<li>Card, Orson Scott – <dfn>Ender's Game</dfn> <span class="loc">(PS3553.A655)</span></li>

<li>Crichton, Michael – <dfn>Congo</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Jurassic Park</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Timeline</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Dick, Philip K. – <dfn>Dr. Bloodmoney</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Dick, Philip K. – <dfn>Flow My Tears, The Policeman Said</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Herbert, Frank – <dfn>Dune</dfn> <span class="loc">(PS3558.E63)</span></li>

<li>Jordan, Robert – <dfn>The Eye of the World</dfn> <span class="loc">(PS3560.O7617)</span></li>

<li>King, Stephen – <dfn>The Bazaar of Bad Dreams</dfn> <span class="loc">(PS3561.I483)</span></li>

<li>Myers, Bill – <dfn>Blood of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Fire of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Threshold</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Quinn, Daniel – <dfn>Ishmael: An Adventure of the Mind and Spirit</dfn> <span class="loc">(PS3567.U338)</span></li>

<li>Pearl, Matthew – <dfn>The Dante Club</dfn> <span class="loc">(PS3616.E25)</span></li>

<li>Asimov, Isaac – <dfn>Before the Golden Age: A Science Fiction Anthology of the 1930's</dfn> <span class="loc">(PS648.S3)</span></li>

<li>Saramago, José – <dfn>Todos los nombres</dfn> <span class="loc">(PS9281.A66)</span></li>

</ul>
<h2 id="pq-pz-other-literature">PQ-PZ: Other Literature</h2>

<figure class="resright"><img src="/pix/edda.jpg"></figure>

<ul class="booklist">
<li>Voltaire – <dfn>Candide, Zadig and selected stories</dfn> <span class="loc">(PQ2081.E5)</span></li>

<li>Hesse, Hermann – <dfn>Siddhartha</dfn> <span class="loc">(PT2617.E85)</span></li>

<li>Hesse, Hermann – <dfn>The Glass Bead Game</dfn> <span class="loc">(PT2617.E85 G513)</span></li>

<li>Sturluson, Snorri – <dfn>Poetic Edda</dfn> <span class="loc">(PT7235)</span></li>

<li>Sturluson, Snorri – <dfn>Prose Edda</dfn> <span class="loc">(PT7313.E5)</span></li>

<li>Borges, Jorge Luis – <dfn>Ficciones</dfn> <span class="loc">(PW7797.B635)</span></li>

<li>Connor, Ralph – <dfn>Black Rock: a Tale of the Selkirks</dfn> <span class="loc">(PZ3.G654)</span></li>

<li>Roberts, James Hall – <dfn>The Q Document</dfn> <span class="loc">(PZ4.D913)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Hobbit</dfn> <span class="loc">(PZ7.T5744)</span></li>

<li>Wilder, Laura Ingalls – <dfn>Little House (entire series)</dfn> <span class="loc">(PZ7.W6461)</span></li>

<li>Jacobs, Joseph – <dfn>Favorite Celtic Fairy Tales</dfn> <span class="loc">(PZ8)</span></li>

<li>Baum, L. Frank – <dfn>The Wizard of Oz</dfn> <span class="loc">(PZ8.B327)</span></li>

<li><dfn>The Brothers Grimm Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

<li><dfn>The Complete Grimm's Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

</ul>
<h2 id="qa-general-science">QA: General Science</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hVxvLd6cF0k"><img src="/pix/againstmethod.jpg"></a></figure>

<ul class="booklist">
<li>de Santillanna, Giorgio – <dfn>The Origins of Scientific Thought: from Anazimander to Proclus, 600 B.C. to 300 A.D.</dfn> <span class="loc">(Q125)</span></li>

<li>Gardner, Martin – <dfn>Great Essays in Science</dfn> <span class="loc">(Q171)</span></li>

<li>Kuhn, Thomas – <dfn>The Structure of Scientific Revolutions</dfn> <span class="loc">(Q175)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Wiener, Norbert – <dfn>The Human Use of Human Beings</dfn> <span class="loc">(Q175)</span></li>

<li>Feyerabend, Paul – <dfn>Against Method </dfn> <span class="loc">(Q175)</span></li>

<li>Motterlini, Matteo – <dfn>For and Against Method: Including Lakatos's Lectures on Scientific Method and the Lakatos-Feyerabend Correspondence </dfn> <span class="loc">(Q175.3)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Antifragile</dfn> <span class="loc">(Q375)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>The Black Swan</dfn> <span class="loc">(Q375)</span></li>

</ul>
<h2 id="qa-mathematics">QA: Mathematics</h2>
<ul class="booklist">
<li>Sawyer, W. W. – <dfn>Mathematician's Delight</dfn> <span class="loc">(QA37)</span></li>

<li>Birns, Peter and Brown, Patrick and Muster, John C. C. – <dfn>Unix for People</dfn> <span class="loc">(QA76.6)</span></li>

<li>Raymond, Eric S. – <dfn>The Cathedral and the Bazaar</dfn> <span class="loc">(QA76.76.O63)</span></li>

<li>Bellos, Alex – <dfn>Here's Looking at Euclid</dfn> <span class="loc">(QA141.15)</span></li>

<li>Nyberg, Joseph A. – <dfn>Second Course in Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Wentworth, G. A. – <dfn>New School Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Hart, William – <dfn>College Algebra</dfn> <span class="loc">(QA154)</span></li>

<li>Lial, Margaret L. and Miller, Charles D. – <dfn>Algebra and Trigonometry</dfn> <span class="loc">(QA154.2)</span></li>

<li>Sokal, Alan and Bricmont, Jean – <dfn>Fashionable Nonsense: Postmodern Intellectuals' Abuse of Science</dfn> <span class="loc">(QA175)</span></li>

<li>Neugebauer, Otto – <dfn>The Exact Sciences in Antiquity</dfn> <span class="loc">(QA22)</span></li>

<li>Bharati Krsna Thirthaji Maharaja – <dfn>Vedic Mathematics</dfn> <span class="loc">(QA27.I4)</span></li>

<li>Christian, Robert R. – <dfn>Introduction to Logic and Sets</dfn> <span class="loc">(QA248)</span></li>

<li>Davis, Morton D. – <dfn>Game Theory: A Nontechnical Introduction</dfn> <span class="loc">(QA269)</span></li>

<li>Friedman, Avner – <dfn>Differential Games</dfn> <span class="loc">(QA272)</span></li>

<li>Takahashi, Shin – <dfn>The Manga Guide to Statistics</dfn> <span class="loc">(QA276)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 1-10</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 10-15 and Appendices</dfn> <span class="loc">(QA303)</span></li>

<li>Smith, Edward S. and Salkover, Meyer and Justive, Howard K. – <dfn>Unified Calculus</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny – <dfn>Calculus with Analytic Geometry</dfn> <span class="loc">(QA33)</span></li>

<li>Sperling, Abraham and Stuart, Monroe – <dfn>Mathematics (Made Simple Self-Teaching Library)</dfn> <span class="loc">(QA39.2)</span></li>

<li>Horblit, Marcus and Nielson, Kaj L. – <dfn>Problems in Plane Geometry with Solutions</dfn> <span class="loc">(QA459)</span></li>

<li>Shively, Levi S. – <dfn>Modern Geometry</dfn> <span class="loc">(QA473)</span></li>

<li>Nelson, Alfred L. and Folley, Karl W. – <dfn>Plane and Spherical Trigonometry</dfn> <span class="loc">(QA531.N45)</span></li>

<li>Love, Clyde E. – <dfn>Analytic Geometry</dfn> <span class="loc">(QA551)</span></li>

<li>Hutton, Graham – <dfn>Programming in Haskell</dfn> <span class="loc">(QA76.62)</span></li>

<li>Kernighan, Brian W. and Ritchie, Dennis M. – <dfn>The C Programming Language</dfn> <span class="loc">(QA76.73.C15)</span></li>

<li>Barski, Conrad – <dfn>Land of Lisp</dfn> <span class="loc">(QA76.76.C672)</span></li>

<li>Hofstadter, Douglas – <dfn>Gödel, Escher, Bach</dfn> <span class="loc">(QA9.8)</span></li>

<li>Emmet, E. R. – <dfn>Brain Puzzler's Delight</dfn> <span class="loc">(QA95)</span></li>

<li>Emmet, E. R. – <dfn>Puzzles for Pleasure</dfn> <span class="loc">(QA95)</span></li>

<li>Gardner, Martin – <dfn>aha! Gotcha, Paradoxes to puzzle and delight</dfn> <span class="loc">(QA95)</span></li>

<li>Heafford, Philip – <dfn>The Math Entertainer</dfn> <span class="loc">(QA95)</span></li>

</ul>
<h2 id="qb-qr-other-sciences">QB-QR: Other Sciences</h2>
<ul class="booklist">
<li>Hawking, Stephen W. – <dfn>A Brief History of Time</dfn> <span class="loc">(QB981)</span></li>

<li>Lerner, Eric – <dfn>The Big Bang Never Happened</dfn> <span class="loc">(QB991.B54)</span></li>

<li>McEvoy, J. P. and Zarate, Oscar – <dfn>Quantum Theory, A Graphic Guide</dfn> <span class="loc">(QC173.98)</span></li>

<li>Booker, Christopher – <dfn>The Real Global Warming Disaster</dfn> <span class="loc">(QC981.8.G56)</span></li>

<li>Greenburg, Arthur – <dfn>From Alchemy to Chemistry in Picture and Story</dfn> <span class="loc">(QD11)</span></li>

<li>Valentine, Basil – <dfn>Of Natural and Supernatural Things: Also, of the First Tincture, Root, and Spirit of Metals and Minerals: How the Same are Conceived, Generated, Brought Forth, Changed and Augmented</dfn> <span class="loc">(QD25)</span></li>

<li>Watson, James – <dfn>The Double Helix</dfn> <span class="loc">(QH31.D434)</span></li>

<li>Fodor, Jerry and Piattelli Palmarini, Massimo – <dfn>What Darwin Got Wrong</dfn> <span class="loc">(QH375)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Kadans, Joseph M. – <dfn>Modern Encyclopedia of Herbs</dfn> <span class="loc">(QK99.A1)</span></li>

<li>McFarland, J. Horace – <dfn>Getting Acquainted with Trees</dfn> <span class="loc">(QK482)</span></li>

<li>Kurzweil, Ray – <dfn>The Singularity is Near</dfn> <span class="loc">(QP376)</span></li>

<li>Kandel, Eric R. and Schwartz, James H. and Jessell, Thomas M. – <dfn>Essentials of Neural Science and Behavior</dfn> <span class="loc">(QP355.2)</span></li>

</ul>
<h2 id="r-medicine">R: Medicine</h2>
<ul class="booklist">
<li>FC&amp;A – <dfn>The Folk Remedy Encyclopedia: Olive Oil, Vinegar, Honey and 1,001 Other Home Remedies</dfn> <span class="loc">(R733)</span></li>

<li><dfn>Better Homes and Gardens Family Medical Guide</dfn> <span class="loc">(RC81.A2)</span></li>

<li><dfn>The Encyclopedia of Common Diseases</dfn> <span class="loc">(RC81.A2)</span></li>

</ul>
<h2 id="s-t-agriculture-and-technology">S-T: Agriculture and Technology</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=YRNKjQg6y-c"><img src="/pix/salatin.jpg"></a></figure>

<ul class="booklist">
<li>Mollison, Bill – <dfn>Introduction to Permaculture</dfn> <span class="loc">(S494.5.P47)</span></li>

<li>Salatin, Joel – <dfn>Everything I Want to Do Is Illegal</dfn> <span class="loc">(S605.5)</span></li>

<li>David the Good – <dfn>Totally Crazy Easy Florida Gardening</dfn></li>

<li>Seymour, John – <dfn>The Complete Book of Self-Sufficiency</dfn> <span class="loc">(S605.5)</span></li>

<li>Cobleigh, Rolfe – <dfn>Handy Farm Devices and How to Make Them (2 copies)</dfn> <span class="loc">(S676)</span></li>

<li>Seymour, John – <dfn>Gardener's Delight</dfn> <span class="loc">(SB322)</span></li>

<li>Seymour, John – <dfn>The Self-Sufficient Gardener</dfn> <span class="loc">(SB324.3)</span></li>

<li>Haring, Elda – <dfn>The Seedling Handbook</dfn> <span class="loc">(SB405)</span></li>

<li>Abraham, George – <dfn>The Green Thumb Garden Handbook</dfn> <span class="loc">(SB453)</span></li>

<li><dfn>Reader's Digest Illustrated Guide to Gardening</dfn> <span class="loc">(SB453)</span></li>

<li>Kaczynski, Theodore John – <dfn>Technological Slavery</dfn> <span class="loc">(T14.5)</span></li>

<li>Kaczynski, Theodore John – <dfn>Anti-Tech Revolution: Why and How</dfn> <span class="loc">(T14.5)</span></li>

<li>Macaulay, David and Ardleym Neil – <dfn>The Way Things Work</dfn> <span class="loc">(T47)</span></li>

<li>Slater, Robert and Li, Ling and Li, Wen – <dfn>Portraits in Silicon</dfn> <span class="loc">(TK7885.2)</span></li>

<li>Bishop, Michael and Zimmerman, Holmes – <dfn>Detailing Cars and Trucks</dfn> <span class="loc">(TL152)</span></li>

<li>Allaby, Michael and Lovelock, James – <dfn>The Greening of Mars</dfn> <span class="loc">(TL795.7)</span></li>

<li>Abbey, Barbara – <dfn>The Complete Book of Knitting</dfn> <span class="loc">(TT820)</span></li>

<li>Bishop, Jack – <dfn>Vegetables Every Day</dfn> <span class="loc">(TX801)</span></li>

<li>Lo, Kenneth – <dfn>Chinese Regional Cooking</dfn> <span class="loc">(TX724.5.C5)</span></li>

</ul>
<h2 id="books-as-of-yet-unsorted">Books as of yet unsorted</h2>
<ul class="booklist">
<li>Seb Falk – <dfn>The Light Ages: The Surprising Story of Medieval Science</dfn></li>

<li><dfn>The Penny Catechism: A Catechism of Christian Doctrine</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese Reader, Part 1</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese</dfn></li>

<li>Flame Tree Publishing – <dfn>Gothic Fantasy: Lost Worlds Short Stories</dfn></li>

<li>Lee, Christopher – <dfn>This Sceptered Isle 55 BC to 1901</dfn></li>

<li>Malice, Michael – <dfn>Dear Reader</dfn></li>

<li>McCloskey, Deirdre N. – <dfn>Economic Writing</dfn></li>

<li>Meyer, Jerome S. – <dfn>The Provocative Puzzler</dfn></li>

<li>Parikh, Prashant – <dfn>Language and Equilibrium</dfn></li>

<li>Reed, Lawrence W. – <dfn>Great Myths of the Great Depression</dfn></li>

<li><dfn>Using HTML4, Java 1.1, and Javascript 1.2</dfn></li>

<li>Valizadeh, Roosh – <dfn>Game</dfn></li>

<li>Vikernes, Varg – <dfn>MYFAROG 2.6</dfn></li>

</ul>
<div style="clear:both" class="taglist">Read related articles:<br><a id="tag_personal" href="https://lukesmith.xyz/tags/personal">Personal</a> · <a id="tag_science" href="https://lukesmith.xyz/tags/science">Science</a> · <a id="tag_tradition" href="https://lukesmith.xyz/tags/tradition">Tradition</a> · <a id="tag_lifestyle" href="https://lukesmith.xyz/tags/lifestyle">Lifestyle</a> · <a id="tag_philosophy" href="https://lukesmith.xyz/tags/philosophy">Philosophy</a></div>
<br clear="both">
</article>
<main>
<a href="/"><header>
	<h1 id="tag_My Personal Library">My Personal Library</h1>
</header></a>
<article>
<p>This is a list of the books in my personal library. If you have any
questions or want me to review any of them, email me
(<a href="mailto:luke@lukesmith.xyz">luke@lukesmith.xyz</a>).</p>
<p>I haven't read every book here, nor do I own all the books I've read
or like. I also don't necessarily like all the books I own.</p>
<p>Check out <a href="https://notrelated.xyz">my podcast, <em>Not Related!</em></a>
for some book reviews and other things. Books I've talked about in one
way or another in the podcast will have a link to that episode.</p>
<h2 id="-lindypressnet-books">🆕 LindyPress.net Books</h2>
<p>Note that now I am reprinting out-of-print works at
<a href="https://lindypress.net">LindyPress.net</a>. You can buy any of these books
yourself if you'd like. (Most of them are pretty exclusive in that I'm
the only one reprinting them.)</p>
<ul>
<li>Pseudo-Aristotle – <a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a></li>
<li><a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a></li>
<li>Isidore of Seville – <a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a></li>
<li>Roger Bacon ‐ <a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a></li>
<li>Marcus Aurelius – <a href="https://lindypress.net/book?pk=2">Meditations</a></li>
<li><a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a></li>
</ul>
<p>(These are at the top since I don't know if anyone has given them Library of
Congress numbers, and I suppose as an ad.)</p>
<h2 id="a-bd-general-works-philosophy-logic-speculative-philosophy">A-BD: General Works, Philosophy, Logic, Speculative Philosophy</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hCVdCS0t46I"><img src="/pix/searle.jpg" title="Searle (actually literally) did nothing wrong."></a></figure>

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
<h2 id="bm-bx-specific-religions-and-theology">BM-BX: Specific Religions and Theology</h2>

<figure class="resright"><img src="/pix/biglot.jpg" title="A Greek and Latin biglottic Bible"></figure>

<ul class="booklist">
<li><dfn>'תְּהִלַּת ה</dfn> <span class="loc">(BM675/D3)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Key to Theosophy</dfn> <span class="loc">(BP561)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Voice of Silence</dfn> <span class="loc">(BP561)</span></li>

<li>Wright, Stuart – <dfn>Armageddon in Waco</dfn> <span class="loc">(BP605.B62)</span></li>

<li>Lewis, C. S. – <dfn>Mere Christianity</dfn> <span class="loc">(BR123)</span></li>

<li>Lewis, C. S. – <dfn>The Screwtape Letters</dfn> <span class="loc">(BR125)</span></li>

<li>Reardon, Patrick Henry – <dfn>Christ in the Psalms</dfn> <span class="loc">(BS1430.4)</span></li>

<li>Leithart, Peter J. – <dfn>Solomon Among the Postmoderns</dfn> <span class="loc">(BS1475.52)</span></li>

<li>Porter, J. R. – <dfn>The Lost Bible</dfn> <span class="loc">(BS1700)</span></li>

<li>Heiser, Michael – <dfn>Reversing Hermon: Enoch, the Watchers and the Forgotten Mission of Jesus Christ</dfn> <span class="loc">(BS1830.E7)</span></li>

<li><dfn>The New Oxford Annotated Bible</dfn> <span class="loc">(BS191.5.A1)</span></li>

<li><dfn>The New English Bible</dfn> <span class="loc">(BS192.A1)</span></li>

<li>Montano, Arias and Leudsen, Johann – <dfn>Greek-Latin Parallel New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>Pocket Interlinear New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>The New International Dictionary of New Testament Theology (3 Volumes)</dfn> <span class="loc">(BS2312)</span></li>

<li><dfn>Ἡ Καινὴ Διαθήκη</dfn> <span class="loc">(BS2312)</span></li>

<li>Kümmel, Werner Georg – <dfn>Introduction to the New Testament</dfn> <span class="loc">(BS2330)</span></li>

<li>Aland, Kurt – <dfn>Synopsis Quattuor Evangeliorum</dfn> <span class="loc">(BS2560.A2)</span></li>

<li>Mack. Burton L. – <dfn>A Myth of Innocence</dfn> <span class="loc">(BS2585.2)</span></li>

<li>Ehrman, Bart D. – <dfn>Lost Christianities: The Battles for Scriptures and the Faiths We Never Knew</dfn> <span class="loc">(BS2840.E4)</span></li>

<li>Luther, Martin – <dfn>Luther's Small Catechism with Additions Including the Augsburg Confession</dfn> <span class="loc">(BR331.K64)</span></li>

<li>Strong, James – <dfn>Strong's Exhaustive Concordance of the Bible with Hebrew and Greek Dictionaries</dfn> <span class="loc">(BS425)</span></li>

<li><dfn>Illustrated Dictionary and Concordance of the Bible</dfn> <span class="loc">(BS440)</span></li>

<li>McDowell, Josh – <dfn>The New Evidence that Demands a Verdict</dfn> <span class="loc">(BS480)</span></li>

<li>Laymon, Charles M. – <dfn>The Interpreter's One-Volume Commentary on the Bible</dfn> <span class="loc">(BS491.2)</span></li>

<li>Cross, John R. – <dfn>The Stranger on the Road to Emmaus</dfn> <span class="loc">(BS511.2)</span></li>

<li><dfn>Reader's Digest Mysteries of the Bible; the Enduring Questions of the Scriptures</dfn> <span class="loc">(BS538)</span></li>

<li>Smith, Brendan Powell – <dfn>The Brick Bible</dfn> <span class="loc">(BS550.3)</span></li>

<li>Kent, Paul and McLaughlan, David – <dfn>Know Your Bible: All 66 Books Explained and Applied</dfn> <span class="loc">(BS593)</span></li>

<li><dfn>Septuagint with Apocrypha</dfn> <span class="loc">(BS742)</span></li>

<li><dfn>Biblia Sacra Vulgata</dfn> <span class="loc">(BS75)</span></li>

<li>Newman, John Henry – <dfn>An Essay on the Development of Christian Doctrine</dfn> <span class="loc">(BT21)</span></li>

<li>Robinson, James M. – <dfn>The Nag Hammadi Library</dfn> <span class="loc">(BT1391)</span></li>

<li>Lewis, C. S. – <dfn>Surprised by Joy: The Shape of My Early Life</dfn> <span class="loc">(BV4935.L43)</span></li>

<li>Carman, Stephen L. and Owen, Bob – <dfn>Quest: The Story of an Aerospace Engineer who Challenged God to Prove Himself</dfn> <span class="loc">(BV4930)</span></li>

<li>Ware, Timothy – <dfn>The Orthodox Church</dfn> <span class="loc">(BX106)</span></li>

<li>Aveling, J. C. H. – <dfn>The Jesuits</dfn> <span class="loc">(BX3706.2)</span></li>

<li><dfn>The Book of Common Prayer</dfn> <span class="loc">(BX5145)</span></li>

<li><dfn>Five Great Encyclicals: Labor, Education, Marriage, Reconstructing the Social Order, Atheistic Communism</dfn> <span class="loc">(BX860)</span></li>

</ul>
<h2 id="c-auxiliary-sciences-of-history">C: Auxiliary Sciences of History</h2>
<ul class="booklist">
<li>Graeber, David and Wengrow, David – <dfn>The Dawn of Everything: A New History of Humanity</dfn> <span class="loc">(CB19)</span></li>

<li>McNeill, William H. – <dfn>The Rise of the West: A History of the Human Community</dfn> <span class="loc">(CB59)</span></li>

<li>Sitchin, Zecharia – <dfn>The 12th Planet</dfn> <span class="loc">(CB156)</span></li>

<li>Rohl, David – <dfn>The Lords of Avaris: Uncovering the Legendary Origins of Western Civilization</dfn> <span class="loc">(CB245)</span> <a href="https://notrelated.xyz/#02.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Casson, Lionel and Clairborne, Robert and Fagan, Brian and Karp, Walter – <dfn>Mysteries of the Past</dfn> <span class="loc">(CB311)</span></li>

<li>Fisher, Marshall John and Fisher, David E. – <dfn>Mysteries of Lost Empires</dfn> <span class="loc">(CB311)</span></li>

<li>Hawkes, Jacquetta – <dfn>The Atlas of Early Man</dfn> <span class="loc">(CB311)</span></li>

<li>Platt, Richard and Riddell, Chris – <dfn>Castle Diary</dfn> <span class="loc">(CB351)</span></li>

<li>Cahill, Thomas – <dfn>Mysteries of the Middle Ages</dfn> <span class="loc">(CB351)</span></li>

</ul>
<h2 id="d-world-history">D: World History</h2>

<figure class="resright"><img src="/pix/racehutton.jpg" title="Hutton's book on the Third Reich"></figure>

<ul class="booklist">
<li>Malesky, Kee – <dfn>All Facts Considered, the Essential Library of Inessential Knowledge</dfn> <span class="loc">(D10)</span></li>

<li>Evola, Julius – <dfn>Revolt Against the Modern World</dfn> <span class="loc">(D16.8)</span></li>

<li>Epstein, Steven A. – <dfn>An Economic and Social History of Later Medieval Europe, 1000-1500</dfn> <span class="loc">(D117)</span></li>

<li>Pirenne, Henri – <dfn>A History of Europe</dfn> <span class="loc">(D117)</span></li>

<li>Cantor, Nroman F. – <dfn>Medieval History: The Life and Death of a Civilization</dfn> <span class="loc">(D118)</span></li>

<li>Roberts, J. M. – <dfn>New History of the World</dfn> <span class="loc">(D20)</span></li>

<li>Mann, Charles C. – <dfn>1493, Uncovering the New World Columbus Created</dfn> <span class="loc">(D228)</span></li>

<li>Rogan, Eugene L. – <dfn>The FAll of the Ottomans: The Great War in the Middle East</dfn> <span class="loc">(D566)</span></li>

<li>Sanborn, Frederick R. – <dfn>Design for War: A Study of Secret Power Politics</dfn> <span class="loc">(D742.U5)</span></li>

<li>Cheyney, Edward P. – <dfn>A Short History of England</dfn> <span class="loc">(DA32)</span></li>

<li>Thomas, Charles – <dfn>Celtic Britain</dfn> <span class="loc">(DA140)</span></li>

<li>Sellar, W.C. &amp; Yeatman R.J. – <dfn>1066 and All That</dfn> <span class="loc">(DA33)</span></li>

<li>Freeman, John and Sharpe, Sue – <dfn>This Beautiful Land: Britain</dfn> <span class="loc">(DA632)</span></li>

<li>Hutton, Christopher – <dfn>Race and the Third Reich</dfn> <span class="loc">(DD253)</span></li>

<li>Tacitus, C. Cornellius – <dfn>Annales et Historiae</dfn> <span class="loc">(DG207.T3)</span></li>

<li>Shirer, William L. – <dfn>The Rise and Fall of the Third Reich</dfn> <span class="loc">(DD256.5)</span></li>

<li>MacDonald, Kevin – <dfn>The Culture of Critique: An Evolutionary Analysis of Jewish Involvement in Twentieth-Century Intellectual and Political Movements</dfn> <span class="loc">(DS143)</span></li>

<li>Ford, Henry Sr. – <dfn>The International Jew: The World's Foremost Problem</dfn> <span class="loc">(DS145)</span></li>

<li>Ali, Tariq – <dfn>The Duel: Pakistan on the Flight Path of American Power</dfn> <span class="loc">(DS384)</span></li>

<li>De Bary, William Theodore – <dfn>The Sources of Indian Tradition</dfn> <span class="loc">(DS423)</span></li>

<li>Keay, John – <dfn>India, A History</dfn> <span class="loc">(DS451)</span></li>

<li>Ebrey, Patricia Buckley – <dfn>Cambridge Illustrated History of China</dfn> <span class="loc">(DS706)</span></li>

<li>National Geographic Society – <dfn>Journey into China</dfn> <span class="loc">(DS712)</span></li>

</ul>
<h2 id="e-f-history-of-the-americas">E-F: History of the Americas</h2>

<figure class="resright"><img src="/pix/foxfire.jpg"></figure>

<ul class="booklist">
<li>Hancock, Graham – <dfn>America Before: The Key to Earth's Lost Civilization</dfn> <span class="loc">(E61)</span></li>

<li>Little, Gregory – <dfn>Path of Souls: The Native American Death Journey: Cygnus, Orion, the Milky Way, Giant Skeletons in Mounds, &amp; the Smithsonian</dfn> <span class="loc">(E98.M8)</span></li>

<li>Mooney, James – <dfn>Myths of the Cherokee</dfn> <span class="loc">(E99.C5)</span></li>

<li>Greenblatt, Stephen – <dfn>New World Encounters</dfn> <span class="loc">(E141)</span></li>

<li>Fischer, David Hackett – <dfn>Albion's Seed: Four British Folkways in America</dfn> <span class="loc">(E169.1)</span> <a href="https://notrelated.xyz/#01.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Sowell, Thomas – <dfn>Ethnic America</dfn> <span class="loc">(E184.A1)</span></li>

<li>Hurmence, Belinda – <dfn>Before Freedom: 48 Oral Histories of Former North and South Carolina Slaves</dfn> <span class="loc">(E444)</span></li>

<li>Adams, Nehemiah – <dfn>A South-side View of Slavery: or Three Months at the South in 1854</dfn> <span class="loc">(E449)</span></li>

<li>Parsons, Charles Grandison – <dfn>An Inside View of Slavery; or A Tour Among the Planters</dfn> <span class="loc">(E449)</span></li>

<li>Long, A. L. – <dfn>Memoirs of Robert E. Lee</dfn> <span class="loc">(E467.1.L4)</span></li>

<li>Henry, Robert Selph – <dfn>The Story of the Confederacy</dfn> <span class="loc">(E487)</span></li>

<li>Mann, Charles C. – <dfn>1491, New Revelations of the Americas Before Columbus</dfn> <span class="loc">(E61)</span></li>

<li>Wharton, H. M. – <dfn>War Songs and Poems of the Southern Confederacy, 1861-1865: a Collection of the Most Popular and Impressive Songs and Poems of War Times, Dear to Every Southern Heart</dfn> <span class="loc">(E647)</span></li>

<li><dfn>The Blue Book of the John Birch Society</dfn> <span class="loc">(E743.5)</span></li>

<li>Stormer, John A. – <dfn>The Death of a Nation</dfn> <span class="loc">(E743.5)</span></li>

<li>Ramo, Joshua Cooper – <dfn>The Age of the Unthinkable</dfn> <span class="loc">(E902)</span></li>

<li>de las Casas, Bartolomé – <dfn>Brevisima relación de la destrución de las Indias</dfn> <span class="loc">(F1411)</span></li>

<li><dfn>The Foxfire Book</dfn> <span class="loc">(F291.2)</span></li>

<li><dfn>The Foxfire Book 2</dfn> <span class="loc">(F291.2)</span></li>

</ul>
<h2 id="g-geography-anthropology-recreation">G: Geography, Anthropology, Recreation</h2>
<ul class="booklist">
<li>Winer, Richard – <dfn>Ghost Ships: True Stories of Nautical Nightmares, Hauntings, and Disasters</dfn> <span class="loc">(G525)</span></li>

<li><dfn>National Geographic Collegiate Atlas of the World</dfn> <span class="loc">(G1021)</span></li>

<li>Wells, Spencer – <dfn>Pandora's Seed: The Unforeseen Cost of Civilization</dfn> <span class="loc">(GF75)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cochran, Gregory and Harpending, Henry – <dfn>the 10,000 Explosion: How Civilization Accelerated Human Evolution</dfn> <span class="loc">(GN281.4)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cremo, Michael A. &amp; Thompson, Ricahrd L. – <dfn>Forbidden Archaeology: The Hidden History of the Human Race</dfn> <span class="loc">(GN741)</span></li>

<li>Hancock, Graham – <dfn>Magicians of the Gods: The Forgotten Wisdom of Earth's Lost Civilization</dfn> <span class="loc">(GN751)</span></li>

<li>Cayce, Hugh Lynn – <dfn>Edgar Cayce on Atlantis</dfn> <span class="loc">(GN751.C35)</span></li>

<li>Marshack, Alexander – <dfn>The Roots of Civilization: The Cognitive Beginnings of Man's First Art, Symbol and Notation</dfn> <span class="loc">(GN772)</span></li>

<li>Bord, Janet and Bord, Colin – <dfn>Prehistoric Britain from the Air</dfn> <span class="loc">(GN805)</span></li>

<li>Bruce, Annette J. – <dfn>More Tellable Cracker Tales</dfn> <span class="loc">(GR110.F5)</span></li>

</ul>
<h2 id="h-social-sciences">H: Social Sciences</h2>
<p>
</p><figure class="resright"><img src="/pix/democracy.jpg"></figure>


<figure class="resright"><img src="/pix/pike.jpg"></figure>
<p></p>
<ul class="booklist">
<li>Greenspan, Alan – <dfn>The Age of Turbulence</dfn> <span class="loc">(HB119.G74)</span></li>

<li>Hazlitt, Hentry – <dfn>Economics in One Lesson (two copies)</dfn> <span class="loc">(HB171)</span></li>

<li>Keynes, John Maynard – <dfn>The General Theory of Employment, Interest and Money</dfn> <span class="loc">(HB171)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Rothbard, Murray – <dfn>Man, Economy and State with Power and Market</dfn> <span class="loc">(HB171)</span></li>

<li>von Mises, Ludwig – <dfn>Economic Policy</dfn> <span class="loc">(HB171)</span></li>

<li>Boulding, Kenneth E. – <dfn>Economic Analysis</dfn> <span class="loc">(HB171.5)</span></li>

<li>Goodman, Kennard E. and Moore, William L. – <dfn>Economics in Everyday Life</dfn> <span class="loc">(HB171.5)</span></li>

<li>Pindyck, Robert S. and Rubinfeld, Daniel L. – <dfn>Microeconomics</dfn> <span class="loc">(HB172)</span></li>

<li>Fisher, David Hackett – <dfn>The Great Wave: Price Revolutions and the Rhythm of History</dfn> <span class="loc">(HB231)</span></li>

<li>Soros, George – <dfn>The Crash of 2008 and What It Means</dfn> <span class="loc">(HB3722)</span> <a href="https://notrelated.xyz/#02.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Keen, Steve – <dfn>Debunking Economics: The Naked Emperor Dethroned?</dfn> <span class="loc">(HB71)</span></li>

<li>Krugman, Paul – <dfn>The Accidental Theorist</dfn> <span class="loc">(HB74.5)</span></li>

<li>Hoppe, Hans Hermann – <dfn>Democracy: The God That Failed: The Economics and Politics of Monarchy, Democracy and Natural Law</dfn> <span class="loc">(HB74.P65)</span></li>

<li>Ekelund, Robert B. Jr. and Hébert, Robert F – <dfn>A History of Economic Theory and Method</dfn> <span class="loc">(HB75)</span></li>

<li>Buchholz, Todd G. – <dfn>New Ideas from Dead Economists, an Introduction to Modern Economic Thought</dfn> <span class="loc">(HB76)</span></li>

<li>Heilbroner, Robert L. – <dfn>The Worldly Philosophers</dfn> <span class="loc">(HB76)</span></li>

<li>Paul Erlich – <dfn>The Population Bomb</dfn> <span class="loc">(HB875.E35)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Palmer, Tom G. – <dfn>After the Welfare State</dfn> <span class="loc">(HB99.3)</span></li>

<li>Krugman, Paul – <dfn>Peddling Prosperity</dfn> <span class="loc">(HB99.7)</span></li>

<li>Walton, Gary M. and Rockoff, Hugh – <dfn>History of the American Economy</dfn> <span class="loc">(HC103)</span></li>

<li>Krugman, Paul – <dfn>The Great Unravelling</dfn> <span class="loc">(HC106)</span></li>

<li>Krugman, Paul – <dfn>The Conscience of a Liberal</dfn> <span class="loc">(HC110.I5)</span></li>

<li>Clark, Gregory – <dfn>A Farewell to Alms</dfn> <span class="loc">(HC21)</span></li>

<li>Easterly, William – <dfn>The Elusive Quest for Growth</dfn> <span class="loc">(HC59.72.P6)</span></li>

<li>Simon, Julian L. and Kahn, Herman – <dfn>The Resourceful Earth</dfn> <span class="loc">(HC59.R445)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Dixit, Avinash K. and Nalebuff, Barry J. – <dfn>Thinking Strategically, The Competitive Edge in Business, Politics, and Everyday Life</dfn> <span class="loc">(HD30.28)</span></li>

<li>Adams, Scott – <dfn>The Dilbert Principle</dfn> <span class="loc">(HD31)</span></li>

<li>Ehrenreich, Barbara – <dfn>Nickel and Dimed</dfn> <span class="loc">(HD4918)</span></li>

<li>Thiel, Peter – <dfn>Zero to One: Notes on Start-Ups, or How to Build the Future</dfn> <span class="loc">(HD62.5)</span></li>

<li>Montgomery, David – <dfn>Beyond Equality: Labor and the Radical Republicans 1862-1872</dfn> <span class="loc">(HD8076)</span></li>

<li>Caplan, Bryan – <dfn>The Myth of the Rational Voter: Why Democracies Choose Bad Policies</dfn> <span class="loc">(HD87)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bhagwati, Jagdish – <dfn>In Defense of Globalization</dfn> <span class="loc">(HF1359)</span></li>

<li>Krugman, Paul and Obstfield, Maurice – <dfn>International Economics</dfn> <span class="loc">(HF1359)</span></li>

<li>Lechner, Frank J. and Boli, John – <dfn>The Globalization Reader</dfn> <span class="loc">(HF1359)</span></li>

<li>Myrdal, Gunnar – <dfn>Beyond the Welfare State</dfn> <span class="loc">(HF1411)</span></li>

<li>Graeber, David – <dfn>Bullshit Jobs: A Theory</dfn> <span class="loc">(HF5549.5.J63)</span> <a href="https://notrelated.xyz/#02.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Soros, George – <dfn>In Defense of Open Society</dfn> <span class="loc">(HG172.S63)</span></li>

<li>Boortz, Neal and Linder, John – <dfn>The Fairtax Book: Saying Goodbye to the Income Tax and the IRS</dfn> <span class="loc">(HJ4652)</span></li>

<li>Stove, David – <dfn>Darwinian Fairytales</dfn> <span class="loc">(HM106)</span></li>

<li>O'Brien, Jodi – <dfn>The Production of Reality</dfn> <span class="loc">(HM1033)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Skin in the Game</dfn> <span class="loc">(HM1101)</span></li>

<li>Berne, Eric – <dfn>Games People Play</dfn> <span class="loc">(HM1106)</span></li>

<li>Pinker, Steven – <dfn>The Better Angels of Our Nature</dfn> <span class="loc">(HM1116)</span></li>

<li>Kropotkin, Peter – <dfn>Mutual Aid: A Factor of Evolution</dfn> <span class="loc">(HM131)</span></li>

<li>Diamond, Jared – <dfn>Guns, Germs and Steel</dfn> <span class="loc">(HM206)</span></li>

<li>Bork, Robert H. – <dfn>Slouching Towards Gomorrah: Modern Liberalism and American Decline</dfn> <span class="loc">(HN59.2)</span></li>

<li>Arnold, Matthew – <dfn>Culture and Anarchy</dfn> <span class="loc">(HN389)</span></li>

<li>Jones, E. Michael – <dfn>Libido Dominandi: Sexual Liberation and Political Control</dfn> <span class="loc">(HQ472.U6)</span></li>

<li>Eisler, Riane – <dfn>The Chalice and the Blade, Our History, Our Future</dfn> <span class="loc">(HQ1075)</span></li>

<li>Harris, Judith Rich – <dfn>The Nurture Assumption</dfn> <span class="loc">(HQ772)</span></li>

<li>Beuerlein, Mark – <dfn>The Dumbest Generation</dfn> <span class="loc">(HQ799.7)</span></li>

<li>Street, Oliver Day – <dfn>Symbolism of the Three Degrees</dfn> <span class="loc">(HS425)</span></li>

<li><dfn>Morals and Dogma of the Ancient and Accepted Scottish Rite of Freemasonry</dfn> <span class="loc">(HS767)</span></li>

<li><dfn>The 9/11 Commission Report: Final Report of the National Commission on Terrorist Attacks upon the United States</dfn> <span class="loc">(HV6432.7)</span></li>

<li>Engels, Frederick – <dfn>Socialism: Utopian and Scientific</dfn> <span class="loc">(HX276)</span></li>

<li>Hayek, F. A. – <dfn>The Intellectuals and Socialism</dfn> <span class="loc">(HX528)</span></li>

<li>More, Thomas – <dfn>Utopia</dfn> <span class="loc">(HX810.5)</span></li>

<li>Stringham, Edward P. – <dfn>Anarchy and the Law</dfn> <span class="loc">(HX833)</span></li>

<li>Schumpeter, Joseph Alois – <dfn>Capitalism, Socialism and Democracy</dfn> <span class="loc">(HX86)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bastiat, Frederic – <dfn>The Law</dfn> <span class="loc">(HX87)</span></li>

</ul>
<h2 id="j-k-political-science-and-law">J-K: Political Science and Law</h2>

<figure class="resright"><img src="/pix/archeofuturism.jpg"></figure>

<ul class="booklist">
<li>Faye, Guillaume – <dfn>Archeofuturism: European Visions of the Post-Catastrophic Age</dfn> <span class="loc">(JA84.F8)</span></li>

<li>Plato – <dfn>The Republic</dfn> <span class="loc">(JC71)</span></li>

<li>Machiavelli, Niccolò – <dfn>The Prince and Other Writings</dfn> <span class="loc">(JC143)</span></li>

<li>Hobbes, Thomas – <dfn>Leviathan</dfn> <span class="loc">(JC153)</span></li>

<li>Filmer, Robert – <dfn>Patriarcha, or, The Natural Power of Kings</dfn> <span class="loc">(JC153.F48)</span></li>

<li>Samons, Loren J. – <dfn>What's Wrong with Democracy?</dfn> <span class="loc">(JC421)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Mill, John Stewart – <dfn>On Liberty</dfn> <span class="loc">(JC585)</span></li>

<li>Reed, Lawrence W. – <dfn>Are We Good Enough for Liberty?</dfn> <span class="loc">(JC585)</span></li>

<li>Jeffery, – <dfn>People's War: New Light on the Struggle for South Africa</dfn> <span class="loc">(JQ1998.A4)</span></li>

<li>Beard, Charles – <dfn>An Economic Interpretation of the Constitution of the United States</dfn> <span class="loc">(JK146)</span></li>

<li>Smith, Bradley A. – <dfn>Unfree Speech: The Folly of Campaign Finance Reform</dfn> <span class="loc">(JK1991)</span></li>

<li>de Tocqueville, Alexis – <dfn>Democracy in America</dfn> <span class="loc">(JK216)</span></li>

<li>Brimelow, Peter – <dfn>Alien Nation: Common Sense about America's Immigration Disaster</dfn> <span class="loc">(JV6493)</span></li>

<li>Fukuyama, Francis – <dfn>America at the Crossroads: Democracy, Power and Neoconservative Legacy</dfn> <span class="loc">(JZ1480)</span></li>

<li>Silverglate, Harvey A. and French, David A. and Lukianoff, Greg – <dfn>FIRE's Guide to Free Speech on Campus</dfn> <span class="loc">(KF4123.5)</span></li>

<li>Bernstein, David E. – <dfn>You Can't Say That!</dfn> <span class="loc">(KF4749)</span></li>

</ul>
<h2 id="l-n-education-music-fine-arts">L-N: Education, Music, Fine Arts</h2>
<ul class="booklist">
<li>Bloom, Allan – <dfn>The Closing of the American Mind: How Higher Education Has Failed Democracy and Impoverished the Souls of Today's Students</dfn> <span class="loc">(LA227.3)</span></li>

<li>Russell, Bertrand – <dfn>Education and the Good Life</dfn> <span class="loc">(LB775)</span></li>

<li><dfn>Baptist Hymnal</dfn> <span class="loc">(M2122)</span></li>

<li>Towner, D. B., Lorenz, E. S. and Wilson, Ira B. – <dfn>Songs of Praise: A Collection of Gospel Songs for Men's Voices</dfn> <span class="loc">(M2198)</span></li>

<li>International Graphic Society – <dfn>The Arts of Mankind: Painting, Architecture, Music</dfn> <span class="loc">(N5302)</span></li>

<li>Barral i Altet, Xavier – <dfn>The Early Middle Ages: From Late Antiquity to A.D. 1000</dfn> <span class="loc">(NA350)</span></li>

<li>Churchill, Winston S. – <dfn>Painting as a Pastime: An instructive and inspiring invitation to the joy of painting</dfn> <span class="loc">(ND1142)</span></li>

<li>Cornelius, Maurits – <dfn>The Graphic Work of M.C. Escher</dfn> <span class="loc">(NE670.E75)</span></li>

</ul>
<h2 id="p-philology-linguistics">P: Philology, Linguistics</h2>

<figure class="resright"><img src="/pix/westernclassical.jpg" title="Good for learning some #Lindy linguistics"></figure>

<ul class="booklist">
<li>Smith, Luke – <dfn>External Possession and the Undisentanglability of Syntax and Semantics</dfn></li>

<li>Chomsky, Noam – <dfn>Language and Mind</dfn> <span class="loc">(P106)</span></li>

<li>Harris, Roy – <dfn>Language, Saussure and Wittgenstein, How to Play Games with Words</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>Words and Rules, the Ingredients of Language</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>The Stuff of Thought</dfn> <span class="loc">(P107)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: I Linguistic Theory: Foundations</dfn> <span class="loc">(P121)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: II Linguistics Theory: Extensions and Implications</dfn> <span class="loc">(P121)</span></li>

<li>Ohio State University – <dfn>Language Files 11</dfn> <span class="loc">(P121)</span></li>

<li>Chomsky, Noam – <dfn>The Logical Structure of Linguistic Theory</dfn> <span class="loc">(P158)</span></li>

<li>Falk, Yehuda N. – <dfn>Lexical-Functional Grammar, An Introduction to Parallel Constraint-Based Syntax</dfn> <span class="loc">(P158.25)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Chomsky's Minimalism</dfn> <span class="loc">(P158.28)</span></li>

<li>Gutiérrez, Bravo and Arellanes Arellanes, Francisco and Peón Herrero, Mario Ernesto Chávez – <dfn>Nuevos estudios de Teoría de la Optimalidad</dfn> <span class="loc">(P158.42)</span></li>

<li>Richards, Norvin – <dfn>Contiguity Theory</dfn> <span class="loc">(P224.R43)</span></li>

<li>Bresnan, Joan and Asudeh, Ash and Tolivonen, Ida and Wechsler, Stephen – <dfn>Lexical-Functional Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Chomsky, Noam – <dfn>Aspects of the Theory of Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Freidin, Robert – <dfn>Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Saeed, John I. – <dfn>Semantics</dfn> <span class="loc">(P325)</span></li>

<li>Dalby, Andrew – <dfn>Dictionary of Languages, the Definitive Reference to More than 400 Languages</dfn> <span class="loc">(P371)</span></li>

<li>Allan, Keith – <dfn>The Western Classical Tradition in Linguistics</dfn> <span class="loc">(P61)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Western Linguistics: An Historical Introduction</dfn> <span class="loc">(P61)</span></li>

<li>Klein, Jared – <dfn>An Indo-European Chrestomathy</dfn></li>

<li>Watkins, Calvert – <dfn>The American Heritage Dictionary of Indo-European Roots</dfn> <span class="loc">(P615)</span></li>

<li>Sampson, Geoff – <dfn>Schools of Linguistics</dfn> <span class="loc">(P77)</span></li>

<li>Harris, Randy Allen – <dfn>The Linguistics Wars</dfn> <span class="loc">(P85.C47)</span></li>

<li>Cutting, Joan – <dfn>Pragmatics and Discourse</dfn> <span class="loc">(P99.4.P72)</span></li>

</ul>
<h2 id="pa-greek-and-latin-language-and-literature">PA: Greek and Latin language and Literature</h2>

<figure class="resright"><img src="/pix/hughes.jpg" title="These are actually pretty good and readable English translations."></figure>

<ul class="booklist">
<li>Morrison, Clinton and Barnes, David H. – <dfn>New Testament Word Lists</dfn> <span class="loc">(PA881)</span></li>

<li>Magoffin, Ralph van Deman and Henry, Margaret Young – <dfn>Latin First Year</dfn> <span class="loc">(PA2087)</span></li>

<li>Wheelock, Frederic M. – <dfn>Latin, an Introductory Course Based on Ancient Authors</dfn> <span class="loc">(PA2087.5)</span></li>

<li>Orberg, Hans H – <dfn>Roma Aeterna</dfn> <span class="loc">(PA2094.5)</span></li>

<li>Orberg, Hans H – <dfn>Colloquium Personarum</dfn> <span class="loc">(PA2095)</span></li>

<li>Orberg, Hans H – <dfn>Lingua Latina</dfn> <span class="loc">(PA2095)</span></li>

<li>Simpson, D. P. – <dfn>Cassell's Latin Dictionary</dfn> <span class="loc">(PA2365.E5)</span></li>

<li>Landis, Paul – <dfn>Four Famous Greek Plays</dfn> <span class="loc">(PA3626.A2)</span></li>

<li>Aeschylus – <dfn>The Oresteia</dfn> <span class="loc">(PA3827.A7)</span></li>

<li>Apollonius of Rhodes – <dfn>Jason and the Argonauts (Argonautica)</dfn> <span class="loc">(PA3872)</span></li>

<li>Euripides – <dfn>Three Plays of Euripides: Alcestis, Medea, the Bacchae</dfn> <span class="loc">(PA3975)</span></li>

<li>Euripides – <dfn>Alcestis and Other Plays</dfn> <span class="loc">(PA3975.A5)</span></li>

<li>Corpus Hermeticum – <dfn>Hermes Trismegistus</dfn> <span class="loc">(PA3998)</span></li>

<li>Homer – <dfn>The Iliad</dfn> <span class="loc">(PA4025.A2)</span></li>

<li>Homer – <dfn>The Odyssey</dfn> <span class="loc">(PA4025.A5)</span></li>

<li>Sophocles – <dfn>The Theban Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>The Complete Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>Electra and Other Plays</dfn> <span class="loc">(PA4414.A2)</span></li>

<li>Feyerabend, Karl – <dfn>Greek-English Dictionary</dfn> <span class="loc">(PA445.E5)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Liddell, H. G. and Scott – <dfn>Greek-English Lexicon</dfn> <span class="loc">(PA445.E5)</span></li>

<li>Juvenal – <dfn>The Sixteen Satires</dfn> <span class="loc">(PA6447.E5)</span></li>

<li>Lucretius – <dfn>On the Nature of Things</dfn> <span class="loc">(PA6483.E5)</span></li>

<li>Hughes, Ted – <dfn>Tales from Ovid: Twenty-Four Passages from the 'Metamorphoses' by Ovid</dfn> <span class="loc">(PA6522)</span></li>

<li>Petronius – <dfn>the Satyricon and the Fragments</dfn> <span class="loc">(PA6558.E5)</span></li>

<li>Pliny the Younger – <dfn>Pliny: A Self-Portrait in Letters</dfn> <span class="loc">(PA6639.E5)</span></li>

<li>Virgil – <dfn>Aeneid</dfn> <span class="loc">(PA6807.A5)</span></li>

<li>Virgil – <dfn>The Pastoral Poems</dfn> <span class="loc">(PA6807.B7)</span></li>

</ul>
<h2 id="pc-romance-languages">PC: Romance Languages</h2>

<figure class="resright"><img src="/pix/lathrop.jpg" title="Lathrop's Course on Historical Spanish"></figure>

<ul class="booklist">
<li>Decker, Henry W. and Bernhard, Francoise – <dfn>Modern French</dfn> <span class="loc">(PC211)</span></li>

<li>Azevedo, Milton M. – <dfn>Introducción a la Lingüística Española</dfn> <span class="loc">(PC4073)</span></li>

<li>Lathrop, T. A. and Gutiérrex Cuadrado, Juan – <dfn>Curso de gramática histórica española</dfn> <span class="loc">(PC4101)</span></li>

<li>Moreno, Oscar – <dfn>Gramática avanzada del español</dfn> <span class="loc">(PC4129.E5)</span></li>

<li>Cash, Annette G. and Murray, James C. – <dfn>Teoría y técnicas de traduccón: primeras etapas</dfn> <span class="loc">(PC4498)</span></li>

<li>Gili Gaya, Samuel – <dfn>Vox: Diccionario abreviado de la lengua española</dfn> <span class="loc">(PC4625)</span></li>

</ul>
<h2 id="pd-pf-germanic-languages-and-literatures">PD-PF: Germanic Languages and Literatures</h2>
<ul class="booklist">
<li>Lambdin, Thomas O. – <dfn>An Introduction to the Gothic Language</dfn> <span class="loc">(PD1123)</span></li>

<li>Hugo – <dfn>Swedish Phrase Book</dfn> <span class="loc">(PD5121)</span></li>

<li>Warriner, John E. and Whitten, Mary E. and Friggith, Francis J. – <dfn>Warriner's English Grammar and Composition</dfn> <span class="loc">(PE1112)</span></li>

<li>Elson, William H. and Keck, Christine – <dfn>Elson Grammar School Literature Book Two</dfn> <span class="loc">(PE1121)</span></li>

<li>Mitchell, Brucew and Robinson, Fred C. – <dfn>A Guide to Old English</dfn> <span class="loc">(PE131)</span></li>

<li>Evans, Jonathan – <dfn>An Introduction to Old English</dfn> <span class="loc">(PE135)</span></li>

<li>Bright, James W. – <dfn>Bright's Anglo-Saxon Reader</dfn> <span class="loc">(PE137)</span></li>

<li>Gottschalk, Katherine and Keith Hjortshoj – <dfn>The Elements of Teaching Writing</dfn> <span class="loc">(PE1404)</span></li>

<li>Forsyth, Mark – <dfn>The Elements of Eloquence</dfn> <span class="loc">(PE1421)</span></li>

<li>McCloskey, Deirdre N. – <dfn>Economical Writing</dfn> <span class="loc">(PE1479.E35)</span></li>

<li>Sharp, Stanley Louis and Strothmann, Friedrich Wilhelm – <dfn>German Reading Grammar</dfn> <span class="loc">(PF3111)</span></li>

<li>Morgan, Baynard Quincy and Strothmann, Friedrich Wilhelm – <dfn>Reading German</dfn> <span class="loc">(PF3117)</span></li>

<li>Berlitz – <dfn>Berlitz Self-Teaching German</dfn> <span class="loc">(PF3121)</span></li>

</ul>
<h2 id="pj-pl-oriental-indo-iranian-east-asian-and-oceanian-languages">PJ-PL: Oriental, Indo-Iranian, East-Asian and Oceanian Languages</h2>

<figure class="resright"><img src="/pix/sastry.jpg" title="Sanskrit in the Development of World Thought"></figure>

<ul class="booklist">
<li>Anonymous – <dfn>The Epic of Gilgamesh</dfn> <span class="loc">(PJ3771.G5)</span></li>

<li>Wightwick, Jane and Gaafar, Mahmoud – <dfn>Mastering Arabic</dfn> <span class="loc">(PJ6307)</span></li>

<li>Luxenberg, Christoph – <dfn>The Syro-Aramaic Reading of the Koran: A Contribution to Decoding the Language of the Koran</dfn> <span class="loc">(PJ6696)</span></li>

<li>Burnell, Arthur Coke – <dfn>On the Aindra school of Sanskrit grammarians, their place in the Sanskrit and subordinate literatures</dfn> <span class="loc">(PK407)</span></li>

<li>Sastry, Vempaty Kutumba – <dfn>Sanskrit and Development of World Thought</dfn> <span class="loc">(PK423)</span></li>

<li>Elwell-Sutton, L. P. – <dfn>Elementary Persian Grammar</dfn> <span class="loc">(PK6235)</span></li>

<li>Whitney, William Dwight – <dfn>A Sanskrit Grammar: Including Both the Classical Language, and the Older Dialects, of the Veda and Brahmana</dfn> <span class="loc">(PK663)</span></li>

<li>Sutherland, Goldman – <dfn>Devavanipravesika</dfn> <span class="loc">(PK666)</span></li>

<li>Whitney, William Dwight – <dfn>The Roots, Verb-Forms, And Primary Derivatives of the Sankstrit Language: A Supplement to his Sanskrit Grammar</dfn> <span class="loc">(PK745)</span></li>

<li>DeFrancis, John – <dfn>Intermediate Chinese</dfn> <span class="loc">(PL11117)</span></li>

<li>DeFrancis, John – <dfn>Advanced Chinese</dfn> <span class="loc">(PL1121.C5)</span></li>

<li>Defense Language Institute – <dfn>Chinese: Basic Course</dfn> <span class="loc">(PL1125)</span></li>

<li>Seligman, Scott D. – <dfn>Mandarin Chinese at a Glance</dfn> <span class="loc">(PL1125.E6)</span></li>

<li>DeFrancis, John – <dfn>The Chinese Language, Fact and Fantasy</dfn> <span class="loc">(PL1171)</span></li>

<li><dfn>Oxford Chinese Dictionary</dfn> <span class="loc">(PL1455)</span></li>

<li>Waley, Arthur – <dfn>Translations from the Chinese</dfn> <span class="loc">(PL3277.E3)</span></li>

<li>Burlington, Scott – <dfn>Instant Hawaiian</dfn> <span class="loc">(PL6445)</span></li>

<li>Pukui, Mary Kawena and Elbert, Samuel H. and Mookini, Esther T. – <dfn>The Pocket Hawaiian Dictionary</dfn> <span class="loc">(PL6446)</span></li>

</ul>
<h2 id="pn-general-literature">PN: General Literature</h2>
<ul class="booklist">
<li>Butterworth, Hezekiah – <dfn>The Story of America</dfn> <span class="loc">(PN1009.A1)</span></li>

<li>Kaplar, Richard T. and Patrick D. Maines – <dfn>The Government Factor: Undermining Journalistic Ethics in the Information Age</dfn> <span class="loc">(PN4888.E8)</span></li>

<li>Schwarz, Leo W. – <dfn>Feast of Leviathan: Tales of Adventure, Faith and Love from Jewish Literature</dfn> <span class="loc">(PN6071.J5)</span></li>

<li><dfn>Treasury of Familiar Quotations</dfn> <span class="loc">(PN6081)</span></li>

<li><dfn>Reader's Digest Treasury of American Humor</dfn> <span class="loc">(PN6162)</span></li>

<li>The Onion – <dfn>Dispatches from the Tenth Circle</dfn> <span class="loc">(PN6165)</span></li>

<li>The Onion – <dfn>Our Dumb World</dfn> <span class="loc">(PN6231.A74)</span></li>

<li>Raymond, Eric S. – <dfn>The New Hacker's Dictionary</dfn> <span class="loc">(PN6231.E4)</span></li>

<li>The Onion – <dfn>Our Dumb Century</dfn> <span class="loc">(PN6231.N6)</span></li>

<li>Gómez Dávila, Nicolás – <dfn>Escolios a un texto implícito</dfn> <span class="loc">(PN6275)</span></li>

<li>Brown, Jeffrey – <dfn>Darth Vader and Son</dfn> <span class="loc">(PN6727.B7575)</span></li>

<li>Watterson, Bill – <dfn>Calvin and Hobbes: Scientific Progress Goes 'Boink'</dfn> <span class="loc">(PN6728.C34)</span></li>

<li>Lewis, C. S. – <dfn>The Discarded Image: An Introduction to Medieval and Renaissance Literature</dfn> <span class="loc">(PN671)</span></li>

</ul>
<h2 id="pq-romance-literature">PQ: Romance Literature</h2>

<figure class="resright"><img src="/pix/inferno.jpg"></figure>

<ul class="booklist">
<li>de Montaigne, Michel – <dfn>Montaigne Selected Essays</dfn> <span class="loc">(PQ1642.E6)</span></li>

<li>Morlière, Jean-Baptiste – <dfn>Tartuffe and Other Plays</dfn> <span class="loc">(PQ1842)</span></li>

<li>De Saint-Exupéry – <dfn>Sazadeo Qickek</dfn> <span class="loc">(PQ2637.A274)</span></li>

<li>Alighieri, Dante – <dfn>The Divine Comedy</dfn> <span class="loc">(PQ4315)</span></li>

<li>Alighieri, Dante – <dfn>The Inferno</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Alighieri, Dante – <dfn>I: Hell (Sayers translation)</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Eco, Umberto – <dfn>Foucault's Pendulum</dfn> <span class="loc">(PQ4864.C6)</span></li>

<li>De la Vega, Garcilaso – <dfn>Poesías</dfn> <span class="loc">(PQ6391)</span></li>

<li>Garcia Lorca, Federico – <dfn>Rosita la soltera</dfn> <span class="loc">(PQ6613.A763)</span></li>

<li>Pérez-Reverte, Arturo – <dfn>La tabla de Flandés</dfn> <span class="loc">(PQ6666.E765)</span></li>

<li>Rulfo, Juan &amp;ndash; Pedro – <dfn>y El Llano en llamas</dfn> <span class="loc">(PQ7297.R89)</span></li>

</ul>
<h2 id="pr-english-literature">PR: English Literature</h2>
<ul class="booklist">
<li>Clark, Thomas Curtis and Gillespie, Esther A. – <dfn>1000 Quotable Poems</dfn> <span class="loc">(PR1175)</span></li>

<li><dfn>Beowulf</dfn> <span class="loc">(PR1583)</span></li>

<li>Chaucer, Geoffrey – <dfn>Chaucer's Major Poetry</dfn> <span class="loc">(PR1851)</span></li>

<li>Chaucer, Geoffrey – <dfn>The Canterbury Tales</dfn> <span class="loc">(PR1870.A1)</span></li>

<li>Collis, Louise – <dfn>Memoirs of a Medieval Woman</dfn> <span class="loc">(PR2007)</span></li>

<li>Malory, Thomas – <dfn>Le Morte d'Arthur</dfn> <span class="loc">(PR2041)</span></li>

<li>Craig, W. J. – <dfn>The Complete Works of William Shakespeare</dfn> <span class="loc">(PR2753.C8)</span></li>

<li>Shakespeare, William – <dfn>Hamlet (2 copies)</dfn> <span class="loc">(PR2801.A2)</span></li>

<li>Shakespeare, William – <dfn>Macbeth</dfn> <span class="loc">(PR2823.A2)</span></li>

<li>Shakespeare, William – <dfn>A Midsummer Night's Dream</dfn> <span class="loc">(PR2827.A2)</span></li>

<li>Shakespeare, William – <dfn>The Merchant of Venice</dfn> <span class="loc">(PR2825.A2)</span></li>

<li>Shakespeare, William – <dfn>The Sonnets</dfn> <span class="loc">(PR2848.A2)</span></li>

<li>Crystal, David – <dfn>The Oxford Dictionary of Original Shakespearean Pronunciation</dfn> <span class="loc">(PR2892)</span></li>

<li>Bunyan, John – <dfn>Pilgrim's Progress</dfn> <span class="loc">(PR3330)</span></li>

<li>Milton, John – <dfn>Paradise Lost and Other Poems</dfn> <span class="loc">(PR3560)</span></li>

<li>Coleridge, Samuel Taylor – <dfn>The Rime of the Ancient Mariner</dfn> <span class="loc">(PR4479)</span></li>

<li>Dickens, Charles – <dfn>Great Expectations</dfn> <span class="loc">(PR4560)</span></li>

<li>Shaw, George Bernard – <dfn>Pygmalion</dfn> <span class="loc">(PR5363)</span></li>

<li>Stevenson, Robert Louis – <dfn>The Black Arrow</dfn> <span class="loc">(PR5484)</span></li>

<li>Stevenson, Robert Louis – <dfn>New Arabian Nights</dfn> <span class="loc">(PR5484)</span></li>

<li>Wells, H. G. – <dfn>The Island of Dr. Moreau</dfn> <span class="loc">(PR5774)</span></li>

<li>Wilde, Oscar – <dfn>The Importance of Being Earnest</dfn> <span class="loc">(PR5818)</span></li>

<li>Christie, Agatha – <dfn>Death on the Nile</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Christie, Agatha – <dfn>The Nursery Rhyme Murders</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Golding, William – <dfn>Lord of the Flies</dfn> <span class="loc">(PR6013.O35)</span></li>

<li>Lewis, C. S. – <dfn>The Lion, the Witch and the Wardrobe</dfn> <span class="loc">(PR6023.E926)</span></li>

<li>Huxley, Aldous – <dfn>Brave New World</dfn> <span class="loc">(PR6015.U9)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Lord of the Rings, One-Volume Edition</dfn> <span class="loc">(PR6039.O32)</span></li>

<li>White, T. H. – <dfn>The Once and Future King</dfn> <span class="loc">(PR6045.H2)</span></li>

<li>Adams, Douglas – <dfn>Life, the Universe and Everything</dfn> <span class="loc">(PR6051.D3352)</span></li>

<li>Erickson, Paul – <dfn>Doctor Who: The Ark</dfn> <span class="loc">(PR6052.R449)</span></li>

<li>Burgess, Anthony – <dfn>A Clockwork Orange</dfn> <span class="loc">(PR6052.U638)</span></li>

<li>Grimwade, Peter – <dfn>Doctor Who: Planet of Fire</dfn> <span class="loc">(PR6057.R545)</span></li>

<li>Halleck, Reuben Post – <dfn>History of English Literature</dfn> <span class="loc">(PR85)</span></li>

<li>Achebe, Chinua – <dfn>Things Fall Apart</dfn> <span class="loc">(PR9387.9.A3)</span></li>

</ul>
<h2 id="ps-american-literature">PS: American Literature</h2>

<figure class="resright"><img src="/pix/lovecraft.jpg"></figure>

<ul class="booklist">
<li>Twain, Mark – <dfn>A Connecticut Yankee in King Arthur's Court</dfn> <span class="loc">(PS1308)</span></li>

<li>Hawthorne, Nathaniel – <dfn>The Scarlet Letter</dfn> <span class="loc">(PS1868)</span></li>

<li>Poe, Edgar Allan – <dfn>Edgar Allan Poe Reader</dfn> <span class="loc">(PS2603)</span></li>

<li>Poe, Edgar Allen – <dfn>Tales of Terror and Detection</dfn> <span class="loc">(PS2612)</span></li>

<li>Thoreau, Henry David – <dfn>Walden</dfn> <span class="loc">(PS3048)</span></li>

<li>Wallace, Lew – <dfn>Ben Hur</dfn> <span class="loc">(PS3134)</span></li>

<li>Faulkner, William – <dfn>Light in August</dfn> <span class="loc">(PS3511.A86)</span></li>

<li>Fitzgerald, F. Scott – <dfn>The Great Gatsby</dfn> <span class="loc">(PS3511.I9)</span></li>

<li>Heinlein, Robert A. – <dfn>For Us, the Living</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Heinlein, Robert A. – <dfn>The Moon is a Harsh Mistress</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Lovecraft, H. P. – <dfn>Great Tales of Horror</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Case of Charles Dexter Ward</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Doom That Came to Sarnath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Dream Quest of Unknown Kadath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Tomb</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Rodgers, Marion Elizabeth – <dfn>Mencken &amp; Sara</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Mencken, H. L. – <dfn>The Vintage Mencken</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Rand, Ayn – <dfn>Atlas Shugged</dfn> <span class="loc">(PS3535.A547)</span></li>

<li>Skinner, B. F. – <dfn>Walden Two</dfn> <span class="loc">(PS3537.K527)</span></li>

<li>Smith, Clark Ashton – <dfn>Hyperborea</dfn> <span class="loc">(PS3537.M335)</span></li>

<li>Bear, Greg – <dfn>Darwin's Radio</dfn> <span class="loc">(PS3552.E157)</span></li>

<li>Card, Orson Scott – <dfn>Ender's Game</dfn> <span class="loc">(PS3553.A655)</span></li>

<li>Crichton, Michael – <dfn>Congo</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Jurassic Park</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Timeline</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Dick, Philip K. – <dfn>Dr. Bloodmoney</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Dick, Philip K. – <dfn>Flow My Tears, The Policeman Said</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Herbert, Frank – <dfn>Dune</dfn> <span class="loc">(PS3558.E63)</span></li>

<li>Jordan, Robert – <dfn>The Eye of the World</dfn> <span class="loc">(PS3560.O7617)</span></li>

<li>King, Stephen – <dfn>The Bazaar of Bad Dreams</dfn> <span class="loc">(PS3561.I483)</span></li>

<li>Myers, Bill – <dfn>Blood of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Fire of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Threshold</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Quinn, Daniel – <dfn>Ishmael: An Adventure of the Mind and Spirit</dfn> <span class="loc">(PS3567.U338)</span></li>

<li>Pearl, Matthew – <dfn>The Dante Club</dfn> <span class="loc">(PS3616.E25)</span></li>

<li>Asimov, Isaac – <dfn>Before the Golden Age: A Science Fiction Anthology of the 1930's</dfn> <span class="loc">(PS648.S3)</span></li>

<li>Saramago, José – <dfn>Todos los nombres</dfn> <span class="loc">(PS9281.A66)</span></li>

</ul>
<h2 id="pq-pz-other-literature">PQ-PZ: Other Literature</h2>

<figure class="resright"><img src="/pix/edda.jpg"></figure>

<ul class="booklist">
<li>Voltaire – <dfn>Candide, Zadig and selected stories</dfn> <span class="loc">(PQ2081.E5)</span></li>

<li>Hesse, Hermann – <dfn>Siddhartha</dfn> <span class="loc">(PT2617.E85)</span></li>

<li>Hesse, Hermann – <dfn>The Glass Bead Game</dfn> <span class="loc">(PT2617.E85 G513)</span></li>

<li>Sturluson, Snorri – <dfn>Poetic Edda</dfn> <span class="loc">(PT7235)</span></li>

<li>Sturluson, Snorri – <dfn>Prose Edda</dfn> <span class="loc">(PT7313.E5)</span></li>

<li>Borges, Jorge Luis – <dfn>Ficciones</dfn> <span class="loc">(PW7797.B635)</span></li>

<li>Connor, Ralph – <dfn>Black Rock: a Tale of the Selkirks</dfn> <span class="loc">(PZ3.G654)</span></li>

<li>Roberts, James Hall – <dfn>The Q Document</dfn> <span class="loc">(PZ4.D913)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Hobbit</dfn> <span class="loc">(PZ7.T5744)</span></li>

<li>Wilder, Laura Ingalls – <dfn>Little House (entire series)</dfn> <span class="loc">(PZ7.W6461)</span></li>

<li>Jacobs, Joseph – <dfn>Favorite Celtic Fairy Tales</dfn> <span class="loc">(PZ8)</span></li>

<li>Baum, L. Frank – <dfn>The Wizard of Oz</dfn> <span class="loc">(PZ8.B327)</span></li>

<li><dfn>The Brothers Grimm Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

<li><dfn>The Complete Grimm's Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

</ul>
<h2 id="qa-general-science">QA: General Science</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hVxvLd6cF0k"><img src="/pix/againstmethod.jpg"></a></figure>

<ul class="booklist">
<li>de Santillanna, Giorgio – <dfn>The Origins of Scientific Thought: from Anazimander to Proclus, 600 B.C. to 300 A.D.</dfn> <span class="loc">(Q125)</span></li>

<li>Gardner, Martin – <dfn>Great Essays in Science</dfn> <span class="loc">(Q171)</span></li>

<li>Kuhn, Thomas – <dfn>The Structure of Scientific Revolutions</dfn> <span class="loc">(Q175)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Wiener, Norbert – <dfn>The Human Use of Human Beings</dfn> <span class="loc">(Q175)</span></li>

<li>Feyerabend, Paul – <dfn>Against Method </dfn> <span class="loc">(Q175)</span></li>

<li>Motterlini, Matteo – <dfn>For and Against Method: Including Lakatos's Lectures on Scientific Method and the Lakatos-Feyerabend Correspondence </dfn> <span class="loc">(Q175.3)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Antifragile</dfn> <span class="loc">(Q375)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>The Black Swan</dfn> <span class="loc">(Q375)</span></li>

</ul>
<h2 id="qa-mathematics">QA: Mathematics</h2>
<ul class="booklist">
<li>Sawyer, W. W. – <dfn>Mathematician's Delight</dfn> <span class="loc">(QA37)</span></li>

<li>Birns, Peter and Brown, Patrick and Muster, John C. C. – <dfn>Unix for People</dfn> <span class="loc">(QA76.6)</span></li>

<li>Raymond, Eric S. – <dfn>The Cathedral and the Bazaar</dfn> <span class="loc">(QA76.76.O63)</span></li>

<li>Bellos, Alex – <dfn>Here's Looking at Euclid</dfn> <span class="loc">(QA141.15)</span></li>

<li>Nyberg, Joseph A. – <dfn>Second Course in Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Wentworth, G. A. – <dfn>New School Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Hart, William – <dfn>College Algebra</dfn> <span class="loc">(QA154)</span></li>

<li>Lial, Margaret L. and Miller, Charles D. – <dfn>Algebra and Trigonometry</dfn> <span class="loc">(QA154.2)</span></li>

<li>Sokal, Alan and Bricmont, Jean – <dfn>Fashionable Nonsense: Postmodern Intellectuals' Abuse of Science</dfn> <span class="loc">(QA175)</span></li>

<li>Neugebauer, Otto – <dfn>The Exact Sciences in Antiquity</dfn> <span class="loc">(QA22)</span></li>

<li>Bharati Krsna Thirthaji Maharaja – <dfn>Vedic Mathematics</dfn> <span class="loc">(QA27.I4)</span></li>

<li>Christian, Robert R. – <dfn>Introduction to Logic and Sets</dfn> <span class="loc">(QA248)</span></li>

<li>Davis, Morton D. – <dfn>Game Theory: A Nontechnical Introduction</dfn> <span class="loc">(QA269)</span></li>

<li>Friedman, Avner – <dfn>Differential Games</dfn> <span class="loc">(QA272)</span></li>

<li>Takahashi, Shin – <dfn>The Manga Guide to Statistics</dfn> <span class="loc">(QA276)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 1-10</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 10-15 and Appendices</dfn> <span class="loc">(QA303)</span></li>

<li>Smith, Edward S. and Salkover, Meyer and Justive, Howard K. – <dfn>Unified Calculus</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny – <dfn>Calculus with Analytic Geometry</dfn> <span class="loc">(QA33)</span></li>

<li>Sperling, Abraham and Stuart, Monroe – <dfn>Mathematics (Made Simple Self-Teaching Library)</dfn> <span class="loc">(QA39.2)</span></li>

<li>Horblit, Marcus and Nielson, Kaj L. – <dfn>Problems in Plane Geometry with Solutions</dfn> <span class="loc">(QA459)</span></li>

<li>Shively, Levi S. – <dfn>Modern Geometry</dfn> <span class="loc">(QA473)</span></li>

<li>Nelson, Alfred L. and Folley, Karl W. – <dfn>Plane and Spherical Trigonometry</dfn> <span class="loc">(QA531.N45)</span></li>

<li>Love, Clyde E. – <dfn>Analytic Geometry</dfn> <span class="loc">(QA551)</span></li>

<li>Hutton, Graham – <dfn>Programming in Haskell</dfn> <span class="loc">(QA76.62)</span></li>

<li>Kernighan, Brian W. and Ritchie, Dennis M. – <dfn>The C Programming Language</dfn> <span class="loc">(QA76.73.C15)</span></li>

<li>Barski, Conrad – <dfn>Land of Lisp</dfn> <span class="loc">(QA76.76.C672)</span></li>

<li>Hofstadter, Douglas – <dfn>Gödel, Escher, Bach</dfn> <span class="loc">(QA9.8)</span></li>

<li>Emmet, E. R. – <dfn>Brain Puzzler's Delight</dfn> <span class="loc">(QA95)</span></li>

<li>Emmet, E. R. – <dfn>Puzzles for Pleasure</dfn> <span class="loc">(QA95)</span></li>

<li>Gardner, Martin – <dfn>aha! Gotcha, Paradoxes to puzzle and delight</dfn> <span class="loc">(QA95)</span></li>

<li>Heafford, Philip – <dfn>The Math Entertainer</dfn> <span class="loc">(QA95)</span></li>

</ul>
<h2 id="qb-qr-other-sciences">QB-QR: Other Sciences</h2>
<ul class="booklist">
<li>Hawking, Stephen W. – <dfn>A Brief History of Time</dfn> <span class="loc">(QB981)</span></li>

<li>Lerner, Eric – <dfn>The Big Bang Never Happened</dfn> <span class="loc">(QB991.B54)</span></li>

<li>McEvoy, J. P. and Zarate, Oscar – <dfn>Quantum Theory, A Graphic Guide</dfn> <span class="loc">(QC173.98)</span></li>

<li>Booker, Christopher – <dfn>The Real Global Warming Disaster</dfn> <span class="loc">(QC981.8.G56)</span></li>

<li>Greenburg, Arthur – <dfn>From Alchemy to Chemistry in Picture and Story</dfn> <span class="loc">(QD11)</span></li>

<li>Valentine, Basil – <dfn>Of Natural and Supernatural Things: Also, of the First Tincture, Root, and Spirit of Metals and Minerals: How the Same are Conceived, Generated, Brought Forth, Changed and Augmented</dfn> <span class="loc">(QD25)</span></li>

<li>Watson, James – <dfn>The Double Helix</dfn> <span class="loc">(QH31.D434)</span></li>

<li>Fodor, Jerry and Piattelli Palmarini, Massimo – <dfn>What Darwin Got Wrong</dfn> <span class="loc">(QH375)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Kadans, Joseph M. – <dfn>Modern Encyclopedia of Herbs</dfn> <span class="loc">(QK99.A1)</span></li>

<li>McFarland, J. Horace – <dfn>Getting Acquainted with Trees</dfn> <span class="loc">(QK482)</span></li>

<li>Kurzweil, Ray – <dfn>The Singularity is Near</dfn> <span class="loc">(QP376)</span></li>

<li>Kandel, Eric R. and Schwartz, James H. and Jessell, Thomas M. – <dfn>Essentials of Neural Science and Behavior</dfn> <span class="loc">(QP355.2)</span></li>

</ul>
<h2 id="r-medicine">R: Medicine</h2>
<ul class="booklist">
<li>FC&amp;A – <dfn>The Folk Remedy Encyclopedia: Olive Oil, Vinegar, Honey and 1,001 Other Home Remedies</dfn> <span class="loc">(R733)</span></li>

<li><dfn>Better Homes and Gardens Family Medical Guide</dfn> <span class="loc">(RC81.A2)</span></li>

<li><dfn>The Encyclopedia of Common Diseases</dfn> <span class="loc">(RC81.A2)</span></li>

</ul>
<h2 id="s-t-agriculture-and-technology">S-T: Agriculture and Technology</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=YRNKjQg6y-c"><img src="/pix/salatin.jpg"></a></figure>

<ul class="booklist">
<li>Mollison, Bill – <dfn>Introduction to Permaculture</dfn> <span class="loc">(S494.5.P47)</span></li>

<li>Salatin, Joel – <dfn>Everything I Want to Do Is Illegal</dfn> <span class="loc">(S605.5)</span></li>

<li>David the Good – <dfn>Totally Crazy Easy Florida Gardening</dfn></li>

<li>Seymour, John – <dfn>The Complete Book of Self-Sufficiency</dfn> <span class="loc">(S605.5)</span></li>

<li>Cobleigh, Rolfe – <dfn>Handy Farm Devices and How to Make Them (2 copies)</dfn> <span class="loc">(S676)</span></li>

<li>Seymour, John – <dfn>Gardener's Delight</dfn> <span class="loc">(SB322)</span></li>

<li>Seymour, John – <dfn>The Self-Sufficient Gardener</dfn> <span class="loc">(SB324.3)</span></li>

<li>Haring, Elda – <dfn>The Seedling Handbook</dfn> <span class="loc">(SB405)</span></li>

<li>Abraham, George – <dfn>The Green Thumb Garden Handbook</dfn> <span class="loc">(SB453)</span></li>

<li><dfn>Reader's Digest Illustrated Guide to Gardening</dfn> <span class="loc">(SB453)</span></li>

<li>Kaczynski, Theodore John – <dfn>Technological Slavery</dfn> <span class="loc">(T14.5)</span></li>

<li>Kaczynski, Theodore John – <dfn>Anti-Tech Revolution: Why and How</dfn> <span class="loc">(T14.5)</span></li>

<li>Macaulay, David and Ardleym Neil – <dfn>The Way Things Work</dfn> <span class="loc">(T47)</span></li>

<li>Slater, Robert and Li, Ling and Li, Wen – <dfn>Portraits in Silicon</dfn> <span class="loc">(TK7885.2)</span></li>

<li>Bishop, Michael and Zimmerman, Holmes – <dfn>Detailing Cars and Trucks</dfn> <span class="loc">(TL152)</span></li>

<li>Allaby, Michael and Lovelock, James – <dfn>The Greening of Mars</dfn> <span class="loc">(TL795.7)</span></li>

<li>Abbey, Barbara – <dfn>The Complete Book of Knitting</dfn> <span class="loc">(TT820)</span></li>

<li>Bishop, Jack – <dfn>Vegetables Every Day</dfn> <span class="loc">(TX801)</span></li>

<li>Lo, Kenneth – <dfn>Chinese Regional Cooking</dfn> <span class="loc">(TX724.5.C5)</span></li>

</ul>
<h2 id="books-as-of-yet-unsorted">Books as of yet unsorted</h2>
<ul class="booklist">
<li>Seb Falk – <dfn>The Light Ages: The Surprising Story of Medieval Science</dfn></li>

<li><dfn>The Penny Catechism: A Catechism of Christian Doctrine</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese Reader, Part 1</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese</dfn></li>

<li>Flame Tree Publishing – <dfn>Gothic Fantasy: Lost Worlds Short Stories</dfn></li>

<li>Lee, Christopher – <dfn>This Sceptered Isle 55 BC to 1901</dfn></li>

<li>Malice, Michael – <dfn>Dear Reader</dfn></li>

<li>McCloskey, Deirdre N. – <dfn>Economic Writing</dfn></li>

<li>Meyer, Jerome S. – <dfn>The Provocative Puzzler</dfn></li>

<li>Parikh, Prashant – <dfn>Language and Equilibrium</dfn></li>

<li>Reed, Lawrence W. – <dfn>Great Myths of the Great Depression</dfn></li>

<li><dfn>Using HTML4, Java 1.1, and Javascript 1.2</dfn></li>

<li>Valizadeh, Roosh – <dfn>Game</dfn></li>

<li>Vikernes, Varg – <dfn>MYFAROG 2.6</dfn></li>

</ul>
<div style="clear:both" class="taglist">Read related articles:<br><a id="tag_personal" href="https://lukesmith.xyz/tags/personal">Personal</a> · <a id="tag_science" href="https://lukesmith.xyz/tags/science">Science</a> · <a id="tag_tradition" href="https://lukesmith.xyz/tags/tradition">Tradition</a> · <a id="tag_lifestyle" href="https://lukesmith.xyz/tags/lifestyle">Lifestyle</a> · <a id="tag_philosophy" href="https://lukesmith.xyz/tags/philosophy">Philosophy</a></div>
<br clear="both">
</article>
</main>
<footer>
	<a href="https://lukesmith.xyz">https://lukesmith.xyz</a>

	<p>
	<img class="lw" src="/pix/btc.svg">Bitcoin (<a href="/pix/btc-logo.png">QR</a>): <code>bc1qkyvknjap3cjtgfqd5qwc0q2ygry7nep7d4t57y</code>
	<br>
	<img class="lw" src="/pix/xmr.svg">Monero (<a href="/pix/xmr-logo.png">QR</a>): <code class="crypto">48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh</code>
	</p><p><a href="/index.xml"><img src="/rss.svg" style="max-height:1.5em" alt="RSS Feed" title="Subscribe via RSS for updates."></a>
</p></footer>
<a href="https://lukesmith.xyz">https://lukesmith.xyz</a>
<p>
	<img class="lw" src="/pix/btc.svg">Bitcoin (<a href="/pix/btc-logo.png">QR</a>): <code>bc1qkyvknjap3cjtgfqd5qwc0q2ygry7nep7d4t57y</code>
	<br>
	<img class="lw" src="/pix/xmr.svg">Monero (<a href="/pix/xmr-logo.png">QR</a>): <code class="crypto">48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh</code>
	</p>
<img class="lw" src="/pix/btc.svg">
Bitcoin (
<a href="/pix/btc-logo.png">QR</a>
):
<code>bc1qkyvknjap3cjtgfqd5qwc0q2ygry7nep7d4t57y</code>
<br>
<img class="lw" src="/pix/xmr.svg">
Monero (
<a href="/pix/xmr-logo.png">QR</a>
):
<code class="crypto">48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh</code>
48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh
<code class="crypto">48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh</code>
<p>
	<img class="lw" src="/pix/btc.svg">Bitcoin (<a href="/pix/btc-logo.png">QR</a>): <code>bc1qkyvknjap3cjtgfqd5qwc0q2ygry7nep7d4t57y</code>
	<br>
	<img class="lw" src="/pix/xmr.svg">Monero (<a href="/pix/xmr-logo.png">QR</a>): <code class="crypto">48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh</code>
	</p>
<p><a href="/index.xml"><img src="/rss.svg" style="max-height:1.5em" alt="RSS Feed" title="Subscribe via RSS for updates."></a>
</p>
<a href="/index.xml"><img src="/rss.svg" style="max-height:1.5em" alt="RSS Feed" title="Subscribe via RSS for updates."></a>
<img src="/rss.svg" style="max-height:1.5em" alt="RSS Feed" title="Subscribe via RSS for updates.">
<a href="/index.xml"><img src="/rss.svg" style="max-height:1.5em" alt="RSS Feed" title="Subscribe via RSS for updates."></a>
<p><a href="/index.xml"><img src="/rss.svg" style="max-height:1.5em" alt="RSS Feed" title="Subscribe via RSS for updates."></a>
</p>
<footer>
	<a href="https://lukesmith.xyz">https://lukesmith.xyz</a>

	<p>
	<img class="lw" src="/pix/btc.svg">Bitcoin (<a href="/pix/btc-logo.png">QR</a>): <code>bc1qkyvknjap3cjtgfqd5qwc0q2ygry7nep7d4t57y</code>
	<br>
	<img class="lw" src="/pix/xmr.svg">Monero (<a href="/pix/xmr-logo.png">QR</a>): <code class="crypto">48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh</code>
	</p><p><a href="/index.xml"><img src="/rss.svg" style="max-height:1.5em" alt="RSS Feed" title="Subscribe via RSS for updates."></a>
</p></footer>
<body>
<main>
<a href="/"><header>
	<h1 id="tag_My Personal Library">My Personal Library</h1>
</header></a>
<article>
<p>This is a list of the books in my personal library. If you have any
questions or want me to review any of them, email me
(<a href="mailto:luke@lukesmith.xyz">luke@lukesmith.xyz</a>).</p>
<p>I haven't read every book here, nor do I own all the books I've read
or like. I also don't necessarily like all the books I own.</p>
<p>Check out <a href="https://notrelated.xyz">my podcast, <em>Not Related!</em></a>
for some book reviews and other things. Books I've talked about in one
way or another in the podcast will have a link to that episode.</p>
<h2 id="-lindypressnet-books">🆕 LindyPress.net Books</h2>
<p>Note that now I am reprinting out-of-print works at
<a href="https://lindypress.net">LindyPress.net</a>. You can buy any of these books
yourself if you'd like. (Most of them are pretty exclusive in that I'm
the only one reprinting them.)</p>
<ul>
<li>Pseudo-Aristotle – <a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a></li>
<li><a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a></li>
<li>Isidore of Seville – <a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a></li>
<li>Roger Bacon ‐ <a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a></li>
<li>Marcus Aurelius – <a href="https://lindypress.net/book?pk=2">Meditations</a></li>
<li><a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a></li>
</ul>
<p>(These are at the top since I don't know if anyone has given them Library of
Congress numbers, and I suppose as an ad.)</p>
<h2 id="a-bd-general-works-philosophy-logic-speculative-philosophy">A-BD: General Works, Philosophy, Logic, Speculative Philosophy</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hCVdCS0t46I"><img src="/pix/searle.jpg" title="Searle (actually literally) did nothing wrong."></a></figure>

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
<h2 id="bm-bx-specific-religions-and-theology">BM-BX: Specific Religions and Theology</h2>

<figure class="resright"><img src="/pix/biglot.jpg" title="A Greek and Latin biglottic Bible"></figure>

<ul class="booklist">
<li><dfn>'תְּהִלַּת ה</dfn> <span class="loc">(BM675/D3)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Key to Theosophy</dfn> <span class="loc">(BP561)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Voice of Silence</dfn> <span class="loc">(BP561)</span></li>

<li>Wright, Stuart – <dfn>Armageddon in Waco</dfn> <span class="loc">(BP605.B62)</span></li>

<li>Lewis, C. S. – <dfn>Mere Christianity</dfn> <span class="loc">(BR123)</span></li>

<li>Lewis, C. S. – <dfn>The Screwtape Letters</dfn> <span class="loc">(BR125)</span></li>

<li>Reardon, Patrick Henry – <dfn>Christ in the Psalms</dfn> <span class="loc">(BS1430.4)</span></li>

<li>Leithart, Peter J. – <dfn>Solomon Among the Postmoderns</dfn> <span class="loc">(BS1475.52)</span></li>

<li>Porter, J. R. – <dfn>The Lost Bible</dfn> <span class="loc">(BS1700)</span></li>

<li>Heiser, Michael – <dfn>Reversing Hermon: Enoch, the Watchers and the Forgotten Mission of Jesus Christ</dfn> <span class="loc">(BS1830.E7)</span></li>

<li><dfn>The New Oxford Annotated Bible</dfn> <span class="loc">(BS191.5.A1)</span></li>

<li><dfn>The New English Bible</dfn> <span class="loc">(BS192.A1)</span></li>

<li>Montano, Arias and Leudsen, Johann – <dfn>Greek-Latin Parallel New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>Pocket Interlinear New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>The New International Dictionary of New Testament Theology (3 Volumes)</dfn> <span class="loc">(BS2312)</span></li>

<li><dfn>Ἡ Καινὴ Διαθήκη</dfn> <span class="loc">(BS2312)</span></li>

<li>Kümmel, Werner Georg – <dfn>Introduction to the New Testament</dfn> <span class="loc">(BS2330)</span></li>

<li>Aland, Kurt – <dfn>Synopsis Quattuor Evangeliorum</dfn> <span class="loc">(BS2560.A2)</span></li>

<li>Mack. Burton L. – <dfn>A Myth of Innocence</dfn> <span class="loc">(BS2585.2)</span></li>

<li>Ehrman, Bart D. – <dfn>Lost Christianities: The Battles for Scriptures and the Faiths We Never Knew</dfn> <span class="loc">(BS2840.E4)</span></li>

<li>Luther, Martin – <dfn>Luther's Small Catechism with Additions Including the Augsburg Confession</dfn> <span class="loc">(BR331.K64)</span></li>

<li>Strong, James – <dfn>Strong's Exhaustive Concordance of the Bible with Hebrew and Greek Dictionaries</dfn> <span class="loc">(BS425)</span></li>

<li><dfn>Illustrated Dictionary and Concordance of the Bible</dfn> <span class="loc">(BS440)</span></li>

<li>McDowell, Josh – <dfn>The New Evidence that Demands a Verdict</dfn> <span class="loc">(BS480)</span></li>

<li>Laymon, Charles M. – <dfn>The Interpreter's One-Volume Commentary on the Bible</dfn> <span class="loc">(BS491.2)</span></li>

<li>Cross, John R. – <dfn>The Stranger on the Road to Emmaus</dfn> <span class="loc">(BS511.2)</span></li>

<li><dfn>Reader's Digest Mysteries of the Bible; the Enduring Questions of the Scriptures</dfn> <span class="loc">(BS538)</span></li>

<li>Smith, Brendan Powell – <dfn>The Brick Bible</dfn> <span class="loc">(BS550.3)</span></li>

<li>Kent, Paul and McLaughlan, David – <dfn>Know Your Bible: All 66 Books Explained and Applied</dfn> <span class="loc">(BS593)</span></li>

<li><dfn>Septuagint with Apocrypha</dfn> <span class="loc">(BS742)</span></li>

<li><dfn>Biblia Sacra Vulgata</dfn> <span class="loc">(BS75)</span></li>

<li>Newman, John Henry – <dfn>An Essay on the Development of Christian Doctrine</dfn> <span class="loc">(BT21)</span></li>

<li>Robinson, James M. – <dfn>The Nag Hammadi Library</dfn> <span class="loc">(BT1391)</span></li>

<li>Lewis, C. S. – <dfn>Surprised by Joy: The Shape of My Early Life</dfn> <span class="loc">(BV4935.L43)</span></li>

<li>Carman, Stephen L. and Owen, Bob – <dfn>Quest: The Story of an Aerospace Engineer who Challenged God to Prove Himself</dfn> <span class="loc">(BV4930)</span></li>

<li>Ware, Timothy – <dfn>The Orthodox Church</dfn> <span class="loc">(BX106)</span></li>

<li>Aveling, J. C. H. – <dfn>The Jesuits</dfn> <span class="loc">(BX3706.2)</span></li>

<li><dfn>The Book of Common Prayer</dfn> <span class="loc">(BX5145)</span></li>

<li><dfn>Five Great Encyclicals: Labor, Education, Marriage, Reconstructing the Social Order, Atheistic Communism</dfn> <span class="loc">(BX860)</span></li>

</ul>
<h2 id="c-auxiliary-sciences-of-history">C: Auxiliary Sciences of History</h2>
<ul class="booklist">
<li>Graeber, David and Wengrow, David – <dfn>The Dawn of Everything: A New History of Humanity</dfn> <span class="loc">(CB19)</span></li>

<li>McNeill, William H. – <dfn>The Rise of the West: A History of the Human Community</dfn> <span class="loc">(CB59)</span></li>

<li>Sitchin, Zecharia – <dfn>The 12th Planet</dfn> <span class="loc">(CB156)</span></li>

<li>Rohl, David – <dfn>The Lords of Avaris: Uncovering the Legendary Origins of Western Civilization</dfn> <span class="loc">(CB245)</span> <a href="https://notrelated.xyz/#02.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Casson, Lionel and Clairborne, Robert and Fagan, Brian and Karp, Walter – <dfn>Mysteries of the Past</dfn> <span class="loc">(CB311)</span></li>

<li>Fisher, Marshall John and Fisher, David E. – <dfn>Mysteries of Lost Empires</dfn> <span class="loc">(CB311)</span></li>

<li>Hawkes, Jacquetta – <dfn>The Atlas of Early Man</dfn> <span class="loc">(CB311)</span></li>

<li>Platt, Richard and Riddell, Chris – <dfn>Castle Diary</dfn> <span class="loc">(CB351)</span></li>

<li>Cahill, Thomas – <dfn>Mysteries of the Middle Ages</dfn> <span class="loc">(CB351)</span></li>

</ul>
<h2 id="d-world-history">D: World History</h2>

<figure class="resright"><img src="/pix/racehutton.jpg" title="Hutton's book on the Third Reich"></figure>

<ul class="booklist">
<li>Malesky, Kee – <dfn>All Facts Considered, the Essential Library of Inessential Knowledge</dfn> <span class="loc">(D10)</span></li>

<li>Evola, Julius – <dfn>Revolt Against the Modern World</dfn> <span class="loc">(D16.8)</span></li>

<li>Epstein, Steven A. – <dfn>An Economic and Social History of Later Medieval Europe, 1000-1500</dfn> <span class="loc">(D117)</span></li>

<li>Pirenne, Henri – <dfn>A History of Europe</dfn> <span class="loc">(D117)</span></li>

<li>Cantor, Nroman F. – <dfn>Medieval History: The Life and Death of a Civilization</dfn> <span class="loc">(D118)</span></li>

<li>Roberts, J. M. – <dfn>New History of the World</dfn> <span class="loc">(D20)</span></li>

<li>Mann, Charles C. – <dfn>1493, Uncovering the New World Columbus Created</dfn> <span class="loc">(D228)</span></li>

<li>Rogan, Eugene L. – <dfn>The FAll of the Ottomans: The Great War in the Middle East</dfn> <span class="loc">(D566)</span></li>

<li>Sanborn, Frederick R. – <dfn>Design for War: A Study of Secret Power Politics</dfn> <span class="loc">(D742.U5)</span></li>

<li>Cheyney, Edward P. – <dfn>A Short History of England</dfn> <span class="loc">(DA32)</span></li>

<li>Thomas, Charles – <dfn>Celtic Britain</dfn> <span class="loc">(DA140)</span></li>

<li>Sellar, W.C. &amp; Yeatman R.J. – <dfn>1066 and All That</dfn> <span class="loc">(DA33)</span></li>

<li>Freeman, John and Sharpe, Sue – <dfn>This Beautiful Land: Britain</dfn> <span class="loc">(DA632)</span></li>

<li>Hutton, Christopher – <dfn>Race and the Third Reich</dfn> <span class="loc">(DD253)</span></li>

<li>Tacitus, C. Cornellius – <dfn>Annales et Historiae</dfn> <span class="loc">(DG207.T3)</span></li>

<li>Shirer, William L. – <dfn>The Rise and Fall of the Third Reich</dfn> <span class="loc">(DD256.5)</span></li>

<li>MacDonald, Kevin – <dfn>The Culture of Critique: An Evolutionary Analysis of Jewish Involvement in Twentieth-Century Intellectual and Political Movements</dfn> <span class="loc">(DS143)</span></li>

<li>Ford, Henry Sr. – <dfn>The International Jew: The World's Foremost Problem</dfn> <span class="loc">(DS145)</span></li>

<li>Ali, Tariq – <dfn>The Duel: Pakistan on the Flight Path of American Power</dfn> <span class="loc">(DS384)</span></li>

<li>De Bary, William Theodore – <dfn>The Sources of Indian Tradition</dfn> <span class="loc">(DS423)</span></li>

<li>Keay, John – <dfn>India, A History</dfn> <span class="loc">(DS451)</span></li>

<li>Ebrey, Patricia Buckley – <dfn>Cambridge Illustrated History of China</dfn> <span class="loc">(DS706)</span></li>

<li>National Geographic Society – <dfn>Journey into China</dfn> <span class="loc">(DS712)</span></li>

</ul>
<h2 id="e-f-history-of-the-americas">E-F: History of the Americas</h2>

<figure class="resright"><img src="/pix/foxfire.jpg"></figure>

<ul class="booklist">
<li>Hancock, Graham – <dfn>America Before: The Key to Earth's Lost Civilization</dfn> <span class="loc">(E61)</span></li>

<li>Little, Gregory – <dfn>Path of Souls: The Native American Death Journey: Cygnus, Orion, the Milky Way, Giant Skeletons in Mounds, &amp; the Smithsonian</dfn> <span class="loc">(E98.M8)</span></li>

<li>Mooney, James – <dfn>Myths of the Cherokee</dfn> <span class="loc">(E99.C5)</span></li>

<li>Greenblatt, Stephen – <dfn>New World Encounters</dfn> <span class="loc">(E141)</span></li>

<li>Fischer, David Hackett – <dfn>Albion's Seed: Four British Folkways in America</dfn> <span class="loc">(E169.1)</span> <a href="https://notrelated.xyz/#01.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Sowell, Thomas – <dfn>Ethnic America</dfn> <span class="loc">(E184.A1)</span></li>

<li>Hurmence, Belinda – <dfn>Before Freedom: 48 Oral Histories of Former North and South Carolina Slaves</dfn> <span class="loc">(E444)</span></li>

<li>Adams, Nehemiah – <dfn>A South-side View of Slavery: or Three Months at the South in 1854</dfn> <span class="loc">(E449)</span></li>

<li>Parsons, Charles Grandison – <dfn>An Inside View of Slavery; or A Tour Among the Planters</dfn> <span class="loc">(E449)</span></li>

<li>Long, A. L. – <dfn>Memoirs of Robert E. Lee</dfn> <span class="loc">(E467.1.L4)</span></li>

<li>Henry, Robert Selph – <dfn>The Story of the Confederacy</dfn> <span class="loc">(E487)</span></li>

<li>Mann, Charles C. – <dfn>1491, New Revelations of the Americas Before Columbus</dfn> <span class="loc">(E61)</span></li>

<li>Wharton, H. M. – <dfn>War Songs and Poems of the Southern Confederacy, 1861-1865: a Collection of the Most Popular and Impressive Songs and Poems of War Times, Dear to Every Southern Heart</dfn> <span class="loc">(E647)</span></li>

<li><dfn>The Blue Book of the John Birch Society</dfn> <span class="loc">(E743.5)</span></li>

<li>Stormer, John A. – <dfn>The Death of a Nation</dfn> <span class="loc">(E743.5)</span></li>

<li>Ramo, Joshua Cooper – <dfn>The Age of the Unthinkable</dfn> <span class="loc">(E902)</span></li>

<li>de las Casas, Bartolomé – <dfn>Brevisima relación de la destrución de las Indias</dfn> <span class="loc">(F1411)</span></li>

<li><dfn>The Foxfire Book</dfn> <span class="loc">(F291.2)</span></li>

<li><dfn>The Foxfire Book 2</dfn> <span class="loc">(F291.2)</span></li>

</ul>
<h2 id="g-geography-anthropology-recreation">G: Geography, Anthropology, Recreation</h2>
<ul class="booklist">
<li>Winer, Richard – <dfn>Ghost Ships: True Stories of Nautical Nightmares, Hauntings, and Disasters</dfn> <span class="loc">(G525)</span></li>

<li><dfn>National Geographic Collegiate Atlas of the World</dfn> <span class="loc">(G1021)</span></li>

<li>Wells, Spencer – <dfn>Pandora's Seed: The Unforeseen Cost of Civilization</dfn> <span class="loc">(GF75)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cochran, Gregory and Harpending, Henry – <dfn>the 10,000 Explosion: How Civilization Accelerated Human Evolution</dfn> <span class="loc">(GN281.4)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cremo, Michael A. &amp; Thompson, Ricahrd L. – <dfn>Forbidden Archaeology: The Hidden History of the Human Race</dfn> <span class="loc">(GN741)</span></li>

<li>Hancock, Graham – <dfn>Magicians of the Gods: The Forgotten Wisdom of Earth's Lost Civilization</dfn> <span class="loc">(GN751)</span></li>

<li>Cayce, Hugh Lynn – <dfn>Edgar Cayce on Atlantis</dfn> <span class="loc">(GN751.C35)</span></li>

<li>Marshack, Alexander – <dfn>The Roots of Civilization: The Cognitive Beginnings of Man's First Art, Symbol and Notation</dfn> <span class="loc">(GN772)</span></li>

<li>Bord, Janet and Bord, Colin – <dfn>Prehistoric Britain from the Air</dfn> <span class="loc">(GN805)</span></li>

<li>Bruce, Annette J. – <dfn>More Tellable Cracker Tales</dfn> <span class="loc">(GR110.F5)</span></li>

</ul>
<h2 id="h-social-sciences">H: Social Sciences</h2>
<p>
</p><figure class="resright"><img src="/pix/democracy.jpg"></figure>


<figure class="resright"><img src="/pix/pike.jpg"></figure>
<p></p>
<ul class="booklist">
<li>Greenspan, Alan – <dfn>The Age of Turbulence</dfn> <span class="loc">(HB119.G74)</span></li>

<li>Hazlitt, Hentry – <dfn>Economics in One Lesson (two copies)</dfn> <span class="loc">(HB171)</span></li>

<li>Keynes, John Maynard – <dfn>The General Theory of Employment, Interest and Money</dfn> <span class="loc">(HB171)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Rothbard, Murray – <dfn>Man, Economy and State with Power and Market</dfn> <span class="loc">(HB171)</span></li>

<li>von Mises, Ludwig – <dfn>Economic Policy</dfn> <span class="loc">(HB171)</span></li>

<li>Boulding, Kenneth E. – <dfn>Economic Analysis</dfn> <span class="loc">(HB171.5)</span></li>

<li>Goodman, Kennard E. and Moore, William L. – <dfn>Economics in Everyday Life</dfn> <span class="loc">(HB171.5)</span></li>

<li>Pindyck, Robert S. and Rubinfeld, Daniel L. – <dfn>Microeconomics</dfn> <span class="loc">(HB172)</span></li>

<li>Fisher, David Hackett – <dfn>The Great Wave: Price Revolutions and the Rhythm of History</dfn> <span class="loc">(HB231)</span></li>

<li>Soros, George – <dfn>The Crash of 2008 and What It Means</dfn> <span class="loc">(HB3722)</span> <a href="https://notrelated.xyz/#02.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Keen, Steve – <dfn>Debunking Economics: The Naked Emperor Dethroned?</dfn> <span class="loc">(HB71)</span></li>

<li>Krugman, Paul – <dfn>The Accidental Theorist</dfn> <span class="loc">(HB74.5)</span></li>

<li>Hoppe, Hans Hermann – <dfn>Democracy: The God That Failed: The Economics and Politics of Monarchy, Democracy and Natural Law</dfn> <span class="loc">(HB74.P65)</span></li>

<li>Ekelund, Robert B. Jr. and Hébert, Robert F – <dfn>A History of Economic Theory and Method</dfn> <span class="loc">(HB75)</span></li>

<li>Buchholz, Todd G. – <dfn>New Ideas from Dead Economists, an Introduction to Modern Economic Thought</dfn> <span class="loc">(HB76)</span></li>

<li>Heilbroner, Robert L. – <dfn>The Worldly Philosophers</dfn> <span class="loc">(HB76)</span></li>

<li>Paul Erlich – <dfn>The Population Bomb</dfn> <span class="loc">(HB875.E35)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Palmer, Tom G. – <dfn>After the Welfare State</dfn> <span class="loc">(HB99.3)</span></li>

<li>Krugman, Paul – <dfn>Peddling Prosperity</dfn> <span class="loc">(HB99.7)</span></li>

<li>Walton, Gary M. and Rockoff, Hugh – <dfn>History of the American Economy</dfn> <span class="loc">(HC103)</span></li>

<li>Krugman, Paul – <dfn>The Great Unravelling</dfn> <span class="loc">(HC106)</span></li>

<li>Krugman, Paul – <dfn>The Conscience of a Liberal</dfn> <span class="loc">(HC110.I5)</span></li>

<li>Clark, Gregory – <dfn>A Farewell to Alms</dfn> <span class="loc">(HC21)</span></li>

<li>Easterly, William – <dfn>The Elusive Quest for Growth</dfn> <span class="loc">(HC59.72.P6)</span></li>

<li>Simon, Julian L. and Kahn, Herman – <dfn>The Resourceful Earth</dfn> <span class="loc">(HC59.R445)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Dixit, Avinash K. and Nalebuff, Barry J. – <dfn>Thinking Strategically, The Competitive Edge in Business, Politics, and Everyday Life</dfn> <span class="loc">(HD30.28)</span></li>

<li>Adams, Scott – <dfn>The Dilbert Principle</dfn> <span class="loc">(HD31)</span></li>

<li>Ehrenreich, Barbara – <dfn>Nickel and Dimed</dfn> <span class="loc">(HD4918)</span></li>

<li>Thiel, Peter – <dfn>Zero to One: Notes on Start-Ups, or How to Build the Future</dfn> <span class="loc">(HD62.5)</span></li>

<li>Montgomery, David – <dfn>Beyond Equality: Labor and the Radical Republicans 1862-1872</dfn> <span class="loc">(HD8076)</span></li>

<li>Caplan, Bryan – <dfn>The Myth of the Rational Voter: Why Democracies Choose Bad Policies</dfn> <span class="loc">(HD87)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bhagwati, Jagdish – <dfn>In Defense of Globalization</dfn> <span class="loc">(HF1359)</span></li>

<li>Krugman, Paul and Obstfield, Maurice – <dfn>International Economics</dfn> <span class="loc">(HF1359)</span></li>

<li>Lechner, Frank J. and Boli, John – <dfn>The Globalization Reader</dfn> <span class="loc">(HF1359)</span></li>

<li>Myrdal, Gunnar – <dfn>Beyond the Welfare State</dfn> <span class="loc">(HF1411)</span></li>

<li>Graeber, David – <dfn>Bullshit Jobs: A Theory</dfn> <span class="loc">(HF5549.5.J63)</span> <a href="https://notrelated.xyz/#02.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Soros, George – <dfn>In Defense of Open Society</dfn> <span class="loc">(HG172.S63)</span></li>

<li>Boortz, Neal and Linder, John – <dfn>The Fairtax Book: Saying Goodbye to the Income Tax and the IRS</dfn> <span class="loc">(HJ4652)</span></li>

<li>Stove, David – <dfn>Darwinian Fairytales</dfn> <span class="loc">(HM106)</span></li>

<li>O'Brien, Jodi – <dfn>The Production of Reality</dfn> <span class="loc">(HM1033)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Skin in the Game</dfn> <span class="loc">(HM1101)</span></li>

<li>Berne, Eric – <dfn>Games People Play</dfn> <span class="loc">(HM1106)</span></li>

<li>Pinker, Steven – <dfn>The Better Angels of Our Nature</dfn> <span class="loc">(HM1116)</span></li>

<li>Kropotkin, Peter – <dfn>Mutual Aid: A Factor of Evolution</dfn> <span class="loc">(HM131)</span></li>

<li>Diamond, Jared – <dfn>Guns, Germs and Steel</dfn> <span class="loc">(HM206)</span></li>

<li>Bork, Robert H. – <dfn>Slouching Towards Gomorrah: Modern Liberalism and American Decline</dfn> <span class="loc">(HN59.2)</span></li>

<li>Arnold, Matthew – <dfn>Culture and Anarchy</dfn> <span class="loc">(HN389)</span></li>

<li>Jones, E. Michael – <dfn>Libido Dominandi: Sexual Liberation and Political Control</dfn> <span class="loc">(HQ472.U6)</span></li>

<li>Eisler, Riane – <dfn>The Chalice and the Blade, Our History, Our Future</dfn> <span class="loc">(HQ1075)</span></li>

<li>Harris, Judith Rich – <dfn>The Nurture Assumption</dfn> <span class="loc">(HQ772)</span></li>

<li>Beuerlein, Mark – <dfn>The Dumbest Generation</dfn> <span class="loc">(HQ799.7)</span></li>

<li>Street, Oliver Day – <dfn>Symbolism of the Three Degrees</dfn> <span class="loc">(HS425)</span></li>

<li><dfn>Morals and Dogma of the Ancient and Accepted Scottish Rite of Freemasonry</dfn> <span class="loc">(HS767)</span></li>

<li><dfn>The 9/11 Commission Report: Final Report of the National Commission on Terrorist Attacks upon the United States</dfn> <span class="loc">(HV6432.7)</span></li>

<li>Engels, Frederick – <dfn>Socialism: Utopian and Scientific</dfn> <span class="loc">(HX276)</span></li>

<li>Hayek, F. A. – <dfn>The Intellectuals and Socialism</dfn> <span class="loc">(HX528)</span></li>

<li>More, Thomas – <dfn>Utopia</dfn> <span class="loc">(HX810.5)</span></li>

<li>Stringham, Edward P. – <dfn>Anarchy and the Law</dfn> <span class="loc">(HX833)</span></li>

<li>Schumpeter, Joseph Alois – <dfn>Capitalism, Socialism and Democracy</dfn> <span class="loc">(HX86)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bastiat, Frederic – <dfn>The Law</dfn> <span class="loc">(HX87)</span></li>

</ul>
<h2 id="j-k-political-science-and-law">J-K: Political Science and Law</h2>

<figure class="resright"><img src="/pix/archeofuturism.jpg"></figure>

<ul class="booklist">
<li>Faye, Guillaume – <dfn>Archeofuturism: European Visions of the Post-Catastrophic Age</dfn> <span class="loc">(JA84.F8)</span></li>

<li>Plato – <dfn>The Republic</dfn> <span class="loc">(JC71)</span></li>

<li>Machiavelli, Niccolò – <dfn>The Prince and Other Writings</dfn> <span class="loc">(JC143)</span></li>

<li>Hobbes, Thomas – <dfn>Leviathan</dfn> <span class="loc">(JC153)</span></li>

<li>Filmer, Robert – <dfn>Patriarcha, or, The Natural Power of Kings</dfn> <span class="loc">(JC153.F48)</span></li>

<li>Samons, Loren J. – <dfn>What's Wrong with Democracy?</dfn> <span class="loc">(JC421)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Mill, John Stewart – <dfn>On Liberty</dfn> <span class="loc">(JC585)</span></li>

<li>Reed, Lawrence W. – <dfn>Are We Good Enough for Liberty?</dfn> <span class="loc">(JC585)</span></li>

<li>Jeffery, – <dfn>People's War: New Light on the Struggle for South Africa</dfn> <span class="loc">(JQ1998.A4)</span></li>

<li>Beard, Charles – <dfn>An Economic Interpretation of the Constitution of the United States</dfn> <span class="loc">(JK146)</span></li>

<li>Smith, Bradley A. – <dfn>Unfree Speech: The Folly of Campaign Finance Reform</dfn> <span class="loc">(JK1991)</span></li>

<li>de Tocqueville, Alexis – <dfn>Democracy in America</dfn> <span class="loc">(JK216)</span></li>

<li>Brimelow, Peter – <dfn>Alien Nation: Common Sense about America's Immigration Disaster</dfn> <span class="loc">(JV6493)</span></li>

<li>Fukuyama, Francis – <dfn>America at the Crossroads: Democracy, Power and Neoconservative Legacy</dfn> <span class="loc">(JZ1480)</span></li>

<li>Silverglate, Harvey A. and French, David A. and Lukianoff, Greg – <dfn>FIRE's Guide to Free Speech on Campus</dfn> <span class="loc">(KF4123.5)</span></li>

<li>Bernstein, David E. – <dfn>You Can't Say That!</dfn> <span class="loc">(KF4749)</span></li>

</ul>
<h2 id="l-n-education-music-fine-arts">L-N: Education, Music, Fine Arts</h2>
<ul class="booklist">
<li>Bloom, Allan – <dfn>The Closing of the American Mind: How Higher Education Has Failed Democracy and Impoverished the Souls of Today's Students</dfn> <span class="loc">(LA227.3)</span></li>

<li>Russell, Bertrand – <dfn>Education and the Good Life</dfn> <span class="loc">(LB775)</span></li>

<li><dfn>Baptist Hymnal</dfn> <span class="loc">(M2122)</span></li>

<li>Towner, D. B., Lorenz, E. S. and Wilson, Ira B. – <dfn>Songs of Praise: A Collection of Gospel Songs for Men's Voices</dfn> <span class="loc">(M2198)</span></li>

<li>International Graphic Society – <dfn>The Arts of Mankind: Painting, Architecture, Music</dfn> <span class="loc">(N5302)</span></li>

<li>Barral i Altet, Xavier – <dfn>The Early Middle Ages: From Late Antiquity to A.D. 1000</dfn> <span class="loc">(NA350)</span></li>

<li>Churchill, Winston S. – <dfn>Painting as a Pastime: An instructive and inspiring invitation to the joy of painting</dfn> <span class="loc">(ND1142)</span></li>

<li>Cornelius, Maurits – <dfn>The Graphic Work of M.C. Escher</dfn> <span class="loc">(NE670.E75)</span></li>

</ul>
<h2 id="p-philology-linguistics">P: Philology, Linguistics</h2>

<figure class="resright"><img src="/pix/westernclassical.jpg" title="Good for learning some #Lindy linguistics"></figure>

<ul class="booklist">
<li>Smith, Luke – <dfn>External Possession and the Undisentanglability of Syntax and Semantics</dfn></li>

<li>Chomsky, Noam – <dfn>Language and Mind</dfn> <span class="loc">(P106)</span></li>

<li>Harris, Roy – <dfn>Language, Saussure and Wittgenstein, How to Play Games with Words</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>Words and Rules, the Ingredients of Language</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>The Stuff of Thought</dfn> <span class="loc">(P107)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: I Linguistic Theory: Foundations</dfn> <span class="loc">(P121)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: II Linguistics Theory: Extensions and Implications</dfn> <span class="loc">(P121)</span></li>

<li>Ohio State University – <dfn>Language Files 11</dfn> <span class="loc">(P121)</span></li>

<li>Chomsky, Noam – <dfn>The Logical Structure of Linguistic Theory</dfn> <span class="loc">(P158)</span></li>

<li>Falk, Yehuda N. – <dfn>Lexical-Functional Grammar, An Introduction to Parallel Constraint-Based Syntax</dfn> <span class="loc">(P158.25)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Chomsky's Minimalism</dfn> <span class="loc">(P158.28)</span></li>

<li>Gutiérrez, Bravo and Arellanes Arellanes, Francisco and Peón Herrero, Mario Ernesto Chávez – <dfn>Nuevos estudios de Teoría de la Optimalidad</dfn> <span class="loc">(P158.42)</span></li>

<li>Richards, Norvin – <dfn>Contiguity Theory</dfn> <span class="loc">(P224.R43)</span></li>

<li>Bresnan, Joan and Asudeh, Ash and Tolivonen, Ida and Wechsler, Stephen – <dfn>Lexical-Functional Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Chomsky, Noam – <dfn>Aspects of the Theory of Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Freidin, Robert – <dfn>Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Saeed, John I. – <dfn>Semantics</dfn> <span class="loc">(P325)</span></li>

<li>Dalby, Andrew – <dfn>Dictionary of Languages, the Definitive Reference to More than 400 Languages</dfn> <span class="loc">(P371)</span></li>

<li>Allan, Keith – <dfn>The Western Classical Tradition in Linguistics</dfn> <span class="loc">(P61)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Western Linguistics: An Historical Introduction</dfn> <span class="loc">(P61)</span></li>

<li>Klein, Jared – <dfn>An Indo-European Chrestomathy</dfn></li>

<li>Watkins, Calvert – <dfn>The American Heritage Dictionary of Indo-European Roots</dfn> <span class="loc">(P615)</span></li>

<li>Sampson, Geoff – <dfn>Schools of Linguistics</dfn> <span class="loc">(P77)</span></li>

<li>Harris, Randy Allen – <dfn>The Linguistics Wars</dfn> <span class="loc">(P85.C47)</span></li>

<li>Cutting, Joan – <dfn>Pragmatics and Discourse</dfn> <span class="loc">(P99.4.P72)</span></li>

</ul>
<h2 id="pa-greek-and-latin-language-and-literature">PA: Greek and Latin language and Literature</h2>

<figure class="resright"><img src="/pix/hughes.jpg" title="These are actually pretty good and readable English translations."></figure>

<ul class="booklist">
<li>Morrison, Clinton and Barnes, David H. – <dfn>New Testament Word Lists</dfn> <span class="loc">(PA881)</span></li>

<li>Magoffin, Ralph van Deman and Henry, Margaret Young – <dfn>Latin First Year</dfn> <span class="loc">(PA2087)</span></li>

<li>Wheelock, Frederic M. – <dfn>Latin, an Introductory Course Based on Ancient Authors</dfn> <span class="loc">(PA2087.5)</span></li>

<li>Orberg, Hans H – <dfn>Roma Aeterna</dfn> <span class="loc">(PA2094.5)</span></li>

<li>Orberg, Hans H – <dfn>Colloquium Personarum</dfn> <span class="loc">(PA2095)</span></li>

<li>Orberg, Hans H – <dfn>Lingua Latina</dfn> <span class="loc">(PA2095)</span></li>

<li>Simpson, D. P. – <dfn>Cassell's Latin Dictionary</dfn> <span class="loc">(PA2365.E5)</span></li>

<li>Landis, Paul – <dfn>Four Famous Greek Plays</dfn> <span class="loc">(PA3626.A2)</span></li>

<li>Aeschylus – <dfn>The Oresteia</dfn> <span class="loc">(PA3827.A7)</span></li>

<li>Apollonius of Rhodes – <dfn>Jason and the Argonauts (Argonautica)</dfn> <span class="loc">(PA3872)</span></li>

<li>Euripides – <dfn>Three Plays of Euripides: Alcestis, Medea, the Bacchae</dfn> <span class="loc">(PA3975)</span></li>

<li>Euripides – <dfn>Alcestis and Other Plays</dfn> <span class="loc">(PA3975.A5)</span></li>

<li>Corpus Hermeticum – <dfn>Hermes Trismegistus</dfn> <span class="loc">(PA3998)</span></li>

<li>Homer – <dfn>The Iliad</dfn> <span class="loc">(PA4025.A2)</span></li>

<li>Homer – <dfn>The Odyssey</dfn> <span class="loc">(PA4025.A5)</span></li>

<li>Sophocles – <dfn>The Theban Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>The Complete Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>Electra and Other Plays</dfn> <span class="loc">(PA4414.A2)</span></li>

<li>Feyerabend, Karl – <dfn>Greek-English Dictionary</dfn> <span class="loc">(PA445.E5)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Liddell, H. G. and Scott – <dfn>Greek-English Lexicon</dfn> <span class="loc">(PA445.E5)</span></li>

<li>Juvenal – <dfn>The Sixteen Satires</dfn> <span class="loc">(PA6447.E5)</span></li>

<li>Lucretius – <dfn>On the Nature of Things</dfn> <span class="loc">(PA6483.E5)</span></li>

<li>Hughes, Ted – <dfn>Tales from Ovid: Twenty-Four Passages from the 'Metamorphoses' by Ovid</dfn> <span class="loc">(PA6522)</span></li>

<li>Petronius – <dfn>the Satyricon and the Fragments</dfn> <span class="loc">(PA6558.E5)</span></li>

<li>Pliny the Younger – <dfn>Pliny: A Self-Portrait in Letters</dfn> <span class="loc">(PA6639.E5)</span></li>

<li>Virgil – <dfn>Aeneid</dfn> <span class="loc">(PA6807.A5)</span></li>

<li>Virgil – <dfn>The Pastoral Poems</dfn> <span class="loc">(PA6807.B7)</span></li>

</ul>
<h2 id="pc-romance-languages">PC: Romance Languages</h2>

<figure class="resright"><img src="/pix/lathrop.jpg" title="Lathrop's Course on Historical Spanish"></figure>

<ul class="booklist">
<li>Decker, Henry W. and Bernhard, Francoise – <dfn>Modern French</dfn> <span class="loc">(PC211)</span></li>

<li>Azevedo, Milton M. – <dfn>Introducción a la Lingüística Española</dfn> <span class="loc">(PC4073)</span></li>

<li>Lathrop, T. A. and Gutiérrex Cuadrado, Juan – <dfn>Curso de gramática histórica española</dfn> <span class="loc">(PC4101)</span></li>

<li>Moreno, Oscar – <dfn>Gramática avanzada del español</dfn> <span class="loc">(PC4129.E5)</span></li>

<li>Cash, Annette G. and Murray, James C. – <dfn>Teoría y técnicas de traduccón: primeras etapas</dfn> <span class="loc">(PC4498)</span></li>

<li>Gili Gaya, Samuel – <dfn>Vox: Diccionario abreviado de la lengua española</dfn> <span class="loc">(PC4625)</span></li>

</ul>
<h2 id="pd-pf-germanic-languages-and-literatures">PD-PF: Germanic Languages and Literatures</h2>
<ul class="booklist">
<li>Lambdin, Thomas O. – <dfn>An Introduction to the Gothic Language</dfn> <span class="loc">(PD1123)</span></li>

<li>Hugo – <dfn>Swedish Phrase Book</dfn> <span class="loc">(PD5121)</span></li>

<li>Warriner, John E. and Whitten, Mary E. and Friggith, Francis J. – <dfn>Warriner's English Grammar and Composition</dfn> <span class="loc">(PE1112)</span></li>

<li>Elson, William H. and Keck, Christine – <dfn>Elson Grammar School Literature Book Two</dfn> <span class="loc">(PE1121)</span></li>

<li>Mitchell, Brucew and Robinson, Fred C. – <dfn>A Guide to Old English</dfn> <span class="loc">(PE131)</span></li>

<li>Evans, Jonathan – <dfn>An Introduction to Old English</dfn> <span class="loc">(PE135)</span></li>

<li>Bright, James W. – <dfn>Bright's Anglo-Saxon Reader</dfn> <span class="loc">(PE137)</span></li>

<li>Gottschalk, Katherine and Keith Hjortshoj – <dfn>The Elements of Teaching Writing</dfn> <span class="loc">(PE1404)</span></li>

<li>Forsyth, Mark – <dfn>The Elements of Eloquence</dfn> <span class="loc">(PE1421)</span></li>

<li>McCloskey, Deirdre N. – <dfn>Economical Writing</dfn> <span class="loc">(PE1479.E35)</span></li>

<li>Sharp, Stanley Louis and Strothmann, Friedrich Wilhelm – <dfn>German Reading Grammar</dfn> <span class="loc">(PF3111)</span></li>

<li>Morgan, Baynard Quincy and Strothmann, Friedrich Wilhelm – <dfn>Reading German</dfn> <span class="loc">(PF3117)</span></li>

<li>Berlitz – <dfn>Berlitz Self-Teaching German</dfn> <span class="loc">(PF3121)</span></li>

</ul>
<h2 id="pj-pl-oriental-indo-iranian-east-asian-and-oceanian-languages">PJ-PL: Oriental, Indo-Iranian, East-Asian and Oceanian Languages</h2>

<figure class="resright"><img src="/pix/sastry.jpg" title="Sanskrit in the Development of World Thought"></figure>

<ul class="booklist">
<li>Anonymous – <dfn>The Epic of Gilgamesh</dfn> <span class="loc">(PJ3771.G5)</span></li>

<li>Wightwick, Jane and Gaafar, Mahmoud – <dfn>Mastering Arabic</dfn> <span class="loc">(PJ6307)</span></li>

<li>Luxenberg, Christoph – <dfn>The Syro-Aramaic Reading of the Koran: A Contribution to Decoding the Language of the Koran</dfn> <span class="loc">(PJ6696)</span></li>

<li>Burnell, Arthur Coke – <dfn>On the Aindra school of Sanskrit grammarians, their place in the Sanskrit and subordinate literatures</dfn> <span class="loc">(PK407)</span></li>

<li>Sastry, Vempaty Kutumba – <dfn>Sanskrit and Development of World Thought</dfn> <span class="loc">(PK423)</span></li>

<li>Elwell-Sutton, L. P. – <dfn>Elementary Persian Grammar</dfn> <span class="loc">(PK6235)</span></li>

<li>Whitney, William Dwight – <dfn>A Sanskrit Grammar: Including Both the Classical Language, and the Older Dialects, of the Veda and Brahmana</dfn> <span class="loc">(PK663)</span></li>

<li>Sutherland, Goldman – <dfn>Devavanipravesika</dfn> <span class="loc">(PK666)</span></li>

<li>Whitney, William Dwight – <dfn>The Roots, Verb-Forms, And Primary Derivatives of the Sankstrit Language: A Supplement to his Sanskrit Grammar</dfn> <span class="loc">(PK745)</span></li>

<li>DeFrancis, John – <dfn>Intermediate Chinese</dfn> <span class="loc">(PL11117)</span></li>

<li>DeFrancis, John – <dfn>Advanced Chinese</dfn> <span class="loc">(PL1121.C5)</span></li>

<li>Defense Language Institute – <dfn>Chinese: Basic Course</dfn> <span class="loc">(PL1125)</span></li>

<li>Seligman, Scott D. – <dfn>Mandarin Chinese at a Glance</dfn> <span class="loc">(PL1125.E6)</span></li>

<li>DeFrancis, John – <dfn>The Chinese Language, Fact and Fantasy</dfn> <span class="loc">(PL1171)</span></li>

<li><dfn>Oxford Chinese Dictionary</dfn> <span class="loc">(PL1455)</span></li>

<li>Waley, Arthur – <dfn>Translations from the Chinese</dfn> <span class="loc">(PL3277.E3)</span></li>

<li>Burlington, Scott – <dfn>Instant Hawaiian</dfn> <span class="loc">(PL6445)</span></li>

<li>Pukui, Mary Kawena and Elbert, Samuel H. and Mookini, Esther T. – <dfn>The Pocket Hawaiian Dictionary</dfn> <span class="loc">(PL6446)</span></li>

</ul>
<h2 id="pn-general-literature">PN: General Literature</h2>
<ul class="booklist">
<li>Butterworth, Hezekiah – <dfn>The Story of America</dfn> <span class="loc">(PN1009.A1)</span></li>

<li>Kaplar, Richard T. and Patrick D. Maines – <dfn>The Government Factor: Undermining Journalistic Ethics in the Information Age</dfn> <span class="loc">(PN4888.E8)</span></li>

<li>Schwarz, Leo W. – <dfn>Feast of Leviathan: Tales of Adventure, Faith and Love from Jewish Literature</dfn> <span class="loc">(PN6071.J5)</span></li>

<li><dfn>Treasury of Familiar Quotations</dfn> <span class="loc">(PN6081)</span></li>

<li><dfn>Reader's Digest Treasury of American Humor</dfn> <span class="loc">(PN6162)</span></li>

<li>The Onion – <dfn>Dispatches from the Tenth Circle</dfn> <span class="loc">(PN6165)</span></li>

<li>The Onion – <dfn>Our Dumb World</dfn> <span class="loc">(PN6231.A74)</span></li>

<li>Raymond, Eric S. – <dfn>The New Hacker's Dictionary</dfn> <span class="loc">(PN6231.E4)</span></li>

<li>The Onion – <dfn>Our Dumb Century</dfn> <span class="loc">(PN6231.N6)</span></li>

<li>Gómez Dávila, Nicolás – <dfn>Escolios a un texto implícito</dfn> <span class="loc">(PN6275)</span></li>

<li>Brown, Jeffrey – <dfn>Darth Vader and Son</dfn> <span class="loc">(PN6727.B7575)</span></li>

<li>Watterson, Bill – <dfn>Calvin and Hobbes: Scientific Progress Goes 'Boink'</dfn> <span class="loc">(PN6728.C34)</span></li>

<li>Lewis, C. S. – <dfn>The Discarded Image: An Introduction to Medieval and Renaissance Literature</dfn> <span class="loc">(PN671)</span></li>

</ul>
<h2 id="pq-romance-literature">PQ: Romance Literature</h2>

<figure class="resright"><img src="/pix/inferno.jpg"></figure>

<ul class="booklist">
<li>de Montaigne, Michel – <dfn>Montaigne Selected Essays</dfn> <span class="loc">(PQ1642.E6)</span></li>

<li>Morlière, Jean-Baptiste – <dfn>Tartuffe and Other Plays</dfn> <span class="loc">(PQ1842)</span></li>

<li>De Saint-Exupéry – <dfn>Sazadeo Qickek</dfn> <span class="loc">(PQ2637.A274)</span></li>

<li>Alighieri, Dante – <dfn>The Divine Comedy</dfn> <span class="loc">(PQ4315)</span></li>

<li>Alighieri, Dante – <dfn>The Inferno</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Alighieri, Dante – <dfn>I: Hell (Sayers translation)</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Eco, Umberto – <dfn>Foucault's Pendulum</dfn> <span class="loc">(PQ4864.C6)</span></li>

<li>De la Vega, Garcilaso – <dfn>Poesías</dfn> <span class="loc">(PQ6391)</span></li>

<li>Garcia Lorca, Federico – <dfn>Rosita la soltera</dfn> <span class="loc">(PQ6613.A763)</span></li>

<li>Pérez-Reverte, Arturo – <dfn>La tabla de Flandés</dfn> <span class="loc">(PQ6666.E765)</span></li>

<li>Rulfo, Juan &amp;ndash; Pedro – <dfn>y El Llano en llamas</dfn> <span class="loc">(PQ7297.R89)</span></li>

</ul>
<h2 id="pr-english-literature">PR: English Literature</h2>
<ul class="booklist">
<li>Clark, Thomas Curtis and Gillespie, Esther A. – <dfn>1000 Quotable Poems</dfn> <span class="loc">(PR1175)</span></li>

<li><dfn>Beowulf</dfn> <span class="loc">(PR1583)</span></li>

<li>Chaucer, Geoffrey – <dfn>Chaucer's Major Poetry</dfn> <span class="loc">(PR1851)</span></li>

<li>Chaucer, Geoffrey – <dfn>The Canterbury Tales</dfn> <span class="loc">(PR1870.A1)</span></li>

<li>Collis, Louise – <dfn>Memoirs of a Medieval Woman</dfn> <span class="loc">(PR2007)</span></li>

<li>Malory, Thomas – <dfn>Le Morte d'Arthur</dfn> <span class="loc">(PR2041)</span></li>

<li>Craig, W. J. – <dfn>The Complete Works of William Shakespeare</dfn> <span class="loc">(PR2753.C8)</span></li>

<li>Shakespeare, William – <dfn>Hamlet (2 copies)</dfn> <span class="loc">(PR2801.A2)</span></li>

<li>Shakespeare, William – <dfn>Macbeth</dfn> <span class="loc">(PR2823.A2)</span></li>

<li>Shakespeare, William – <dfn>A Midsummer Night's Dream</dfn> <span class="loc">(PR2827.A2)</span></li>

<li>Shakespeare, William – <dfn>The Merchant of Venice</dfn> <span class="loc">(PR2825.A2)</span></li>

<li>Shakespeare, William – <dfn>The Sonnets</dfn> <span class="loc">(PR2848.A2)</span></li>

<li>Crystal, David – <dfn>The Oxford Dictionary of Original Shakespearean Pronunciation</dfn> <span class="loc">(PR2892)</span></li>

<li>Bunyan, John – <dfn>Pilgrim's Progress</dfn> <span class="loc">(PR3330)</span></li>

<li>Milton, John – <dfn>Paradise Lost and Other Poems</dfn> <span class="loc">(PR3560)</span></li>

<li>Coleridge, Samuel Taylor – <dfn>The Rime of the Ancient Mariner</dfn> <span class="loc">(PR4479)</span></li>

<li>Dickens, Charles – <dfn>Great Expectations</dfn> <span class="loc">(PR4560)</span></li>

<li>Shaw, George Bernard – <dfn>Pygmalion</dfn> <span class="loc">(PR5363)</span></li>

<li>Stevenson, Robert Louis – <dfn>The Black Arrow</dfn> <span class="loc">(PR5484)</span></li>

<li>Stevenson, Robert Louis – <dfn>New Arabian Nights</dfn> <span class="loc">(PR5484)</span></li>

<li>Wells, H. G. – <dfn>The Island of Dr. Moreau</dfn> <span class="loc">(PR5774)</span></li>

<li>Wilde, Oscar – <dfn>The Importance of Being Earnest</dfn> <span class="loc">(PR5818)</span></li>

<li>Christie, Agatha – <dfn>Death on the Nile</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Christie, Agatha – <dfn>The Nursery Rhyme Murders</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Golding, William – <dfn>Lord of the Flies</dfn> <span class="loc">(PR6013.O35)</span></li>

<li>Lewis, C. S. – <dfn>The Lion, the Witch and the Wardrobe</dfn> <span class="loc">(PR6023.E926)</span></li>

<li>Huxley, Aldous – <dfn>Brave New World</dfn> <span class="loc">(PR6015.U9)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Lord of the Rings, One-Volume Edition</dfn> <span class="loc">(PR6039.O32)</span></li>

<li>White, T. H. – <dfn>The Once and Future King</dfn> <span class="loc">(PR6045.H2)</span></li>

<li>Adams, Douglas – <dfn>Life, the Universe and Everything</dfn> <span class="loc">(PR6051.D3352)</span></li>

<li>Erickson, Paul – <dfn>Doctor Who: The Ark</dfn> <span class="loc">(PR6052.R449)</span></li>

<li>Burgess, Anthony – <dfn>A Clockwork Orange</dfn> <span class="loc">(PR6052.U638)</span></li>

<li>Grimwade, Peter – <dfn>Doctor Who: Planet of Fire</dfn> <span class="loc">(PR6057.R545)</span></li>

<li>Halleck, Reuben Post – <dfn>History of English Literature</dfn> <span class="loc">(PR85)</span></li>

<li>Achebe, Chinua – <dfn>Things Fall Apart</dfn> <span class="loc">(PR9387.9.A3)</span></li>

</ul>
<h2 id="ps-american-literature">PS: American Literature</h2>

<figure class="resright"><img src="/pix/lovecraft.jpg"></figure>

<ul class="booklist">
<li>Twain, Mark – <dfn>A Connecticut Yankee in King Arthur's Court</dfn> <span class="loc">(PS1308)</span></li>

<li>Hawthorne, Nathaniel – <dfn>The Scarlet Letter</dfn> <span class="loc">(PS1868)</span></li>

<li>Poe, Edgar Allan – <dfn>Edgar Allan Poe Reader</dfn> <span class="loc">(PS2603)</span></li>

<li>Poe, Edgar Allen – <dfn>Tales of Terror and Detection</dfn> <span class="loc">(PS2612)</span></li>

<li>Thoreau, Henry David – <dfn>Walden</dfn> <span class="loc">(PS3048)</span></li>

<li>Wallace, Lew – <dfn>Ben Hur</dfn> <span class="loc">(PS3134)</span></li>

<li>Faulkner, William – <dfn>Light in August</dfn> <span class="loc">(PS3511.A86)</span></li>

<li>Fitzgerald, F. Scott – <dfn>The Great Gatsby</dfn> <span class="loc">(PS3511.I9)</span></li>

<li>Heinlein, Robert A. – <dfn>For Us, the Living</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Heinlein, Robert A. – <dfn>The Moon is a Harsh Mistress</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Lovecraft, H. P. – <dfn>Great Tales of Horror</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Case of Charles Dexter Ward</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Doom That Came to Sarnath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Dream Quest of Unknown Kadath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Tomb</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Rodgers, Marion Elizabeth – <dfn>Mencken &amp; Sara</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Mencken, H. L. – <dfn>The Vintage Mencken</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Rand, Ayn – <dfn>Atlas Shugged</dfn> <span class="loc">(PS3535.A547)</span></li>

<li>Skinner, B. F. – <dfn>Walden Two</dfn> <span class="loc">(PS3537.K527)</span></li>

<li>Smith, Clark Ashton – <dfn>Hyperborea</dfn> <span class="loc">(PS3537.M335)</span></li>

<li>Bear, Greg – <dfn>Darwin's Radio</dfn> <span class="loc">(PS3552.E157)</span></li>

<li>Card, Orson Scott – <dfn>Ender's Game</dfn> <span class="loc">(PS3553.A655)</span></li>

<li>Crichton, Michael – <dfn>Congo</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Jurassic Park</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Timeline</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Dick, Philip K. – <dfn>Dr. Bloodmoney</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Dick, Philip K. – <dfn>Flow My Tears, The Policeman Said</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Herbert, Frank – <dfn>Dune</dfn> <span class="loc">(PS3558.E63)</span></li>

<li>Jordan, Robert – <dfn>The Eye of the World</dfn> <span class="loc">(PS3560.O7617)</span></li>

<li>King, Stephen – <dfn>The Bazaar of Bad Dreams</dfn> <span class="loc">(PS3561.I483)</span></li>

<li>Myers, Bill – <dfn>Blood of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Fire of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Threshold</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Quinn, Daniel – <dfn>Ishmael: An Adventure of the Mind and Spirit</dfn> <span class="loc">(PS3567.U338)</span></li>

<li>Pearl, Matthew – <dfn>The Dante Club</dfn> <span class="loc">(PS3616.E25)</span></li>

<li>Asimov, Isaac – <dfn>Before the Golden Age: A Science Fiction Anthology of the 1930's</dfn> <span class="loc">(PS648.S3)</span></li>

<li>Saramago, José – <dfn>Todos los nombres</dfn> <span class="loc">(PS9281.A66)</span></li>

</ul>
<h2 id="pq-pz-other-literature">PQ-PZ: Other Literature</h2>

<figure class="resright"><img src="/pix/edda.jpg"></figure>

<ul class="booklist">
<li>Voltaire – <dfn>Candide, Zadig and selected stories</dfn> <span class="loc">(PQ2081.E5)</span></li>

<li>Hesse, Hermann – <dfn>Siddhartha</dfn> <span class="loc">(PT2617.E85)</span></li>

<li>Hesse, Hermann – <dfn>The Glass Bead Game</dfn> <span class="loc">(PT2617.E85 G513)</span></li>

<li>Sturluson, Snorri – <dfn>Poetic Edda</dfn> <span class="loc">(PT7235)</span></li>

<li>Sturluson, Snorri – <dfn>Prose Edda</dfn> <span class="loc">(PT7313.E5)</span></li>

<li>Borges, Jorge Luis – <dfn>Ficciones</dfn> <span class="loc">(PW7797.B635)</span></li>

<li>Connor, Ralph – <dfn>Black Rock: a Tale of the Selkirks</dfn> <span class="loc">(PZ3.G654)</span></li>

<li>Roberts, James Hall – <dfn>The Q Document</dfn> <span class="loc">(PZ4.D913)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Hobbit</dfn> <span class="loc">(PZ7.T5744)</span></li>

<li>Wilder, Laura Ingalls – <dfn>Little House (entire series)</dfn> <span class="loc">(PZ7.W6461)</span></li>

<li>Jacobs, Joseph – <dfn>Favorite Celtic Fairy Tales</dfn> <span class="loc">(PZ8)</span></li>

<li>Baum, L. Frank – <dfn>The Wizard of Oz</dfn> <span class="loc">(PZ8.B327)</span></li>

<li><dfn>The Brothers Grimm Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

<li><dfn>The Complete Grimm's Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

</ul>
<h2 id="qa-general-science">QA: General Science</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hVxvLd6cF0k"><img src="/pix/againstmethod.jpg"></a></figure>

<ul class="booklist">
<li>de Santillanna, Giorgio – <dfn>The Origins of Scientific Thought: from Anazimander to Proclus, 600 B.C. to 300 A.D.</dfn> <span class="loc">(Q125)</span></li>

<li>Gardner, Martin – <dfn>Great Essays in Science</dfn> <span class="loc">(Q171)</span></li>

<li>Kuhn, Thomas – <dfn>The Structure of Scientific Revolutions</dfn> <span class="loc">(Q175)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Wiener, Norbert – <dfn>The Human Use of Human Beings</dfn> <span class="loc">(Q175)</span></li>

<li>Feyerabend, Paul – <dfn>Against Method </dfn> <span class="loc">(Q175)</span></li>

<li>Motterlini, Matteo – <dfn>For and Against Method: Including Lakatos's Lectures on Scientific Method and the Lakatos-Feyerabend Correspondence </dfn> <span class="loc">(Q175.3)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Antifragile</dfn> <span class="loc">(Q375)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>The Black Swan</dfn> <span class="loc">(Q375)</span></li>

</ul>
<h2 id="qa-mathematics">QA: Mathematics</h2>
<ul class="booklist">
<li>Sawyer, W. W. – <dfn>Mathematician's Delight</dfn> <span class="loc">(QA37)</span></li>

<li>Birns, Peter and Brown, Patrick and Muster, John C. C. – <dfn>Unix for People</dfn> <span class="loc">(QA76.6)</span></li>

<li>Raymond, Eric S. – <dfn>The Cathedral and the Bazaar</dfn> <span class="loc">(QA76.76.O63)</span></li>

<li>Bellos, Alex – <dfn>Here's Looking at Euclid</dfn> <span class="loc">(QA141.15)</span></li>

<li>Nyberg, Joseph A. – <dfn>Second Course in Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Wentworth, G. A. – <dfn>New School Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Hart, William – <dfn>College Algebra</dfn> <span class="loc">(QA154)</span></li>

<li>Lial, Margaret L. and Miller, Charles D. – <dfn>Algebra and Trigonometry</dfn> <span class="loc">(QA154.2)</span></li>

<li>Sokal, Alan and Bricmont, Jean – <dfn>Fashionable Nonsense: Postmodern Intellectuals' Abuse of Science</dfn> <span class="loc">(QA175)</span></li>

<li>Neugebauer, Otto – <dfn>The Exact Sciences in Antiquity</dfn> <span class="loc">(QA22)</span></li>

<li>Bharati Krsna Thirthaji Maharaja – <dfn>Vedic Mathematics</dfn> <span class="loc">(QA27.I4)</span></li>

<li>Christian, Robert R. – <dfn>Introduction to Logic and Sets</dfn> <span class="loc">(QA248)</span></li>

<li>Davis, Morton D. – <dfn>Game Theory: A Nontechnical Introduction</dfn> <span class="loc">(QA269)</span></li>

<li>Friedman, Avner – <dfn>Differential Games</dfn> <span class="loc">(QA272)</span></li>

<li>Takahashi, Shin – <dfn>The Manga Guide to Statistics</dfn> <span class="loc">(QA276)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 1-10</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 10-15 and Appendices</dfn> <span class="loc">(QA303)</span></li>

<li>Smith, Edward S. and Salkover, Meyer and Justive, Howard K. – <dfn>Unified Calculus</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny – <dfn>Calculus with Analytic Geometry</dfn> <span class="loc">(QA33)</span></li>

<li>Sperling, Abraham and Stuart, Monroe – <dfn>Mathematics (Made Simple Self-Teaching Library)</dfn> <span class="loc">(QA39.2)</span></li>

<li>Horblit, Marcus and Nielson, Kaj L. – <dfn>Problems in Plane Geometry with Solutions</dfn> <span class="loc">(QA459)</span></li>

<li>Shively, Levi S. – <dfn>Modern Geometry</dfn> <span class="loc">(QA473)</span></li>

<li>Nelson, Alfred L. and Folley, Karl W. – <dfn>Plane and Spherical Trigonometry</dfn> <span class="loc">(QA531.N45)</span></li>

<li>Love, Clyde E. – <dfn>Analytic Geometry</dfn> <span class="loc">(QA551)</span></li>

<li>Hutton, Graham – <dfn>Programming in Haskell</dfn> <span class="loc">(QA76.62)</span></li>

<li>Kernighan, Brian W. and Ritchie, Dennis M. – <dfn>The C Programming Language</dfn> <span class="loc">(QA76.73.C15)</span></li>

<li>Barski, Conrad – <dfn>Land of Lisp</dfn> <span class="loc">(QA76.76.C672)</span></li>

<li>Hofstadter, Douglas – <dfn>Gödel, Escher, Bach</dfn> <span class="loc">(QA9.8)</span></li>

<li>Emmet, E. R. – <dfn>Brain Puzzler's Delight</dfn> <span class="loc">(QA95)</span></li>

<li>Emmet, E. R. – <dfn>Puzzles for Pleasure</dfn> <span class="loc">(QA95)</span></li>

<li>Gardner, Martin – <dfn>aha! Gotcha, Paradoxes to puzzle and delight</dfn> <span class="loc">(QA95)</span></li>

<li>Heafford, Philip – <dfn>The Math Entertainer</dfn> <span class="loc">(QA95)</span></li>

</ul>
<h2 id="qb-qr-other-sciences">QB-QR: Other Sciences</h2>
<ul class="booklist">
<li>Hawking, Stephen W. – <dfn>A Brief History of Time</dfn> <span class="loc">(QB981)</span></li>

<li>Lerner, Eric – <dfn>The Big Bang Never Happened</dfn> <span class="loc">(QB991.B54)</span></li>

<li>McEvoy, J. P. and Zarate, Oscar – <dfn>Quantum Theory, A Graphic Guide</dfn> <span class="loc">(QC173.98)</span></li>

<li>Booker, Christopher – <dfn>The Real Global Warming Disaster</dfn> <span class="loc">(QC981.8.G56)</span></li>

<li>Greenburg, Arthur – <dfn>From Alchemy to Chemistry in Picture and Story</dfn> <span class="loc">(QD11)</span></li>

<li>Valentine, Basil – <dfn>Of Natural and Supernatural Things: Also, of the First Tincture, Root, and Spirit of Metals and Minerals: How the Same are Conceived, Generated, Brought Forth, Changed and Augmented</dfn> <span class="loc">(QD25)</span></li>

<li>Watson, James – <dfn>The Double Helix</dfn> <span class="loc">(QH31.D434)</span></li>

<li>Fodor, Jerry and Piattelli Palmarini, Massimo – <dfn>What Darwin Got Wrong</dfn> <span class="loc">(QH375)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Kadans, Joseph M. – <dfn>Modern Encyclopedia of Herbs</dfn> <span class="loc">(QK99.A1)</span></li>

<li>McFarland, J. Horace – <dfn>Getting Acquainted with Trees</dfn> <span class="loc">(QK482)</span></li>

<li>Kurzweil, Ray – <dfn>The Singularity is Near</dfn> <span class="loc">(QP376)</span></li>

<li>Kandel, Eric R. and Schwartz, James H. and Jessell, Thomas M. – <dfn>Essentials of Neural Science and Behavior</dfn> <span class="loc">(QP355.2)</span></li>

</ul>
<h2 id="r-medicine">R: Medicine</h2>
<ul class="booklist">
<li>FC&amp;A – <dfn>The Folk Remedy Encyclopedia: Olive Oil, Vinegar, Honey and 1,001 Other Home Remedies</dfn> <span class="loc">(R733)</span></li>

<li><dfn>Better Homes and Gardens Family Medical Guide</dfn> <span class="loc">(RC81.A2)</span></li>

<li><dfn>The Encyclopedia of Common Diseases</dfn> <span class="loc">(RC81.A2)</span></li>

</ul>
<h2 id="s-t-agriculture-and-technology">S-T: Agriculture and Technology</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=YRNKjQg6y-c"><img src="/pix/salatin.jpg"></a></figure>

<ul class="booklist">
<li>Mollison, Bill – <dfn>Introduction to Permaculture</dfn> <span class="loc">(S494.5.P47)</span></li>

<li>Salatin, Joel – <dfn>Everything I Want to Do Is Illegal</dfn> <span class="loc">(S605.5)</span></li>

<li>David the Good – <dfn>Totally Crazy Easy Florida Gardening</dfn></li>

<li>Seymour, John – <dfn>The Complete Book of Self-Sufficiency</dfn> <span class="loc">(S605.5)</span></li>

<li>Cobleigh, Rolfe – <dfn>Handy Farm Devices and How to Make Them (2 copies)</dfn> <span class="loc">(S676)</span></li>

<li>Seymour, John – <dfn>Gardener's Delight</dfn> <span class="loc">(SB322)</span></li>

<li>Seymour, John – <dfn>The Self-Sufficient Gardener</dfn> <span class="loc">(SB324.3)</span></li>

<li>Haring, Elda – <dfn>The Seedling Handbook</dfn> <span class="loc">(SB405)</span></li>

<li>Abraham, George – <dfn>The Green Thumb Garden Handbook</dfn> <span class="loc">(SB453)</span></li>

<li><dfn>Reader's Digest Illustrated Guide to Gardening</dfn> <span class="loc">(SB453)</span></li>

<li>Kaczynski, Theodore John – <dfn>Technological Slavery</dfn> <span class="loc">(T14.5)</span></li>

<li>Kaczynski, Theodore John – <dfn>Anti-Tech Revolution: Why and How</dfn> <span class="loc">(T14.5)</span></li>

<li>Macaulay, David and Ardleym Neil – <dfn>The Way Things Work</dfn> <span class="loc">(T47)</span></li>

<li>Slater, Robert and Li, Ling and Li, Wen – <dfn>Portraits in Silicon</dfn> <span class="loc">(TK7885.2)</span></li>

<li>Bishop, Michael and Zimmerman, Holmes – <dfn>Detailing Cars and Trucks</dfn> <span class="loc">(TL152)</span></li>

<li>Allaby, Michael and Lovelock, James – <dfn>The Greening of Mars</dfn> <span class="loc">(TL795.7)</span></li>

<li>Abbey, Barbara – <dfn>The Complete Book of Knitting</dfn> <span class="loc">(TT820)</span></li>

<li>Bishop, Jack – <dfn>Vegetables Every Day</dfn> <span class="loc">(TX801)</span></li>

<li>Lo, Kenneth – <dfn>Chinese Regional Cooking</dfn> <span class="loc">(TX724.5.C5)</span></li>

</ul>
<h2 id="books-as-of-yet-unsorted">Books as of yet unsorted</h2>
<ul class="booklist">
<li>Seb Falk – <dfn>The Light Ages: The Surprising Story of Medieval Science</dfn></li>

<li><dfn>The Penny Catechism: A Catechism of Christian Doctrine</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese Reader, Part 1</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese</dfn></li>

<li>Flame Tree Publishing – <dfn>Gothic Fantasy: Lost Worlds Short Stories</dfn></li>

<li>Lee, Christopher – <dfn>This Sceptered Isle 55 BC to 1901</dfn></li>

<li>Malice, Michael – <dfn>Dear Reader</dfn></li>

<li>McCloskey, Deirdre N. – <dfn>Economic Writing</dfn></li>

<li>Meyer, Jerome S. – <dfn>The Provocative Puzzler</dfn></li>

<li>Parikh, Prashant – <dfn>Language and Equilibrium</dfn></li>

<li>Reed, Lawrence W. – <dfn>Great Myths of the Great Depression</dfn></li>

<li><dfn>Using HTML4, Java 1.1, and Javascript 1.2</dfn></li>

<li>Valizadeh, Roosh – <dfn>Game</dfn></li>

<li>Vikernes, Varg – <dfn>MYFAROG 2.6</dfn></li>

</ul>
<div style="clear:both" class="taglist">Read related articles:<br><a id="tag_personal" href="https://lukesmith.xyz/tags/personal">Personal</a> · <a id="tag_science" href="https://lukesmith.xyz/tags/science">Science</a> · <a id="tag_tradition" href="https://lukesmith.xyz/tags/tradition">Tradition</a> · <a id="tag_lifestyle" href="https://lukesmith.xyz/tags/lifestyle">Lifestyle</a> · <a id="tag_philosophy" href="https://lukesmith.xyz/tags/philosophy">Philosophy</a></div>
<br clear="both">
</article>
</main>
<footer>
	<a href="https://lukesmith.xyz">https://lukesmith.xyz</a>

	<p>
	<img class="lw" src="/pix/btc.svg">Bitcoin (<a href="/pix/btc-logo.png">QR</a>): <code>bc1qkyvknjap3cjtgfqd5qwc0q2ygry7nep7d4t57y</code>
	<br>
	<img class="lw" src="/pix/xmr.svg">Monero (<a href="/pix/xmr-logo.png">QR</a>): <code class="crypto">48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh</code>
	</p><p><a href="/index.xml"><img src="/rss.svg" style="max-height:1.5em" alt="RSS Feed" title="Subscribe via RSS for updates."></a>
</p></footer>


</body>
<html lang="en"><head>
	<title>My Personal Library | Luke's Webpage</title>
	<link rel="canonical" href="https://lukesmith.xyz">
	<link rel="alternate" type="application/rss+xml" title="Luke's Webpage RSS" href="/index.xml">
	<link rel="stylesheet" type="text/css" href="/style.css">
	<link rel="icon" href="/favicon.ico">
	<meta name="description" content="This is a list of the books in my personal library. If you have any questions or want me to review any of them, email me (luke@lukesmith.xyz).
I haven't read every book here, nor do I own all the books I've read or like. I also don't necessarily like all the books I own.
Check out my podcast, Not Related! for some book reviews and other things. Books I've talked about in one way or another in the podcast will have a link to that episode.">
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
<p>This is a list of the books in my personal library. If you have any
questions or want me to review any of them, email me
(<a href="mailto:luke@lukesmith.xyz">luke@lukesmith.xyz</a>).</p>
<p>I haven't read every book here, nor do I own all the books I've read
or like. I also don't necessarily like all the books I own.</p>
<p>Check out <a href="https://notrelated.xyz">my podcast, <em>Not Related!</em></a>
for some book reviews and other things. Books I've talked about in one
way or another in the podcast will have a link to that episode.</p>
<h2 id="-lindypressnet-books">🆕 LindyPress.net Books</h2>
<p>Note that now I am reprinting out-of-print works at
<a href="https://lindypress.net">LindyPress.net</a>. You can buy any of these books
yourself if you'd like. (Most of them are pretty exclusive in that I'm
the only one reprinting them.)</p>
<ul>
<li>Pseudo-Aristotle – <a href="https://lindypress.net/book?pk=9">The Secret of Secrets</a></li>
<li><a href="https://lindypress.net/book?pk=6">The Books of Enoch and Book of
Jubilees</a></li>
<li>Isidore of Seville – <a href="https://lindypress.net/book?pk=5">Etymologiae, sive Originum Viginti
Libri</a></li>
<li>Roger Bacon ‐ <a href="https://lindypress.net/book?pk=3">Compendium Studii
Theologiae</a></li>
<li>Marcus Aurelius – <a href="https://lindypress.net/book?pk=2">Meditations</a></li>
<li><a href="https://lindypress.net/book?pk=1">Anti-Modernist Papal Encyclicals</a></li>
</ul>
<p>(These are at the top since I don't know if anyone has given them Library of
Congress numbers, and I suppose as an ad.)</p>
<h2 id="a-bd-general-works-philosophy-logic-speculative-philosophy">A-BD: General Works, Philosophy, Logic, Speculative Philosophy</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hCVdCS0t46I"><img src="/pix/searle.jpg" title="Searle (actually literally) did nothing wrong."></a></figure>

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
<h2 id="bm-bx-specific-religions-and-theology">BM-BX: Specific Religions and Theology</h2>

<figure class="resright"><img src="/pix/biglot.jpg" title="A Greek and Latin biglottic Bible"></figure>

<ul class="booklist">
<li><dfn>'תְּהִלַּת ה</dfn> <span class="loc">(BM675/D3)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Key to Theosophy</dfn> <span class="loc">(BP561)</span></li>

<li>Blavatsky, Helena Petrovna – <dfn>The Voice of Silence</dfn> <span class="loc">(BP561)</span></li>

<li>Wright, Stuart – <dfn>Armageddon in Waco</dfn> <span class="loc">(BP605.B62)</span></li>

<li>Lewis, C. S. – <dfn>Mere Christianity</dfn> <span class="loc">(BR123)</span></li>

<li>Lewis, C. S. – <dfn>The Screwtape Letters</dfn> <span class="loc">(BR125)</span></li>

<li>Reardon, Patrick Henry – <dfn>Christ in the Psalms</dfn> <span class="loc">(BS1430.4)</span></li>

<li>Leithart, Peter J. – <dfn>Solomon Among the Postmoderns</dfn> <span class="loc">(BS1475.52)</span></li>

<li>Porter, J. R. – <dfn>The Lost Bible</dfn> <span class="loc">(BS1700)</span></li>

<li>Heiser, Michael – <dfn>Reversing Hermon: Enoch, the Watchers and the Forgotten Mission of Jesus Christ</dfn> <span class="loc">(BS1830.E7)</span></li>

<li><dfn>The New Oxford Annotated Bible</dfn> <span class="loc">(BS191.5.A1)</span></li>

<li><dfn>The New English Bible</dfn> <span class="loc">(BS192.A1)</span></li>

<li>Montano, Arias and Leudsen, Johann – <dfn>Greek-Latin Parallel New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>Pocket Interlinear New Testament</dfn> <span class="loc">(BS1965)</span></li>

<li><dfn>The New International Dictionary of New Testament Theology (3 Volumes)</dfn> <span class="loc">(BS2312)</span></li>

<li><dfn>Ἡ Καινὴ Διαθήκη</dfn> <span class="loc">(BS2312)</span></li>

<li>Kümmel, Werner Georg – <dfn>Introduction to the New Testament</dfn> <span class="loc">(BS2330)</span></li>

<li>Aland, Kurt – <dfn>Synopsis Quattuor Evangeliorum</dfn> <span class="loc">(BS2560.A2)</span></li>

<li>Mack. Burton L. – <dfn>A Myth of Innocence</dfn> <span class="loc">(BS2585.2)</span></li>

<li>Ehrman, Bart D. – <dfn>Lost Christianities: The Battles for Scriptures and the Faiths We Never Knew</dfn> <span class="loc">(BS2840.E4)</span></li>

<li>Luther, Martin – <dfn>Luther's Small Catechism with Additions Including the Augsburg Confession</dfn> <span class="loc">(BR331.K64)</span></li>

<li>Strong, James – <dfn>Strong's Exhaustive Concordance of the Bible with Hebrew and Greek Dictionaries</dfn> <span class="loc">(BS425)</span></li>

<li><dfn>Illustrated Dictionary and Concordance of the Bible</dfn> <span class="loc">(BS440)</span></li>

<li>McDowell, Josh – <dfn>The New Evidence that Demands a Verdict</dfn> <span class="loc">(BS480)</span></li>

<li>Laymon, Charles M. – <dfn>The Interpreter's One-Volume Commentary on the Bible</dfn> <span class="loc">(BS491.2)</span></li>

<li>Cross, John R. – <dfn>The Stranger on the Road to Emmaus</dfn> <span class="loc">(BS511.2)</span></li>

<li><dfn>Reader's Digest Mysteries of the Bible; the Enduring Questions of the Scriptures</dfn> <span class="loc">(BS538)</span></li>

<li>Smith, Brendan Powell – <dfn>The Brick Bible</dfn> <span class="loc">(BS550.3)</span></li>

<li>Kent, Paul and McLaughlan, David – <dfn>Know Your Bible: All 66 Books Explained and Applied</dfn> <span class="loc">(BS593)</span></li>

<li><dfn>Septuagint with Apocrypha</dfn> <span class="loc">(BS742)</span></li>

<li><dfn>Biblia Sacra Vulgata</dfn> <span class="loc">(BS75)</span></li>

<li>Newman, John Henry – <dfn>An Essay on the Development of Christian Doctrine</dfn> <span class="loc">(BT21)</span></li>

<li>Robinson, James M. – <dfn>The Nag Hammadi Library</dfn> <span class="loc">(BT1391)</span></li>

<li>Lewis, C. S. – <dfn>Surprised by Joy: The Shape of My Early Life</dfn> <span class="loc">(BV4935.L43)</span></li>

<li>Carman, Stephen L. and Owen, Bob – <dfn>Quest: The Story of an Aerospace Engineer who Challenged God to Prove Himself</dfn> <span class="loc">(BV4930)</span></li>

<li>Ware, Timothy – <dfn>The Orthodox Church</dfn> <span class="loc">(BX106)</span></li>

<li>Aveling, J. C. H. – <dfn>The Jesuits</dfn> <span class="loc">(BX3706.2)</span></li>

<li><dfn>The Book of Common Prayer</dfn> <span class="loc">(BX5145)</span></li>

<li><dfn>Five Great Encyclicals: Labor, Education, Marriage, Reconstructing the Social Order, Atheistic Communism</dfn> <span class="loc">(BX860)</span></li>

</ul>
<h2 id="c-auxiliary-sciences-of-history">C: Auxiliary Sciences of History</h2>
<ul class="booklist">
<li>Graeber, David and Wengrow, David – <dfn>The Dawn of Everything: A New History of Humanity</dfn> <span class="loc">(CB19)</span></li>

<li>McNeill, William H. – <dfn>The Rise of the West: A History of the Human Community</dfn> <span class="loc">(CB59)</span></li>

<li>Sitchin, Zecharia – <dfn>The 12th Planet</dfn> <span class="loc">(CB156)</span></li>

<li>Rohl, David – <dfn>The Lords of Avaris: Uncovering the Legendary Origins of Western Civilization</dfn> <span class="loc">(CB245)</span> <a href="https://notrelated.xyz/#02.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Casson, Lionel and Clairborne, Robert and Fagan, Brian and Karp, Walter – <dfn>Mysteries of the Past</dfn> <span class="loc">(CB311)</span></li>

<li>Fisher, Marshall John and Fisher, David E. – <dfn>Mysteries of Lost Empires</dfn> <span class="loc">(CB311)</span></li>

<li>Hawkes, Jacquetta – <dfn>The Atlas of Early Man</dfn> <span class="loc">(CB311)</span></li>

<li>Platt, Richard and Riddell, Chris – <dfn>Castle Diary</dfn> <span class="loc">(CB351)</span></li>

<li>Cahill, Thomas – <dfn>Mysteries of the Middle Ages</dfn> <span class="loc">(CB351)</span></li>

</ul>
<h2 id="d-world-history">D: World History</h2>

<figure class="resright"><img src="/pix/racehutton.jpg" title="Hutton's book on the Third Reich"></figure>

<ul class="booklist">
<li>Malesky, Kee – <dfn>All Facts Considered, the Essential Library of Inessential Knowledge</dfn> <span class="loc">(D10)</span></li>

<li>Evola, Julius – <dfn>Revolt Against the Modern World</dfn> <span class="loc">(D16.8)</span></li>

<li>Epstein, Steven A. – <dfn>An Economic and Social History of Later Medieval Europe, 1000-1500</dfn> <span class="loc">(D117)</span></li>

<li>Pirenne, Henri – <dfn>A History of Europe</dfn> <span class="loc">(D117)</span></li>

<li>Cantor, Nroman F. – <dfn>Medieval History: The Life and Death of a Civilization</dfn> <span class="loc">(D118)</span></li>

<li>Roberts, J. M. – <dfn>New History of the World</dfn> <span class="loc">(D20)</span></li>

<li>Mann, Charles C. – <dfn>1493, Uncovering the New World Columbus Created</dfn> <span class="loc">(D228)</span></li>

<li>Rogan, Eugene L. – <dfn>The FAll of the Ottomans: The Great War in the Middle East</dfn> <span class="loc">(D566)</span></li>

<li>Sanborn, Frederick R. – <dfn>Design for War: A Study of Secret Power Politics</dfn> <span class="loc">(D742.U5)</span></li>

<li>Cheyney, Edward P. – <dfn>A Short History of England</dfn> <span class="loc">(DA32)</span></li>

<li>Thomas, Charles – <dfn>Celtic Britain</dfn> <span class="loc">(DA140)</span></li>

<li>Sellar, W.C. &amp; Yeatman R.J. – <dfn>1066 and All That</dfn> <span class="loc">(DA33)</span></li>

<li>Freeman, John and Sharpe, Sue – <dfn>This Beautiful Land: Britain</dfn> <span class="loc">(DA632)</span></li>

<li>Hutton, Christopher – <dfn>Race and the Third Reich</dfn> <span class="loc">(DD253)</span></li>

<li>Tacitus, C. Cornellius – <dfn>Annales et Historiae</dfn> <span class="loc">(DG207.T3)</span></li>

<li>Shirer, William L. – <dfn>The Rise and Fall of the Third Reich</dfn> <span class="loc">(DD256.5)</span></li>

<li>MacDonald, Kevin – <dfn>The Culture of Critique: An Evolutionary Analysis of Jewish Involvement in Twentieth-Century Intellectual and Political Movements</dfn> <span class="loc">(DS143)</span></li>

<li>Ford, Henry Sr. – <dfn>The International Jew: The World's Foremost Problem</dfn> <span class="loc">(DS145)</span></li>

<li>Ali, Tariq – <dfn>The Duel: Pakistan on the Flight Path of American Power</dfn> <span class="loc">(DS384)</span></li>

<li>De Bary, William Theodore – <dfn>The Sources of Indian Tradition</dfn> <span class="loc">(DS423)</span></li>

<li>Keay, John – <dfn>India, A History</dfn> <span class="loc">(DS451)</span></li>

<li>Ebrey, Patricia Buckley – <dfn>Cambridge Illustrated History of China</dfn> <span class="loc">(DS706)</span></li>

<li>National Geographic Society – <dfn>Journey into China</dfn> <span class="loc">(DS712)</span></li>

</ul>
<h2 id="e-f-history-of-the-americas">E-F: History of the Americas</h2>

<figure class="resright"><img src="/pix/foxfire.jpg"></figure>

<ul class="booklist">
<li>Hancock, Graham – <dfn>America Before: The Key to Earth's Lost Civilization</dfn> <span class="loc">(E61)</span></li>

<li>Little, Gregory – <dfn>Path of Souls: The Native American Death Journey: Cygnus, Orion, the Milky Way, Giant Skeletons in Mounds, &amp; the Smithsonian</dfn> <span class="loc">(E98.M8)</span></li>

<li>Mooney, James – <dfn>Myths of the Cherokee</dfn> <span class="loc">(E99.C5)</span></li>

<li>Greenblatt, Stephen – <dfn>New World Encounters</dfn> <span class="loc">(E141)</span></li>

<li>Fischer, David Hackett – <dfn>Albion's Seed: Four British Folkways in America</dfn> <span class="loc">(E169.1)</span> <a href="https://notrelated.xyz/#01.03"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Sowell, Thomas – <dfn>Ethnic America</dfn> <span class="loc">(E184.A1)</span></li>

<li>Hurmence, Belinda – <dfn>Before Freedom: 48 Oral Histories of Former North and South Carolina Slaves</dfn> <span class="loc">(E444)</span></li>

<li>Adams, Nehemiah – <dfn>A South-side View of Slavery: or Three Months at the South in 1854</dfn> <span class="loc">(E449)</span></li>

<li>Parsons, Charles Grandison – <dfn>An Inside View of Slavery; or A Tour Among the Planters</dfn> <span class="loc">(E449)</span></li>

<li>Long, A. L. – <dfn>Memoirs of Robert E. Lee</dfn> <span class="loc">(E467.1.L4)</span></li>

<li>Henry, Robert Selph – <dfn>The Story of the Confederacy</dfn> <span class="loc">(E487)</span></li>

<li>Mann, Charles C. – <dfn>1491, New Revelations of the Americas Before Columbus</dfn> <span class="loc">(E61)</span></li>

<li>Wharton, H. M. – <dfn>War Songs and Poems of the Southern Confederacy, 1861-1865: a Collection of the Most Popular and Impressive Songs and Poems of War Times, Dear to Every Southern Heart</dfn> <span class="loc">(E647)</span></li>

<li><dfn>The Blue Book of the John Birch Society</dfn> <span class="loc">(E743.5)</span></li>

<li>Stormer, John A. – <dfn>The Death of a Nation</dfn> <span class="loc">(E743.5)</span></li>

<li>Ramo, Joshua Cooper – <dfn>The Age of the Unthinkable</dfn> <span class="loc">(E902)</span></li>

<li>de las Casas, Bartolomé – <dfn>Brevisima relación de la destrución de las Indias</dfn> <span class="loc">(F1411)</span></li>

<li><dfn>The Foxfire Book</dfn> <span class="loc">(F291.2)</span></li>

<li><dfn>The Foxfire Book 2</dfn> <span class="loc">(F291.2)</span></li>

</ul>
<h2 id="g-geography-anthropology-recreation">G: Geography, Anthropology, Recreation</h2>
<ul class="booklist">
<li>Winer, Richard – <dfn>Ghost Ships: True Stories of Nautical Nightmares, Hauntings, and Disasters</dfn> <span class="loc">(G525)</span></li>

<li><dfn>National Geographic Collegiate Atlas of the World</dfn> <span class="loc">(G1021)</span></li>

<li>Wells, Spencer – <dfn>Pandora's Seed: The Unforeseen Cost of Civilization</dfn> <span class="loc">(GF75)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cochran, Gregory and Harpending, Henry – <dfn>the 10,000 Explosion: How Civilization Accelerated Human Evolution</dfn> <span class="loc">(GN281.4)</span> <a href="https://notrelated.xyz/#01.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Cremo, Michael A. &amp; Thompson, Ricahrd L. – <dfn>Forbidden Archaeology: The Hidden History of the Human Race</dfn> <span class="loc">(GN741)</span></li>

<li>Hancock, Graham – <dfn>Magicians of the Gods: The Forgotten Wisdom of Earth's Lost Civilization</dfn> <span class="loc">(GN751)</span></li>

<li>Cayce, Hugh Lynn – <dfn>Edgar Cayce on Atlantis</dfn> <span class="loc">(GN751.C35)</span></li>

<li>Marshack, Alexander – <dfn>The Roots of Civilization: The Cognitive Beginnings of Man's First Art, Symbol and Notation</dfn> <span class="loc">(GN772)</span></li>

<li>Bord, Janet and Bord, Colin – <dfn>Prehistoric Britain from the Air</dfn> <span class="loc">(GN805)</span></li>

<li>Bruce, Annette J. – <dfn>More Tellable Cracker Tales</dfn> <span class="loc">(GR110.F5)</span></li>

</ul>
<h2 id="h-social-sciences">H: Social Sciences</h2>
<p>
</p><figure class="resright"><img src="/pix/democracy.jpg"></figure>


<figure class="resright"><img src="/pix/pike.jpg"></figure>
<p></p>
<ul class="booklist">
<li>Greenspan, Alan – <dfn>The Age of Turbulence</dfn> <span class="loc">(HB119.G74)</span></li>

<li>Hazlitt, Hentry – <dfn>Economics in One Lesson (two copies)</dfn> <span class="loc">(HB171)</span></li>

<li>Keynes, John Maynard – <dfn>The General Theory of Employment, Interest and Money</dfn> <span class="loc">(HB171)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Rothbard, Murray – <dfn>Man, Economy and State with Power and Market</dfn> <span class="loc">(HB171)</span></li>

<li>von Mises, Ludwig – <dfn>Economic Policy</dfn> <span class="loc">(HB171)</span></li>

<li>Boulding, Kenneth E. – <dfn>Economic Analysis</dfn> <span class="loc">(HB171.5)</span></li>

<li>Goodman, Kennard E. and Moore, William L. – <dfn>Economics in Everyday Life</dfn> <span class="loc">(HB171.5)</span></li>

<li>Pindyck, Robert S. and Rubinfeld, Daniel L. – <dfn>Microeconomics</dfn> <span class="loc">(HB172)</span></li>

<li>Fisher, David Hackett – <dfn>The Great Wave: Price Revolutions and the Rhythm of History</dfn> <span class="loc">(HB231)</span></li>

<li>Soros, George – <dfn>The Crash of 2008 and What It Means</dfn> <span class="loc">(HB3722)</span> <a href="https://notrelated.xyz/#02.05"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Keen, Steve – <dfn>Debunking Economics: The Naked Emperor Dethroned?</dfn> <span class="loc">(HB71)</span></li>

<li>Krugman, Paul – <dfn>The Accidental Theorist</dfn> <span class="loc">(HB74.5)</span></li>

<li>Hoppe, Hans Hermann – <dfn>Democracy: The God That Failed: The Economics and Politics of Monarchy, Democracy and Natural Law</dfn> <span class="loc">(HB74.P65)</span></li>

<li>Ekelund, Robert B. Jr. and Hébert, Robert F – <dfn>A History of Economic Theory and Method</dfn> <span class="loc">(HB75)</span></li>

<li>Buchholz, Todd G. – <dfn>New Ideas from Dead Economists, an Introduction to Modern Economic Thought</dfn> <span class="loc">(HB76)</span></li>

<li>Heilbroner, Robert L. – <dfn>The Worldly Philosophers</dfn> <span class="loc">(HB76)</span></li>

<li>Paul Erlich – <dfn>The Population Bomb</dfn> <span class="loc">(HB875.E35)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Palmer, Tom G. – <dfn>After the Welfare State</dfn> <span class="loc">(HB99.3)</span></li>

<li>Krugman, Paul – <dfn>Peddling Prosperity</dfn> <span class="loc">(HB99.7)</span></li>

<li>Walton, Gary M. and Rockoff, Hugh – <dfn>History of the American Economy</dfn> <span class="loc">(HC103)</span></li>

<li>Krugman, Paul – <dfn>The Great Unravelling</dfn> <span class="loc">(HC106)</span></li>

<li>Krugman, Paul – <dfn>The Conscience of a Liberal</dfn> <span class="loc">(HC110.I5)</span></li>

<li>Clark, Gregory – <dfn>A Farewell to Alms</dfn> <span class="loc">(HC21)</span></li>

<li>Easterly, William – <dfn>The Elusive Quest for Growth</dfn> <span class="loc">(HC59.72.P6)</span></li>

<li>Simon, Julian L. and Kahn, Herman – <dfn>The Resourceful Earth</dfn> <span class="loc">(HC59.R445)</span> <a href="https://notrelated.xyz/#02.07"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Dixit, Avinash K. and Nalebuff, Barry J. – <dfn>Thinking Strategically, The Competitive Edge in Business, Politics, and Everyday Life</dfn> <span class="loc">(HD30.28)</span></li>

<li>Adams, Scott – <dfn>The Dilbert Principle</dfn> <span class="loc">(HD31)</span></li>

<li>Ehrenreich, Barbara – <dfn>Nickel and Dimed</dfn> <span class="loc">(HD4918)</span></li>

<li>Thiel, Peter – <dfn>Zero to One: Notes on Start-Ups, or How to Build the Future</dfn> <span class="loc">(HD62.5)</span></li>

<li>Montgomery, David – <dfn>Beyond Equality: Labor and the Radical Republicans 1862-1872</dfn> <span class="loc">(HD8076)</span></li>

<li>Caplan, Bryan – <dfn>The Myth of the Rational Voter: Why Democracies Choose Bad Policies</dfn> <span class="loc">(HD87)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bhagwati, Jagdish – <dfn>In Defense of Globalization</dfn> <span class="loc">(HF1359)</span></li>

<li>Krugman, Paul and Obstfield, Maurice – <dfn>International Economics</dfn> <span class="loc">(HF1359)</span></li>

<li>Lechner, Frank J. and Boli, John – <dfn>The Globalization Reader</dfn> <span class="loc">(HF1359)</span></li>

<li>Myrdal, Gunnar – <dfn>Beyond the Welfare State</dfn> <span class="loc">(HF1411)</span></li>

<li>Graeber, David – <dfn>Bullshit Jobs: A Theory</dfn> <span class="loc">(HF5549.5.J63)</span> <a href="https://notrelated.xyz/#02.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Soros, George – <dfn>In Defense of Open Society</dfn> <span class="loc">(HG172.S63)</span></li>

<li>Boortz, Neal and Linder, John – <dfn>The Fairtax Book: Saying Goodbye to the Income Tax and the IRS</dfn> <span class="loc">(HJ4652)</span></li>

<li>Stove, David – <dfn>Darwinian Fairytales</dfn> <span class="loc">(HM106)</span></li>

<li>O'Brien, Jodi – <dfn>The Production of Reality</dfn> <span class="loc">(HM1033)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Skin in the Game</dfn> <span class="loc">(HM1101)</span></li>

<li>Berne, Eric – <dfn>Games People Play</dfn> <span class="loc">(HM1106)</span></li>

<li>Pinker, Steven – <dfn>The Better Angels of Our Nature</dfn> <span class="loc">(HM1116)</span></li>

<li>Kropotkin, Peter – <dfn>Mutual Aid: A Factor of Evolution</dfn> <span class="loc">(HM131)</span></li>

<li>Diamond, Jared – <dfn>Guns, Germs and Steel</dfn> <span class="loc">(HM206)</span></li>

<li>Bork, Robert H. – <dfn>Slouching Towards Gomorrah: Modern Liberalism and American Decline</dfn> <span class="loc">(HN59.2)</span></li>

<li>Arnold, Matthew – <dfn>Culture and Anarchy</dfn> <span class="loc">(HN389)</span></li>

<li>Jones, E. Michael – <dfn>Libido Dominandi: Sexual Liberation and Political Control</dfn> <span class="loc">(HQ472.U6)</span></li>

<li>Eisler, Riane – <dfn>The Chalice and the Blade, Our History, Our Future</dfn> <span class="loc">(HQ1075)</span></li>

<li>Harris, Judith Rich – <dfn>The Nurture Assumption</dfn> <span class="loc">(HQ772)</span></li>

<li>Beuerlein, Mark – <dfn>The Dumbest Generation</dfn> <span class="loc">(HQ799.7)</span></li>

<li>Street, Oliver Day – <dfn>Symbolism of the Three Degrees</dfn> <span class="loc">(HS425)</span></li>

<li><dfn>Morals and Dogma of the Ancient and Accepted Scottish Rite of Freemasonry</dfn> <span class="loc">(HS767)</span></li>

<li><dfn>The 9/11 Commission Report: Final Report of the National Commission on Terrorist Attacks upon the United States</dfn> <span class="loc">(HV6432.7)</span></li>

<li>Engels, Frederick – <dfn>Socialism: Utopian and Scientific</dfn> <span class="loc">(HX276)</span></li>

<li>Hayek, F. A. – <dfn>The Intellectuals and Socialism</dfn> <span class="loc">(HX528)</span></li>

<li>More, Thomas – <dfn>Utopia</dfn> <span class="loc">(HX810.5)</span></li>

<li>Stringham, Edward P. – <dfn>Anarchy and the Law</dfn> <span class="loc">(HX833)</span></li>

<li>Schumpeter, Joseph Alois – <dfn>Capitalism, Socialism and Democracy</dfn> <span class="loc">(HX86)</span> <a href="https://notrelated.xyz/#01.02"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Bastiat, Frederic – <dfn>The Law</dfn> <span class="loc">(HX87)</span></li>

</ul>
<h2 id="j-k-political-science-and-law">J-K: Political Science and Law</h2>

<figure class="resright"><img src="/pix/archeofuturism.jpg"></figure>

<ul class="booklist">
<li>Faye, Guillaume – <dfn>Archeofuturism: European Visions of the Post-Catastrophic Age</dfn> <span class="loc">(JA84.F8)</span></li>

<li>Plato – <dfn>The Republic</dfn> <span class="loc">(JC71)</span></li>

<li>Machiavelli, Niccolò – <dfn>The Prince and Other Writings</dfn> <span class="loc">(JC143)</span></li>

<li>Hobbes, Thomas – <dfn>Leviathan</dfn> <span class="loc">(JC153)</span></li>

<li>Filmer, Robert – <dfn>Patriarcha, or, The Natural Power of Kings</dfn> <span class="loc">(JC153.F48)</span></li>

<li>Samons, Loren J. – <dfn>What's Wrong with Democracy?</dfn> <span class="loc">(JC421)</span> <a href="https://notrelated.xyz/#01.04"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Mill, John Stewart – <dfn>On Liberty</dfn> <span class="loc">(JC585)</span></li>

<li>Reed, Lawrence W. – <dfn>Are We Good Enough for Liberty?</dfn> <span class="loc">(JC585)</span></li>

<li>Jeffery, – <dfn>People's War: New Light on the Struggle for South Africa</dfn> <span class="loc">(JQ1998.A4)</span></li>

<li>Beard, Charles – <dfn>An Economic Interpretation of the Constitution of the United States</dfn> <span class="loc">(JK146)</span></li>

<li>Smith, Bradley A. – <dfn>Unfree Speech: The Folly of Campaign Finance Reform</dfn> <span class="loc">(JK1991)</span></li>

<li>de Tocqueville, Alexis – <dfn>Democracy in America</dfn> <span class="loc">(JK216)</span></li>

<li>Brimelow, Peter – <dfn>Alien Nation: Common Sense about America's Immigration Disaster</dfn> <span class="loc">(JV6493)</span></li>

<li>Fukuyama, Francis – <dfn>America at the Crossroads: Democracy, Power and Neoconservative Legacy</dfn> <span class="loc">(JZ1480)</span></li>

<li>Silverglate, Harvey A. and French, David A. and Lukianoff, Greg – <dfn>FIRE's Guide to Free Speech on Campus</dfn> <span class="loc">(KF4123.5)</span></li>

<li>Bernstein, David E. – <dfn>You Can't Say That!</dfn> <span class="loc">(KF4749)</span></li>

</ul>
<h2 id="l-n-education-music-fine-arts">L-N: Education, Music, Fine Arts</h2>
<ul class="booklist">
<li>Bloom, Allan – <dfn>The Closing of the American Mind: How Higher Education Has Failed Democracy and Impoverished the Souls of Today's Students</dfn> <span class="loc">(LA227.3)</span></li>

<li>Russell, Bertrand – <dfn>Education and the Good Life</dfn> <span class="loc">(LB775)</span></li>

<li><dfn>Baptist Hymnal</dfn> <span class="loc">(M2122)</span></li>

<li>Towner, D. B., Lorenz, E. S. and Wilson, Ira B. – <dfn>Songs of Praise: A Collection of Gospel Songs for Men's Voices</dfn> <span class="loc">(M2198)</span></li>

<li>International Graphic Society – <dfn>The Arts of Mankind: Painting, Architecture, Music</dfn> <span class="loc">(N5302)</span></li>

<li>Barral i Altet, Xavier – <dfn>The Early Middle Ages: From Late Antiquity to A.D. 1000</dfn> <span class="loc">(NA350)</span></li>

<li>Churchill, Winston S. – <dfn>Painting as a Pastime: An instructive and inspiring invitation to the joy of painting</dfn> <span class="loc">(ND1142)</span></li>

<li>Cornelius, Maurits – <dfn>The Graphic Work of M.C. Escher</dfn> <span class="loc">(NE670.E75)</span></li>

</ul>
<h2 id="p-philology-linguistics">P: Philology, Linguistics</h2>

<figure class="resright"><img src="/pix/westernclassical.jpg" title="Good for learning some #Lindy linguistics"></figure>

<ul class="booklist">
<li>Smith, Luke – <dfn>External Possession and the Undisentanglability of Syntax and Semantics</dfn></li>

<li>Chomsky, Noam – <dfn>Language and Mind</dfn> <span class="loc">(P106)</span></li>

<li>Harris, Roy – <dfn>Language, Saussure and Wittgenstein, How to Play Games with Words</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>Words and Rules, the Ingredients of Language</dfn> <span class="loc">(P106)</span></li>

<li>Pinker, Steven – <dfn>The Stuff of Thought</dfn> <span class="loc">(P107)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: I Linguistic Theory: Foundations</dfn> <span class="loc">(P121)</span></li>

<li>Newmeyer, Frederick – <dfn>Linguistics: The Cambridge Survey: II Linguistics Theory: Extensions and Implications</dfn> <span class="loc">(P121)</span></li>

<li>Ohio State University – <dfn>Language Files 11</dfn> <span class="loc">(P121)</span></li>

<li>Chomsky, Noam – <dfn>The Logical Structure of Linguistic Theory</dfn> <span class="loc">(P158)</span></li>

<li>Falk, Yehuda N. – <dfn>Lexical-Functional Grammar, An Introduction to Parallel Constraint-Based Syntax</dfn> <span class="loc">(P158.25)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Chomsky's Minimalism</dfn> <span class="loc">(P158.28)</span></li>

<li>Gutiérrez, Bravo and Arellanes Arellanes, Francisco and Peón Herrero, Mario Ernesto Chávez – <dfn>Nuevos estudios de Teoría de la Optimalidad</dfn> <span class="loc">(P158.42)</span></li>

<li>Richards, Norvin – <dfn>Contiguity Theory</dfn> <span class="loc">(P224.R43)</span></li>

<li>Bresnan, Joan and Asudeh, Ash and Tolivonen, Ida and Wechsler, Stephen – <dfn>Lexical-Functional Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Chomsky, Noam – <dfn>Aspects of the Theory of Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Freidin, Robert – <dfn>Syntax</dfn> <span class="loc">(P291)</span></li>

<li>Saeed, John I. – <dfn>Semantics</dfn> <span class="loc">(P325)</span></li>

<li>Dalby, Andrew – <dfn>Dictionary of Languages, the Definitive Reference to More than 400 Languages</dfn> <span class="loc">(P371)</span></li>

<li>Allan, Keith – <dfn>The Western Classical Tradition in Linguistics</dfn> <span class="loc">(P61)</span></li>

<li>Seuren, Pieter A. M. – <dfn>Western Linguistics: An Historical Introduction</dfn> <span class="loc">(P61)</span></li>

<li>Klein, Jared – <dfn>An Indo-European Chrestomathy</dfn></li>

<li>Watkins, Calvert – <dfn>The American Heritage Dictionary of Indo-European Roots</dfn> <span class="loc">(P615)</span></li>

<li>Sampson, Geoff – <dfn>Schools of Linguistics</dfn> <span class="loc">(P77)</span></li>

<li>Harris, Randy Allen – <dfn>The Linguistics Wars</dfn> <span class="loc">(P85.C47)</span></li>

<li>Cutting, Joan – <dfn>Pragmatics and Discourse</dfn> <span class="loc">(P99.4.P72)</span></li>

</ul>
<h2 id="pa-greek-and-latin-language-and-literature">PA: Greek and Latin language and Literature</h2>

<figure class="resright"><img src="/pix/hughes.jpg" title="These are actually pretty good and readable English translations."></figure>

<ul class="booklist">
<li>Morrison, Clinton and Barnes, David H. – <dfn>New Testament Word Lists</dfn> <span class="loc">(PA881)</span></li>

<li>Magoffin, Ralph van Deman and Henry, Margaret Young – <dfn>Latin First Year</dfn> <span class="loc">(PA2087)</span></li>

<li>Wheelock, Frederic M. – <dfn>Latin, an Introductory Course Based on Ancient Authors</dfn> <span class="loc">(PA2087.5)</span></li>

<li>Orberg, Hans H – <dfn>Roma Aeterna</dfn> <span class="loc">(PA2094.5)</span></li>

<li>Orberg, Hans H – <dfn>Colloquium Personarum</dfn> <span class="loc">(PA2095)</span></li>

<li>Orberg, Hans H – <dfn>Lingua Latina</dfn> <span class="loc">(PA2095)</span></li>

<li>Simpson, D. P. – <dfn>Cassell's Latin Dictionary</dfn> <span class="loc">(PA2365.E5)</span></li>

<li>Landis, Paul – <dfn>Four Famous Greek Plays</dfn> <span class="loc">(PA3626.A2)</span></li>

<li>Aeschylus – <dfn>The Oresteia</dfn> <span class="loc">(PA3827.A7)</span></li>

<li>Apollonius of Rhodes – <dfn>Jason and the Argonauts (Argonautica)</dfn> <span class="loc">(PA3872)</span></li>

<li>Euripides – <dfn>Three Plays of Euripides: Alcestis, Medea, the Bacchae</dfn> <span class="loc">(PA3975)</span></li>

<li>Euripides – <dfn>Alcestis and Other Plays</dfn> <span class="loc">(PA3975.A5)</span></li>

<li>Corpus Hermeticum – <dfn>Hermes Trismegistus</dfn> <span class="loc">(PA3998)</span></li>

<li>Homer – <dfn>The Iliad</dfn> <span class="loc">(PA4025.A2)</span></li>

<li>Homer – <dfn>The Odyssey</dfn> <span class="loc">(PA4025.A5)</span></li>

<li>Sophocles – <dfn>The Theban Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>The Complete Plays</dfn> <span class="loc">(PA4414.A1)</span></li>

<li>Sophocles – <dfn>Electra and Other Plays</dfn> <span class="loc">(PA4414.A2)</span></li>

<li>Feyerabend, Karl – <dfn>Greek-English Dictionary</dfn> <span class="loc">(PA445.E5)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Liddell, H. G. and Scott – <dfn>Greek-English Lexicon</dfn> <span class="loc">(PA445.E5)</span></li>

<li>Juvenal – <dfn>The Sixteen Satires</dfn> <span class="loc">(PA6447.E5)</span></li>

<li>Lucretius – <dfn>On the Nature of Things</dfn> <span class="loc">(PA6483.E5)</span></li>

<li>Hughes, Ted – <dfn>Tales from Ovid: Twenty-Four Passages from the 'Metamorphoses' by Ovid</dfn> <span class="loc">(PA6522)</span></li>

<li>Petronius – <dfn>the Satyricon and the Fragments</dfn> <span class="loc">(PA6558.E5)</span></li>

<li>Pliny the Younger – <dfn>Pliny: A Self-Portrait in Letters</dfn> <span class="loc">(PA6639.E5)</span></li>

<li>Virgil – <dfn>Aeneid</dfn> <span class="loc">(PA6807.A5)</span></li>

<li>Virgil – <dfn>The Pastoral Poems</dfn> <span class="loc">(PA6807.B7)</span></li>

</ul>
<h2 id="pc-romance-languages">PC: Romance Languages</h2>

<figure class="resright"><img src="/pix/lathrop.jpg" title="Lathrop's Course on Historical Spanish"></figure>

<ul class="booklist">
<li>Decker, Henry W. and Bernhard, Francoise – <dfn>Modern French</dfn> <span class="loc">(PC211)</span></li>

<li>Azevedo, Milton M. – <dfn>Introducción a la Lingüística Española</dfn> <span class="loc">(PC4073)</span></li>

<li>Lathrop, T. A. and Gutiérrex Cuadrado, Juan – <dfn>Curso de gramática histórica española</dfn> <span class="loc">(PC4101)</span></li>

<li>Moreno, Oscar – <dfn>Gramática avanzada del español</dfn> <span class="loc">(PC4129.E5)</span></li>

<li>Cash, Annette G. and Murray, James C. – <dfn>Teoría y técnicas de traduccón: primeras etapas</dfn> <span class="loc">(PC4498)</span></li>

<li>Gili Gaya, Samuel – <dfn>Vox: Diccionario abreviado de la lengua española</dfn> <span class="loc">(PC4625)</span></li>

</ul>
<h2 id="pd-pf-germanic-languages-and-literatures">PD-PF: Germanic Languages and Literatures</h2>
<ul class="booklist">
<li>Lambdin, Thomas O. – <dfn>An Introduction to the Gothic Language</dfn> <span class="loc">(PD1123)</span></li>

<li>Hugo – <dfn>Swedish Phrase Book</dfn> <span class="loc">(PD5121)</span></li>

<li>Warriner, John E. and Whitten, Mary E. and Friggith, Francis J. – <dfn>Warriner's English Grammar and Composition</dfn> <span class="loc">(PE1112)</span></li>

<li>Elson, William H. and Keck, Christine – <dfn>Elson Grammar School Literature Book Two</dfn> <span class="loc">(PE1121)</span></li>

<li>Mitchell, Brucew and Robinson, Fred C. – <dfn>A Guide to Old English</dfn> <span class="loc">(PE131)</span></li>

<li>Evans, Jonathan – <dfn>An Introduction to Old English</dfn> <span class="loc">(PE135)</span></li>

<li>Bright, James W. – <dfn>Bright's Anglo-Saxon Reader</dfn> <span class="loc">(PE137)</span></li>

<li>Gottschalk, Katherine and Keith Hjortshoj – <dfn>The Elements of Teaching Writing</dfn> <span class="loc">(PE1404)</span></li>

<li>Forsyth, Mark – <dfn>The Elements of Eloquence</dfn> <span class="loc">(PE1421)</span></li>

<li>McCloskey, Deirdre N. – <dfn>Economical Writing</dfn> <span class="loc">(PE1479.E35)</span></li>

<li>Sharp, Stanley Louis and Strothmann, Friedrich Wilhelm – <dfn>German Reading Grammar</dfn> <span class="loc">(PF3111)</span></li>

<li>Morgan, Baynard Quincy and Strothmann, Friedrich Wilhelm – <dfn>Reading German</dfn> <span class="loc">(PF3117)</span></li>

<li>Berlitz – <dfn>Berlitz Self-Teaching German</dfn> <span class="loc">(PF3121)</span></li>

</ul>
<h2 id="pj-pl-oriental-indo-iranian-east-asian-and-oceanian-languages">PJ-PL: Oriental, Indo-Iranian, East-Asian and Oceanian Languages</h2>

<figure class="resright"><img src="/pix/sastry.jpg" title="Sanskrit in the Development of World Thought"></figure>

<ul class="booklist">
<li>Anonymous – <dfn>The Epic of Gilgamesh</dfn> <span class="loc">(PJ3771.G5)</span></li>

<li>Wightwick, Jane and Gaafar, Mahmoud – <dfn>Mastering Arabic</dfn> <span class="loc">(PJ6307)</span></li>

<li>Luxenberg, Christoph – <dfn>The Syro-Aramaic Reading of the Koran: A Contribution to Decoding the Language of the Koran</dfn> <span class="loc">(PJ6696)</span></li>

<li>Burnell, Arthur Coke – <dfn>On the Aindra school of Sanskrit grammarians, their place in the Sanskrit and subordinate literatures</dfn> <span class="loc">(PK407)</span></li>

<li>Sastry, Vempaty Kutumba – <dfn>Sanskrit and Development of World Thought</dfn> <span class="loc">(PK423)</span></li>

<li>Elwell-Sutton, L. P. – <dfn>Elementary Persian Grammar</dfn> <span class="loc">(PK6235)</span></li>

<li>Whitney, William Dwight – <dfn>A Sanskrit Grammar: Including Both the Classical Language, and the Older Dialects, of the Veda and Brahmana</dfn> <span class="loc">(PK663)</span></li>

<li>Sutherland, Goldman – <dfn>Devavanipravesika</dfn> <span class="loc">(PK666)</span></li>

<li>Whitney, William Dwight – <dfn>The Roots, Verb-Forms, And Primary Derivatives of the Sankstrit Language: A Supplement to his Sanskrit Grammar</dfn> <span class="loc">(PK745)</span></li>

<li>DeFrancis, John – <dfn>Intermediate Chinese</dfn> <span class="loc">(PL11117)</span></li>

<li>DeFrancis, John – <dfn>Advanced Chinese</dfn> <span class="loc">(PL1121.C5)</span></li>

<li>Defense Language Institute – <dfn>Chinese: Basic Course</dfn> <span class="loc">(PL1125)</span></li>

<li>Seligman, Scott D. – <dfn>Mandarin Chinese at a Glance</dfn> <span class="loc">(PL1125.E6)</span></li>

<li>DeFrancis, John – <dfn>The Chinese Language, Fact and Fantasy</dfn> <span class="loc">(PL1171)</span></li>

<li><dfn>Oxford Chinese Dictionary</dfn> <span class="loc">(PL1455)</span></li>

<li>Waley, Arthur – <dfn>Translations from the Chinese</dfn> <span class="loc">(PL3277.E3)</span></li>

<li>Burlington, Scott – <dfn>Instant Hawaiian</dfn> <span class="loc">(PL6445)</span></li>

<li>Pukui, Mary Kawena and Elbert, Samuel H. and Mookini, Esther T. – <dfn>The Pocket Hawaiian Dictionary</dfn> <span class="loc">(PL6446)</span></li>

</ul>
<h2 id="pn-general-literature">PN: General Literature</h2>
<ul class="booklist">
<li>Butterworth, Hezekiah – <dfn>The Story of America</dfn> <span class="loc">(PN1009.A1)</span></li>

<li>Kaplar, Richard T. and Patrick D. Maines – <dfn>The Government Factor: Undermining Journalistic Ethics in the Information Age</dfn> <span class="loc">(PN4888.E8)</span></li>

<li>Schwarz, Leo W. – <dfn>Feast of Leviathan: Tales of Adventure, Faith and Love from Jewish Literature</dfn> <span class="loc">(PN6071.J5)</span></li>

<li><dfn>Treasury of Familiar Quotations</dfn> <span class="loc">(PN6081)</span></li>

<li><dfn>Reader's Digest Treasury of American Humor</dfn> <span class="loc">(PN6162)</span></li>

<li>The Onion – <dfn>Dispatches from the Tenth Circle</dfn> <span class="loc">(PN6165)</span></li>

<li>The Onion – <dfn>Our Dumb World</dfn> <span class="loc">(PN6231.A74)</span></li>

<li>Raymond, Eric S. – <dfn>The New Hacker's Dictionary</dfn> <span class="loc">(PN6231.E4)</span></li>

<li>The Onion – <dfn>Our Dumb Century</dfn> <span class="loc">(PN6231.N6)</span></li>

<li>Gómez Dávila, Nicolás – <dfn>Escolios a un texto implícito</dfn> <span class="loc">(PN6275)</span></li>

<li>Brown, Jeffrey – <dfn>Darth Vader and Son</dfn> <span class="loc">(PN6727.B7575)</span></li>

<li>Watterson, Bill – <dfn>Calvin and Hobbes: Scientific Progress Goes 'Boink'</dfn> <span class="loc">(PN6728.C34)</span></li>

<li>Lewis, C. S. – <dfn>The Discarded Image: An Introduction to Medieval and Renaissance Literature</dfn> <span class="loc">(PN671)</span></li>

</ul>
<h2 id="pq-romance-literature">PQ: Romance Literature</h2>

<figure class="resright"><img src="/pix/inferno.jpg"></figure>

<ul class="booklist">
<li>de Montaigne, Michel – <dfn>Montaigne Selected Essays</dfn> <span class="loc">(PQ1642.E6)</span></li>

<li>Morlière, Jean-Baptiste – <dfn>Tartuffe and Other Plays</dfn> <span class="loc">(PQ1842)</span></li>

<li>De Saint-Exupéry – <dfn>Sazadeo Qickek</dfn> <span class="loc">(PQ2637.A274)</span></li>

<li>Alighieri, Dante – <dfn>The Divine Comedy</dfn> <span class="loc">(PQ4315)</span></li>

<li>Alighieri, Dante – <dfn>The Inferno</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Alighieri, Dante – <dfn>I: Hell (Sayers translation)</dfn> <span class="loc">(PQ4315.2)</span></li>

<li>Eco, Umberto – <dfn>Foucault's Pendulum</dfn> <span class="loc">(PQ4864.C6)</span></li>

<li>De la Vega, Garcilaso – <dfn>Poesías</dfn> <span class="loc">(PQ6391)</span></li>

<li>Garcia Lorca, Federico – <dfn>Rosita la soltera</dfn> <span class="loc">(PQ6613.A763)</span></li>

<li>Pérez-Reverte, Arturo – <dfn>La tabla de Flandés</dfn> <span class="loc">(PQ6666.E765)</span></li>

<li>Rulfo, Juan &amp;ndash; Pedro – <dfn>y El Llano en llamas</dfn> <span class="loc">(PQ7297.R89)</span></li>

</ul>
<h2 id="pr-english-literature">PR: English Literature</h2>
<ul class="booklist">
<li>Clark, Thomas Curtis and Gillespie, Esther A. – <dfn>1000 Quotable Poems</dfn> <span class="loc">(PR1175)</span></li>

<li><dfn>Beowulf</dfn> <span class="loc">(PR1583)</span></li>

<li>Chaucer, Geoffrey – <dfn>Chaucer's Major Poetry</dfn> <span class="loc">(PR1851)</span></li>

<li>Chaucer, Geoffrey – <dfn>The Canterbury Tales</dfn> <span class="loc">(PR1870.A1)</span></li>

<li>Collis, Louise – <dfn>Memoirs of a Medieval Woman</dfn> <span class="loc">(PR2007)</span></li>

<li>Malory, Thomas – <dfn>Le Morte d'Arthur</dfn> <span class="loc">(PR2041)</span></li>

<li>Craig, W. J. – <dfn>The Complete Works of William Shakespeare</dfn> <span class="loc">(PR2753.C8)</span></li>

<li>Shakespeare, William – <dfn>Hamlet (2 copies)</dfn> <span class="loc">(PR2801.A2)</span></li>

<li>Shakespeare, William – <dfn>Macbeth</dfn> <span class="loc">(PR2823.A2)</span></li>

<li>Shakespeare, William – <dfn>A Midsummer Night's Dream</dfn> <span class="loc">(PR2827.A2)</span></li>

<li>Shakespeare, William – <dfn>The Merchant of Venice</dfn> <span class="loc">(PR2825.A2)</span></li>

<li>Shakespeare, William – <dfn>The Sonnets</dfn> <span class="loc">(PR2848.A2)</span></li>

<li>Crystal, David – <dfn>The Oxford Dictionary of Original Shakespearean Pronunciation</dfn> <span class="loc">(PR2892)</span></li>

<li>Bunyan, John – <dfn>Pilgrim's Progress</dfn> <span class="loc">(PR3330)</span></li>

<li>Milton, John – <dfn>Paradise Lost and Other Poems</dfn> <span class="loc">(PR3560)</span></li>

<li>Coleridge, Samuel Taylor – <dfn>The Rime of the Ancient Mariner</dfn> <span class="loc">(PR4479)</span></li>

<li>Dickens, Charles – <dfn>Great Expectations</dfn> <span class="loc">(PR4560)</span></li>

<li>Shaw, George Bernard – <dfn>Pygmalion</dfn> <span class="loc">(PR5363)</span></li>

<li>Stevenson, Robert Louis – <dfn>The Black Arrow</dfn> <span class="loc">(PR5484)</span></li>

<li>Stevenson, Robert Louis – <dfn>New Arabian Nights</dfn> <span class="loc">(PR5484)</span></li>

<li>Wells, H. G. – <dfn>The Island of Dr. Moreau</dfn> <span class="loc">(PR5774)</span></li>

<li>Wilde, Oscar – <dfn>The Importance of Being Earnest</dfn> <span class="loc">(PR5818)</span></li>

<li>Christie, Agatha – <dfn>Death on the Nile</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Christie, Agatha – <dfn>The Nursery Rhyme Murders</dfn> <span class="loc">(PR6005.H66)</span></li>

<li>Golding, William – <dfn>Lord of the Flies</dfn> <span class="loc">(PR6013.O35)</span></li>

<li>Lewis, C. S. – <dfn>The Lion, the Witch and the Wardrobe</dfn> <span class="loc">(PR6023.E926)</span></li>

<li>Huxley, Aldous – <dfn>Brave New World</dfn> <span class="loc">(PR6015.U9)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Lord of the Rings, One-Volume Edition</dfn> <span class="loc">(PR6039.O32)</span></li>

<li>White, T. H. – <dfn>The Once and Future King</dfn> <span class="loc">(PR6045.H2)</span></li>

<li>Adams, Douglas – <dfn>Life, the Universe and Everything</dfn> <span class="loc">(PR6051.D3352)</span></li>

<li>Erickson, Paul – <dfn>Doctor Who: The Ark</dfn> <span class="loc">(PR6052.R449)</span></li>

<li>Burgess, Anthony – <dfn>A Clockwork Orange</dfn> <span class="loc">(PR6052.U638)</span></li>

<li>Grimwade, Peter – <dfn>Doctor Who: Planet of Fire</dfn> <span class="loc">(PR6057.R545)</span></li>

<li>Halleck, Reuben Post – <dfn>History of English Literature</dfn> <span class="loc">(PR85)</span></li>

<li>Achebe, Chinua – <dfn>Things Fall Apart</dfn> <span class="loc">(PR9387.9.A3)</span></li>

</ul>
<h2 id="ps-american-literature">PS: American Literature</h2>

<figure class="resright"><img src="/pix/lovecraft.jpg"></figure>

<ul class="booklist">
<li>Twain, Mark – <dfn>A Connecticut Yankee in King Arthur's Court</dfn> <span class="loc">(PS1308)</span></li>

<li>Hawthorne, Nathaniel – <dfn>The Scarlet Letter</dfn> <span class="loc">(PS1868)</span></li>

<li>Poe, Edgar Allan – <dfn>Edgar Allan Poe Reader</dfn> <span class="loc">(PS2603)</span></li>

<li>Poe, Edgar Allen – <dfn>Tales of Terror and Detection</dfn> <span class="loc">(PS2612)</span></li>

<li>Thoreau, Henry David – <dfn>Walden</dfn> <span class="loc">(PS3048)</span></li>

<li>Wallace, Lew – <dfn>Ben Hur</dfn> <span class="loc">(PS3134)</span></li>

<li>Faulkner, William – <dfn>Light in August</dfn> <span class="loc">(PS3511.A86)</span></li>

<li>Fitzgerald, F. Scott – <dfn>The Great Gatsby</dfn> <span class="loc">(PS3511.I9)</span></li>

<li>Heinlein, Robert A. – <dfn>For Us, the Living</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Heinlein, Robert A. – <dfn>The Moon is a Harsh Mistress</dfn> <span class="loc">(PS3515.E288)</span></li>

<li>Lovecraft, H. P. – <dfn>Great Tales of Horror</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Case of Charles Dexter Ward</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Doom That Came to Sarnath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Dream Quest of Unknown Kadath</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Lovecraft, H. P. – <dfn>The Tomb</dfn> <span class="loc">(PS3523.O833)</span></li>

<li>Rodgers, Marion Elizabeth – <dfn>Mencken &amp; Sara</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Mencken, H. L. – <dfn>The Vintage Mencken</dfn> <span class="loc">(PS3525.E43)</span></li>

<li>Rand, Ayn – <dfn>Atlas Shugged</dfn> <span class="loc">(PS3535.A547)</span></li>

<li>Skinner, B. F. – <dfn>Walden Two</dfn> <span class="loc">(PS3537.K527)</span></li>

<li>Smith, Clark Ashton – <dfn>Hyperborea</dfn> <span class="loc">(PS3537.M335)</span></li>

<li>Bear, Greg – <dfn>Darwin's Radio</dfn> <span class="loc">(PS3552.E157)</span></li>

<li>Card, Orson Scott – <dfn>Ender's Game</dfn> <span class="loc">(PS3553.A655)</span></li>

<li>Crichton, Michael – <dfn>Congo</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Jurassic Park</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Crichton, Michael – <dfn>Timeline</dfn> <span class="loc">(PS3553.R48)</span></li>

<li>Dick, Philip K. – <dfn>Dr. Bloodmoney</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Dick, Philip K. – <dfn>Flow My Tears, The Policeman Said</dfn> <span class="loc">(PS3554.I3)</span></li>

<li>Herbert, Frank – <dfn>Dune</dfn> <span class="loc">(PS3558.E63)</span></li>

<li>Jordan, Robert – <dfn>The Eye of the World</dfn> <span class="loc">(PS3560.O7617)</span></li>

<li>King, Stephen – <dfn>The Bazaar of Bad Dreams</dfn> <span class="loc">(PS3561.I483)</span></li>

<li>Myers, Bill – <dfn>Blood of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Fire of Heaven</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Myers, Bill – <dfn>Threshold</dfn> <span class="loc">(PS3563.Y36)</span></li>

<li>Quinn, Daniel – <dfn>Ishmael: An Adventure of the Mind and Spirit</dfn> <span class="loc">(PS3567.U338)</span></li>

<li>Pearl, Matthew – <dfn>The Dante Club</dfn> <span class="loc">(PS3616.E25)</span></li>

<li>Asimov, Isaac – <dfn>Before the Golden Age: A Science Fiction Anthology of the 1930's</dfn> <span class="loc">(PS648.S3)</span></li>

<li>Saramago, José – <dfn>Todos los nombres</dfn> <span class="loc">(PS9281.A66)</span></li>

</ul>
<h2 id="pq-pz-other-literature">PQ-PZ: Other Literature</h2>

<figure class="resright"><img src="/pix/edda.jpg"></figure>

<ul class="booklist">
<li>Voltaire – <dfn>Candide, Zadig and selected stories</dfn> <span class="loc">(PQ2081.E5)</span></li>

<li>Hesse, Hermann – <dfn>Siddhartha</dfn> <span class="loc">(PT2617.E85)</span></li>

<li>Hesse, Hermann – <dfn>The Glass Bead Game</dfn> <span class="loc">(PT2617.E85 G513)</span></li>

<li>Sturluson, Snorri – <dfn>Poetic Edda</dfn> <span class="loc">(PT7235)</span></li>

<li>Sturluson, Snorri – <dfn>Prose Edda</dfn> <span class="loc">(PT7313.E5)</span></li>

<li>Borges, Jorge Luis – <dfn>Ficciones</dfn> <span class="loc">(PW7797.B635)</span></li>

<li>Connor, Ralph – <dfn>Black Rock: a Tale of the Selkirks</dfn> <span class="loc">(PZ3.G654)</span></li>

<li>Roberts, James Hall – <dfn>The Q Document</dfn> <span class="loc">(PZ4.D913)</span></li>

<li>Tolkien, J. R. R. – <dfn>The Hobbit</dfn> <span class="loc">(PZ7.T5744)</span></li>

<li>Wilder, Laura Ingalls – <dfn>Little House (entire series)</dfn> <span class="loc">(PZ7.W6461)</span></li>

<li>Jacobs, Joseph – <dfn>Favorite Celtic Fairy Tales</dfn> <span class="loc">(PZ8)</span></li>

<li>Baum, L. Frank – <dfn>The Wizard of Oz</dfn> <span class="loc">(PZ8.B327)</span></li>

<li><dfn>The Brothers Grimm Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

<li><dfn>The Complete Grimm's Fairy Tales</dfn> <span class="loc">(PZ8.G882)</span></li>

</ul>
<h2 id="qa-general-science">QA: General Science</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=hVxvLd6cF0k"><img src="/pix/againstmethod.jpg"></a></figure>

<ul class="booklist">
<li>de Santillanna, Giorgio – <dfn>The Origins of Scientific Thought: from Anazimander to Proclus, 600 B.C. to 300 A.D.</dfn> <span class="loc">(Q125)</span></li>

<li>Gardner, Martin – <dfn>Great Essays in Science</dfn> <span class="loc">(Q171)</span></li>

<li>Kuhn, Thomas – <dfn>The Structure of Scientific Revolutions</dfn> <span class="loc">(Q175)</span> <a href="https://notrelated.xyz/#02.01"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Wiener, Norbert – <dfn>The Human Use of Human Beings</dfn> <span class="loc">(Q175)</span></li>

<li>Feyerabend, Paul – <dfn>Against Method </dfn> <span class="loc">(Q175)</span></li>

<li>Motterlini, Matteo – <dfn>For and Against Method: Including Lakatos's Lectures on Scientific Method and the Lakatos-Feyerabend Correspondence </dfn> <span class="loc">(Q175.3)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>Antifragile</dfn> <span class="loc">(Q375)</span></li>

<li>Taleb, Nassim Nicholas – <dfn>The Black Swan</dfn> <span class="loc">(Q375)</span></li>

</ul>
<h2 id="qa-mathematics">QA: Mathematics</h2>
<ul class="booklist">
<li>Sawyer, W. W. – <dfn>Mathematician's Delight</dfn> <span class="loc">(QA37)</span></li>

<li>Birns, Peter and Brown, Patrick and Muster, John C. C. – <dfn>Unix for People</dfn> <span class="loc">(QA76.6)</span></li>

<li>Raymond, Eric S. – <dfn>The Cathedral and the Bazaar</dfn> <span class="loc">(QA76.76.O63)</span></li>

<li>Bellos, Alex – <dfn>Here's Looking at Euclid</dfn> <span class="loc">(QA141.15)</span></li>

<li>Nyberg, Joseph A. – <dfn>Second Course in Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Wentworth, G. A. – <dfn>New School Algebra</dfn> <span class="loc">(QA152)</span></li>

<li>Hart, William – <dfn>College Algebra</dfn> <span class="loc">(QA154)</span></li>

<li>Lial, Margaret L. and Miller, Charles D. – <dfn>Algebra and Trigonometry</dfn> <span class="loc">(QA154.2)</span></li>

<li>Sokal, Alan and Bricmont, Jean – <dfn>Fashionable Nonsense: Postmodern Intellectuals' Abuse of Science</dfn> <span class="loc">(QA175)</span></li>

<li>Neugebauer, Otto – <dfn>The Exact Sciences in Antiquity</dfn> <span class="loc">(QA22)</span></li>

<li>Bharati Krsna Thirthaji Maharaja – <dfn>Vedic Mathematics</dfn> <span class="loc">(QA27.I4)</span></li>

<li>Christian, Robert R. – <dfn>Introduction to Logic and Sets</dfn> <span class="loc">(QA248)</span></li>

<li>Davis, Morton D. – <dfn>Game Theory: A Nontechnical Introduction</dfn> <span class="loc">(QA269)</span></li>

<li>Friedman, Avner – <dfn>Differential Games</dfn> <span class="loc">(QA272)</span></li>

<li>Takahashi, Shin – <dfn>The Manga Guide to Statistics</dfn> <span class="loc">(QA276)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 1-10</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny and Gulick, Frances – <dfn>Calculus with Analytic Geometry Solutions Manual for Chapters 10-15 and Appendices</dfn> <span class="loc">(QA303)</span></li>

<li>Smith, Edward S. and Salkover, Meyer and Justive, Howard K. – <dfn>Unified Calculus</dfn> <span class="loc">(QA303)</span></li>

<li>Elis, Robert and Gulick, Denny – <dfn>Calculus with Analytic Geometry</dfn> <span class="loc">(QA33)</span></li>

<li>Sperling, Abraham and Stuart, Monroe – <dfn>Mathematics (Made Simple Self-Teaching Library)</dfn> <span class="loc">(QA39.2)</span></li>

<li>Horblit, Marcus and Nielson, Kaj L. – <dfn>Problems in Plane Geometry with Solutions</dfn> <span class="loc">(QA459)</span></li>

<li>Shively, Levi S. – <dfn>Modern Geometry</dfn> <span class="loc">(QA473)</span></li>

<li>Nelson, Alfred L. and Folley, Karl W. – <dfn>Plane and Spherical Trigonometry</dfn> <span class="loc">(QA531.N45)</span></li>

<li>Love, Clyde E. – <dfn>Analytic Geometry</dfn> <span class="loc">(QA551)</span></li>

<li>Hutton, Graham – <dfn>Programming in Haskell</dfn> <span class="loc">(QA76.62)</span></li>

<li>Kernighan, Brian W. and Ritchie, Dennis M. – <dfn>The C Programming Language</dfn> <span class="loc">(QA76.73.C15)</span></li>

<li>Barski, Conrad – <dfn>Land of Lisp</dfn> <span class="loc">(QA76.76.C672)</span></li>

<li>Hofstadter, Douglas – <dfn>Gödel, Escher, Bach</dfn> <span class="loc">(QA9.8)</span></li>

<li>Emmet, E. R. – <dfn>Brain Puzzler's Delight</dfn> <span class="loc">(QA95)</span></li>

<li>Emmet, E. R. – <dfn>Puzzles for Pleasure</dfn> <span class="loc">(QA95)</span></li>

<li>Gardner, Martin – <dfn>aha! Gotcha, Paradoxes to puzzle and delight</dfn> <span class="loc">(QA95)</span></li>

<li>Heafford, Philip – <dfn>The Math Entertainer</dfn> <span class="loc">(QA95)</span></li>

</ul>
<h2 id="qb-qr-other-sciences">QB-QR: Other Sciences</h2>
<ul class="booklist">
<li>Hawking, Stephen W. – <dfn>A Brief History of Time</dfn> <span class="loc">(QB981)</span></li>

<li>Lerner, Eric – <dfn>The Big Bang Never Happened</dfn> <span class="loc">(QB991.B54)</span></li>

<li>McEvoy, J. P. and Zarate, Oscar – <dfn>Quantum Theory, A Graphic Guide</dfn> <span class="loc">(QC173.98)</span></li>

<li>Booker, Christopher – <dfn>The Real Global Warming Disaster</dfn> <span class="loc">(QC981.8.G56)</span></li>

<li>Greenburg, Arthur – <dfn>From Alchemy to Chemistry in Picture and Story</dfn> <span class="loc">(QD11)</span></li>

<li>Valentine, Basil – <dfn>Of Natural and Supernatural Things: Also, of the First Tincture, Root, and Spirit of Metals and Minerals: How the Same are Conceived, Generated, Brought Forth, Changed and Augmented</dfn> <span class="loc">(QD25)</span></li>

<li>Watson, James – <dfn>The Double Helix</dfn> <span class="loc">(QH31.D434)</span></li>

<li>Fodor, Jerry and Piattelli Palmarini, Massimo – <dfn>What Darwin Got Wrong</dfn> <span class="loc">(QH375)</span> <a href="https://notrelated.xyz/#01.06"><img src="/pix/nr.svg" alt="notrelated episode"></a></li>

<li>Kadans, Joseph M. – <dfn>Modern Encyclopedia of Herbs</dfn> <span class="loc">(QK99.A1)</span></li>

<li>McFarland, J. Horace – <dfn>Getting Acquainted with Trees</dfn> <span class="loc">(QK482)</span></li>

<li>Kurzweil, Ray – <dfn>The Singularity is Near</dfn> <span class="loc">(QP376)</span></li>

<li>Kandel, Eric R. and Schwartz, James H. and Jessell, Thomas M. – <dfn>Essentials of Neural Science and Behavior</dfn> <span class="loc">(QP355.2)</span></li>

</ul>
<h2 id="r-medicine">R: Medicine</h2>
<ul class="booklist">
<li>FC&amp;A – <dfn>The Folk Remedy Encyclopedia: Olive Oil, Vinegar, Honey and 1,001 Other Home Remedies</dfn> <span class="loc">(R733)</span></li>

<li><dfn>Better Homes and Gardens Family Medical Guide</dfn> <span class="loc">(RC81.A2)</span></li>

<li><dfn>The Encyclopedia of Common Diseases</dfn> <span class="loc">(RC81.A2)</span></li>

</ul>
<h2 id="s-t-agriculture-and-technology">S-T: Agriculture and Technology</h2>

<figure class="resright"><a href="https://www.youtube.com/watch?v=YRNKjQg6y-c"><img src="/pix/salatin.jpg"></a></figure>

<ul class="booklist">
<li>Mollison, Bill – <dfn>Introduction to Permaculture</dfn> <span class="loc">(S494.5.P47)</span></li>

<li>Salatin, Joel – <dfn>Everything I Want to Do Is Illegal</dfn> <span class="loc">(S605.5)</span></li>

<li>David the Good – <dfn>Totally Crazy Easy Florida Gardening</dfn></li>

<li>Seymour, John – <dfn>The Complete Book of Self-Sufficiency</dfn> <span class="loc">(S605.5)</span></li>

<li>Cobleigh, Rolfe – <dfn>Handy Farm Devices and How to Make Them (2 copies)</dfn> <span class="loc">(S676)</span></li>

<li>Seymour, John – <dfn>Gardener's Delight</dfn> <span class="loc">(SB322)</span></li>

<li>Seymour, John – <dfn>The Self-Sufficient Gardener</dfn> <span class="loc">(SB324.3)</span></li>

<li>Haring, Elda – <dfn>The Seedling Handbook</dfn> <span class="loc">(SB405)</span></li>

<li>Abraham, George – <dfn>The Green Thumb Garden Handbook</dfn> <span class="loc">(SB453)</span></li>

<li><dfn>Reader's Digest Illustrated Guide to Gardening</dfn> <span class="loc">(SB453)</span></li>

<li>Kaczynski, Theodore John – <dfn>Technological Slavery</dfn> <span class="loc">(T14.5)</span></li>

<li>Kaczynski, Theodore John – <dfn>Anti-Tech Revolution: Why and How</dfn> <span class="loc">(T14.5)</span></li>

<li>Macaulay, David and Ardleym Neil – <dfn>The Way Things Work</dfn> <span class="loc">(T47)</span></li>

<li>Slater, Robert and Li, Ling and Li, Wen – <dfn>Portraits in Silicon</dfn> <span class="loc">(TK7885.2)</span></li>

<li>Bishop, Michael and Zimmerman, Holmes – <dfn>Detailing Cars and Trucks</dfn> <span class="loc">(TL152)</span></li>

<li>Allaby, Michael and Lovelock, James – <dfn>The Greening of Mars</dfn> <span class="loc">(TL795.7)</span></li>

<li>Abbey, Barbara – <dfn>The Complete Book of Knitting</dfn> <span class="loc">(TT820)</span></li>

<li>Bishop, Jack – <dfn>Vegetables Every Day</dfn> <span class="loc">(TX801)</span></li>

<li>Lo, Kenneth – <dfn>Chinese Regional Cooking</dfn> <span class="loc">(TX724.5.C5)</span></li>

</ul>
<h2 id="books-as-of-yet-unsorted">Books as of yet unsorted</h2>
<ul class="booklist">
<li>Seb Falk – <dfn>The Light Ages: The Surprising Story of Medieval Science</dfn></li>

<li><dfn>The Penny Catechism: A Catechism of Christian Doctrine</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese Reader, Part 1</dfn></li>

<li>DeFrancis, John – <dfn>Beginning Chinese</dfn></li>

<li>Flame Tree Publishing – <dfn>Gothic Fantasy: Lost Worlds Short Stories</dfn></li>

<li>Lee, Christopher – <dfn>This Sceptered Isle 55 BC to 1901</dfn></li>

<li>Malice, Michael – <dfn>Dear Reader</dfn></li>

<li>McCloskey, Deirdre N. – <dfn>Economic Writing</dfn></li>

<li>Meyer, Jerome S. – <dfn>The Provocative Puzzler</dfn></li>

<li>Parikh, Prashant – <dfn>Language and Equilibrium</dfn></li>

<li>Reed, Lawrence W. – <dfn>Great Myths of the Great Depression</dfn></li>

<li><dfn>Using HTML4, Java 1.1, and Javascript 1.2</dfn></li>

<li>Valizadeh, Roosh – <dfn>Game</dfn></li>

<li>Vikernes, Varg – <dfn>MYFAROG 2.6</dfn></li>

</ul>
<div style="clear:both" class="taglist">Read related articles:<br><a id="tag_personal" href="https://lukesmith.xyz/tags/personal">Personal</a> · <a id="tag_science" href="https://lukesmith.xyz/tags/science">Science</a> · <a id="tag_tradition" href="https://lukesmith.xyz/tags/tradition">Tradition</a> · <a id="tag_lifestyle" href="https://lukesmith.xyz/tags/lifestyle">Lifestyle</a> · <a id="tag_philosophy" href="https://lukesmith.xyz/tags/philosophy">Philosophy</a></div>
<br clear="both">
</article>
</main>
<footer>
	<a href="https://lukesmith.xyz">https://lukesmith.xyz</a>

	<p>
	<img class="lw" src="/pix/btc.svg">Bitcoin (<a href="/pix/btc-logo.png">QR</a>): <code>bc1qkyvknjap3cjtgfqd5qwc0q2ygry7nep7d4t57y</code>
	<br>
	<img class="lw" src="/pix/xmr.svg">Monero (<a href="/pix/xmr-logo.png">QR</a>): <code class="crypto">48jewbtxe4jU3MnzJFjTs3gVFWh2nRrAMWdUuUd7Ubo375LL4SjLTnMRKBrXburvEh38QSNLrJy3EateykVCypnm6gcT9bh</code>
	</p><p><a href="/index.xml"><img src="/rss.svg" style="max-height:1.5em" alt="RSS Feed" title="Subscribe via RSS for updates."></a>
</p></footer>


</body></html>
