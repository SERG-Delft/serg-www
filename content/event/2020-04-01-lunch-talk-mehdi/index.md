---
title: "SERG Lunch: Ecosystem-Scale Call Graph Construction"

# event: 
# event_url: 

location: Online

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-04-01T12:30:00Z"
date_end: "2020-04-01T13:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Mehdi Keshani]
tags: [events,lunch-talks]

# Is this a featured talk? (true/false)
featured: true

# Adding an image and image caption
# image:
# caption: 
# focal_point: Right

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: []

# Projects (optional).
#   Associate this post with one or more projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

---


This presentation will be about the FASTEN project and ongoing research that builds the basis of FASTEN.

Slides are available [here](/slides/2020-04-01-lunch-talk-mehdi.pdf).

The main goal of the FASTEN project is to make package management more intelligent. Incidents like leftpad (A significant portion of the Internet has been broken by removing a package from a package manager) proved that the current way of managing packages has some flaws. FASTEN wants to mitigate such flaws by enriching package managers with method-level information. The idea behind FASTEN is to use call graph level information instead of package-level information. In order to provide call graph level information, we use call graph construction tools. However, the existing tools are designed for project-level use cases(e.g. in compilers, etc.) and do not work properly in the ecosystem-scale. In this presentation, I talk about FASTEN, how it works and how do we make call graph construction scalable.

