---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


<b>Refereed Conference Publications</b>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship.


<b>Preprints</b>
{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship.

<b>Refereed Workshop Publications</b>
{% for post in site.workshops reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship.

<b>Other Publications (Work in Cardiology with My Brother, Yuhei Kasai, M.D.)</b>
{% for post in site.others reversed %}
  {% include archive-single.html %}
{% endfor %}

