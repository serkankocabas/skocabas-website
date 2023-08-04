---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: collection
    id: featured
    content:
      title: Working papers
      filters:
        folders:
          - content/research
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
          - content/research
        exclude_featured: true
    design:
      columns: '2'
      view: citation
---
