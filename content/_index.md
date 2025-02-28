---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
---
<script type="text/javascript">
  window.location.href = '/tour/';
</script>

sections:
  - block: hero
    content:
      title: |
        BioAI
        Research Group
      image:
        filename: welcome1.jpg
      text: |
        <br>
        Welcome to the BioAI Lab at the School of Computer Science, Xiangtan University!<br>
        <br>
        Our lab is dedicated to advancing the frontiers of artificial intelligence, multimodal large models, and intelligent drug discovery. We invite you to explore our research and join us in shaping the future of AI-driven healthcare! Our ultimate ambition is to build a transformative framework for end-to-end intelligent drug discovery, leveraging cutting-edge AI technologies to design and optimize therapeutic molecules. 


  - block: collection
    content:
      title: |
        RESENT POSTS
      count: 3
      filters:
        folders:
          - news
      design:
        view: ciation
        columns: '1'
      
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'


  # - block: collection
  #   content:
  #     title: Recent Tutorials
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: tutorials
  #   design:
  #     view: card
  #     columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       # publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

---
