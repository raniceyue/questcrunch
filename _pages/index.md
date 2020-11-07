---
# The HOME page of the website~~
title: "QuestCrunch"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-1.jpg # Banner for prototype here
  actions:
    - label: "View Prototype"
      url: "https://github.com/mmistakes/minimal-mistakes/" # Link to prototype here
excerpt: "Helping students focus better!" # Call to action
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'

feature_row:
  - image_path: /images/phase0.svg
    alt: "placeholder image 2"
    title: "Phase 0"
    excerpt: 'Phase 0 was when we created our Project Proposal for our initial conceptualization of the application.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row2:
  - image_path: /images/phase1.svg
    alt: "placeholder image 2"
    title: "Phase 1A/B"
    excerpt: 'Phase 1A/B was when we constructed our User Study Plan, and conducted our User Study on our target users.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row3:
  - image_path: /images/phase2.svg
    alt: "placeholder image 2"
    title: "Phase 2A"
    excerpt: 'Phase 2A was when we began experimenting with different types of user interface styles and prototypes to consider for our final prototype'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row4:
  - image_path: /images/phase2b.svg
    alt: "placeholder image 2"
    title: "Phase 2B"
    excerpt: 'Phase 2B was when we conducted our Expert (Peer) Evaluation, to get a feeling of the '
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row5:
  - image_path: /images/phase2c.svg
    alt: "placeholder image 2"
    title: "Phase 2C"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row type="center" %}

{% include feature_row id="feature_row2" type="center" %}

{% include feature_row id="feature_row3" type="center" %}

{% include feature_row id="feature_row4" type="center" %}

{% include feature_row id="feature_row5" type="center" %}
