---
title: "SERG Lunch: How to Analyze Build Logs using Chunk Retrieval"

# event: 
# event_url: 

location: Discord

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2020-03-25T12:30:00Z"
date_end: "2020-03-25T13:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Carolin Brandt]
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


You will hear the presentation I gave for my master thesis defense in Munich :)

Slides are available [here](https://surfdrive.surf.nl/files/index.php/s/Pv4sffs1hJVNTtP).

Continuous integration produces detailed logs about the status and results of 
the various tools involved in the build. These build logs are a valuable data source 
for developers and researchers to inspect test results, to check the duration of build steps 
and to understand the cause of a build failure. However, build logs are very verbose, 
at best semi-structured and their structure differs highly between projects. 
This makes it hard to process and analyze them. 

In this thesis, we evaluate and compare three different techniques that aim to retrieve 
specified log parts (chunks) from a build log, namely program synthesis by example, 
textual similarity and search keywords. We conduct an empirical study by comparing 
these techniques on our manually labeled LogChunks data set of 797 Travis CI build logs 
from a broad range of 80 projects. Our findings show that none of the three techniques 
in general outperforms the others. We discuss under which circumstances each technique 
performs best and provide a recommendation on when developers or researchers should use which technique.

