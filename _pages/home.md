---
title: "Welcome!"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/splash/code.jpg
  actions:
    - label: "Blog"
      url: "/posts/"
excerpt: "This is Ryan Harding's personal website. Feel free to explore. Thank you for stopping by!"
intro: 
  - excerpt: 'I am a computer science major at the University of Texas in Austin. I hope to use computers to make the world a better place. Click below to learn more about me.'
  - url: "/about/"
    btn_label: "About Me"
    btn_class: "btn--primary"
feature_row:
  - image_path: /assets/splash/feat1-1.jpg
    title: "Projects"
    excerpt: "Personal coding projects, hosted and explained in depth."


  - image_path: /assets/splash/feat1-2.jpg
    title: "Career Updates"
    excerpt: "Information relating to work endeavors and professional developments."


  - image_path: /assets/splash/feat1-3.jpg
    title: "Tech News"
    excerpt: "Captivating, important, and insightful tech developments. All right here."


---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}