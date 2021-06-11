---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

Hey, there! I am **{{ site.author.name }}** <br>
I just completed my junior year at BITS Pilani. Personality-wise, I’m an outgoing introvert. Oxymoron, huh? But trust me, it’s actually a thing!  <br> I am a tech enthusiast. I am a big fan of the royal family, chicken and not writing regularly. In my free time, I like to scroll through my LinkedIn feed and sleep!  <br>
Oh and my birthday is on September 2 and I love surprise gifts! xD  <br>
Now that you know a bit about me I would love to know more about you. So drop me an email, and let's connect!
<!-- If you know how life works, mail me? -->

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
