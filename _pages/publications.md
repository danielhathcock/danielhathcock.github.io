---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

# Preprints

{% for pub in site.preprints reversed %}
__{{pub.title}}__\
<span style="color:#888888;">with {{pub.authors}}.</span>\
{{pub.venue}}
{% if pub.link %} <a href="{{ pub.link }}"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a> {%- endif -%}
{% if pub.fileurl %} <a href="{{ pub.fileurl }}"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> {% endif %}
{% endfor %}

# Publications

{% for pub in site.publications reversed %}
__{{pub.title}}__\
<span style="color:#888888;">with {{pub.authors}}.</span>\
{{pub.venue}}
{% if pub.link %} <a href="{{ pub.link }}"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a> {%- endif -%}
{% if pub.fileurl %} <a href="{{ pub.fileurl }}"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> {% endif %}
{% endfor %}

