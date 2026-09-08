---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MutDafny: A Mutation-Based Approach to Assess Dafny Specifications"
authors: [Isabel Amaral, Alexandra Mendes, José Campos]
date: 2026-04-17
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2026-04-20T22:41:47Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*48th IEEE/ACM International Conference on Software Engineering (ICSE 2026)*"
publication_short: "In *ICSE 2026*"
publication_ranking: "<b>CORE A* conference</b>"
# Awards
#award_text: "**ACM SIGSOFT Distinguished Paper award**"
#award_text: "**Awarded:** _Artifact Evaluation Award (Available, Reusable)_. **Most cited paper from ICSE 2020 ([Google Scholar Metrics](https://scholar.google.com/citations?hl=en&view_op=list_hcore&venue=vtDF2hFAQ-cJ.2023&vq=eng_softwaresystems))**"

abstract: "In verification-aware languages, such as Dafny, despite their critical role, specifications are as prone to error as implementations. Flaws in specifications can result in formally verified programs that deviate from the intended behavior. In this paper, we explore the use of mutation testing to reveal weaknesses in formal specifications written in Dafny.
We present MutDafny, a tool that increases the reliability of Dafny specifications by automatically signaling potential weaknesses. Using a mutation testing approach, we introduce faults (mutations) into the code and rely on formal specifications for detecting them. If a program with a mutant verifies, this may indicate a weakness in the specification. We extensively analyze mutation operators from popular tools, identifying the ones applicable to Dafny. In addition, we synthesize new operators tailored for the language from bugfix commits in publicly available Dafny projects on GitHub. Drawing from both, we equipped our tool with a total of 40 mutation operators. We evaluate MutDafny's effectiveness and efficiency on a dataset of 794 real-world Dafny programs, and manually analyze a subset of the resulting undetected mutants, identifying five weak real-world specifications (on average, one at every 241 lines of code) that would benefit from strengthening."
# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: publication/2026/icse/icse26-mutdafny.pdf
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
    - /publications/2026/icse
---
