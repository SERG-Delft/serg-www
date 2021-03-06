---
title: "PhD Defense: Data-Driven Software Engineering"

# event: 
# event_url: 

location: Senaatszaal, TU Delft

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2021-03-24T17:30:00Z"
date_end: "2021-03-24T19:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Vladimir Kovalenko]
tags: [events,talk]

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


**Summary**

Specialized tools, such as IDEs, issue trackers, and code review tools, are an indispensable part of the modern software engineering process. These tools are constantly evolving. Besides enabling tools to support a wider range of technologies and frameworks, we are learning to provide additional features in completely new ways. One prominent stream of innovation in software engineering tools is dedicated to utilizing historical data to enable data-driven features, such as defect prediction engines and recommender systems, which leverage records of prior activity to assist with decision making. Many data-driven features in software engineering tools initially get born out of the context of real-world tools as techniques devised and evaluated in synthetic settings by researchers. While convenient, synthetic evaluation of approaches that are ultimately aimed at bringing improvement to real world problems involves a number of simplifications and assumptions.

In this dissertation, we highlight several aspects that, while vital for bringing innovative methods to software engineering tools, are often discarded in existing research. We closely explore several topics specific to artificial evaluation environments, such as simplifications in mining file modification histories, use of synthetic datasets for source code authorship attribution, and a gap between accuracy of reviewer recommendation models and their perception by users. Moreover, we make a case for sharing technical artifacts by converting data mining pipelines into reusable tools, and propose a novel approach to modeling expertise transfer from code modification by capturing individual contribution style of developers.

Key contributions of this dissertation include a high-level model of the lifecycle of a data-driven software engineering technique, a discussion of dangerous assumptions and simplifications that are made on every step in this lifecycle, a demonstration of importance of a careful approach to mining software repositories, and a demonstration of serious misalignment between artificial evaluation and realistic environments for the problems of code reviewer recommendation and code authorship attribution.

We conclude the dissertation by discussing underlying reasons for misalignment between research environments and real-world tools, and propose potential steps to narrow it down and ultimately accelerate innovation in software engineering tooling.


**Advisors:** Alberto Bacchelli, Arie van Deursen

