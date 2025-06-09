---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
class: page-publications  
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find a full list of my publications on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}


<div class="publications-list">
  {% assign sorted_publications = site.publications | sort: 'year' | reverse %}
  {% for post in sorted_publications %}
    {% include publication.html entry=post %}
    {% unless forloop.last %}
      <hr class="publication-divider">
    {% endunless %}
  {% endfor %}
</div>
