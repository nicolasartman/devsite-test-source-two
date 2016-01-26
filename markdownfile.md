{% extends "default.html" %}

{% block body %}

here is a list:
{% for i in range(0,2) %}
- Here is thing number {{i}}
{% endfor %}


<a href="{{ '/somewhere#testreplacement-nothing-after-this-testtext' | link}}">here is a link</a>


<a href="{{ link('/subsite-one/somewhere#testreplacement-nothing-after-this-testtext') }}">another link</a>

{% endblock %}