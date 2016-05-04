---
title: Bags
published: true
process:
    markdown: true
    twig: true
child_type: minimalblog_item
routable: true
cache_enable: true
visible: true
content:
    items: '@self.children'
    limit: 200
    order:
        by: folder
        dir: asc
    pagination: false
    url_taxonomy_filters: false
---

Travelling a lot means to have to pack my bag quite often. I'm usually able to pack in about 30min for an undetermined period. 

In order to speed up this task, I made list of generic bags. It's a also a good way to check if some items are missing.