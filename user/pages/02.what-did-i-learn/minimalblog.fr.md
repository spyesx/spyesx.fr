---
title: Learned
published: true
slug: what-did-i-learn
process:
    markdown: true
    twig: true
child_type: minimalblog_item
routable: true
cache_enable: true
visible: true
content:
    items: '@self.children'
    limit: 400
    order:
        by: date
        dir: asc
    pagination: true
    url_taxonomy_filters: true
---

