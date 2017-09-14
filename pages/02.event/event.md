---
title: Events
blog_url: event
body_classes: header-image fullwidth

sitemap:
    changefreq: daily
    priority: 1.03

content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 50
    pagination: true

feed:
    description: Sample Event Description
    limit: 10

pagination: true
---

# Here are some events
## Hope this works!
items: @self.children
items: @page.descendants:'/event/events'
