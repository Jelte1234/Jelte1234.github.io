---
layout: default
title: "Tinkering"
menu_item: "Tinkering"
permalink: '/tinkering/'
basename: 'tinkering'
---

{% assign all = site.tinkering | concat: site.tinkerworks_design | concat: site.tinkerworks_photography %}

{% include list_portfolio_items.html collection=all %}

