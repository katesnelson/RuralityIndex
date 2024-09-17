---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Community Assets and Relative Rurality (CARR)
      image:
        filename: carr_orig_map.jpeg
      text: |
        <br>
        
        The **CARR index** is a continuous, multidimensional measure of rurality based on the concept of sustainable development that integrates measures of environmental, social, and economic resources.
  
  - block: collection
    content:
      title: News and Updates
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
          filename: carr_orig_map.jpeg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Featured Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: portfolio
  - id: projects
    content:
      title: Data Documentation
      text: ""
      filters:
        folders:
          - project
design:
         columns: '1'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
