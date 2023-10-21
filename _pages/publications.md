---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
#author:
#  name: Jurlind Budurushi
#  googlescholar: https://scholar.google.de/citations?user=CrFW5JsAAAAJ
---

<!--{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}-->

{% include base_path %}


<p></p>
[Journals](#journals) | [Proceedings](#proceedings) | [Editor](#editor) | [Book chapters](#bookchapters) | [Preprints](#preprints) | [Phd](#phd)

<!-- Journals -->
<h2 id="journals" style="color: white; padding: 5px; background-color: #52adc8; margin-bottom: -20px">Journals</h2>
{% for post in site.publications reversed %}
  {% if post.type == "journals" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


<!-- Proceedings -->
<h2 id="proceedings" style="color: white; padding: 5px; background-color: #52adc8; margin-bottom: -20px">Proceedings</h2>
{% for post in site.publications reversed %}
  {% if post.type == "publications" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


<!-- Editor -->
<h2 id="editor" style="color: white; padding: 5px; background-color: #52adc8; margin-bottom: -20px">Editor</h2>
{% for post in site.publications reversed %}
  {% if post.type == "editors" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


<!-- Book chapters -->
<h2 id="bookchapters" style="color: white; padding: 5px; background-color: #52adc8; margin-bottom: -20px">Book chapters</h2>
{% for post in site.publications reversed %}
  {% if post.type == "bookchapters" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


<!-- Preprints -->
<h2 id="preprints" style="color: white; padding: 5px; background-color: #52adc8; margin-bottom: -20px">Preprints</h2>
{% for post in site.publications reversed %}
  {% if post.type == "preprints" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


<!-- Phd -->
<h2 id="phd" style="color: white; padding: 5px; background-color: #52adc8; margin-bottom: -20px">Phd</h2>
{% for post in site.publications reversed %}
  {% if post.type == "phd" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}