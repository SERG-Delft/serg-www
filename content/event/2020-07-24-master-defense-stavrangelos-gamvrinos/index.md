---
title: "Master Thesis Defense on Language-agnostic Incremental Code Clone Detection"

# event: 
# event_url: 

location: Zoom

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-07-24T10:00:00Z"
date_end: "2020-07-24T12:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Stavrangelos Gamvrinos]
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


Code duplication is a form of technical debt frequently observed in software systems. Its existence negatively affects the maintainability of a system in numerous ways. In order to tackle the issues that come with it, various automated clone detection techniques have been proposed throughout the years. However, the vast majority of them operate using the entire codebase as input, resulting in redundant calculations and undesirable delays when this process is repeated for every new revision of a project. On the other hand, newer incremental techniques address this by storing intermediate information that can be reused across revisions. However, all these approaches are language-specific, utilizing language parsers to generate more sophisticated source code representations, in an attempt to detect more complex types of clones. As a result, less popular languages, for which finding or building a parser is challenging, are unfortunately not supported. 

In this study we propose LIICD, a language-agnostic incremental clone detector, capable of detecting exact-match clones. We assess its performance and compare it with a state-of-the-art commercial-grade detector, found within the Software Improvement Group (SIG). Furthermore, we use a similarity estimation technique called Locality Sensitive Hashing (LSH) in an attempt to extend and improve the original approach. Our experiments result in some interesting findings. Firstly, the proposed incremental detector is very efficient and able to scale well for larger codebases. Additionally, it provides a significant improvement compared to a non-incremental commercial-grade detector. Lastly, our LSH-based extension proves to have difficulties matching our original approach's performance. However, future suggestions indicate how the potential of the technique can be further investigated.

