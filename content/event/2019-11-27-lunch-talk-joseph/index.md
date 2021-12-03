---
title: "SERG Lunch: The State of Automated Dependency Updating Services"

# event: 
# event_url: 

location: Social Data Lab, Building 28

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2019-11-27T12:30:00Z"
date_end: "2019-11-27T13:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Joseph Hejderup]
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


**TL;DR** See attached Twitter thread

Software developers love package management systems! They provide a simple gateway to import thousands of free third-party libraries into your code. What is not free is the maintenance of third-party libraries: you have to keep up-to-date with news about your libraries (also known as dependencies) such as security fixes and performance bugs. This is challenging as we don't use one dependency but a small network of them! As a solution, there are several services on [Github](https://github.com/) such as [dependabot](https://dependabot.com/), [renovate](https://renovate.whitesourcesoftware.com/), and [depfu](https://depfu.com/) that automate this tedious task for you. This is great! However, in this talk, I will explain the problems of trusting automated dependency updating services and a solution that can mitigate some of the problems!


![Skärmavbild 2019-11-21 kl  12 36 32](https://user-images.githubusercontent.com/2521475/69348493-8f6a3d00-0c76-11ea-8b13-f6f603cb9703.png)

