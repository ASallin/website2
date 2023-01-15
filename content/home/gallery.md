---
# An instance of the Featured widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 70

title: "Gallery"

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: markdown
  # Choose how many pages you would like to display (0 = all pages)
  count: 3
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
  
design:
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 2
  columns: '4'
---
{{< gallery album="demo" >}}