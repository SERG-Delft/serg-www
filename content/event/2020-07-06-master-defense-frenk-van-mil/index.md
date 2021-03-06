---
title: "Master Thesis Defense on Inferring Personality from GitHub Communication Data: Promises & Perils"

# event: 
# event_url: 

location: Skype

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-07-06T10:15:00Z"
date_end: "2020-07-06T12:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Frenk van Mil]
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


Personality plays a significant role in our lives; it does not only influence what we think, feel, and do, but also affects what we say about what we think, feel, and do. In software engineering (SE), it might help in improving team composition through a combination of personalities within a team, and it could help explain work preferences and work satisfaction. Earlier studies in the field of software engineering have focused on extracting personality from developers with the use of questionnaires and automatic tools such as psycholinguistic tests. Psycholinguistic tests infer personality based on the words people use. As taking questionnaires is time-consuming, the interest in automated tools has grown. However, there is a lack of studies comparing different psycholinguistic models on actual SE data to validate to what extent these tools apply to software engineering.

In this study, we compare two well-established academical models proposed by Yarkoni and Golbeck and the popular industrial model Personality Insights by IBM. We use the three models to infer personality from comments on open-source projects on GitHub and compare the found scores to a ground-truth obtained through a questionnaire among software developers.

In this study, we establish a baseline and compare three models on their performance to this baseline. We show three methods to perform almost equally when mean-centered, indicating the three methods may work on different scales. We show log-transformations to improve LIWC category scores found by reducing the effect of outliers and give recommendations for thirteen preprocessing steps to improve the inference on SE data. We found 600 to 1200 words per person to provide sufficient accuracy while remaining resource-aware and recommend a minimum of a hundred words for all three methods. Furthermore, we do not find enough evidence for discrimination by all three methods for people proficient in English compared to those who found themselves non-proficient in English.

We find existing psycholinguistic models to be most useful for software engineering when used on a group or team level. When used on an individual level, one should take into account possible inaccuracies and consider the potentially harmful impact the misuse or misinterpretation of scores may have on an individual.

Thesis: [link](https://repository.tudelft.nl/islandora/object/uuid%3Ac58343a1-3700-42c4-bc81-aacca9f54248)

