---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/header.svg
  caption:
excerpt: 'A site for publishers and users of open data'
intro: 
  - excerpt: "This lab is hosted by [SINTEF](http://www.sintef.no).<br/>The purpose of the lab is to experiment with support and tools for overcoming barriers to publication and use of open data. We would like to test the lab in collaboration with hackatons and other initiatives for use of (open) data."
feature_row:
  - image_path: /assets/images/publish-icons.png
    alt: "publishing"
    title: "Publishing open data"
    excerpt: "Information and tools for owners and providers of open data."
    url: "/publish/intro/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - image_path: /assets/images/use-icons.png
    alt: "using"
    title: "Using open data"
    excerpt: "Information and tools for innovators and developers using open data."
    url: "/use/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - image_path: /assets/images/research-icons.png
    alt: "survey"
    title: "Research on open data"
    excerpt: "[Help us learn more](/news/survey) about what makes open data easy or difficult to use, and learn more about our research."
    url: "/research/intro/"
    btn_class: "btn--primary"
    btn_label: "More info"

feature_row2:
  - image_path: /assets/images/kommuner-uten-hav.svg
    alt: "Data from Norwegian Municipalities"
    title: "Data from Norwegian Municipalities"
    excerpt: "Find out which open data sets are available from the ten municipalities in Norway with the highest population."
    url: "/news/municipalities/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - image_path: /assets/images/showcases-icon.png
    alt: "Showcases"
    title: "Showcases using open data"
    excerpt: "Descriptions of cases using open data, including references to the data used and links open source repositories."
    url: "/showcases/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - image_path: /assets/images/node-red-icon.png
    alt: "prototyping"
    title: "Prototyping with open data using Node-red"
    excerpt: "Node-red is a graphical tool for making prototypes. See how you can use the tool to connect to SBanken and more."
    url: "/news/using-nodered/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
    
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" %}