---
title: "SERG talk: JUGE, An Infrastructure for Benchmarking Java Unit Test Generators"

# event: 
# event_url: 

location: Online

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2021-06-16T11:00:00Z"
date_end: "2021-06-16T12:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Xavier Devroey]
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

Researchers and practitioners have designed and implemented various automated test case generators to support effective software testing. Such generators exist for various languages (e.g., Java, C#, or Python) and for various platforms (e.g., desktop, web, or mobile applications). Such generators exhibit varying effectiveness and efficiency, depending on the testing goals they aim to satisfy (e.g., unit-testing of libraries vs. system-testing of entire applications) and the underlying techniques they implement. In this context, practitioners need to be able to compare different generators to identify the most suited one for their requirements, while researchers seek to identify future research directions. This can be achieved through the systematic execution of large-scale evaluations of different generators. However, the execution of such empirical evaluations is not trivial and requires a substantial effort to collect benchmarks, setup the evaluation infrastructure, and collect and analyse the results. In this paper, we present our JUnit Generation benchmarking infrastructure (JUGE) supporting generators (e.g., search-based, random-based, symbolic execution, etc.) seeking to automate the production of unit tests for various purposes (e.g., validation, regression testing, fault localization,etc.). The primary goal is to reduce the overall effort, ease the comparison of several generators, and enhance the the knowledge transfer between academia and industry by standardizing the evaluation and comparison process. Since 2013, eight editions of a unit testing tool competition, co-located with the Search-Based Software Testing Workshop, have taken place and used and updated JUGE. As a result, an increasing amount of tools (over ten) from both academia and industry have been evaluated on JUGE, matured over the years, and allowed the identification of future research directions. Based on our experience in the competition, we discuss the expected impact of JUGE in improving the knowledge transfer on tools and approaches for test generation between academia and industry. Indeed, the JUGE infrastructure demonstrated an implementation design that is flexible enough to enable the integration of further unit test generation tools, which is practical for developers, and that allows researchers to experiment with new, advanced unit testing tools and approaches.

**Paper:** [arXiv:2106.07520](https://arxiv.org/abs/2106.07520)

**Short bio:** See [https://xdevroey.be](https://xdevroey.be).







