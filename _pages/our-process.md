---
layout: single
classes: wide
title: "Our Process"
permalink: /our-process/
sidebar:
    nav: "sidebar-nav"
toc: true
toc_label: "Table of Contents"

gallery:
  - url: 
    image_path: /images/unnamed1.png
    alt: 
    title:
  - url: 
    image_path: /images/unnamed2.png
    alt: 
    title:
---

## Project Proposal

**The Initial Idea**

Our initial project idea, was called PomoFomo. Our idea for PopoFomo was to create an application that encourages students to study, using peer motivation and competition between peers. 

The main idea for the application is to create a platform where students have access to a shared virtual room with their friends and they can work together to complete self-scheduled timed study sessions, and earn coins upon completion of a study session. The coins earned then can be used to decorate the shared virtual room with their friends. Friend may compete with each other through viewing total coins accumulated on a common leaderboard between friend groups, or between individuals. 

<img src="../images/pomofomo.png" width="200" alt="Shared Room in PomoFomo"/>{: .align-center}
_Shared Room in PomoFomo_

The competition and rewards offered by these features were something we saw as a solution to address the pain points and frustrations of studying alone.

<img src="../images/ideas.svg" alt="drawing" width="300"/>{: .align-center}

In the creation of our project proposal, we decided to come up with a list of features that we may want to see as students using the application, through creating _user stories_, using [Trello](https://trello.com/en), which is a online application that acts like a corkboard with sticky notes for brainstorming purposes.

[View Our Trello](https://trello.com/b/sV0HTqzV/pomofomo){: .btn .btn--info}

**Issues**

However, we realised that this solution is already widely available and several existing platforms such as Forest and Pomodoro already address this issue of lack of focus and motivation among students. Hence, we decided to specialize our target audience and re-focus the solution to the problem we aimed to solve. 

**QuestCrunch**

We decided to create an application that enables teachers to ensure productivity of their students, for events such as timed quizzes, assignments or mock papers. As there is no existing solution for this niche market, the lack of home-based learning solutions for teachers was something we felt was pertinent to address, especially now with the Covid-19 situation where students are expected to stay motivated and disciplined at home. Thus, QuestCrunch was born. 


## User Study Plan

<img src="../images/interview.svg" alt="drawing" width="300"/>{: .align-center}

As our application aims to provide a solution that involves both teachers and students, we have 2 target users, namely teachers and students. Our User Study Plan consists of online surveys, as well as online scripted interviews with real teachers and students within the Secondary and Junior College level. 

Upon completion of the User Study Plan, our team was able to gain more insights on the issues students may face from both the student's personal perspective, as well as from the perspective of experienced teachers who may have more understanding on the behaviours and worries of their students, and the struggles a student may face when studying.

Using the insights gained, we were able to have an idea of the kind of functions and features that will be useful in addressing the pain points highlighted in our user study. Thus began our design process.

Our complete User Study Plan and the results and responses received from the students and teachers we interviewd and took our surveys, can be viewed at the link below in `pdf` form

[View User Study Report](../downloads/user-study-plan.pdf){: .btn .btn--info}

## Design Process

### Ideation Stage  

The team came together to brainstorm different possible user interfaces using the Crazy 8's method exercise practiced in lecture

![](../images/pasted image 0.png)

{% include gallery caption="" %}

![](../images/harshi-crazy8.png)



### Prototype 1st Iteration
For this 1st iteration, each member came up with 1 prototype each based on our own design ideas, and the list of functions we had came up with for QuestCrunch.


{% include figure 
    image_path="/images/v1.png" 
    caption="Prototypes 1, 2, 3 and 4" 
%}

{% capture links-to-prototypes %}

**Links to Prototypes**  
- [Prototype 1](https://www.figma.com/file/Thxmllsblou1vUSflYXVrk/CS3240-Project-Prototype?node-id=0%3A1)
- [Prototype 2](https://www.figma.com/file/UA5p3GrWht12BUhlObDx4X/Elizabeth-Prototype?node-id=1%3A137) 
- [Prototype 3](https://www.figma.com/file/PQWmo02hn3ZehW9WVRuF23/QuestCrunch-Prototype---Harshita?node-id=0%3A1)  
- [Prototype 4](https://www.figma.com/file/1ToIF30VJqs9NkOJ5psGkh/CS3240-QuestCrunch-Beats-Prototype?node-id=0%3A1)  

{% endcapture %}

<div class="notice--primary">{{ links-to-prototypes | markdownify }}</div>

The above prototypes were evaluated by our group's TA, who gave feedback, and insights on the features that she liked from each prototype

### Prototype 2nd Iteration
For the 2nd iteration, we decided to pick the 2 best prototypes from the 4 prototypes in the 1st iteration, to be used for our [Expert (Peer) Evaluation]().

**Prototype A**  
Prototype A is a minimalist take on the application, with a soothing colour palette and simplified icons. We felt that its simple UI could be appealing to teachers, which is one of our major target user groups.

{% include figure 
    image_path="/images/v2-1.png" 
    caption="Prototype A" 
%}

**Prototype B**  
Prototype B is a gamified take on the application, with a bold colour palette and pixel art that grabs attention. We felt that this eye-catching UI could be appealing to students, which is our other major target user group.

{% include figure 
    image_path="/images/v2-2.png" 
    caption="Prototype B" 
%}

Using these 2 prototypes, we conducted our [Expert (Peer) Evaluation]() to guage the usability, pros and cons of each respective prototype. We aimed to use the results, opinions and feedback gathered from the evaluation to further refine and create a final prototype from the 2 prototypes. 

### Prototype 3rd Iteration
For the 3rd iteration, after gathering feedback from our expert evaluation, we decided to combine the good aspects of each respective prototype into 1 semi-final prototype.

![](../images/v3-1.png)
![](../images/v3-2.png)

In coming up with this 3rd iteration of the prototype, we carefully considered _Neilson's Heuristics_ in the design of each page and employed 8 of the heuristics in our design.

| Heuristic          | Feature in Prototype |
|--------------------|----------------------|
|Visibility of system status |  a. When user does an action, they will receive a notification pop up to indicate completeness of the action taken <br> b. Teachers are informed of the the number of available rewards in the rewards tab |
|Match between system and the real world | a. Icons that were used mirrors similar events in the real world: eg: to represent the calendar view, we had a Calendar icon. A House icon to represent the home page. These icons are very much understandable and user were able to navigate through the prototype well. <br> b. Teachers are informed of the availability status of rewards through the 3-colour traffic colour theme (green, yellow, red) to represent available, runnings low or unavailable respectively |
|User control and freedom | Users are allowed to go back when they are on secondary pages (not the landing page for respective menu tab icons) |
|Consistency and standards | Buttons, fonts and font size were standardized throughout the final prototype |
|Error Prevention | We included respective warning messages for ‘dangerous’ acts such as deleting rewards and forfeiting quests |
|Recognition over recall | a. The calendar view helps to consolidate the quests for the month <br> b. The home page also displays new quests for the students so that students do not have to remember which quests were already present and which are new <br> c. There is a progress bar for students when doing quest so that they do not have to remember the time left |
|Flexibility and Efficiency of Use | a. Students can scan a QR code or type in the generated code to join a class <br> b. Students can also view and join quests in list form of calendar form |
|Aesthetic and minimalistic Design| The functionalities offered to the both sets of users only have the relevant information presented to them. Eg. for the statistics shown for quest for students, the view only allows students to see the overall statistics, whereas for teachers, they are able to view the specific groups who have not completed the quest |

Using this 3rd prototype, we conducted another evaluation with our target users, Teachers and Students. 

### Prototype 4th Iteration
For the 4th iteration, after gathering insights from our [Real User Evaluation](/questcrunch/evaluation/#user-evaluation), we decided to do one last polish of our application's user interface based on the feedback given by our real users.

We sought to fix the design issues raised from the evaluation, and made further changes to standardise the styling of our components, and made certain labels easier to comprehend so that our application would be easier to navigate through. Thus resulted in our fourth and final prototype for the application. 

{% include figure 
    image_path="/images/v4.png"
    caption="Prototype 4th Iteration" 
%}