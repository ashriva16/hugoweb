---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-01-01
type: landing

design:
  spacing: '6rem'

sections:
  - block: hero-banner
    id: hero
    content:
      eyebrow: ''
      title: 'Ankit Shrivastava'
      lead: ''
      background: uq
      cta:
        text: 'Contact'
        url: 'mailto:ankit.shrivastava@gmail.com'

  - block: resume-biography-3
    id: bio
    content:
      username: admin
      text: |
        Hi there! 👋 I'm an Applied Scientist passionate about advancing and applying methods in **scientific machine learning** and **scientific computing** to address complex, real-world problems across diverse engineering domains.

        My work applies principles from **deep learning, signal and image processing, uncertainty quantification, optimization, and numerical modeling** to develop robust, high-impact solutions.

        I’ve collaborated with multidisciplinary teams on challenges in power grid resilience, semiconductor manufacturing, structural engineering, computational fluid dynamics, and medical imaging.
        I also have working experience with **natural language processing**, **computer vision**, and **high-performance computing**.

        Beyond project work, I serve as a peer **reviewer** for journals in applied mathematics, mechanics, uncertainty quantification, and computational science, contributing to the advancement of the field.

          <div class="stats-row container my-5 py-3">
            <div>
              <b>8+</b>
              <span>Years of Experience</span>
            </div>
            <div>
              <b>15+</b>
              <span>Research Projects</span>
            </div>
            <div>
              <b>7+</b>
              <span>Peer-Reviewed Publications</span>
            </div>
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

  # - block: markdown
  #   id: focus-areas
  #   content:
  #     title: 'Focus Areas'
  #     text: |
  #       - **Scientific ML & UQ:** Physics-informed learning, multimodal/multifidelity modeling, active learning, and Bayesian optimization.
  #       - **Computational Modeling:** Numerical methods for PDEs, multiscale simulations, and high-performance computing (CUDA, OpenMP, MPI).
  #       - **Applications:** Power-grid resilience, semiconductor manufacturing, structural engineering, CFD, and medical imaging.
  #   design:
  #     columns: '1'

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
