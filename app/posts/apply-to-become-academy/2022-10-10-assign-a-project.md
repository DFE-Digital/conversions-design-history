---
title: Assigning a project
description: We created a feature that allows team leads to assign conversions projects to delivery officers.
date: 2022-10-10
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    title: "{{ title }}"
    parent: Manage an academy conversion
---
DfE’s 9 regions consist of a list of authorities. Each authority has a team lead who is responsible for assigning [applications to become an academy](https://www.gov.uk/government/publications/academy-conversion-application-forms)  to delivery officers (DO). 

Given team leads assign projects to DOs in the as-is process, it made sense to introduce a project assignment feature in our service.

## Understanding the problem
We collated our user research findings about assigning projects on a Lucidspark board.

[![A series of digital post-it notes about assigning an academy conversion project to delivery officers.](/images/apply-to-become-academy/assign-a-project/user-feedback.png)](/images/apply-to-become-academy/assign-a-project/user-feedback.png)

We then thought of possible solutions and problems with assigning projects in our service.

[![A series of post it note questions about assigning projects.](/images/apply-to-become-academy/assign-a-project/ideas.png)](/images/apply-to-become-academy/assign-a-project/ideas.png)

## Design provocations

We compared our notes with other project assignment designs in DfE.

[![Screenshots from the Get help buying for schools service.](/images/apply-to-become-academy/assign-a-project/get-help-buying.png)](/images/apply-to-become-academy/assign-a-project/get-help-buying.png)

[![Screenshots from the Complete conversions, transfers and changes service.](/images/apply-to-become-academy/assign-a-project/complete-service.png)](/images/apply-to-become-academy/assign-a-project/complete-service.png)

We also reflected on the as-is process for assigning projects to DOs.

[![Guidance on assigning conversion projects in KIM and TRAMS.](/images/apply-to-become-academy/assign-a-project/kim-and-trams.png)](/images/apply-to-become-academy/assign-a-project/kim-and-trams.png)

Our interaction designer used these points of reference to create 2 design provocations:

1.	**Choose from a pre-populated list of DOs**. This was based on the designs of other DfE services, including our sister service Complete conversions, transfers and changes.

[![Screenshots of option 1, choose from a list of delivery officers.](/images/apply-to-become-academy/assign-a-project/option-1.png)](/images/apply-to-become-academy/assign-a-project/option-1.png)

2.	**Enter the email address of the assigned DO.** This would save time updating a list of DOs when someone leaves, for example.

[![Screenshots of option 2, offline communications + entering email address. Continue doing the as-is process for assigning projects.](/images/apply-to-become-academy/assign-a-project/option-2.png)](/images/apply-to-become-academy/assign-a-project/option-2.png)

We discussed the 2 options as a team and considered the pros and cons of each one.

[![Questions and feedback sticky notes about options 1 and 2.](/images/apply-to-become-academy/assign-a-project/pros-and-cons.png)](/images/apply-to-become-academy/assign-a-project/pros-and-cons.png)

This prompted a follow-on discussion about how we would maintain a list of users. We considered different approaches and the implications of each approach.

[![A digital whiteboard that shows a list of possible solutions based on options 1 and 2.](/images/apply-to-become-academy/assign-a-project/maintaining-users.png)](/images/apply-to-become-academy/assign-a-project/maintaining-users.png)

[![A set of questions and feedback sticky notes about some design solutions.](/images/apply-to-become-academy/assign-a-project/user-management-comments.png)](/images/apply-to-become-academy/assign-a-project/user-management-comments.png)

## Prototype design

We created a prototype design considering everything that we discussed as a team. We then tested our prototype with team leads.

[![A list of academy conversion projects. The first project displays an EMPTY tag next to delivery officer.](/images/apply-to-become-academy/assign-a-project/project-list-unassigned.png)](/images/apply-to-become-academy/assign-a-project/project-list-unassigned.png)

[![A conversion project for Bristol Gateway School. It has an EMPTY tag for delivery officer.](/images/apply-to-become-academy/assign-a-project/task-list.png)](/images/apply-to-become-academy/assign-a-project/task-list.png)

[![A page asking the user to assign a delivery officer to a project.](/images/apply-to-become-academy/assign-a-project/who-is-on-project.png)](/images/apply-to-become-academy/assign-a-project/who-is-on-project.png)

[![A dropdown list of names to select from to assign a project.](/images/apply-to-become-academy/assign-a-project/dropdown.png)](/images/apply-to-become-academy/assign-a-project/dropdown.png)

[![A page asking the user to assign a delivery officer to a project. Adrian Horan has been selected.](/images/apply-to-become-academy/assign-a-project/dropdown-selected.png)](/images/apply-to-become-academy/assign-a-project/dropdown-selected.png)

[![A conversion project for Bristol Gateway School. A success banner shows that the project is assigned and Adrian Horan is the delivery officer.](/images/apply-to-become-academy/assign-a-project/project-assigned.png)](/images/apply-to-become-academy/assign-a-project/project-assigned.png)

### Next steps

We will test our prototype with delivery officers in user research sessions.