---
tags: false
layout: collection
title: Apply to Become an Academy
description: A service for candidates to submit an application to their chosen teacher training courses
related:
  items:
  - text: Prototype
    description: |
      Username: `academy`
      Password: `conversions`
    href: https://academy-conversions.herokuapp.com/
  - text: User needs
    href: /apply-to-become-academy/user-needs/user-needs
  - text: Glossary
    href: /apply-to-become-academy/glossary-list/glossary-full-list
  - text: Go back to all SDD design histories
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
