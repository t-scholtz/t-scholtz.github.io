---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="text-align:center; margin-bottom:0; padding-bottom:0;margin-top:0;">
  <!-- Profile Image (circular) -->
  <picture style="margin-top:0;">
    <img src="/images/{{ site.author.avatar }}" alt="Profile picture." 
         class="profile-photo" 
         style="border-radius:50%; width:280px; height:280px; object-fit:cover; margin-bottom:1rem;">
  </picture>
  <!-- Name -->
  <h1 class="header-name" itemprop="name" style="margin-bottom:0rem;">{{ site.author.name }}</h1>
  <!-- Contact Icons / Links -->
 <div id="contact" style="display:flex; flex-wrap:wrap; justify-content:center; gap:1.5rem; margin-bottom:0; padding-bottom:0; margin-top:0;">
  <!-- Email -->
  {% if site.author.email %}
    <div class="cv-item">
      <a href="mailto:{{ site.author.email }}" title="Email">
        <i class="fas fa-envelope"></i>
      </a>
    </div>
  {% endif %}

  <!-- GitHub -->
  {% if site.author.github %}
    <div class="cv-item">
      <a href="https://github.com/{{ site.author.github }}" target="_blank" title="GitHub">
        <i class="fab fa-github"></i>
      </a>
    </div>
  {% endif %}

  <!-- LinkedIn -->
  {% if site.author.linkedin %}
    <div class="cv-item">
      <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" target="_blank" title="LinkedIn">
        <i class="fab fa-linkedin"></i>
      </a>
    </div>
  {% endif %}
  <!-- CV -->
  {% if site.author.cv %}
    <div class="cv-item">
      <a href="{{ site.author.cv }}" target="_blank" title="Curriculum Vitae">
        <i class="fa fa-file"></i>
      </a>
    </div>
  {% endif %}
</div>
</div>

---
Human history is, at its core, a story of technological progress. Historians may focus on kings, and political scientists may debate policy, but lasting change comes from technological innovation. Shakespeare’s impact on the English language was only possible because of the invention and widespread adoption of the printing press. I’m motivated to help humanity by pushing technological boundaries.

I am a PhD student in Computer Engineering, focusing on computer architecture and embedded systems. My research sits at the intersection of low-level systems and hardware–software co-design, with a particular interest in domain-specific architectures.

## Current Position

**Graduate Research Assistant — [FoRTE Lab](https://forte-research.com/), Virginia Tech**  
I work on automated bespoke processor generation tools, with a focus on evaluating the effectiveness of bespoke processors.

## Education

**Ph.D. in Computer Engineering, Virginia Tech** \| *2025 – Present*  
Advisor: Matthew Hicks  

**B.S. in Computer Engineering, University at Buffalo** \| *2021 – 2025*
