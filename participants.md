---
layout: page
title: Participants
---


| Name | Affiliation |
|-------|-------|
| Ruth Hoffmann | University of St Andrews |
| Max Horn | University of Siegen |
| Chris Jefferson | University of St Andrews | 
| Alexander Konovalov | University of St Andrews |
| Iryna Raievska | Institute of Mathematics of National Academy of Sciences |
| Maryna Raievska | Institute of Mathematics of National Academy of Sciences |

<!--

<a href="{{ site.baseurl }}/images/group-photo-large.jpg">
  <img alt="Group photo for GAP Days Spring 2019 in Halle. Click for larger
  version" src="{{ site.baseurl }}/images/group-photo-small.jpg" /></a>
*Photo by [Patrick Salfeld](http://conway1.mathematik.uni-halle.de/~salfeld/index-en.html).*

<ol>
{% for p in site.data.participants %}
  <li>
    <strong>{{ p.name }}</strong>
    {% if p.affiliation != null %} ({{ p.affiliation }}){% endif %}
    {% if p.links != null %}
        {% for item in p.links %}
            <a href="{{ item[1] }}">({{ item[0] }})</a>
        {% endfor %}
    {% endif %}
    <br/>
      {% if p.talk != null %} Talk: {{ p.talk }}{% endif %}
  </li>
{% endfor %}
</ol>

{% if site.data.feedback.size > 0 %}

<ul>
{% for p in site.data.feedback %}
  <li>
    <strong>{{ p.name }}</strong>
    {% if p.package != null %} (author of {{ p.package }}){% endif %}
    <br/>
    {% if p.feedback != null %} {{ p.feedback }}{% endif %}
  </li>
{% endfor %}
</ul>

{% endif %}
-->
