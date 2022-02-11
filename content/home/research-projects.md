---
widget: custom-portfolio
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...
title: Research projects
weight: 30

content:
  # Page type to display. E.g. project.
  page_type: project

# Uncomment to only show content with specific tags
# filters:
#   tags:
#     - tag

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below)
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `filter_button` below.
  filter_button:
    - name: Featured
      tag: 'featured'
    - name: Category 1
      tag: cat-1
    - name: Category 2
      tag: cat-2
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact  
  #   3 = Card
  #   4 = Citation
  #   5 = Showcase
  #   6 = Simple Card (Custom)
  view: 6
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
