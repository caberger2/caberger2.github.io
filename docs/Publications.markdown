---
layout: page
title: Publications
permalink: /publications/
---

{% capture bib %}{% bibliography %}{% endcapture %}
{{ bib | replace: 'CFSTAR', '<sup>*</sup>' }}
{{ bib | replace: 'UGSTAR', '<sup>**</sup>' }}

<small>* denotes equal contribution</small>\
<small>** denotes undergraduate mentee</small>
