---
title: "PhD Defense: Augmented fine-grained defect prediction for code review"

# event: 
# event_url: 

location: Senaatszaal, TU Delft

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-09-02T10:00:00Z"
date_end: "2020-09-02T12:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Luca Pascarella]
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


Summary

Code review is a widely used technique to support software quality. It is a manual activity, often subject to repetitive and tedious tasks that increase the mental load of reviewers and compromise their effectiveness. The developer-centered nature of code review can represent a bottleneck that does not scale in large systems with the consequence of com- promising firms’ profits. This challenge has led to an entire line of research on code review improvement.
In this thesis, we present our results and remarks on the effectiveness of using fine- grained defect prediction in code review while investigating what are the information needs that lead a proper code review. We started reimplementing the state of the art of defect prediction to understand its replicability; then, we evaluated this model in a more realistic scenario that is typically considered. To improve defect prediction techniques, we come up with a fine-grained just-in-time defect prediction model that anticipates the prediction at commit time and reduces the granularity at the file level. After that, we explored how to improve further prediction performance by using alternative sources of information. We conducted a comprehensive investigation of code comments written by both open and closed source developers. Finally, to understand how to improve code review further, we explored from a reviewers’ perspective what is the information that reviewers need to lead a proper code review.
Our findings show that the state of the art of defect prediction, when evaluated in a realistic scenario, cannot be directly used to support code review. Furthermore, we assessed that alternative sets of metrics, anticipated feedback, and fine-grained suggestions represent independent directions to improve prediction performance. Finally, we discovered that research must create intelligent tools that other than predict defects must satisfy actual reviewers’ needs, such as expert selection, splittable changes, realtime communication, and self summarization of changes.

Thesis: [link](https://www.lucapascarella.com/articles/thesis/luca-pascarella-phd-thesis.pdf)

**Advisors:** Alberto Bacchelli, Arie van Deursen

