---
# A Recent and Upcoming Talks section created with the Pages widget.
# This section displays recent talks from `content/talk/`.

widget: "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless: true       # This file represents a page section.
active: true         # Activate this widget? true/false
weight: 50           # Order that this section will appear.

title: "Teaching"
subtitle: ""

content:
  # Page type to display. E.g. post, talk, or publication.
  page_type: teaching
  
  # Choose how much pages you would like to display (0 = all pages)
  count: 5
  
  # Choose how many pages you would like to offset by
  offset: 0

  # Page order. Descending (desc) or ascending (asc) date.
  order: desc

  # Filter posts by a taxonomy term
  filter_default: 0
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "\*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: "All"
      tag: "*"
    
    - name: "Statistics"
      tag: "statistics"

    - name: "Programing"
      tag: "programing"
  
    - name: "AI/Bioinformatics"
      tag: "machine learning"
      tag: "bioinformatics"

    - name: "Epidemiology"
      tag: "epidemiology"

    - name: "Talks"
      tag: "talk"

    
design:
  columns: 2

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 3
  
  
advanced:
 # Custom CSS. 
 css_style: ""

 # CSS class.
 css_class: ""
---