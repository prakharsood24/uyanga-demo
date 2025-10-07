---
layout: default
title: Uyanga Turmunkh
---

<section id="bio" class="section">
## Bio
Short bio paragraph for the draft. Replace with content from the CV.

[Download CV]({{ site.baseurl }}/assets/cv.pdf)
</section>

<section id="publications" class="section">
## Publications
<ul class="list">
{% for p in site.data.publications %}
<li class="item">
  <strong>{{ p.title }}</strong><br>
  <span class="meta">{{ p.authors }} <span class="dot">·</span> {{ p.venue }}</span><br>
  {% if p.pub_link %}<a href="{{ p.pub_link }}" target="_blank" rel="noopener">Published version</a>{% endif %}
  {% if p.data_link %} <span class="dot">·</span> <a href="{{ p.data_link }}" target="_blank" rel="noopener">Data and files</a>{% endif %}
</li>
{% endfor %}
</ul>
</section>

<section id="ongoing" class="section">
## Ongoing projects
<ul class="list">
{% for w in site.data.ongoing %}
<li class="item">
  <strong>{{ w.title }}</strong>
  {% if w.note %}<span class="meta"> <span class="dot">·</span> {{ w.note }}</span>{% endif %}<br>
  {% if w.link %}<a href="{{ w.link }}" target="_blank" rel="noopener">Link</a>{% endif %}
</li>
{% endfor %}
</ul>
</section>

<section id="contact" class="section">
## Contact
Email: <a href="mailto:YOUR_EMAIL">YOUR_EMAIL</a><br>
Google Scholar: <a href="SCHOLAR_LINK" target="_blank" rel="noopener">Scholar</a>
</section>
