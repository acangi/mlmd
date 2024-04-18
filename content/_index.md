---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    design:
      columns: 2
    content:
      title: |
        {{< figure src="mlmd_logo.png" width="200" >}}
      text: |
        # Machine Learning for Materials Design
        
        **The Machine Learning for Materials Design** research group accelerates materials innovation through machine learning and computational modeling, with a focus on developing sustainable materials for a greener future. Our applications span energy storage devices, thermoelectrics, spintronics, neuromorphic devices, and advanced semiconductor modeling.

        Our research group is research department of the [Center for Advanced Systems Understanding](https://www.casus.science) 
        at [Helmholtz-Zentrum Dresden-Rossendorf](https://www.hzdr.de).


  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 1
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
      view: showcase
      columns: '2'
  

  - block: markdown
    content:
      title: Social Media
      subtitle:
      text: <a class="twitter-timeline" data-lang="en" data-height="600" data-theme="light" href="https://twitter.com/AttilaCangi?ref_src=twsrc%5Etfw">Tweets by AttilaCangi</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    design:
      view: card
      columns: '2'
  

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---