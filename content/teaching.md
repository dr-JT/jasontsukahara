---
title: Teaching
type: landing

sections: 

  - block: portfolio
    content:
      title: Currently Teaching (Fall 2023)
      subtitle: Undergraduate Level
      filters: 
        folders: 
          - course
        exclude_tags: [graduate, inactive]
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: 2
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  
  - block: portfolio
    content:
      title: Previous Courses
      subtitle: Graduate Level
      text: 
      filters:
        folders:
          - course
        exclude_tags: [active, undergraduate]
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: 2
      background:
        color: "#F7F7F7"
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ["100px", "0", "0", "0"]
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  
  - block: portfolio
    content:
      title: '&nbsp;'
      subtitle: Undergraduate Level
      text: 
      filters:
        folders:
          - course
        exclude_tags: [active, graduate]
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: 2
      background:
        color: "#F7F7F7"
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ["0", "0", "100px", "0"]
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      
  
---
