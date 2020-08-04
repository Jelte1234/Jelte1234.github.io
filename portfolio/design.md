---
layout: default
title: "Design"
menu_item: "Design"
permalink: '/design/'
---

{% assign all = site.design | concat: site.cad | concat: site.tinkerworks_design %}

{% include list_portfolio_items.html collection=all %}

