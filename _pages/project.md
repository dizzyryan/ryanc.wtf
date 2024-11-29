---
layout: archive
title: "Project"
permalink: /projects/
author_profile: true
---




# Abstract

I plan to upload some of my projects to this website, including those I completed during university courses as well as my personal side projects. I’m still deciding what else to include here—maybe some useful tools (well, at least they’re useful to me...). The source codes will be available on GitHub, but I’ll also provide some usage instructions here.

{% include base_path %}

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}