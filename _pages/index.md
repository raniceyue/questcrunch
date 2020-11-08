---
# The HOME page of the website~~
title: "QuestCrunch"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image:  # Banner for prototype here
  actions:
    - label: "View Prototype"
      url: "https://www.figma.com/proto/b6j5J3EQfgije7wrV8qEiU/CS3240-Team-24-Final-Prototype?node-id=185%3A7968&scaling=scale-down" # Link to prototype here
excerpt: "Helping students focus better!" # Call to action
intro: 
  - excerpt: 'Hello! We are Group 24, and this is our portfolio website, documenting the conceptualization and design process of our project prototype, QuestCrunch. <br> <br> 
  
  QuestCrunch is an educational mobile application aimed towards helping teachers aid their students in developing self-study habits outside of school and tuition.
  Read more about our application [here](/questcrunch/about)'

feature_row:
  - image_path: /images/phase0.svg
    alt: "placeholder image 2"
    title: "Project Proposal"
    excerpt: 'Phase 0 was when we conceptualised our idea of our application, the problems we our application wanted to address, and the solutions that we wanted to provide in our application, through our Project Proposal.'
    url: "/our-process/#project-proposal"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row2:
  - image_path: /images/phase1.svg
    alt: "placeholder image 2"
    title: "User Study - Planning and Execution"
    excerpt: 'Phase 1A/B was when we constructed our User Study Plan, and conducted a user study on our target user groups-- teachers, and students, to gain a better insight on the pain points and struggles of students in developing self-study habits.'
    url: "/our-process/#user-study-plan"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row3:
  - image_path: /images/phase2.svg
    alt: "placeholder image 2"
    title: "Prototyping"
    excerpt: 'Phase 2A was when we began prototyping our application. We exeprimented with different styles, and came up with features that address the pain points highlighted in our user study.'
    url: "/our-process/#design-process"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row4:
  - image_path: /images/phase2b.svg
    alt: "placeholder image 2"
    title: "Evaluation"
    excerpt: 'Phase 2B was when we conducted our Expert (Peer) Evaluation, to get more insights on the usability and intuitiveness of our user interface. From Phase 2A, we selected 2 prototypes to be used for our Expert Evaluation. The insights gained from this phase were used to further refine and develop a semi-final prototype.'
    url: "/evaluation/#expert-peer-evaluation"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row5:
  - image_path: /images/4.svg
    alt: "placeholder image 2"
    title: "Final Prototype"
    excerpt: ''
    url: "/evaluation/#expert-peer-evaluation"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="left" %}

{% include feature_row id="feature_row5" type="left" %}

