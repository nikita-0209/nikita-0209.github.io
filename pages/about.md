---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

Hey, there! I am **{{ site.author.name }}** <br>
I am a passionate professional and strive for perfection. I appreciate constructive criticism. I am known for my dedication and meticulous nature. I have a knack for devising simple ways to crack seemingly complex problems.
<!-- I am a tech enthusiast. I am a big fan of the royal family, chicken and not writing regularly. My hobbies change like moods. I love experimenting. No, not a cliche line, I really do!. I've tried my hand at product management, research, If you know how life works, mail me? -->

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
