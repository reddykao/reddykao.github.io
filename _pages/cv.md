---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  h1, h2, h3, h4, h5, h6 {
    color: #2E8B57; /* Sea Green */
  }
  p, li {
    color: #4682B4; /* Steel Blue */
  }
  .cv-section {
    background-color: #F0F8FF; /* Alice Blue */
    padding: 10px;
    border-radius: 5px;
    margin-bottom: 10px;
  }
  .cv-section ul {
    list-style-type: square;
  }
</style>

<div class="cv-section">
  <h2>Education</h2>
  <ul>
    <li>M.S. in Graduate Institute of Biomedical Electronics and Bioinformatics, National Taiwan University, 2024 (expected)</li>
    <li>B.S. in Electronics and Electrical Engineering, GitHub University, 2019</li>
    <li>B.S. in Digital Healthcare, GitHub University, 2019</li>
  </ul>
</div>

<div class="cv-section">
  <h2>Work experience</h2>
  <ul>
    <li>Spring 2024: Research Assistant
      <ul>
        <li>National Taiwan Univeristy Hospital (NTUH)</li>
        <li>Duties include: Updates and improvements to template</li>
        <li>Supervisor: Dr</li>
      </ul>
    </li>
    <li>Fall 2015: Research Assistant
      <ul>
        <li>GitHub University</li>
        <li>Duties included: Merging pull requests</li>
        <li>Supervisor: Professor Hub</li>
      </ul>
    </li>
    <li>Summer 2015: Research Assistant
      <ul>
        <li>GitHub University</li>
        <li>Duties included: Tagging issues</li>
        <li>Supervisor: Professor Git</li>
      </ul>
    </li>
  </ul>
</div>

<div class="cv-section">
  <h2>Skills</h2>
  <ul>
    <li>Skill 1</li>
    <li>Skill 2
      <ul>
        <li>Sub-skill 2.1</li>
        <li>Sub-skill 2.2</li>
        <li>Sub-skill 2.3</li>
      </ul>
    </li>
    <li>Skill 3</li>
  </ul>
</div>

<div class="cv-section">
  <h2>Publications</h2>
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
</div>

<div class="cv-section">
  <h2>Talks</h2>
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
</div>

<div class="cv-section">
  <h2>Teaching</h2>
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
</div>

<div class="cv-section">
  <h2>Service and leadership</h2>
  <ul>
    <li>Currently signed in to 43 different slack teams</li>
  </ul>
</div>
