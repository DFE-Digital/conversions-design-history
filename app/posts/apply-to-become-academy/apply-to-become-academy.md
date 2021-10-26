---
tags: false
layout: collection
title: Manage an academy conversion
description: An internal service for DfE colleagues to manage applications from schools applying to become academies.
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
