---
layout: default
title: Uyanga Turmunkh
---

<section id="about" class="home-section">
<div class="container">
<div class="row">
<div class="col-xs-12 col-md-4">
  <div id="profile">
    <div class="portrait" style="background-image: url('{{ site.baseurl }}/assets/turmunkh_bright.png');"></div>
    <h2>Uyanga Turmunkh</h2>
    <h3>Associate Professor</h3>
    <h3><a href="SCHOLAR_LINK" target="_blank">Department of Economics and Quantitative Methods<br />
IESEG School of Management, Lille, France</a></h3>
    <ul class="network-icon">
      <li><a href="[SCHOLAR_LINK](https://scholar.google.com/citations?user=3NgcfZIAAAAJ&hl=en)" target="_blank"><i class="ai ai-google-scholar big-icon"></i></a></li>
      <li><a href="[LINKEDIN_LINK](https://www.linkedin.com/in/uyangaturmunkh/)" target="_blank"><i class="fa fa-linkedin big-icon"></i></a></li>
    </ul>
  </div>
</div>

<div class="col-xs-12 col-md-8">
  ## Short Biography
  Judgment and decision-making, risk and ambiguity, environmental problems and human behaviour,
cooperation, communication, gender

  [Download CV]({{ site.baseurl }}/assets/Turmunkh_CV.pdf)

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
