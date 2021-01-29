---
layout: page
header:
  image_fullwidth: head.jpg
title: "About Us"
meta_title: "About Us"
subheadline: "The Team behind this site"
permalink: "/about/"
---

{% for author_entry in site.data.authors %}{% assign author = author_entry[1] %}
<a name="{{ author_entry[0] }}"/>
<div class="row" style="margin-bottom: 10px">
  <div class="columns small-4">
    {% if author.img %}
    <img src="/images/users/{{ author.img }}"/>
    {% endif %}
  </div>
  <div class="columns small-8">
    <h3 style="margin:0px">
    {% if author.uri %}<a href="{{ author.uri }}">{% endif %}
    {{ author.name }}
    {%if author.postfix %}, {{ author.postfix}}{% endif %}
    {% if author.uri %}</a>{% endif %}
    {% if author.twitter %}<a href="http://twitter.com/{{ author.twitter }}" class="icon-twitter"></a>{% endif %}
    {% if author.github %}<a href="http://github.com/{{ author.github }}" class="icon-github"></a>{% endif %}
    </h3>
    <p><i>{{ author.role }}</i></p>
    <p style="font-size: 12px">{{ author.about }}</p>
  </div>
</div>
{% endfor %}
