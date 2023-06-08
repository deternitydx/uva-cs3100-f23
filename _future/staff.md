---
layout: default 
title: Course Staff
nav_order: 4
---

# Course Staff 

{% for type in site.data.tas %}

## {{type.group}}

<div class="d-flex" style="flex-wrap: wrap;">
{% for person in type.people %}

<div class="float-left" style="width: 40%; margin: 10px;">
<img src="{{person.picture}}" alt="Staff Photo">
<h3>{{person.name}}</h3>
{% if person.role %}
<h4>{{person.role}}</h4>
{% endif %}
{% if person.tagline %}
<p>{{person.tagline}}</p>
{% endif %}
<p>
{% if person.askme %}
<b>Ask me about: </b> {{person.askme}} <br>
{% endif %}
{% if person.tips %}
<b>Tips for cso1: </b> {{person.tips}} <br>
{% endif %}
</p>
</div>

{% endfor %}

</div>
{% endfor %}

