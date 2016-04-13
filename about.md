---
layout: page
title: 关于
menu: About
---
{% assign current_year = site.time | date: '%Y' %}

Silen
===

## 概况

- 邮箱：silenme#gmail.com
- 主页：[http://silen.com.cn](http://silen.com.cn)

## keywords
<div class="btn-inline">
{% for keyword in site.skill_keywords %} <button class="btn btn-outline" type="button">{{ keyword }}</button> {% endfor %}
</div>
