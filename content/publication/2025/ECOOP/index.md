---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Contract Usage and Evolution in Android Mobile Applications"
authors: [David Ferreira, alexandra-mendes, jff, carolina-carreira]
date: 2025-02-28
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2025-02-28T22:42:47Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In *39th European Conference on Object-Oriented Programming (ECOOP 2025), 2025*"
publication_short: "In *ECOOP 2025*"
publication_ranking: "<b>CORE A conference</b>"
# Awards
#award_text: "**ACM SIGSOFT Distinguished Paper award**"
#award_text: "**Awarded:** _Artifact Evaluation Award (Available, Reusable)_. **Most cited paper from ICSE 2020 ([Google Scholar Metrics](https://scholar.google.com/citations?hl=en&view_op=list_hcore&venue=vtDF2hFAQ-cJ.2023&vq=eng_softwaresystems))**"

abstract: "Contracts and assertions are effective methods to enhance software quality by enforcing preconditions, postconditions, and invariants. Previous research has demonstrated the value of contracts in traditional software development. However, the adoption and impact of contracts in the context of mobile app development, particularly of Android apps, remain unexplored.


To address this, we present the first large-scale empirical study on the use of contracts in Android apps, written in Java or Kotlin. We consider contract elements divided into five categories: conditional runtime exceptions, APIs, annotations, assertions, and other. We analyzed 2,390 Android apps from the F-Droid repository and processed more than 52,977 KLOC to determine 1) how and to what extent contracts are used, 2) which language features are used to denote contracts, 3) how contract usage evolves from the first to the last version, and 4) whether contracts are used safely in the context of program evolution and inheritance. 
Our findings include: 1) although most apps do not specify contracts, annotation-based approaches are the most popular; 2) apps that use contracts continue to use them in later versions, but the number of methods increases at a higher rate than the number of contracts; and 3) there are potentially unsafe specification changes when apps evolve and in subtyping relationships, which indicates a lack of specification stability. Finally, we present a qualitative study that gathers challenges faced by practitioners when using contracts and that validates our recommendations."

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

url_pdf: publication/2025/ECOOP/ecoop25-contracts-android.pdf 
url_code: https://github.com/sr-lab/contracts-android
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
    - /publications/2025/ECOOP
---
