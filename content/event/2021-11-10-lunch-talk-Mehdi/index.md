---
title: "Frankenstein: Fast and Lightweight Call Graph Generation for Software Builds"

# event: 
# event_url: 

location: Online

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2021-11-10T11:00:00Z"
date_end: "2021-11-10T12:00:00Z"
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


Abstract:

all Graphs are a rich data source and built the foundation for advanced static analysis that can, for example, detect security vulnerability or dead code. Call Graph generation is usually considered to be a full program analysis: not just the program, but also all its dependencies are processed together. Unfortunately, this is very expensive and makes it hard to run these static analyses in build systems that are typically limited in resources. Even powerful servers would suffer from slow build times, which renders these analyses impractical. We will address this problem by proposing an incremental implementation of a Class-Hierarchy Analysis algorithm for the call graph generation. We adopt existing work on incremental program analysis and solve the specific challenges that emerge for call graph generation in Java. Our approach leverages the fact that, very often, dependency sets do not change between builds: we can generate call graphs for these dependencies, cache their generation for the subsequent build, and introduce a novel stitching algorithm, Frankenstein, that merges all these partial call graphs into a complete call graph for the whole program. Our evaluation results show that this lightweight approach can substantially outperform the fastest existing framework, OPAL, by a median of 5.9X (average 2.6X). We further show that we do not add any overhead to the memory usage of existing tools. This makes the proposed approach practical for build systems with limited memory resources. Despite all the improvements in speed, we can achieve call graphs for which the set of identified call edges is close to identical to our baseline OPAL(F1: 0.95). Such an incremental approach for call-graph generation will open the door for using expensive static analyses in build processes.

