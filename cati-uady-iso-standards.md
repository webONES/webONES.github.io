---
layout: page
permalink: /cati-uady-iso-standards/
title: "CATI UADY ISO Standards"
modified: 2015-07-15 22:33
tags: [uady, cati, iso, bad]
---
# {{page.title}}

{% for iso in site.data.isos %}
  <h3>
    {{iso.title}}
  </h3>
  <blockquote>
    <p>
      {{iso.content}}
    </p>
  </blockquote>
{% endfor %}
