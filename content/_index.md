---
# Leave the homepage title empty to use the site title
title:
date: 2024-2-10
type: landing

sections:
  - block: markdown
    content:
      title: 1 new block
      subtitle: My subtitle
      text: 'Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code! and more. do I need quotes? 
      who knows? this is the new line, with  quotes'
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'


  - block: hero
    content:
      title: 2 Tegla Loroupe Peace Foundation
    # banner:
    # image: tlhome.jpg
    # caption: 'Image credit: Olympics Committee'
      image:
        placement: 3
        caption: 'Photo by '
        focal_point: 'Center'
        preview_only: false
        alt_text: Ambassador Tegla Loroupe
        filename: tlhome.jpg
      text: 
        <br>     
        Ambassador Tegla Loroupe has led the World Olympics Refugee Team to two Olympics.

  - block: collection
    content:
      title: 3 Latest News
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
      title: 4
      subtitle: ''
      text:
    design:
      columns: '1'
     # background:
      #  image: 
       #   filename: tlhome.jpg
        #  filters:
       #     brightness: 1
       #   parallax: false
       #   position: center
       #   size: cover
        #  text_color_light: true
     # spacing:
     #   padding: ['20px', '0', '20px', '0']
     # css_class: fullscreen
  
  - block: markdown
    content:
      title: 5
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  - block: markdown
    content:
      title: '6 Tegla Loroupe Peace Foundation 
      <br>
      ## The Tegla Loroupe Peace Foundation creates peace initiatives in East African pastoralist conflict areas.

      Since its founding in 2003 by **World Champion Tegla Loroupe**, thousands of athletes have trained and competed in Peace Races held in conflict areas in Kenya, in Uganda, and in other conflict areas.
<hl>
Since 2015, hundreds of refugee athletes from South Sudan, Congo, Ethiopia, Somalia and other countries have trained at the [Tegla Loroupe International Olympic Refugee Training Camp in Ngong, Kenya](http://bit.ly/37Y0sc3), just  to the west of Nairobi.

In 2016, Ambassador Tegla Loroupe led the International Refugee Olympic team to Rio, where five of the Ngong Training Camp athletes competed.

In 2021, Ambassador Tegla Loroupe led the International Refugee Olympic team to Tokyo.

Tegla Loroupe describes who we are:  an organization dedicated to athletes who compete for themselves, for their families, for their societies, and for peace, honesty and justice among all peoples.'

      subtitle: Peace Through Sports Again
  #    image:
  #    placement: 2
   #   focal_point: right
    design:
      columns: '1'
      background:
        image: 
          filename: tlhome.jpg
          image_darken: 0.9
          image_size: cover
          image_position: left
          image_parallax: true
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen


   
  - block: markdown
        content:
          title: 7
          subtitle: ''
          text:
        design:
          columns: '1'
          background:
            image: 
              filename: tlhome.jpg
              filters:
                brightness: 1
              parallax: false
              position: center
              size: cover
              text_color_light: true
          spacing:
            padding: ['20px', '0', '20px', '0']
          css_class: fullscreen
---


