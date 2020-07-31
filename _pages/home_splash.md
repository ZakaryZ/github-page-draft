---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#000"
  overlay_image: /images/0.jpg
  overlay_filter: 0.7
  caption: "Photo: [**Tamsui, Taiwan by Yijuan Zhi**]()"
  actions:
    - label: "Learn More About Me"
      url: /about/
excerpt:
  Welcome to Yijuan Zhi's blog!<br>
  <small> I recently graduated from University of Massachusetts, Amherst with a bachelor degree in Computer Science and a minor degree in Mathematics. </small>
intro: 
  - excerpt: 'This blog is where I share the notes I am taking or took. Including technical stuff learning, leetcode notes and commands learning. `progress = learning` '
feature_row:
  - image_path: /images/technical_main2.png
    alt: "Technical Notes"
    title: "Technical Notes"
    excerpt: "Technical learning diary, including web programming, network, OS, etc"
    url: /blog/
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /images/leetcode_main.png
    alt: "LeetCode Notes"
    title: "LeetCode Notes"
    excerpt: "Collecting classic and typical leetcode question notes"
    url: /blog/
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /images/command_main.jpg
    alt: "Commands Notes"
    title: "Commands Notes"
    excerpt: "Terminal's best friends, commands for emacs, git, npm, mongodb, etc"
    url: /blog/
    btn_class: "btn--primary"
    btn_label: "Learn more"      
---
{% include feature_row id="intro" type="center" %}
{% include feature_row %}