---
title: My page
type: landing
author: admin

sections:
  - block: v1/about
  - block: 
    content:
      title: A little more about me...
      text: 
      
        I am originally from Bothell, WA (~30 miles north of Seattle). I will always consider Washington State as my home. I earned my B.A. in Behavioral Neuroscience at Western Washington University. This is where I found my interest in cognitive psychology. I took a year off after college to participate in an 8-week silent meditation retreat on Shamatha and the Four Immeasurables in Phuket, Thailand with my teacher [Alan Wallace](https://www.alanwallace.org). 
        
        
        From there I went on to do a 2 year M.A. program in General Experimental Psychology at California State University, San Bernardino (CSUSB). At CSUSB I worked with Dr. Hideya Koshino doing research on selective attention and working memory. 
        
        
        I was, then, accepted into Randy Engle’s lab as a Ph.D. student at Georgia Tech. I graduated with my Ph.D. in December 2022. My research in the lab involves investigating the nature of attention control with the use of pupillometry. I make use of the R statistical programming language to analyze data in a way that is most consistent with open science and reproducibility practices. I have developed several R Packages relevant to the lab's research. 
        
        
        Outside of psychology, my interests include Buddhist spiritual practice (mainly influenced by the Nyingma tradition from Tibetan Buddhism and Dzogchen teachings in particular), teaching meditation and mindfulness practices, hiking, camping, riding my bicycle around town, and photography.
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
