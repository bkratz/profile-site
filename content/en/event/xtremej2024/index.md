---
title: "By the bye: JNI"
slug: xtremej_2024
event: XtremeJ
event_url: https://xtremej.dev/

location: Remote
# address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States

summary: JNI vs FFM - a (subjective) comparison
abstract: |
  Many years ago I was working for a project in which we had to integrate a program written in C into a web application written in Java. The C program was doing complex financial calculations, developed over many many years. No chance to rewrite it in Java.
  The solution was to integrate it via JNI (Java Native Interface). Painful memories to this day.
  Reading and writing programs with JNI is very "rough" (to say the least) and has many traps and pitfalls.
  With project "Panama" and the new "Foreign Function & Memories API"  (FFM) Java is aiming to address exactly these pain-points when working with code and data outside of the JVM-runtime.
  This new API has made me curious.  In this talk I want to compare the native calls using JNI and the new Foreign Function & Memories API. How does it feel and does FFM keep its promises?
  I hope (and believe) that at the end of this comparison there will be a definite "Goodbye to JNI".

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2024-11-04T17:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2024-11-04T00:00:00Z"

authors: []
tags: [event]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
url_code: "https://github.com/bkratz/SudokuSolverFFM"
url_pdf: ""
url_slides: "uploads/XtremeJ_2024_ByTheByeJNI.pdf"
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:

---
