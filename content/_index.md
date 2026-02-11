---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24

type: landing

sections:
  - block: slider
    content: 
      slides:
      - title: Welcome to
        content: 'Taiwan–Japan Neuroscience Exchange Association (TJNEA)'
        align: left
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.75
          position: right
          color: '#666'
    design:
      slide_height: ''
      is_fullscreen: true
      loop: false
      interval: 2000
  
  - block: collection  
    content:
      title: News
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
      view: stream #card
      columns: '2'

  - block: contact
    content:
      text: |
        {{% cta cta_link="../about/" cta_text="Read more →" %}}
         
    design:
      columns: '2'
---
