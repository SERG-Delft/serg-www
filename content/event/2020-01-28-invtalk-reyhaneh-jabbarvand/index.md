---
title: "Advancing Energy Testing of Mobile Apps"

# event: 
# event_url: 

location: Social Data Lab

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-01-28T13:45:00Z"
date_end: "2020-01-28T14:45:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Reyhaneh Jabbarvand]
tags: [events,talks]

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


## Abstract

The utility of a smartphone is limited by its battery capacity and the ability of its hardware and software to efficiently use the device’s battery. To properly characterize the energy consumption of an app and identify energy defects, it is critical that apps are properly tested, i.e., analyzed dynamically to assess the app’s energy properties. However, currently there is a lack of testing tools for evaluating the energy properties of apps. As a result, for energy testing, developers are relying on tests intended for evaluating the functional correctness of apps. Are such tests adequate for revealing energy defects in apps? If not, what are the properties of tests that can effectively find energy inefficiencies in apps and how can we automatically generate such tests? Answers to these questions are the subject of my presentation. 

In the first part of this talk, I will introduce μDroid, a mutation testing technique that can be used by developers to assess the adequacy of their test suite for revealing energy-related defects. Applying μDroid to real-world Android apps with available test suites showed that current Android testing tools are in fact ineffective at finding energy defects. Based on the insights from this study, I identified characteristics of tests that can effectively find energy issues in Android apps. In the second part of this talk, I will present COBWEB, a search-based evolutionary energy testing technique that automatically generates energy tests. Experimental results on real-world Android apps demonstrate not only COBWEB's ability to effectively and efficiently test energy behavior of apps, but also its superiority over state-of-the-art and state-of-practice techniques in finding a wider and more diverse set of energy defects.


## Biography

Reyhaneh Jabbarvand is a PhD candidate in the Donald Bren School of Information and Computer Sciences at the University of California, Irvine (UCI), advised by Prof. Sam Malek. Her research interests are in the area of Software Engineering with a focus on developing new techniques to produce secure and energy efficient software. She is the lead author of several publications that have appeared in top Software Engineering venues, including ICSE, ESEC/FSE, ISSTA, and ASE. Reyhaneh has been awarded the Google PhD Fellowship in Programing Technology and Software Engineering for her work on advancing energy testing of Android and has been recognized as a Rising Star in EECS. She was one of the first one who explored the usage of testing to assess energy behavior of mobile apps. Through her research, she has constructed a comprehensive energy defect model for Android by identifying a large number of energy anti-patterns. Her proposed techniques helped reveal several types of previously unknown energy defects in open-source Android apps, which were fixed by the patches she provided to their developers. 

More info about her can be found at: [https://www.ics.uci.edu/~jabbarvr/](https://www.ics.uci.edu/~jabbarvr/)



