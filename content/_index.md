---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Machine Learning for Materials Design
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Our research group **Machine Learning for Materials Design** is a research department of the [Center for Advanced Systems Understanding](https://www.casus.science) 
        at [Helmholtz-Zentrum Dresden-Rossendorf](https://www.hzdr.de).
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: <a class="twitter-timeline" data-theme="light" href="https://twitter.com/AttilaCangi?ref_src=twsrc%5Etfw">Tweets by AttilaCangi</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---