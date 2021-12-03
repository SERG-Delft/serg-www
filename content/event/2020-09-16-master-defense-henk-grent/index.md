---
title: "Master Thesis Defense on Automatically Identifying Parameter Constraints for Complex Web APIs: A Case Study at Adyen"

# event: 
# event_url: 

location: Zoom

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-09-16T16:00:00Z"
date_end: "2020-09-16T17:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Henk Grent]
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


Web APIs can have constraints on parameters, such that not all parameters are either always required or always optional. Sometimes the presence or value of one parameter could cause another parameter to be required. Additionally, parameters could have restrictions on what kinds of values are valid. We refer to these as inter-parameter and single-parameter constraints respectively. Having a clear overview of the constraints can help API consumers to integrate without the need for additional support and with fewer integration faults.
We developed two approaches for identifying parameter constraints in complex web APIs. One approach uses online documentation to infer inter-parameter constraints, the other depends on static code analysis to extract inter- and single-parameter constraints from the control ﬂow of the API’s source code. In our case study at several APIs at Adyen, the documentation- and code-based approach can identify 21% and 53% percent of the constraints respectively. When the constraints identiﬁed by both approaches are combined, 66% of the inter-parameter constraints can be identiﬁed. Code analysis is able to identify 78% of the single-parameter constraints.

Thesis: [link](http://resolver.tudelft.nl/uuid:672634ec-53ee-4ebd-a1f0-c958c646a261)

