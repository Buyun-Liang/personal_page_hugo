---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: Powerlifting
subtitle:

content:
  # # Page type to display. E.g. post, event, publication...
  page_type: powerlifting
  # Filter on criteria
  # filters:
  #   folders:
  #     - powerlifting
  #   tag: ''
  #   category: ''
  #   publication_type: ''
  #   author: ''
  #   exclude_featured: false
  #   exclude_future: false
  #   exclude_past: false
    # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0
  filter_button:
    - name: Selected
      tag: 'Selected'
    - name: All
      tag: '*'
  # Choose how many pages you would like to display (0 = all pages)
  count: 5
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
  

design:
  # Choose a view for the listings:
  view: 0
  # columns: '2'
---