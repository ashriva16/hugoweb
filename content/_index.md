---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-01-01
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    id: bio
    content:
      username: admin
      text: |
        Applied scientist advancing **scientific machine learning** and **scientific computing** to solve complex engineering problems. I build physics-informed and multimodal ML models, use Bayesian optimization for faster discovery, and deploy robust numerical methods for high-impact applications across power systems, semiconductor manufacturing, structural mechanics, CFD, and medical imaging.
      button:
        text: Download CV
        url: /assets/pdf/workfolio.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      avatar:
        size: medium
        shape: circle

  - block: markdown
    id: focus-areas
    content:
      title: 'Focus Areas'
      text: |
        - **Scientific ML & UQ:** Physics-informed learning, multimodal/multifidelity modeling, active learning, and Bayesian optimization.
        - **Computational Modeling:** Numerical methods for PDEs, multiscale simulations, and high-performance computing (CUDA, OpenMP, MPI).
        - **Applications:** Power-grid resilience, semiconductor manufacturing, structural engineering, CFD, and medical imaging.
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: Projects
      text: 'Selected research and engineering projects.'
      count: 3
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false

  - block: collection
    id: papers
    content:
      title: Papers
      text: 'Peer-reviewed articles, preprints, and conference papers.'
      count: 2
      filters:
        folders:
          - publications
    design:
      view: article-grid
      show_date: true
      show_read_time: false
      show_read_more: true

  - block: collection
    id: talks
    content:
      title: Talks
      text: 'Invited and contributed presentations.'
      count: 3
      filters:
        folders:
          - events
    design:
      view: date-title-summary
      show_date: true
      show_read_more: false

  - block: collection
    id: news
    content:
      title: News
      text: 'Highlights and recent updates.'
      page_type: blog
      count: 5
      filters:
        exclude_featured: false
    design:
      view: date-title-summary
      show_date: true
      show_read_more: false
---
