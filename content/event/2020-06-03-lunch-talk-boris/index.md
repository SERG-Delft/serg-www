---
title: "SERG talk: JCrashPack2.0: Search-based crash reproduction hardness analysis"

# event: 
# event_url: 

location: Online

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-06-03T14:00:00Z"
date_end: "2020-06-03T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Boris Cherry]
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


This talk discusses the results of my three months internship in the SERG team, done as part of my master thesis at the [University of Namur](https://www.unamur.be/en/inf). During this internship, I worked with [Xavier Devroey](http://xdevroey.be) and [Pouria Derakhshanfar](https://twitter.com/pderakhshanfar) on [JCrashPack](https://github.com/STAMP-project/JCrashPack), a benchmark for Java crash reproduction. More specifically, I explored the following question: Can we measure the difficulty for search-based crash reproduction to reproduce a crash using software quality metrics?

**Abstract:**  Search-Based Crash Reproduction (SBCR) aims to help developers in their debugging tasks by generating a test case that reproduces a specific crash based on its stack trace and the source code. In traditional search-based unit test generation approaches, the hardness to generate test cases is evaluated using static code analysis, like complexity, coupling, or code size. Unlike unit test generation, SBCR does not seek to achieve high structural coverage but to reproduce a specific behavior leading to a crash. In this work, we revisit links between SBCR and software quality metrics to assess the hardness of search-based crash reproducing test case generation. We use the values of the fitness function of Botsing, a search-based crash reproducing tool, as an indicator of the difficulty of the tool to reproduce a crash. Our results show pieces of evidence of an existing link between some software quality metrics and the values of the fitness score. However, we did not find any strong correlation between an individual metric and the hardness to reproduce a crash.

