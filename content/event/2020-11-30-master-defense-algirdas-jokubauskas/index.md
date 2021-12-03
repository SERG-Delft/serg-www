---
title: "Master Thesis Defense on Investigating Dependency Code Reuse Using Callgraphs"

# event: 
# event_url: 

location: Online (Zoom)

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-11-30T09:00:00Z"
date_end: "2020-11-30T11:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Algirdas Jokubauskas]
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


Software development is more and more reliant on external code. This external code is developed, bundled into packages and shared using package repositories like crates.io or npm. Reusing shared code bundles greatly improves development speed but without proper care and knowledge of included external code it can cause issues as well. Over-reliance on simple trivial packages that can be easily implemented locally can cause severe consequences like not being able to build if the package is no longer available. Furthermore, including large packages when only a small amount of it is being used can cause software projects become bloated with unnecessary code. This thesis proposes several metrics: leanness index, software composition index and utilization index that quantify how software projects reuse their dependencies or how much of the dependencies are utilized by their dependents. All three of the metrics are based on full function callgraph of the applications. Computation of these metrics was implemented for Rust and applied on every package in Rust package repository crates.io. General findings showed that dependency leanness was rather low: 21.7% of all packages in crates.io used less than 5% of their included dependencies while 95% of all crates used less than 62.4%. Another discovery revealed that packages in crates.io tend to consist mostly of code from external dependencies as opposed to local code: on average 91% of lines of code come from external dependencies. Lastly, using utilization index functions that were never used by any other crate in crates.io were identified: in 95% of packages, 71% of their callgraphs are never used.

