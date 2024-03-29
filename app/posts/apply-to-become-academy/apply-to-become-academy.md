---
tags: false
layout: collection
title: Manage an academy conversion
description: Our service helps create strong schools where children can thrive and teachers can prosper. It is an efficient and unified end-to-end service that will support schools becoming academies and the DfE staff that manage these academy conversions.
The benefits of our service will include:
related:
  items:
  - text: Prototype
    description: |
      Username: `academy`
      Password: `conversions`
    href: https://academy-conversions.herokuapp.com/
  - text: User needs
    href: /apply-to-become-academy/user-needs/user-needs
  - text: A to Z Glossary
    href: https://sdd-design-history.netlify.app/glossary/
  - text: Our product vision
    href: /apply-to-become-academy/product-vision/product-vision
  - text: All SDD design histories
    href: https://sdd-design-history.netlify.app/
  
pagination:
  data: collections.apply-to-become-academy
  reverse: true
  size: 50
permalink: "apply-to-become-academy/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 3
---
