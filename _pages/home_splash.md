---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#000"
  overlay_image: /images/2020-08-01-firstblog/hello-image.jpg
  overlay_filter: 0.3
  caption: "Photo: [**At Kaohsiung City, Taiwan by an_vision*]()"
  actions:
    - label: "Learn More About Me"
      url: /about/
excerpt:
  Welcome to Yijuan Zhi's blog! <br>
  <small> In May 2020, I graduated from University of Massachusetts, Amherst with a bachelor degree in Computer Science and a minor degree in Mathematics. <br> I will be joining Antra as a SDE in Sep 2020! I am so excited for it! </small>
intro: 
  - excerpt: This blog is where I share the notes I am taking or took. Including technical stuff learning, leetcode notes and commands learning. <br> `progress = learning`
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