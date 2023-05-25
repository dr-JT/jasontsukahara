---
title: My page
type: landing
author: admin

sections:
  - block: v1/about
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        tags: [jtsukahara]
        featured_only: true
      archive:
        enable: true
        text: See all publications
        link: publication/
      sort_by: 'Date'
      sort_ascending: false
    design:
      columns: '1'
      view: compact
---
