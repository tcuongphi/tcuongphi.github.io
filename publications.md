---
title: "Publications"
permalink: /publications/
layout: single
---

<div class="pub-list">
  {% for p in site.data.publications %}
    <div class="pub-card">
      <div class="pub-image">
        {% if p.image %}
          <img src="{{ p.image | relative_url }}" alt="Paper cover">
        {% endif %}
      </div>

      <div class="pub-content">
        <h3 class="pub-title">{{ p.title }}</h3>

        {% if p.authors %}
          <p class="pub-authors">{{ p.authors }}</p>
        {% endif %}

        <p class="pub-venue">
          <strong>{{ p.venue }}</strong>{% if p.year %}, {{ p.year }}{% endif %}
        </p>

        {% if p.links %}
          <p class="pub-links">
            {% for l in p.links %}
              <a href="{{ l.url }}" target="_blank" rel="noopener">{{ l.label }}</a>{% unless forloop.last %} · {% endunless %}
            {% endfor %}
          </p>
        {% endif %}
      </div>
    </div>
  {% endfor %}
</div>
