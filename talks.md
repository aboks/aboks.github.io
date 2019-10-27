---
layout: default
---
# Talks

This is a list of talks I have presented in the past, or would like to present in the future. Interested in having 
one of these talks at your event? Let me know!

<ul>
{% assign sorted_talks = site.talks | sort: "title" %}
{% for talk in sorted_talks %}
    <li><a href="{{ talk.url }}">{{ talk.title }}</a></li>
{% endfor %}
</ul>