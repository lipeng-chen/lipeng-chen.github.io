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


{% assign pubs = site.publications | sort: 'year' | reverse %}

<div class="publications-page">

  
  <!-- 出版物列表 -->
  <div class="publications-list">
    {% for pub in pubs %}
      <section class="publication-item" data-year="{{ pub.year }}">
        <h3 class="publication-title">
          {{ pub.title }}
          {% if pub.pdf %}
            <a href="{{ pub.pdf | prepend: '/files/' | relative_url }}" target="_blank" class="pdf-link" title="Download PDF">
              <i class="fas fa-file-pdf"></i>
            </a>
          {% endif %}
        </h3>
        
        <div class="publication-meta">
          <div class="publication-authors">{{ pub.authors }}</div>
          <div class="publication-details">
            <em>{{ pub.venue }}</em>, {{ pub.year }}
            {% if pub.pages %} | pp. {{ pub.pages }}{% endif %}
            {% if pub.doi %} | DOI: <a href="https://doi.org/{{ pub.doi }}" target="_blank">{{ pub.doi }}</a>{% endif %}
          </div>
        </div>
      </section>
    {% endfor %}
  </div>
</div>

<!-- 添加调试信息 -->
<script>
console.log('Publications count:', {{ pubs.size }});
</script>