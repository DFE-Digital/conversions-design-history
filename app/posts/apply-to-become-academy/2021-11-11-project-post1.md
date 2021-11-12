---
title: Improving the project template 
description: Delivery officers use a Word document called a project template to bring together lots of information about a school and a trust. They then present this template at an Advisory Board meeting.
date: 2021-11-11
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    title: "{{ title }}"
    parent: Manage an academy conversion
---

### Date the work was done 
August to October 2021 
 
## What is the project template 
Delivery officers use a Word document called a project template to bring together lots of information about a school and a trust. They then present this template at an Advisory Board meeting. Regional school commissioners (RSCs) and Advisory Board members then use this template to decide if the school can convert and join or form a trust. 

## The current project template 
The current template is in a Word document format. Delivery officers fill it out manually or they can download it from a system called KIM (knowledge information management). In KIM, some of the fields will be populated with existing data. To complete the whole template in full, delivery officers must go to many different systems to find the information they need to fill it out. 

The current template also has some readability and accessibility issues.
These include: 
- information is placed very close together so it’s hard to read and make sense of 
- the table structure uses split or merged cells making it hard to find a coherent reading order 
- the template is hard to scan because the headers do not stand out 
- the template has lots of acronyms that new delivery officers sometimes do not understand 
 
In our team’s previous private beta, the service was built in Microsoft Dynamics. The template that this system generated had some issues, such as: 
- it was difficult to move and change things in the template 
- it was difficult to format text 
- some things people expected to be populated were not. 

Our team wanted to make sure that the template we produced worked for all the people that use it. These people are: 
- delivery officers that create the template 
- team leaders that check the information in the template 
- Advisory Board members who need to read and understand the template 
- RSCs who also need to read and understand the template and make a decision based on the information in it 
 
## Working with the policy team that created the template 
Before changing the template, we spoke to the policy team who ‘own’ and created it. We wanted to make them aware about our work and check they were happy for us to make improvements. The policy team told us that the template was old and probably needed a refresh. We assured them that we would not be removing any information, but rather looking at improving the layout. 

## Improving the project template 
To improve the accessibility and readability of the template our content designer: 
- removed the merged and split cells by changing the table layout to 2 columns 
- frontloaded important information like the school and trust name to the top of the template 
- put less important information in the footer, like the author of the template 
- grouped similar information together, like dates 
- added more white space around some of the information to make it easier to read 
- Followed the GOV.UK style guide by writing out acronyms in the template 
 
## Checking our developers could generate a template in the new format 
Once the new format of the template was done, our developers investigated if our new service could generate the template into a Word document. Because the new layout was much simpler than the previous one, our developers could replicate it exactly. However, there were some issues with the rich text editor in the section called the rationale. Depending on how delivery officers write their rationale (for example copying and pasting it from Word), we might not be able to replicate this section in exactly the way delivery officers want. We decided to do some testing to see if this would be a problem. 

## Testing the rationale on the new template 
Our interaction designer did some testing on the rationale and tried to write this section in two different ways, such as: 
- writing the rationale directly into the service and formatting it using the rich text editor 
- writing the rationale in Word and then pasting it into the system and reformatting it. From the research we understand this may be a common way of writing the rationale. 

When the rationale was written and formatted directly in the system, it converted into Word reasonably well. There were some formatting issues, but they were errors that would be easy to fix. However, when the rationale was created in Word and pasted into the system, the conversion back to Word generated lots of formatting errors. These errors are not easily fixed. We decided as a team to remove the rich text editor feature and will continue our research to find a more appropriate solution that will meet the needs of our users. 


{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "1. Current project template",
      img: { src: "1. current-project-template.png" }
    }, {
      text: "2. TRAMS project template",
      img: { src: "2. TRAMS-project-template.png" }
    },  {
      text: "3. New project template",
      img: { src: "3. new-project-template.png" }
    }, {
      text: "4. Rationale with text editor",
      img: { src: "4. rationale-with-text-editor.png" }
    },{
      text: "5. Rationale without text editor",
      img: { src: "5. rationale-without-text-editor.png" }
    }]
}) }}