---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ProofPulse: Interactive Proof Coverage Analysis for Dafny"
authors: [Álvaro Silva, Rúben Martins, Alexandra Mendes]
date: 2026-08-24
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2026-08-24T20:41:47Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*41st IEEE/ACM International Conference on Automated Software Engineering (ASE 2026)*"
publication_short: "In *ASE 2026*"
publication_ranking: "<b>CORE A* conference</b>"
# Awards
#award_text: "**ACM SIGSOFT Distinguished Paper award**"
#award_text: "**Awarded:** _Artifact Evaluation Award (Available, Reusable)_. **Most cited paper from ICSE 2020 ([Google Scholar Metrics](https://scholar.google.com/citations?hl=en&view_op=list_hcore&venue=vtDF2hFAQ-cJ.2023&vq=eng_softwaresystems))**"

abstract: "Deductive verification ensures that an implementation satisfies its specification, but successful verification does not guarantee the quality of the specification. As such, weak specifications and redundant invariants may create overconfidence in *verified* code.
<br/>
We present ProofPulse, a tool for Dafny that diagnoses specification quality using a three-valued proof coverage model. By analyzing proof dependencies, ProofPulse distinguishes between elements that contribute to specification intent, those used only for auxiliary checks, and those irrelevant to any proof obligation. 
<br/>
Evaluated against an oracle of 252 programs from the dafny-synthesis benchmark, ProofPulse provides a high-precision signal for specification weaknesses, particularly unnecessary preconditions and vacuous proofs. With unsat-core minimization, ProofPulse achieves perfect precision for precondition classification and reduces false positives across all evaluated categories. These results show that proof coverage is a practical complement to verification. Although it cannot fully capture semantic intent, it can reveal weak proof coupling in programs that otherwise appear fully verified. 
<br/>
Just as a pulse check distinguishes vitality from the mere absence of symptoms, ProofPulse exposes weaknesses in proofs that technically verify successfully but still suffer from inadequate or redundant code and specifications.
<br/>Demo: https://www.youtube.com/watch?v=8pO3NAodjoQ
<br/>Code: https://github.com/VeriFixer/ProofPulse
<br/>Prebuilt Docker image: https://doi.org/10.5281/zenodo.21174686"
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

url_pdf: publication/2026/ASE1/ASE26-ProofPulse.pdf
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
    - /publications/2026/ASE1
---
