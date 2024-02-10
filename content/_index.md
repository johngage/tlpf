---
# Leave the homepage title empty to use the site title
title:
date: 2024-2-10
type: landing

sections:
  - block: hero
    content:
      title: |
        Tegla Loroupe Peace Foundation
    banner:
      image: 'tlhome.jpg' 

      caption: 'Image credit: Olympics Committee'
    ßimage:
        filename: tlhome.jpg
      text: |
        <br>
        
Ambassador Tegla Loroupe has led the World Olympics Refugee Team to two Olympics.
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
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---