---
# An instance of the Featured widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: featured
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 3

title: Featured Research
subtitle: ""

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publication

  # Choose how many pages you would like to display (0 = all pages)
  count: 8
  # Filter on criteria
  filters:
    publication_type: "2"
    author: ""
    category: ""
    tag: ""

  # Fixed editorial order, independent of publication date.
  sort_by: Params.featured_order
  order: asc

design:
  columns: '1'
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 4
---
