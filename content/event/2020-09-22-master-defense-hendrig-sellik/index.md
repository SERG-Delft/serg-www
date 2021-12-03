---
title: "Master Thesis Defense on Using Deep Learning to Detect Off-by-One Errors in Java Source Code"

# event: 
# event_url: 

location: Zoom

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-09-22T10:00:00Z"
date_end: "2020-09-22T11:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Hendrig Sellik]
tags: [events,defenses]

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


Mistakes in binary conditions are a source of error in many software systems. They happen when developers use < or > instead of <= or >=. These boundary mistakes are hard to find for developers and pose a manual labor-intensive work. While researches have been proposing solutions to identify errors in boundary conditions, the problem remains a challenge. Therefore it is necessary to research and develop new techniques to cope with such errors.

In this thesis, we proposed deep learning networks to learn mistakes in boundary conditions and later detect them in code never seen before. We trained our model on approximately 1.6M examples with faults in different boundary conditions. We achieved an accuracy of 85.06\%, a precision of 85.23\% and a recall of 84.82\% on a controlled dataset. Additionally, we performed tests on 41 real-world boundary condition bugs found from GitHub and tried to find bugs from the Java project of Adyen. However, the false-positive rate of the model remains an issue.

