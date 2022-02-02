---
title: "PhD Defense: The Application Perspective of Mutation Testing"

# event: 
# event_url: 

location: Online

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-06-24T12:30:00Z"
date_end: "2020-06-24T14:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Qianqian Zhu]
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


The main goal of this thesis is to investigate, improve and extend the applicability of mutation testing. To seek the potential directions of how to improve and extend the applicability of mutation testing, we have started with a systematic literature review on the current state of how mutation testing is applied. The results from the systematic literature review have further guided us towards three directions of research:

1. speeding up mutation testing;
2. deepening our understanding of mutation testing;
3. exploring new application domains of mutation testing. 

For the first direction, we have leveraged compression techniques and weak mutation information to speed up mutation testing. The results have shown our proposed mutant compression techniques can effectively speed up strong mutation testing up to 94.3 times with an accuracy > 90%. Given the second direction, we are interested in gaining a better understanding of mutation testing especially in the situation where engineers cannot kill all the mutants by just adding test cases. We have investigated the relationships between code quality regarding the testability and observability, and the mutation score. We have observed a correlation between observability metrics and the mutation score. Furthermore, relatively simple refactoring operations/adding tests enable an increase in the mutation score. As for the third direction, we have explored two new application domains: one is physical computing, and the other is GPU programming. In both application domains, we have designed new mutation operators based on our observations of the common mistakes that could happen during the implementation of the software. We have found promising results in that mutation testing can help in revealing weaknesses of the test suite for both application domains. In summary, we have improved the applicability of mutation by proposing a new speed-up approach and investigating the relationship between testability/observability and mutation testing. Also, we have extended the applicability of mutation testing in physical computing and GPU programming domains.

**Thesis:** [doi](https://doi.org/10.4233/uuid:116a487e-c14d-47f8-b1f5-8e9738d263d0)

**Advisors:** Andy Zaidman, Annibale Panichella, Arie van Deursen



