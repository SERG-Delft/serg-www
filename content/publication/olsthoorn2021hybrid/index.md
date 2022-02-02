---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Hybrid Multi-level Crossover for Unit Test Case Generation"
authors:
  - Mitchell Olsthoorn
  - Pouria Derakhshanfar
  - Annibale Panichella

# The date it was published
date: 2021-07-01
doi: "10.1007/978-3-030-88106-1_6"

# Schedule page publish date (NOT publication's date).
# Use the paper notification date
publishDate: 2021-06-30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "13th International Symposium on Search-Based Software Engineering"
publication_short: "SSBSE'21"

abstract: "State-of-the-art search-based approaches for test case generation work at test case level, where tests are represented as sequences of statements. These approaches make use of genetic operators (i.e., mutation and crossover) that create test variants by adding, altering, and removing statements from existing tests. While this encoding schema has been shown to be very effective for many-objective test case generation, the standard crossover operator (single-point) only alters the structure of the test cases but not the input data. In this paper, we argue that changing both the test case structure and the input data is necessary to increase the genetic variation and improve the search process. Hence, we propose a hybrid multi-level crossover (HMX) operator that combines the traditional test-level crossover with data-level recombination. The former evolves and alters the test case structures, while the latter evolves the input data using numeric and string-based recombinational operators. We evaluate our new crossover operator by performing an empirical study on more than 100 classes selected from open-source Java libraries for numerical operations and string manipulation. We compare HMX with the single-point crossover that is used in EvoSuite w.r.t structural coverage and fault detection capability. Our results show that HMX achieves a statistically significant increase in 30% of the classes up to 19% in structural coverage compared to the single-point crossover. Moreover, the fault detection capability improved up to 12% measured using strong mutation score."

# Summary. An optional shortened abstract.
summary: ""

tags:
  - Test Case Generation
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

url_pdf: https://research.tudelft.nl/en/publications/hybrid-multi-level-crossover-for-unit-test-case-generation
url_code: https://github.com/mitchellolsthoorn/SSBSE-Research-2021-crossover-replication
url_dataset: https://github.com/mitchellolsthoorn/SSBSE-Research-2021-crossover-replication
url_poster:
url_project:
url_slides: https://www.slideshare.net/PouriaDerakhshanfar/hybrid-multilevel-crossover-for-unit-test-case-generation-ssbse-2021-250420326
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
