---
title: Talks
layout: default
year: 2017
permalink: /talks/
---
# Talks

**To be announced!**

{% for talk in site.data.2017.talks %}
#### <a name="{{ talk.id }}"></a>{{ talk.title }} - {% if talk.author_url %}[{{ talk.author }}]({{ talk.author_url }}){% else %}{{ talk.author }}{% endif %}
{% if talk.slides %}[SLIDES]({{ talk.slides }}) {% endif %}
> {{ talk.abstract }}
{% endfor %}
