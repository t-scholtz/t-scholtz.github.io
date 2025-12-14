---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="text-align:center; margin-bottom:0; padding-bottom:0;">
  <!-- Profile Image (circular) -->
  <picture>
    <img src="/images/{{ site.author.avatar }}" alt="Profile picture." 
         class="profile-photo" 
         style="border-radius:50%; width:300px; height:300px; object-fit:cover; margin-bottom:1rem;">
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
I am a PhD student in Computer Engineering focusing on computer architecture and embedded systems. My research sits at the intersection of low-level systems and hardware–software co-design, with an interest in domain-specific architectures. I work on tools for designing application-specific, bespoke processors.

---

# Education

**Ph.D. Computer Engineering, Virginia Tech**  
*2025 – Present*  
Research Area: Computer Architecture and Embedded Systems

**Bachelor of Science, Computer Engineering, University at Buffalo**  
GPA: 3.88 | *2021 – 2025*

---

# Current Position

**Graduate Research Assistant — FoRTE Lab, Virginia Tech**  
Supervisor: Prof. Matthew Hicks  
Dates: June 2025 – Present  
Research Area: Computer Architecture and Embedded Systems  

- Developed a hardware-agnostic tool for generating application-specific, bespoke processors, enabling greater flexibility and improved performance compared to existing generation methodologies.  
- Evaluated current approaches to bespoke processor design and analyzed trade-offs in performance, effectiveness, and design complexity.
