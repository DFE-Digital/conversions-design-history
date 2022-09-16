---
title: Pre-HTB prototype version 2
description: Our prorotype has changed significantly due to peer reviews, user testing, increased knowledge and a move to a more focused MVP.
date: 2021-03-03
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    title: "{{ title }}"
    parent: Manage an academy conversion
---
### Date the work was done
February 2021

## Designing a v2 prototype

The second version of the prototype started as another static Figma file. This click-through allowed us to quickly update and explain to the team our new thoughts and learnings. 

Feeling more confident that our approach more closely met the needs of our users, we moved to a HTML prototype using the GOVUK prototyping kit.

The HTML prototype will give our users a more natural environment in which to explore our service and in-turn give us more opportunities to get detailed feedback on the service we are producing.

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Projects page",
      img: { src: "projects-page.png" }
    }, {
      text: "Task list page",
      img: { src: "task-list-page.png" }
    }, {
      text: "Application form",
      img: { src: "application-form.png" }
    }, {
      text: "Key dates",
      img: { src: "key-dates.png" }
    }, {
      text: "Notes",
      img: { src: "notes.png" }
    }, {
      text: "Project overview summary page",
      img: { src: "project-overview-summary-page.png" }
    },  {
      text: "Pupil forcasts (reference only)",
      img: { src: "pupil-forcasts-(reference-only).png" }
    }, {
      text: "Set htb date task",
      img: { src: "set-htb-date-task.png" }
    },{
      text: "Write rationale",
      img: { src: "write-rationale.png" }
    }]
}) }}
