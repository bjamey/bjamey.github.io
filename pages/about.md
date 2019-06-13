---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}**,<br>
And this is all about me.<br>
So let look at what I can offer.

<div class="row">
{% include skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include skills.html title="Real Life Skills" source=site.data.irl-skills %}
</div>

<div class="row">
{% include timeline.html %}
</div>