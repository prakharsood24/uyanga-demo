---
layout: default
title: Uyanga Turmunkh
---

<!-- === ABOUT SECTION === -->
<section id="about" class="home-section">
  <div class="container">
    <div class="row">
      <!-- LEFT COLUMN: photo & info -->
      <div class="col-xs-12 col-md-5 text-center">
        <img src="{{ site.baseurl }}/assets/turmunkh_bright.png" alt="Uyanga Turmunkh" class="img-circle img-responsive center-block" style="width:200px; height:200px; object-fit:cover; margin-bottom:20px;">
        <h2 style="margin-top:0;">Uyanga Turmunkh</h2>
        <h4>Associate Professor</h4>
        <p style="color:#555; font-size:15px;">
          <a href="[https://www.ieseg.fr/en/faculty/research-department/economics/](https://www.ieseg.fr/en/faculty-and-research/departments/economics-and-quantitative-methods/)" target="_blank">Department of Economics and Quantitative Methods</a><br>
          IESEG School of Management, Lille, France
        </p>

        <ul class="list-inline" style="margin-top:10px;">
          <li><a href="https://scholar.google.com/citations?user=3NgcfZIAAAAJ&hl=en" target="_blank"><i class="ai ai-google-scholar big-icon"></i></a></li>
          <li><a href="https://www.linkedin.com/in/uyangaturmunkh" target="_blank"><i class="fa fa-linkedin big-icon"></i></a></li>
        </ul>
      </div>

      <!-- RIGHT COLUMN: biography text -->
      <div class="col-xs-12 col-md-6 col-md-offset-1">
        <h1>Short Biography</h1>
        <p>
         Bio Here
        </p>
        <p>
          <a href="{{ site.baseurl }}/assets/Turmunkh_CV.pdf" target="_blank">Download CV</a>
        </p>
    <div class="col-md-6">
        <h3>Interests</h3>
        <ul>
          <li>Judgment and decision-making</li>
          <li>Risk and ambiguity</li>
          <li>Environmental problems</li>
          <li>Cooperation</li>
          <li>Communication</li>
          <li>Gender</li>
        </ul>
    </div>
    <div class="col-md-6">
      <h3>Education</h3>
      <ul>
          <li>Judgment and decision-making</li>
          <li>Risk and ambiguity</li>
          <li>Environmental problems</li>
          <li>Cooperation</li>
          <li>Communication</li>
          <li>Gender</li>
        </ul>
      </div>
      </div>
    </div>
  </div>
</section>

<!-- === PUBLICATIONS === -->
<section id="publications" class="home-section">
  <div class="container">
    <div class="row">
      <div class="col-xs-12">
        <h1>Publications</h1>
        <ul style="list-style:none; padding-left:0;">
          {% for p in site.data.publications %}
          <li style="margin-bottom:15px;">
            <strong>{{ p.title }}</strong><br>
            <span style="color:#666;">{{ p.authors }} · {{ p.venue }}</span><br>
            {% if p.pub_link %}<a href="{{ p.pub_link }}" target="_blank">Published version</a>{% endif %}
            {% if p.data_link %} · <a href="{{ p.data_link }}" target="_blank">Data & files</a>{% endif %}
          </li>
          {% endfor %}
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- === ONGOING PROJECTS === -->
<section id="projects" class="home-section">
  <div class="container">
    <div class="row">
      <div class="col-xs-12">
        <h1>Ongoing Projects</h1>
        <ul style="list-style:none; padding-left:0;">
          {% for w in site.data.ongoing %}
          <li style="margin-bottom:15px;">
            <strong>{{ w.title }}</strong>{% if w.note %} · <span style="color:#666;">{{ w.note }}</span>{% endif %}<br>
            {% if w.link %}<a href="{{ w.link }}" target="_blank">Project URL</a>{% endif %}
          </li>
          {% endfor %}
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- === CONTACT === -->
<section id="contact" class="home-section">
  <div class="container">
    <div class="row">
      <div class="col-xs-12 col-md-12">
        <h1>Contact</h1>
      </div>
      <div class="col-xs-12 col-md-12">
        <ul class="fa-ul" style="margin-left:0;">
          <li><i class="fa-li fa fa-envelope"></i> <a href="mailto:u.turmunkh@ieseg.fr">u.turmunkh@ieseg.fr</a></li>
          <li><i class="fa-li fa fa-map-marker"></i> IESEG School of Management, Lille, France</li>
        </ul>
      </div>
    </div>
  </div>
</section>
