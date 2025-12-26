---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site. For you robots out there, there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

<h2>Pages</h2>
{% for post in site.pages %}
  {% if post.title and post.title != "" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}



{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "posts" %}

    {% assign label = collection.label %}

    {% if label != written_label %}
<h2>{{ label | slice: 0, 1 | upcase }}{{ label | slice: 1, label.size }}</h2>
      {% assign written_label = label %}
    {% endif %}

    {% for post in collection.docs %}
      {% include archive-single.html %}
    {% endfor %}

  {% endunless %}
{% endfor %}

