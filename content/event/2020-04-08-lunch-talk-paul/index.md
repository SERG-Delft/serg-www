---
title: "SERG Lunch: Improving SPLs test suites using adversarial generation"

# event: 
# event_url: 

location: Online

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-04-08T12:30:00Z"
date_end: "2020-04-08T13:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Paul Temple]
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


In this talk, I will present a technique related to the test of Software Product Lines. This problem is hard due to (i) the high number of variants that are usually considered in SPLs, and (ii) the new dimension added to the tests for the assessment of performances (i.e., providing inputs that may impact the performances of the variants). Thus, it is necessary to try to reduce the number of inputs to assess the performances of the different variants, which, in the end, may have an impact on the choice made by the end-users for choosing one specific variant. Machine Learning is now very common in various situations, including performance prediction of variants or constraints discovery in the combination of features that are allowed by a feature model. In the Machine Learning community, starting from the late 2000s, a new trend has appeared trying to warn against the abusive use of Machine Learning models in various domains and the potential risks that they may incur. This trend is known as adversarial machine learning. It aims at crafting inputs for machine learning models to make them perform erroneous prediction. I will present our attempts at the University of Namur to use these kinds of techniques to generate new inputs and variants that may mislead prediction models used in the context of SPLs testing.

[Paul Temple](https://templep.github.io) is a post-doc working for the PReCISE research center of the University of Namur. His reserach interests include machine learning, softwre product line engineering, and software testing.

Slides are available [here](https://github.com/templep/Delft_Presentation).

