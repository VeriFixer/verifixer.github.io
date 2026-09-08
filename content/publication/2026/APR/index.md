---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DafnyFix: Single-Transformation Automated Repair in Dafny"
authors: [Isabel Amaral, Álvaro Silva, João F. Ferreira, Alexandra Mendes]
date: 2026-09-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2026-09-01T20:41:47Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Automated Program Repair, 2026*, Co-located with *41st IEEE/ACM International Conference on Automated Software Engineering (ASE 2026)*"
publication_short: "In *APR 2026*"
# publication_ranking: "<b>CORE A* conference</b>"
# Awards
#award_text: "**ACM SIGSOFT Distinguished Paper award**"
#award_text: "**Awarded:** _Artifact Evaluation Award (Available, Reusable)_. **Most cited paper from ICSE 2020 ([Google Scholar Metrics](https://scholar.google.com/citations?hl=en&view_op=list_hcore&venue=vtDF2hFAQ-cJ.2023&vq=eng_softwaresystems))**"

abstract: "Formal verification using verification-aware languages, like Dafny, ensures a program’s conformance to its specification. Assuming a correct and complete specification, a verification failure may indicate an implementation fault that the developer must identify and correct. However, debugging verification failures is particularly challenging, as verification diagnostics do not directly hint at the implementation changes required for verification to succeed. Automated Program Repair has long been explored for traditional programming languages to reduce manual debugging effort, yet it remains largely underexplored in verification-aware contexts.
<br/>
We propose *DafnyFix*, a repair framework for Dafny that searches over a space of single-transformation candidate patches generated through three complementary heuristics: existing mutation testing operators, newly introduced repair-oriented mutation operators, and state-guided repair templates inspired by AutoFix. We evaluate DafnyFix’s effectiveness on a dataset of implementation faults in LLM-generated Dafny programs curated from the dafny-synthesis benchmark, and successfully repair 62.5% of the faults, showing that small deterministic transformations can repair a substantial number of faulty LLM-generated implementations. Our results further show that the proposed repair heuristics are complementary, targeting different categories of implementation faults. Additionally, we identify six fault patterns of LLM-generated programs in our dataset that can be corrected by small program transformations."
# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: publication/2026/APR/APR26-DafnyFix.pdf
#url_code: https://github.com/sr-lab/contracts-android
url_dataset: 
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

aliases:
    - /publications/2026/APR
---
