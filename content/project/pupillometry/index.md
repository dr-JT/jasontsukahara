---
title: pupillometry
summary: An easy to use R package to preprocess pupil data for researchers that are not experts in either pupillometry or working with data in R
tags:
  - R Package
date: '2022-08-25T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://dr-jt.github.io/pupillometry/index.html'

image:

links:
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---

### An R package to preprocess pupil data

This package was developed for ease-of-use for researchers that are not experts in either pupillometry or working with data in R. The preprocessing steps can easily be implemented using the pipe operator `%>%` and a code template is provided: [Preprocessing Code (Template)](https://dr-jt.github.io/pupillometry/articles/preprocess_overview.html) in which preprocessing steps can be modified and/or removed.

This package contains various functions for different steps in the preprocessing pipeline for pupil data. The preprocessing steps are based on current standards such as:

- deblinking

- artifact rejection (e.g., MAD)

- smoothing (low-pass filter)

- interpolation

- baseline correction

```r
data_pupil <- pupil_read("folder/file.csv", eyetracker = "eyelink") %>%
  pupil_deblink(extend = 75) %>%
  pupil_artifact(n = 16) %>%
  pupil_smooth(type = "mwa", n = 51) %>%
  pupil_interpolate(type = "linear") %>%
  pupil_baselinecorrect(bc_onset_message = "Stimulus_Onset")
```
