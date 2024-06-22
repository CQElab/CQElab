---
# Leave the homepage title empty to use the site title
title:
date: 2024-06-12
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: hero
    content:
      title: Chen Quantum Engineering Lab
      text: University of Washington
      announcement:
          text: PhD and postdoc positions available.
          link:
            text: Read more
            url: opportunities/
    design:
      css_class: dark
      background:
        color: transparent
        image:
          # Add your image background to `assets/media/`.
          filename: welcome.gif
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false

  - block: 'github.cqelab.stats'
    content:
      items:
        - statistic:
          description: |
            Quantum Devices and Materials
        - statistic: 
          description: |
            Quantum Control and Sensing
        - statistic: 
          description: |
            Quantum Computation
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]

  - block: 'github.cqelab.markdown'
    content:
      title: ""
      subtitle: ''
      text: |-
        We are an upcoming research lab at the University of Washington. Our aim is to advance **Quantum Science and Engineering** through the experimental and theoretical study of solid-state platforms spanning **Superconducting quantum circuits**, **atomic-scale defect centers**, and **nanophononics**. 

        Our group operates at the boundary of experiment and theory. Through a co-design process, we seek to 1) develop a profound understanding of quantum device physics and materials challenges, and 2) to build enabling next-generation solid-state quantum devices for quantum computation, quantum sensing, and quantum communication. Check out our [research](projects/) page for more information.

        We are a highly interdisciplinary group, with backgrounds in materials science, mechanical engineering, electrical engineering, and physics. We are always looking for talented and motivated students and postdocs to join our group. Check our [open positions](opportunities/) page for more information.
    design:
      spacing:
        padding: [0, 0, 0, 0]

  - block: 'github.cqelab.collection'
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 6
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [64px, 64px, 0, 64px]
        
  - block: 'github.cqelab.markdown'
    content:
      title: Advising Statement
      subtitle: ''
      text: |-
        Coming soon!
    design:
      columns: '1'
---
