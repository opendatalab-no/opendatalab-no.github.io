---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/header-image1.png
  caption:
excerpt: 'A site for publishers and users of open data'
intro: 
  - excerpt: 'This lab is hosted by SINTEF. The purpose is to experiment with support and tools for overcomming barriers to publication and use of open data. We would like to test the lab in collaboration with hackatons and other initiatives for use of (open) data.'
feature_row:
  - image_path: /assets/images/what-is-open-data.png
    alt: "what is open data"
    title: "What is open data?"
    excerpt: "Get a quick introduction to what open data is."
    url: "/news/open-data/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - image_path: /assets/images/publish-data.png
    alt: "publishing"
    title: "Publishing open data"
    excerpt: "Information and tools for owners and providers of open data."
    url: "/publish/intro/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - image_path: /assets/images/use-data.png
    alt: "using"
    title: "Using open data!"
    excerpt: "Information and tools for innovators and developers using open data."
    url: "/use/intro/"
    btn_class: "btn--primary"
    btn_label: "Learn More"

news: 
  - excerpt: 'Recent posts:'
feature_row2:
  - image_path: /assets/images/node-red-icon.png
    alt: "prototyping"
    title: "Using Node-Red for Open Data"
    excerpt: "Node-red is a graphical tool for making prototypes. See how you can use the tool to connect to SBanken and more."
    url: "/news/using-nodered/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - image_path: /assets/images/Survey_Icon.png
    alt: "survey"
    title: "Tell us about your experience!"
    excerpt: "Help us learn more about what makes open data easy or difficult to use."
    url: "/news/survey/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
    
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="news" type="center" %}

{% include feature_row id="feature_row2" %}