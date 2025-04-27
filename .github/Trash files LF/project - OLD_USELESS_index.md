---
title: Project
summary: My projects
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: project
    content:
      title: Project
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 2
---
