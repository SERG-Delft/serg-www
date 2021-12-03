---
title: "SERG talk: A Model for Detecting Faults in Build Specifications"

# event: 
# event_url: 

location: Online

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-12-16T12:00:00Z"
date_end: "2020-12-16T13:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Thodoris Sotiropoulos, Athens University of Economics and Business]
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


**Abstract:** 
Incremental and parallel builds are crucial features of
modern build systems. Parallelism enables fast builds by
running independent tasks simultaneously, while incrementality
saves time and computing resources by processing the build
operations that were affected by a particular code change.
Writing build definitions that lead to error-free incremental
and parallel builds is a challenging task. This is mainly
because developers are often unable to predict the effects of
build operations on the file system and how different build
operations interact with each other. Faulty build scripts may
seriously degrade the reliability of automated builds, as they
cause build failures, and non-deterministic and incorrect outputs.

To reason about arbitrary build executions, we present BuildFS, a
generally-applicable model that takes into account the specification
(as declared in build scripts) and the actual behavior (low-level
file system operation) of build operations. We then formally define
different types of faults related to incremental and parallel builds
in terms of the conditions under which a file system operation
violates the specification of a build operation. Our testing approach,
which relies on the proposed model, analyzes the execution of single
full build, translates it into BuildFS, and uncovers faults by
checking for corresponding violations.

We evaluate the effectiveness, efficiency, and applicability of our
approach by examining 612 Make and Gradle projects. Notably, thanks to
our treatment of build executions, our method is the first to handle
JVM-oriented build systems. The results indicate that our approach is
(1) able to uncover several important issues (247 issues found in
47 open-source projects have been confirmed and fixed by the
upstream developers), and (2) much faster than a state-of-the-art tool
for Make builds (the median and average speedup is 39X and 74X respectively).

**Short bio:**
[Thodoris Sotiropoulos](https://www.balab.aueb.gr/thodoris-sotiropoulos.html) is a PhD candidate at the [Department of Management Science and Technology](https://www.dept.aueb.gr/en/dmst). He holds an MSc with distinction in Advanced Computing from Imperial College London, and a BSc in Management Science and Technology from the Athens University of Economics and Business. He has previously worked in industry as a software engineer at the Greek Research and Technology Network (GRNET). His main research interests include programming languages, program analysis, software testing, and software reliability.


