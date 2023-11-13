---
title: Тултипы
tags: [formatting]
keywords: popovers, tooltips, user interface text, glossaries, definitions
last_updated: July 3, 2016
summary: "Ты можешь попробовать добавить сюда информацию."
sidebar: mydoc_sidebar
permalink: mydoc_adding_tooltips.html
folder: mydoc
---

## Creating tooltips
Сюда можно написать все что угодно.

Suppose you have a glossary.yml file inside your \_data folder. You could pull in that glossary definition like this:

{% raw %}
```html
<a href="#" data-toggle="tooltip" data-original-title="{{site.data.glossary.jekyll_platform}}">Jekyll</a> is my favorite tool for building websites.
```
{% endraw %}

This renders to the following:

<a href="#" data-toggle="tooltip" data-original-title="{{site.data.glossary.jekyll_platform}}">Jekyll</a> is my favorite tool for building websites.

{% include links.html %}
