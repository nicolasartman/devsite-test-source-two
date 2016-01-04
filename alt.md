{% extends "default.html" %}

{% block body %}
this is from the second source repo, for version 2, inside the alt.md file

{% for i in range(0,2) %}
- Here is thing number {{i}}
{% endfor %}

{% endblock %}