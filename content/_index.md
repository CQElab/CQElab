---
# Leave the homepage title empty to use the site title
title:
date: 2024-06-12
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: 'github.cqelab.coverimage'
    content:
      title: Chen Quantum Engineering Lab
      text: University of Washington
      announcement:
          text: Our website has moved!
          link:
            text: Visit
            url: https://sites.uw.edu/chenmo/
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

  - block: 'github.cqelab.markdown'
    content:
      title: ""
      subtitle: ''
      text: |-
        We are an experimental group at the University of Washington, dedicated to advancing **Quantum Science and Engineering**. We leverage both experimental and theoretical tools to explore solid-state platforms, including **superconducting qubits**, **atomic-scale defects**, and **nanophononics**. 

        We have moved to a [new lab website](https://sites.uw.edu/chenmo/), visit us there!
    design:
      spacing:
        padding: [0, 0, 0, 0]

  # - block: 'github.cqelab.collection'
  #   content:
  #     title: Recent CQE News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 6
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     # Reduce spacing
  #     spacing:
  #       padding: [64px, 64px, 0, 64px]
        
  # - block: 'github.cqelab.markdown'
  #   content:
  #     title: Advising Statement
  #     subtitle: ''
  #     text: |-
  #       Coming soon!
  #   design:
  #     columns: '1'
---
