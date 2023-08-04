---
title: Research
sections: 
- block: collection
    content:
      title: Working papers
      filters:
        folders:
          - research
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Work in progress
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - research
        exclude_featured: true
    design:
      columns: '2'
      view: citation

cms_exclude: true
# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 3

# Optional header image (relative to `static/media/` folder).
header:
  caption: ''
  image: ''
---
