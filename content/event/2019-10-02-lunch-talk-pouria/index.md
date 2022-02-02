---
title: "SERG Lunch: Class Integration Testing (CLING)"

# event: 
# event_url: 

location: Social Data Lab, Building 28

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2019-10-02T12:30:00Z"
date_end: "2019-10-02T13:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Pouria Derakhshanfar]
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


Search-based approaches have been used in the literature to automate the process of creating unit test cases. However, related work has shown that generated unit-tests with high code coverage could be ineffective, i.e., they may not detect all faults or kill all injected mutants. In this paper, we proposed an integration-level test case generator named CLING, that exploits the integration code of a pair of classes (caller and callee) that interact with one another through method calls. In particular, CLING generates integration-level test cases that maximize the Coupled Branches Criterion (CBC). CBC is a novel integration-level coverage criterion that measures how thoroughly a test suite exercises the interactions between callers and callees. We evaluate CLING on 140 pairs of classes from five different open-source Java projects. Our results show that (1) CLING generates test suites with high CBC coverage; (2) such generated suites can kill, on average, 10% mutants that are not killable by unit-level tests generated with EvoSuite for the same classes; (3) CLING detects 29 integration faults that remain undetected when using automatically generated unit-level test suites.

