---
layout: default
title: Uyanga Turmunkh
---

<section id="about" class="home-section">
<div class="container">
<div class="row">
<div class="col-xs-12 col-md-4">
  <div id="profile">
    <div class="portrait" style="background-image: url('{{ site.baseurl }}/assets/headshot.png');"></div>
    <h2>Uyanga Turmunkh</h2>
    <h3>Professional Title</h3>
    <h3><a href="SCHOLAR_LINK" target="_blank">Institution / Affiliation</a></h3>
    <ul class="network-icon">
      <li><a href="SCHOLAR_LINK" target="_blank"><i class="ai ai-google-scholar big-icon"></i></a></li>
      <li><a href="LINKEDIN_LINK" target="_blank"><i class="fa fa-linkedin big-icon"></i></a></li>
    </ul>
  </div>
</div>

<div class="col-xs-12 col-md-8">
  ## Short Biography
  Short bio paragraph goes here. Replace with content from the CV.

  [Download CV]({{ site.baseurl }}/assets/cv.pdf)

  ### Research Interests
  - Behavioral and experimental economics
  - Decision theory
  - Market design
</div>
</div>
</div>
</section>

<section id="publications" class="home-section">
<div class="container">
  ## Publications
  <ul>
  {% for p in site.data.publications %}
    <li><strong>{{ p.title }}</strong><br>{{ p.authors }} · {{ p.venue }}<br>
    {% if p.pub_link %}<a href="{{ p.pub_link }}" target="_blank">Published version</a>{% endif %}
    {% if p.data_link %} · <a href="{{ p.data_link }}" target="_blank">Data & files</a>{% endif %}
    </li>
  {% endfor %}
  </ul>
</div>
</section>

<section id="projects" class="home-section">
<div class="container">
  ## Ongoing Projects
  <ul>
  {% for w in site.data.projects %}
    <li><strong>{{ w.title }}</strong>{% if w.note %} · {{ w.note }}{% endif %}
    {% if w.link %}<br><a href="{{ w.link }}" target="_blank">Link</a>{% endif %}</li>
  {% endfor %}
  </ul>
</div>
</section>

<section id="contact" class="home-section">
<div class="container">
  ## Contact
  Email: [YOUR_EMAIL](mailto:YOUR_EMAIL)  
  Google Scholar: [Scholar](SCHOLAR_LINK)
</div>
</section>
