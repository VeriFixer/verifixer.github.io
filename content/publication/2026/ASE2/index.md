---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DSpec2Test: Specification-Driven Test Generation in Dafny"
authors: [Sofia Vieira Pinto, Álvaro Silva, João Pascoal Faria, Alexandra Mendes]
date: 2026-08-24
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2026-08-24T20:42:47Z

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
award_text: "**Awarded:** _Artifact Evaluation (Available, Functional, and Reusable)_. **Most cited paper from ICSE 2020 ([Google Scholar Metrics](https://scholar.google.com/citations?hl=en&view_op=list_hcore&venue=vtDF2hFAQ-cJ.2023&vq=eng_softwaresystems))**"

abstract: "Verification-aware languages, such as Dafny, integrate logical constructs into code and enable automatic verification of program correctness. However, tests remain helpful in scenarios that verification alone does not address (e.g., to support test-driven development). Existing Dafny test generation tools are implementation-based,
limiting their applicability in this context.
<br/>
We present DSpec2Test, a specification-driven test generation tool for Dafny that automatically derives tests from formal specifications, without considering implementation details. Our tool extends Dafny’s generate-tests command with a new black-box mode based on Disjunctive Normal Form (DNF) equivalence class partitioning and optional Boundary Value Analysis (BVA). DSpec2Test relies on the Z3 SMT solver to synthesize inputs and expected outputs that meet the specification-derived constraints.
<br/>
We evaluate DSpec2Test on programs from DafnyBench mutated using MutDafny and compare it against Dafny’s existing implementation-driven Block mode. DSpec2Test achieves a 93.9% mutation kill rate on a dataset of 131 mutants, outperforming Block’s 82.4%, and uniquely killing 17 mutants. These results suggest that specification-driven testing is an effective and complementary approach for testing Dafny programs.
<br/>Demo: https://youtu.be/mK1EeJfinRQ
<br/>Code: https://github.com/VeriFixer/DSpec2Test
<br/>Prebuilt docker image: https://doi.org/10.5281/zenodo.21191158"
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

url_pdf: publication/2026/ASE2/ase26-dspec2test.pdf
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
    - /publications/2026/ase2
---
