---
title: "SERG Lunch: A Simple Implementation of the Delta Maintainability Model"

# event: 
# event_url: 

location: Online

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-05-13T12:30:00Z"
date_end: "2020-05-13T13:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Arie van Deursen]
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


The Delta-Maintainability Model (DMM) offers a methodology for assessing the way an individual commit affects the maintainability of a system.
In a nutshell, the DMM measures the proportion of _low-risk change_ in a commit. The resulting value ranges from 0.0 (all changes are risky) to 1.0 (all changes are low risk). It rewards making methods better, and penalizes making things worse.

Recently, we implemented a simple version of the DMM as part of [PyDriller](https://github.com/ishepard/pydriller), the open source git repository mining tool.

In this talk, we walk through the Delta-Maintainability Model, discuss the implementation choices made, offer a comparison with the (more robust) DMM implementation provided by SIG, and explore its application to a number of open source systems.

This is based on joint work with Marco di Biase and Magiel Bruntink from the [Software Improvement Group](https://www.softwareimprovementgroup.com/).

See  also:

1. Marco di Biase, Ayushi Rastogi, Magiel Bruntink, and Arie van Deursen. The Delta Maintainability Model: measuring maintainability of fine-grained code changes. IEEE/ACM International Conference on Technical Debt (TechDebt) at ICSE 2019, pp 113-122 ([online](https://pure.tudelft.nl/portal/en/publications/the-delta-maintainability-model-measuring-maintainability-of-finegrained-code-changes(6ff67dee-2781-47d7-916f-bd36c5b61beb).html)).

2. The PyDriller [documentation of the DMM](https://pydriller.readthedocs.io/en/latest/deltamaintainability.html).

3. Davide Spadini, Maur??cio Finavaro Aniche and Alberto Bacchelli. PyDriller: Python framework for mining software repositories. ESEC/SIGSOFT FSE 2018: 908-911 ([online](https://pure.tudelft.nl/portal/en/publications/pydriller-python-framework-for-mining-software-repositories(5985f510-058b-4f79-93b0-c30730f561d9).html)).

