---
title: Pre HTB prototype v1 findings and changes
description: Our prorotype has changed significantly due to peer reviews, user testing, increased knowledge and a move to a more focused MVP.
date: 2021-03-03
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    title: "{{ title }}"
    parent: Apply to Become an Academy
---
### Date the work was done
February 2021

## Introduction
Our first static prototype was our interpretation of user needs and understanding of the service. The static prototype was used as a conversational tool for our user sessions to see how well we understood the problem space. Consequently, we identified several things that needed to change, including the scope of MVP. From this point the product will focus on facilitating users with the creation of their headteacher board (HTB) papers, as this is where we feel our service adds the most value.

In addition to user testing, we iterated our prototype due to other factors including:
-	Internal interaction designer peer review
-	Continuing to learn about users, their roles and needs
-	Access to previous and new dashboard research
-	Use of the GDS prototyping kit

The main changes have been:
- The service tabs have been moved to global navigation because tabs are normally reserved for more granular information.
- Application, notes and dates have been moved from the right hand navigation into tabs to make sure they don’t fall below the fold and have more visual prominence. It also allows the full application to be easily accessed.
- Filters removed from the dashboard pages, and project seperate by service


## Research findings
### Who we tested with 
For this round of research, we tested with three users who had experience as project leads managing academy conversions. The small number of participants was due, in part, to the availability of volunteers from teams supporting schools’ Covid response.

## Findings
-	On the projects page users need to see how many days until opening, not just the HTB date.
-	In addition to the date assigned to them, users need to see the date the application was received.
-	‘Apply to become’ should come first in the navigation, followed by ‘Academy transfers’ and then ‘Significant change’.
-	Users did not understand progress tags as they did not reflect the way our users currently manage their projects.
-	The urgent tag meant different things to different users. 

“What’s jumping out at me… is that they’re clearly grouped together, but it’s not immediately obvious to me what ‘at review’, ‘in progress’ and whatever the other one was, means”

- The task page received positive comments but users wanted to see the tasks reflect the sections and structure of the HTB template more.

“It’s kind of doing both of the things I wanted.”

“In my mind I am then completing my HTB template as I fill out the sections.”


## What else have we learnt

-	Project leads spilt work into delivery projects and trust management work and do both as part of their role. 
-	Users would work on say a Significant change and a Transfer at the same time as a Conversion.
-	Some regions are using Teams and Word to track changes to manage the HTB template review process with managers and ESFA
-	Teams often use trackers that outline a list of activities and dates they need to work towards.
-	Users wouldn’t want anything that means tasks would be duplicated with other systems.

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
