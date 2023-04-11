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
      text: My research focuses on the control of attention and its role in mind and life. <br><br>Read more about me [here](/jasontsukahara)
  
  - block: portfolio
    id: projects
    content:
      title: Projects
      text: 
      filters:
        folders:
          - project
        # Exclude content with these tags
        exclude_tags: []
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
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
      
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
      archive:
        enable: true
        text: See all publications
        link: publication/
    design:
      columns: '1'
      view: list
      
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
---
