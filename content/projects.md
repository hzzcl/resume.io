---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Recent News
      text: ''
      filters:
        folders:
          - project
    design:
      # 原来的参数
      # view: article-grid
      fill_image: true
      # columns: 3
      #新参数
      # View options: showcase, cards, masonry, list-v2, list-v1, compact, article-grid
      view: showcase
      # For showcase, card, masonry views, position the image on the
      # left/right (order: 1) or at top/bottom (order: 2)
      flip_alt_rows: false
      # Card view footer options: show (default), hide
      show_card_footer: false
      # Number of items per row or in carousel
      columns: 1
      # For list-v1 and list-v2 views
      show_dates: false
---
