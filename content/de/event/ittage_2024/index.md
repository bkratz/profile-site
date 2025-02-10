---
title: "By the bye: JNI"
slug: ittage_2024
event: IT Tage
event_url: https://www.ittage.informatik-aktuell.de

location: Frankfurt
# address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States

summary: JNI vs FFM - ein (subjektiver) Vergleich
abstract: |
  Vor vielen Jahren habe ich in einem Projekt einen in C geschriebenen Rechenkern in eine in Java geschriebene Web-Anwendung einbinden müssen.
  Der Rechenkern war recht komplex und über Jahre "gereift". Somit war es keine Option, ihn in Java neu zu schreiben.
  Die Lösung:  den Rechenkern aus der Web-Anwendung heraus über JNI (Java Native Interface) aufzurufen.
  Eine bis heute schmerzhafte Erinnerung.
  Das Lesen und Programmieren von JNI ist sehr "spröde" (um es freundlich auszudrücken) und birgt zudem noch einige Gefahren.

  Mit Projekt Panama und der neuen "Foreign Function and Memory API"  hat man sich auf die Fahnen geschrieben, genau diese Sprödheit und die Gefahren beim Arbeiten mit Code und Daten außerhalb der JVM-Runtime zu umgehen.

  Das hat meine Neugier geweckt. Ich möchte in diesem Vortrag gegenüberstellen, wie sich native Aufrufe mit JNI und mit der "Foreign Function und Memory API" umsetzen lassen.
  Ist die Sprödheit in der neuen Welt Geschichte?
  Kann ich jetzt wirklich gefahrlos APIs aufrufen, die nicht in Java implementiert sind und nicht in einer JVM laufen?

  Ich hoffe (und glaube) am Ende der Gegenüberstellung steht ein eindeutiges "Goodbye to JNI".
# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2024-12-10T17:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2024-12-10T00:00:00Z"

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
url_slides: "uploads/IT_Tage_2024_ByTheByeJNI.pdf"
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
