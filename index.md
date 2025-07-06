---
layout: home
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/bio-photo.jpg
  actions:
    - label: "View Resume"
      url: "/resume.pdf"
    - label: "Contact Me"
      url: "/contact/"
excerpt: "PhD Student in Computer Science at Stanford University, specializing in Artificial Intelligence and Machine Learning. Passionate about building intelligent systems that can understand and interact with the world."
intro: 
  - excerpt: 'I am a PhD student in Computer Science at Stanford University, working on cutting-edge research in artificial intelligence and machine learning. My work focuses on developing intelligent systems that can understand, reason, and interact with the world around us.'
feature_row:
  - image_path: /assets/images/research-unsplash.jpg
    alt: "Research"
    title: "Research"
    excerpt: "Exploring the frontiers of AI and ML with a focus on developing intelligent systems."
    url: "/research/"
    btn_label: "Learn More"
    btn_class: "btn--primary"
  - image_path: /assets/images/projects-unsplash.jpg
    alt: "Projects"
    title: "Projects"
    excerpt: "Building innovative applications and tools that showcase practical AI implementations."
    url: "/projects/"
    btn_label: "View Projects"
    btn_class: "btn--primary"
  - image_path: /assets/images/publications-unsplash.jpg
    alt: "Publications"
    title: "Publications"
    excerpt: "Contributing to the scientific community through peer-reviewed publications."
    url: "/publications/"
    btn_label: "Read Papers"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
