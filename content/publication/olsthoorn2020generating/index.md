---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Generating Highly-structured Input Data by Combining Search-based Testing and Grammar-based Fuzzing"
authors:
  - Mitchell Olsthoorn
  - Arie van Deursen
  - Annibale Panichella

# The date it was published
date: 2020-12-21
doi: "10.1145/3324884.3418930"

# Schedule page publish date (NOT publication's date).
# Use the paper notification date
publishDate: 2020-07-03

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 35th IEEE/ACM International Conference on Automated Software Engineering"
publication_short: "ASE'20"

abstract: "Software testing is an important and time-consuming task that is often done manually. In the last decades, researchers have come up with techniques to generate input data (e.g., fuzzing) and automate the process of generating test cases (e.g., search-based testing). However, these techniques are known to have their own limitations: search-based testing does not generate highly-structured data; grammar-based fuzzing does not generate test case structures. To address these limitations, we combine these two techniques. By applying grammar-based mutations to the input data gathered by the search-based testing algorithm, it allows us to co-evolve both aspects of test case generation. We evaluate our approach, called G-EvoSuite, by performing an empirical study on 20 Java classes from the three most popular JSON parsers across multiple search budgets. Our results show that the proposed approach on average improves branch coverage for JSON related classes by 15 % (with a maximum increase of 50 %) without negatively impacting other classes."

# Summary. An optional shortened abstract.
summary: ""

tags:
  - Fuzzing
  - Test Case Generation
  - Search-based Software Engineering
  - Many-objective Optimization
  - EvoSuite
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://research.tudelft.nl/files/82771549/ASE_2020_Pure.pdf"
url_code: "https://doi.org/10.5281/zenodo.4001744"
url_dataset: "https://doi.org/10.5281/zenodo.4001744"
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [ubri]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
