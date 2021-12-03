---
title: "SERG talk"

# event: 
# event_url: 

location: Online

summary: ""
# abstract: ""

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: "2021-05-12T11:00:00Z"
date_end: "2021-05-12T12:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate:

authors: [Amir Mir,]
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


**Type4Py: Deep Similarity Learning-Based Type Inference for Python (Amir Mir)**

Dynamic languages, such as Python and Javascript, trade static typing for developer flexibility. While this allegedly enables greater productivity, lack of static typing can cause runtime exceptions, type inconsistencies, and is a major factor for weak IDE support. To alleviate these issues, PEP 484 introduced optional type annotations for Python. As retrofitting types to existing codebases is error-prone and laborious, learning-based approaches have been proposed to enable automatic type annotations based on existing, partially annotated codebases. However, the prediction of rare and user-defined types is still challenging. In this paper, we present Type4Py, a deep similarity learning-based type inference model for Python. We design a hierarchical neural network model that learns to discriminate between types of the same kind and dissimilar types in a high-dimensional space, which results in clusters of types. Nearest neighbor search suggests likely type signatures of given Python functions. The types visible to analyzed modules are surfaced using lightweight dependency analysis. The results of quantitative and qualitative evaluation indicate that Type4Py significantly outperforms state-of-the-art approaches at the type prediction task. Considering the Top-1 prediction, Type4Py obtains 19.33% and 13.49% higher precision than Typilus and TypeWriter, respectively, while utilizing a much bigger vocabulary.

Preprint: [https://arxiv.org/abs/2101.04470](https://arxiv.org/abs/2101.04470)

