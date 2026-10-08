---
title: "Publications"
type: landing

sections:
  - block: markdown
    content:
      title: Publications
      text: |
        Our recent publications and preprints.

        Publication entries are managed in the `content/publication/` folder.

  - block: collection
    content:
      title: Selected Publications
      text: ""
      filters:
        folders:
          - publication
      sort_by: "date"
      sort_ascending: false
      count: 12
    design:
      view: citation

  - block: cta-card
    content:
      title: Full Publication List
      text: |
        Explore all articles, preprints, and research outputs from the BEAR group.
      button:
        text: Browse Publications
        url: /publication/
    design:
      card:
        css_class: "bg-primary-300"
        css_style: ""
---