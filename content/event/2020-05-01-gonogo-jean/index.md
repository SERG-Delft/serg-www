---
title: "Data-driven Log Recommendation"

# event: 
# event_url: 

location: online

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-05-01T15:00:00Z"
date_end: "2020-05-01T16:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Jeanderson Candido]
tags: [events]

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


In this talk, I will be discussing the challenges of logging an enterprise
system in the context of Adyen, our industry partner, and talk about my ongoing
work.

Log data plays a key role in many important analysis tasks that critical for
business such as auditing, application performance monitoring (APM), and root
cause analysis (RCA).  However, developing and maintaining logging code is
hard: developers need to choose an appropriate log level, message format,
variables that must be logged, and where to place log statements.  Many
empirical studies provide evidence that logging is usually conducted
afterthoughts and highlight the need for tooling support to assist developers.

My current work focuses on the problem of log placement. Since this
presentation is part of my Go/No-Go Meeting, I am going to revisit the work
I've done in my first year and share my vision and goals for my Ph.D.


