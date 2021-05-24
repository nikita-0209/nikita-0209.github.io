---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

Hi I am **{{ site.author.name }}** <br>
I am known for my dedication and meticulous nature. I have a knack for devising simple ways to crack seemingly complex problems. I am currently pursuing a double major in Physics and Computer Science at BITS Pilani. 
<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. -->

<div class="row">
{% include about/skills.html title="Programming" source=site.data.programming-skills %}
{% include about/skills.html title="Deep Learning" source=site.data.dl-skills %}
</div>
<div class="row">
{% include about/skills.html title="Framework" source=site.data.framework-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

# **Education**
<div class="row">
{% include about/timeline.html %}
</div>
