---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: As a cognitive psychologist and practicing Buddhist, I am curious about the ways in which we use attention, how well we are able to use it, and how it impacts our mind and life in meaningful ways. <br><br>Read more about me [here](/authors/admin)
  - block: features
    content:
      title: Skills
      items:
        - name: Psychology
          description: Experimental, Differential, and Neuroscience
          icon: brain
          icon_pack: fas
        - name: Statistics
          description: Genearl Linear Model, Structural Equation Modelling, and more
          icon: chart-line
          icon_pack: fas
        - name: R
          description: Data Science, Analysis, and Package Development
          icon: r-project
          icon_pack: fab
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '1'
      view: compact
      background: 
        color: '#ABBEC4'
  - block: portfolio
    id: projects
    content:
      title: Projects
      text: 
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: Research
          tag: Research
        - name: R Packages
          tag: R Package
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      background:
        color: '#698996'
---
