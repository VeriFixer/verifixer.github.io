---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        VeriFixer Project
      image:
        filename: VeriFixer-Logo-300dpi.png
      text: |
        We are building tools and methods that support users in repairing flaws in verification-aware programming languages (e.g., Dafny and Verus). By reducing flaws, errors, and vulnerabilities, verification-aware programming languages prove particularly valuable in critical sectors like healthcare, aerospace, and the financial sector. 
  
        {{% cta cta_link="./about/" cta_text="Learn more" %}}
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: collection
    content:
      title: Featured Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        #publication_type: 'article'
        featured_only: true
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
