---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Improving Debugging in Verification-Aware Languages Through Automated Fault Localization: A Case Study in Dafny"
authors: [Álvaro Silva, Isabel Amaral, João Pascoal Faria, Alexandra Mendes]
date: 2026-08-23
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2026-08-23T20:50:47Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*37th IEEE International Symposium on Software Reliability Engineering (ISSRE 2026)*"
publication_short: "In *ISSRE 2026*"
publication_ranking: "<b>CORE A conference</b>"
# Awards
#award_text: "**ACM SIGSOFT Distinguished Paper award**"
#award_text: "**Awarded:** _Artifact Evaluation Award (Available, Reusable)_. **Most cited paper from ICSE 2020 ([Google Scholar Metrics](https://scholar.google.com/citations?hl=en&view_op=list_hcore&venue=vtDF2hFAQ-cJ.2023&vq=eng_softwaresystems))**"

abstract: "Verification-aware languages, like Dafny, integrate formal specifications directly into source code to enable static correctness checks. However, when verification fails, the feedback provided is often limited to the specific condition of the error, such as a violated postcondition, rather than the root cause of the fault. For example, in Dafny, while its counterexample features provide concrete execution traces, they typically expose a single failing path per assertion failure, leaving the developer to manually inspect the entire trace to locate the error.
<br/>
This paper investigates automated fault localization for verification-aware languages by comparing two paradigms: state-based and counterexample-based localization. Our state-based localization strategy replicates the “snapshot” methodology of AutoFix by inferring invariants and predicates to identify suspicious program states. The counterexample-based strategy consists of a family of techniques that progressively enrich the use of verifier output: from raw counterexample extraction, to structured single-trace ranking, and to multi-trace aggregation.
<br/>
To validate these methods, we present an evaluation framework that uses MutDafny to generate a diverse mutant dataset from DafnyBench and measures localization effectiveness using the EXAM score. Our results show that counterexample-based approaches substantially outperform state-based localization in this setting. Structured ranking over a single trace yields the largest improvement over raw counterexample output, while multi-trace aggregation provides additional gains in robustness and debugging utility by increasing coverage and reducing path bias introduced by the solver. These findings demonstrate that effective fault localization in verification-aware languages depends both on using counterexample information and on how that information is structured and diversified."
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

url_pdf: publication/2026/issre/issre26-counterexamples.pdf
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
    - /publications/2026/issre
---
