---
title: "Master Thesis Defense on A Distributed and Scalable Real-Time Log Analysis"

# event: 
# event_url: 

location: Online (zoom)

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-10-20T14:30:00Z"
date_end: "2020-10-20T16:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Rick Proost]
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


Monitoring software behaviour is being done in various ways. Log messages are being output by almost any kind of running software system. Therefore, learning how software behaves from doing analysis over log data can lead to new insights about the system. However, the number of log messages in a computer system grow fast, and analysing the log data by hand is a time-consuming job.

The objective of this study is to propose and implement a scalable architecture for doing real-time log analysis. Log data is structured so that analysis can take place, and the solution is horizontally scalable in every module so that the approach can scale with an ever-growing software solution. The focus of the study is on scalability, and ease-of-use of the implementation of the proposed approach.

The proposed solution can scale horizontally and the test set up showed that reporting features for anomalies remained instantaneous when processing 1.2 million log lines per minute. The usability of the proposed approach is tested in a case study at Weave, where bugs were found by running the proposed solution in a controlled environment.


