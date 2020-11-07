---
layout: single
classes: wide
title: "Prototype Evaluation"
permalink: /evaluation/
sidebar:
    nav: "sidebar-nav"
toc: true
toc_label: "Table of Contents"
---

## Overview
For our project, we conducted both expert (peer) and user evaluation. The evaluation was done on the 2 prototypes, for both the teacher and student views. 

Expert evaluation was done by all 4 members of the team before we conducted the user evaluation in Week 10. 

User evaluation has 2 sets, one set of 4 peer evaluators evaluating both views for each prototype was conducted in Week 10. 

The other set was with real users, 2 students and 2 teachers evaluated the respective prototypes. The real user evaluation was conducted in week 11. 

## Expert (Peer) Evaluation

### Plan

Firstly, we presented 2 prototypes to the experts. As each prototype has 2 user flows - one for teacher and one for student - we came up with the following combination of testing using the **Latin Square Counterbalancing Method**

| Evaluator | Prototype Sequence | View Sequence |
|-----------|--------------------|---------------|
|1| A &#9658; B| Teacher &#9658; Student|
|2| A &#9658; B| Student &#9658; Teacher |
|3| B &#9658; A| Teacher &#9658; Student |
|4| B &#9658; A| Student &#9658; Teacher |

{% capture lattice-example %}
_**Example**_  
Evaluator 1 will evaluate Prototype A's Teacher view first, followed by Prototype B's Teacher view, followed by Prototype A's Student view, followed by Prototype B's student view
{% endcapture %}

<div class="notice--primary">{{ lattice-example | markdownify}}</div>

We gave each evaluator a list of tasks, and each evaluator was instructed to complete each task in succession. Each evaluator's performance on each task was rated using the following scale:

|Percentage|Description|
|----------|-----------|
|0%|Failed to complete the task correctly, gives up, or succeeds only with an assistance from moderator|
|50%|Succeeds, but in a roundabout way, making errors, needing to back track or using on-line help|
|100%|Succeeds quickly, following the intended user flow|

### Takeaways

After the evaluation, we summarised the issues raised during each evaluation session for each prototype. 

**Prototype A**  

|No.| Page/Component| Issue | Severity |
|---|---------------|-------|----------|
|1| Navbar | &#8226; Group icon was not intuitive as it led to a page that started quests. <br> &#8226; Path to Quest Page was not user-friendly | High |
|2| Groups Page | Felt lacking in functionality and was too simple | Medium |
|3| Overall | Lack of back/cancel buttons can make it hard for the user to feel in control | Medium |
|4| Overall | Application does not prompt the user for confirmation/show a success message after the user completes some activity, may make the user feel not in control. | Medium |
|5| Home Page | Class details may provide too much information for user to parse through in a dropdown | Medium |
|6| Overall | Colour scheme may be too monotonic | Low |
|7| Home Page | Calendar icon to switch to calendar view was not intuitive | Low |

**Prototype B**

|No.| Page/Component| Issue | Severity |
|---|---------------|-------|----------|
|1| Class Details Page, Quest Page | Too many details in one page can increase cognitive load placed on user | High |
|2| Navbar | Symbols used were not intuitive (e.g. Pencil for study tab, Calendar for quests tab) | High |
|3| Class Details | Path to complete tasks (e.g. Add students to class) in Class Details page is not intuitive | High |
|4| Quest Page | Difference between Calendar View and List View was not clear | Medium |
|5| Home Page | Home page did not provide enough information for the user to understand the current state of the application | Medium |
|6| Overall | Lack of back/cancel buttons can make it hard for the user to feel in control | Medium |
|7| Overall | Application does not prompt the user for confirmation/show a success message after the user completes some activity, may make the user feel not in control.| Medium |
|8| Overall | Distracting background and colour scheme can make it difficult for users to navigate through the application | Low |

**Prototype A vs. Prototype B**

From the evaluation, we summarised the aspects that we felt one prototype performed better in during the evaluation. 

|Aspects| Prototype A| Prototype B|
|-------|------------|------------|
| User Flow |&#10004; | |
| Functionality | |&#10004; |
| Appeal to Teachers | &#10004;| |
| Appeal to Students | | &#10004;| 

Overall, our findings were that Prototype A had a clear user flow, but was too plain looking and felt lacking in functionality due to its simplistic take. On the other hand, prototype B was visually pleasing but at times it seemed visually overwhelming and overly complicated, making users confused on certain user navigation with a significantly lower percentage of completion. Yet, the majority of the users still preferred prototype B for its completeness.

As such, we aimed to strike a balance between functional, completeness, visual simplicity and appeal for our final prototype, while addressing the above problems raised, so that our application will be both easy to navigate and appealing to our target audiences.

## User Evaluation

### Plan

### Takeaways