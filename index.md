---
layout: default
title: Board Game Cheat Sheets
---

# Board Game Cheat Sheets

## Games

<ul>
{% assign games = site.games | sort: "title" %}
{% for game in games %}
  <li><a href="{{ game.url | relative_url }}">{{ game.title }}</a> {% if game.lang == "pt-br" %}🇧🇷{% endif %}{% if game.lang == "en" %}🇬🇧{% endif %}</li>
{% endfor %}
</ul>
