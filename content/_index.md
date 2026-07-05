---
title: Jun-Sik Yoo
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: ""
      username: admin
    design:
      background:
        color: white
      spacing:
        padding: ["40px", "0", "40px", "0"]

  - block: markdown
    id: research
    content:
      title: Research
      subtitle: ""
      text: |-
        My work focuses on high-dimensional computational systems in physics and AI. I develop numerical, statistical, and machine-learning methods for extracting reliable structure from large-scale scientific computations.

        ### Lattice QCD and Precision Physics

        I work on first-principles calculations of hadronic matrix elements relevant to precision Standard Model tests and searches for physics beyond the Standard Model. My research includes proton decay, electroweak radiative corrections, nucleon charges and form factors, electric dipole moments, and inclusive scattering.

        ### High-Performance Scientific Computing

        I develop and optimize lattice-field-theory software for modern HPC architectures, including GPU and many-core systems. My work includes solver optimization, deflation, data pipelines, production workflows, and performance analysis on large-scale computing platforms.

        ### Machine Learning and Representation Geometry

        I study the internal geometry of neural network computations, including transformer layer updates, quantization-induced changes, numerical manifolds, predictive visual representations, and scientific machine-learning methods for field theory.
    design:
      columns: "1"
      spacing:
        padding: ["30px", "0", "30px", "0"]

  - block: collection
    id: publications
    content:
      title: Selected Publications
      subtitle: ""
      text: ""
      count: 6
      filters:
        folders:
          - publication
        featured_only: true
      sort_by: "Date"
      sort_ascending: false
    design:
      view: citation
      columns: "1"

  - block: collection
    id: projects
    content:
      title: Selected Projects
      subtitle: ""
      text: ""
      count: 6
      filters:
        folders:
          - project
      sort_by: "Date"
      sort_ascending: false
    design:
      view: card
      columns: "2"

  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ""
      text: |-
        For research collaboration, speaking invitations, or questions about my work, please contact me by email.

        **Email:** YOUR_EMAIL@lanl.gov  
        **GitHub:** [YOUR_GITHUB_USERNAME](https://github.com/YOUR_GITHUB_USERNAME)  
        **Google Scholar:** [Profile](https://scholar.google.com/citations?user=YOUR_ID)
    design:
      columns: "1"
      spacing:
        padding: ["30px", "0", "60px", "0"]
---
