---
# Leave the homepage title empty to use the site title
title: Qianrong-Guo
date: 2023-06-01
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Development Intern
          company: WuXi Biologics
          company_url: 'https://www.wuxibiologics.com/'
          company_logo: wuxi
          location: Shanghai
          date_start: '2022-09-01'
          date_end: '2022-12-01'
          description: |2-
              Data Technology and Analysis Department - Data Technology AI Team

              Responsibilities:

              * Graph-based and language model development for Protein-protein Interaction (PPI) prediction and antibiotic discovery
        - title: Research Assistant
          company: The University of Edinburgh
          company_url: 'https://www.ed.ac.uk/'
          company_logo: uoe
          location: Edinburgh
          date_start: '2022-04-01'
          date_end: '2022-08-01'
          description: |2-
              Responsibilities:

              * Conducted research on deep learning techniques in phenotypic drug discovery against glioblastoma cells.
              
              * Developed and optimized a graph neural network for feature extraction, combining information from RDkit and features extracted from a large pre-trained language model (ChemBERTa).
              
              * Improved model architecture and evaluation metrics, particularly for handling imbalanced data.
          tags:
            - Drug Discovery
            - Graph Neural Networks 
            - Natural Language Processing
        - title: Research Assistant
          company: China University of Geosciences
          company_url: 'https://en.cug.edu.cn/'
          company_logo: cug
          location: Wuhan
          date_start: '2020-04-01'
          date_end: '2021-06-01'
          description: |2-
              Effects of red phosphorus on metabolism of microorganisms. Supervised by Dr. Liang Feng.

              Responsibilities:

              * Investigated the effects of red phosphorus on the metabolism of microorganisms.
              
              * Utilized Gradient Boosting Tree and Random Forest algorithms to predict the optimal concentration of different types of red phosphorus using transcriptomics data and visible light wavelength.
              
              * Conducted data cleaning, analysis, and visualization using Python.
        - title: Research Assistant
          company: China University of Geosciences
          company_url: 'https://en.cug.edu.cn/'
          company_logo: cug
          location: Wuhan
          date_start: '2019-03-01'
          date_end: '2019-07-01'
          description: |2-
              Neosinocalamus growth prediction using image data

              Responsibilities:

              * Analyzed the growth and development of Neosinocalamus affinis using image data.
              
              * Collected and processed leaves from Neosinocalamus affinis.
              
              * Applied K-means clustering to analyze the correlation between the size, number, and positions of phytoliths and the growth of Neosinocalamus affinis.
              
              * Identified the connection between the cells' structure and components at the molecular level and the growth of Neosinocalamus affinis.
    design:
      columns: '2'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: q.guo22@imperial.ac.uk
      address:
        street: 86 Wood Ln
        city: London
        postcode: 'W12 0BZ'
        country: United Kindom
      directions: U301/05, 3rd Floor, Building E - Sir Michael Uren, White City Campus
      # Automatically link email and phone or display as text?
    design:
      columns: '2'
---
---
