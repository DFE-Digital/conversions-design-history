---
title: Record a decision
description: Delivery officers (DOs) present proposed academy conversions and transfers at advisory board (AB). This is so the Regional Director (formerly the Regional Schools Commissioner) can make a decision.
date: 2022-06-28
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    title: "{{ title }}"
    parent: Manage an academy conversion
---
Delivery officers (DOs) present proposed academy conversions and transfers at advisory board (AB). This is so the Regional Director (formerly the Regional Schools Commissioner) can make a decision.

The decision can also escalate to:  
 
- A different Regional Director, if they do not agree with the decision made 
- A Minister, if a school or academy challenge the Regional Director’s decision

## Types of decision
There are four types of decision:  

### Approved
This is the decision for most projects. Once someone approves a project, this decision is final. A new application will need to go to AB to change it.

### Approved with conditions
This is less common. An example condition is an improved strategy for how the trust taking on an academy will grow.

### Declined
This is very rare. If a project is not approved, then it is often deferred for approval later. Declined decisions are also final and are only changed with a new application.

Our analysis so far confirms there are no standard reasons for declining a project.

### Deferred
The project is not approved and a DO brings it to a future AB once the reasons for deferral are addressed. An example is the trust managing an academy should engage more with stakeholders.

Our research so far shows there is no standard set of deferral reasons.

## Why the decision needs recording

Recording the decision is useful to the:  

- Central Director (formerly the National Schools Commissioner) so they know the decisions made across the 9 regions  
- Department for Education, so they can report on the decisions made across the 9 regions  
- Complete conversions, transfers and changes team who manage the [post AB process](https://sdd-design-history.netlify.app/postab/) 

The minutes from AB meetings include other information with the decision:  

- Date of decision 
- Conditions of approval  
- Reasons for deferring a project  
- Reasons for declining a project  
- The status of the project

## Our design

The Manage an academy conversion team created a proof of concept to record a decision.

Our team (Prepare for advisory board) took this concept and made several changes:  
 
### Removed references to the AB making the decision.

Several people can make the decision, so we removed references to AB to avoid confusion. 

[![A page called Record the decision in the Prepare for advisory board service.](/images/apply-to-become-academy/recording-a-decision/removed-references-to-the-ab-making-the-decision.png)](/images/apply-to-become-academy/recording-a-decision/removed-references-to-the-ab-making-the-decision.png)

&nbsp;


### Changed link text to record a decision.

The change in status of a project is the outcome of recording a decision. We made recording the decision the call to action.  

[![A project for St Wilfrid's Primary School in Prepare for advisory board.](/images/apply-to-become-academy/recording-a-decision/changed-link-text-to-record-a-decision.png)](/images/apply-to-become-academy/recording-a-decision/changed-link-text-to-record-a-decision.png)

&nbsp;

### Added an are you sure page if the user follows the decline journey. 

Declined cases are rare and irreversible, so we added a page to help DOs feel confident. We used a red warning button in line with the GOV.UK Design System guidance on when to use [buttons](https://design-system.service.gov.uk/components/button/).  

[![A page called Are you sure you want to record a declined decision? It has a warning button with the text Yes, record the decision.](/images/apply-to-become-academy/recording-a-decision/added-an-are-you-sure-page-if-the-user-follows-the-decline-journey.png)](/images/apply-to-become-academy/recording-a-decision/added-an-are-you-sure-page-if-the-user-follows-the-decline-journey.png)

&nbsp;

### Added checkboxes for declined and deferred reasons.
Giving users a list to select from is better practice than an open-ended [textarea](https://design-system.service.gov.uk/components/textarea/).  

[![A page called why was this project declined? It has multiple check boxes to select from.](/images/apply-to-become-academy/recording-a-decision/added-checkboxes-for-declined-and-deferred-reasons.png)](/images/apply-to-become-academy/recording-a-decision/added-checkboxes-for-declined-and-deferred-reasons.png)

[![A page called why was this project deferred? It has multiple check boxes to select from.](/images/apply-to-become-academy/recording-a-decision/added-checkboxes-for-declined-and-deferred-reasons-2.png)](/images/apply-to-become-academy/recording-a-decision/added-checkboxes-for-declined-and-deferred-reasons-2.png)

&nbsp;

### Added a record the decision link to the projects list.

We will test in user research whether users click the link here or on an individual project page. For example, St Wilfrid’s Primary School.  

[![Three projects, one for St Wilfrid's Primary School, one for Bolton Spa Primary and one for Blessed John Henry Newman Roman Catholic College.](/images/apply-to-become-academy/recording-a-decision/added-a-record-the-decision-link-to-the-projects-list.png)](/images/apply-to-become-academy/recording-a-decision/added-a-record-the-decision-link-to-the-projects-list.png)

&nbsp;

### Updated the status labels once the DO records the decision.

We felt it was best to use the Design System [tag component](https://design-system.service.gov.uk/components/tag/). The Government Digital Service (GDS) will update this more often than our custom made tags.  

[![An information banner that says decision recorded and approved. This is for St Wilfrid's Primary School](/images/apply-to-become-academy/recording-a-decision/updated-the-status-labels-once-the-do-records-the-decision-approved.png)](/images/apply-to-become-academy/recording-a-decision/updated-the-status-labels-once-the-do-records-the-decision-approved.png)

[![An information banner that says decision recorded and declined.](/images/apply-to-become-academy/recording-a-decision/updated-the-status-labels-once-the-do-records-the-decision-declined.png)](/images/apply-to-become-academy/recording-a-decision/updated-the-status-labels-once-the-do-records-the-decision-declined.png)

[![An information banner that says decision recorded and deferred.](/images/apply-to-become-academy/recording-a-decision/updated-the-status-labels-once-the-do-records-the-decision-deferred.png)](/images/apply-to-become-academy/recording-a-decision/updated-the-status-labels-once-the-do-records-the-decision-deferred.png)  

&nbsp;

### Updated the decision tab and summary list labels.

We did this to make the decision overview easier to understand. Calling the tab and summary row decision felt confusing, so we gave them unique names.  

[![A page called why was this project declined? It has multiple check boxes to select from.](/images/apply-to-become-academy/recording-a-decision/updated-the-decision-tab-and-summary-list-labels.png)](/images/apply-to-become-academy/recording-a-decision/updated-the-decision-tab-and-summary-list-labels.png) 

## Next steps
We will:

- Test the new prototype with our subject matter expert and in user research  
- Add the prototype to our development environment so we can test with real projects  
- Create a proof of concept for our Manage an academy transfer product 