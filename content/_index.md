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
      title: Active Research Areas
      text: 
      filters:
        folders:
          - project
        # Exclude content with these tags
        exclude_tags: [R Package, guide]
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
      
  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
      archive:
        enable: true
        text: See all publications
        link: publication/
      sort_by: 'Date'
      sort_ascending: false
    design:
      columns: '1'
      view: list
          
  - block: portfolio
    id: rpackages
    content:
      title: R Packages
      text: 
      filters:
        folders:
          - project
        # Exclude content with these tags
        exclude_tags: [Research, guide]
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
      
  - block: portfolio
    id: teaching
    content:
      title: Currently Teaching
      text: 
      filters:
        folders:
          - course
        # Exclude content with these tags
        exclude_tags: [inactive]
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: 2
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
      
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
