---
layout: default
title: "Andrey Lappo — QA Engineer Portfolio"
description: "2,500+ issues filed. Manual QA | Documentation Testing | Localization QA"
---

{% capture readme %}{% include_relative README.md %}{% endcapture %}
{% assign parts = readme | split: '---' %}
{% if parts.size > 2 %}
  {% assign body = parts[2] %}
{% else %}
  {% assign body = readme %}
{% endif %}

{{ body | markdownify }}
