---
title: "PhD Defense: Supporting Quality In Test Code For Higher Quality Software Systems"

# event: 
# event_url: 

location: Senaatszaal, TU Delft

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2021-03-18T15:00:00Z"
date_end: "2021-03-18T17:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Davide Spadini]
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

Automated testing has become an essential process for improving the quality of software systems. Automated tests can help ensure that production code is robust under many usage conditions and that code meets performance and security needs. Nevertheless, writing effective tests is challenging and, unfortunately, often neglected. In the first part of this dissertation, we summarize and explain why test and production code are not treated with the same care, and we set our goal: we want to discover new techniques and tools to support developers when writing and reviewing code. To this aim, we investigate the impact of test design issues on code quality and the practices when writing and reviewing test code.

First, we create and make publicly available Pydriller, a Python framework to analyze software repositories that will help us gather important information for the following studies. Then, we study test design issues and their impact on the overall software code quality, demonstrating how important it is to have a good and effective test suite. Afterward, together with SIG, a company setting in which part of this dissertation was conducted, we study how developers in industry react to these test design issues. Our results show that the current detection rules for test issues are not precise enough and, more importantly, do not support prioritization. We present new rules that can be used to prioritize these issues and show that the results achieved with the new rules better align with developers’ perception of importance.

In the second part of the dissertation we focus on how to help developers better reviewing test code. First, we investigate developers’ needs when it comes to code reviewing, identifying seven high-level information needs that could be addressed through automated tools, saving up time for reviewers. Then, we focus on code review of test code specifically: we first study when and how developers review test code, identifying current practices, revealing the challenges faced during test code reviews, and uncovering needs for tools that can support the review of test code. Later, we investigate the impact of TestDriven Code Review (TDR) on the code review effectiveness, showing that it can increase the number of test code issues found. We discuss when TDR can and can not be applied and why not all developers see TDR as a worthy practice.




**Advisors:** Alberto Bacchelli, Arie van Deursen

